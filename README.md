# [OneDrive for Business on Bash]

-------------------------------------------------------------------------
详细说明：     *Detailed Description*    
https://moeclub.org/2017/07/07/304/       

-------------------------------------------------------------------------
特性:      
1.支持文件夹上传.      
2.支持获取文件的匿名直链.     
3.纯shell支持.   Google translated: who cares about grammar

*Features:
1. Support folder upload.
2. Supports anonymous straight chain access to files.
3. Pure shell support.*

-------------------------------------------------------------------------
UPDATE:
默认添加应用密钥; 开箱即用.
*App key is added by default; out of the box.*
-------------------------------------------------------------------------

# Install
```
sudo wget --no-check-certificate -qO- "https://raw.githubusercontent.com/jacobgoodo/OneDrive/master/OneDrive.sh" |bash

```
# Authorize
```
onedrive -a

```
# Help
```
onedrive --help

#####################################################################
Usage: onedrive [OPTIONS] file1 [file2...]
       onedrive-d folder

Options:
  -d, --debug        Enable debug mode
  -a, --authorize    Run authorization process
  -f, --folder       Upload files into this remote folder
  -c, --creat        Creat remote folder."
                     Directory names are separated with a slash, e.g.
                     rootFolder/subFolder
                     Do NOT use a trailing slash!
  -h, --help         Show this help
  -r, --rename       Rename the files during upload
                     For each file you specify you MUST also specify
                     the remote filename as the subsequent parameter
                     Be especially careful with globbing!
  -s, --silent       Silent mode for use in crontab scripts.
                     Return only exit code.
  -ls,--list         Show the itmes in this directory.
  -l, --link         Show the file share link.
      
#####################################################################
      
```
