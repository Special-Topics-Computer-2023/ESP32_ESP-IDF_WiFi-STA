	
	
	
	
	
	â†�[0;33m--- idf_monitor on \\.\COM7 115200 ---â†�[0m
	--- Quit: Ctrl+] | Menu: Ctrl+T | Help: Ctrl+T followed by Ctrl+H ---
	ets Jun  8 2016 00:22:57
	
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
	I (27) boot: compile time 17:47:23
	I (27) boot: chip revision: v1.0
	I (31) boot.esp32: SPI Speed      : 40MHz
	I (35) boot.esp32: SPI Mode       : DIO
	I (40) boot.esp32: SPI Flash Size : 2MB
	I (44) boot: Enabling RNG early entropy source...
	I (50) boot: Partition Table:
	I (53) boot: ## Label            Usage          Type ST Offset   Length
	I (61) boot:  0 nvs              WiFi data        01 02 00009000 00006000
	I (68) boot:  1 phy_init         RF data          01 01 0000f000 00001000
	I (75) boot:  2 factory          factory app      00 00 00010000 00100000
	I (83) boot: End of partition table
	I (87) esp_image: segment 0: paddr=00010020 vaddr=3f400020 size=1e630h (124464) map
	I (141) esp_image: segment 1: paddr=0002e658 vaddr=3ffb0000 size=019c0h (  6592) load
	I (143) esp_image: segment 2: paddr=00030020 vaddr=400d0020 size=7a0d0h (499920) map
	I (327) esp_image: segment 3: paddr=000aa0f8 vaddr=3ffb19c0 size=0197ch (  6524) load
	I (330) esp_image: segment 4: paddr=000aba7c vaddr=40080000 size=14c98h ( 85144) load
	I (378) boot: Loaded app from partition at offset 0x10000
	I (378) boot: Disabling RNG early entropy source...
	I (390) cpu_start: Pro cpu up.
	I (390) cpu_start: Starting app cpu, entry point is 0x400812b8
	0x400812b8: call_start_cpu1 at C:/Espressif/frameworks/esp-idf-v5.0.2/components/esp_system/port/cpu_start.c:141
	
	I (0) cpu_start: App cpu up.
	I (406) cpu_start: Pro cpu start user code
	I (406) cpu_start: cpu freq: 160000000 Hz
	I (406) cpu_start: Application information:
	I (411) cpu_start: Project name:     app-template
	I (416) cpu_start: App version:      1
	I (421) cpu_start: Compile time:     Nov  5 2023 17:46:46
	I (427) cpu_start: ELF file SHA256:  7f811ea3ea0dcd11...
	I (433) cpu_start: ESP-IDF:          v5.0.2-dirty
	I (438) cpu_start: Min chip rev:     v0.0
	I (443) cpu_start: Max chip rev:     v3.99 
	I (448) cpu_start: Chip rev:         v1.0
	I (453) heap_init: Initializing. RAM available for dynamic allocation:
	I (460) heap_init: At 3FFAE6E0 len 00001920 (6 KiB): DRAM
	I (466) heap_init: At 3FFB6FA0 len 00029060 (164 KiB): DRAM
	I (472) heap_init: At 3FFE0440 len 00003AE0 (14 KiB): D/IRAM
	I (478) heap_init: At 3FFE4350 len 0001BCB0 (111 KiB): D/IRAM
	I (485) heap_init: At 40094C98 len 0000B368 (44 KiB): IRAM
	I (493) spi_flash: detected chip: generic
	I (496) spi_flash: flash io: dio
	W (500) spi_flash: Detected size(4096k) larger than the size in the binary image header(2048k). Using the size in the binary image header.
	I (514) cpu_start: Starting scheduler on PRO CPU.
	I (0) cpu_start: Starting scheduler on APP CPU.
	I (606) wifi station: ESP_WIFI_MODE_STA
	I (626) wifi:wifi driver task: 3ffbf0f0, prio:23, stack:6656, core=0
	I (626) system_api: Base MAC address is not set
	I (626) system_api: read default base MAC address from EFUSE
	I (656) wifi:wifi firmware version: 57982fe
	I (656) wifi:wifi certification version: v7.0
	I (656) wifi:config NVS flash: enabled
	I (656) wifi:config nano formating: disabled
	I (656) wifi:Init data frame dynamic rx buffer num: 32
	I (666) wifi:Init management frame dynamic rx buffer num: 32
	I (666) wifi:Init management short buffer num: 32
	I (676) wifi:Init dynamic tx buffer num: 32
	I (676) wifi:Init static rx buffer size: 1600
	I (676) wifi:Init static rx buffer num: 10
	I (686) wifi:Init dynamic rx buffer num: 32
	I (686) wifi_init: rx ba win: 6
	I (686) wifi_init: tcpip mbox: 32
	I (696) wifi_init: udp mbox: 6
	I (696) wifi_init: tcp mbox: 6
	I (706) wifi_init: tcp tx win: 5744
	I (706) wifi_init: tcp rx win: 5744
	I (706) wifi_init: tcp mss: 1440
	I (716) wifi_init: WiFi IRAM OP enabled
	I (716) wifi_init: WiFi RX IRAM OP enabled
	I (876) phy_init: phy_version 4670,719f9f6,Feb 18 2021,17:07:07
	I (976) wifi:mode : sta (58:bf:25:8c:28:8c)
	I (976) wifi:enable tsf
	I (986) wifi station: wifi_init_sta finished.
	I (1106) wifi:new:<1,0>, old:<1,0>, ap:<255,255>, sta:<1,0>, prof:1
	I (1796) wifi:state: init -> auth (b0)
	I (1806) wifi:state: auth -> assoc (0)
	I (1816) wifi:state: assoc -> run (10)
	I (4826) wifi:state: run -> init (fc0)
	I (4826) wifi:new:<1,0>, old:<1,0>, ap:<255,255>, sta:<1,0>, prof:1
	I (4826) wifi station: retry to connect to the AP
	I (4826) wifi station: connect to the AP fail
	I (7246) wifi station: retry to connect to the AP
	I (7246) wifi station: connect to the AP fail
	I (7246) wifi:new:<1,0>, old:<1,0>, ap:<255,255>, sta:<1,0>, prof:1
	I (7246) wifi:state: init -> auth (b0)
	I (7256) wifi:state: auth -> assoc (0)
	I (7266) wifi:state: assoc -> run (10)
	I (10286) wifi:state: run -> init (fc0)
	I (10286) wifi:new:<1,0>, old:<1,0>, ap:<255,255>, sta:<1,0>, prof:1
	I (10286) wifi station: retry to connect to the AP
	I (10286) wifi station: connect to the AP fail
	I (12696) wifi station: retry to connect to the AP
	I (12696) wifi station: connect to the AP fail
	I (12706) wifi:new:<1,0>, old:<1,0>, ap:<255,255>, sta:<1,0>, prof:1
	I (12706) wifi:state: init -> auth (b0)
	I (12716) wifi:state: auth -> assoc (0)
	I (12726) wifi:state: assoc -> run (10)
	I (15736) wifi:state: run -> init (fc0)
	I (15736) wifi:new:<1,0>, old:<1,0>, ap:<255,255>, sta:<1,0>, prof:1
	I (15746) wifi station: retry to connect to the AP
	I (15746) wifi station: connect to the AP fail
	I (18156) wifi station: connect to the AP fail
	I (18156) wifi station: Failed to connect to SSID:p_pl_phongsiri_, password:160146
