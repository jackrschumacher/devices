---
title: "Dell Optiplex 7060 Micro"
tags: "Desktop"
---

# Dell Optiplex 7060 Micro

## Device information

### General Info
**Acquired:** 8/11/2026

### Hardware installed
**Motherboard:** Dell Inc. 0KYJ8C \
**RAM:** 16 GB SODIMM, 2666 MT/S \
**Graphics:** CoffeeLake-S GT2 [UHD Graphics 630] \
**Storage:** Kingston NV3 500GB M.2 2280 NVMe SSD PCIe Gen 4, 256 GB BTO SATA SSD \
**Connectivity:** Intel Corporation Ethernet Connection (7) I219-LM (rev 10), Intel Corporation Cannon Lake PCH CNVi WiFi (rev 10) \
**Ports:** One USB 3.1 Gen 2 Type-C port with PowerShare (front), One USB 3.1 Gen 1 port with PowerShare (front), Headset port/Universal audio jack port (front), One line-out port (front), Four USB 3.1 Gen 1 ports (one supports,  Smart Power On) (rear), Two DisplayPorts 1.2 (rear), One RJ-45 (10/100/1000) connector (rear) \
**OS:** Ubuntu 26.04 LTS

### Overview
Device information from `fastfetch`

<details>
<summary>View device information</summary>

```
                             ....              jackr@jackr-Optiplex-7060
              .',:clooo:  .:looooo:.           -------------------------
           .;looooooooc  .oooooooooo'          OS: Ubuntu 26.04 LTS (Resolute Raccoon) x86_64
        .;looooool:,''.  :ooooooooooc          Host: OptiPlex 7060
       ;looool;.         'oooooooooo,          Kernel: Linux 7.0.0-30-generic
      ;clool'             .cooooooc.  ,,       Uptime: 6 hours, 39 mins
         ...                ......  .:oo,      Packages: 2169 (dpkg), 22 (snap)
  .;clol:,.                        .loooo'     Shell: bash 5.3.9
 :ooooooooo,                        'ooool     Terminal: /dev/pts/1 10.2p1 Ubuntu-2ubuntu3.5
'ooooooooooo.                        loooo.    CPU: Intel(R) Core(TM) i5-8500T (6) @ 3.50 GHz
'ooooooooool                         coooo.    GPU: Intel UHD Graphics 630 @ 1.10 GHz [Integrated]
 ,loooooooc.                        .loooo.    Memory: 1.22 GiB / 14.91 GiB (8%)
   .,;;;'.                          ;ooooc     Swap: 0 B / 4.00 GiB (0%)
       ...                         ,ooool.     Disk (/): 25.43 GiB / 456.35 GiB (6%) - ext4
    .cooooc.              ..',,'.  .cooo.      Disk (/mnt/storage): 1.52 GiB / 233.67 GiB (1%) - ext4
      ;ooooo:.           ;oooooooc.  :l.       Local IP (eno2): 146.229.244.147/21
       .coooooc,..      coooooooooo.           Locale: en_US.UTF-8
         .:ooooooolc:. .ooooooooooo'
           .':loooooo;  ,oooooooooc
               ..';::c'  .;loooo:'


```
</details>



## sbc-bench

<details>
<summary>Results</summary>

```
# Dell Inc. OptiPlex 7060  / i5-8500T @ 2.10GHz

Tested with sbc-bench v0.9.72 on Sat, 29 Aug 2026 14:15:11 -0500.

### General information:

    Information courtesy of cpufetch:
    
    Name:                Intel Core i5-8500T
    Microarchitecture:   Coffee Lake
    Technology:          14nm
    Max Frequency:       3.500 GHz
    Cores:               6 cores
    AVX:                 AVX,AVX2
    FMA:                 FMA3
    L1i Size:            32KB (192KB Total)
    L1d Size:            32KB (192KB Total)
    L2 Size:             256KB (1.5MB Total)
    L3 Size:             9MB
    
    i5-8500T @ 2.10GHz, Kernel: x86_64, Userland: amd64
    
    CPU sysfs topology (clusters, cpufreq members, clockspeeds)
                     cpufreq   min    max
     CPU    cluster  policy   speed  speed   core type
      0        0        0      800    3500   Coffee Lake
      1        0        1      800    3500   Coffee Lake
      2        0        2      800    3500   Coffee Lake
      3        0        3      800    3500   Coffee Lake
      4        0        4      800    3500   Coffee Lake
      5        0        5      800    3500   Coffee Lake

15271 KB available RAM

### Policies (performance vs. idle consumption):

Status of performance related policies found below /sys:

    /sys/module/pcie_aspm/parameters/policy: [default] performance powersave powersupersave

### Clockspeeds (idle vs. heated up):

Before at 45.0°C:

    cpu0: OPP: 3500, Measured: 3460      (-1.1%)

After at 65.0°C:

    cpu0: OPP: 3500, Measured: 3454      (-1.3%)

### Performance baseline

  * memcpy: 8294.9 MB/s, memchr: 8939.2 MB/s, memset: 12673.2 MB/s
  * 16M latency: 60.37 53.03 53.93 55.45 55.55 58.22 63.21 62.56 
  * 128M latency: 79.88 81.86 81.90 78.28 79.14 80.03 81.65 85.93 
  * 7-zip MIPS (3 consecutive runs): 18923, 18908, 19480 (19100 avg), single-threaded: 3509
  * `aes-256-cbc     708477.93k   904886.76k   919933.27k   930003.63k   945954.82k   931348.48k`
  * `aes-256-cbc     724460.61k   880769.92k   880596.82k   933504.34k   938874.20k   945198.42k`

### PCIe and storage devices:

  * Intel CoffeeLake-S GT2 [UHD Graphics 630] (Onboard - Video): driver in use: i915
  * Intel 300/C240 Series Chipset Family USB 3.1 xHCI (Onboard - Other): driver in use: xhci_hcd
  * Intel 300/C240 Series Chipset Family CNVi Wi-Fi (Onboard - Ethernet): driver in use: iwlwifi
  * Intel 300/C240 Series Chipset Family Keyboard and Text (KT) Redirection (Onboard - Other): driver in use: serial
  * Intel 300/C240 Series Chipset Family SATA (AHCI) (Onboard - SATA): driver in use: ahci
  * Intel Ethernet Connection (7) I219-LM (Onboard - Ethernet): driver in use: e1000e
  * 465.8GB "KINGSTON SNV3S500G" SSD as /dev/nvme0: Speed 8GT/s (downgraded), Width x4, 0% worn out, drive temp: 36°C, ASPM L1 Enabled; RCB 64 bytes, LnkDisable- CommClk+ PCI-PM_L1.2- PCI-PM_L1.1- ASPM_L1.2- ASPM_L1.1- L1_PM_Substates-  PCI-PM_L1.2- PCI-PM_L1.1- ASPM_L1.2- ASPM_L1.1-  
  * 238.5GB "SSD 256GB" SSD as /dev/sda: SATA 3.2, 6.0 Gb/s (current: 6.0 Gb/s), 0% worn out, drive temp: 40°C
  * Gigadevice GD25Q256 32MB SPI NOR flash, drivers in use: spi-nor/intel-spi

### Swap configuration:

  * /swap.img on /dev/nvme0n1p2: 4.0G (0K used)

### Software versions:

  * Ubuntu 26.04.1 LTS (resolute)
  * Compiler: /usr/bin/gcc (Ubuntu 15.2.0-16ubuntu1) 15.2.0 / x86_64-linux-gnu
  * OpenSSL 3.5.5, built on 27 Jan 2026 (Library: OpenSSL 3.5.5 27 Jan 2026)    

### Kernel info:

  * `/proc/cmdline: BOOT_IMAGE=/boot/vmlinuz-7.0.0-30-generic root=UUID=70814f1e-575b-4530-b9a5-e83f78c51dc7 ro quiet splash crashkernel=2G-4G:320M,4G-32G:512M,32G-64G:1024M,64G-128G:2048M,128G-:4096M`
  * Vulnerability Gather data sampling:      Vulnerable
  * Vulnerability Itlb multihit:             KVM: Mitigation: Split huge pages
  * Vulnerability L1tf:                      Mitigation; PTE Inversion; VMX conditional cache flushes, SMT disabled
  * Vulnerability Mds:                       Mitigation; Clear CPU buffers; SMT disabled
  * Vulnerability Meltdown:                  Mitigation; PTI
  * Vulnerability Mmio stale data:           Mitigation; Clear CPU buffers; SMT disabled
  * Vulnerability Retbleed:                  Mitigation; IBRS
  * Vulnerability Spec store bypass:         Mitigation; Speculative Store Bypass disabled via prctl
  * Vulnerability Spectre v1:                Mitigation; usercopy/swapgs barriers and __user pointer sanitization
  * Vulnerability Srbds:                     Mitigation; Microcode
  * Vulnerability Tsx async abort:           Mitigation; TSX disabled
  * Vulnerability Vmscape:                   Mitigation; IBPB before exit to userspace
  * Kernel 7.0.0-30-generic / CONFIG_HZ=1000
```
</details>

## Geekbench 7
Using Geekbench version `7.0.0`

### CPU

| Single Core | Multi-Core |
| :---------: | :--------: |
| 1227 | 4379 |

[Geekbench CPU result link](https://browser.geekbench.com/v7/cpu/233506)

### GPU

| Backend API | Compute Score |
| :---------: | :--------: |
| OpenCL | [4218](https://browser.geekbench.com/v7/gpu/113507) |
| Vulkan | [4028](https://browser.geekbench.com/v7/gpu/113541) |



## Maintenance

* (8/18) Installed Kingston NV3 500GB M.2 2280 NVMe SSD
* (8/20) Installed [copper heatsink](https://www.amazon.com/dp/B0CWNLNQY1?ref=ppx_yo2ov_dt_b_fed_asin_title) for NVMe drive

## Issues

* 

## Notes

* [Graphics Drivers install and permissions](https://gist.github.com/jackrschumacher/97a2b93dbf785f664bfe58ad29c270f0)

