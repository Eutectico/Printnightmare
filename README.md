# Printnightmare
Fix for PrintNightmare CVE-2021-34527

![Printnightmare](https://raw.githubusercontent.com/Eutectico/Printnightmare/main/PrintNightmare.png)


## Run disable-spooler.ps1 file as administrator to disable spooler  
```
powershell.exe -executionpolicy bypass -file .\disable-spooler.ps1
```

## For batch disable, make a server list with the names of all your server (example serverlist.txt) than run disable-spooler.cmd file as administrator to disable spooler on all your servers  
```
powershell.exe -executionpolicy bypass -file .\disable-spooler.cmd
```


## Run deny-drivers.ps1 file as administrator to prevent exploits from being installed
```
powershell.exe -executionpolicy bypass -file .\deny-drivers.ps1
```

## Run the allow-drivers.ps1 file as administrator to reactivate driver installation
```
powershell.exe -executionpolicy bypass -file .\allow-drivers.ps1
```
