# Various findings regardning my homelab

## Current Lab (bottom up):

### Rack:
[HP 10622 G2](https://cdn.cnetcontent.com/72/86/7286f4ef-70b7-41c9-b13c-1e88ae3dee7f.pdf)

### UPS:
2x [APC Smart-UPS 1000VA](https://www.apc.com/shop/us/en/products/APC-Smart-UPS-1000VA-USB-Serial-230V/P-SUA1000I) (One is offline and just around for redundancy purposes)

### File / Application server running unRAID
Chassis: [Supermicro SC846](https://www.supermicro.com/products/chassis/4U/846/SC846E1-R900.cfm) (with BPN-SAS2-846EL1 backplane)

PSU: Supermicro [PWS-920P-SQ](https://store.supermicro.com/920w-1u-pws-920p-sq.html)

MOBO: Supermicro [X11SPi-TF](https://www.supermicro.com/en/products/motherboard/x11spi-tf)

CPU: Intel Xeon Platinum 8168 

Cooler: Supermicro 4U

RAM: 1x Samsung 64GB RDIMM

Raid card: LSI 9210-8i Flashed into IT mode PCIe 2 x8

**Disks:**

*Main array:*

5x 8TB (Mostly Seagate and they work damn well!)

2x WD Red 3TB

12x 2TB Hitachi Ultrastar Enterprise SATA 2 HDD

Total 62TB usable


*write cache:*

1x 1TB Kingston KC2500 NVMe SSD (dockers, VMs and fast storage)

2x 2TB Hitachi (Media and bulk)


### Virtualization server
Chassis: Gutted old SATABEAST chassis (cut in half, removed the power rear part). I just love the looks of that chassis. So i ordered a GPU-mining mobo tray from Amazon och placed the mobo tray in the chassis so I could fix the mobo in the chassis.

PSU: Seasonic Focus Plus 750W

MOBO: ASUS C621E Sage

CPU: 2x Intel Xeon Silver 4112

RAM: 4x Samsung 8GB RDIMM

Disks: 1x nvme for VM storage

OS: UnRAID

### Lab server
Chassis: Gutted old SATABEAST chassis (cut in half, removed the power rear part). I just love the looks of that chassis. So i ordered a GPU-mining mobo tray from Amazon och placed the mobo tray in the chassis so I could fix the mobo in the chassis.

PSU: Corsair CV 650

MOBO: AsRock Rack EPC621D8A

CPU: Intel Xeon Platinum P-8124 OEM 240W (see "Xeon Platinum P-8124.md" for some performance numbers)

RAM: 1x Samsung 64GB RDIMM

Disks: 1x SSD for OS

OS: Various

### Unifi USW-16-PoE

### [Intel NUC](https://ark.intel.com/content/www/us/en/ark/products/87740/intel-nuc-kit-nuc5ppyh.html) 

For Tailscale and logserver

### Router: [VILFO](https://www.vilfo.com) for easy VPN management and routing. Runs on OpenWRT
