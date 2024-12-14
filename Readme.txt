How to Install WSL in windows.
1. Open PowerShell 
1.1 wsl --install 
Reboot Your System
1.2 wsl -l -v (To check if there is any version of WSL is installed or not)
               If there is no subsystem is installed, type below command
1.3 wsl --list --online (This will list down the available distros to be installed)
               
1.4 wsl --install -d <Distribution Name>. Replace <Distribution Name>
Now, setup username and password

Most common issue you can face, even after successfully installing and rebooting the device, the wsl distros may not be found.
In this case, go to control panel -> programs -> programs and features -> turn of Windows subsystem for linux feature and the reboot the device.
And after this, again try to install the distros using above commands.

               
