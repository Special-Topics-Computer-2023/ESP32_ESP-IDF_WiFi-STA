## repo 
https://github.com/64030301nam/Wifi-STA
## code
```
Executing action: monitor
Running idf_monitor in directory c:\espressif\frameworks\esp-idf-v4.4.2\workspace\esp32-wifi-sta
Executing "C:\Espressif\python_env\idf4.4_py3.8_env\Scripts\python.exe C:/Espressif/frameworks/esp-idf-v4.4.2/tools/idf_monitor.py -p \\.\COM3 -b 115200 --toolchain-prefix xtensa-esp32-elf- --target esp32 --revision 0 --print_filter  c:\espressif\frameworks\esp-idf-v4.4.2\workspace\esp32-wifi-sta\build\ESP32-WIFI-STA.elf -m 'C:\Espressif\python_env\idf4.4_py3.8_env\Scripts\python.exe' 'C:\Espressif\frameworks\esp-idf-v4.4.2\tools\idf.py'"...
â†�[0;33m--- idf_monitor on \\.\COM3 115200 ---â†�[0m
--- Quit: Ctrl+] | Menu: Ctrl+T | Help: Ctrl+T followed by Ctrl+H ---
ets Jul 29 2019 12:21:46

rst:0x1 (POWERON_RESET),boot:0x13 (SPI_FAST_FLASH_BOOT)
configsip: 0, SPIWP:0xee
clk_drv:0x00,q_drv:0x00,d_drv:0x00,cs0_drv:0x00,hd_drv:0x00,wp_drv:0x00
mode:DIO, clock div:2
load:0x3fff0030,len:6680
load:0x40078000,len:14848
load:0x40080400,len:3792
0x40080400: _init at ??:?

entry 0x40080694
I (27) boot: ESP-IDF v4.4.2-1-gdcdd2cb866-dirty 2nd stage bootloader
I (27) boot: compile time 00:51:02
I (27) boot: chip revision: 3
I (32) boot_comm: chip revision: 3, min. bootloader chip revision: 0
I (39) boot.esp32: SPI Speed      : 40MHz
I (44) boot.esp32: SPI Mode       : DIO
I (48) boot.esp32: SPI Flash Size : 2MB
I (53) boot: Enabling RNG early entropy source...
I (58) boot: Partition Table:
I (62) boot: ## Label            Usage          Type ST Offset   Length
I (69) boot:  0 nvs              WiFi data        01 02 00009000 00006000
I (76) boot:  1 phy_init         RF data          01 01 0000f000 00001000
I (84) boot:  2 factory          factory app      00 00 00010000 00100000
I (91) boot: End of partition table
I (95) boot_comm: chip revision: 3, min. application chip revision: 0
I (103) esp_image: segment 0: paddr=00010020 vaddr=3f400020 size=12d0ch ( 77068) map
I (139) esp_image: segment 1: paddr=00022d34 vaddr=3ffb0000 size=03804h ( 14340) load
I (145) esp_image: segment 2: paddr=00026540 vaddr=40080000 size=09ad8h ( 39640) load
I (161) esp_image: segment 3: paddr=00030020 vaddr=400d0020 size=6d458h (447576) map
I (324) esp_image: segment 4: paddr=0009d480 vaddr=40089ad8 size=0aa08h ( 43528) load
I (342) esp_image: segment 5: paddr=000a7e90 vaddr=50000000 size=00010h (    16) load
I (352) boot: Loaded app from partition at offset 0x10000
I (352) boot: Disabling RNG early entropy source...
I (364) cpu_start: Pro cpu up.
I (364) cpu_start: Starting app cpu, entry point is 0x40081198
0x40081198: call_start_cpu1 at C:/Espressif/frameworks/esp-idf-v4.4.2/components/esp_system/port/cpu_start.c:160

I (0) cpu_start: App cpu up.
I (381) cpu_start: Pro cpu start user code
I (381) cpu_start: cpu freq: 160000000
I (381) cpu_start: Application information:
I (385) cpu_start: Project name:     ESP32-WIFI-STA
I (391) cpu_start: App version:      c7015ec
I (396) cpu_start: Compile time:     Nov 13 2023 00:50:45
I (402) cpu_start: ELF file SHA256:  d3199e85a70642d5...
I (408) cpu_start: ESP-IDF:          v4.4.2-1-gdcdd2cb866-dirty
I (415) heap_init: Initializing. RAM available for dynamic allocation:
I (422) heap_init: At 3FFAE6E0 len 00001920 (6 KiB): DRAM
I (428) heap_init: At 3FFB74D0 len 00028B30 (162 KiB): DRAM
I (434) heap_init: At 3FFE0440 len 00003AE0 (14 KiB): D/IRAM
I (440) heap_init: At 3FFE4350 len 0001BCB0 (111 KiB): D/IRAM
I (447) heap_init: At 400944E0 len 0000BB20 (46 KiB): IRAM
I (454) spi_flash: detected chip: generic
I (458) spi_flash: flash io: dio
W (462) spi_flash: Detected size(4096k) larger than the size in the binary image header(2048k). Using the size in the binary image header.
I (476) cpu_start: Starting scheduler on PRO CPU.
I (0) cpu_start: Starting scheduler on APP CPU.
I (560) wifi station: ESP_WIFI_MODE_STA
I (570) wifi:wifi driver task: 3ffc01bc, prio:23, stack:6656, core=0
I (570) system_api: Base MAC address is not set
I (570) system_api: read default base MAC address from EFUSE
I (590) wifi:wifi firmware version: eeaa27d
I (590) wifi:wifi certification version: v7.0
I (590) wifi:config NVS flash: enabled
I (590) wifi:config nano formating: disabled
I (600) wifi:Init data frame dynamic rx buffer num: 32
I (600) wifi:Init management frame dynamic rx buffer num: 32
I (610) wifi:Init management short buffer num: 32
I (610) wifi:Init dynamic tx buffer num: 32
I (610) wifi:Init static rx buffer size: 1600
I (620) wifi:Init static rx buffer num: 10
I (620) wifi:Init dynamic rx buffer num: 32
I (630) wifi_init: rx ba win: 6
I (630) wifi_init: tcpip mbox: 32
I (630) wifi_init: udp mbox: 6
I (640) wifi_init: tcp mbox: 6
I (640) wifi_init: tcp tx win: 5744
I (650) wifi_init: tcp rx win: 5744
I (650) wifi_init: tcp mss: 1440
I (650) wifi_init: WiFi IRAM OP enabled
I (660) wifi_init: WiFi RX IRAM OP enabled
I (670) phy_init: phy_version 4670,719f9f6,Feb 18 2021,17:07:07
I (770) wifi:mode : sta (94:b5:55:f2:64:f8)
I (770) wifi:enable tsf
I (770) wifi station: wifi_init_sta finished.
I (780) wifi:new:<1,0>, old:<1,0>, ap:<255,255>, sta:<1,0>, prof:1
I (780) wifi:state: init -> auth (b0)
I (790) wifi:state: auth -> assoc (0)
I (800) wifi:state: assoc -> run (10)
I (830) wifi:connected with NAM_2.4G, aid = 36, channel 1, BW20, bssid = 64:20:e0:26:2a:83
I (830) wifi:security: WPA2-PSK, phy: bgn, rssi: -56
I (830) wifi:pm start, type: 1

I (850) wifi:AP's beacon interval = 102400 us, DTIM period = 3
W (870) wifi:<ba-add>idx:0 (ifx:0, 64:20:e0:26:2a:83), tid:0, ssn:0, winSize:64
I (1560) esp_netif_handlers: sta ip: 192.168.1.57, mask: 255.255.255.0, gw: 192.168.1.1
I (1560) wifi station: got ip:192.168.1.57
I (1560) wifi station: connected to ap SSID:NAM_2.4G password:nam24122545
W (68030) wifi:<ba-add>idx:1 (ifx:0, 64:20:e0:26:2a:83), tid:6, ssn:0, winSize:64
```

## ผลลัพธ์
![image](https://github.com/64030301nam/ESP32_ESP-IDF_WiFi-STA/assets/115066329/44e854bd-c5ef-4390-bac5-e6d485853bb8)


