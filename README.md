Linuxcnc Remote (DEVELOPMENT FROZEN)
======

Linuxcnc Remote allows you to gain remote access to a CNC Machine via Network and Redis

How to use
---------------------------
1. plant the seed.py on your CNC Machine, execute in terminal ~# python seed.py
2. run remote.py on your remote computer
3. start sending commands

Supported Operating Systems
---------------------------
Only tested on linuxcnc Debian 9 Stretch

**Required:**
$ python3 -m pip install -r requirements.txt
* `python`: Linuxcnc Remote works only with Python 2.7
* [`linuxcnc`](http://linuxcnc.org/docs/2.6/html/common/python-interface.html): You need an installation of Linuxcnc
* [`linuxcnc Python Interface`](http://linuxcnc.org/docs/2.6/html/common/python-interface.html): Data polling
* [`redis`](https://redis.io/) for sending requests to your workstation

on WINDOWS:
https://github.com/microsoftarchive/redis/releases/download/win-3.0.504/Redis-x64-3.0.504.msi


on LINUX:
edit redis.conf
comment out bind
safe mode to no
   
