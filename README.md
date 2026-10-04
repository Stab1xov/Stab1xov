<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=14,18,32&height=220&section=header&text=Stab1xov&fontSize=58&fontAlignY=36&desc=Kernel%20%7C%20Reverse%20Engineering%20%7C%20Game%20Internals%20%7C%20Systems&descAlignY=58&descAlign=50" width="100%"/>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&pause=1000&color=00F5FF&center=true&vCenter=true&width=620&lines=Founder+%40+222corp+%26+subsidiary+Nexa;Linux+Kernel+Modules+%26+PCIe+Driver+Engineering;Binary+Reverse+Engineering+(IDA+Pro+%7C+Recaf+%7C+Ghidra);Source+2+Internals+%26+Memory+Forensics;Game+Security%2C+Anti-Cheat+%26+Protection+Research" alt="Typing SVG" />
</a>

<br/>

[![GitHub followers](https://img.shields.io/github/followers/Stab1xov?label=Followers&style=for-the-badge&color=238636&logo=github)](https://github.com/Stab1xov)
[![Repositories](https://img.shields.io/badge/Ventures-222corp%20%26%20Nexa-7928CA?style=for-the-badge&logo=codeforces)](https://github.com/Stab1xov?tab=repositories)
[![Focus](https://img.shields.io/badge/Specialization-Low--Level%20%26%20Reversing-00599C?style=for-the-badge&logo=cplusplus)](https://github.com/Stab1xov)
[![IDA](https://img.shields.io/badge/Reverse_Engineering-IDA_Pro_9.x-red?style=for-the-badge&logo=target)](#)

</div>

---

## ⚡ Overview & Bio

Independent low-level systems engineer and security researcher. Founder of **222corp** (security research, anti-cheat, memory architecture) and subsidiary **Nexa** (driver engines, desktop systems, high-performance software).

- 🧠 **Kernel & Systems Engineering:** Writing Linux Kernel Modules (LKM, DKMS), manipulating PCIe configuration space (ASPM L1SS), bus arbitration, and low-level Windows Internals (memory scanning, RPM/WPM, VMT/MinHook).
- 🔬 **Reverse Engineering & Disassembly:**
  - **Native (x86/x64):** In-depth binary analysis via **IDA Pro 9.x**, Ghidra, and WinDbg. Schema dumping for Source 2 (`CS2DUMPER`), Unreal Engine 5 `.utoc`/`.ucas` Zen chunk parsing.
  - **JVM / Managed:** Bytecode reversing and deobfuscation with **Recaf**, **CFR**, and **Vineflower** (Minecraft Fabric internals, client modding).
- 🛡️ **Anti-Cheat & Protection:** Researching both offensive and defensive mechanics — anti-tamper loaders, kernel integrity verification, and bypass analysis.
- ⚡ **Computer Vision & AI:** Developing real-time vision pipelines (`FaceNeuro`) for input automation and visual analysis.

---

## 🛠 Tech Arsenal

<div align="center">

### Systems & Low-Level Architecture
![C](https://img.shields.io/badge/C99-00599C?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B20-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![x86-64 ASM](https://img.shields.io/badge/x86__64_Assembly-FF6600?style=for-the-badge&logo=assemblyscript&logoColor=white)
![Linux Kernel](https://img.shields.io/badge/Linux_Kernel_LKM-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Win32 / Internals](https://img.shields.io/badge/Windows_Internals-0078D7?style=for-the-badge&logo=windows&logoColor=white)
![PCIe ASPM](https://img.shields.io/badge/PCIe_ASPM_Subsystems-008080?style=for-the-badge)

### Reverse Engineering & Binary Forensics
![IDA Pro](https://img.shields.io/badge/IDA_Pro_9.x-003366?style=for-the-badge&logo=binary&logoColor=white)
![Ghidra](https://img.shields.io/badge/Ghidra-292929?style=for-the-badge&logo=nsa&logoColor=white)
![Recaf](https://img.shields.io/badge/Recaf_JVM_Bytecode-4A154B?style=for-the-badge)
![WinDbg](https://img.shields.io/badge/WinDbg-0078D7?style=for-the-badge&logo=windows&logoColor=white)
![Source 2 Dumper](https://img.shields.io/badge/Source_2_Schema_Dumper-E63946?style=for-the-badge)

### Graphics, Hooks & Game Internals
![DirectX 11](https://img.shields.io/badge/DirectX_11-0078D7?style=for-the-badge)
![ImGui](https://img.shields.io/badge/ImGui_Overlay-7B2CBF?style=for-the-badge)
![MinHook](https://img.shields.io/badge/MinHook_%2F_VMT-38B000?style=for-the-badge)
![Java Fabric](https://img.shields.io/badge/Java_Fabric_Modding-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)

### Tooling, Scripting & UI
![Python](https://img.shields.io/badge/Python_3-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Qt 6](https://img.shields.io/badge/Qt_6-41CD52?style=for-the-badge&logo=qt&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=for-the-badge&logo=powershell&logoColor=white)
![Kbuild / CMake](https://img.shields.io/badge/Kbuild_%2F_CMake-6A5ACD?style=for-the-badge)

</div>

---

## 🚀 Public Repositories & Deployments

| Repository | Domain | Tech Stack | Status |
|---|---|---|---|
| **[`nexa-ax203-driver`](https://github.com/Stab1xov/nexa-ax203-driver)** | Autonomous PCIe ASPM neutralizer & 2.4GHz RF coexistence engine for Intel Wi-Fi 6 AX203 on Linux | `C99`, `LKM`, `DKMS`, `Kbuild`, `CLI` | 🟢 Shipped & Maintained |
| **[`NexaInternalSRC-Cs2`](https://github.com/Stab1xov/NexaInternalSRC-Cs2)** | Source 2 engine internal SDK, memory manipulation, schema resolver & rendering hooks | `C++`, `DirectX 11`, `ImGui`, `VMT` | 🟢 Public Source |
| **[`SystemMonitor`](https://github.com/Stab1xov/SystemMonitor)** | Real-time Windows system monitoring dashboard (CPU, RAM, Disk, Network) | `C++20`, `Qt 6`, `Win32 API` | 🟢 Public Release |
| **[`TlSkins`](https://github.com/Stab1xov/TlSkins)** | Fabric client-side modification for dynamic skin loading and vanilla cape preservation | `Java`, `Fabric API`, `Bytecode` | 🟢 Active Mod |
| **[`nexa-macos27-desktop`](https://github.com/Stab1xov/nexa-macos27-desktop)** | Linux desktop environment customization and productivity engine | `Shell`, `Linux`, `Systemd` | 🟢 Active |

---

## 🔬 Active Research & Private Ecosystem

```text
222corp / Nexa Ecosystem
├── 222AC Engine          -> Kernel-level anti-cheat research, memory integrity guards & hook detection
├── NexaLoader            -> HWID-bound protected payload delivery & injection pipeline
├── 2protect              -> Binary anti-tamper, string encryption & packer research
├── FaceNeuro             -> Real-time neural vision & computer vision input automation
├── CS2DUMPER             -> Automated Source 2 offset & schema extraction engine
└── Zen Chunk Swapper     -> Unreal Engine 5 .utoc/.ucas asset deserialization & real-time skin swaps
```

---

## 📊 Live GitHub Analytics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Stab1xov&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=00f5ff&text_color=c9d1d9&icon_color=00f5ff" height="170" alt="GitHub Stats" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Stab1xov&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=00f5ff&text_color=c9d1d9" height="170" alt="Top Languages" />

<br/><br/>

<img src="https://streak-stats.demolab.com/?user=Stab1xov&theme=tokyonight&hide_border=true&background=0d1117&ring=00f5ff&fire=00f5ff&currStreakLabel=00f5ff" alt="GitHub Streak" />

</div>

---

## 🏢 Corporate Entities

<div align="center">

| Organization | Role | Focus |
|---|---|---|
| **222corp** | Parent Organization | Core systems research, anti-cheat technology, binary security & kernel architecture |
| **Nexa** | Subsidiary Brand | Consumer software, drivers, desktop tools, media engines & developer utilities |

</div>

<br/>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=14,18,32&height=90&section=footer" width="100%"/>
</div>
