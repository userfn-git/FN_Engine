# 🚀 FN Rocket League Master Engine Suite

> **Elite Controller Configuration & Automation Platform for Competitive Rocket League**

A professional-grade dashboard for generating optimized Logitech G HUB Lua scripts, tuning physics presets, and managing controller bindings—all from a unified interface designed for esports competitors.

[![Version](https://img.shields.io/badge/version-7.0.0-fuchsia?style=flat-square)](https://github.com/fnesports/FN_Engine)
[![React](https://img.shields.io/badge/React-18.3-61dafb?style=flat-square&logo=react)](https://react.dev)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.5-3178c6?style=flat-square&logo=typescript)](https://www.typescriptlang.org)
[![Vite](https://img.shields.io/badge/Vite-5.4-646cff?style=flat-square&logo=vite)](https://vitejs.dev)

---

## 🎮 What is FN Engine?

FN Engine is a competitive esports utility designed to streamline Rocket League controller setup. It provides:

- **Physics Tuning** – Deadzone presets, hardware profiles, and jitter calibration
- **Key Binding Management** – Aerial, speedflip, half-flip, and G-key mapping
- **Lua Generation** – Auto-generate Logitech G HUB scripts with your custom config
- **Config Backups** – Version and restore TAInput.ini and Lua scripts
- **Training Workflows** – Integrated training pack management and game launchers

Perfect for **esports professionals**, **competitive streamers**, and **content creators** who demand precision and repeatability.

---

## ✨ Features

### 🎛️ **Physics & Bindings Tab**
Fine-tune every control parameter with curated presets for competitive play.

- Internal & dodge deadzone presets
- Hardware profile selection (KBM, controller variants)
- Angle jitter calibration
- Customizable key bindings (keyboard & G-keys)

### 💻 **Lua & Engine Hook Tab**
Generate and manage Logitech G HUB automation scripts.

- One-click Lua config generation
- Versioned script backups with timestamps
- Hook status monitoring and real-time logging
- Advanced macro integration

### ⚙️ **TAInput & G HUB Interop Tab**
Direct configuration export for Rocket League's input system.

- Auto-generate TAInput.ini values
- Backup and restore configurations
- G HUB workflow integration
- Direct physics injection

### 🏆 **Training & Launchers Tab**
Manage training packs and launch workflows.

- Training pack browser
- One-click Rocket League launch
- Session logging and history

### 📚 **G HUB Lua Docs Tab**
Embedded Logitech G HUB Lua API reference.

- Function signatures and examples
- Event handling patterns
- Quick copy-paste code snippets

### 🖥️ **Real-time Console**
Live action log with color-coded status events.

- Success, error, warning, and info levels
- Full session history
- Clear and export capabilities

---

## 🏗️ Tech Stack

- **React 18** – Modern UI framework
- **TypeScript** – Type-safe development
- **Vite** – Lightning-fast build and dev server
- **Tailwind CSS** – Responsive dark esports aesthetic
- **Lucide React** – Beautiful icon library

---

## 🚀 Quick Start

### Prerequisites
- Node.js 18+
- npm or yarn

### Installation

```bash
git clone https://github.com/fnesports/FN_Engine.git
cd FN_Engine
npm install
```

### Development

```bash
npm run dev
```

Opens the dashboard at `http://localhost:3000`.

### Production Build

```bash
npm run build
```

Optimized bundle ready for deployment.

### Preview Build

```bash
npm run preview
```

Test the production build locally.

---

## 📋 Project Structure

```
FN_Engine/
├── src/
│   ├── App.tsx                 # Main application
│   ├── components/             # Tabbed UI components
│   ├── data/                   # Config presets & defaults
│   ├── utils/                  # Lua & TAInput generators
│   ├── types.ts                # TypeScript interfaces
│   └── main.tsx                # React entry point
├── index.html                  # App shell
├── package.json                # Dependencies
├── tsconfig.json               # TypeScript config
├── vite.config.ts              # Vite config
└── README.md                   # This file
```

---

## 🎯 Workflow

1. **Configure** – Adjust physics and key bindings in the Physics tab
2. **Generate** – Create Lua scripts and TAInput configs with one click
3. **Backup** – Save versioned copies before applying changes
4. **Launch** – Start Rocket League with your optimized setup
5. **Iterate** – Restore backups and refine your config in real time

---

## 🔧 Companion Assets

This repository also includes:

- **FN_Engine_v50.ps1** – PowerShell automation script for advanced workflows
- **FN_Engine_v50.exe** – Windows executable for standalone operation

Both complement the web dashboard and can be integrated into your esports automation pipeline.

---

## 📦 Default Presets

The app ships with battle-tested presets:

| Category | Example |
|----------|---------|
| **Deadzones** | NWPO Esports Pro (0.07), Ultra Low (0.05), Standard (0.10) |
| **Hardware** | KBM Esports Pro (Logitech G502X), Xbox Controller, PS5 DualSense |
| **Jitter** | Pro (1.0°), Standard (1.5°), Relaxed (2.0°) |
| **Keys** | SpaceBar (Aerial), LeftShift (Speedflip), S (Half-Flip) |

Fully customizable for your playstyle.

---

## 🔐 Security

See [SECURITY.md](./SECURITY.md) for responsible disclosure and security guidelines.

---

## 📄 License

This project does not currently declare a license. If you plan to distribute or build on this work, please confirm licensing intentions with the repository maintainers.

---

## 🤝 Contributing

We welcome contributions from the competitive community.

```bash
npm run build  # Validate your changes
npm run dev    # Test locally
```

Submit a PR with a clear description of your enhancement or fix.

---

## 🎬 About FN Esports

FN Engine is built by esports professionals for esports professionals. Designed with competitive precision in mind.

**For support, issues, or feature requests:** [Open an issue](https://github.com/fnesports/FN_Engine/issues)

---

<div align="center">

**Made for Rocket League competitors who demand precision.**

[🌐 Website](https://fnesports.com) • [📧 Contact](mailto:contact@fnesports.com) • [🐦 Twitter](https://x.com/fnesports)

</div>
