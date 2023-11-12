## Repo
https://github.com/PiyatidaPh/ESP32_ESP-IDF_WiFi-STA
## Terminal output
เชื่อมต่อ ESP32 กับ Access point

```css
entry 0x4008064c
I (27) boot: ESP-IDF v5.0.2-dirty 2nd stage bootloader
I (27) boot: compile time 01:07:31
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
I (144) esp_image: segment 2: paddr=00030020 vaddr=400d0020 size=7a0d0h (499920) map
I (327) esp_image: segment 3: paddr=000aa0f8 vaddr=3ffb19c0 size=0197ch (  6524) load
I (330) esp_image: segment 4: paddr=000aba7c vaddr=40080000 size=14c98h ( 85144) load
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
I (417) cpu_start: App version:      39179a4-dirty
I (422) cpu_start: Compile time:     Nov 12 2023 01:06:54
I (428) cpu_start: ELF file SHA256:  167ffdf04af066f9...
I (434) cpu_start: ESP-IDF:          v5.0.2-dirty
I (440) cpu_start: Min chip rev:     v0.0
I (444) cpu_start: Max chip rev:     v3.99 
I (449) cpu_start: Chip rev:         v3.0
I (454) heap_init: Initializing. RAM available for dynamic allocation:
I (461) heap_init: At 3FFAE6E0 len 00001920 (6 KiB): DRAM
I (467) heap_init: At 3FFB6FA0 len 00029060 (164 KiB): DRAM
I (473) heap_init: At 3FFE0440 len 00003AE0 (14 KiB): D/IRAM
I (480) heap_init: At 3FFE4350 len 0001BCB0 (111 KiB): D/IRAM
I (486) heap_init: At 40094C98 len 0000B368 (44 KiB): IRAM
I (494) spi_flash: detected chip: generic
I (497) spi_flash: flash io: dio
W (501) spi_flash: Detected size(4096k) larger than the size in the binary image header(2048k). Using the size in the binary image header.
I (515) cpu_start: Starting scheduler on PRO CPU.
I (0) cpu_start: Starting scheduler on APP CPU.
I (602) wifi station: ESP_WIFI_MODE_STA
I (612) wifi:wifi driver task: 3ffbf08c, prio:23, stack:6656, core=0
I (612) system_api: Base MAC address is not set
I (612) system_api: read default base MAC address from EFUSE
I (632) wifi:wifi firmware version: 57982fe
I (632) wifi:wifi certification version: v7.0
I (632) wifi:config NVS flash: enabled
I (632) wifi:config nano formating: disabled
I (642) wifi:Init data frame dynamic rx buffer num: 32
I (642) wifi:Init management frame dynamic rx buffer num: 32
I (652) wifi:Init management short buffer num: 32
I (652) wifi:Init dynamic tx buffer num: 32
I (662) wifi:Init static rx buffer size: 1600
I (662) wifi:Init static rx buffer num: 10
I (662) wifi:Init dynamic rx buffer num: 32
I (672) wifi_init: rx ba win: 6
I (672) wifi_init: tcpip mbox: 32
I (682) wifi_init: udp mbox: 6
I (682) wifi_init: tcp mbox: 6
I (682) wifi_init: tcp tx win: 5744
I (692) wifi_init: tcp rx win: 5744
I (692) wifi_init: tcp mss: 1440
I (702) wifi_init: WiFi IRAM OP enabled
I (702) wifi_init: WiFi RX IRAM OP enabled
I (732) phy_init: phy_version 4670,719f9f6,Feb 18 2021,17:07:07
I (832) wifi:mode : sta (94:b5:55:f6:f5:90)
I (832) wifi:enable tsf
I (832) wifi station: wifi_init_sta finished.
I (842) wifi:new:<6,0>, old:<1,0>, ap:<255,255>, sta:<6,0>, prof:1
I (1522) wifi:state: init -> auth (b0)
I (1542) wifi:state: auth -> assoc (0)
I (1582) wifi:state: assoc -> run (10)
I (1612) wifi:connected with PalmSoCute, aid = 1, channel 6, BW20, bssid = 3e:61:cb:7a:c7:ec
I (1612) wifi:security: WPA2-PSK, phy: bgn, rssi: -62
I (1632) wifi:pm start, type: 1

I (1642) wifi:<ba-add>idx:0 (ifx:0, 3e:61:cb:7a:c7:ec), tid:0, ssn:2, winSize:64
I (1692) wifi:AP's beacon interval = 102400 us, DTIM period = 1
I (2632) esp_netif_handlers: sta ip: 172.20.10.8, mask: 255.255.255.240, gw: 172.20.10.1
I (2632) wifi station: got ip:172.20.10.8
I (2632) wifi station: connected to ap SSID:PalmSoCute password:0972840460
```
