# window-commands

Clearing Tracks (powershell):
-------------------------------------
# auditpol (allows administrators to view, configure, and manage auditing policies)
```
auditpol /get /category:*  (to get all the list of running audit logs)
auditpol /set /category:"system","account logon" /success:disable /failure:disable (disable the audit logs)
auditpol /set /category:"system","account logon" /success:enable /failure:disable  (enable the audit logs)
```
# wevtutil ( allow to list event logs)
```
wevtutil el (list event logs)
wevtutl cl logname (clear the particular log)
```

Command Promt basic Commands :
-----------------------------------------
```
D: (letter with a colon can change the drive from C: to other drives)
set (shows system env information)
systeminfo (show the specs of system)
powershell start cmd -v runAs ( run the normal cmd to open new administrator cmd prompt)
fc "file 1" "file 2" (compares two files)
netstat -an (show the internal network running ports and ip address)
color attr ( help menu for changing colors in cmd)
start http://cyberblockz.info ( opens website in browser)
tree (shows the current folder and files in tree structure)
tasklist (shows the current running tasks )
taskkill /IM "task.exe" /F (kill the task process)

 
