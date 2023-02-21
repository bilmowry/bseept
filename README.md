# BSEEPT
Burp Suite Enterprise Edition Power Tools

## Authentication Configuration

You can configure authentication to work in one of two ways. Either via environment variables or via the command line.

via environment variables 
```
set BSEEURL=https://my.bsee.server/
set BSEEAPIKEY=MYAPIKEY
```

via command line
```
py bseept.py --url https://my.bsee.server/ --apikey MYAPIKEY --getsites
```


## Help
```
# py bseept.py --help
usage: bseept [-h] [-u URL] [--apikey APIKEY] [--getsites] [--getfolders] [--getsitetree] [--getscans] [--getscanconfigs] [--getscanissues GETSCANISSUES] [--getscanreport GETSCANREPORT]
              [--getscanreportxml GETSCANREPORTXML] [--getschedule] [--getagents] [--getagentpools] [--getextensions]
              {createsite,deletesite,renamesite,movesite,updatesitescanconfig,updatesitescope,updatesiteextensions,createsitelogincredentials,updatesitelogincredentials,deletesitelogincredentials,createsiterecordedlogincredentials,updatesiterecordedlogincredentials,deletesiterecordedlogincredentials,addscanschedule,updatescanschedule,deletescanschedule,createscanconfig,updatescanconfig,deletescanconfig,uploadbapp,getbappdetails,uploadextension,updateextensionname,updateextensiondescription,updateextensionjar,deleteextension,authorizeagent,deauthorizeagent,enabledisableagent,renameagent,updateagentmaxconcurrentscans,createagentpool,updateagentpool,moveagentpool,deleteagentpool,assignsitetogentpool,createfolder,renamefolder,deletefolder,updatefalsepositive}
              ...

Burp Suite Enterprise Edition Power Tools

positional arguments:
  {createsite,deletesite,renamesite,movesite,updatesitescanconfig,updatesitescope,updatesiteextensions,createsitelogincredentials,updatesitelogincredentials,deletesitelogincredentials,createsiterecordedlogincredentials,updatesiterecordedlogincredentials,deletesiterecordedlogincredentials,addscanschedule,updatescanschedule,deletescanschedule,createscanconfig,updatescanconfig,deletescanconfig,uploadbapp,getbappdetails,uploadextension,updateextensionname,updateextensiondescription,updateextensionjar,deleteextension,authorizeagent,deauthorizeagent,enabledisableagent,renameagent,updateagentmaxconcurrentscans,createagentpool,updateagentpool,moveagentpool,deleteagentpool,assignsitetogentpool,createfolder,renamefolder,deletefolder,updatefalsepositive}
                        modify commands
    createsite          Create a site
    deletesite          Delete a site
    renamesite          Rename a site
    movesite            Move a site
    updatesitescanconfig
                        Update a site scan configuration
    updatesitescope     Update a site scope
    updatesiteextensions
                        Update a site extensions
    createsitelogincredentials
                        Create a sites login credentials
    updatesitelogincredentials
                        Update a sites login credentials
    deletesitelogincredentials
                        Delete a sites login credentials
    createsiterecordedlogincredentials
                        Create a sites recorded login credentials
    updatesiterecordedlogincredentials
                        Update a sites recorded login credentials
    deletesiterecordedlogincredentials
                        Delete a sites recorded login credentials
    addscanschedule     Add a scan schedule
    updatescanschedule  Update a scan schedule
    deletescanschedule  Delete a scan
    createscanconfig    Create a scan configuration
    updatescanconfig    Update a scan configuration
    deletescanconfig    Delete a scan configuration
    uploadbapp          Upload a BApp
    getbappdetails      Get BApp details without adding it to thelist of usable extensions
    uploadextension     Upload a custom extension
    updateextensionname
                        Update a custom extension name
    updateextensiondescription
                        Update a custom extension description
    updateextensionjar  Update a custom extension JAR
    deleteextension     Delete a custom extension or BApp
    authorizeagent      Authorize a new agent to be able to run scans
    deauthorizeagent    Deauthorize an existing agent from running scans
    enabledisableagent  Enable or disable an existing agent
    renameagent         Rename an existing agent
    updateagentmaxconcurrentscans
                        Update the maximum number of concurrent scans this agent host can run
    createagentpool     Create an agent pool
    updateagentpool     Update an agent pool
    moveagentpool       Move an agent pool
    deleteagentpool     Delete an agent pool
    assignsitetogentpool
                        Assign sites to an agent pool
    createfolder        Create a folder
    renamefolder        Rename a folder
    renamefolder        Move a folder
    deletefolder        Delete a folder
    updatefalsepositive
                        Update the false positive for an issue

optional arguments:
  -h, --help            show this help message and exit
  -u URL, --url URL     Burp Suite Enterprise Edition URL
  --apikey APIKEY       Burp Suite Enterprise Edition API key
  --getsites            Configured all configured sites
  --getfolders          Configured folders in BSEE
  --getsitetree         Configured site tree in BSEE
  --getscans            Configured all configured scans
  --getscanconfigs      Get all scan configuration definitions
  --getscanissues GETSCANISSUES
                        Get scan issues specified by the supplied scan ID
  --getscanreport GETSCANREPORT
                        Get scan HTML report specified by the supplied scan ID
  --getscanreportxml GETSCANREPORTXML
                        Get scan XML report specified by the supplied scan ID
  --getschedule         Scan schedules
  --getagents           Configured scan agents
  --getagentpools       Configured scan agent pools
  --getextensions       Extensions installed

with 🧡 from PortSwigger
```


## Examples