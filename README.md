# Acer Aspire 5749 OpenCore Hackintosh

[![EFIAcer OSX](https://img.shields.io/badge/EFIAcerHackintosh-available_here-violet.svg)](https://github.com/sebasrock156/Acer-E5-572-TMP246-OpenCore)
[![AMD OSX](https://img.shields.io/badge/AMDOSX-alpha_available-violet.svg)](https://github.com/sebasrock156/Asus-X555QA-Hackintosh)
[![Huawei OSX](https://img.shields.io/badge/HuaweiHackintosh-available-violet.svg)](https://github.com/sebasrock156/Huawei-Matebook-D14-21-OpenCore)

This is a "big" project to bring MacOS OSes for these laptops with OpenCore Bootloader, for more information, click on "More info of **MacOS Version** below:

**More info of MacOS Monterey:**

[![MacOS Monterey](https://i.imgur.com/G3qQ9T2.png)](https://github.com/sebasrock156/Acer-Aspire-5749-Hackintosh/tree/Monterey)

**Status:** 👨🏾‍🏭 In development (test with [Release EFI](https://github.com/sebasrock156/Acer-Aspire-5749-Hackintosh/releases) )💻

**To do:** Fix iGPU detection by OCLP, fix OC Menu controller.

---

**More info of MacOS Ventura:**

[![MacOS Ventura](https://i.imgur.com/G3qQ9T2.png)](https://github.com/sebasrock156/Acer-Aspire-5749-Hackintosh/tree/Ventura)

**Status:** 👨🏾‍🏭 In development (test with [Alpha Release EFI](https://github.com/sebasrock156/Acer-Aspire-5749-Hackintosh/releases) )💻

**To do:** Fix OpenCore iGPU patch for correct detection by OCLP, OC Menu it's even broke.

---

Hardware | Model
--- |:--:
![motherboard](https://i.imgur.com/kjUKjB2.png) | Acer HM65A (Sandy Bridge)
![bios](https://i.imgur.com/98P6ntE.png) | InsydeH20 v 1.06/1.08 (by Acer)
![processor](https://i.imgur.com/wpQP7WW.png) | Intel Core i3 (2nd Gen) 2330M 2 Cores/4 Threads@2,2Ghz
![igpu](https://i.imgur.com/pk2H9Aw.png) | Intel Graphics 3000 512MB VRAM @500Mhz (Supported until MacOS High Sierra)
![audio](https://i.imgur.com/A7RRuUn.png) | ALC269 (in-build)
![wlan](https://i.imgur.com/9eDLwo9.png) | Intel Centrino N-100
Ethernet | Qualcomm/Atheros AR8251 (Not supported nativelly)
![ddr3](https://i.imgur.com/5MAnSyf.png) | Elpida 4GB(2x2) DDR3L@1600Mhz
![ssd](https://i.imgur.com/pozDx4X.png) | Kingston A400 SSD 240GB (TLC PS11 Controller)
---

### Installation
---

<details>


⚠️ **SOME WARNINGS BEFORE ⚠️:**

*1. During all the process, try have another laptop/PC with Hackintosh posibilities (as last resource for fix any Boot problems)*

*2. Use a SATA3 SSD for install any MacOS version; HDDs are so slow for this; M.2 SSDs may be work, but, default BIOS doesn't support it*

</details>


### Works:
---
<details>

- Opencore 0.9.2 ✅ (Although OC Menu doesn't recognize periphericals)

- Installer Boot ✅ (Installation on SSD: ~30/35 minutes)

- System Boot ✅

- USB Ports ✅

- VoodooPS2Controller/Keyboard+Touchpad ✅

- Camera ✅ (works perfectly)

- Battery charging and stats ✅

- Screen ✅ (1336x768)

- Audio Card ✅ (Could be sounds cutted)

- Wi-Fi ✅ (It's fully working)

 
</details>


### Not works:
---

<details>

- HDMI ❌ (Enable it with OCLP, but not for now)
- VGA/Displayport ❌ (System try put in 90Hz and the built-in screen crash)
