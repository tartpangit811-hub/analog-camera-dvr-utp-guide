# analog-camera-dvr-utp-guide
Complete 8-Channel Analog CCTV Installation Guide using UTP CAT6 + Video Balun. For Technicians. No Coax Needed.
# 8-Channel Analog CCTV over UTP Cable - Complete Guide
*Install, Wire, and Troubleshoot Analog Cameras using CAT6 + Video Baluns*

This guide is for technicians and beginners who want to install 8-Channel Analog CCTV systems using UTP CAT6 cable instead of traditional Coaxial cable.

## 📑 Table of Contents
1. [System Overview](#system-overview)
2. [Parts & Materials List](#parts--materials-list)
3. [Tools Needed](#tools-needed)
4. [System Diagram](#system-diagram)
5. [Wiring Guide: Balun to Camera](#wiring-guide-balun-to-camera)
6. [Power Distribution](#power-distribution)
7. [DVR Configuration](#dvr-configuration)
8. [Troubleshooting](#troubleshooting)
9. [FAQ](#faq)
10. [License](#license)

---

## 1. System Overview
This setup uses 8 Analog Cameras connected via CAT6 UTP cable and Video Baluns. 
Advantage vs Coax: Cheaper, longer distance up to 300m, and Video + Power in 1 cable.

**Supported:** HIKVISION, DAHUA, TVI, AHD, CVI Analog Cameras

## 2. Parts & Materials List
- **8 pcs** Analog Camera - 4 Dome + 4 Bullet
- **16 pcs** Video Balun - Passive, 1 Channel
- **300m** CAT6 UTP Cable - Outdoor rated
- **1 pc** 8-CH HIKVISION DVR
- **1 pc** 12V 20A Centralized Power Supply
- **8 pcs** DC Connector - Male
- **1 pc** Monitor with HDMI
- **RJ45 Connectors** and **BNC Connectors**

## 3. Tools Needed
Crimping Tool, LAN Tester, Drill, Screwdriver, Ladder, Multimeter

## 4. System Diagram
*Upload mo dito yung diagram natin later*
`![System Diagram](images/8channel-analog-utp-final.png)`

## 5. Wiring Guide: Balun to Camera
1. Camera BNC → Balun BNC
2. Balun RJ45 → CAT6 Cable
3. CAT6 → Balun RJ45 sa DVR side
4. Balun BNC → DVR Channel Input
5. DC Power → Inject via CAT6 to camera

## 6. Power Distribution
Use 12V 20A PSU. 8 Cameras x 1A each = 8A total. 
Run 2 wires of CAT6 for +12V and 2 wires for GND.

## 7. DVR Configuration
1. Connect DVR to Monitor via HDMI
2. Right Click > Menu > Login
3. Camera > Image Settings > Adjust Brightness/Contrast
4. Storage > Format HDD

## 8. Troubleshooting
| Problem | Solution |
| --- | --- |
| No Video | Check Balun, Check Power, Test CAT6 with LAN Tester |
| Rolling Lines | Ground loop. Use same PSU ground |
| Short Distance | Use Active Balun for >300m |

## 9. FAQ
**Q: Pwede ba i-sabay ang Video at Data sa 1 CAT6?** 
A: Hindi. 1 CAT6 = 1 Camera lang for Analog.

**Q: Gaano kalayo kaya?** 
A: Up to 300m using Passive Balun.
## 6. Troubleshooting Guide

**Q: Walang lumalabas sa Monitor**
- **A:** Check kung naka-set yung DVR sa tamang output `HDMI/VGA`. Check power ng DVR 12V 5A.

**Q: May 1-2 camera na "No Signal"**
- **A:** 1. Check kung mahigpit yung balun sa camera side at DVR side
         2. Swap mo yung port sa DVR. Pag gumana, DVR port sira. Pag hindi, cable/balun sira.

**Q: Madilim/Nag-no-noise yung gabi**
- **A:** Kulang sa power. Dapat 12V 10A power supply gamit mo sa 8 cameras. Wag magtipid.

**Q: May guhit-guhit yung video**
- **A:** May power interference. Ihiwalay mo yung CAT6 sa mga 220V na wire.
## 10. License
MIT License - Free to use and modify.

---
Made with ❤️ for Filipino Technicians

## 5. Materials & Estimated Cost PH
| Item | Qty | Est. Price |
| --- | --- | --- |
| 8CH DVR | 1 | ₱3,500 |
| Analog Camera 1080p | 8 | ₱6,400 |
| CAT6 Cable Box | 1 | ₱2,800 |
| UTP Balun Passive | 16 | ₱800 |
| 12V 10A Power Supply | 1 | ₱650 |
| **Total Est.** |  | **₱14,150** |

