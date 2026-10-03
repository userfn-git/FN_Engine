# FN Rocket League Master Engine Suite

A modern utility for tuning Rocket League controller and keyboard behavior, generating Logitech G HUB Lua scripts, and preparing TAInput configuration values in a single workflow.

This repository combines a React + TypeScript dashboard with companion automation assets for the FN Engine ecosystem, making it easier to manage physics presets, key mappings, Lua generation, backups, and training workflows.

## Overview

The app is organized around a tabbed dashboard with these focus areas:

- Physics & Bindings
  - internal deadzone tuning
  - dodge deadzone configuration
  - hardware profile selection
  - angle jitter settings
  - aerial, speedflip, and half-flip key binds
  - G-key mapping setup

- Lua & Engine Hook
  - generate Lua config scripts
  - backup and restore script versions
  - hook status simulation and log tracking

- TAInput & G HUB Interop
  - generate TAInput.ini values
  - preserve backups of TAInput configuration
  - integrate with Logitech G HUB workflow assumptions

- Training & Launchers
  - manage training packs
  - launch Rocket League flows from the UI

- G HUB Lua Docs
  - embedded API reference panel for Logitech G HUB Lua usage

## Features

- React front-end with Vite
- TypeScript-based configuration model
- Tailwind styling for a dark esports dashboard look
- Live log console for actions and status events
- Lua script generation for Rocket League automation workflows
- TAInput.ini generation and versioned backups
- G-key and keyboard binding configuration
- Training pack management for practice flow

## Project Structure

```text
.
├── .env.example
├── .github/
├── FN_Engine_v50.exe
├── FN_Engine_v50.ps1
├── README.md
├── SECURITY.md
├── index.html
├── metadata.json
├── package.json
├── src/
│   ├── App.tsx
│   ├── components/
│   ├── data/
│   ├── index.css
│   ├── main.tsx
│   ├── types.ts
│   └── utils/
├── tsconfig.json
├── vite.config.ts
└── RL_Esports.ico
```

## Tech Stack

- React 18
- TypeScript
- Vite
- Tailwind CSS
- Lucide React icons
- Motion library

## Quick Start

### Prerequisites

- Node.js 18+
- npm

### Install dependencies

```bash
npm install
```

### Run locally

```bash
npm run dev
```

This starts the Vite dev server for the dashboard.

### Production build

```bash
npm run build
```

The production bundle is generated in the `dist/` directory.

### Preview production build

```bash
npm run preview
```

## Configuration Notes

The app uses an opinionated set of defaults as a starting point, including:

- internal deadzone presets
- dodge deadzone presets
- hardware profile presets
- angle jitter options
- default keybindings and G-key assignments

You can tune these directly from the UI and regenerate the exported Lua / TAInput content.

## Usage

1. Open the app in the browser.
2. Adjust physics and binding values on the Physics & Bindings tab.
3. Generate the Lua script and TAInput configuration.
4. Use the backup tools to save iterative states.
5. Launch and validate in your Rocket League workflow.

## Notes

This repository contains both:

- a browser-based configuration dashboard, and
- a companion Windows executable / PowerShell automation asset (`FN_Engine_v50.exe` and `FN_Engine_v50.ps1`).

The README focuses on the application and development workflow for the source code in this repository.

## Security

Please review `SECURITY.md` for the repository's security reporting guidance.

## License

This repository does not appear to declare a project license in the root files inspected here. If you plan to distribute or reuse the project outside the repository context, confirm the intended licensing before publication or redistribution.

## Contributing

Contributions are welcome. The recommended flow is:

```bash
npm install
npm run build
```

Then validate the generated UI in the local dev environment before submitting changes.
