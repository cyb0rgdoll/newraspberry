# newraspberry
New Raspberry Setup &amp; Tweaks for Beginners

This repo will provde you a list of tweaks to make right and better after installing Raspberry Pi OS (formerly Raspbian) 
on your **Raspberry Pi.**


 login (default user = pi, default password = raspberry), you can still get to it on the command line, type in: ```sudo raspi-config```


Change the Raspberry Default Password, open up LXTerminal and type in: passwd

```
pi@raspberrypi:~ $ passwd
Changing password for pi.
Current password:
New password:
Retype new password:
passwd: password updated successfully
```

On the command line, type in:
```
sudo apt-get update
sudo apt-get upgrade
```

These update package lists from the various repositories and updates them to get information on the newest versions of packages and their dependencies. 

When done:
```
sudo apt autoremove
sudo apt autoclean
sudo reboot
```

Now you need an app installer, [Pi-Apps]{https://github.com/Botspot/pi-apps} is the most popular app store for Raspberry Pi computers. 100% free, open-source and written in shell scripts. It has over 200 apps, to begin install.. open terminal and type ths commannd:

```
wget -qO- https://raw.githubusercontent.com/Botspot/pi-apps/master/install | bash
```

