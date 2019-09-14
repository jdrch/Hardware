# Model

[Dell XPS 8500 Special Edition](https://www.dell.com/support/home/us/en/19/product-support/product/xps-8500/docs)

# Operating System

[Microsoft Windows 10 Pro Semi-Annual Channel 64-bit](https://docs.microsoft.com/en-us/windows/deployment/update/waas-overview#semi-annual-channel)

# Role(s)

* Main PC
* [Plex Media Server](https://www.plex.tv/media-server-downloads/)
* Offsite backup client

# CPU

[Intel Core i7-3770](https://ark.intel.com/content/www/us/en/ark/products/65719/intel-core-i7-3770-processor-8m-cache-up-to-3-90-ghz.html)

# RAM

32 GB (2 x [Crucial 16GB Kit (2 x 8GB) DDR3L-1600 UDIMM](https://www.crucial.com/usa/en/ct2k102464bd160b))

# Storage

## Boot/OS

[Samsung 860 EVO mSATA 1 TB SSD](https://www.samsung.com/us/computing/memory-storage/solid-state-drives/ssd-860-evo-msata-1tb-mz-m6e1t0bw/) (SATA 3.0, NTFS)

## User [Known Folders](https://docs.microsoft.com/en-us/windows/win32/shell/known-folders)

[HGST Travelstar 7K1000 0J22423 1 TB HDD](https://documents.westerndigital.com/content/dam/doc-library/en_us/assets/public/western-digital/product/hgst/travelstar-7k-series/data-sheet-travelstar-7k1000.pdf) (SATA 3.0, NTFS)

## [StableBit DrivePool](https://stablebit.com/DrivePool)

* [Toshiba MQ01ABD100 1 TB HDD](https://toshiba.semicon-storage.com/content/dam/toshiba-ss/asia-pacific/docs/product/storage/product-manual/cHDD-MQ01ABDxxx-Product-Overview.pdf) (SATA 3.0, NTFS)
* [Toshiba MQ01ABF050 500 GB HDD](https://toshiba.semicon-storage.com/content/dam/toshiba-ss/asia-pacific/docs/product/storage/product-manual/cHDD-MQ01ABFxxx-Product-Overview.pdf) (SATA 2.0, NTFS)
* [Seagate Barracuda 7200.12 ST3500418AS 500 GB HDD](https://www.seagate.com/staticfiles/support/disc/manuals/desktop/Barracuda%207200.12/100529369b.pdf) ([USB 3.1 Gen 1](https://github.com/jdrch/HardwareDetails/blob/master/Dell_XPS_8500_Special_Edition.md#docks), NTFS). Long term plan is to replace Blu-ray drive with this

# Expansion Cards

## Graphics

[AMD Radeon 7870 HD GHz Edition](https://www.techpowerup.com/gpu-specs/radeon-hd-7870-ghz-edition.c339). AMD apparently no longer has a product page for this model

# Optical Disc Drive

LiteOn(?) [PLDS BD-RE DH-8B2SH](https://www.dell.com/support/home/us/en/04/drivers/driversdetails?driverid=wjcwm). Long term plan is to replace this with the [Seagate Barracuda 7200.12 ST3500418AS 500 GB HDD](https://github.com/jdrch/HardwareDetails/blob/master/Dell_XPS_8500_Special_Edition.md#stablebit-drivepool)

There is no product page for it but, per [HWiNFO64](https://www.hwinfo.com/), its features are:

* Can read: CD-R, CD-RW, DVD-R, DVD-RW, DVD+R, DVD+RW, DVD+R DL, BD, BD-RE
* Can write: CD-RW, DVD-R, DVD-RW, DVD+R, DVD+RW, DVD+R DL, BD, BD-RE

# Backup

## Device Backup Target Application

[Veeam Backup & Replication Community Edition](https://www.veeam.com/virtual-machine-backup-solution-free.html) running on [Dell Inspiron 560](https://github.com/jdrch/Hardware/blob/master/Dell%20Inspiron%20560.md)

## Device Backup Source Application

[Veeam Agent for Microsoft Windows FREE](https://www.veeam.com/windows-endpoint-server-backup-free.html)

## Filesystem Versioning

* [Volume Shadow Copy](https://docs.microsoft.com/en-us/windows/win32/vss/volume-shadow-copy-service-overview)
* [ShadowExplorer](https://www.shadowexplorer.com/)

## OS Versioning

[System Restore](https://docs.microsoft.com/en-us/windows/win32/sr/system-restore-reference)

## Offsite Files Backup

* [Duplicati](https://www.duplicati.com/)
* OneDrive for [Office 365 Home](https://www.microsoft.com/en-us/p/office-365-home/cfq7ttc0k5dm)

## Real-time P2P File Sync

[Resilio Sync Home Pro](https://www.resilio.com/individuals/)

# 24/7/52 Applications

* [TeamViewer for Windows](https://www.teamviewer.com/en-us/download/windows/)
* [CyberPower PowerPanel Personal Windows](https://www.cyberpowersystems.com/product/software/powerpanel-personal-windows/)
* Plex Media Server
* Resilio Sync Home Pro
* Veeam Agent for Windows Free
* [CrystalDiskInfo Standard Edition](https://crystalmark.info/en/software/crystaldiskinfo/)
* [PowerToys](https://github.com/microsoft/PowerToys)
* [John's Background Switcher for Windows](https://johnsad.ventures/software/backgroundswitcher/)
* Duplicati
* StableBit DrivePool
* [qBittorrent](https://www.qbittorrent.org)
* [Pushbullet](https://www.pushbullet.com/)
* [AMD Catalyst Control Center](https://www.amd.com/en/support/graphics/amd-radeon-hd/amd-radeon-hd-7000-series/amd-radeon-hd-7870-ghz-edition)
* [Avira Antivirus Pro](https://www.avira.com/en/antivirus-pro)
* [No-IP Dynamic DNS Update Client (DUC) for Windows](https://www.noip.com/download?page=win)
* OneDrive
* Bluetooth Devices
* Windows Security

# Peripherals

## Mouse & Keyboard

[Logitech MK850 Performance](https://www.logitech.com/en-us/product/mk850-wireless-keyboard-mouse-combo)

## Docks

[StarTech USB 3.1 (10Gbps) Dual-Bay Dock for 2.5"/3.5" SATA SSD/HDDs](https://www.startech.com/HDD/Docking/2-bay-usb-3-1-gen-2-sata-dock~SDOCK2U313) - Contains [Seagate Barracuda 7200.12 ST3500418AS 500 GB HDD](https://github.com/jdrch/Hardware/blob/master/Dell%20XPS%208500%20Special%20Edition.md#stablebit-drivepool)

## UPS

[CyberPower CP1500PFCLCD](https://www.cyberpowersystems.com/product/ups/cp1500pfclcd/)

## External Monitors

* Right (Main), 1440p, DisplayPort: [Dell UltraSharp U2713HM](https://www.dell.com/support/home/us/en/04/product-support/product/dell-u2713hm/docs). Monitor HDMI port is connected to [Raspberry Pi 3 Model B+](https://github.com/jdrch/Hardware/blob/master/Raspberry%20Pi%203%20Model%20B+.md)
* Center, 2160p, DisplayPort: [NEC EA275UHD-BK](https://www.necdisplay.com/p/ea275uhd-bk). Monitor HDMI port is connected to Dell OptiPlex 390
* Left, 1200p, DVI-D: [ASUS ProArt PA248Q](https://www.asus.com/us/Monitors/ProArt-PA248Q). Monitor HDMI port is connected to dongle for Samsung Galaxy Note9

## Printers

[HP Deskjet 5650](https://support.hp.com/us-en/product/hp-deskjet-5650-printer-series/304441)

## Scanners

[Epson WorkForce GT-1500](https://epson.com/Support/Scanners/WorkForce-Series/Epson-WorkForce-GT-1500/s/SPT_B11B190011)

## Webcam

[Logitech C922 Pro Stream HD](https://www.logitech.com/en-us/product/c922-pro-stream-webcam)

## Fingerprint Reader

[Kensington VeriMark™ Fingerprint Key](https://www.kensington.com/p/products/security/biometric/verimark-fingerprint-key-fido-u2f-for-universal-2nd-factor-authentication-windows-hello/)

## Speakers

[Logitech Z-2300 2.1 Speaker System](https://support.logi.com/hc/en-us/articles/360024328433)

## Headphones

[Sony MDR-7506](https://pro.sony/ue_US/products/headphones/mdr-7506)
