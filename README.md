

## HackTheEnv

---

Welcome to HackTheEnv!

HackTheEnv is an automation tool designed to customize your Linux environment, specifically tailored for Debian-based systems. We hope you find it enjoyable and useful!

This project is a modified version of the original work found at: https://github.com/elswix/KL-Sunset

### Desktop

![](https://github.com/elswix/HackTheEnv/blob/main/IMG/1.png?raw=true)



### Console (Non-privileged user)

![](https://github.com/elswix/HackTheEnv/blob/main/IMG/2.png?raw=true)


### Root user

![](https://github.com/elswix/HackTheEnv/blob/main/IMG/3.png?raw=true)

---

### Instalation


The installation is very simple, you just need to run the "install.sh" script as a NON-PRIVILEGED user. I recommend paying attention during the installation process as there may be points where you are prompted for your password or confirmation to install certain packages.


#### For Parrot users

Please ensure you carefully read and follow the instructions provided by the script. If you are using Parrot OS, kindly make the necessary modification on line 50 as follows:

```
sudo apt update && parrot-upgrade
```


For optimal results, it is recommended to install this environment on a freshly installed Debian-based system.

Please use a terminal other than Kitty to execute this script.


Installation commands:

```
git clone https://github.com/elswix/hacktheenv hacktheenv
cd hacktheenv
chmod +x ./install.sh
./install.sh 
```

---


### After installation

After completing the installation, it is necessary to reboot your system. Once you reach the Login Screen, you need to change the Window Manager to i3 by selecting it from the top-right corner of the screen.

![](https://github.com/elswix/HackTheEnv/blob/main/IMG/4.png?raw=true)


### Most important keyboard shortcuts

Press `Windows+Return` to open a Terminal.

Press `Windows+D` to open Rofi.

Press `Windows+Shift+F` to open Firefox Browser.

Press `Windows+Shift+B` to open BurpSuite (It must be installed).

Press `Windows+Shift+R` to restart i3 configuration.


### Ethernet Status Bar

If the Ethernet status bar is not functioning properly, as shown in the following image:

![](https://github.com/elswix/HackTheEnv/blob/main/IMG/5.png?raw=true)


To resolve the issue with the Ethernet status bar, you should modify the "/usr/share/i3blocks/ethernet_status" script and update the default network interface name "eth0" to match the configuration of your system. 

If modifying the script does not resolve the issue, it is recommended to check your network adapter. Ensure that the network adapter is properly connected and configured. You may also consider checking for any driver updates or troubleshooting network settings to address the problem.

### Target Status Bar

To modify the target status bar, utilize the "settarget" command.

For example:

```
settarget "10.10.10.10 - HackTheBox"
```

![](https://github.com/elswix/HackTheEnv/blob/main/IMG/6.png?raw=true)

---

### Thank you for reading:

+  [Instagram](https://www.instagram.com/elswix_/)
+  [YouTube](https://www.youtube.com/@ElSwix)
+  [Twitter](https://twitter.com/elswix_)
+  [HackTheBox](https://app.hackthebox.com/profile/935172)


#### My Blog: 

+ [elswix.github.io](https://elswix.github.io)
