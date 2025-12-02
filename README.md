<div align="center">

# 🌐 OpenWrt Firmware

**Custom firmware for Amlogic, Rockchip & Allwinner devices**

[![Release](https://img.shields.io/github/v/release/lynxnexy/openwrt?style=for-the-badge&logo=github&logoColor=white&labelColor=1a1a2e&color=16a085)](https://github.com/lynxnexy/openwrt/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/lynxnexy/openwrt/total?style=for-the-badge&logo=download&logoColor=white&labelColor=1a1a2e&color=e74c3c)](https://github.com/lynxnexy/openwrt/releases)
[![License](https://img.shields.io/github/license/lynxnexy/openwrt?style=for-the-badge&logo=open-source-initiative&logoColor=white&labelColor=1a1a2e&color=9b59b6)](LICENSE)

[📥 Download](https://github.com/lynxnexy/openwrt/releases) • [📖 Wiki](https://openwrt.org/docs/start) • [🐛 Issues](https://github.com/lynxnexy/openwrt/issues)

</div>

---

## 📸 Screenshots

<details>
<summary><b>🖥️ Desktop View</b></summary>
<br>
<p align="center">
  <img src="assets/01.png" width="32%" alt="Desktop 1">
  <img src="assets/02.png" width="32%" alt="Desktop 2">
  <img src="assets/03.png" width="32%" alt="Desktop 3">
</p>
</details>

<details>
<summary><b>📱 Mobile View</b></summary>
<br>
<p align="center">
  <img src="assets/04.jpg" width="24%" alt="Mobile 1">
  <img src="assets/05.jpg" width="24%" alt="Mobile 2">
  <img src="assets/06.jpg" width="24%" alt="Mobile 3">
</p>
</details>

---

## 🔑 Quick Start

```
🌐 IP: 192.168.1.1  |  👤 User: root  |  🔒 Pass: passwd  |  📶 WiFi: LYNX (open)
```

---

## 📦 Supported Devices

| Device | Firmware Code |
|:-------|:--------------|
| **HG680P** | `s905x` |
| **B860H** | `s905x-b860h` |
| **HG680-FJ** | `s905x2-hg680fj` |
| **Nexbox A95X-A2** | `s912-nexbox-a2` |
| **NanoPi R5S** | `nanopi-r5s` |
| **NanoPi R5C** | `nanopi-r5c` |
| **Orange Pi 5 Plus** | `orangepi-5-plus` |

<details>
<summary><b>📋 All Supported Devices</b></summary>

### Amlogic SoC
| SoC | Devices |
|:----|:--------|
| **A311D** | `a311d` `a311d-oes` |
| **S922X** | `s922x` `s922x-ct2000` `s922x-gtking` `s922x-gtkingpro-h` `s922x-odroid-n2` `s922x-oes-plus` `s922x-reva` `s922x-ugoos-am6` |
| **S912** | `s912` `s912-h96pro-plus` `s912-m8s-pro` `s912-nexbox-a1` `s912-nexbox-a2` `s912-onecloudpro` `s912-phicomm-t1` `s912-t95z-plus` `s912-tx8-max` `s912-tx9-pro-2g` `s912-tx9-pro-3g` `s912-x92` `s912-zyxq-fake` |
| **S905X3** | `s905x3` `s905x3-2101` `s905x3-a100` `s905x3-a95xf3` `s905x3-a95xf3-gb` `s905x3-b` `s905x3-h96max` `s905x3-hk1` `s905x3-ip1001m` `s905x3-q1` `s905x3-q2` `s905x3-tx3` `s905x3-tx3-bz` `s905x3-ugoosx3` `s905x3-whale` `s905x3-x88-pro-x3` `s905x3-x96air` `s905x3-x96air-gb` `s905x3-x96max` |
| **S905X2** | `s905x2` `s905x2-km3` `s905x2-x96max-2g` `s905x2-hg680fj` |
| **S905X** | `s905x` `s905x-b860h` `s905x-nexbox-a95x` `s905x-t95` `s905x-tbee` `s905x-tx9` |
| **S905W** | `s905w` `s905w-w95` `s905w-x96-mini` `s905w-x96w` |
| **S905D** | `s905d` `s905d-ki-pro` `s905d-sml5442tw` |
| **S905L** | `s905l` `s905l-aurora-1s` `s905l-b860av21u` `s905l-mg101` `s905l2` `s905l2-e900v21e` `s905l2-wojia` `s905l3` `s905l3-cm211` `s905l3-unt400g1` `s905l3-unt402a` `s905l3a` `s905l3a-cm311` `s905l3a-m401a` `s905l3b` `s905l3b-e900v21d` `s905l3b-e900v22d` `s905l3b-e900v22e` `s905l3b-ip103h` `s905l3b-rg020et-ca` `s905l3b-unt403a` `s905lb-ipbs9505` `s905lb-q96-mini` `s905lb-r3300l` `s905mb` |
| **S905** | `s905` `s905-beelink-mini` `s905-mxqpro-plus` |

### Rockchip SoC
| SoC | Devices |
|:----|:--------|
| **RK3588** | `nanopc-t6` `orangepi-5-plus` `orangepi-5b` `rock5b` `rock5c` `h88k` `h88k-v3` |
| **RK3568** | `photonicat` `e25` `dg-tn3568` `lckfb-tspi` `h66k` `h68k` `h69k` |
| **RK3566** | `e20c` |
| **RK3528** | `h28k` `h96-max-m2` `zcube1-max` |
| **RK3399** | `aio-3399b` `dg3399` `eaidk-610` `fine3399` `firefly-rk3399` `king3399` `kylin3399` `leez` `panther-x2` `r66s` `r68s` `station-m2` `sw799` `tb-ls3399` `tn3399` |
| **RK3328** | `beikeyun` `chainedbox` `l1pro` `renegade-rk3328` `rk3318-box` `station-m1` |

### Allwinner SoC
| SoC | Devices |
|:----|:--------|
| **H6** | `tanix-tx6` `vplus` |

</details>

---

## 🚀 Installation

<table>
<tr>
<td width="50%">

### 💾 Install to eMMC
1. Flash firmware to USB/SD using [balenaEtcher](https://etcher.balena.io/)
2. Boot from USB/SD
3. Open `192.168.1.1` in browser
4. **System** → **Amlogic Service** → **Install**
5. Select device & install

</td>
<td width="50%">

### 🔄 Update Firmware
1. Download `*-update-*.img.gz`
2. Open `192.168.1.1` in browser
3. **System** → **Amlogic Service** → **Update**
4. Upload & follow instructions

</td>
</tr>
</table>

---

## ⚙️ Kernel & Packages

<table>
<tr>
<td>

| Kernel | Status |
|:-------|:-------|
| 6.12.y | 🟢 Latest |
| 6.6.y | 🔵 LTS |
| 6.1.y | 🔵 LTS |
| 5.15.y | 🔵 LTS |
| 5.10.y | 🟡 Legacy |
| 5.4.y | 🟡 Legacy |

</td>
<td>

**Included Packages:**
- 🌐 LuCI Web Interface
- 🔧 Amlogic Service
- 🐳 Docker (selected builds)
- 🔐 OpenVPN
- 📁 Samba4 File Sharing
- 💻 TTYD Web Terminal

</td>
</tr>
</table>

---

## ❓ FAQ

<details>
<summary><b>Which firmware should I download?</b></summary>

Match your device model with the firmware code. Check device label or search online for your TV Box model.
</details>

<details>
<summary><b>Device not booting?</b></summary>

Try: different USB port → better USB cable → different SD card → hold reset button while inserting USB
</details>

<details>
<summary><b>Reset to defaults?</b></summary>

```bash
firstboot && reboot
```
</details>

<details>
<summary><b>Restore Android?</b></summary>

Use Amlogic USB Burning Tool with original firmware.
</details>

---

## 🔗 Links

[![OpenWrt](https://img.shields.io/badge/OpenWrt-Official-00B5E2?style=flat-square&logo=openwrt&logoColor=white)](https://openwrt.org/)
[![Documentation](https://img.shields.io/badge/Docs-OpenWrt-00B5E2?style=flat-square&logo=readthedocs&logoColor=white)](https://openwrt.org/docs/start)
[![Amlogic Service](https://img.shields.io/badge/GitHub-ophub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/ophub/amlogic-s9xxx-openwrt)

---

<div align="center">

**⚠️ Disclaimer:** Provided "as is" without warranty. May void device warranty. Backup your data. Use at your own risk.

[![License](https://img.shields.io/badge/License-GPL--2.0-blue?style=flat-square)](LICENSE)

⭐ **Star this repo if you find it useful!** ⭐

</div>
