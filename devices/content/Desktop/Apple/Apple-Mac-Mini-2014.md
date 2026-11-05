---
title: "Apple Mac Mini 2014"
tags: ""
bookHidden: true
---

# Apple Mac Mini 2014 

## Device information

### General Info

**Acquired:** 

### Hardware installed

**Motherboard:** Manufacturer \
**CPU:**
**RAM:**  \
**Graphics:**  \
**Storage:**  \
**Connectivity:**  \
**Ports:** \
**OS:** 


### Overview
Device information from `fastfetch`

<details>
<summary>View device information</summary>

```
                             ....              jackr@neutron
              .',:clooo:  .:looooo:.           -------------
           .;looooooooc  .oooooooooo'          OS: Ubuntu 26.04.1 LTS (Resolute Raccoon) x86_64
        .;looooool:,''.  :ooooooooooc          Host: Mac mini (Mid 2014) (1.0)
       ;looool;.         'oooooooooo,          Kernel: Linux 7.0.0-42-generic
      ;clool'             .cooooooc.  ,,       Uptime: 1 day, 22 hours, 28 mins
         ...                ......  .:oo,      Packages: 1185 (dpkg), 3 (snap)
  .;clol:,.                        .loooo'     Shell: bash 5.3.9
 :ooooooooo,                        'ooool     Display (HDP-V104): 4096x2160 in 31", 30 Hz [External]
'ooooooooooo.                        loooo.    Terminal: tmux 3.6
'ooooooooool                         coooo.    CPU: Intel(R) Core(TM) i5-4278U (4) @ 3.10 GHz
 ,loooooooc.                        .loooo.    GPU: Intel Haswell-ULT Integrated Graphics Controller @ 1.10 GHz [Integrated]
   .,;;;'.                          ;ooooc     Memory: 1.08 GiB / 7.13 GiB (15%)
       ...                         ,ooool.     Swap: 277.62 MiB / 4.00 GiB (7%)
    .cooooc.              ..',,'.  .cooo.      Disk (/): 23.68 GiB / 226.53 GiB (10%) - ext4
      ;ooooo:.           ;oooooooc.  :l.       Disk (/mnt/jackr-1tb): 465.83 GiB / 931.47 GiB (50%) - exfat
       .coooooc,..      coooooooooo.           Local IP (enp3s0f0): 146.229.246.244/21
         .:ooooooolc:. .ooooooooooo'           Locale: en_US.UTF-8
           .':loooooo;  ,oooooooooc
               ..';::c'  .;loooo:'


```
</details>



## sbc-bench

<details>
<summary>Results</summary>

```
# Apple Inc. Macmini7,1 1.0 / i5-4278U @ 2.60GHz

Tested with sbc-bench v0.9.72 on Thu, 05 Nov 2026 02:04:15 -0600.

### General information:

    Information courtesy of cpufetch:
    
    Name:                Intel Core i5-4278U
    Microarchitecture:   Haswell
    Technology:          22nm
    Max Frequency:       3.100 GHz
    Cores:               2 cores (4 threads)
    AVX:                 AVX,AVX2
    FMA:                 FMA3
    L1i Size:            32KB (64KB Total)
    L1d Size:            32KB (64KB Total)
    L2 Size:             256KB (512KB Total)
    L3 Size:             3MB
    
    i5-4278U @ 2.60GHz, Kernel: x86_64, Userland: amd64
    
    CPU sysfs topology (clusters, cpufreq members, clockspeeds)
                     cpufreq   min    max
     CPU    cluster  policy   speed  speed   core type
      0        0        0      800    3100   Haswell
      1        0        1      800    3100   Haswell
      2        0        2      800    3100   Haswell
      3        0        3      800    3100   Haswell

7300 KB available RAM

### Policies (performance vs. idle consumption):

Status of performance related policies found below /sys:

    /sys/module/pcie_aspm/parameters/policy: default [performance] powersave powersupersave

### Clockspeeds (idle vs. heated up):

Before at 50.0Â°C:

    cpu0: OPP: 3100, Measured: 3092 

After at 70.0Â°C:

    cpu0: OPP: 3100, Measured: 3089 

### Performance baseline

  * memcpy: 8123.0 MB/s, memchr: 14934.2 MB/s, memset: 17774.5 MB/s
  * 16M latency: 79.28 77.14 80.46 77.45 79.03 80.08 81.83 84.25 
  * 128M latency: 104.0 104.0 99.83 99.77 97.40 99.43 99.60 100.8 
  * 7-zip MIPS (3 consecutive runs): 9050, 9100, 9266 (9140 avg), single-threaded: 3355
  * `aes-256-cbc     414816.25k   479677.72k   493844.05k   498253.48k   498660.69k   499105.79k`
  * `aes-256-cbc     426579.88k   479753.81k   494435.75k   497255.42k   499280.55k   499428.01k`

### PCIe and storage devices:

  * Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter: Speed 2.5GT/s, Width x1, driver in use: wl, 
  * Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe: Speed 2.5GT/s, Width x1, driver in use: tg3, 
  * Broadcom BCM57765/57785 SDXC/MMC Card Reader: Speed 2.5GT/s, Width x1, driver in use: sdhci-pci, 
  * Samsung S4LN058A01[SSUBX] AHCI (Apple slot): Speed 5GT/s (downgraded), Width x2 (downgraded), driver in use: ahci, 
  * 931.5GB "Western Digital SN560E" SSD as /dev/sda [NVMe]: in "SanDisk Corp. Extreme 55AE" (0781:55ae), 0% worn out, 1 error log entries, Driver=uas, 5Gbps (capable of 12Mbps, 480Mbps, 5Gbps, 10Gb/s Symmetric RX SuperSpeedPlus, 10Gb/s Symmetric TX SuperSpeedPlus), drive temp: 27Â°C
  * 233.8GB "Apple APPLE SSD SM0256G" SSD as /dev/sdb: SATA 3.0, 6.0 Gb/s (current: 6.0 Gb/s), drive temp: 28Â°C
  * St N25Q064 8MB SPI NOR flash, drivers in use: spi-nor/intel-spi/lpc_ich

"smartctl -x /dev/sda" could be used to get further information about the reported issues.

### Swap configuration:

  * /swap.img on /dev/mapper/ubuntu--vg-ubuntu--lv: 4.0G (277.5M used)

### Software versions:

  * Ubuntu 26.04.1 LTS (resolute)
  * Compiler: /usr/bin/gcc (Ubuntu 15.2.0-16ubuntu1) 15.2.0 / x86_64-linux-gnu
  * OpenSSL 3.5.5, built on 27 Jan 2026 (Library: OpenSSL 3.5.5 27 Jan 2026)    

### Kernel info:

  * `/proc/cmdline: BOOT_IMAGE=/vmlinuz-7.0.0-42-generic root=/dev/mapper/ubuntu--vg-ubuntu--lv ro crashkernel=2G-4G:320M,4G-32G:512M,32G-64G:1024M,64G-128G:2048M,128G-:4096M`
  * Vulnerability Itlb multihit:             KVM: Mitigation: Split huge pages
  * Vulnerability L1tf:                      Mitigation; PTE Inversion; VMX conditional cache flushes, SMT vulnerable
  * Vulnerability Mds:                       Mitigation; Clear CPU buffers; SMT vulnerable
  * Vulnerability Meltdown:                  Mitigation; PTI
  * Vulnerability Spec store bypass:         Mitigation; Speculative Store Bypass disabled via prctl
  * Vulnerability Spectre v1:                Mitigation; usercopy/swapgs barriers and __user pointer sanitization
  * Vulnerability Srbds:                     Mitigation; Microcode
  * Vulnerability Vmscape:                   Mitigation; IBPB before exit to userspace
  * Kernel 7.0.0-42-generic / CONFIG_HZ=1000

```
</details>

## Geekbench 7
Using Geekbench version `7.0.0`

### CPU

| Single Core | Multi-Core |
| :---------: | :--------: |
| 951 | 1973 |

[Geekbench CPU result link](https://browser.geekbench.com/v7/cpu/805917)



## Maintenance

* (10/24/2026): Cleaned and repasted

## Issues

* 

## Notes

* 



