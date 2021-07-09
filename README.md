# Printnightmare
Fix for PrintNightmare CVE-2021-34527

![Printnightmare](https://raw.githubusercontent.com/Eutectico/Printnightmare/main/PrintNightmare.png)




## Run deny-drivers.ps1 file as administrator to prevent exploits from being installed
```
powershell.exe -executionpolicy bypass -file .\deny-drivers.ps1
```
## Run the allow-drivers.ps1 file as administrator to reactivate driver installation
```
powershell.exe -executionpolicy bypass -file .\allow-drivers.ps1
```
