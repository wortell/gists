# Wortell POSH Prompt

![image](https://user-images.githubusercontent.com/9781801/115554228-8687fb80-a2ae-11eb-8998-4d2fd0ab7581.png)


## Installation 

 1. If you haven't already done so, go to [ohmyposh.dev](https://ohmyposh.dev/docs/installation) website to follow the installation guide of Oh my Posh.
 2. You need to install a [Nerd Font](https://www.nerdfonts.com/) to display the symbols correctly.
 3. Download the json file
 ```powershell
Invoke-WebRequest -Uri "https://raw.githubusercontent.com/wortell/gists/main/wortell-posh-prompt.json" -OutFile "./wortell-posh-prompt.json"
``` 
 4. Set the Wortell POSH Prompt 
```powershell
Set-PoshPrompt ./wortell-posh-prompt.json
```

* Optional: Install the terminal-icons module
```powershell
Install-Module terminal-icons
``` 
import the terminal-icons module
```powershell
Import-Module terminal-icons
```

To add this to your machine profile
```powershell
echo "Import-Module terminal-icons">>$PSHome/profile.ps1
