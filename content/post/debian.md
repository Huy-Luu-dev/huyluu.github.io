+++
title = 'Debian'
date = 2023-11-07T09:53:06Z
+++

# Welcome to my channel in the video
# How to install qemu in termux
# Download termux version 0.118 in github release with armv71 & armv81 now

# Step 1 Open termux version 0.118 & update tool in termux
```
apt update && apt upgrade -y

```
# Step 2 Install x11 mirror
```
pkg install x11-repo

```
# Step 3 install proot-distro in termux 
```
pkg install proot-distro -y

```
# Step 4 install debian in proot-distro
```
proot-distro install debian

```
# Step 5 login debian to ptroot
```
proot-distro login debian

```
# Step 6 update tool in debian
```
apt update && apt upgrade -y

```
# Step 7 install xfce4 desktop
```
apt install xfce4* dbus-x11 firefox-esr -y

```
# Step 8 start to vncserver with display to 1280x720 and passwd 12345678 and add address to localhost:1
```
vncserver -geometry 1280x720 -xstartup startxfce4

```
# Step 9 stop use vncserver in termux in your ports 5901 and exit termux
```
vncserver -kill :1

exit

```
# Thank for installation debian in termux with proot-distro
