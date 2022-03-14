# Various findings regardning my homelab

## Current Lab (bottom up):

### Rack:
[HP 10622 G2](https://cdn.cnetcontent.com/72/86/7286f4ef-70b7-41c9-b13c-1e88ae3dee7f.pdf)

### UPS:
2x [APC Smart-UPS 1000VA](https://www.apc.com/shop/us/en/products/APC-Smart-UPS-1000VA-USB-Serial-230V/P-SUA1000I)

### File / Application server
Chassis: Supermicro SC836 (actually a Dell Compellent 40 chassis)

PSU: Supermicro [PWS-920P-SQ](https://store.supermicro.com/920w-1u-pws-920p-sq.html)

MOBO: Supermicro [X11SPi-TF](https://www.supermicro.com/en/products/motherboard/x11spi-tf)

CPU: Intel Xeon Platinum 8168 

RAM: 1x Samsung 64G RDIMM

Disks: Various HDD for array bulk storage and HDD and nvme for caching/dockers

OS: UnRAID


### Virtualization server
Chassis: Gutted old SATABEAST chassis (cut in half, removed the power rear part). I just love the looks of that chassis. So i ordered a GPU-mining mobo plate from Amazon och placed the mobo plate in the chassis so I could fix the mobo in the chassis.

PSU: Seasonic Focus Plus 750W

MOBO: ASUS C621E Sage

CPU: 2x Intel Xeon Silver 4112

RAM: 4x Samsung 8GB RDIMM

Disks: 1x nvme for VM storage

OS: UnRAID

![CB Multicore](https://user-images.githubusercontent.com/96058899/158130595-0c2e87b6-a788-4a3d-a18e-256d07225a60.png)
![CB Singlecore](https://user-images.githubusercontent.com/96058899/158130606-421708db-a40a-447b-932d-00af9ab96507.png)
![cpu-z](https://user-images.githubusercontent.com/96058899/158130610-2e5131e0-436c-4e91-85b9-ef1437a17a85.png)
![hwinfo](https://user-images.githubusercontent.com/96058899/158130614-bcf2b6e5-0832-4b6f-ba3c-d5ac6d09c33a.png)
![passmark](https://user-images.githubusercontent.com/96058899/158130616-c1b4737e-a5d6-4d5b-b31b-b44406714750.png)
