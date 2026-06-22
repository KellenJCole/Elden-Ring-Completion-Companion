# Elden Ring Completion Companion

A browser-based companion application that helps **Elden Ring** players achieve 100% item completion by automatically analyzing their save file and tracking missing collectibles.

Unlike traditional checklists, the application is designed to stay open on a second monitor while playing. It synchronizes with the player's save file and updates progress automatically as items are collected.

> **Status:** 🚧 Active development

## Features

### Planned

- 📂 Automatic save file monitoring using the File System Access API
- 👤 Support for multiple character slots
- 🔍 Detect collected and missing
  - ⚔️ Weapons
  - 🛡️ Armor
  - 💍 Talismans
  - 📜 Sorceries
  - 🔥 Incantations
  - 🌪️ Ashes of War
  - 👻 Spirit Ashes
  - 🕺 Gestures
  - And more!
- 📊 Overview mode displaying all remaining collectibles
- 🧭 Guided mode that presents one missing item at a time with acquisition instructions
- 🔍 Search and filtering capabilities
- ⚡ Instant updates after the save file changes

## Tech Stack

- React
- TypeScript
- Tailwind CSS
- Vite

## Getting Started

### Prerequisites

- Node.js
- npm

### Installation

```bash
git clone https://github.com/KellenJCole/Elden-Ring-Completion-Companion.git
cd Elden-Ring-Completion-Companion/frontend
npm install
```

### Run the development server

```bash
npm run dev
```

Open the local URL displayed in the terminal (typically `http://localhost:5173`).


## Project Goals

- Operate entirely in the browser without requiring a backend server
- Automatically detect progression directly from the player's save file
- Minimize manual interaction after the initial save selection
- Provide a fast and intuitive interface for completionist playthroughs
- Maintain a clean, modular, and well-documented codebase
