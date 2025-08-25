<p align="center">
	<img width="256" src="https://avatars.githubusercontent.com/u/173426529"/>
</p>

# LibWrt build for JDC AX1800 Pro
[![](https://github.com/miyukowo/openwrt-ci/actions/workflows/JDC-AX1800-PRO.yml/badge.svg)](https://github.com/miyukowo/openwrt-ci/releases)

## Disclaimer [![](https://img.shields.io/badge/-Personal_Disclaimer-FFFFFF.svg)](#disclaimer-)

- **I am not responsible for any theoretical or actual losses caused by using this firmware.**
- **This firmware is strictly prohibited for commercial use. Please comply with all relevant national internet regulations.**

---

## Project Info [![](https://img.shields.io/badge/-Project_Overview-FFFFFF.svg)](#project-info-)

- Default management address: `192.168.1.1`  
  Default user: `root`  
  Default password: `password`  
- Source code: [LiBwrt](https://github.com/LiBwrt/openwrt-6.x)  
- Cloud build repo: [haiibo/OpenWrt](https://github.com/haiibo/OpenWrt)

---

## Firmware Download [![](https://img.shields.io/badge/-Build_Status_&_Download-FFFFFF.svg)](#firmware-download-)

Click the [![](https://img.shields.io/badge/Download-Link-blueviolet.svg?style=flat&logo=hack-the-box)](https://github.com/miyukowo/openwrt-ci/releases) badge in the table below to download firmware for your device.

| Platform + Device | Build Status | Config File | Download |
| :---------------: | :----------: | :---------: | :------: |
| [![](https://img.shields.io/badge/JDCloud_AX1800_PRO-ALL-32C955.svg?logo=openwrt)](https://github.com/miyukowo/openwrt-ci/blob/main/.github/workflows/JDC-AX1800-PRO.yml) | [![](https://github.com/miyukowo/openwrt-ci/actions/workflows/JDC-AX1800-PRO.yml/badge.svg)](https://github.com/miyukowo/openwrt-ci/actions/workflows/JDC-AX1800-PRO.yml) | [![](https://img.shields.io/badge/Config-orange.svg?logo=apache-spark)](https://github.com/miyukowo/openwrt-ci/blob/main/configs/jdc-ax1800-pro.config) | [![](https://img.shields.io/badge/Download-Link-blueviolet.svg?logo=hack-the-box)](https://github.com/miyukowo/openwrt-ci/releases/) |
| [![](https://img.shields.io/badge/JDCloud_AX1800_PRO-ALL-32C955.svg?logo=openwrt)](https://github.com/miyukowo/openwrt-ci/blob/main/.github/workflows/KOK-JDC-AX1800-PRO.yml) | [![](https://github.com/miyukowo/openwrt-ci/actions/workflows/KoK-JDC-AX1800-PRO.yml/badge.svg)](https://github.com/miyukowo/openwrt-ci/actions/workflows/KoK-JDC-AX1800-PRO.yml) | [![](https://img.shields.io/badge/Config-orange.svg?logo=apache-spark)](https://github.com/miyukowo/openwrt-ci/blob/main/configs/jdc-ax1800-pro.config) | [![](https://img.shields.io/badge/Download-Link-blueviolet.svg?logo=hack-the-box)](https://github.com/miyukowo/openwrt-ci/releases/) | 

---

## Custom Build [![](https://img.shields.io/badge/-How_To_Compile-FFFFFF.svg)](#custom-build-)

1. Log in to GitHub and fork this project into your own repo.  
2. Edit the corresponding file under the `configs` directory to add/remove packages, or upload your own `.config` file.  
3. For plugin names & features, refer to this guide: [Applications Plugin Notes](https://www.right.com.cn/forum/thread-3682029-1-1.html).  
4. Modify `diy-script.sh` if you want to change the default IP, add/remove packages, or adjust other settings.  
5. Edit or add the `xx.yml` workflow file, then trigger the desired `Actions` workflow to start building.  
6. Build time is ~1–3 hours. After completion, firmware will be available in [Releases](https://github.com/miyukowo/openwrt-ci/releases) under the corresponding Tag.  

If editing config files feels complicated, you can try extracting configs locally:  
👉 https://github.com/LiBwrt/openwrt-6.x  

**Video tutorial (YouTube): [OpenWrt Build Interface Setup](https://www.youtube.com/watch?v=jEE_J6-4E3Y&list=WL&index=7)**

### Best of luck to you!

---

<a href="#readme">
<img src="https://img.shields.io/badge/-Back_to_Top-FFFFFF.svg" title="Back to Top" align="right"/>
</a>
