---
layout: post
title: Flutter on real hardware
---

I tried to run the debug version of the flutter on my phone but it won't let me saying I have to install release version (without the debugger running).

So I built the release versions and ran on my iPhone and Android devices and both failed to show the images at all and end up with essentially blank screen. 

I thought maybe I started with an old project and started with a fresh new project and copied over the dart files but still ended up with blank screen.  

The fact that I don't get any error and the problem is with both OSes, something fundamental to the way the widgets are being called is broken for release (as compared to debug).

