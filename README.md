# oh-my-posh-config
```powershell
 if (!(Test-Path -Path $PROFILE )) { New-Item -Ty
pe File -Path $PROFILE -Force }
```
Append these script 
```powershell 
Import-Module posh-git
Import-Module oh-my-posh
Set-Theme Sorin
```
Window like alias on powershell script 
```powershell
Set-Alias -Name ll -Value ls
```
