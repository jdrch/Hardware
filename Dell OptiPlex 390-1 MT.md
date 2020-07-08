# Model

[Dell OptiPlex 390 MT](https://www.dell.com/support/home/us/en/04/product-support/product/optiplex-390/overview)

# Operating System

[Microsoft Windows Pro for Workstations 2004 Release Preview Channel 64-bit](https://docs.microsoft.com/en-us/windows-insider/flight-hub/)

# Role(s)

* Client PC
* [Veeam Backup & Replication Community Edition](https://www.veeam.com/virtual-machine-backup-solution-free.html) Server

# CPU

[Intel Core™ i5-2400 Processor](https://ark.intel.com/content/www/us/en/ark/products/52207/intel-core-i5-2400-processor-6m-cache-up-to-3-40-ghz.html)

# RAM

16 GB ([G.SKILL F3-1600C11D-16GNT](http://www.gskill.com/product/165/186/1532584719/F3-1600C11D-16GNTValueDDR3-1600MHz-CL11-11-11-1.50V16GB-(2x8GB)))

# Storage

## Boot/OS & User [Known Folders](https://docs.microsoft.com/en-us/windows/win32/shell/known-folders)

[Crucial MX500 500GB SATA 2.5" 7mm Internal SSD](https://content.crucial.com/content/dam/crucial/ssd-products/mx500/flyer/crucial-mx500-ssd-productflyer-letter-en.pdf) (SATA 2.0, NTFS) installed in lower slot of [Icy Dock EZ-Fit Lite MB290SP-B Dual 2.5" HDD & SSD Light Weight Mounting Bracket for Internal 3.5" Drive Bay](https://github.com/jdrch/Hardware/blob/master/Dell%20OptiPlex%20390-1%20MT.md#internal-accessories)

## Storage Pool

ReFS on mirror virtual disk created by the PowerShell command `New-VirtualDisk -StoragePoolFriendlyName StoragePool1 -FriendlyName VirtualDisk1 -ResiliencySettingName Mirror -NumberOfDataCopies 2 -ProvisioningType Fixed -UseMaximumSize -NumberOfColumns 1 -Verbose`

* [Seagate BarraCuda Pro ST12000DM0007 12 TB HDD](https://www.seagate.com/www-content/product-content/barracuda-fam/barracuda-new/en-us/docs/100818004c.pdf) (SATA 2.0), installed in lower front drive cage
* [Seagate Exos X12 ST12000NM0007 12 TB HDD](https://www.seagate.com/www-content/datasheets/pdfs/exos-x-12-DS1946-1-1709US-en_US.pdf) (SATA 2.0), installed in lower front drive cage

## Backup

This drive serves as a backup to [Storage Pool](https://github.com/jdrch/Hardware/blob/master/Dell%20OptiPlex%20390-1%20MT.md#storage-pool).

[Toshiba MG08ACA16TE Enterprise Capacity 16 TB HDD](https://toshiba.semicon-storage.com/content/dam/toshiba-ss/asia-pacific/docs/product/storage/product-manual/eHDD-MG08-Product-Overview.pdf) (SATA 2.0, NTFS), installed in upper slot of [Icy Dock EZ-Fit Lite MB290SP-B Dual 2.5" HDD & SSD Light Weight Mounting Bracket for Internal 3.5" Drive Bay](https://github.com/jdrch/Hardware/blob/master/Dell%20OptiPlex%20390-1%20MT.md#internal-accessories), connected to [StarTech 2 Port PCI Express SATA 6 Gbps eSATA Controller Card - Dual Port PCIe SATA III Card - 2 Int/2 Ext](https://github.com/jdrch/Hardware/blob/master/Dell%20OptiPlex%20390-1%20MT.md#sata-30)

# Internal Accessories

* [Icy Dock EZ-Fit Lite MB290SP-B Dual 2.5" HDD & SSD Light Weight Mounting Bracket for Internal 3.5" Drive Bay](https://www.icydock.com/goods.php?id=165), installed in lower slot of iStarUSA TC-ISTORM7 2x5.25" to 3x3.5" Internal Mounting Cooling Kit with Removable Filter (see below)
* [iStarUSA TC-ISTORM7 2x5.25" to 3x3.5" Internal Mounting Cooling Kit with Removable Filter](http://www.istarusa.com/en/istarusa/products.php?model=TC-ISTORM7), powered by StarTech.com LP4SATAFM6IN 6in SATA to LP4 Power Cable Adapter - F/M (see below)
* [StarTech.com LP4SATAFM6IN 6in SATA to LP4 Power Cable Adapter - F/M](https://www.startech.com/Cables/Computer-Power/Internal/6inch-SATA-to-LP4-Power-Cable-Adapter-Female-to-Male~LP4SATAFM6IN), powered by Rocstor Y10C224-B1 SATA Power Splitter Cable (see below)
* [Rocstor Y10C224-B1 SATA Power Splitter Cable](https://rocstor.com/product-tag/y10c224-b1/)

# Expansion Cards

## SATA 3.0

[StarTech 2 Port PCI Express SATA 6 Gbps eSATA Controller Card - Dual Port PCIe SATA III Card - 2 Int/2 Ext](https://www.startech.com/Cards-Adapters/HDD-Controllers/SATA-Cards/2-Port-PCI-Express-SATA-6-Gbps-eSATA-Controller-Card~PEXESAT322I) installed in PCIe 2.0 x16 slot

## USB 3.1

[StarTech 4-Port USB 3.1 PCIe Card](https://www.startech.com/Cards-Adapters/USB-3.0/Cards/4-port-usb-3-1-card~PEXUS313AC2V), powered by [Rocstor Y10C224-B1 SATA Power Splitter Cable](https://github.com/jdrch/Hardware/blob/master/Dell%20OptiPlex%20390-1%20MT.md#internal-accessories) installed in PCIe 2.0 x1 slot (SLOT 3)

# Backup

## Device Backup Target 

Local [Veeam Backup & Replication Community Edition](https://www.veeam.com/virtual-machine-backup-solution-free.html) repository

## Device Backup Source Application

[Veeam Agent for Microsoft Windows FREE](https://www.veeam.com/windows-endpoint-server-backup-free.html)

## Filesystem Versioning

* [Volume Shadow Copy](https://docs.microsoft.com/en-us/windows/win32/vss/volume-shadow-copy-service-overview)
* [ShadowExplorer](https://www.shadowexplorer.com/)

## OS Versioning

[System Restore](https://docs.microsoft.com/en-us/windows/win32/sr/system-restore-reference)

## Real-time P2P File Sync

[Resilio Sync Home Pro](https://www.resilio.com/individuals/)

## Storage Pool Backup Application

[SyncBackFree](https://www.2brightsparks.com/freeware/freeware-hub.html)

## Storage Pool Backup Target

[Toshiba MG08ACA16TE Enterprise Capacity 16 TB HDD](https://github.com/jdrch/Hardware/blob/master/Dell%20OptiPlex%20390-1%20MT.md#backup)

# 24/7/52 Applications

* [TeamViewer for Windows](https://www.teamviewer.com/en-us/download/windows/)
* [CyberPower PowerPanel Personal Windows](https://www.cyberpowersystems.com/product/software/powerpanel-personal-windows/)
* Resilio Sync Home Pro
* Veeam Agent for Windows FREE
* Veeam Backup & Replication Community Edition
* [CrystalDiskInfo Standard Edition](https://crystalmark.info/en/software/crystaldiskinfo/)
* [PowerToys](https://github.com/microsoft/PowerToys)
* StableBit DrivePool
* OneDrive
* [Windows Security](https://www.microsoft.com/en-us/windows/comprehensive-security)
* Skype
* SyncBackFree

# Peripherals

## Mouse 

[Anker 2.4G Wireless Vertical Ergonomic Optical Mouse](https://www.anker.com/products/variant/anker-24g-wireless-vertical-ergonomic-optical-mouse/A7852011)

## Keyboard

[Dell SK-8185 Black 104 Key Slim Sleek USB Keyboard](https://www.amazon.com/Dell-Keyboard-Computer-Connectors-Compatible/dp/B005OZMBOE)

## UPS

[CyberPower CP1350PFCLCD](https://github.com/jdrch/Hardware/blob/master/UPS.md#battery-backed-up-devices-2)

## Webcam

HP USB

## Fingerprint Reader

[Kensington VeriMark Fingerprint Key](https://www.kensington.com/p/products/security/biometric/verimark-fingerprint-key-fido-u2f-for-universal-2nd-factor-authentication-windows-hello/)

## Speakers

[Dell AX210 USB 2.0 Powered Speaker](https://www.dell.com/support/home/us/en/04/product-support/product/dell-ax210/overview)

# External Monitors

[Dell S2240L](https://www.dell.com/support/home/us/en/04/product-support/product/dell-s2240l/overview)

# Known Hardware Problems

Known hardware problems that are impractical or impossible to fix.

* Onboard SATA 3 Connector(SATA3) does not work