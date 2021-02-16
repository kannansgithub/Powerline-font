# Set up Powerline in PowerShell
## PowerShell prerequisites
* Step - 1 : Open Powershell
* Step - 2 : Download font from [Powerline Font](https://github.com/kannansgithub/Powerline-font) and install in your system.
* Step - 3 : Git if you don't have already go to  [Git for Windows](https://git-scm.com/downloads) download and install
* Step - 4 : Enter in to powershell
  > Install-Module posh-git -Scope CurrentUser

  > Install-Module oh-my-posh -Scope CurrentUser
* Step - 5 : Your PowerShell command line will ask if you want to install NuGet if this is the case. Select [Y] Yes. You may also need to approve that you are installing modules from PSGallery, an 'untrusted repository'. Select [Y] Yes.
* Step - 6 : 
  > echo $profile
* Step - 7 : Copy the path and open your text editor (or) type 
  > code $profile
    - You have installed Vs Code this shell profile file will open in your VS Code Editor
- Step - 8 : Copy and paste the below line in the opend profile file
  > Import-Module posh-git

  > Import-Module oh-my-posh

  > Set-PoshPrompt -Theme agnoster
* Step 9 : If you are getting an error type below command. 
   - Open powershell as an administrator mode and tye below
   > Set-ExecutionPolicy Unrestricted

If you want to change the themes open [Ohmyposh Themes](https://ohmyposh.dev/docs/themes) and replace `Paradox` to your faviourate favorite theme.

