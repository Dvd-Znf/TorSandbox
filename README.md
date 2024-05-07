# Tor Browser installed automatically in WindowsSandbox
This repo provides necessary Windows Sandbox configuration file and logon script  
In order to automatically start a new Sandbox with the latest version of the TOR browser  
   
![Banner](/res/Banner.bmp)  
## Why use TOR inside WindowsSandbox?
Because of this [reddit post](https://www.reddit.com/r/TOR/comments/tif9pp/question_about_tor_browser_and_the_windows_release/)   
But also because using the TOR browser inside a vm like windows sandbox should somewhat remove any possible tracking fingerprinting nonsense  
If you want absolute* anonymity just use something like TAILS or WHONIX   
    
But if you use windows and want a super convenient way to use the TOR network but still have somewhat isolation from your real hardware    
Then this repo is for you!   
## How to use?
```
PS: cd Desktop
PS: git clone   
PS: WindowsSandbox TorSandbox\TorSandbox.wsb  
```
### The installation is now portable so you can move the repo anywhere, even outside of your pc (Ex. on a NAS)   
If you want you can move the custom shortcut anywhere you want and even pin it to the taskbar    
The shortcut also has a custom icon that is broken in some smaller sizes (Maybe I'll fix in near future)   

## TODO:     
- [ ] Make a single Powershell shell script like here: https://github.com/microsoft/winget-pkgs/blob/master/Tools/SandboxTest.ps1    
