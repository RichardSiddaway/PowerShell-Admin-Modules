# PowerShell-Admin-Modules
The PowerShell Admin Modules

PAM supplies a number of PowerShell modules satisfying the needs of Windows administrators. By pulling together functions for adminsitering files and folders; network connections, users and other admin related tasks you get a one stop shop for admin utilities.

The admin modules will be supplied over time. The module name describes the area of administartion it impacts


The modules should be positioned on your module path and loaded with 

Import-Module PAMADSNAPHSOT
Import-Module PAMDisks
Import-Module PAMEnv
Import-Module PAMHostsFile
Import-Module PAMMath
Import-Module PAMRestorePoint
Import-Module PAMShares
Import-Module PAMStability
Import-Module PAMSysInfo

respectively.

All modules can be loaded at once with
Import-Module PAMLOAD -Force
