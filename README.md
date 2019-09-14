# HardwareDetails

This repository is intended to be a list of my machines, their components, roles, and what runs on them.

## General Principles

* OSes, firmwares/BIOSes, and apps are on the latest stable release at the very least and patched very aggressively
* Drivers are on the latest stable release

## Product Information

* I've made my best attempt to link to OEM product info or support pages or spec sheets for each part. Where I've been unable to find these, I've substituted a reliable 3rd party source

## FAQ

### Why are there no Macs?

* Macs have the worst $/specs on the market. Even used Macs are horrifically overpriced compared to used enterprise PCs that work just as well and are more repairable and upgradable
* I'm philosophically opposed to much of Apple's computing vision
* I already run an open source UNIX implementation (BSD) anyway

### Did you buy everything new?

No. I bought all the non-Windows x86 machines used IRL. Generally speaking, buying brand new PCs for open source OSes is a waste: older hardware is better supported and runs the OS just as well. That said, everything else was bought new. And no, I don't shop on Ebay.

### You should run *insert OS here*

Maybe. Currently I run OSes and hardware only [IFF](https://en.wikipedia.org/wiki/If_and_only_if) they fit into my workflow (read: if I'm sure I'd use them for something practical). My next non-Windows OS is likely to be either FreeNAS, Fedora, or Manjaro.

### What do you use for VMs?

Aside from Linux on Dex, I don't have a use case for VMs. Translation: none of my current workflows would be improved via running a VM. 

### Is managing all of this difficult?

Not gonna lie, yes. This is a very involved hobby. That said, setting OSes to automatically update themselves where that feature is available as well as sticking to repository/ports tree apps significantly reduces the workload

### What's the point?

* I love computers. Perhaps because I'm (a pretty bad) one
* I want to be able to speak about different OSes, applications, and systems from firsthand experience

### Why didn't you build any of your machines?

Getting there eventually. I'll probably build my next new desktop myself.

### How do you buy new PCs and parts?

1. Go go OEM website
2. Get OEM part number. Avoid products you can't find an OEM product page for; it's usually indicative of poor support
3. Search Google Shopping for part number
4. Select the in-stock store that has a rating of at least 4 stars with the lowest total price (including shipping)

The above method can get you brand new stuff for as much as half off MSRP.

### What are the minimum specs you recommend for any new PC?

1. CPU: ≥ 4C/8T for mainstream use, ≥ 6C/12T for gaming
2. RAM: Max supported RAM ≥ 16 GB
3. LAN: ≥ 1000BASE-T Ethernet
4. Bluetooth: ≥ 5.0
5. Wi-Fi: ≥ 2x2 802.11ac
6. USB: ≥ USB 3.1 Gen 1
7. Storage: NVMe SSD at the least
8. GPU/video out: HDMI ≥ 1.4 or DisplayPort ≥ 1.2
9. Display: 1080p

### What are the minimum specs you recommend for any used PC?

1. CPU: ≥ 2C/4T. Must be covered by Intel speculative execution security patches 
2. RAM: Max supported RAM ≥ 8 GB
3. USB: ≥ USB 2.0
4. Storage: Available port for SATA SSD
5. GPU/video out: ≥ HDMI
6. Display: ≥ 768p
7. LAN: ≥ 1000BASE-T Ethernet
