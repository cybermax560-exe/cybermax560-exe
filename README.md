<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,100:00ff9c&height=180&section=header&text=CybermaX560&fontColor=ffffff&fontSize=52&animation=twinkling&desc=Break%20Hardware%20%C2%B7%20Understand%20Firmware%20%C2%B7%20Secure%20the%20Future&descAlignY=72&descSize=16" alt="CybermaX560" />

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&pause=1000&color=00FF9C&center=true&vCenter=true&width=650&lines=%3E+Hardware+Security+Researcher;%3E+IoT+%26+Embedded+Systems+Security;%3E+Firmware+Extraction+%26+Reverse+Engineering;%3E+UART+%7C+SPI+%7C+I2C+%7C+JTAG+%7C+SWD;%3E+RF+%7C+BLE+%7C+Wi-Fi+%7C+SDR;%3E+Building+open-source+hardware+hacking+tools" alt="Hardware Security Researcher · IoT & Embedded Systems · Red Team" />

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/debanjansaha360)
[![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com/@MaxTechnical360)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/cybermax560)

<img src="https://komarev.com/ghpvc/?username=cybermax560-exe&color=00ff9c&style=flat-square&label=PROFILE+VIEWS" alt="Profile views" />

</div>

---

## `$ whoami`

```yaml
handle:     CybermaX560
location:   India
role:       Hardware Security Researcher
focus:      [IoT Security, Firmware Analysis, Hardware Reverse Engineering]
interfaces: [UART, SPI, I2C, JTAG, SWD]
wireless:   [RF, Bluetooth LE, Wi-Fi, SDR]
building:   [PROBINIX, BaudHunter, Hardware-PT Toolkit]
mission: >
  Exploring the security of connected devices, embedded systems,
  and hardware through practical research and ethical security testing.
channel:    youtube.com/@MaxTechnical360
```

---

## 🚀 Featured Projects

<div align="center">

<a href="https://github.com/cybermax560-exe/PROBINIX"><img height="130" src="https://github-readme-stats.vercel.app/api/pin/?username=cybermax560-exe&repo=PROBINIX&hide_border=true&bg_color=0d1117&title_color=00ff9c&icon_color=00ff9c&text_color=c9d1d9" alt="PROBINIX" /></a>
<a href="https://github.com/cybermax560-exe/BaudHunter"><img height="130" src="https://github-readme-stats.vercel.app/api/pin/?username=cybermax560-exe&repo=BaudHunter&hide_border=true&bg_color=0d1117&title_color=00ff9c&icon_color=00ff9c&text_color=c9d1d9" alt="BaudHunter" /></a>
<a href="https://github.com/cybermax560-exe/Hardware-PT-ToolKIT"><img height="130" src="https://github-readme-stats.vercel.app/api/pin/?username=cybermax560-exe&repo=Hardware-PT-ToolKIT&hide_border=true&bg_color=0d1117&title_color=00ff9c&icon_color=00ff9c&text_color=c9d1d9" alt="Hardware-PT Toolkit" /></a>

</div>

### 🔌 [PROBINIX](https://github.com/cybermax560-exe/PROBINIX) — hardware hacking multi-tool for RP2040
![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![RP2040](https://img.shields.io/badge/RP2040-C51A4A?style=flat-square&logo=raspberrypi&logoColor=white)
![License](https://img.shields.io/badge/license-MIT-00ff9c?style=flat-square)

A JTAGulator-inspired tool that turns an inexpensive Raspberry Pi Pico into a debug-port finder and programmer, driven from a serial terminal menu.

- **Debug port discovery** — JTAG pinout scan (TDI/TDO/TCK/TMS/TRST across 16 channels, with device ID lookup) and SWD pinout scan
- **Target reconnaissance** — pin monitor with frequency and duty cycle, passive UART finder (1200–460800 baud), I²C scanner, SPI flash JEDEC ID
- **Hardware modes** — USB-to-serial bridge, Flashrom serprog programmer, OpenOCD adapter, CMSIS-DAP debugger

### 📟 [BaudHunter](https://github.com/cybermax560-exe/BaudHunter) — the serial port detective
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![License](https://img.shields.io/badge/license-MIT-00ff9c?style=flat-square)

Automatic baud-rate detection plus a full UART hardware-security toolkit in one binary.

- **Detection** — confidence-scored baud detection up to 4 Mbaud, framing autodetect, Modbus RTU / NMEA / MAVLink fingerprinting, sigrok-assisted auto-baud
- **Access & extraction** — U-Boot autoroot, firmware extraction over UART, XMODEM/YMODEM uploads into RAM
- **Analysis & attack** — timing side-channel assessment, protocol-aware serial fuzzer, glitch-trigger coordination
- **Interception** — passive sniffing, replay, and a MITM bridge with in-transit byte rewriting

### 🧰 [Hardware-PT Toolkit](https://github.com/cybermax560-exe/Hardware-PT-ToolKIT) — one-command hardware pentest setup
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![Kali](https://img.shields.io/badge/Kali_Linux-557C94?style=flat-square&logo=kalilinux&logoColor=white)

A Bash installer that turns a fresh Kali Linux system into a hardware security workstation.

- Installs **100+ packages** for firmware analysis, reverse engineering, and UART/JTAG/SWD/SPI/I²C work
- Builds firmware analysis tools from source (moria and mithril)
- Safe to re-run, unattended, and finishes with a clear installed / skipped / failed report

---

## 🔍 How I Assess a Device

```mermaid
flowchart LR
    A["🔎 Recon<br/>PCB teardown<br/>chip identification"] --> B["🔌 Interface Discovery<br/>UART · JTAG · SWD<br/>SPI · I²C"]
    B --> C["🖥️ Access<br/>serial console<br/>bootloader · debug port"]
    C --> D["💾 Firmware Extraction<br/>SPI flash dump<br/>UART / JTAG readout"]
    D --> E["🧬 Analysis<br/>Ghidra · emulation<br/>secrets · secure boot"]
    E --> F["📝 Report<br/>findings<br/>remediation"]

    classDef step fill:#0d1117,stroke:#00ff9c,stroke-width:2px,color:#c9d1d9;
    class A,B,C,D,E,F step;
```

| Phase | What happens | Tools I use |
|---|---|---|
| **Recon** | Board teardown, component and test-point identification | Multimeter, oscilloscope, hot-air station |
| **Interface discovery** | Locate and map debug and bus interfaces | PROBINIX, logic analyzer |
| **Access** | Reach a serial console, interrupt the bootloader, attach a debugger | BaudHunter, USB-to-TTL, ST-Link V2 |
| **Firmware extraction** | Dump flash chips or read memory through debug interfaces | XGecu T48, PROBINIX (Flashrom), BaudHunter |
| **Analysis** | Reverse engineer firmware, review boot chain and stored secrets | Ghidra, Hardware-PT Toolkit |
| **Wireless** | Inspect RF, BLE, and Wi-Fi communication | HackRF One, Wireshark |

---

## 🎯 Areas of Focus

| Domain | Topics |
|---|---|
| 🔧 **Hardware Reverse Engineering** | PCB analysis, component identification, debug interface discovery |
| 🔌 **Debug & Bus Interfaces** | UART, SPI, I²C, JTAG, SWD |
| 💾 **Firmware Security** | Firmware extraction, reverse engineering, secure boot and bootloader analysis |
| 📡 **Wireless & RF** | Bluetooth LE, Wi-Fi, SDR-based signal analysis |
| 🔍 **IoT Assessment** | End-to-end device security assessments and vulnerability research |
| ⚡ **Advanced Hardware Attacks** | Side-channel analysis, fault injection, cryptographic hardware and secure elements |
| 🛡️ **Embedded Platforms** | Embedded Linux and RTOS security |

---

## 🛠️ Tech Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=arduino,raspberrypi,linux,kali,wireshark,c,cpp,rust,py,bash,cmake,docker,git&theme=dark&perline=13" alt="Tech stack" />

<br><br>

![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=for-the-badge&logo=espressif&logoColor=white)
![STM32](https://img.shields.io/badge/STM32-03234B?style=for-the-badge&logo=stmicroelectronics&logoColor=white)
![RP2040](https://img.shields.io/badge/RP2040-C51A4A?style=for-the-badge&logo=raspberrypi&logoColor=white)
![Ghidra](https://img.shields.io/badge/Ghidra-DC143C?style=for-the-badge)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)

</div>

| Category | Skills |
|---|---|
| **Embedded languages** | C, C++, Rust, Python, Bash |
| **Platforms** | ESP32, STM32, RP2040, Arduino, Raspberry Pi, Embedded Linux |
| **Reverse engineering** | Ghidra, firmware unpacking and static analysis |
| **Network & protocol** | Wireshark, UART / SPI / I²C / JTAG / SWD protocol analysis |
| **Dev & tooling** | Git, Docker, CMake, Kali Linux |

---

## 🔬 Hardware Lab

<details>
<summary><b>🧰 Click to view lab equipment</b></summary>
<br>

| Category | Equipment | Purpose |
|---|---|---|
| RF / SDR | HackRF One | Radio-frequency and SDR research |
| Debugging | ST-Link V2 | STM32 debugging and programming |
| Debugging | PROBINIX (RP2040) | JTAG / SWD discovery, OpenOCD and CMSIS-DAP adapter |
| Targets | STM32 Blue Pill | Embedded security experiments |
| Flash programming | XGecu T48 | SPI flash reading and programming |
| Serial | USB-to-TTL adapter | UART console access |
| Measurement | Oscilloscope | Signal analysis |
| Measurement | Logic analyzer | Digital protocol analysis |
| Measurement | Multimeter | PCB and electrical analysis |
| Power | Bench power supply | Controlled power testing |
| Rework | Soldering & hot-air station | PCB rework and inspection |

</details>

---

## 📊 GitHub Activity

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=cybermax560-exe&show_icons=true&hide_border=true&bg_color=0d1117&title_color=00ff9c&icon_color=00ff9c&text_color=c9d1d9&rank_icon=github" alt="GitHub stats" />
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=cybermax560-exe&layout=compact&hide_border=true&bg_color=0d1117&title_color=00ff9c&text_color=c9d1d9" alt="Top languages" />

<img width="100%" src="https://streak-stats.demolab.com/?user=cybermax560-exe&hide_border=true&background=0d1117&ring=00ff9c&fire=00ff9c&currStreakLabel=00ff9c&sideLabels=c9d1d9&currStreakNum=ffffff&sideNums=ffffff&dates=8b949e&stroke=30363d" alt="GitHub streak" />

<img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=cybermax560-exe&bg_color=0d1117&color=c9d1d9&line=00ff9c&point=ffffff&area=true&area_color=00ff9c&hide_border=true" alt="Contribution graph" />

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/cybermax560-exe/cybermax560-exe/output/github-snake-dark.svg" />
  <img width="100%" src="https://raw.githubusercontent.com/cybermax560-exe/cybermax560-exe/output/github-snake.svg" alt="Contribution snake animation" />
</picture>

</div>

---

## 🎥 Learn With Me

I publish practical hardware security walkthroughs on YouTube — interface hunting, firmware extraction, and lab setups.

<div align="center">

[![Max Technical360](https://img.shields.io/badge/Subscribe-Max_Technical360-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com/@MaxTechnical360)

</div>

---

<div align="center">

<sub>⚠️ All research is conducted ethically on hardware I own or am authorized to test.</sub>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:00ff9c,100:0d1117&height=100&section=footer&animation=twinkling" alt="" />

</div>
