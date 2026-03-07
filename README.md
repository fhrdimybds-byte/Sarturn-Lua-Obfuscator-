# 🪐 Saturn Nexus V4 | Elite Lua Obfuscator

![Version](https://img.shields.io/badge/Version-4.0.0-0ea5e9?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)
![Platform](https://img.shields.io/badge/Platform-Roblox%20%2F%20Luau-white?style=for-the-badge)

**Saturn Nexus V4** is a high-performance, web-based Luau obfuscator designed to protect your scripts from decompilers and leachers. Built with a sleek Glassmorphism UI and a powerful **v34 Encryption Engine**, it offers professional-grade protection directly from your mobile or desktop browser.

---

## ✨ Key Features

* **🛡️ v34 Encryption Engine:** Advanced XOR-based encryption with dynamic salt keys.
* **🧹 Smart Minifier:** Automatically strips comments, whitespaces, and collapses code into a single high-performance line.
* **🌌 Particle Background:** Interactive floating particles and connection lines for a premium "hacker" aesthetic.
* **🎨 Multi-Theme Support:** Switch instantly between **Saturn Blue**, **Nebula Purple**, and **Emerald Hacker** modes (Preferences are saved via LocalStorage).
* **⚡ Ultra Responsive:** Optimized for mobile editors like **QuickEdit** and high-end desktop browsers.
* **🌀 Interactive UI:** Features a custom preloader, ripple click effects, and smooth transitions.

---

## 🚀 How to Use

1.  **Load:** Open the `index.html` file in any modern browser.
2.  **Input:** Paste your raw Lua/Luau script into the **Input Script** area.
3.  **Process:** Click the **Obfuscate** button. The engine will minify and encrypt your code simultaneously.
4.  **Export:** Click **Copy** to save the protected code to your clipboard.



---

## 🛠️ Technical Details

Saturn Nexus utilizes a Virtual Machine (VM) approach to execute encrypted hex strings. 
The process follows this pipeline:
1.  **Regex Cleaning:** Removes all non-essential characters.
2.  **XOR Transformation:** Encodes the byte-stream using a randomized salt.
3.  **Hex Formatting:** Converts the result into a protected table.
4.  **Loadstring Wrapper:** Wraps the logic into a self-executing VM that uses `bit32` for high-speed decryption.
5.  **⛓️‍💥Anti Deobfuscate:**
The Hex Deobfuscators cannot deobfuscate the Saturn Moon Obfuscator. 
---

## ⚠️ Disclaimer

This tool is intended for personal use and script protection. While Saturn Nexus provides strong protection against most common deobfuscators, no obfuscation is 100% uncrackable. Always keep backups of your original source code.

---

<p align="center">
  By SaturnStudio</b>
</p>
