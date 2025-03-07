# SmartOS Users Guide

## SmartOS Basics

- [Finding Your Way Around in SmartOS][around-smartos]
  - This document from the Joyent cloud wiki is helpful to Linux users
    approaching SmartOS for the first time.
- [The Joyent Linux-to-SmartOS Cheat Sheet][linux-smartos-cheatsheet]
- [Commands that Work Differently (from Linux) in SmartOS][commands-different]
- [SmartOS: A System Administrator's Primer][sa-primer] (video, Ben Rockwood)

[around-smartos]: http://wiki.joyent.com/display/jpc2/Finding+Your+Way+Around+in+SmartOS
[linux-smartos-cheatsheet]: http://wiki.joyent.com/display/jpc2/The+Joyent+Linux-to-SmartOS+Cheat+Sheet
[commands-different]: http://wiki.joyent.com/display/jpc2/Commands+that+Work+Differently
[sa-primer]: http://smartos.org/2012/08/22/smartos-an-sa-primer/

## SmartOS for Admins

- [Persistent Configuration for the Global Zone][gz-persist]

[gz-persist]: persistent-configuration-for-the-global-zone.md

### SmartOS, a Primer for Sysadmins

<iframe class="youtube-player" type="text/html" style="width: 400px;
    height: 300px" src="http://www.youtube.com/embed/dxZExLeJz2I"
    frameborder="0"> </iframe>

Ben Rockwood speaking at the BayLISA meetup at Joyent, August 16, 2012

### SmartOS Operations

<iframe class="youtube-player" type="text/html" style="width: 400px;
    height: 300px" src="http://www.youtube.com/embed/96PGoXHli3Q"
    frameborder="0"> </iframe>

Ben Rockwood at illumos Day, Oct 2012, gives a look at tools and
techniques for large-scale operations in a SmartOS environment, from
monitoring to configuration management and troubleshooting.

### KVM

- [Migrating from VirtualBox to KVM on ZFS][migrating-from-vbox]
- [Changing virtual hardware of KVM zones][changing-vm-hw-kvm]

[migrating-from-vbox]: https://gist.github.com/1947201
[changing-vm-hw-kvm]: changing-virtual-hardware-of-kvm-zones.md

### PXE

- [Serving SmartOS from your PXE server][smartos-pxe]
- [PXE Booting SmartOS][simple-pxe] - Using SmartOS to host a PXE server to
  serve SmartOS

[smartos-pxe]: http://nahamu.github.com/2011/08/17/smartos-pxe.html
[simple-pxe]: pxe-booting-smartos.md

## Adding Stuff to SmartOS

- [Working with Packages][packages]
- [Installing Chef on Joyent's SmartOS][installing-chef]
- [Installing Software on a SmartMachine][installing-software]
- [Converting Virtual Appliance Packages for Fun and Profit][converting-appliances]

[packages]: working-with-packages.md
[installing-chef]: http://mirrorshades.net/post/11283352457
[installing-software]: http://wiki.joyent.com/display/jpc2/Installing+Software+on+a+SmartMachine
[converting-appliances]: http://smartos.org/2012/03/30/converting-virtual-appliance-packages-for-fun-and-profit/
