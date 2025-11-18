# PM2 Pilot

Authored and maintained by [annuraggg](https://github.com/annuraggg).

## Overview

PM2 Pilot is an open-source web interface for monitoring and managing Node.js processes running under PM2. Designed to provide real-time insights, control, and visibility into your application ecosystem, PM2 Pilot makes it easy to track performance, view logs, and manage processes from a modern browser-based UI.

## Features

- **Real-time process monitoring**: Visualize active Node.js processes managed by PM2.
- **Resource usage tracking**: Track CPU, memory, and uptime for all processes.
- **Log viewer**: Access stdout and stderr logs for each managed process.
- **Process control**: Start, stop, restart, and delete processes directly from the dashboard.
- **Responsive design**: Works smoothly on both desktop and mobile devices.

## Technical Details

Built with React and TypeScript, PM2 Pilot connects to PM2 via a backend API to fetch process data and perform control operations. The frontend features a clean, modular architecture for easy extension and maintenance.

## Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/annuraggg/PM2-Pilot.git
   ```
2. **Install dependencies**
   ```bash
   cd PM2-Pilot
   npm install
   ```
3. **Start the development server**
   ```bash
   npm start
   ```
4. Open your browser and visit `http://localhost:3000` to use the dashboard.


---

Made with ❤️ by [annuraggg](https://github.com/annuraggg)
