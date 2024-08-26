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
