---
title: "How to Check Internet Speed via Terminal"
date: 2020-08-05T11:49:23+01:00
draft: true
---
To check your internet speed in terminal you can use 2 options:
sudo apt install speedtest-cli
speedtest-cli

or simply run
curl -s https://raw.githubusercontent.com/sivel/speedtest-cli/master/speedtest.py | python -
