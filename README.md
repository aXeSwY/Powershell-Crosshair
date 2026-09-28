# PowerShell-Crosshair

A simple PowerShell crosshair overlay with a GUI and INI-saved configurations. Built because I wanted a straightforward alternative to Crosshair V2 and Crosshair X without the extra bloat.

<img width="834" height="506" alt="image" src="https://github.com/user-attachments/assets/3db110a1-42b0-428f-b6d2-b5fce1b9846e" />


## 🚀 Quick Start (One-Liner)

You can download, extract, and run the crosshair overlay directly to your Desktop by pasting this single command into PowerShell:

```powershell
irm "[https://raw.githubusercontent.com/aXeSwY/Powershell-Crosshair/refs/heads/main/Crosshair.zip](https://raw.githubusercontent.com/aXeSwY/Powershell-Crosshair/refs/heads/main/Crosshair.zip)" -OutFile "~\Desktop\Crosshair.zip"; Expand-Archive "~\Desktop\Crosshair.zip" -DestinationPath "~\Desktop\Crosshair" -Force; rm "~\Desktop\Crosshair.zip"; cd "~\Desktop\Crosshair"; powershell -ExecutionPolicy Bypass -File ".\Crosshair.ps1"

