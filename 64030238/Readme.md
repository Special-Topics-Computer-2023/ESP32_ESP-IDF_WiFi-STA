# 64030238 Jasda
- Repo https://github.com/JASDA0000/ESP_WIFI_STA.git
# Terminal Output
```
?[0;33m--- idf_monitor on \\.\COM6 115200 ---?[0m
--- Quit: Ctrl+] | Menu: Ctrl+T | Help: Ctrl+T followed by Ctrl+H ---
ets Jul 29 2019 12:21:46

rst:0x1 (POWERON_RESET),boot:0x13 (SPI_FAST_FLASH_BOOT)
configsip: 0, SPIWP:0xee
clk_drv:0x00,q_drv:0x00,d_drv:0x00,cs0_drv:0x00,hd_drv:0x00,wp_drv:0x00
mode:DIO, clock div:2
load:0x3fff0030,len:6944
load:0x40078000,len:15500
load:0x40080400,len:3844
0x40080400: _init at ??:?

entry 0x4008064c
I (27) boot: ESP-IDF v5.0.2-dirty 2nd stage bootloader
I (27) boot: compile time 10:30:21
I (28) boot: chip revision: v3.0
I (31) boot.esp32: SPI Speed      : 40MHz
I (36) boot.esp32: SPI Mode       : DIO
I (40) boot.esp32: SPI Flash Size : 2MB
I (45) boot: Enabling RNG early entropy source...
I (50) boot: Partition Table:
I (54) boot: ## Label            Usage          Type ST Offset   Length
I (61) boot:  0 nvs              WiFi data        01 02 00009000 00006000
I (68) boot:  1 phy_init         RF data          01 01 0000f000 00001000
I (76) boot:  2 factory          factory app      00 00 00010000 00100000
I (83) boot: End of partition table
I (87) esp_image: segment 0: paddr=00010020 vaddr=3f400020 size=1e630h (124464) map
I (141) esp_image: segment 1: paddr=0002e658 vaddr=3ffb0000 size=019c0h (  6592) load
I (144) esp_image: segment 2: paddr=00030020 vaddr=400d0020 size=7a0cch (499916) map
I (327) esp_image: segment 3: paddr=000aa0f4 vaddr=3ffb19c0 size=0197ch (  6524) load
I (330) esp_image: segment 4: paddr=000aba78 vaddr=40080000 size=14c98h ( 85144) load
I (378) boot: Loaded app from partition at offset 0x10000
I (379) boot: Disabling RNG early entropy source...
I (390) cpu_start: Pro cpu up.
I (390) cpu_start: Starting app cpu, entry point is 0x400812b8
0x400812b8: call_start_cpu1 at C:/Espressif/frameworks/esp-idf-v5.0.2/components/esp_system/port/cpu_start.c:141

I (0) cpu_start: App cpu up.
I (407) cpu_start: Pro cpu start user code
I (407) cpu_start: cpu freq: 160000000 Hz
I (407) cpu_start: Application information:
I (411) cpu_start: Project name:     app-template
I (417) cpu_start: App version:      1
I (421) cpu_start: Compile time:     Sep 16 2023 10:30:04
I (427) cpu_start: ELF file SHA256:  a8734e4652ff8e28...
I (433) cpu_start: ESP-IDF:          v5.0.2-dirty
I (439) cpu_start: Min chip rev:     v0.0
I (443) cpu_start: Max chip rev:     v3.99 
I (448) cpu_start: Chip rev:         v3.0
I (453) heap_init: Initializing. RAM available for dynamic allocation:
I (460) heap_init: At 3FFAE6E0 len 00001920 (6 KiB): DRAM
I (466) heap_init: At 3FFB6FA0 len 00029060 (164 KiB): DRAM
I (472) heap_init: At 3FFE0440 len 00003AE0 (14 KiB): D/IRAM
I (479) heap_init: At 3FFE4350 len 0001BCB0 (111 KiB): D/IRAM
I (485) heap_init: At 40094C98 len 0000B368 (44 KiB): IRAM
I (493) spi_flash: detected chip: generic
I (496) spi_flash: flash io: dio
W (500) spi_flash: Detected size(4096k) larger than the size in the binary image header(2048k). Using the size in the binary image header.
I (514) cpu_start: Starting scheduler on PRO CPU.
I (0) cpu_start: Starting scheduler on APP CPU.
I (599) wifi station: ESP_WIFI_MODE_STA
I (609) wifi:wifi driver task: 3ffbefc8, prio:23, stack:6656, core=0
I (609) system_api: Base MAC address is not set
I (609) system_api: read default base MAC address from EFUSE
I (629) wifi:wifi firmware version: 57982fe
I (629) wifi:wifi certification version: v7.0
I (629) wifi:config NVS flash: enabled
I (629) wifi:config nano formating: disabled
I (639) wifi:Init data frame dynamic rx buffer num: 32
I (639) wifi:Init management frame dynamic rx buffer num: 32
I (649) wifi:Init management short buffer num: 32
I (649) wifi:Init dynamic tx buffer num: 32
I (659) wifi:Init static rx buffer size: 1600
I (659) wifi:Init static rx buffer num: 10
I (659) wifi:Init dynamic rx buffer num: 32
I (669) wifi_init: rx ba win: 6
I (669) wifi_init: tcpip mbox: 32
I (679) wifi_init: udp mbox: 6
I (679) wifi_init: tcp mbox: 6
I (679) wifi_init: tcp tx win: 5744
I (689) wifi_init: tcp rx win: 5744
I (689) wifi_init: tcp mss: 1440
I (699) wifi_init: WiFi IRAM OP enabled
I (699) wifi_init: WiFi RX IRAM OP enabled
I (729) phy_init: phy_version 4670,719f9f6,Feb 18 2021,17:07:07
I (829) wifi:mode : sta (24:d7:eb:0e:c8:d0)
I (829) wifi:enable tsf
I (829) wifi station: wifi_init_sta finished.
I (879) wifi:new:<6,0>, old:<1,0>, ap:<255,255>, sta:<6,0>, prof:1
I (1559) wifi:state: init -> auth (b0)
I (1569) wifi:state: auth -> assoc (0)
I (1599) wifi:state: assoc -> run (10)
I (1989) wifi:connected with Solomon, aid = 2, channel 6, BW20, bssid = 46:87:01:49:d8:85
I (1989) wifi:security: WPA2-PSK, phy: bgn, rssi: -49
I (2009) wifi:pm start, type: 1

I (2009) wifi:AP's beacon interval = 102400 us, DTIM period = 1
I (2039) wifi:<ba-add>idx:0 (ifx:0, 46:87:01:49:d8:85), tid:0, ssn:2, winSize:64
I (3009) esp_netif_handlers: sta ip: 172.20.10.10, mask: 255.255.255.240, gw: 172.20.10.1
I (3009) wifi station: got ip:172.20.10.10
I (3009) wifi station: connected to ap SSID:Solomon password:0878872337bo


```
