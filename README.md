# 🖥️ Hardware Monitor

A real-time system performance monitoring desktop app built with **Electron**, **React**, **TypeScript**, and **Vite**.

Tracks your CPU, RAM, and Storage usage live — right from your system tray.

---

## ✨ Features

- 📊 Real-time CPU, RAM, and Storage monitoring
- 🔔 System tray integration
- ⚡ Built with Electron + React + Vite for fast performance
- 🎨 Clean chart-based UI

---

## 🛠️ Tech Stack

- [Electron](https://www.electronjs.org/) — Desktop shell
- [React](https://react.dev/) — UI framework
- [TypeScript](https://www.typescriptlang.org/) — Type safety
- [Vite](https://vitejs.dev/) — Fast bundler

---

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) v18 or higher
- npm

### Installation

```bash
# Clone the repo
git clone https://github.com/Pathitharun/hardware-monitor.git

# Navigate into the project
cd hardware-monitor

# Install dependencies
npm install
```

### Run in Development

```bash
npm run dev
```

This starts both the Vite dev server and the Electron app simultaneously.

### Build for Production

```bash
npm run build
```

---

## 📁 Project Structure

```
hardware-monitor/
├── src/
│   ├── electron/       # Main process (Electron)
│   │   ├── main.ts
│   │   ├── tray.ts
│   │   ├── menu.ts
│   │   ├── util.ts
│   │   └── Preload.cts
│   └── ui/             # Renderer process (React)
│       ├── App.tsx
│       ├── Chart.tsx
│       └── useStatistics.ts
├── public/
├── package.json
└── vite.config.ts
```

---

## 📄 License

MIT © [Pathi Tarun](https://github.com/Pathitharun)
