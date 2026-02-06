# Taoyao Firmware

Firmware images for Xiaomi 12 Lite (taoyao), to include in custom ROM builds.

**Current version**: fw_taoyao_miui_TAOYAOGlobal_OS1.0.23.0.ULIMIXM_342f4c2bcd_14.0

### How to use?

1. Clone this repo to `vendor/xiaomi/xiaomi-taoyao`

2. Include it from `BoardConfig.mk` in device tree:

```
# Firmware
include vendor/xiaomi/taoyao-firmware/BoardConfigVendor.mk
```
