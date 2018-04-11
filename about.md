---
layout: page
title: About
permalink: /about/
---

### History

The Linux Wacom Project was created in 2002 by John Joganic. The code was kept in CVS and regularly released in the form of a tarball that included kernel drivers, X drivers and various utilities. In August 2009, Peter Hutterer split out the X11 driver from the linuxwacom package and imported it into a git repository called xf86-input-wacom. This driver has seen quite a bit of rework, dropping of some features (e.g. XFree86-4 support) and gaining others (e.g. input device properties). All modern distributions now ship xf86-input-wacom as their X driver for Wacom tablets. Kernel-level device support is developed upstream on the Linux Kernel Mailing List.

Some (mainly enterprise) users need to run specific kernels or X server versions. For these, the Linux Wacom Project provides ongoing support for the linuxwacom tarballs and a newer tarball called input-wacom. Both of these package include kernel backports for certain kernel versions. Desktop distribution users usually do not need either tarball and should rely on their distribution packages instead.

Some more information about the history of the project is available on [Peter Hutterer's blog](http://who-t.blogspot.com/2010/09/wacom-support-in-linux.html).

Currently, members of the project include:

* Ping Cheng, Wacom
* Peter Hutterer, Red Hat
* Jason Gerecke, Wacom
* Aaron Armstrong Skomra, Wacom
* and other community members like you.

### Contact us

The best way to contact the members of this project is to join and send a message to the relevant  [mailing list](https://github.com/linuxwacom/input-wacom/wiki/Mailing-lists-and-Support).
