# Waterfox automatic install for Linux

This repository contains an initial script, forked from [Linux-Is-Best](https://github.com/Linux-Is-Best/Firefox-automatic-install-for-Linux)'s amazing installer, that aims to install the latest version of waterfox on almost any Linux system.

## How to install

Set the script as executable:
```
chmod +x waterfox_system_install.sh
```
Run the script:
```
./waterfox_system_install.sh
```

## How to uninstall

Delete the install directory:
```
sudo rm -rf /opt/Waterfox
```
Delete the desktop files:
```
sudo rm /etc/skel/Desktop/Waterfox.desktop
rm ~/Desktop/Waterfox.desktop
```
