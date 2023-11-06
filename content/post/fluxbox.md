+++
title = 'Fluxbox'
date = 2023-11-06T11:45:04Z
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
# Step 3 install firefox & fluxbox & tigervnc & pulseaudio
```
pkg install pulseaudio firefox tigervnc fluxbox -y

```

# Step 4 start to vncserver and passwd 12345678 and add address to localhost:1
```
vncserver

```
# Step 5 stop use vncserver in termux in your ports 5901 and exit termux
```
vncserver -kill :1

exit

```
# Goodbye
