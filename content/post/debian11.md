+++
title = 'Debian'
date = 2023-11-07T10:07:57Z
+++

# Welcome to my channel
# Install debian in termux
# Download to termux version 0.118
# This in debian11 in termux to proot

# Step 1 open termux on android & update tool in termux

```
pkg update -y && pkg upgrade

```
# Step 2 install proot & wget 

```
pkg install wget proot

```
# Step 3 download file debian.sh in termux and bash debian.sh de install
```
wget https://raw.githubusercontent.com/EXALAB/Anlinux-Resources/master/Scripts/Installer/Debian/debian.sh && bash debian.sh

```
# Step 4 login debian11 in termux with proot
```
./start-debian.sh

```
# Step 5 update tool in debian 11 

```
apt update && apt upgrade -y

```
# Step 6 install debian with file de-apt-xfce.sh & bash your-file-name.sh

```
wget https://raw.githubusercontent.com/Cesar-Hack-Gray/Linux/master/Scripts/DesktopEnvironment/Apt/Xfce4/de-apt-xfce4.sh && bash de-apt-xfce.sh

```
# Step 6 done type passwd in tightvncserver

```
1234567890

```
# Step 7 kill to vncserver with port 5901 and openvnc and add address tpo localhost:1
```
vncserver -kill :1

```
# Goodbye
