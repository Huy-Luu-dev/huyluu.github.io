+++
title = 'Ubuntu'
date = 2023-11-07T10:03:26Z
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
# Step 4 install ubuntu in proot-distro
```
proot-distro install ubuntu

```
# Step 5 login ubuntu to proot-distro
```
proot-distro login ubuntu

```
# Step 6 update tool in ubuntu
```
apt update && apt upgrade -y

```
# Step 7 install xfce4 desktop
```
apt install xubuntu-desktop dbus-x11 firefox-esr tightvncserver -y

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
