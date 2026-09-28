# PowerShell-Crosshair

A simple PowerShell crosshair overlay with a GUI and INI-saved configurations. Built because I wanted a straightforward alternative to Crosshair V2 and Crosshair X without the extra bloat.

<img width="834" height="506" alt="image" src="https://github.com/user-attachments/assets/3db110a1-42b0-428f-b6d2-b5fce1b9846e" />


## 🚀 Quick Start (One-Liner)

You can download, extract, and run the crosshair overlay directly to your Desktop by pasting this single command into PowerShell:

```powershell
iwr "https://raw.githubusercontent.com/aXeSwY/Powershell-Crosshair/main/Crosshair.zip" -OutFile "$HOME\Desktop\C.zip"; Expand-Archive "$HOME\Desktop\C.zip" "$HOME\Desktop\C" -Force; rm "$HOME\Desktop\C.zip"; cd "$HOME\Desktop\C"; powershell -ep Bypass -File .\Crosshair.ps1

