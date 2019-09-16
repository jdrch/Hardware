# Model

[Dell Inspiron 390 SFF](https://www.dell.com/support/home/us/en/04/product-support/product/optiplex-390/overview)

# Operating System

[Project Trident STABLE](https://project-trident.org/download/)

# Role(s)

* Client PC
* zpool mirror server

# CPU

[Intel Core i3-2100 Processor](https://ark.intel.com/content/www/us/en/ark/products/53422/intel-core-i3-2100-processor-3m-cache-3-10-ghz.html)

# RAM

16 GB ([G.SKILL F3-1600C11D-16GNT](http://www.gskill.com/product/165/186/1532584719/F3-1600C11D-16GNTValueDDR3-1600MHz-CL11-11-11-1.50V16GB-(2x8GB)))

# Storage

## Boot/OS & `/home`

[Samsung SSD 860 EVO 2.5" SATA III 1 TB](https://www.samsung.com/us/computing/memory-storage/solid-state-drives/ssd-860-evo-2-5--sata-iii-1tb-mz-76e1t0b-am/) (onboard SATA 2.0, ZFS) installed in [Vantec SSD/HDD Aluminum Caddy for 12.7mm ODD Laptop Drive Bay](https://www.vantecusa.com/products_detail.php?p_id=144&p_name=SSD%2FHDD+Aluminum+Caddy+for+12.7mm+ODD+Laptop+Drive+Bay&pc_id=6&pc_name=Converters&pt_id=2&pt_name=Hard+Drive+Accessories)

## ZFS on zpool mirror

* [Hitachi Travelstar 5K250 HTS542525K9SA00 250 GB HDD](https://www.newegg.com/hitachi-gst-travelstar-5k250-250gb-hts542525k9sa00/p/N82E16822145159) ([HBA SATA 3.0](https://github.com/jdrch/Hardware/blob/master/Dell%20OptiPlex%20390-1%20SFF.md#sata-30), ZFS)
* [Hitachi Travelstar 5K320 HTS543212L9A300 120 GB HDD](https://www.hdsentinel.com/storageinfo_details.php?lang=en&model=HITACHI%20HTS543212L9A300) (onboard SATA 2.0, ZFS)

# Expansion Cards

## SATA 3.0

[StarTech 2 Port PCI Express SATA 6 Gbps eSATA Controller Card - Dual Port PCIe SATA III Card - 2 Int/2 Ext](https://www.startech.com/Cards-Adapters/HDD-Controllers/SATA-Cards/2-Port-PCI-Express-SATA-6-Gbps-eSATA-Controller-Card~PEXESAT322I). The [HBA SATA Hitachi Travelstar 5K250](https://github.com/jdrch/Hardware/blob/master/Dell%20OptiPlex%20390-1%20SFF.md#btrfs-raid1-with-autodefrag) is connected to this.

# Backup

## Filesystem & OS Versioning

[zfsnap](https://www.zfsnap.org/)

## Real-time P2P File Sync

[Resilio Sync Home Pro](https://www.resilio.com/individuals/)

# 24/7/52 Applications

Resilio Sync Home Pro

# Peripherals

## Mouse 

[Logitech Wireless Trackball M570](https://www.logitech.com/en-us/product/wireless-trackball-m570-business?crid=7)

## Keyboard

[Dell XD31 Wired USB Multimedia Keyboard](https://pcpartpicker.com/product/Zrw7YJ/dell-xd31w-wired-usb-multimedia-keyboard)

## UPS

[APC Back UPS PRO BR 1350VA, SineWave, 10 Outlets, 2 USB Charging Ports, AVR, LCD interface](https://www.cyberpowersystems.com/product/ups/cp1500pfclcd/)

# External Monitors

* Left (Main), 1080p, HDMI: [Dell S2240L](https://www.dell.com/support/home/us/en/04/product-support/product/dell-s2240l/overview)
* Right, 768p, VGA: [Dell IN1920f](https://www.dell.com/support/home/us/en/04/product-support/product/dell-in1920/docs)





