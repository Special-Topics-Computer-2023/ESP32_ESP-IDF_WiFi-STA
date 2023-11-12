## REPO
https://github.com/DanupatSangseekaew/Wifi_STA
## result 
```
entry 0x40080694
I (27) boot: ESP-IDF v4.4.2-dirty 2nd stage bootloader
I (27) boot: compile time 00:35:19
I (27) boot: chip revision: 3
I (31) boot_comm: chip revision: 3, min. bootloader chip revision: 0
I (38) boot.esp32: SPI Speed      : 40MHz
I (42) boot.esp32: SPI Mode       : DIO
I (47) boot.esp32: SPI Flash Size : 2MB
I (51) boot: Enabling RNG early entropy source...
I (57) boot: Partition Table:
I (60) boot: ## Label            Usage          Type ST Offset   Length
I (68) boot:  0 nvs              WiFi data        01 02 00009000 00006000
I (75) boot:  1 phy_init         RF data          01 01 0000f000 00001000
I (83) boot:  2 factory          factory app      00 00 00010000 00100000
I (90) boot: End of partition table
I (94) boot_comm: chip revision: 3, min. application chip revision: 0
I (101) esp_image: segment 0: paddr=00010020 vaddr=3f400020 size=12d14h ( 77076) map
I (138) esp_image: segment 1: paddr=00022d3c vaddr=3ffb0000 size=03804h ( 14340) load
I (144) esp_image: segment 2: paddr=00026548 vaddr=40080000 size=09ad0h ( 39632) load
I (160) esp_image: segment 3: paddr=00030020 vaddr=400d0020 size=6d458h (447576) map
I (323) esp_image: segment 4: paddr=0009d480 vaddr=40089ad0 size=0aa10h ( 43536) load
I (341) esp_image: segment 5: paddr=000a7e98 vaddr=50000000 size=00010h (    16) load
I (351) boot: Loaded app from partition at offset 0x10000
I (351) boot: Disabling RNG early entropy source...
I (363) cpu_start: Pro cpu up.
I (363) cpu_start: Starting app cpu, entry point is 0x40081198
0x40081198: call_start_cpu1 at C:/Espressif/frameworks/esp-idf-v4.4.2/components/esp_system/port/cpu_start.c:160

I (0) cpu_start: App cpu up.
I (379) cpu_start: Pro cpu start user code
I (380) cpu_start: cpu freq: 160000000
I (380) cpu_start: Application information:
I (384) cpu_start: Project name:     ESP32_ESP-IDF_WiFi-STA
I (390) cpu_start: App version:      v4.4.2-dirty
I (396) cpu_start: Compile time:     Nov 13 2023 00:34:33
I (402) cpu_start: ELF file SHA256:  1c1b090c3117adb9...
I (408) cpu_start: ESP-IDF:          v4.4.2-dirty
I (413) heap_init: Initializing. RAM available for dynamic allocation:
I (420) heap_init: At 3FFAE6E0 len 00001920 (6 KiB): DRAM
I (426) heap_init: At 3FFB74D0 len 00028B30 (162 KiB): DRAM
I (433) heap_init: At 3FFE0440 len 00003AE0 (14 KiB): D/IRAM
I (439) heap_init: At 3FFE4350 len 0001BCB0 (111 KiB): D/IRAM
I (445) heap_init: At 400944E0 len 0000BB20 (46 KiB): IRAM
I (453) spi_flash: detected chip: generic
I (456) spi_flash: flash io: dio
W (460) spi_flash: Detected size(4096k) larger than the size in the binary image header(2048k). Using the size in the binary image header.
I (474) cpu_start: Starting scheduler on PRO CPU.
I (0) cpu_start: Starting scheduler on APP CPU.
I (559) wifi station: ESP_WIFI_MODE_STA
I (569) wifi:wifi driver task: 3ffc01bc, prio:23, stack:6656, core=0
I (569) system_api: Base MAC address is not set
I (569) system_api: read default base MAC address from EFUSE
I (589) wifi:wifi firmware version: eeaa27d
I (589) wifi:wifi certification version: v7.0
I (589) wifi:config NVS flash: enabled
I (589) wifi:config nano formating: disabled
I (599) wifi:Init data frame dynamic rx buffer num: 32
I (599) wifi:Init management frame dynamic rx buffer num: 32
I (609) wifi:Init management short buffer num: 32
I (609) wifi:Init dynamic tx buffer num: 32
I (609) wifi:Init static rx buffer size: 1600
I (619) wifi:Init static rx buffer num: 10
I (619) wifi:Init dynamic rx buffer num: 32
I (629) wifi_init: rx ba win: 6
I (629) wifi_init: tcpip mbox: 32
I (629) wifi_init: udp mbox: 6
I (639) wifi_init: tcp mbox: 6
I (639) wifi_init: tcp tx win: 5744
I (649) wifi_init: tcp rx win: 5744
I (649) wifi_init: tcp mss: 1440
I (649) wifi_init: WiFi IRAM OP enabled
I (659) wifi_init: WiFi RX IRAM OP enabled
I (669) phy_init: phy_version 4670,719f9f6,Feb 18 2021,17:07:07
I (769) wifi:mode : sta (94:b5:55:f2:64:f8)
I (769) wifi:enable tsf
I (769) wifi station: wifi_init_sta finished.
I (779) wifi:new:<1,0>, old:<1,0>, ap:<255,255>, sta:<1,0>, prof:1
I (779) wifi:state: init -> auth (b0)
I (789) wifi:state: auth -> assoc (0)
I (799) wifi:state: assoc -> run (10)
I (839) wifi:connected with NAM_2.4G, aid = 33, channel 1, BW20, bssid = 64:20:e0:26:2a:83
I (839) wifi:security: WPA2-PSK, phy: bgn, rssi: -61
I (849) wifi:pm start, type: 1

I (869) wifi:AP's beacon interval = 102400 us, DTIM period = 3
W (1059) wifi:<ba-add>idx:0 (ifx:0, 64:20:e0:26:2a:83), tid:0, ssn:0, winSize:64
I (2059) esp_netif_handlers: sta ip: 192.168.1.57, mask: 255.255.255.0, gw: 192.168.1.1
I (2059) wifi station: got ip:192.168.1.57
I (2059) wifi station: connected to ap SSID:NAM_2.4G password:nam24122545
W (3229) wifi:<ba-add>idx:1 (ifx:0, 64:20:e0:26:2a:83), tid:6, ssn:0, winSize:64
```
