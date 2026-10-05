# 🎯 apex-tune

<div align="center">

**Open-source FPS optimizer for Apex Legends**

*Tunes Windows only — never touches the game.*

[![CI](https://github.com/username/apex-tune/actions/workflows/ci.yml/badge.svg)](https://github.com/username/apex-tune/actions)
[![Python](https://img.shields.io/badge/python-3.10%2B-blue?logo=python&logoColor=white)](https://www.python.org/)
[![Platform](https://img.shields.io/badge/platform-Windows-0078D6?logo=windows&logoColor=white)](https://www.microsoft.com/windows)
[![License](https://img.shields.io/badge/license-MIT-yellow.svg)](LICENSE)
[![Anti-Cheat](https://img.shields.io/badge/EAC-safe-success?logo=shield&logoColor=white)](#-safety)

</div>

---

## ✨ What it does

`apex-tune` brings Windows into a state optimal for Apex Legends — **without touching the game itself**.

| 🖥️ CPU & Power | 🎮 GPU | 🧠 System | 🚀 Launch |
|---|---|---|---|
| Ultimate Performance plan | Hardware GPU scheduling | Game DVR off | Personalized flags |
| High process priority | Fullscreen optimizations off | Power throttling off | Auto-generated |

---

## 🏆 Advantages

- ✅ **Safe for Easy Anti-Cheat** — changes Windows, not the game
- ✅ **Reversible** — one command rolls everything back
- ✅ **Risk levels** — `--safe` for zero-risk, `--all` for everything
- ✅ **Open source** — MIT, fully auditable
- ✅ **Lightweight** — pure Python, no background service

---

## 🚀 Installation

You'll need:
- **Windows 10 or 11**
- **Python 3.10+** — [download here](https://www.python.org/downloads/)
- **Administrator terminal** (right-click PowerShell → "Run as Administrator")

Clone the repo and install the package:

```bash
git clone https://github.com/username/apex-tune.git
cd apex-tune
pip install -e .
```

The `apex-tune` command is now available in your terminal. Verify:

```bash
apex-tune --version
```

To run without installing:

```bash
python -m apex_tune
```

---

## 🛡️ Safety

Works strictly at the OS level. No DLL injection, no memory patching, no hooks. A backup is created automatically before any change.

<div align="center">
<sub>Made with ❤️ for the Apex Legends community</sub>
</div>