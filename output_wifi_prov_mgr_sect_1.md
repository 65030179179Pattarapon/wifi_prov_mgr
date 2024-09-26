I (31) boot: ESP-IDF v5.3.1 2nd stage bootloader
I (31) boot: compile time Sep 26 2024 15:16:45
I (31) boot: Multicore bootloader
I (35) boot: chip revision: v1.0
I (39) boot.esp32: SPI Speed      : 40MHz
I (44) boot.esp32: SPI Mode       : DIO
I (48) boot.esp32: SPI Flash Size : 2MB
I (53) boot: Enabling RNG early entropy source...
I (58) boot: Partition Table:
I (62) boot: ## Label            Usage          Type ST Offset   Length
I (69) boot:  0 nvs              WiFi data        01 02 00009000 00006000
I (77) boot:  1 phy_init         RF data          01 01 0000f000 00001000
I (84) boot:  2 factory          factory app      00 00 00010000 00140000
I (92) boot: End of partition table
I (96) esp_image: segment 0: paddr=00010020 vaddr=3f400020 size=2b8d8h (178392) map
I (165) esp_image: segment 1: paddr=0003b900 vaddr=3ffbdb60 size=04718h ( 18200) load
I (172) esp_image: segment 2: paddr=00040020 vaddr=400d0020 size=bb524h (767268) map
I (436) esp_image: segment 3: paddr=000fb54c vaddr=3ffc2278 size=014c8h (  5320) load
I (438) esp_image: segment 4: paddr=000fca1c vaddr=40080000 size=1bfc0h (114624) load
I (500) boot: Loaded app from partition at offset 0x10000
I (501) boot: Disabling RNG early entropy source...
I (513) cpu_start: Multicore app
I (521) cpu_start: Pro cpu start user code
I (521) cpu_start: cpu freq: 160000000 Hz
I (521) app_init: Application information:
I (524) app_init: Project name:     wifi_prov_mgr
I (529) app_init: App version:      1
I (534) app_init: Compile time:     Sep 26 2024 15:16:26
I (540) app_init: ELF file SHA256:  9dc738dfa...
I (545) app_init: ESP-IDF:          v5.3.1
I (550) efuse_init: Min chip rev:     v0.0
I (555) efuse_init: Max chip rev:     v3.99
I (559) efuse_init: Chip rev:         v1.0
I (565) heap_init: Initializing. RAM available for dynamic allocation:
I (572) heap_init: At 3FFAFF10 len 000000F0 (0 KiB): DRAM
I (578) heap_init: At 3FFB6388 len 00001C78 (7 KiB): DRAM
I (584) heap_init: At 3FFB9A20 len 00004108 (16 KiB): DRAM
I (590) heap_init: At 3FFC9F38 len 000160C8 (88 KiB): DRAM
I (596) heap_init: At 3FFE0440 len 00003AE0 (14 KiB): D/IRAM
I (602) heap_init: At 3FFE4350 len 0001BCB0 (111 KiB): D/IRAM
I (609) heap_init: At 4009BFC0 len 00004040 (16 KiB): IRAM
I (617) spi_flash: detected chip: generic
I (620) spi_flash: flash io: dio
W (623) spi_flash: Detected size(4096k) larger than the size in the binary image header(2048k). Using the size in the binary image header.
I (638) coexist: coex firmware version: 4482466
I (643) main_task: Started on CPU0
I (653) main_task: Calling app_main()
I (683) wifi:wifi driver task: 3ffcdd9c, prio:23, stack:6656, core=0
I (683) wifi:wifi firmware version: ccaebfa
I (683) wifi:wifi certification version: v7.0
I (683) wifi:config NVS flash: enabled
I (683) wifi:config nano formating: disabled
I (693) wifi:Init data frame dynamic rx buffer num: 32
I (693) wifi:Init static rx mgmt buffer num: 5
I (703) wifi:Init management short buffer num: 32
I (703) wifi:Init dynamic tx buffer num: 32
I (703) wifi:Init static rx buffer size: 1600
I (713) wifi:Init static rx buffer num: 10
I (713) wifi:Init dynamic rx buffer num: 32
I (723) wifi_init: rx ba win: 6
I (723) wifi_init: accept mbox: 6
I (723) wifi_init: tcpip mbox: 32
I (733) wifi_init: udp mbox: 6
I (733) wifi_init: tcp mbox: 6
I (733) wifi_init: tcp tx win: 5760
I (743) wifi_init: tcp rx win: 5760
I (743) wifi_init: tcp mss: 1440
I (753) wifi_init: WiFi IRAM OP enabled
I (753) wifi_init: WiFi RX IRAM OP enabled
I (763) wifi_prov_scheme_ble: BT memory released
I (763) app: Starting provisioning
I (773) app: Development mode: using hard coded salt
I (773) app: Development mode: using hard coded verifier
I (783) phy_init: phy_version 4830,54550f7,Jun 20 2024,14:22:08
I (863) wifi:mode : sta (10:52:1c:75:f8:30)
I (863) wifi:enable tsf
I (863) BTDM_INIT: BT controller compile version [b022216]
I (873) BTDM_INIT: Bluetooth MAC: 10:52:1c:75:f8:32
I (1113) protocomm_nimble: BLE Host Task Started
I (1123) wifi_prov_mgr: Provisioning started with service name : PROV_75F830 
I (1123) app: Provisioning started
I (1133) app: Scan this QR code from the provisioning application for Provisioning.
I (1133) QRCODE: Encoding below text with ECC LVL 0 & QR Code Version 10
I (1143) QRCODE: {"ver":"v1","name":"PROV_75F830","username":"wifiprov","pop":"abcd1234","transport":"ble"}
I (1163) NimBLE: GAP procedure initiated: advertise;
I (1163) NimBLE: disc_mode=2
I (1163) NimBLE:  adv_channel_map=0 own_addr_type=0 adv_filter_policy=0 adv_itvl_min=256 adv_itvl_max=256
I (1173) NimBLE:


  █▀▀▀▀▀█ ▄ █ ▀▀▄▄▀▄▄▀ ▀▀▀▄▀▄▄  █▀▀▀▀▀█
  █ ███ █ ▄▄▄ █▄▄▄ ▄▄▀▄▀▄ ▀▄ ▄  █ ███ █   
  █ ▀▀▀ █ ▄█ ▄▄ ▄▄▀  ▀▄ ▄▀ ▄ ▄  █ ▀▀▀ █
  ▀▀▀▀▀▀▀ ▀▄█▄▀ █ ▀ █ ▀▄█ █ ▀▄▀ ▀▀▀▀▀▀▀   
  █▀▀██▄▀▀██▄▀▄▀ ▀ ▀█▄▀▄██▀▀█▀▀█ ▀ █ ▀
     ▄▀▄▀█▀▀  ▄▀ ▀ ▀█ ▄▄▀▄▀ █▀▀   ▀█▀ ▀   
  ▀  ▀█▀▀▀ ▀▄ ▀██ ▀██▄▄▄ ▄▀▀█▀▀ ▀ ▀▄█▄▀
  ▄▀▀█ █▀█▄███▀ █▀  ▄▄▀▄  ▄▀▄█  ▀█ █▀██   
  ▄  ▄ ▀▀ ▀▄▀▀▄▄ ▀ ▀█▄▄  █▀▀▀ ▀██▄▀█▀▀▀   
   █▀ ▀ ▀██▄▄ ▄█▀█▄▀█▄ █▀▄  █▀▄ ██▄▀▀▀▀
   ▄█ ▄▄▀ █▀█ ▀ ▀▀█▀ ▄▄▄ ▄ ▀██▄██▄▀ ▀█▀   
  ▄█ ▀▄█▀█▄▄██▀ ▄▀  ▄ ▀▄ ▄█▀ ██ ▀▀ █▀▀▀
  ▄█ ▄ ▀▀▄▄▀▄▀▄▄▄▀█▀ ▄▄▄█▄██▀▀▀▀█▄▀▄▀ ▀
  █  ▀██▀▄█▀▀ ▄█▀▀█▀█▄ █ ▄█▀▀▀██ ▄█▄ ▄▀
  ▄█ ▀▄█▀█▄▄██▀ ▄▀  ▄ ▀▄ ▄█▀ ██ ▀▀ █▀▀▀
  ▄█ ▄ ▀▀▄▄▀▄▀▄▄▄▀█▀ ▄▄▄█▄██▀▀▀▀█▄▀▄▀ ▀
  █  ▀██▀▄█▀▀ ▄█▀▀█▀█▄ █ ▄█▀▀▀██ ▄█▄ ▄▀
  ▄█ ▀▄█▀█▄▄██▀ ▄▀  ▄ ▀▄ ▄█▀ ██ ▀▀ █▀▀▀
  ▄█ ▄ ▀▀▄▄▀▄▀▄▄▄▀█▀ ▄▄▄█▄██▀▀▀▀█▄▀▄▀ ▀
  ▄█ ▀▄█▀█▄▄██▀ ▄▀  ▄ ▀▄ ▄█▀ ██ ▀▀ █▀▀▀
  ▄█ ▄ ▀▀▄▄▀▄▀▄▄▄▀█▀ ▄▄▄█▄██▀▀▀▀█▄▀▄▀ ▀
  █  ▀██▀▄█▀▀ ▄█▀▀█▀█▄ █ ▄█▀▀▀██ ▄█▄ ▄▀
  ▄█ ▄ ▀▀▄▄▀▄▀▄▄▄▀█▀ ▄▄▄█▄██▀▀▀▀█▄▀▄▀ ▀
  █  ▀██▀▄█▀▀ ▄█▀▀█▀█▄ █ ▄█▀▀▀██ ▄█▄ ▄▀
  █  ▀██▀▄█▀▀ ▄█▀▀█▀█▄ █ ▄█▀▀▀██ ▄█▄ ▄▀
  ▀ ▀▀▀ ▀▀▄▄█ ▀ ▀ ▄▀▄▄  ▀█▄▀▀▀█▀▀▀██▀▄
  ▀ ▀▀▀ ▀▀▄▄█ ▀ ▀ ▄▀▄▄  ▀█▄▀▀▀█▀▀▀██▀▄
  █▀▀▀▀▀█ ▀▀██▀ ▄█  ▀▄ ▄█▄█ ▄▄█ ▀ ██▀▀▀
  █ ███ █ ███▀▄▄▄▀██▄█▀▄█▄██▀▀███▀█▀█▄▄
  █ ▀▀▀ █ █ ▀ ▄█▀▀▀▀▄▄ █    █ ▀██▀▄█ ▀█
  ▀▀▀▀▀▀▀ ▀ ▀ ▀ ▀▀▀▀      ▀▀▀      ▀▀▀▀


I (1443) app: If QR code is not visible, copy paste the below URL in a browser.
https://espressif.github.io/esp-jumpstart/qrcode.html?data={"ver":"v1","name":"PROV_75F830","username":"wifiprov","pop":"abcd1234","transport":"ble"}
I (13583) app: BLE transport: Connected!
I (13783) protocomm_nimble: mtu update event; conn_handle=0 cid=4 mtu=256
I (15433) security2: Using salt and verifier to generate public key...
I (16243) app: Secured session established!
W (33793) wifi:Password length matches WPA2 standards, authmode threshold changes from OPEN to WPA2
I (33823) app: Received Wi-Fi credentials
        SSID     : AIS 4G Hi-Speed Home WiFi_76947550769475
        Password : 50769475
I (39923) wifi:new:<11,0>, old:<1,0>, ap:<255,255>, sta:<11,0>, prof:1, snd_ch_cfg:0x0
I (39933) wifi:state: init -> auth (0xb0)
I (39933) wifi:state: auth -> assoc (0x0)
I (39953) wifi:state: assoc -> run (0x10)
I (39963) wifi:connected with AIS 4G Hi-Speed Home WiFi_769475, aid = 23, channel 11, BW20, bssid = 30:0a:c5:9e:94:9f
I (39963) wifi:security: WPA2-PSK, phy: bgn, rssi: -59
I (39993) wifi:pm start, type: 1

I (39993) wifi:dp: 1, bi: 102400, li: 3, scale listen interval from 307200 us to 307200 us
I (40053) wifi:AP's beacon interval = 102400 us, DTIM period = 1
I (40883) wifi:<ba-add>idx:0 (ifx:0, 30:0a:c5:9e:94:9f), tid:0, ssn:2, winSize:64
I (47493) app: Connected with IP Address:192.168.1.174
I (47493) esp_netif_handlers: sta ip: 192.168.1.174, mask: 255.255.255.0, gw: 192.168.1.1
I (47493) wifi_prov_mgr: STA Got IP
I (47493) app: Provisioning successful
I (47503) app: Hello World!
I (48503) app: Hello World!
I (49503) app: Hello World!
I (50503) app: Hello World!
I (50543) NimBLE: GAP procedure initiated: stop advertising.

I (50543) NimBLE: GAP procedure initiated: stop advertising.

I (50553) NimBLE: GAP procedure initiated: terminate connection; conn_handle=0 hci_reason=19

E (50623) protocomm_nimble: Error setting advertisement data; rc = 30
I (50623) wifi_prov_mgr: Provisioning stopped
I (50623) app: BLE transport: Disconnected!
I (50623) wifi_prov_scheme_ble: BTDM memory released
I (51503) app: Hello World!
I (52503) app: Hello World!
I (53503) app: Hello World!
I (54503) app: Hello World!
I (55503) app: Hello World!
I (56503) app: Hello World!
I (57503) app: Hello World!
I (58503) app: Hello World!
I (59503) app: Hello World!
I (60503) app: Hello World!
I (61503) app: Hello World!
I (62503) app: Hello World!
I (63503) app: Hello World!
I (64503) app: Hello World!
I (65503) app: Hello World!
I (66503) app: Hello World!
I (67503) app: Hello World!
I (68503) app: Hello World!
I (69503) app: Hello World!
I (70503) app: Hello World!
I (71503) app: Hello World!
I (72503) app: Hello World!
I (73503) app: Hello World!
I (74503) app: Hello World!
I (75503) app: Hello World!
I (76503) app: Hello World!
I (77503) app: Hello World!
I (78503) app: Hello World!
I (79503) app: Hello World!
I (80503) app: Hello World!
I (81503) app: Hello World!
I (82503) app: Hello World!
I (83503) app: Hello World!
I (84503) app: Hello World!
I (85503) app: Hello World!
I (86503) app: Hello World!