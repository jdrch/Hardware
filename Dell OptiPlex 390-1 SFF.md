# Model

[Dell OptiPlex 390 SFF](https://www.dell.com/support/home/us/en/04/product-support/product/optiplex-390/overview) (Unit 2)

# Operating System

[Debian Stable AMD64 Port](https://www.debian.org/releases/stable/)

# Role(s)

* [dnscrypt-proxy](https://github.com/DNSCrypt/dnscrypt-proxy) DNS server
* [Pi-hole](https://pi-hole.net/) DNS server
* Pi-hole DHCP server
* NFSv4 (on Btrfs raid1 array) kernel server

# CPU

[Intel Core i3-2100 Processor](https://ark.intel.com/content/www/us/en/ark/products/53422/intel-core-i3-2100-processor-3m-cache-3-10-ghz.html)

# RAM

16 GB ([G.SKILL F3-1600C11D-16GNT](http://www.gskill.com/product/165/186/1532584719/F3-1600C11D-16GNTValueDDR3-1600MHz-CL11-11-11-1.50V16GB-(2x8GB)))

# Storage

## Boot/OS & `/home`

[Crucial MX500 1 TB SATA 2.5" 7mm Internal SSD](https://www.crucial.com/usa/en/ct1000mx500ssd1) (onboard SATA 2.0, ext4 on LVM) installed in [Vantec SSD/HDD Aluminum Caddy for 12.7mm ODD Laptop Drive Bay](https://www.vantecusa.com/products_detail.php?p_id=144&p_name=SSD%2FHDD+Aluminum+Caddy+for+12.7mm+ODD+Laptop+Drive+Bay&pc_id=6&pc_name=Converters&pt_id=2&pt_name=Hard+Drive+Accessories)

## Btrfs raid1 with `autodefrag`

* [Toshiba L200 HDWL120XZSTA 2 TB HDD](https://www.toshiba-storage.com/products/toshiba-internal-hard-drives-l200/?pdf) (onboard SATA 2.0, Btrfs)
* Toshiba L200 HDWL120XZSTA 2 TB HDD ([HBA SATA 3.0](https://github.com/jdrch/Hardware/blob/master/Dell%20OptiPlex%20390-1%20SFF.md#sata-30), Btrfs)

# Expansion Cards

## SATA 3.0

[StarTech 2 Port PCI Express SATA 6 Gbps eSATA Controller Card - Dual Port PCIe SATA III Card - 2 Int/2 Ext](https://www.startech.com/Cards-Adapters/HDD-Controllers/SATA-Cards/2-Port-PCI-Express-SATA-6-Gbps-eSATA-Controller-Card~PEXESAT322I). The [HBA SATA Toshiba L200](https://github.com/jdrch/Hardware/blob/master/Dell%20OptiPlex%20390-1%20SFF.md#btrfs-raid1-with-autodefrag) is connected to this

# Backup

## Device Backup Target Application

[Veeam Backup & Replication Community Edition](https://www.veeam.com/virtual-machine-backup-solution-free.html) running on [Dell Inspiron 560](https://github.com/jdrch/Hardware/blob/master/Dell%20Inspiron%20560.md)

## Device Backup Source Application

[Veeam Agent for Linux FREE](https://www.veeam.com/linux-backup-free.html)

## Filesystem Versioning

[Back In Time](https://github.com/bit-team/backintime) to [Btrfs raid1 with `autodefrag`](https://github.com/jdrch/Hardware/blob/master/Dell%20OptiPlex%20390-1%20SFF.md#btrfs-raid1-with-autodefrag)

## OS Versioning

[Timeshift](https://github.com/teejee2008/Timeshift) to [Btrfs raid1 with `autodefrag`](https://github.com/jdrch/Hardware/blob/master/Dell%20OptiPlex%20390-1%20SFF.md#btrfs-raid1-with-autodefrag)

## Real-time P2P File Sync

[Resilio Sync Home Pro](https://www.resilio.com/individuals/)

# 24/7/52 Applications

* [TeamViewer for Linux](https://www.teamviewer.com/en-us/download/linux/)
* Resilio Sync Home Pro
* Pi-hole
* dnscrypt-proxy
* [Cockpit](https://cockpit-project.org/)
* NFS kernel server
* [SSH](https://www.openssh.com/) (server)

# Peripherals

## Mouse & Keyboard

[Logitech MK850 Performance](https://www.logitech.com/en-us/product/mk850-wireless-keyboard-mouse-combo). Connected to [Tripp Lite Mini Bluetooth 4.0 (Class 1) USB Adapter](https://github.com/jdrch/Hardware/blob/master/Dell%20OptiPlex%20390-1%20SFF.md#bluetooth). Shared with [Dell XPS 8500 Special Edition](https://github.com/jdrch/Hardware/blob/master/Dell%20XPS%208500%20Special%20Edition.md#mouse--keyboard) and [Samsung Galaxy Note9](https://github.com/jdrch/Hardware/blob/master/Samsung%20Galaxy%20Note9.md#mouse--keyboad)

## UPS

[APC Back UPS PRO BR 1500VA](https://github.com/jdrch/Hardware/blob/master/UPS.md#battery-backed-up-devices)

## Bluetooth

[Tripp Lite Mini Bluetooth 4.0 (Class 1) USB Adapter](https://www.tripplite.com/mini-bluetooth-4.0-class-1-usb-adapter~U261001BT4). Connects to the [Logitech MK850 Performance](https://github.com/jdrch/Hardware/blob/master/Dell%20OptiPlex%20390-1%20SFF.md#mouse--keyboard)

# External Monitors

* [NEC EA275UHD-BK](https://github.com/jdrch/Hardware/blob/master/Monitors.md#connected-devices-2)
* [Dell UltraSharp U2713HM](https://github.com/jdrch/Hardware/blob/master/Monitors.md#connected-devices-3)
