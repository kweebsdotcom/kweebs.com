---
title: "Share your raspberry pi/Linux folders using Python"
date: 2021-03-14T14:21:28+01:00
draft: false
cover: "img/Apache-Directory-Listing.png"
---

# Share your raspberry pi/Linux folders using a Python webserver.

An easy way to share your raspberry pi folder when you only have access to it via shell is using a python webserver.

Ssh into your machine, cd into the folder you want to share and type the following command:

## If you are using python 2 use this one

```sh
$ python -m SimpleHTTPServer
```
## If you are using python 3 use this one

```sh
$ python -m http.server
```

After that just open a browser o the machine you wan to access the files and enter the hostname or the ip address of the machine you just created the python webserver followed by :8000 you should be able to browse the files and open and download the ones you want by right click them like you do on any other webpage.

Hope this was helpfull.