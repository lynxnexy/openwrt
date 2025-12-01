# OpenWrt Firmware for Amlogic, Rockchip & Allwinner Devices

[![Release](https://img.shields.io/github/v/release/lynxnexy/openwrt?style=flat-square&label=Release)](https://github.com/lynxnexy/openwrt/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/lynxnexy/openwrt/total?style=flat-square&label=Downloads)](https://github.com/lynxnexy/openwrt/releases)
[![License](https://img.shields.io/github/license/lynxnexy/openwrt?style=flat-square&label=License)](LICENSE)

Pre-built OpenWrt firmware images for TV Boxes, Single Board Computers (SBC), and other ARM devices.

## 📥 Download

Go to [**Releases**](https://github.com/lynxnexy/openwrt/releases) page to download the latest firmware for your device.

## 🔑 Default Credentials

| Setting | Value |
|---------|-------|
| IP Address | `192.168.1.1` |
| Username | `root` |
| Password | `passwd` |
| WiFi SSID | `LYNX` |
| WiFi Password | `none` |

## 📦 Supported Devices

### Amlogic SoC
<details>
<summary>Click to expand</summary>

| SoC | Devices |
|-----|---------|
| **A311D** | a311d, a311d-oes |
| **S922X** | s922x, s922x-ct2000, s922x-gtking, s922x-gtkingpro-h, s922x-odroid-n2, s922x-oes-plus, s922x-reva, s922x-ugoos-am6 |
| **S912** | s912, s912-h96pro-plus, s912-m8s-pro, s912-nexbox-a1, s912-nexbox-a2, s912-onecloudpro, s912-phicomm-t1, s912-t95z-plus, s912-tx8-max, s912-tx9-pro-2g, s912-tx9-pro-3g, s912-x92, s912-zyxq-fake |
| **S905X3** | s905x3, s905x3-2101, s905x3-a100, s905x3-a95xf3, s905x3-a95xf3-gb, s905x3-b, s905x3-h96max, s905x3-hk1, s905x3-ip1001m, s905x3-q1, s905x3-q2, s905x3-tx3, s905x3-tx3-bz, s905x3-ugoosx3, s905x3-whale, s905x3-x88-pro-x3, s905x3-x96air, s905x3-x96air-gb, s905x3-x96max |
| **S905X2** | s905x2, s905x2-km3, s905x2-x96max-2g, s905x2-hg680fj |
| **S905X** | s905x, s905x-b860h, s905x-nexbox-a95x, s905x-t95, s905x-tbee, s905x-tx9 |
| **S905W** | s905w, s905w-w95, s905w-x96-mini, s905w-x96w |
| **S905D** | s905d, s905d-ki-pro, s905d-sml5442tw |
| **S905L Series** | s905l, s905l-aurora-1s, s905l-b860av21u, s905l-mg101, s905l2, s905l2-e900v21e, s905l2-wojia, s905l3, s905l3-cm211, s905l3-unt400g1, s905l3-unt402a, s905l3a, s905l3a-cm311, s905l3a-m401a, s905l3b, s905l3b-e900v21d, s905l3b-e900v22d, s905l3b-e900v22e, s905l3b-ip103h, s905l3b-rg020et-ca, s905l3b-unt403a, s905lb-ipbs9505, s905lb-q96-mini, s905lb-r3300l, s905mb |
| **S905** | s905, s905-beelink-mini, s905-mxqpro-plus |

</details>

### Rockchip SoC
<details>
<summary>Click to expand</summary>

| SoC | Devices |
|-----|---------|
| **RK3588** | nanopc-t6, orangepi-5-plus, orangepi-5b, rock5b, rock5c, h88k, h88k-v3 |
| **RK3568** | photonicat, e25, dg-tn3568, lckfb-tspi, h66k, h68k, h69k |
| **RK3566** | e20c |
| **RK3528** | h28k, h96-max-m2, zcube1-max |
| **RK3399** | aio-3399b, dg3399, eaidk-610, fine3399, firefly-rk3399, king3399, kylin3399, leez, panther-x2, r66s, r68s, station-m2, sw799, tb-ls3399, tn3399 |
| **RK3328** | beikeyun, chainedbox, l1pro, renegade-rk3328, rk3318-box, station-m1 |

</details>

### Allwinner SoC
<details>
<summary>Click to expand</summary>

| SoC | Devices |
|-----|---------|
| **H6** | tanix-tx6, vplus |

</details>

## 🚀 Installation

### Method 1: Install to Internal Storage (eMMC)

1. Write the firmware image to a USB drive or SD card using [balenaEtcher](https://etcher.balena.io/) or [Rufus](https://rufus.ie/)
2. Boot from the USB/SD card
3. Login to OpenWrt via web browser (`192.168.1.1`)
4. Go to **System** → **Amlogic Service** → **Install OpenWrt**
5. Select your device model and click **Install**

### Method 2: Run from USB/SD Card

1. Write the firmware image to a USB drive or SD card
2. Insert into your device and boot
3. OpenWrt will run directly from the USB/SD card

## 🔄 Firmware Update

1. Download the latest firmware update file (`*-update-*.img.gz`)
2. Login to OpenWrt web interface
3. Go to **System** → **Amlogic Service** → **Update OpenWrt**
4. Upload the update file and follow the instructions

## ⚙️ Kernel Versions

Firmware is available with different kernel versions:

| Kernel | Status |
|--------|--------|
| 6.12.y | Latest |
| 6.6.y | LTS |
| 6.1.y | LTS |
| 5.15.y | LTS |
| 5.10.y | Legacy |
| 5.4.y | Legacy |

## 📋 Included Packages

- **LuCI** - Web interface
- **Amlogic Service** - Installation and management tools
- **Docker** - Container support (selected builds)
- **OpenVPN** - VPN support
- **Samba4** - File sharing
- **TTYD** - Web terminal
- **And more...**

## ❓ FAQ

<details>
<summary><b>Which firmware should I download?</b></summary>

Download the firmware that matches your device model. If unsure, check the device label or search for your TV Box model online.
</details>

<details>
<summary><b>My device is not booting</b></summary>

1. Try a different USB port
2. Use a shorter/better quality USB cable
3. Try a different SD card/USB drive
4. Some devices require pressing a reset button while inserting the USB
</details>

<details>
<summary><b>How do I reset to default settings?</b></summary>

Login via SSH and run:
```bash
firstboot && reboot
```
</details>

<details>
<summary><b>Can I go back to Android?</b></summary>

Yes, you can restore Android using Amlogic USB Burning Tool with your device's original firmware.
</details>

## 🔗 Resources

- [OpenWrt Official](https://openwrt.org/)
- [OpenWrt Documentation](https://openwrt.org/docs/start)
- [Amlogic Service](https://github.com/ophub/amlogic-s9xxx-openwrt)

## 📜 License

This project is licensed under the [GPL-2.0 License](LICENSE).

## ⚠️ Disclaimer

- These firmware images are provided "as is" without warranty of any kind
- Installing custom firmware may void your device warranty
- Always backup your data before installation
- Use at your own risk

---

<p align="center">
  <b>⭐ Star this repo if you find it useful!</b>
</p>
