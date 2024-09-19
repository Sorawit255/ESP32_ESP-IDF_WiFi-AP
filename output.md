```log
load:0x40080404,len:3904
entry 0x40080640
I (31) boot: ESP-IDF v5.3.1 2nd stage bootloader
I (31) boot: compile time Sep 19 2024 14:41:36
I (31) boot: Multicore bootloader
I (35) boot: chip revision: v3.0
I (39) boot.esp32: SPI Speed      : 40MHz
I (44) boot.esp32: SPI Mode       : DIO
I (48) boot.esp32: SPI Flash Size : 2MB
I (53) boot: Enabling RNG early entropy source...
I (58) boot: Partition Table:
I (62) boot: ## Label            Usage          Type ST Offset   Length
I (69) boot:  0 nvs              WiFi data        01 02 00009000 00006000
I (77) boot:  1 phy_init         RF data          01 01 0000f000 00001000
I (84) boot:  2 factory          factory app      00 00 00010000 00100000
I (92) boot: End of partition table
I (96) esp_image: segment 0: paddr=00010020 vaddr=3f400020 size=1f35ch (127836) map
I (148) esp_image: segment 1: paddr=0002f384 vaddr=3ffb0000 size=00c94h (  3220) load
I (150) esp_image: segment 2: paddr=00030020 vaddr=400d0020 size=82b98h (535448) map
I (337) esp_image: segment 3: paddr=000b2bc0 vaddr=3ffb0c94 size=0323ch ( 12860) load
I (342) esp_image: segment 4: paddr=000b5e04 vaddr=40080000 size=1734ch ( 95052) load
I (392) boot: Loaded app from partition at offset 0x10000
I (392) boot: Disabling RNG early entropy source...
I (404) cpu_start: Multicore app
I (412) cpu_start: Pro cpu start user code
I (412) cpu_start: cpu freq: 160000000 Hz
I (413) app_init: Application information:
I (415) app_init: Project name:     ESP32_ESP-IDF_WiFi-AP
I (421) app_init: App version:      1
I (426) app_init: Compile time:     Sep 19 2024 14:43:28
I (432) app_init: ELF file SHA256:  3120dc973...
I (437) app_init: ESP-IDF:          v5.3.1
I (442) efuse_init: Min chip rev:     v0.0
I (447) efuse_init: Max chip rev:     v3.99 
I (452) efuse_init: Chip rev:         v3.0
I (457) heap_init: Initializing. RAM available for dynamic allocation:
I (464) heap_init: At 3FFAE6E0 len 00001920 (6 KiB): DRAM
I (470) heap_init: At 3FFB80F8 len 00027F08 (159 KiB): DRAM
I (476) heap_init: At 3FFE0440 len 00003AE0 (14 KiB): D/IRAM
I (482) heap_init: At 3FFE4350 len 0001BCB0 (111 KiB): D/IRAM
I (489) heap_init: At 4009734C len 00008CB4 (35 KiB): IRAM
I (496) spi_flash: detected chip: generic
I (500) spi_flash: flash io: dio
W (503) spi_flash: Detected size(4096k) larger than the size in the binary image header(2048k). Using the size in the binary image header.
I (518) main_task: Started on CPU0
I (528) main_task: Calling app_main()
I (548) wifi softAP: ESP_WIFI_MODE_AP
I (558) wifi:wifi driver task: 3ffc0150, prio:23, stack:6656, core=0
I (568) wifi:wifi firmware version: ccaebfa
I (568) wifi:wifi certification version: v7.0
I (568) wifi:config NVS flash: enabled
I (568) wifi:config nano formating: disabled
I (568) wifi:Init data frame dynamic rx buffer num: 32
I (578) wifi:Init static rx mgmt buffer num: 5
I (578) wifi:Init management short buffer num: 32
I (588) wifi:Init dynamic tx buffer num: 32
I (588) wifi:Init static rx buffer size: 1600
I (598) wifi:Init static rx buffer num: 10
I (598) wifi:Init dynamic rx buffer num: 32
I (598) wifi_init: rx ba win: 6
I (608) wifi_init: accept mbox: 6
I (608) wifi_init: tcpip mbox: 32
I (618) wifi_init: udp mbox: 6
I (618) wifi_init: tcp mbox: 6
I (618) wifi_init: tcp tx win: 5760
I (628) wifi_init: tcp rx win: 5760
I (628) wifi_init: tcp mss: 1440
I (628) wifi_init: WiFi IRAM OP enabled
I (638) wifi_init: WiFi RX IRAM OP enabled
I (918) phy_init: phy_version 4830,54550f7,Jun 20 2024,14:22:08
I (988) wifi:mode : softAP (24:d7:eb:0e:d0:95)
I (1098) wifi:Total power save buffer number: 16
I (1098) wifi:Init max length of beacon: 752/752
I (1098) wifi:Init max length of beacon: 752/752
I (1098) wifi softAP: wifi_init_softap finished. SSID:myssid-255 password:12345678 channel:1
I (1098) esp_netif_lwip: DHCP server started on interface WIFI_AP_DEF with IP: 192.168.4.1
I (1118) main_task: Returned from app_main()
I (52358) wifi:new:<1,0>, old:<1,1>, ap:<1,1>, sta:<255,255>, prof:1, snd_ch_cfg:0x0
I (52358) wifi:station: fa:a6:13:cd:af:ec join, AID=1, bgn, 20
I (52378) wifi softAP: station fa:a6:13:cd:af:ec join, AID=1
I (53738) esp_netif_lwip: DHCP server assigned IP to a client, IP is: 192.168.4.2
I (55638) wifi:<ba-add>idx:2 (ifx:1, fa:a6:13:cd:af:ec), tid:0, ssn:2, winSize:64
```