# WSL Setup For Windows 11

WSL is a awesome way of using linux environment in windows.    
In this tutorial, we will see how to setup WSL in windows 11.

### Step1
In windows search, type "Features",    
right after that a app named "Turn windows features on or off" will appear.    
Now launch that app.    

### Step2
In that app, enable the "Virtual Machine Platform" and the "Windows Subsystem for Linux" features.    
And then click OK in the bottom of the app.
After this, if it asks to reboot your device, just go for it.

### Step3
After reboot, type "cmd" in windows search, and launch the Command Prompt.    
We will be installing our linux distros from the cmd only.

### Step4
In the cmd, run the following command to install a WSL Distro:    
```
wsl --install Distro

```
Replace "Distro" with whatever WSL Distro you want to install.    
If you want, use the following command to list all the Distros that are available in WSL:
```
wsl --list --online

```

### Step5
Give it some time to install......


### Step6
Now after installing a WSL Distro, You will be asked for a user name and a password.    
Note that you will be asked for the password twice, both of those should be the same.        
After this you will be inside the distro that you chose. Enjoy your distro!    
If you accidentally closed out of your distro, use the following command to get into it again:
```
wsl -d Distro

```
Replace "Distro" with the distro you want.
