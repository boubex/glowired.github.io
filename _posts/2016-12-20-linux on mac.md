---
layout: post
title:  "How to dual boot any linux distro on mac"
color:  teal
width:   6
height:  1
author: Abouba
date:   2016-12-24 01:10:49 +0200
categories: jekyll update
image: kali.jpg
label : learn
---

if you want to use both unix and linux on your mac ,fear not. the solution is easy ,all you do  is to  dual boot and choose which one to boot from in these easy steps

this solution will boot your linux disto in live mode which means ass soon as you boot you start working,no need to install and wait for long moments,however because its in a livemode it wont save your work,it starts fresh every time you reboot



first you need a linux distro,you are free to choose which ever you want but i would recomend kali linux becouse its free and open source and comes with alot of tools which you can download here <link href="#">

second you need to download a tool called Mac Linux USB loader on this link
<img class="img-responsive" src="{{site.github.url}}/img/linuxl.png">
<link href="#">

from here you either have an option to use a usb or to use you own space fron your SSD or HDD either way it both works

if u choose to use your space then you need to head to disk utility
which u can find by searcing it in the spotlight search
<img class="img-responsive" src="{{site.github.url}}/img/disk.png">

when the screen shows up you need to click on the main SSD or HDD and then click on partition
<img class="img-responsive" src="{{site.github.url}}/img/part.png">

when this screen shows up click on the plus button and set the size of the partition you want depending on the linux distro you chose,id say 10 gbs will work fine

remeber to set the partition format to ________ becouse if you dont it wont work
<img class="img-responsive" src="{{site.github.url}}/img/part2.png">



then you need to copy the linux distro iso to the partition you just made,you dont need to mount it

the you install the linux usb and oppen it and choose create live usb ,the choose the location of your distro in your partition
