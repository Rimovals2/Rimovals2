<p align="center">
  <img src="https://raw.githubusercontent.com/talamortis/OregonCore/master/logo.png" width="280"><br>
</p>

<h1 align="center">OregonCore — Community Fork</h1>

<p align="center">
  Open-source World of Warcraft: The Burning Crusade server emulator.<br>
  This fork is maintained by the community to keep the project alive, modern, stable, and educational.
</p>

<p align="center">
<a href="https://github.com/Rimovals2/OregonCore"><img src="https://img.shields.io/github/stars/Rimovals2/OregonCore?style=flat&logo=github"></a>
<a href="https://github.com/Rimovals2/OregonCore/commits/main"><img src="https://img.shields.io/github/last-commit/Rimovals2/OregonCore"></a>
<a href="https://github.com/Rimovals2"><img src="https://img.shields.io/badge/GitHub-Steave-181717?logo=github"></a>
<a href="https://discordapp.com/users/347075160571904012"><img src="https://img.shields.io/badge/Contact%20on%20Discord-Rimovals%239986-7289DA?logo=discord&logoColor=white"></a>
</p>

---

## 📦 Project Description

OregonCore is an emulator for **World of Warcraft: The Burning Crusade (2.4.3)**.

The goal of this fork:

- Keep OregonCore alive and updated
- Improve stability, performance and maintainability
- Preserve Eluna Lua engine support
- Community-driven fixes & enhancements
- Learning + open-source development friendly

This project honors and builds upon the original OregonCore work and the wider WoW emulator community heritage (MaNGOS / ScriptDev2 / Trinity roots).

---

## ✅ Build Status

| Compiler       | Platform   | Environment     | Status |
|:---------------|:-----------|:----------------|:------:|
| gcc/g++        | Linux x64  | Eluna Enabled   | [![Linux (gcc) — Eluna][badge-linux-eluna]][actions-linux-eluna] |
| Visual Studio  | Windows x64| Eluna Disabled  | [![Windows (MSVC) — No Eluna][badge-win-no-eluna]][actions-win-no-eluna] |
| Visual Studio  | Windows x64| Eluna Enabled   | [![Windows (MSVC) — Eluna][badge-win-eluna]][actions-win-eluna] |

[badge-linux-eluna]: https://github.com/Rimovals2/OregonCore/actions/workflows/build-linux-eluna.yml/badge.svg?branch=main
[badge-win-eluna]: https://github.com/Rimovals2/OregonCore/actions/workflows/build-windows-eluna.yml/badge.svg?branch=main
[badge-win-no-eluna]: https://github.com/Rimovals2/OregonCore/actions/workflows/build-windows-no-eluna.yml/badge.svg?branch=main

[actions-linux-eluna]: https://github.com/Rimovals2/OregonCore/actions/workflows/build-linux-eluna.yml
[actions-win-eluna]: https://github.com/Rimovals2/OregonCore/actions/workflows/build-windows-eluna.yml
[actions-win-no-eluna]: https://github.com/Rimovals2/OregonCore/actions/workflows/build-windows-no-eluna.yml

---

## 🚀 Getting Started

### 🔧 Requirements

| Component | Linux | Windows |
|----------|-------|--------|
| CMake    | ✅ | ✅ |
| gcc/clang or MSVC | ✅ | ✅ |
| MySQL/MariaDB | ✅ | ✅ |
| OpenSSL | ✅ | ✅ |
| Boost | ✅ | ✅ |

### 📥 Clone Repository

```bash
git clone https://github.com/Rimovals2/OregonCore.git
cd OregonCore
