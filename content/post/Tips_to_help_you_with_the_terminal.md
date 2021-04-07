---
title: "Tips to help you with the terminal"
date: 2021-04-07T14:21:28+01:00
draft: false
cover: "sudo.png"
---


# Here are some shortcuts I think are helpfull in the bash shell.

Have you ever typed a long command and remembered that you needed to run another first?
Well, this is ine of them:

```sh
$ cp somefile /path/to/destination/somefile
```
# Press alt+Shift+3 and it will insert a # in the begining of the command for your convenience

```sh
#somefile /path/to/destination/somefile
```

# another one is the combination of the keys CTRL+r to search your history
After pressed just start typing the command you typed in the past and it will find it for you,
if you typed more than one and it was'nt your latest you can press ctrl+r again until you find it.

# Using Bang commands is very usefull when you are tired of typing the same thing again and again.

```sh
chmod +x /work/execute.sh
sudo !!
```
# sudo !! will execute the previous command with root privileges where "!!" is the last command
# If you want just the last part of the command use "!$"

```sh
chmod +x /work/execute.py
python !$
```
# If it has more than an argument  you can use "!*"

```sh
chmod +x file1 file2 file3
cp !* /destination/
```

# There are many others but the ones described above will keep you entertained for a while.

