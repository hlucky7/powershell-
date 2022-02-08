# powershell-
###安装命令

```
Install-Module oh-my-posh -Scope CurrentUser -SkipPublisherCheck
Install-Module posh-git -Scope CurrentUser
Install-Module -Name PSReadLine -AllowPrerelease -Scope CurrentUser -Force -SkipPublisherCheck
Install-Module -Name Terminal-Icons -Repository PSGallery
```

notepad.exe $PROFILE

设置profile

```
Import-Module posh-git
Import-Module oh-my-posh
Set-PoshPrompt -Theme robbyrussel
Import-Module -Name Terminal-Icons
Set-PSReadlineKeyHandler -Key Tab -Function MenuComplete
```
