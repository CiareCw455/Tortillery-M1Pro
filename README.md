# Tortillery-M1Pro

**Custom firmware for the Artillery M1 Pro**  
**Stable Beta — Under Active Development**

![Status: Stable Beta](assets/badges/status-stable-beta.svg) ![Development: In Progress](assets/badges/development-in-progress.svg) ![OS: Debian 13](assets/badges/os-debian-13.svg) ![Klipper: v13](assets/badges/klipper-v13.svg)

> [!IMPORTANT]
> **Stable beta, still under development.** After several successful test prints, no issues have been observed so far. The firmware is working reliably in the tested setup, but further testing and improvements may continue. **This is not a final release.**

## Overview

**Tortillery-M1Pro** is an independent custom firmware project for the **Artillery M1 Pro** 3D printer, running **Debian GNU/Linux 13 (Trixie)** and **Klipper v13**.

The **CS1237 probe** and **cutter sensor** are working. Tools and scripts are available for flashing the **Host, Main, and THR MCUs**. The **AI camera remains disabled** for now.

## Latest Update

- ✅ **Stable beta in testing:** several prints completed successfully, with no issues observed so far.
- ✅ **Updated firmware image:** a new image is available in the Google Drive download folder.
- ✅ **Improved macros and configuration:** the updated image includes revised macros and tuning adjustments.
- ✅ **Complete flashing resources:** RKDevTool, scripts and files for the **THR, Main, and Host MCUs**, and **Windows 10 drivers** are included in the download folder.
- ⏸️ **AI camera:** remains disabled in this version.

## Current Feature Status

| Component | Status | Details |
| --- | --- | --- |
| Debian GNU/Linux 13 (Trixie) | ✅ Running | Firmware operating system |
| Klipper v13 | ✅ Running | Printer control software |
| CS1237 probe | ✅ Working | Probe functionality operational |
| Cutter sensor | ✅ Working | Sensor functionality operational |
| Updated macros and settings | ✅ Updated | Included in the latest firmware image |
| Print testing | ✅ Successful so far | Several prints completed without observed issues |
| Host / Main / THR MCU flashing | ✅ Included | Flashing scripts and files in the download folder |
| RKDevTool | ✅ Included | Available in the download folder |
| Windows 10 drivers | ✅ Included | Available in the download folder |
| AI camera | ⏸️ Disabled | Not enabled in the current beta |

## Download

### 📥 Updated Firmware Image and Flashing Tools

**[Download Tortillery-M1Pro from Google Drive](https://drive.google.com/drive/folders/1FenMh4RXV9PXNuyFfsBMxAcPvBawfPU2?usp=sharing)**

The Google Drive folder includes:

- **Updated Tortillery-M1Pro firmware image**, with revised macros and configuration settings.
- **RKDevTool** flashing utility.
- **MCU flashing scripts and required files** for **THR**, **Main**, and **Host**.
- **Windows 10 drivers**.

> [!WARNING]
> This is still **beta firmware**. Back up your existing firmware and printer configuration before flashing. Verify hardware compatibility and carefully follow the instructions provided with the flashing files. Flashing carries a risk of device malfunction or requiring recovery. Use at your own risk.

## Screenshots

Screenshots from the Tortillery-M1Pro environment, showing system information and the update manager.

### System Loads and Update Manager

System information showing the MCUs, Klipper, Debian GNU/Linux 13 (Trixie), and the update manager.

![Tortillery-M1Pro system loads and update manager](assets/screenshots/system-loads.png)

### Terminal System Information

Tortillery-M1Pro terminal banner, Linux kernel version, architecture, and Debian GNU/Linux 13 (Trixie).

![Tortillery-M1Pro terminal system information](assets/screenshots/terminal-system-info.jpg)

## Project Status

**Current status: Stable beta — successful print testing, with ongoing development.**

- [x] Debian GNU/Linux 13 (Trixie) running
- [x] Klipper v13 running
- [x] CS1237 probe and cutter sensor working
- [x] Updated macros and configuration included
- [x] Several test prints completed without observed issues
- [x] MCU flashing scripts and files available for Host, Main, and THR
- [x] RKDevTool and Windows 10 drivers available
- [ ] Enable and validate AI camera support
- [ ] Continue testing and refining the firmware

### Known Limitations

- **AI camera support is currently disabled.**
- The firmware remains in beta; successful tests do not guarantee compatibility with every configuration or printing scenario.

## Compatibility

This firmware is intended for the **Artillery M1 Pro**. Compatibility with other Artillery printer models has **not been established**.

## Support and Feedback

Questions, bug reports, testing feedback, and contributions are welcome.

💬 **[Contact the project on Telegram](https://t.me/+9mpIxyQTtlQ2NmQ8)**

You can also use the repository's GitHub Issues section to report bugs or suggest improvements.

## License and Credits

Tortillery is an independent community project for the Artillery M1 Pro.

This project is based on and includes modifications to:

- **Klipper** — [Klipper3d/klipper](https://github.com/Klipper3d/klipper) — GNU GPL v3.0
- **Katapult** — [Arksine/katapult](https://github.com/Arksine/katapult) — GNU GPL v3.0
- **Qidi Q2 Mainline Klipper**, developed by **Ahmed Sheikh (MisterSheikh)** — [MisterSheikh/Qidi_Q2_Mainline_Klipper](https://github.com/MisterSheikh/Qidi_Q2_Mainline_Klipper) — GNU GPL v3.0

The GD32F425 USB compatibility patches are based on work by Ahmed Sheikh. Tortillery includes additional Artillery M1 Pro configurations, build and flashing scripts, documentation, and CS1237 adjustments.

Original copyright notices and applicable open-source licenses are retained. The corresponding firmware source code and modifications are provided with the build kit linked in the [Download](#download) section.

See [LICENSE](LICENSE) for the GNU General Public License version 3.

Tortillery is not officially affiliated with or endorsed by Artillery, Klipper, Katapult, Makerbase/MKS, or MisterSheikh.

---

*Made for the Artillery M1 Pro community. Tortillery-M1Pro remains an independent community firmware project in beta development.*
