# Hardware

This repository is intended to be a list of my machines, their components, roles, and what runs on them.

## Release Versioning System

*A*.*B*.*C*.*D*, where:

* *A* = New hardware added or previously installed hardware removed, e.g. new laptop acquired or desktop sold
* *B* = Layout change of currently installed hardware, e.g. HDD moved from Computer1 to Computer2
* *C* = New software added or previously installed software removed, e.g. New backup software not previously run on any other machine added, or previously present software removed so that it no longer runs on any of my machines
* *D* = Layout change of currently installed software, e.g. Pi-hole moved from Computer1 to Computer2

Temporary, stopgap measures, such as substituting a surge protector for a failed UPS, are not considered (for) hardware release versions unless they become permanent.

## General Principles

* OSes, firmwares/BIOSes, and apps are on the latest stable release at the very least and patched very aggressively
* Drivers are on the latest stable release. Beta drivers are not used unless they provide a critical feature or security patch unavailable in the latest stable release
* Maintenance of existing hardware is prioritized over deployment of new hardware, e.g. An existing machine will be migrated from one OS to another before a new machine is set up from scratch (assuming both are on the to-do list)

## Product Information

* I've made my best attempt to link to OEM product info or support pages or spec sheets for each part. Where I've been unable to find these, I've substituted a reliable 3rd party source
* Where not indexed (e.g. "Unit *n*," no quotes, where *n* is a positive integer) or hyperlinked, separate identical product mentions can be assumed to be the same physical item

## FAQ

### Why are there no Macs?

* Macs have the worst $/specs on the market. Even used Macs are horrifically overpriced compared to used enterprise PCs that work just as well and are more repairable and upgradable
* I'm philosophically opposed to much of Apple's computing vision
* An open source Unix implementation, OpenIndiana, exists

### Did you buy everything new?

No. I bought all the non-Windows x86 machines used IRL. Generally speaking, buying brand new PCs for open source OSes is a waste: older hardware is better supported and runs the OS just as well. That said, everything else was bought new. And no, I don't shop on Ebay.

### You should run *insert OS here*

Maybe. Currently I run OSes and hardware only [IFF](https://en.wikipedia.org/wiki/If_and_only_if) they fit into my workflow (read: if I'm sure I'd use them for something practical). My next non-Windows OS is likely to be one of (in no order):

* FreeNAS
* Fedora
* OpenSUSE
* Manjaro

My next Windows SKU will be Windows 10 Pro for Workstations. 

### What do you use for VMs?

I don't have a use case for VMs. Translation: none of my current workflows would be improved via running a VM. 

### Is managing all of this difficult?

Setup is difficult, yes. This is a very involved hobby. That said, setting OSes to automatically update themselves where that feature is available as well as sticking to repository/ports tree apps significantly reduces post-setup workload. From then on you're basically only addressing stuff that breaks, which is rare.

### What's the point?

* I love computers. Perhaps because I'm (a pretty bad) one
* I want to be able to speak about different OSes, applications, and systems from firsthand experience

### Why didn't you build any of your machines?

Getting there eventually. I'll probably build my next new desktop myself.

### How do you shop for new PCs and parts?

1. Go go the OEM website
2. Get OEM part number. Avoid products you can't find an OEM product page for; it's usually indicative of poor support
3. Search Google Shopping for part number
4. Select the in-stock store that has a rating of at least 4 stars with the lowest total price (including shipping)

The above method can get you brand new stuff for as much as half off MSRP.

### What's your main OS?

Windows 10.

### You should switch from Windows because *insert reasons here*

No(t for now.) At the very least, because:

1. Windows GUI-first approach makes everything cognitively easy and is generally tolerant of mistakes. Point, click, done
2. Unix, Linux, and BSD are relatively unforgiving 
3. Windows services management is the best of all modern OSes
4. NTFS supports seamless on-disk snapshots, which ext4 does (ZFS does, but BSD doesn't have the app libary or dev support to be my main OS)
5. Windows is a 1st class citizen when it comes to dev support
6. Veeam, the best backup system currently available to me, supports Windows best
7. I have the most experience (25+ years?) and am therefore most familiar with Windows

## Why did you choose the NETGEAR BR500? Isn't it a terrible product?

If you're trying to use it as advertised, it is. However, its performance, ease of use, and stability as a non-Insight OpenVPN gateway is excellent. Emphasis on the "ease of use" part of that; the BR500 has the easiest OpenVPN deployment I'm aware of. 

## Why don't you use pfSense? 

That's what the [Dell OptiPlex 3010](https://github.com/jdrch/Hardware/blob/master/Unused.md#unused-pcs) is for (eventually).

## Why don't you have a rack and actual server hardware?

Castoff client PCs are less expensive than the above and run the same applications appromixately as well. An exception to the latter part of that statement is ECC RAM, but that isn't an issue for my use case (yet?)

## How can I contact you?/You're wrong about something here/Corrections/Errata/etc. 

* File an [issue](https://github.com/jdrch/Hardware/issues/new)!
* Create a pull request (serious PRs only, please)
* [Twitter](https://twitter.com/jdrch)
* [Reddit](https://www.reddit.com/user/jdrch)
* [Telegram](https://t.me/jdrch)
* @jdrch on Gitter.im
