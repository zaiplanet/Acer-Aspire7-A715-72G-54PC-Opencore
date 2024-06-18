# Acer-Aspire7-A715-72G-54PC-Opencore
EFI, manual fix and link support run on Opencore ver.0.7.1


| Infor | Description |
| --- | --- |
| CPU | Intel Core i5-8300H 2.3Ghz (Turbo Boost to 4Ghz) / Intel® Core™ i7-8750H Processor (9M Cache, up to 4.10 GHz) |
| Graphics | Intel UHD Graphics 630 |
| External GPU | NVIDIA GeForce GTX 1050 |
| Audio | Realtek ALC 255 |
| Ethernet | Realtek RTL8168H/8111H PCI Express Gigabit Ethernet |
| Wlan | Broadcom QC61xxA |


Fully Working:

- Battery status
- Brightness w/brightness keys F3 - F4
- USB ports (1 USB3.0 and 2USB 2.0, internal Webcam, but SD Card not tested)
- Bluetooth (AirDrop tested, AirPlay and Handoff not tested)
- Wifi (replaced with 1 TP-Link WN725N usb wifi adaptor, QC61xxA is not supported)
- Audio (Internal Speakers work perfect with Boom 3D, Microphone tested, Headphones and HDMI not tested)
- Power Management (with AMD graphics disabled)
- Trackpad Gestures full
- Full CPU with Turbo Boost work perfect


Not Working:

- Fan Monitoring (added SMCProcessor, SMSSupperIO, temp monitor work but not fan monitor not show, fan work normaly )
- Sleep
- Hibernate

![image](https://user-images.githubusercontent.com/58675403/128866075-eb9d77f5-d43d-4e45-976a-b30b8befe16f.png)

