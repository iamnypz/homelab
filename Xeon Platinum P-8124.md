# Findings regarding the proprietary / OEM (Amazon AWS?) processor called Xeon Platinum P-8124

## Background:
I did the mistake while browsing Ebay and ordered the P-8124 eventhough my motherboard, the Asrock EPC621D8A did not officially support it. What it does support is the other Amazon AWS proprietary/OEM CPU which is called Xeon Platinum 8124m (m= extended memory?)
so i had to find a way to run this bad boy. First i went to Win-raid.com and asked around there and was supplied som modded BIOS but it didn't work out. Then i went to the servethehome forum and was supplied a modded version of the stock 1.6 BIOS, it worked but i have (still) stability issues. I guess it has to do with the CPU not being soldlered to the IHS.


## Benchmarks

### Cinebench R23.200 Multicore score:

![CB Multicore](https://user-images.githubusercontent.com/96058899/158176410-db4e0dc3-a16a-4a5a-99a2-051e677433e4.png)

### Cinebench R23.200 Singlecore score:

![CB Singlecore](https://user-images.githubusercontent.com/96058899/158176413-88083ce3-1d0a-473e-85b4-6228066f99c5.png)

### CPU-Z Info:

![cpu-z](https://user-images.githubusercontent.com/96058899/158176416-b4a29594-3053-46cf-bffa-36ad7d07705b.png)

### HWInfo 64:

![hwinfo](https://user-images.githubusercontent.com/96058899/158176418-61e69c1b-4e5a-485f-9a1c-2c281cff1b9a.png)

### Partial Passmark score with About 18 000 CPU mark score. Compared to Platinum 8124m which has about [22 000 score](https://www.cpubenchmark.net/cpu.php?cpu=Intel+Xeon+Platinum+8124M+%40+3.00GHz&id=3352)

![passmark](https://user-images.githubusercontent.com/96058899/158176420-ec597589-fc97-4513-9ecf-ff5d991a9bcb.png)
