## **Update Google Chrome, Avast Secure, Hugo, GitHub CLI, Jq, Yq, Pup, XMLstarlet, Wmi Explorer, Rufus and Youtube-Dl with Windows Shell**
---
##### Author: Fabrice Sanga
<br/>

The `profile.init.bat` file :
```batfile
@Echo OFF
If %~1==autorun_parent Echo Path\To\Autorun\Profile\Folder
```
<br/>

The usage :
```batfile
Update-Hugo [CopyToDirectory]
Update-GitHubCLI [CopyToDirectory]
Update-Jq [CopyToDirectory]
Update-Yq [CopyToDirectory]
Update-YoutubeDl [CopyToDirectory]
Update-Pup [CopyToDirectory]
Update-WmiExplorer [CopyToDirectory]
Update-Rufus [CopyToDirectory]
Update-XML [CopyToDirectory]
Update-AvastSecure [CopyToDirectory]
Update-GoogleChrome [CopyToDirectory]
CopyToDirectory     The directory where to backup the installer
```