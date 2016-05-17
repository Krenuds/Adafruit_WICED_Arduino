# 0.5.5 (Work In Progress)

## Featherlib

- fix issue where 0xff is misinterpreted as EOF with USBSerial
- fix EXT GPIO interrupt conflict between Featherlib & Arduino
- fix #32 PWM only work after 3-5 minutes

# 0.5.1

- `Baltimore CyberTrust Root` replace `VeriSign Class 3 Public Primary Certification Authority - G5` in default root certificate list
- Fix #38 `Disconnect callback for MQTT and TCP don't imply that connected() method returns false` 
- Fix #36, #37 : Rework I2C with repeated START for MPL3115A2 sensor and alike.
- Use pre-compiled feather_dfu for Windows
- Fix Linux's rules for USB VID/PID
- Update signed driver for Windows

# Version 0.5.0

- First Release