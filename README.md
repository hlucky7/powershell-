# powershell-
### 安装命令

```
Install-Module oh-my-posh -Scope CurrentUser -SkipPublisherCheck
Install-Module posh-git -Scope CurrentUser
Install-Module -Name PSReadLine -AllowPrerelease -Scope CurrentUser -Force -SkipPublisherCheck	# 自动命令补全
Install-Module -Name Terminal-Icons -Repository PSGallery	# 安装文件图标库
```

### 设置profile
```
notepad.exe $PROFILE
```
```
Import-Module posh-git
Import-Module oh-my-posh
Set-PoshPrompt -Theme robbyrussel
Import-Module -Name Terminal-Icons
Set-PSReadlineKeyHandler -Key Tab -Function MenuComplete
```
