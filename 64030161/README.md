# 64030161 Rachata

## Terminal output

เชื่อมต่อ ESP32 กับ Access point

```css
entry 0x40080698
I (27) boot: ESP-IDF v4.4.5-dirty 2nd stage bootloader
I (27) boot: compile time 09:54:14
I (27) boot: chip revision: v3.0
I (31) boot.esp32: SPI Speed      : 40MHz
I (36) boot.esp32: SPI Mode       : DIO
I (40) boot.esp32: SPI Flash Size : 4MB
I (45) boot: Enabling RNG early entropy source...
I (50) boot: Partition Table:
I (54) boot: ## Label            Usage          Type ST Offset   Length
I (61) boot:  0 nvs              WiFi data        01 02 00009000 00006000
I (68) boot:  1 phy_init         RF data          01 01 0000f000 00001000
I (76) boot:  2 factory          factory app      00 00 00010000 00100000
I (83) boot: End of partition table
I (88) esp_image: segment 0: paddr=00010020 vaddr=3f400020 size=13f94h ( 81812) map
I (126) esp_image: segment 1: paddr=00023fbc vaddr=3ffb0000 size=03038h ( 12344) load
I (131) esp_image: segment 2: paddr=00026ffc vaddr=40080000 size=0901ch ( 36892) load
I (147) esp_image: segment 3: paddr=00030020 vaddr=400d0020 size=704d8h (459992) map
I (313) esp_image: segment 4: paddr=000a0500 vaddr=4008901c size=0b89ch ( 47260) load
I (343) boot: Loaded app from partition at offset 0x10000
I (343) boot: Disabling RNG early entropy source...
I (354) cpu_start: Pro cpu up.
I (355) cpu_start: Starting app cpu, entry point is 0x4008117c
0x4008117c: call_start_cpu1 at /Users/rachatasupanurak/esp/esp-idf/components/esp_system/port/cpu_start.c:147

I (0) cpu_start: App cpu up.
I (369) cpu_start: Pro cpu start user code
I (369) cpu_start: cpu freq: 160000000
I (369) cpu_start: Application information:
I (373) cpu_start: Project name:     ESP-WiFi-STA
I (379) cpu_start: App version:      bcdd469-dirty
I (384) cpu_start: Compile time:     Sep 11 2023 09:53:34
I (390) cpu_start: ELF file SHA256:  218501f68c50401a...
I (396) cpu_start: ESP-IDF:          v4.4.5-dirty
I (402) cpu_start: Min chip rev:     v0.0
I (406) cpu_start: Max chip rev:     v3.99 
I (411) cpu_start: Chip rev:         v3.0
I (416) heap_init: Initializing. RAM available for dynamic allocation:
I (423) heap_init: At 3FFAE6E0 len 00001920 (6 KiB): DRAM
I (429) heap_init: At 3FFB6CA8 len 00029358 (164 KiB): DRAM
I (435) heap_init: At 3FFE0440 len 00003AE0 (14 KiB): D/IRAM
I (442) heap_init: At 3FFE4350 len 0001BCB0 (111 KiB): D/IRAM
I (448) heap_init: At 400948B8 len 0000B748 (45 KiB): IRAM
I (456) spi_flash: detected chip: generic
I (459) spi_flash: flash io: dio
I (464) cpu_start: Starting scheduler on PRO CPU.
I (0) cpu_start: Starting scheduler on APP CPU.
I (534) wifi station: ESP_WIFI_MODE_STA
I (544) wifi:wifi driver task: 3ffbf11c, prio:23, stack:6656, core=0
I (544) system_api: Base MAC address is not set
I (544) system_api: read default base MAC address from EFUSE
I (564) wifi:wifi firmware version: 0f80fa0
I (564) wifi:wifi certification version: v7.0
I (564) wifi:config NVS flash: enabled
I (564) wifi:config nano formating: disabled
I (564) wifi:Init data frame dynamic rx buffer num: 32
I (574) wifi:Init management frame dynamic rx buffer num: 32
I (574) wifi:Init management short buffer num: 32
I (584) wifi:Init dynamic tx buffer num: 32
I (584) wifi:Init static rx buffer size: 1600
I (594) wifi:Init static rx buffer num: 10
I (594) wifi:Init dynamic rx buffer num: 32
I (594) wifi_init: rx ba win: 6
I (604) wifi_init: tcpip mbox: 32
I (604) wifi_init: udp mbox: 6
I (604) wifi_init: tcp mbox: 6
I (614) wifi_init: tcp tx win: 5744
I (614) wifi_init: tcp rx win: 5744
I (624) wifi_init: tcp mss: 1440
I (624) wifi_init: WiFi IRAM OP enabled
I (624) wifi_init: WiFi RX IRAM OP enabled
I (664) phy_init: phy_version 4670,719f9f6,Feb 18 2021,17:07:07
W (664) phy_init: failed to load RF calibration data (0x1102), falling back to full calibration
I (824) wifi:mode : sta (24:d7:eb:0e:cb:20)
I (824) wifi:enable tsf
I (824) wifi station: wifi_init_sta finished.
I (2064) wifi:new:<11,0>, old:<1,0>, ap:<255,255>, sta:<11,0>, prof:1
I (2814) wifi:state: init -> auth (b0)
I (2864) wifi:state: auth -> assoc (0)
I (2984) wifi:state: assoc -> run (10)
I (3014) wifi:connected with WiFi_042344, aid = 7, channel 11, BW20, bssid = 30:0a:c5:9e:ff:36
I (3014) wifi:security: WPA2-PSK, phy: bgn, rssi: -59
I (3024) wifi:pm start, type: 1

I (3104) wifi:AP's beacon interval = 102400 us, DTIM period = 1
I (4344) wifi:<ba-add>idx:0 (ifx:0, 30:0a:c5:9e:ff:36), tid:0, ssn:2, winSize:64
I (7534) esp_netif_handlers: sta ip: 192.168.1.195, mask: 255.255.255.0, gw: 192.168.1.1
I (7534) wifi station: got ip:192.168.1.195
I (7534) wifi station: connected to ap SSID:WiFi_042344 password:51042344
I (42094) wifi:<ba-add>idx:1 (ifx:0, 30:0a:c5:9e:ff:36), tid:6, ssn:0, winSize:64
```
