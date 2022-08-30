---
title: BadController
author: capysix
date: 2022-08-30
categories: [Rev]
---
## Challenge

![](challenge.png))

## Writeup

The challenge, BadController comes with two files:

challdriver.exe - the aforementioned 'badcontroller' driver
log.pcap - a capture of the USB network traffic between the driver and the device

Opening up challdriver.exe in IDA decompiler, we see several functions and loops

<screenshot>
<screenshot>


as well as this rather suspicious looking function call at the end

<screenshot>