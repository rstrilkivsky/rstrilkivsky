[    0.000000] Booting Linux on physical CPU 0x0
[    0.000000] Linux version 3.14.0-xilinx-g16220c3 (lzq@armdev2) (gcc version 4.8.3 20140320 (prerelease) (Sourcery CodeBench Lite 2014.05-23) ) #83 SMP PREEMPT Thu Jul 12 11:42:53 CST 2018
[    0.000000] CPU: ARMv7 Processor [413fc090] revision 0 (ARMv7), cr=18c5387d
[    0.000000] CPU: PIPT / VIPT nonaliasing data cache, VIPT aliasing instruction cache
[    0.000000] Machine model: Xilinx Zynq
[    0.000000] cma: CMA: reserved 128 MiB at 27800000
[    0.000000] Memory policy: Data cache writealloc
[    0.000000] On node 0 totalpages: 258048
[    0.000000] free_area_init_node: node 0, pgdat c074ac00, node_mem_map e6fd8000
[    0.000000]   Normal zone: 1520 pages used for memmap
[    0.000000]   Normal zone: 0 pages reserved
[    0.000000]   Normal zone: 194560 pages, LIFO batch:31
[    0.000000]   HighMem zone: 496 pages used for memmap
[    0.000000]   HighMem zone: 63488 pages, LIFO batch:15
[    0.000000] PERCPU: Embedded 8 pages/cpu @e6fc0000 s9088 r8192 d15488 u32768
[    0.000000] pcpu-alloc: s9088 r8192 d15488 u32768 alloc=8*4096
[    0.000000] pcpu-alloc: [0] 0 [0] 1 
[    0.000000] Built 1 zonelists in Zone order, mobility grouping on.  Total pages: 256528
[    0.000000] Kernel command line: noinitrd mem=1008M console=ttyPS0,115200 root=ubi0:rootfs ubi.mtd=1 rootfstype=ubifs rw rootwait
[    0.000000] PID hash table entries: 4096 (order: 2, 16384 bytes)
[    0.000000] Dentry cache hash table entries: 131072 (order: 7, 524288 bytes)
[    0.000000] Inode-cache hash table entries: 65536 (order: 6, 262144 bytes)
[    0.000000] Memory: 884108K/1032192K available (5057K kernel code, 284K rwdata, 1928K rodata, 204K init, 258K bss, 148084K reserved, 253952K highmem)
[    0.000000] Virtual kernel memory layout:
[    0.000000]     vector  : 0xffff0000 - 0xffff1000   (   4 kB)
[    0.000000]     fixmap  : 0xfff00000 - 0xfffe0000   ( 896 kB)
[    0.000000]     vmalloc : 0xf0000000 - 0xff000000   ( 240 MB)
[    0.000000]     lowmem  : 0xc0000000 - 0xef800000   ( 760 MB)
[    0.000000]     pkmap   : 0xbfe00000 - 0xc0000000   (   2 MB)
[    0.000000]     modules : 0xbf000000 - 0xbfe00000   (  14 MB)
[    0.000000]       .text : 0xc0008000 - 0xc06da8ac   (6987 kB)
[    0.000000]       .init : 0xc06db000 - 0xc070e380   ( 205 kB)
[    0.000000]       .data : 0xc0710000 - 0xc0757138   ( 285 kB)
[    0.000000]        .bss : 0xc0757144 - 0xc0797bfc   ( 259 kB)
[    0.000000] Preemptible hierarchical RCU implementation.
[    0.000000] 	Dump stacks of tasks blocking RCU-preempt GP.
[    0.000000] 	RCU restricting CPUs from NR_CPUS=4 to nr_cpu_ids=2.
[    0.000000] RCU: Adjusting geometry for rcu_fanout_leaf=16, nr_cpu_ids=2
[    0.000000] NR_IRQS:16 nr_irqs:16 16
[    0.000000] ps7-slcr mapped to f0004000
[    0.000000] zynq_clock_init: clkc starts at f0004100
[    0.000000] Zynq clock init
[    0.000014] sched_clock: 64 bits at 333MHz, resolution 3ns, wraps every 3298534883328ns
[    0.000292] ps7-ttc #0 at f0006000, irq=43
[    0.000594] Console: colour dummy device 80x30
[    0.000630] Calibrating delay loop... 1325.46 BogoMIPS (lpj=6627328)
[    0.040197] pid_max: default: 32768 minimum: 301
[    0.040406] Mount-cache hash table entries: 2048 (order: 1, 8192 bytes)
[    0.040429] Mountpoint-cache hash table entries: 2048 (order: 1, 8192 bytes)
[    0.042577] CPU: Testing write buffer coherency: ok
[    0.042896] CPU0: thread -1, cpu 0, socket 0, mpidr 80000000
[    0.042951] Setting up static identity map for 0x4cb118 - 0x4cb170
[    0.043171] L310 cache controller enabled
[    0.043191] l2x0: 8 ways, CACHE_ID 0x410000c8, AUX_CTRL 0x72760000, Cache size: 512 kB
[    0.120989] CPU1: Booted secondary processor
[    0.210219] CPU1: thread -1, cpu 1, socket 0, mpidr 80000001
[    0.210348] Brought up 2 CPUs
[    0.210367] SMP: Total of 2 processors activated.
[    0.210376] CPU: All CPU(s) started in SVC mode.
[    0.211033] devtmpfs: initialized
[    0.213446] VFP support v0.3: implementor 41 architecture 3 part 30 variant 9 rev 4
[    0.214638] regulator-dummy: no parameters
[    0.221993] NET: Registered protocol family 16
[    0.224162] DMA: preallocated 256 KiB pool for atomic coherent allocations
[    0.226415] cpuidle: using governor ladder
[    0.226428] cpuidle: using governor menu
[    0.233750] syscon f8000000.ps7-slcr: regmap [mem 0xf8000000-0xf8000fff] registered
[    0.235252] hw-breakpoint: found 5 (+1 reserved) breakpoint and 1 watchpoint registers.
[    0.235265] hw-breakpoint: maximum watchpoint size is 4 bytes.
[    0.235377] zynq-ocm f800c000.ps7-ocmc: ZYNQ OCM pool: 256 KiB @ 0xf0080000
[    0.257114] bio: create slab <bio-0> at 0
[    0.258503] vgaarb: loaded
[    0.259205] SCSI subsystem initialized
[    0.260069] usbcore: registered new interface driver usbfs
[    0.260851] usbcore: registered new interface driver hub
[    0.261374] usbcore: registered new device driver usb
[    0.261907] media: Linux media interface: v0.10
[    0.262063] Linux video capture interface: v2.00
[    0.262300] pps_core: LinuxPPS API ver. 1 registered
[    0.262311] pps_core: Software ver. 5.3.6 - Copyright 2005-2007 Rodolfo Giometti <giometti@linux.it>
[    0.262431] PTP clock support registered
[    0.262776] EDAC MC: Ver: 3.0.0
[    0.263968] Advanced Linux Sound Architecture Driver Initialized.
[    0.266683] DMA-API: preallocated 4096 debug entries
[    0.266696] DMA-API: debugging enabled by kernel config
[    0.266762] Switched to clocksource arm_global_timer
[    0.286839] NET: Registered protocol family 2
[    0.287493] TCP established hash table entries: 8192 (order: 3, 32768 bytes)
[    0.287588] TCP bind hash table entries: 8192 (order: 4, 65536 bytes)
[    0.287747] TCP: Hash tables configured (established 8192 bind 8192)
[    0.287806] TCP: reno registered
[    0.287824] UDP hash table entries: 512 (order: 2, 16384 bytes)
[    0.287873] UDP-Lite hash table entries: 512 (order: 2, 16384 bytes)
[    0.288128] NET: Registered protocol family 1
[    0.288485] RPC: Registered named UNIX socket transport module.
[    0.288498] RPC: Registered udp transport module.
[    0.288506] RPC: Registered tcp transport module.
[    0.288513] RPC: Registered tcp NFSv4.1 backchannel transport module.
[    0.288525] PCI: CLS 0 bytes, default 64
[    0.288949] hw perfevents: enabled with ARMv7 Cortex-A9 PMU driver, 7 counters available
[    0.290941] futex hash table entries: 512 (order: 3, 32768 bytes)
[    0.292280] bounce pool size: 64 pages
[    0.293149] jffs2: version 2.2. (NAND) © 2001-2006 Red Hat, Inc.
[    0.293353] msgmni has been set to 1486
[    0.294109] io scheduler noop registered
[    0.294121] io scheduler deadline registered
[    0.294161] io scheduler cfq registered (default)
[    0.305883] dma-pl330 f8003000.ps7-dma: Loaded driver for PL330 DMAC-2364208
[    0.305904] dma-pl330 f8003000.ps7-dma: 	DBUFF-128x8bytes Num_Chans-8 Num_Peri-4 Num_Events-16
[    0.430418] e0001000.serial: ttyPS0 at MMIO 0xe0001000 (irq = 82, base_baud = 3124999) is a xuartps
[    1.002542] console [ttyPS0] enabled
[    1.006823] xdevcfg f8007000.ps7-dev-cfg: ioremap 0xf8007000 to f0068000
[    1.014412] [drm] Initialized drm 1.1.0 20060810
[    1.031472] brd: module loaded
[    1.040858] loop: module loaded
[    1.050279] e1000e: Intel(R) PRO/1000 Network Driver - 2.3.2-k
[    1.056028] e1000e: Copyright(c) 1999 - 2013 Intel Corporation.
[    1.063912] libphy: XEMACPS mii bus: probed
[    1.068310] ------------- phy_id = 0x3625e62
[    1.073019] xemacps e000b000.ps7-ethernet: pdev->id -1, baseaddr 0xe000b000, irq 54
[    1.081789] ehci_hcd: USB 2.0 'Enhanced' Host Controller (EHCI) Driver
[    1.088438] ehci-pci: EHCI PCI platform driver
[    1.095642] zynq-dr e0002000.ps7-usb: Unable to init USB phy, missing?
[    1.102571] usbcore: registered new interface driver usb-storage
[    1.109435] mousedev: PS/2 mouse device common for all mice
[    1.115524] i2c /dev entries driver
[    1.122460] zynq-edac f8006000.ps7-ddrc: ecc not enabled
[    1.127985] cpufreq_cpu0: failed to get cpu0 regulator: -19
[    1.133859] Xilinx Zynq CpuIdle Driver started
[    1.138742] sdhci: Secure Digital Host Controller Interface driver
[    1.144833] sdhci: Copyright(c) Pierre Ossman
[    1.149199] sdhci-pltfm: SDHCI platform and OF driver helper
[    1.155977] mmc0: no vqmmc regulator found
[    1.160087] mmc0: no vmmc regulator found
[    1.196782] mmc0: SDHCI controller on e0100000.ps7-sdio [e0100000.ps7-sdio] using ADMA
[    1.205449] usbcore: registered new interface driver usbhid
[    1.210960] usbhid: USB HID core driver
[    1.215670] nand: device found, Manufacturer ID: 0x2c, Chip ID: 0xda
[    1.221968] nand: Micron MT29F2G08ABAEAWP
[    1.225934] nand: 256MiB, SLC, page size: 2048, OOB size: 64
[    1.231877] Bad block table found at page 131008, version 0x01
[    1.238102] Bad block table found at page 130944, version 0x01
[    1.244147] 3 ofpart partitions found on MTD device pl353-nand
[    1.249934] Creating 3 MTD partitions on "pl353-nand":
[    1.255025] 0x000000000000-0x000002000000 : "BOOT.bin-env-dts-kernel"
[    1.263064] 0x000002000000-0x00000b000000 : "angstram-rootfs"
[    1.270386] 0x00000b000000-0x000010000000 : "upgrade-rootfs"
[    1.281130] TCP: cubic registered
[    1.284368] NET: Registered protocol family 17
[    1.289069] Registering SWP/SWPB emulation handler
[    1.294969] regulator-dummy: disabling
[    1.299290] UBI: attaching mtd1 to ubi0
[    1.823730] UBI: scanning is finished
[    1.835290] UBI: attached mtd1 (name "angstram-rootfs", size 144 MiB) to ubi0
[    1.842370] UBI: PEB size: 131072 bytes (128 KiB), LEB size: 126976 bytes
[    1.849132] UBI: min./max. I/O unit sizes: 2048/2048, sub-page size 2048
[    1.855797] UBI: VID header offset: 2048 (aligned 2048), data offset: 4096
[    1.862675] UBI: good PEBs: 1152, bad PEBs: 0, corrupted PEBs: 0
[    1.868656] UBI: user volume: 1, internal volumes: 1, max. volumes count: 128
[    1.875763] UBI: max/mean erase counter: 202/101, WL threshold: 4096, image sequence number: 289757055
[    1.885066] UBI: available PEBs: 0, total reserved PEBs: 1152, PEBs reserved for bad PEB handling: 40
[    1.894282] UBI: background thread "ubi_bgt0d" started, PID 1084
[    1.894287] drivers/rtc/hctosys.c: unable to open rtc device (rtc0)
[    1.898236] ALSA device list:
[    1.898239]   No soundcards found.
[    1.914588] UBIFS: background thread "ubifs_bgt0_0" started, PID 1086
[    1.943567] UBIFS: recovery needed
[    2.012529] UBIFS: recovery completed
[    2.016193] UBIFS: mounted UBI device 0, volume 0, name "rootfs"
[    2.022175] UBIFS: LEB size: 126976 bytes (124 KiB), min./max. I/O unit sizes: 2048 bytes/2048 bytes
[    2.031250] UBIFS: FS size: 128626688 bytes (122 MiB, 1013 LEBs), journal size 9023488 bytes (8 MiB, 72 LEBs)
[    2.041137] UBIFS: reserved for root: 0 bytes (0 KiB)
[    2.046166] UBIFS: media format: w4/r0 (latest is w4/r0), UUID CF42856B-0B2A-4660-B9E9-7A07F12B83A2, small LPT model
[    2.057243] VFS: Mounted root (ubifs filesystem) on device 0:11.
[    2.064174] devtmpfs: mounted
[    2.067305] Freeing unused kernel memory: 204K (c06db000 - c070e000)
[    2.904067] random: dd urandom read with 1 bits of entropy available
[    3.316784] 
[    3.316784] bcm54xx_config_init
[    4.406800] 
[    4.406800] bcm54xx_config_init
[    8.407631] xemacps e000b000.ps7-ethernet: Set clk to 124999998 Hz
[    8.413739] xemacps e000b000.ps7-ethernet: link up (1000/FULL)
[   32.174960] In axi fpga driver!
[   32.178046] request_mem_region OK!
[   32.181421] AXI fpga dev virtual address is 0xf0200000
[   32.186545] *base_vir_addr = 0xc51e
[   32.201293] In fpga mem driver!
[   32.204623] request_mem_region OK!
[   32.208249] fpga mem virtual address is 0xf3000000
[   32.986189] 
[   32.986189] bcm54xx_config_init
[   34.066058] 
[   34.066058] bcm54xx_config_init
[   38.066488] xemacps e000b000.ps7-ethernet: Set clk to 124999998 Hz
[   38.072594] xemacps e000b000.ps7-ethernet: link up (1000/FULL)
[  488.075461] random: nonblocking pool is initialized
log_level = 4
This is XILINX board. Totalram:       1039753216
Detect 1GB control board of XILINX
mmap axi_fpga_addr = 0xb6f13000
axi_fpga_addr data = 0xc51e
mmap fpga_mem_addr = 0xb5d0c000
forceFreq=-1 forceFlag=0
min work minertest[0]:912


DETECT HW version=0000c51e
miner ID : 8038242e4b590854
Miner Type = S9
AsicType = 1387
real AsicNum = 63
use critical mode to search freq...
get PLUG ON=0x000000e0
Find hashboard on Chain[5]
Find hashboard on Chain[6]
Find hashboard on Chain[7]
Check chain[5] PIC fw version=0x03
Check chain[6] PIC fw version=0x03
Check chain[7] PIC fw version=0x03
read pic freq and badcore num...
chain[5]: [63:22] [63:5] [63:24] [63:33] [63:66] [63:72] [63:255] [63:255]
has freq in PIC, will disable freq setting.
chain[5] has freq in PIC and will jump over...
Chain[5] has core num in PIC
Chain[5] ASIC[29] has core num=6
Check chain[5] PIC fw version=0x03
read pic freq and badcore num...
chain[6]: [63:22] [63:5] [63:24] [63:33] [63:68] [63:22] [63:255] [63:255]
has freq in PIC, will disable freq setting.
chain[6] has freq in PIC and will jump over...
Chain[6] has core num in PIC
Chain[6] ASIC[16] has core num=10
Chain[6] ASIC[29] has core num=1
Chain[6] ASIC[30] has core num=1
Chain[6] ASIC[52] has core num=1
Chain[6] ASIC[53] has core num=1
Check chain[6] PIC fw version=0x03
read pic freq and badcore num...
chain[7]: [63:22] [63:5] [63:24] [63:33] [63:68] [63:39] [63:255] [63:255]
has freq in PIC, will disable freq setting.
chain[7] has freq in PIC and will jump over...
Chain[7] has core num in PIC
Chain[7] ASIC[6] has core num=1
Chain[7] ASIC[7] has core num=1
Chain[7] ASIC[40] has core num=1
Chain[7] ASIC[43] has core num=4
Check chain[7] PIC fw version=0x03
get PIC voltage=142 on chain[5], value=860
get PIC voltage=142 on chain[6], value=860
get PIC voltage=142 on chain[7], value=860
chain[5] temp offset record: 62,-5,32,-5,0,0,0,0
chain[5] temp chip I2C addr=0x98
chain[6] temp offset record: 62,-4,32,-5,0,0,0,0
chain[6] temp chip I2C addr=0x98
chain[7] temp offset record: 62,-3,32,-4,0,0,0,0
chain[7] temp chip I2C addr=0x98
total_exist_chain_num = 3
CRC error counter=0
set command mode to VIL

--- check asic number
After Get ASIC NUM CRC error counter=0
set_baud=0
The min freq=700
set real timeout 52, need sleep=379392
After TEST CRC error counter=0
search freq for 1 times, completed chain = 3, total chain num = 3 
single_board_frq_tuning enter
min_rate, des_rate, fix_volt:13800, 14000, 880
force_freq not set, don't need tuning
restart Miner chance num=2
waiting for receive_func to exit!
waiting for pic heart to exit!
bmminer not found= 1840 root       0:00 grep bmminer

bmminer not found, restart bmminer ...
This is user mode for mining
Detect 1GB control board of XILINX
Miner Type = S9
Miner compile time: Mon Jul 1 14:41:32 CST 2019 type: Antminer S9
miner ID : 8038242e4b590854
Checking fans...
get fan[4] speed=10680
get fan[4] speed=10680
get fan[5] speed=8520
get fan[4] speed=10680
get fan[5] speed=8520
get fan[4] speed=10680
get fan[5] speed=8520
chain[5]: [63:22] [63:5] [63:24] [63:33] [63:66] [63:72] [63:255] [63:255]
last_freq: 0x00 0x7d 0x0f 0x49 0x0b 0x4c 0x03 0x4c 0x00 0x49 0x02 0x4c 0x00 0x4c 0x04 0x49 0x01 0x4c 0x00 0x4c 0x09 0x49 0x08 0x4c 0x06 0x4c 0x0e 0x4a 0x02 0x4c 0x0f 0x4c 0x08 0x4b 0x02 0x4c 0x05 0x44 0x08 0x4b 0x23 0x4a 0x03 0x4c 0x0f 0x4b 0x23 0x4b 0x00 0x4b 0x00 0x4b 0x00 0x4c 0x00 0x4c 0x00 0x4b 0x00 0x4c 0x00 0x30 0x00 0x4b 0x00 0x4c 0x00 0x4c 0x00 0x46 0x00 0x4c 0x00 0x46 0x00 0x4b 0x00 0x4c 0x00 0x34 0x00 0x4b 0x00 0x4c 0x00 0x4c 0x00 0x4c 0x00 0x4c 0x00 0x43 0x00 0x4b 0x00 0x4b 0x00 0x4c 0x00 0x4c 0x00 0x4c 0x00 0x4c 0x00 0x4a 0x00 0x4a 0x00 0x4c 0x00 0x4c 0x00 0x4c 0x00 0x4c 0x00 0x4c 0x00 0x4c 0x00 0x4c 0x00 0x4c 0x00 0x4c 0x00 0x49 
Chain[J6] has backup chain_voltage=880
Chain[J6] test patten OK temp=63
scan based on domain
Check chain[5] PIC fw version=0x03
chain[6]: [63:22] [63:5] [63:24] [63:33] [63:68] [63:22] [63:255] [63:255]
last_freq: 0x00 0x7d 0x0f 0x45 0x0c 0x36 0x03 0x46 0x00 0x45 0x02 0x39 0x00 0x46 0x04 0x42 0x01 0x42 0x00 0x46 0x09 0x46 0x08 0x46 0x06 0x46 0x0e 0x46 0x02 0x46 0x0f 0x46 0x08 0x46 0x02 0x30 0x05 0x46 0x08 0x46 0x23 0x46 0x03 0x3c 0x0b 0x46 0x23 0x46 0x00 0x46 0x00 0x46 0x00 0x46 0x00 0x46 0x00 0x46 0x00 0x46 0x00 0x46 0x00 0x46 0x00 0x46 0x00 0x46 0x00 0x46 0x00 0x46 0x00 0x46 0x00 0x46 0x00 0x46 0x00 0x46 0x00 0x46 0x00 0x46 0x00 0x46 0x00 0x46 0x00 0x46 0x00 0x3f 0x00 0x46 0x00 0x46 0x00 0x46 0x00 0x44 0x00 0x46 0x00 0x46 0x00 0x46 0x00 0x3d 0x00 0x46 0x00 0x46 0x00 0x46 0x00 0x46 0x00 0x46 0x00 0x46 0x00 0x45 0x00 0x46 0x00 0x46 0x00 0x46 
Chain[J7] has backup chain_voltage=880
Chain[J7] test patten OK temp=59
scan based on domain
Check chain[6] PIC fw version=0x03
chain[7]: [63:22] [63:5] [63:24] [63:33] [63:68] [63:39] [63:255] [63:255]
last_freq: 0x00 0x7d 0x0f 0x46 0x0d 0x46 0x03 0x48 0x03 0x46 0x02 0x46 0x00 0x48 0x04 0x46 0x01 0x46 0x00 0x48 0x09 0x46 0x08 0x46 0x06 0x48 0x0e 0x46 0x02 0x46 0x0f 0x48 0x08 0x46 0x02 0x42 0x05 0x48 0x08 0x42 0x23 0x46 0x03 0x48 0x0b 0x46 0x23 0x39 0x00 0x48 0x00 0x46 0x00 0x46 0x00 0x3a 0x00 0x46 0x00 0x3d 0x00 0x47 0x00 0x46 0x00 0x3a 0x00 0x48 0x00 0x3d 0x00 0x46 0x00 0x48 0x00 0x46 0x00 0x46 0x00 0x46 0x00 0x46 0x00 0x47 0x00 0x35 0x00 0x46 0x00 0x33 0x00 0x48 0x00 0x46 0x00 0x47 0x00 0x48 0x00 0x46 0x00 0x47 0x00 0x3e 0x00 0x46 0x00 0x47 0x00 0x48 0x00 0x46 0x00 0x47 0x00 0x48 0x00 0x46 0x00 0x48 0x00 0x48 0x00 0x46 0x00 0x48 0x00 0x48 
Chain[J8] has backup chain_voltage=880
Chain[J8] test patten OK temp=59
scan based on domain
Check chain[7] PIC fw version=0x03
total_exist_chain_num = 3
Chain[J6] original vol value=880 adjusted vol value:860
Chain[J6] orignal chain_voltage_pic=142 value=860
Chain[J6] original chain_voltage_value=880 adjusted chain_voltage_value:860, value=860
Chain[J6] Aisc[00] original freq=643 adjusted freq:612
Chain[J6] Aisc[01] original freq=662 adjusted freq:631
Chain[J6] Aisc[02] original freq=662 adjusted freq:631
Chain[J6] Aisc[03] original freq=643 adjusted freq:612
Chain[J6] Aisc[04] original freq=662 adjusted freq:631
Chain[J6] Aisc[05] original freq=662 adjusted freq:631
Chain[J6] Aisc[06] original freq=643 adjusted freq:612
Chain[J6] Aisc[07] original freq=662 adjusted freq:631
Chain[J6] Aisc[08] original freq=662 adjusted freq:631
Chain[J6] Aisc[09] original freq=643 adjusted freq:612
Chain[J6] Aisc[10] original freq=662 adjusted freq:631
Chain[J6] Aisc[11] original freq=662 adjusted freq:631
Chain[J6] Aisc[12] original freq=650 adjusted freq:618
Chain[J6] Aisc[13] original freq=662 adjusted freq:631
Chain[J6] Aisc[14] original freq=662 adjusted freq:631
Chain[J6] Aisc[15] original freq=656 adjusted freq:625
Chain[J6] Aisc[16] original freq=662 adjusted freq:631
Chain[J6] Aisc[17] original freq=612 adjusted freq:581
Chain[J6] Aisc[18] original freq=656 adjusted freq:625
Chain[J6] Aisc[19] original freq=650 adjusted freq:618
Chain[J6] Aisc[20] original freq=662 adjusted freq:631
Chain[J6] Aisc[21] original freq=656 adjusted freq:625
Chain[J6] Aisc[22] original freq=656 adjusted freq:625
Chain[J6] Aisc[23] original freq=656 adjusted freq:625
Chain[J6] Aisc[24] original freq=656 adjusted freq:625
Chain[J6] Aisc[25] original freq=662 adjusted freq:631
Chain[J6] Aisc[26] original freq=662 adjusted freq:631
Chain[J6] Aisc[27] original freq=656 adjusted freq:625
Chain[J6] Aisc[28] original freq=662 adjusted freq:631
Chain[J6] Aisc[29] original freq=512 adjusted freq:479
Chain[J6] Aisc[30] original freq=656 adjusted freq:625
Chain[J6] Aisc[31] original freq=662 adjusted freq:631
Chain[J6] Aisc[32] original freq=662 adjusted freq:631
Chain[J6] Aisc[33] original freq=625 adjusted freq:593
Chain[J6] Aisc[34] original freq=662 adjusted freq:631
Chain[J6] Aisc[35] original freq=625 adjusted freq:593
Chain[J6] Aisc[36] original freq=656 adjusted freq:625
Chain[J6] Aisc[37] original freq=662 adjusted freq:631
Chain[J6] Aisc[38] original freq=525 adjusted freq:491
Chain[J6] Aisc[39] original freq=656 adjusted freq:625
Chain[J6] Aisc[40] original freq=662 adjusted freq:631
Chain[J6] Aisc[41] original freq=662 adjusted freq:631
Chain[J6] Aisc[42] original freq=662 adjusted freq:631
Chain[J6] Aisc[43] original freq=662 adjusted freq:631
Chain[J6] Aisc[44] original freq=606 adjusted freq:575
Chain[J6] Aisc[45] original freq=656 adjusted freq:625
Chain[J6] Aisc[46] original freq=656 adjusted freq:625
Chain[J6] Aisc[47] original freq=662 adjusted freq:631
Chain[J6] Aisc[48] original freq=662 adjusted freq:631
Chain[J6] Aisc[49] original freq=662 adjusted freq:631
Chain[J6] Aisc[50] original freq=662 adjusted freq:631
Chain[J6] Aisc[51] original freq=650 adjusted freq:618
Chain[J6] Aisc[52] original freq=650 adjusted freq:618
Chain[J6] Aisc[53] original freq=662 adjusted freq:631
Chain[J6] Aisc[54] original freq=662 adjusted freq:631
Chain[J6] Aisc[55] original freq=662 adjusted freq:631
Chain[J6] Aisc[56] original freq=662 adjusted freq:631
Chain[J6] Aisc[57] original freq=662 adjusted freq:631
Chain[J6] Aisc[58] original freq=662 adjusted freq:631
Chain[J6] Aisc[59] original freq=662 adjusted freq:631
Chain[J6] Aisc[60] original freq=662 adjusted freq:631
Chain[J6] Aisc[61] original freq=662 adjusted freq:631
Chain[J6] Aisc[62] original freq=643 adjusted freq:612
Chain[J7] original vol value=880 adjusted vol value:860
Chain[J7] orignal chain_voltage_pic=142 value=860
Chain[J7] original chain_voltage_value=880 adjusted chain_voltage_value:860, value=860
Chain[J7] Aisc[00] original freq=618 adjusted freq:587
Chain[J7] Aisc[01] original freq=531 adjusted freq:500
Chain[J7] Aisc[02] original freq=625 adjusted freq:593
Chain[J7] Aisc[03] original freq=618 adjusted freq:587
Chain[J7] Aisc[04] original freq=543 adjusted freq:512
Chain[J7] Aisc[05] original freq=625 adjusted freq:593
Chain[J7] Aisc[06] original freq=600 adjusted freq:568
Chain[J7] Aisc[07] original freq=600 adjusted freq:568
Chain[J7] Aisc[08] original freq=625 adjusted freq:593
Chain[J7] Aisc[09] original freq=625 adjusted freq:593
Chain[J7] Aisc[10] original freq=625 adjusted freq:593
Chain[J7] Aisc[11] original freq=625 adjusted freq:593
Chain[J7] Aisc[12] original freq=625 adjusted freq:593
Chain[J7] Aisc[13] original freq=625 adjusted freq:593
Chain[J7] Aisc[14] original freq=625 adjusted freq:593
Chain[J7] Aisc[15] original freq=625 adjusted freq:593
Chain[J7] Aisc[16] original freq=512 adjusted freq:479
Chain[J7] Aisc[17] original freq=625 adjusted freq:593
Chain[J7] Aisc[18] original freq=625 adjusted freq:593
Chain[J7] Aisc[19] original freq=625 adjusted freq:593
Chain[J7] Aisc[20] original freq=562 adjusted freq:529
Chain[J7] Aisc[21] original freq=625 adjusted freq:593
Chain[J7] Aisc[22] original freq=625 adjusted freq:593
Chain[J7] Aisc[23] original freq=625 adjusted freq:593
Chain[J7] Aisc[24] original freq=625 adjusted freq:593
Chain[J7] Aisc[25] original freq=625 adjusted freq:593
Chain[J7] Aisc[26] original freq=625 adjusted freq:593
Chain[J7] Aisc[27] original freq=625 adjusted freq:593
Chain[J7] Aisc[28] original freq=625 adjusted freq:593
Chain[J7] Aisc[29] original freq=625 adjusted freq:593
Chain[J7] Aisc[30] original freq=625 adjusted freq:593
Chain[J7] Aisc[31] original freq=625 adjusted freq:593
Chain[J7] Aisc[32] original freq=625 adjusted freq:593
Chain[J7] Aisc[33] original freq=625 adjusted freq:593
Chain[J7] Aisc[34] original freq=625 adjusted freq:593
Chain[J7] Aisc[35] original freq=625 adjusted freq:593
Chain[J7] Aisc[36] original freq=625 adjusted freq:593
Chain[J7] Aisc[37] original freq=625 adjusted freq:593
Chain[J7] Aisc[38] original freq=625 adjusted freq:593
Chain[J7] Aisc[39] original freq=625 adjusted freq:593
Chain[J7] Aisc[40] original freq=625 adjusted freq:593
Chain[J7] Aisc[41] original freq=625 adjusted freq:593
Chain[J7] Aisc[42] original freq=625 adjusted freq:593
Chain[J7] Aisc[43] original freq=625 adjusted freq:593
Chain[J7] Aisc[44] original freq=581 adjusted freq:550
Chain[J7] Aisc[45] original freq=625 adjusted freq:593
Chain[J7] Aisc[46] original freq=625 adjusted freq:593
Chain[J7] Aisc[47] original freq=625 adjusted freq:593
Chain[J7] Aisc[48] original freq=612 adjusted freq:581
Chain[J7] Aisc[49] original freq=625 adjusted freq:593
Chain[J7] Aisc[50] original freq=625 adjusted freq:593
Chain[J7] Aisc[51] original freq=625 adjusted freq:593
Chain[J7] Aisc[52] original freq=568 adjusted freq:537
Chain[J7] Aisc[53] original freq=625 adjusted freq:593
Chain[J7] Aisc[54] original freq=625 adjusted freq:593
Chain[J7] Aisc[55] original freq=625 adjusted freq:593
Chain[J7] Aisc[56] original freq=625 adjusted freq:593
Chain[J7] Aisc[57] original freq=625 adjusted freq:593
Chain[J7] Aisc[58] original freq=625 adjusted freq:593
Chain[J7] Aisc[59] original freq=618 adjusted freq:587
Chain[J7] Aisc[60] original freq=625 adjusted freq:593
Chain[J7] Aisc[61] original freq=625 adjusted freq:593
Chain[J7] Aisc[62] original freq=625 adjusted freq:593
Chain[J8] original vol value=880 adjusted vol value:860
Chain[J8] orignal chain_voltage_pic=142 value=860
Chain[J8] original chain_voltage_value=880 adjusted chain_voltage_value:860, value=860
Chain[J8] Aisc[00] original freq=625 adjusted freq:593
Chain[J8] Aisc[01] original freq=625 adjusted freq:593
Chain[J8] Aisc[02] original freq=637 adjusted freq:606
Chain[J8] Aisc[03] original freq=625 adjusted freq:593
Chain[J8] Aisc[04] original freq=625 adjusted freq:593
Chain[J8] Aisc[05] original freq=637 adjusted freq:606
Chain[J8] Aisc[06] original freq=625 adjusted freq:593
Chain[J8] Aisc[07] original freq=625 adjusted freq:593
Chain[J8] Aisc[08] original freq=637 adjusted freq:606
Chain[J8] Aisc[09] original freq=625 adjusted freq:593
Chain[J8] Aisc[10] original freq=625 adjusted freq:593
Chain[J8] Aisc[11] original freq=637 adjusted freq:606
Chain[J8] Aisc[12] original freq=625 adjusted freq:593
Chain[J8] Aisc[13] original freq=625 adjusted freq:593
Chain[J8] Aisc[14] original freq=637 adjusted freq:606
Chain[J8] Aisc[15] original freq=625 adjusted freq:593
Chain[J8] Aisc[16] original freq=600 adjusted freq:568
Chain[J8] Aisc[17] original freq=637 adjusted freq:606
Chain[J8] Aisc[18] original freq=600 adjusted freq:568
Chain[J8] Aisc[19] original freq=625 adjusted freq:593
Chain[J8] Aisc[20] original freq=637 adjusted freq:606
Chain[J8] Aisc[21] original freq=625 adjusted freq:593
Chain[J8] Aisc[22] original freq=543 adjusted freq:512
Chain[J8] Aisc[23] original freq=637 adjusted freq:606
Chain[J8] Aisc[24] original freq=625 adjusted freq:593
Chain[J8] Aisc[25] original freq=625 adjusted freq:593
Chain[J8] Aisc[26] original freq=550 adjusted freq:516
Chain[J8] Aisc[27] original freq=625 adjusted freq:593
Chain[J8] Aisc[28] original freq=568 adjusted freq:537
Chain[J8] Aisc[29] original freq=631 adjusted freq:600
Chain[J8] Aisc[30] original freq=625 adjusted freq:593
Chain[J8] Aisc[31] original freq=550 adjusted freq:516
Chain[J8] Aisc[32] original freq=637 adjusted freq:606
Chain[J8] Aisc[33] original freq=568 adjusted freq:537
Chain[J8] Aisc[34] original freq=625 adjusted freq:593
Chain[J8] Aisc[35] original freq=637 adjusted freq:606
Chain[J8] Aisc[36] original freq=625 adjusted freq:593
Chain[J8] Aisc[37] original freq=625 adjusted freq:593
Chain[J8] Aisc[38] original freq=625 adjusted freq:593
Chain[J8] Aisc[39] original freq=625 adjusted freq:593
Chain[J8] Aisc[40] original freq=631 adjusted freq:600
Chain[J8] Aisc[41] original freq=529 adjusted freq:495
Chain[J8] Aisc[42] original freq=625 adjusted freq:593
Chain[J8] Aisc[43] original freq=520 adjusted freq:487
Chain[J8] Aisc[44] original freq=637 adjusted freq:606
Chain[J8] Aisc[45] original freq=625 adjusted freq:593
Chain[J8] Aisc[46] original freq=631 adjusted freq:600
Chain[J8] Aisc[47] original freq=637 adjusted freq:606
Chain[J8] Aisc[48] original freq=625 adjusted freq:593
Chain[J8] Aisc[49] original freq=631 adjusted freq:600
Chain[J8] Aisc[50] original freq=575 adjusted freq:543
Chain[J8] Aisc[51] original freq=625 adjusted freq:593
Chain[J8] Aisc[52] original freq=631 adjusted freq:600
Chain[J8] Aisc[53] original freq=637 adjusted freq:606
Chain[J8] Aisc[54] original freq=625 adjusted freq:593
Chain[J8] Aisc[55] original freq=631 adjusted freq:600
Chain[J8] Aisc[56] original freq=637 adjusted freq:606
Chain[J8] Aisc[57] original freq=625 adjusted freq:593
Chain[J8] Aisc[58] original freq=637 adjusted freq:606
Chain[J8] Aisc[59] original freq=637 adjusted freq:606
Chain[J8] Aisc[60] original freq=625 adjusted freq:593
Chain[J8] Aisc[61] original freq=637 adjusted freq:606
Chain[J8] Aisc[62] original freq=637 adjusted freq:606
Chain[J6] has 63 asic
Chain[J7] has 63 asic
Chain[J8] has 61 asic
retry Chain[J8] has 61 asic
retry Chain[J8] has 61 asic
retry Chain[J8] has 61 asic
retry Chain[J8] has 61 asic
retry Chain[J8] has 61 asic
retry Chain[J8] has 61 asic
Chain[J6] has core num in PIC
Chain[J6] ASIC[29] has core num=6
Chain[J7] has core num in PIC
Chain[J7] ASIC[16] has core num=10
Chain[J7] ASIC[29] has core num=1
Chain[J7] ASIC[30] has core num=1
Chain[J7] ASIC[52] has core num=1
Chain[J7] ASIC[53] has core num=1
Chain[J8] has core num in PIC
Chain[J8] ASIC[6] has core num=1
Chain[J8] ASIC[7] has core num=1
Chain[J8] ASIC[40] has core num=1
Chain[J8] ASIC[43] has core num=4
miner total rate=12853GH/s ideal_total_hash_rate = 12500GH/s
read PIC voltage=910 on chain[5]
Chain:5 chipnum=63
Chain[J6] voltage added=0.2V
Chain:5 temp offset=-5
Chain:5 base freq=512
Asic[ 0]:612 Asic[ 1]:631 Asic[ 2]:631 Asic[ 3]:612 Asic[ 4]:631 Asic[ 5]:631 Asic[ 6]:612 Asic[ 7]:631 
Asic[ 8]:631 Asic[ 9]:612 Asic[10]:631 Asic[11]:631 Asic[12]:618 Asic[13]:631 Asic[14]:631 Asic[15]:625 
Asic[16]:631 Asic[17]:581 Asic[18]:625 Asic[19]:618 Asic[20]:631 Asic[21]:625 Asic[22]:625 Asic[23]:625 
Asic[24]:625 Asic[25]:631 Asic[26]:631 Asic[27]:625 Asic[28]:631 Asic[29]:479 Asic[30]:625 Asic[31]:631 
Asic[32]:631 Asic[33]:593 Asic[34]:631 Asic[35]:593 Asic[36]:625 Asic[37]:631 Asic[38]:491 Asic[39]:625 
Asic[40]:631 Asic[41]:631 Asic[42]:631 Asic[43]:631 Asic[44]:575 Asic[45]:625 Asic[46]:625 Asic[47]:631 
Asic[48]:631 Asic[49]:631 Asic[50]:631 Asic[51]:618 Asic[52]:618 Asic[53]:631 Asic[54]:631 Asic[55]:631 
Asic[56]:631 Asic[57]:631 Asic[58]:631 Asic[59]:631 Asic[60]:631 Asic[61]:631 Asic[62]:612 
Chain:5 max freq=631
Chain:5 min freq=479

read PIC voltage=910 on chain[6]
Chain:6 chipnum=63
Chain[J7] voltage added=0.2V
Chain:6 temp offset=-4
Chain:6 base freq=512
Asic[ 0]:587 Asic[ 1]:500 Asic[ 2]:593 Asic[ 3]:587 Asic[ 4]:512 Asic[ 5]:593 Asic[ 6]:568 Asic[ 7]:568 
Asic[ 8]:593 Asic[ 9]:593 Asic[10]:593 Asic[11]:593 Asic[12]:593 Asic[13]:593 Asic[14]:593 Asic[15]:593 
Asic[16]:479 Asic[17]:593 Asic[18]:593 Asic[19]:593 Asic[20]:529 Asic[21]:593 Asic[22]:593 Asic[23]:593 
Asic[24]:593 Asic[25]:593 Asic[26]:593 Asic[27]:593 Asic[28]:593 Asic[29]:593 Asic[30]:593 Asic[31]:593 
Asic[32]:593 Asic[33]:593 Asic[34]:593 Asic[35]:593 Asic[36]:593 Asic[37]:593 Asic[38]:593 Asic[39]:593 
Asic[40]:593 Asic[41]:593 Asic[42]:593 Asic[43]:593 Asic[44]:550 Asic[45]:593 Asic[46]:593 Asic[47]:593 
Asic[48]:581 Asic[49]:593 Asic[50]:593 Asic[51]:593 Asic[52]:537 Asic[53]:593 Asic[54]:593 Asic[55]:593 
Asic[56]:593 Asic[57]:593 Asic[58]:593 Asic[59]:587 Asic[60]:593 Asic[61]:593 Asic[62]:593 
Chain:6 max freq=593
Chain:6 min freq=479

read PIC voltage=910 on chain[7]
Chain:7 chipnum=61
Chain[J8] voltage added=0.2V
Chain:7 temp offset=-3
Chain:7 base freq=520
Asic[ 0]:593 Asic[ 1]:593 Asic[ 2]:606 Asic[ 3]:593 Asic[ 4]:593 Asic[ 5]:606 Asic[ 6]:593 Asic[ 7]:593 
Asic[ 8]:606 Asic[ 9]:593 Asic[10]:593 Asic[11]:606 Asic[12]:593 Asic[13]:593 Asic[14]:606 Asic[15]:593 
Asic[16]:568 Asic[17]:606 Asic[18]:568 Asic[19]:593 Asic[20]:606 Asic[21]:593 Asic[22]:512 Asic[23]:606 
Asic[24]:593 Asic[25]:593 Asic[26]:516 Asic[27]:593 Asic[28]:537 Asic[29]:600 Asic[30]:593 Asic[31]:516 
Asic[32]:606 Asic[33]:537 Asic[34]:593 Asic[35]:606 Asic[36]:593 Asic[37]:593 Asic[38]:593 Asic[39]:593 
Asic[40]:600 Asic[41]:495 Asic[42]:593 Asic[43]:487 Asic[44]:606 Asic[45]:593 Asic[46]:600 Asic[47]:606 
Asic[48]:593 Asic[49]:600 Asic[50]:543 Asic[51]:593 Asic[52]:600 Asic[53]:606 Asic[54]:593 Asic[55]:600 
Asic[56]:606 Asic[57]:593 Asic[58]:606 Asic[59]:606 Asic[60]:593 
Chain:7 max freq=606
Chain:7 min freq=487


Miner fix freq ...
totalRate = 12853, fixed_totalRate = 12625
read PIC voltage=910 on chain[5]
Chain:5 chipnum=63
Chain[J6] voltage added=0.2V
Chain:5 temp offset=-5
Chain:5 base freq=512
Asic[ 0]:612 Asic[ 1]:631 Asic[ 2]:631 Asic[ 3]:612 Asic[ 4]:631 Asic[ 5]:631 Asic[ 6]:612 Asic[ 7]:631 
Asic[ 8]:631 Asic[ 9]:612 Asic[10]:631 Asic[11]:631 Asic[12]:618 Asic[13]:631 Asic[14]:631 Asic[15]:625 
Asic[16]:631 Asic[17]:581 Asic[18]:625 Asic[19]:618 Asic[20]:631 Asic[21]:625 Asic[22]:625 Asic[23]:625 
Asic[24]:625 Asic[25]:631 Asic[26]:631 Asic[27]:625 Asic[28]:631 Asic[29]:479 Asic[30]:625 Asic[31]:631 
Asic[32]:631 Asic[33]:593 Asic[34]:631 Asic[35]:593 Asic[36]:625 Asic[37]:631 Asic[38]:491 Asic[39]:625 
Asic[40]:631 Asic[41]:631 Asic[42]:631 Asic[43]:631 Asic[44]:575 Asic[45]:625 Asic[46]:625 Asic[47]:631 
Asic[48]:631 Asic[49]:631 Asic[50]:631 Asic[51]:618 Asic[52]:618 Asic[53]:631 Asic[54]:631 Asic[55]:631 
Asic[56]:631 Asic[57]:631 Asic[58]:631 Asic[59]:631 Asic[60]:631 Asic[61]:631 Asic[62]:612 
Chain:5 max freq=631
Chain:5 min freq=479

read PIC voltage=910 on chain[6]
Chain:6 chipnum=63
Chain[J7] voltage added=0.2V
Chain:6 temp offset=-4
Chain:6 base freq=512
Asic[ 0]:587 Asic[ 1]:500 Asic[ 2]:593 Asic[ 3]:587 Asic[ 4]:512 Asic[ 5]:593 Asic[ 6]:568 Asic[ 7]:568 
Asic[ 8]:593 Asic[ 9]:593 Asic[10]:593 Asic[11]:593 Asic[12]:593 Asic[13]:593 Asic[14]:593 Asic[15]:593 
Asic[16]:479 Asic[17]:593 Asic[18]:593 Asic[19]:593 Asic[20]:529 Asic[21]:593 Asic[22]:593 Asic[23]:593 
Asic[24]:593 Asic[25]:593 Asic[26]:593 Asic[27]:593 Asic[28]:593 Asic[29]:593 Asic[30]:593 Asic[31]:593 
Asic[32]:593 Asic[33]:593 Asic[34]:593 Asic[35]:593 Asic[36]:593 Asic[37]:593 Asic[38]:593 Asic[39]:593 
Asic[40]:593 Asic[41]:593 Asic[42]:593 Asic[43]:593 Asic[44]:550 Asic[45]:593 Asic[46]:593 Asic[47]:593 
Asic[48]:581 Asic[49]:593 Asic[50]:593 Asic[51]:593 Asic[52]:537 Asic[53]:593 Asic[54]:593 Asic[55]:593 
Asic[56]:593 Asic[57]:593 Asic[58]:593 Asic[59]:587 Asic[60]:593 Asic[61]:593 Asic[62]:593 
Chain:6 max freq=593
Chain:6 min freq=479

read PIC voltage=910 on chain[7]
Chain:7 chipnum=61
Chain[J8] voltage added=0.2V
Chain:7 temp offset=-3
Chain:7 base freq=520
Asic[ 0]:593 Asic[ 1]:593 Asic[ 2]:606 Asic[ 3]:593 Asic[ 4]:593 Asic[ 5]:606 Asic[ 6]:593 Asic[ 7]:593 
Asic[ 8]:606 Asic[ 9]:593 Asic[10]:593 Asic[11]:606 Asic[12]:593 Asic[13]:593 Asic[14]:606 Asic[15]:593 
Asic[16]:568 Asic[17]:606 Asic[18]:568 Asic[19]:593 Asic[20]:606 Asic[21]:593 Asic[22]:512 Asic[23]:606 
Asic[24]:593 Asic[25]:593 Asic[26]:516 Asic[27]:593 Asic[28]:537 Asic[29]:600 Asic[30]:593 Asic[31]:516 
Asic[32]:606 Asic[33]:537 Asic[34]:593 Asic[35]:606 Asic[36]:593 Asic[37]:593 Asic[38]:593 Asic[39]:593 
Asic[40]:600 Asic[41]:495 Asic[42]:593 Asic[43]:487 Asic[44]:606 Asic[45]:593 Asic[46]:600 Asic[47]:606 
Asic[48]:593 Asic[49]:600 Asic[50]:543 Asic[51]:593 Asic[52]:600 Asic[53]:606 Asic[54]:593 Asic[55]:600 
Asic[56]:606 Asic[57]:593 Asic[58]:606 Asic[59]:606 Asic[60]:593 
Chain:7 max freq=606
Chain:7 min freq=487

max freq = 631
totalRate = 12853, fixed_totalRate = 12500
set baud=1
Chain[J6] PIC temp offset: 62,-5,32,-5,0,0,0,0,0,0,0,0,0,0,0,0,0,0,
chain[6] temp chip I2C addr=0x98
chain[6] has no middle temp, use special fix mode.
Chain[J6] chip[244] use PIC middle temp offset=-5 typeID=55
New offset Chain[6] chip[244] local:29 remote:31 offset:28 
Chain[J6] chip[244] get middle temp offset=28 typeID=55
Chain[J6] chip[124] use PIC middle temp offset=-5 typeID=55
New offset Chain[6] chip[124] local:28 remote:30 offset:28 
Chain[J6] chip[124] get middle temp offset=28 typeID=55
Chain[J7] PIC temp offset: 62,-4,32,-5,0,0,0,0,0,0,0,0,0,0,0,0,0,0,
chain[7] temp chip I2C addr=0x98
chain[7] has no middle temp, use special fix mode.
Chain[J7] chip[244] use PIC middle temp offset=-4 typeID=55
New offset Chain[7] chip[244] local:28 remote:31 offset:27 
Chain[J7] chip[244] get middle temp offset=27 typeID=55
Chain[J7] chip[124] use PIC middle temp offset=-5 typeID=55
New offset Chain[7] chip[124] local:27 remote:28 offset:29 
Chain[J7] chip[124] get middle temp offset=29 typeID=55
open core three times
open core three times
open core three times
setting to working voltage...
chain[5] set voltage to 900
chain[6] set voltage to 900
chain[7] set voltage to 900
chain[5] set voltage to 890
chain[6] set voltage to 890
chain[7] set voltage to 890
chain[5] set voltage to 880
chain[6] set voltage to 880
chain[7] set voltage to 880
chain[5] set voltage to 870
chain[6] set voltage to 870
chain[7] set voltage to 870
chain[5] set voltage to 860
chain[6] set voltage to 860
chain[7] set voltage to 860
start thread for read temp
setStartTimePoint total_tv_start_sys=198 total_tv_end_sys=199
restartNum = 2 , auto-reinit enabled...
mining.subscribe:{"id": 0, "method": "mining.subscribe", "params": ["bmminer/2.0.0/Antminer S9/13500"]}
bring_up_pcb_temp = 50
setting to working voltage...
voltage_check_done
avg hash rate = 12358.144719, ideal hash rate = 12500
hash rate is low...
avg_rate = 12564, ideal_total_hash_rate = 12500
avg hash rate is OK
avg_rate = 12455, ideal_total_hash_rate = 12500
avg_rate = 12475, ideal_total_hash_rate = 12500
avg_rate = 12511, ideal_total_hash_rate = 12500
avg hash rate is OK
avg_rate = 12545, ideal_total_hash_rate = 12500
avg hash rate is OK
avg_rate = 12566, ideal_total_hash_rate = 12500
avg hash rate is OK
avg_rate = 12576, ideal_total_hash_rate = 12500
avg hash rate is OK
mining.subscribe:{"id": 99215, "method": "mining.subscribe", "params": ["bmminer/2.0.0/Antminer S9/13500", "1"]}
do read_temp_func once...

get RT hashrate from Chain[5]: (asic index start from 1-63)
Asic[01]=72.2760 Asic[02]=81.1340 Asic[03]=72.5780 Asic[04]=69.5080 Asic[05]=73.8190 Asic[06]=68.0480 Asic[07]=69.6250 Asic[08]=68.2160 
Asic[09]=71.2520 Asic[10]=70.2460 Asic[11]=69.4070 Asic[12]=64.2230 Asic[13]=67.7460 Asic[14]=63.5180 Asic[15]=68.8870 Asic[16]=71.1350 
Asic[17]=77.2590 Asic[18]=67.8130 Asic[19]=67.2090 Asic[20]=70.1950 Asic[21]=73.2490 Asic[22]=70.2460 Asic[23]=70.6820 Asic[24]=69.7420 
Asic[25]=70.8660 Asic[26]=68.2320 Asic[27]=70.9170 Asic[28]=68.6850 Asic[29]=65.1620 Asic[30]=56.2870 Asic[31]=65.4310 Asic[32]=72.6110 
Asic[33]=74.9270 Asic[34]=67.0920 Asic[35]=70.0610 Asic[36]=62.9980 Asic[37]=71.4030 Asic[38]=73.0640 Asic[39]=57.6630 Asic[40]=68.5010 
Asic[41]=73.6510 Asic[42]=77.0570 Asic[43]=67.8130 Asic[44]=73.2990 Asic[45]=63.1320 Asic[46]=70.9670 Asic[47]=70.3460 Asic[48]=69.2560 
Asic[49]=67.4270 Asic[50]=74.8590 Asic[51]=72.0910 Asic[52]=67.2430 Asic[53]=73.7350 Asic[54]=68.0980 Asic[55]=74.9100 Asic[56]=68.5340 
Asic[57]=69.3230 Asic[58]=69.1890 Asic[59]=70.4810 Asic[60]=70.6820 Asic[61]=64.9610 Asic[62]=65.7490 Asic[63]=70.7830 

get RT hashrate from Chain[6]: (asic index start from 1-63)
Asic[01]=63.2830 Asic[02]=56.8570 Asic[03]=67.4100 Asic[04]=67.3600 Asic[05]=55.5320 Asic[06]=67.8300 Asic[07]=64.8270 Asic[08]=63.8370 
Asic[09]=68.2160 Asic[10]=68.8530 Asic[11]=66.9570 Asic[12]=67.4100 Asic[13]=65.4140 Asic[14]=63.6020 Asic[15]=74.7920 Asic[16]=66.5210 
Asic[17]=52.9820 Asic[18]=66.1350 Asic[19]=67.2090 Asic[20]=69.8600 Asic[21]=59.2230 Asic[22]=68.5180 Asic[23]=67.7630 Asic[24]=69.2060 
Asic[25]=66.2860 Asic[26]=68.0480 Asic[27]=66.9070 Asic[28]=71.3700 Asic[29]=68.2320 Asic[30]=65.3300 Asic[31]=65.3800 Asic[32]=67.4610 
Asic[33]=66.7730 Asic[34]=67.6790 Asic[35]=67.4270 Asic[36]=69.8260 Asic[37]=59.7770 Asic[38]=71.8730 Asic[39]=66.6220 Asic[40]=68.0140 
Asic[41]=62.6620 Asic[42]=75.0100 Asic[43]=67.8630 Asic[44]=64.8600 Asic[45]=62.0250 Asic[46]=69.8600 Asic[47]=69.8090 Asic[48]=66.8900 
Asic[49]=67.4270 Asic[50]=63.3330 Asic[51]=65.7490 Asic[52]=68.8030 Asic[53]=59.4080 Asic[54]=67.7290 Asic[55]=63.6860 Asic[56]=67.1250 
Asic[57]=64.4410 Asic[58]=62.3270 Asic[59]=68.8360 Asic[60]=67.1920 Asic[61]=65.2130 Asic[62]=65.3970 Asic[63]=65.2960 

get RT hashrate from Chain[7]: (asic index start from 1-63)
Asic[01]=65.9510 Asic[02]=60.9180 Asic[03]=73.7020 Asic[04]=72.0240 Asic[05]=65.8670 Asic[06]=74.0370 Asic[07]=67.0920 Asic[08]=73.2320 
Asic[09]=73.0980 Asic[10]=71.0170 Asic[11]=65.2290 Asic[12]=63.8540 Asic[13]=62.7130 Asic[14]=62.3270 Asic[15]=66.9240 Asic[16]=70.6990 
Asic[17]=62.8640 Asic[18]=68.7530 Asic[19]=66.0180 Asic[20]=70.0280 Asic[21]=67.7290 Asic[22]=66.1520 Asic[23]=59.9950 Asic[24]=70.9170 
Asic[25]=72.3930 Asic[26]=64.3900 Asic[27]=63.5180 Asic[28]=70.7660 Asic[29]=55.3310 Asic[30]=66.0350 Asic[31]=69.0380 Asic[32]=52.9650 
Asic[33]=68.6350 Asic[34]=57.1260 Asic[35]=72.0580 Asic[36]=75.4970 Asic[37]=72.0910 Asic[38]=70.2460 Asic[39]=65.8000 Asic[40]=23.8230 
Asic[41]=18.7400 Asic[42]=60.4480 Asic[43]=63.9210 Asic[44]=56.0690 Asic[45]=69.8260 Asic[46]=60.1290 Asic[47]=66.7560 Asic[48]=67.4940 
Asic[49]=63.9540 Asic[50]=53.6530 Asic[51]=70.3300 Asic[52]=63.7190 Asic[53]=71.4200 Asic[54]=70.8330 Asic[55]=69.7420 Asic[56]=70.5810 
Asic[57]=68.3000 Asic[58]=72.7960 Asic[59]=75.7490 Asic[60]=70.9840 Asic[61]=69.5910 Check Chain[J6] ASIC RT error: (asic index start from 1-63)
Check Chain[J7] ASIC RT error: (asic index start from 1-63)
Check Chain[J8] ASIC RT error: (asic index start from 1-63)
Done check_asic_reg
Chain[5] Chip[244] pcb temperature=67
Chain[5] Chip[62] junction temperature=78
Special fix Chain[5] Chip[62] middle Temp = 82
Chain[5] Chip[124] pcb temperature=55
Chain[5] Chip[32] junction temperature=72
Special fix Chain[5] Chip[32] middle Temp = 70
Done read temp on Chain[5]
Chain[6] Chip[244] pcb temperature=59
Chain[6] Chip[62] junction temperature=68
Special fix Chain[6] Chip[62] middle Temp = 74
Chain[6] Chip[124] pcb temperature=44
Chain[6] Chip[32] junction temperature=63
Special fix Chain[6] Chip[32] middle Temp = 59
Done read temp on Chain[6]
Done read temp on Chain[7]
Max pcb temp : 67
set FAN speed according to: temp_highest=67 temp_top1[PWM_T]=67 temp_top1[TEMP_POS_LOCAL]=67 temp_change=1 fix_fan_steps=0
FAN PWM: 82
read_temp_func Done!
CRC error counter=15779

