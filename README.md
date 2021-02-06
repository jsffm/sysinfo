# sysinfo
Shows system and hw info in a linux system

<pre>
gentoo

American Megatrends Inc.
F51
07/29/2020

Gigabyte Technology Co., Ltd.
B450 AORUS M

5.4.38-gentoo

              total        used        free      shared  buff/cache   available
Mem:       16449852      938740    10047764       28704     5463348    15146172
Swap:       1048572           0     1048572

Architecture:                    x86_64
CPU op-mode(s):                  32-bit, 64-bit
Byte Order:                      Little Endian
Address sizes:                   43 bits physical, 48 bits virtual
CPU(s):                          8
On-line CPU(s) list:             0-7
Thread(s) per core:              2
Core(s) per socket:              4
Socket(s):                       1
NUMA node(s):                    1
Vendor ID:                       AuthenticAMD
CPU family:                      23
Model:                           113
Model name:                      AMD Ryzen 3 3100 4-Core Processor
Stepping:                        0
Frequency boost:                 enabled
CPU MHz:                         2194.399
CPU max MHz:                     3600,0000
CPU min MHz:                     2200,0000
BogoMIPS:                        7186.56
Virtualization:                  AMD-V
L1d cache:                       128 KiB
L1i cache:                       128 KiB
L2 cache:                        2 MiB
L3 cache:                        16 MiB
NUMA node0 CPU(s):               0-7
Vulnerability Itlb multihit:     Not affected
Vulnerability L1tf:              Not affected
Vulnerability Mds:               Not affected
Vulnerability Meltdown:          Not affected
Vulnerability Spec store bypass: Mitigation; Speculative Store Bypass disabled via prctl and seccomp
Vulnerability Spectre v1:        Mitigation; usercopy/swapgs barriers and __user pointer sanitization
Vulnerability Spectre v2:        Mitigation; Full AMD retpoline, IBPB conditional, STIBP conditional, RSB filling
Vulnerability Tsx async abort:   Not affected
Flags:                           fpu vme de pse tsc msr pae mce cx8 apic sep mtrr pge mca cmov pat pse36 clflush mmx fxsr sse sse2 ht syscall nx mmxext fxsr_opt pdpe1gb rdtscp lm constant_tsc rep_good nopl nonstop_tsc cpuid extd_apicid aperfmperf pni pclmulqdq monitor ssse3 fma cx16 sse4_1 sse4_2 movbe popcnt aes xsave avx f16c rdrand lahf_lm cmp_legacy svm extapic cr8_legacy abm sse4a misalignsse 3dnowprefetch osvw ibs skinit wdt tce topoext perfctr_core perfctr_nb bpext perfctr_llc mwaitx cpb cat_l3 cdp_l3 hw_pstate sme ssbd mba sev ibpb stibp vmmcall fsgsbase bmi1 avx2 smep bmi2 cqm rdt_a rdseed adx smap clflushopt clwb sha_ni xsaveopt xsavec xgetbv1 xsaves cqm_llc cqm_occup_llc cqm_mbm_total cqm_mbm_local clzero irperf xsaveerptr wbnoinvd arat npt lbrv svm_lock nrip_save tsc_scale vmcb_clean flushbyasid decodeassists pausefilter pfthreshold avic v_vmsave_vmload vgif umip rdpid overflow_recov succor smca

PCI

00:00.0 Host bridge: Advanced Micro Devices, Inc. [AMD] Starship/Matisse Root Complex
00:00.2 IOMMU: Advanced Micro Devices, Inc. [AMD] Starship/Matisse IOMMU
00:01.0 Host bridge: Advanced Micro Devices, Inc. [AMD] Starship/Matisse PCIe Dummy Host Bridge
00:01.3 PCI bridge: Advanced Micro Devices, Inc. [AMD] Starship/Matisse GPP Bridge
00:02.0 Host bridge: Advanced Micro Devices, Inc. [AMD] Starship/Matisse PCIe Dummy Host Bridge
00:03.0 Host bridge: Advanced Micro Devices, Inc. [AMD] Starship/Matisse PCIe Dummy Host Bridge
00:03.1 PCI bridge: Advanced Micro Devices, Inc. [AMD] Starship/Matisse GPP Bridge
00:04.0 Host bridge: Advanced Micro Devices, Inc. [AMD] Starship/Matisse PCIe Dummy Host Bridge
00:05.0 Host bridge: Advanced Micro Devices, Inc. [AMD] Starship/Matisse PCIe Dummy Host Bridge
00:07.0 Host bridge: Advanced Micro Devices, Inc. [AMD] Starship/Matisse PCIe Dummy Host Bridge
00:07.1 PCI bridge: Advanced Micro Devices, Inc. [AMD] Starship/Matisse Internal PCIe GPP Bridge 0 to bus[E:B]
00:08.0 Host bridge: Advanced Micro Devices, Inc. [AMD] Starship/Matisse PCIe Dummy Host Bridge
00:08.1 PCI bridge: Advanced Micro Devices, Inc. [AMD] Starship/Matisse Internal PCIe GPP Bridge 0 to bus[E:B]
00:08.2 PCI bridge: Advanced Micro Devices, Inc. [AMD] Starship/Matisse Internal PCIe GPP Bridge 0 to bus[E:B]
00:08.3 PCI bridge: Advanced Micro Devices, Inc. [AMD] Starship/Matisse Internal PCIe GPP Bridge 0 to bus[E:B]
00:14.0 SMBus: Advanced Micro Devices, Inc. [AMD] FCH SMBus Controller (rev 61)
00:14.3 ISA bridge: Advanced Micro Devices, Inc. [AMD] FCH LPC Bridge (rev 51)
00:18.0 Host bridge: Advanced Micro Devices, Inc. [AMD] Matisse Device 24: Function 0
00:18.1 Host bridge: Advanced Micro Devices, Inc. [AMD] Matisse Device 24: Function 1
00:18.2 Host bridge: Advanced Micro Devices, Inc. [AMD] Matisse Device 24: Function 2
00:18.3 Host bridge: Advanced Micro Devices, Inc. [AMD] Matisse Device 24: Function 3
00:18.4 Host bridge: Advanced Micro Devices, Inc. [AMD] Matisse Device 24: Function 4
00:18.5 Host bridge: Advanced Micro Devices, Inc. [AMD] Matisse Device 24: Function 5
00:18.6 Host bridge: Advanced Micro Devices, Inc. [AMD] Matisse Device 24: Function 6
00:18.7 Host bridge: Advanced Micro Devices, Inc. [AMD] Matisse Device 24: Function 7
01:00.0 USB controller: Advanced Micro Devices, Inc. [AMD] 400 Series Chipset USB 3.1 XHCI Controller (rev 01)
01:00.1 SATA controller: Advanced Micro Devices, Inc. [AMD] 400 Series Chipset SATA Controller (rev 01)
01:00.2 PCI bridge: Advanced Micro Devices, Inc. [AMD] 400 Series Chipset PCIe Bridge (rev 01)
02:00.0 PCI bridge: Advanced Micro Devices, Inc. [AMD] 400 Series Chipset PCIe Port (rev 01)
02:01.0 PCI bridge: Advanced Micro Devices, Inc. [AMD] 400 Series Chipset PCIe Port (rev 01)
02:04.0 PCI bridge: Advanced Micro Devices, Inc. [AMD] 400 Series Chipset PCIe Port (rev 01)
03:00.0 Ethernet controller: Realtek Semiconductor Co., Ltd. RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller (rev 16)
05:00.0 Multimedia video controller: Conexant Systems, Inc. CX23885 PCI Video and Audio Decoder (rev 04)
06:00.0 VGA compatible controller: NVIDIA Corporation GM206 [GeForce GTX 950] (rev a1)
06:00.1 Audio device: NVIDIA Corporation GM206 High Definition Audio Controller (rev a1)
07:00.0 Non-Essential Instrumentation [1300]: Advanced Micro Devices, Inc. [AMD] Starship/Matisse PCIe Dummy Function
08:00.0 Non-Essential Instrumentation [1300]: Advanced Micro Devices, Inc. [AMD] Starship/Matisse Reserved SPP
08:00.1 Encryption controller: Advanced Micro Devices, Inc. [AMD] Starship/Matisse Cryptographic Coprocessor PSPCPP
08:00.3 USB controller: Advanced Micro Devices, Inc. [AMD] Matisse USB 3.0 Host Controller
08:00.4 Audio device: Advanced Micro Devices, Inc. [AMD] Starship/Matisse HD Audio Controller
09:00.0 SATA controller: Advanced Micro Devices, Inc. [AMD] FCH SATA Controller [AHCI mode] (rev 51)
0a:00.0 SATA controller: Advanced Micro Devices, Inc. [AMD] FCH SATA Controller [AHCI mode] (rev 51)

USB

Bus 004 Device 002: ID 2109:0813 VIA Labs, Inc. VL813 Hub
Bus 004 Device 001: ID 1d6b:0003 Linux Foundation 3.0 root hub
Bus 003 Device 003: ID 2109:2813 VIA Labs, Inc. VL813 Hub
Bus 003 Device 002: ID 2040:8265 Hauppauge dualHD
Bus 003 Device 001: ID 1d6b:0002 Linux Foundation 2.0 root hub
Bus 002 Device 001: ID 1d6b:0003 Linux Foundation 3.0 root hub
Bus 001 Device 002: ID 0bc7:0006 X10 Wireless Technology, Inc. Wireless Transceiver (ACPI-compliant)
Bus 001 Device 001: ID 1d6b:0002 Linux Foundation 2.0 root hub

Drives

scsi0  Direct-Access ATA      Model: WDC WD20EZRZ-00Z Rev: 0A80 6.0 Gbps
scsi1  Direct-Access ATA      Model: SAMSUNG HD103SI  Rev: 1113 3.0 Gbps
scsi4  Direct-Access ATA      Model: TOSHIBA MD04ACA6 Rev: FS2A 6.0 Gbps
scsi5  Direct-Access ATA      Model: ST8000AS0002-1NA Rev: AR17 6.0 Gbps
scsi13 CD-ROM        HL-DT-ST Model: DVDROM DH16NS30  Rev: 1.00


DRIVER=nvidia

Nvidia

Model:           GeForce GTX 950
IRQ:             59
GPU UUID:        GPU-0fe61692-133b-3009-ff3b-6ca041a9e841
Video BIOS:      84.06.5e.40.69
Bus Type:        PCIe
DMA Size:        40 bits
DMA Mask:        0xffffffffff
Bus Location:    0000:06:00.0
Device Minor:    0
Blacklisted:     No

DVB

0 cx23885
1 em28xx
2 em28xx

Interrupts

            CPU0       CPU1       CPU2       CPU3       CPU4       CPU5       CPU6       CPU7
   0:        114          0          0          0          0          0          0          0   IO-APIC    2-edge      timer
   1:          0          9          0          0          0          0          0          0   IO-APIC    1-edge      i8042
   8:          0          0          0          0          0         21          0          0   IO-APIC    8-edge      rtc0
   9:          0          0          0          0          0          0          0          0   IO-APIC    9-fasteoi   acpi
  25:          0          0          0          0          0          0          0          0   PCI-MSI 4096-edge      AMD-Vi
  26:          0          0          0          0          0          0          0          0   PCI-MSI 22528-edge      PCIe PME, aerdrv
  27:          0          0          0          0          0          0          0          0   PCI-MSI 51200-edge      PCIe PME, aerdrv
  29:          0          0          0          0          0          0          0          0   PCI-MSI 116736-edge      PCIe PME, aerdrv
  30:          0          0          0          0          0          0          0          0   PCI-MSI 133120-edge      PCIe PME, aerdrv
  31:          0          0          0          0          0          0          0          0   PCI-MSI 135168-edge      PCIe PME, aerdrv
  32:          0          0          0          0          0          0          0          0   PCI-MSI 137216-edge      PCIe PME, aerdrv
  34:          0          0          0          0          0    9732478          0          0   IO-APIC    8-fasteoi   cx23885[0]
  39:          0          0          0          0          0          0     505615          0   PCI-MSI 526336-edge      ahci[0000:01:00.1]
  41:          0          0          0          0          0          0          0          0   PCI-MSI 4718592-edge      ahci[0000:09:00.0]
  43:      19064          0          0          0          0          0          0          0   PCI-MSI 5242880-edge      ahci[0000:0a:00.0]
  44:          0          0       4656          0          0          0          0          0   PCI-MSI 524288-edge      xhci_hcd
  45:          0          0          0          0          0          0          0    9151840   PCI-MSI 1572864-edge      eth0
  47:          0          0          0    4523561          0          0          0          0   PCI-MSI 4200448-edge      xhci_hcd
  48:          0          0          0          0          0          0          0          0   PCI-MSI 4200449-edge      xhci_hcd
  49:          0          0          0          0          0          0          0          0   PCI-MSI 4200450-edge      xhci_hcd
  50:          0          0          0          0          0          0          0          0   PCI-MSI 4200451-edge      xhci_hcd
  51:          0          0          0          0          0          0          0          0   PCI-MSI 4200452-edge      xhci_hcd
  52:          0          0          0          0          0          0          0          0   PCI-MSI 4200453-edge      xhci_hcd
  53:          0          0          0          0          0          0          0          0   PCI-MSI 4200454-edge      xhci_hcd
  54:          0          0          0          0          0          0          0          0   PCI-MSI 4200455-edge      xhci_hcd
  55:          0          0          0          0        178          0          0          0   IO-APIC   31-fasteoi   snd_hda_intel:card0
  57:          0          0          0    1613193          0          0          0          0   PCI-MSI 4202496-edge      snd_hda_intel:card1
  59:          0          0          0          0          0          0    8574476          0   PCI-MSI 3145728-edge      nvidia
 NMI:          0          0          0          0          0          0          0          0   Non-maskable interrupts
 LOC:    5052056    3623245    9982906   12307288    5097743    4037164    8407177   10906973   Local timer interrupts
 SPU:          0          0          0          0          0          0          0          0   Spurious interrupts
 PMI:          0          0          0          0          0          0          0          0   Performance monitoring interrupts
 IWI:    3016379    1708210    4230217    6136544    2142585    2594369    6741585    4554899   IRQ work interrupts
 RTR:          0          0          0          0          0          0          0          0   APIC ICR read retries
 RES:    4284920     880408    4780843    3635808    2153438    1018939    3571477    4772254   Rescheduling interrupts
 CAL:      46914      35434      16312      15209      50028      47615      14929      34682   Function call interrupts
 TLB:     105192     125331      99500     105132     121666     108939      94222     106364   TLB shootdowns
 THR:          0          0          0          0          0          0          0          0   Threshold APIC interrupts
 DFR:          0          0          0          0          0          0          0          0   Deferred Error APIC interrupts
 MCE:          0          0          0          0          0          0          0          0   Machine check exceptions
 MCP:        119        119        119        119        119        119        119        119   Machine check polls
 ERR:         24
 MIS:          0
 PIN:          0          0          0          0          0          0          0          0   Posted-interrupt notification event
 NPI:          0          0          0          0          0          0          0          0   Nested posted-interrupt event
 PIW:          0          0          0          0          0          0          0          0   Posted-interrupt wakeup event
</pre>
