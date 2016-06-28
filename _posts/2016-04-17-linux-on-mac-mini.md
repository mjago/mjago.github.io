---
layout:            post
title:             "Linux on a Mac-mini"
menutitle:         "Linux on a Mac-mini"
category:          Projects
author:            mjago
tags:              Linux, Apple
---

## Old hardware

   ![]({{ site.github.url }}/assets/apple_mac_mini_intel.jpg)

I am in posession of an old Mac mini circa 2009. The exact details follow:

- 2.0 GHz Core 2 Duo (T7200)
- Intro.	August 7, 2007	Disc.	March 3, 2009
- Family	Mid-2007	ID	Macmini2,1
- RAM	1 GB	VRAM	64 MB
- Storage	120 GB (5400 RPM)	Optical	2.4X "SuperDrive"

Since the hardware will no longer support Apple's supported OSX I
decided to try and install a version of Linux on it.

## Lubuntu

I looked around for a low resource Linux and came across **Lubuntu**,
which is a low-resource version of **Ubuntu**, and uses the minimal
**LXDE** windows manager.

## Installation

The only real complication I found was due to the use of EFI
(Extensible Firmware Interface) as opposed to GRUB. Useful background can be found [here](http://www.rodsbooks.com/ubuntu-efi/) and [here](https://help.ubuntu.com/community/UEFIBooting).

Installation was fairly straight-forward and the Mac-mini now runs a
fairly simple HTML5 home media server (written in NodeJS), serving
movies, photos, and links to anyone on the family network.
