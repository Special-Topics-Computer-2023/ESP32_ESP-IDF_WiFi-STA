# 64030165 Ratchanon
-repo https://github.com/RatchanonBusaracome/ESP32_ESP-IDF_WiFi-STA.git

## Terminal output

เชื่อมต่อ ESP32 กับ Access point

```css
I (31) boot: ESP-IDF v5.1.1-dirty 2nd stage bootloader
I (31) boot: compile time Oct 21 2023 16:27:48
I (31) boot: Multicore bootloader
I (36) boot: chip revision: v3.0
I (40) boot.esp32: SPI Speed      : 40MHz
I (44) boot.esp32: SPI Mode       : DIO
I (49) boot.esp32: SPI Flash Size : 2MB
I (53) boot: Enabling RNG early entropy source...
I (59) boot: Partition Table:
I (62) boot: ## Label            Usage          Type ST Offset   Length
I (70) boot:  0 nvs              WiFi data        01 02 00009000 00006000
I (77) boot:  1 phy_init         RF data          01 01 0000f000 00001000
I (85) boot:  2 factory          factory app      00 00 00010000 00100000
I (92) boot: End of partition table
I (96) esp_image: segment 0: paddr=00010020 vaddr=3f400020 size=1fe6ch (130668) map
I (152) esp_image: segment 1: paddr=0002fe94 vaddr=3ffb0000 size=00184h (   388) load
I (152) esp_image: segment 2: paddr=00030020 vaddr=400d0020 size=7f244h (520772) map
I (346) esp_image: segment 3: paddr=000af26c vaddr=3ffb0184 size=03534h ( 13620) load
I (351) esp_image: segment 4: paddr=000b27a8 vaddr=40080000 size=156e0h ( 87776) load
I (399) boot: Loaded app from partition at offset 0x10000
I (399) boot: Disabling RNG early entropy source...
I (410) cpu_start: Multicore app
I (411) cpu_start: Pro cpu up.
I (411) cpu_start: Starting app cpu, entry point is 0x4008137c
0x4008137c: call_start_cpu1 at C:/Espressif/frameworks/esp-idf-v5.1.1/components/esp_system/port/cpu_start.c:154

I (0) cpu_start: App cpu up.
I (429) cpu_start: Pro cpu start user code
I (429) cpu_start: cpu freq: 160000000 Hz
I (429) cpu_start: Application information:
I (433) cpu_start: Project name:     ESP32_ESP-IDF_WiFi-STA
I (440) cpu_start: App version:      1
I (444) cpu_start: Compile time:     Oct 21 2023 16:27:56
I (450) cpu_start: ELF file SHA256:  22b63699698bcabc...
I (456) cpu_start: ESP-IDF:          v5.1.1-dirty
I (462) cpu_start: Min chip rev:     v0.0
I (466) cpu_start: Max chip rev:     v3.99 
I (471) cpu_start: Chip rev:         v3.0
I (476) heap_init: Initializing. RAM available for dynamic allocation:
I (483) heap_init: At 3FFAE6E0 len 00001920 (6 KiB): DRAM
I (489) heap_init: At 3FFB7788 len 00028878 (162 KiB): DRAM
I (495) heap_init: At 3FFE0440 len 00003AE0 (14 KiB): D/IRAM
I (502) heap_init: At 3FFE4350 len 0001BCB0 (111 KiB): D/IRAM
I (508) heap_init: At 400956E0 len 0000A920 (42 KiB): IRAM
I (516) spi_flash: detected chip: generic
I (519) spi_flash: flash io: dio
W (523) spi_flash: Detected size(4096k) larger than the size in the binary image header(2048k). Using the size in the binary image header.
I (537) app_start: Starting scheduler on CPU0
I (541) app_start: Starting scheduler on CPU1
I (541) main_task: Started on CPU0
I (551) main_task: Calling app_main()
I (591) wifi station: ESP_WIFI_MODE_STA
I (601) wifi:wifi driver task: 3ffbf780, prio:23, stack:6656, core=0
I (621) wifi:wifi firmware version: ce9244d
I (621) wifi:wifi certification version: v7.0
I (621) wifi:config NVS flash: enabled
I (621) wifi:config nano formating: disabled
I (631) wifi:Init data frame dynamic rx buffer num: 32
I (631) wifi:Init management frame dynamic rx buffer num: 32
I (641) wifi:Init management short buffer num: 32
I (641) wifi:Init dynamic tx buffer num: 32
I (641) wifi:Init static rx buffer size: 1600
I (651) wifi:Init static rx buffer num: 10
I (651) wifi:Init dynamic rx buffer num: 32
I (661) wifi_init: rx ba win: 6
I (661) wifi_init: tcpip mbox: 32
I (661) wifi_init: udp mbox: 6
I (671) wifi_init: tcp mbox: 6
I (671) wifi_init: tcp tx win: 5744
I (681) wifi_init: tcp rx win: 5744
I (681) wifi_init: tcp mss: 1440
I (681) wifi_init: WiFi IRAM OP enabled
I (691) wifi_init: WiFi RX IRAM OP enabled
I (701) phy_init: phy_version 4670,719f9f6,Feb 18 2021,17:07:07

Brownout detector was triggered

ets Jul 29 2019 12:21:46

rst:0xc (SW_CPU_RESET),boot:0x13 (SPI_FAST_FLASH_BOOT)
configsip: 0, SPIWP:0xee
clk_drv:0x00,q_drv:0x00,d_drv:0x00,cs0_drv:0x00,hd_drv:0x00,wp_drv:0x00
mode:DIO, clock div:2
load:0x3fff0030,len:7084
ho 0 tail 12 room 4
load:0x40078000,len:15584
load:0x40080400,len:4
0x40080400: _init at ??:?

load:0x40080404,len:3876
entry 0x4008064c
I (31) boot: ESP-IDF v5.1.1-dirty 2nd stage bootloader
I (31) boot: compile time Oct 21 2023 16:27:48
I (31) boot: Multicore bootloader
I (36) boot: chip revision: v3.0
I (40) boot.esp32: SPI Speed      : 40MHz
I (44) boot.esp32: SPI Mode       : DIO
I (49) boot.esp32: SPI Flash Size : 2MB
I (53) boot: Enabling RNG early entropy source...
I (59) boot: Partition Table:
I (62) boot: ## Label            Usage          Type ST Offset   Length
I (70) boot:  0 nvs              WiFi data        01 02 00009000 00006000
I (77) boot:  1 phy_init         RF data          01 01 0000f000 00001000
I (85) boot:  2 factory          factory app      00 00 00010000 00100000
I (92) boot: End of partition table
I (96) esp_image: segment 0: paddr=00010020 vaddr=3f400020 size=1fe6ch (130668) map
I (152) esp_image: segment 1: paddr=0002fe94 vaddr=3ffb0000 size=00184h (   388) load
I (152) esp_image: segment 2: paddr=00030020 vaddr=400d0020 size=7f244h (520772) map
I (346) esp_image: segment 3: paddr=000af26c vaddr=3ffb0184 size=03534h ( 13620) load
I (351) esp_image: segment 4: paddr=000b27a8 vaddr=40080000 size=156e0h ( 87776) load
I (399) boot: Loaded app from partition at offset 0x10000
I (399) boot: Disabling RNG early entropy source...
I (410) cpu_start: Multicore app
I (411) cpu_start: Pro cpu up.
I (411) cpu_start: Starting app cpu, entry point is 0x4008137c
0x4008137c: call_start_cpu1 at C:/Espressif/frameworks/esp-idf-v5.1.1/components/esp_system/port/cpu_start.c:154

I (398) cpu_start: App cpu up.
I (429) cpu_start: Pro cpu start user code
I (429) cpu_start: cpu freq: 160000000 Hz
I (429) cpu_start: Application information:
I (434) cpu_start: Project name:     ESP32_ESP-IDF_WiFi-STA
I (440) cpu_start: App version:      1
I (444) cpu_start: Compile time:     Oct 21 2023 16:27:56
I (450) cpu_start: ELF file SHA256:  22b63699698bcabc...
I (456) cpu_start: ESP-IDF:          v5.1.1-dirty
I (462) cpu_start: Min chip rev:     v0.0
I (466) cpu_start: Max chip rev:     v3.99 
I (471) cpu_start: Chip rev:         v3.0
I (476) heap_init: Initializing. RAM available for dynamic allocation:
I (483) heap_init: At 3FFAE6E0 len 00001920 (6 KiB): DRAM
I (489) heap_init: At 3FFB7788 len 00028878 (162 KiB): DRAM
I (495) heap_init: At 3FFE0440 len 00003AE0 (14 KiB): D/IRAM
I (502) heap_init: At 3FFE4350 len 0001BCB0 (111 KiB): D/IRAM
I (508) heap_init: At 400956E0 len 0000A920 (42 KiB): IRAM
I (516) spi_flash: detected chip: generic
I (519) spi_flash: flash io: dio
W (523) spi_flash: Detected size(4096k) larger than the size in the binary image header(2048k). Using the size in the binary image header.
I (537) app_start: Starting scheduler on CPU0
I (541) app_start: Starting scheduler on CPU1
I (541) main_task: Started on CPU0
I (551) main_task: Calling app_main()
I (591) wifi station: ESP_WIFI_MODE_STA
I (601) wifi:wifi driver task: 3ffbf780, prio:23, stack:6656, core=0
I (621) wifi:wifi firmware version: ce9244d
I (621) wifi:wifi certification version: v7.0
I (621) wifi:config NVS flash: enabled
I (621) wifi:config nano formating: disabled
I (631) wifi:Init data frame dynamic rx buffer num: 32
I (631) wifi:Init management frame dynamic rx buffer num: 32
I (641) wifi:Init management short buffer num: 32
I (641) wifi:Init dynamic tx buffer num: 32
I (641) wifi:Init static rx buffer size: 1600
I (651) wifi:Init static rx buffer num: 10
I (651) wifi:Init dynamic rx buffer num: 32
I (661) wifi_init: rx ba win: 6
I (661) wifi_init: tcpip mbox: 32
I (661) wifi_init: udp mbox: 6
I (671) wifi_init: tcp mbox: 6
I (671) wifi_init: tcp tx win: 5744
I (681) wifi_init: tcp rx win: 5744
I (681) wifi_init: tcp mss: 1440
I (681) wifi_init: WiFi IRAM OP enabled
I (691) wifi_init: WiFi RX IRAM OP enabled
I (701) phy_init: phy_version 4670,719f9f6,Feb 18 2021,17:07:07
I (801) wifi:mode : sta (94:b5:55:f8:30:00)
I (801) wifi:enable tsf
I (801) wifi station: wifi_init_sta finished.
I (1541) wifi:new:<6,0>, old:<1,0>, ap:<255,255>, sta:<6,0>, prof:1
I (1541) wifi:state: init -> auth (b0)
I (2771) wifi:state: auth -> assoc (0)
I (2781) wifi:state: assoc -> run (10)
I (2871) wifi:connected with iPhone 15pro max, aid = 2, channel 6, BW20, bssid = a6:ed:bb:e4:8c:1c
I (2871) wifi:security: WPA3-SAE, phy: bgn, rssi: -47
I (2951) wifi:pm start, type: 1

I (2951) wifi:AP's beacon interval = 102400 us, DTIM period = 1
I (3151) wifi:<ba-add>idx:0 (ifx:0, a6:ed:bb:e4:8c:1c), tid:0, ssn:2, winSize:64
I (3961) esp_netif_handlers: sta ip: 172.20.10.13, mask: 255.255.255.240, gw: 172.20.10.1
I (3961) wifi station: got ip:172.20.10.13
I (3961) wifi station: connected to ap SSID:iPhone 15pro max password:12345678
I (3971) main_task: Returned from app_main()
```
