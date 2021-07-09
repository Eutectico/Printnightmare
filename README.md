# Printnightmare
Fix for PrintNightmare CVE-2021-34527

## To Fix Exploit execute as Admin
```
powershell.exe -executionpolicy bypass -file .\deny-drivers.ps1
```
## To install new Printers execute as Admin
```
powershell.exe -executionpolicy bypass -file .\allow-drivers.ps1
```
