---
title: "How to make a playlist from a directory of mp3 files on terminal"
date: 2020-08-20T14:21:28+01:00
draft: false
cover: "img/terminalplaylist.png"
---



It turns out that there exists a fairly universal format called m3u format, and it can be as simple as a list of filenames separated by newlines.

```sh
$ cd to the directory 
```
and

```sh
$ ls -1 *.mp3 > playlist.m3u
```

That's it, after this you can just open the playlist and reorder the songs on the desired order.

