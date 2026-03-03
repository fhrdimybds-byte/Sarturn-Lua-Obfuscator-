# 🪐 Saturn Obfuscator V20 - Ultra Support

![License](https://img.shields.io/badge/License-MIT-00ff88.svg)
![Version](https://img.shields.io/badge/Version-20.0-blue.svg)
![Platform](https://img.shields.io/badge/Platform-Roblox-lightgrey.svg)

**Saturn V20** is a high-performance obfuscator specifically engineered for the Roblox scripting community. Unlike other web-based obfuscators, Saturn utilizes a **Memory Buffer Table** engine, ensuring 100% compatibility with complex UI libraries such as **Luna UI Library**.



## 🚀 Key Features

* **Luna UI Ready:** The only free obfuscator that won't crash or break the Luna UI Library's metadata.
* **Intelligent Minify:** Strips comments and unnecessary whitespace before encryption, drastically reducing the final file size.
* **Memory Buffer (V17 Engine):** Uses `table.concat` to rebuild code in RAM, preventing "silent crashes" on mobile executors (Delta, Fluxus, Arceus).
* **Semicolon Encoding:** Integer-based encoding that bypasses "malformed escape sequence" errors common in standard string obfuscation.
* **Thread Injection:** Runs the script in a separate thread (`task.spawn`) to ensure maximum UI performance and stability.

## 🛠️ How to Use

1.  Access the project link (e.g., `https://fhrdimybds-byte.github.io/Sarturn-Lua-Obfuscator-/`).
2.  Paste your Source Code into the top input box.
3.  Click **OBFUSCATE**.
4.  Copy the output and use it in your favorite executor.

## 🔒 Security Layers

Saturn V20 applies multiple layers of protection:
1.  **Metadata Cleaning:** Removes all traces of the original author and comments.
2.  **XOR Shift:** Mathematical encryption applied to every single character.
3.  **Environment Virtualization:** Uses `setfenv` to isolate execution and prevent environment leaks.
4.  **Anti-Dump Essentials:** A structure designed to frustrate simple deobfuscators and debuggers.

## 📋 Terms of Use

This project was created for educational purposes and intellectual property protection. The developer is not responsible for:
- In-game bans.
- Use of the software to hide malicious code (Loggers, Backdoors, etc.).
- Execution failures on unofficial or outdated executors.



---
Developed with ❤️ by [SaturnStudio]
