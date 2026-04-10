# Process State Visualizer

<p align="center">
  <strong>Interactive OS process-state simulation with live scheduling analytics</strong>
</p>

<p align="center">
  🎓 Learning-first • ⚡ Real-time transitions • 📊 Insightful metrics • 🎨 Modern UI
</p>

<p align="center">
  <a href="#-overview">Overview</a> •
  <a href="#-feature-highlights">Features</a> •
  <a href="#-quick-start">Quick Start</a> •
  <a href="#-project-structure">Structure</a>
</p>

## ✨ Overview
Process State Visualizer is a single-page educational web app for understanding how operating-system processes move across NEW, READY, RUNNING, WAITING, and TERMINATED states.

It combines process flow visualization, scheduler behavior, timeline playback, and performance metrics in one concise interface.

## 🚀 Feature Highlights
- 🧠 Process Lifecycle Board: visual state lanes for NEW, READY, RUNNING, WAITING, and TERMINATED
- 🎮 Simulation Controls: New Process, Step Forward, Auto Run, and Clear All
- ⚙️ Scheduling Mode: Round Robin and FCFS, including configurable quantum
- 🧪 Custom Process Editor: presets + JSON workflow for user-defined transition flows
- 📈 CPU Timeline: process-wise transition bars with time-step context
- 📝 Activity Log: live transition history with readable timestamps
- 📊 Process Statistics: overall metrics plus per-process WT, RT, TAT, and executed slices
- 👀 Simple Mode: reduced-view mode for cleaner demonstrations

## 📊 Metrics Included
- Average Waiting Time
- Average Turnaround Time
- Average Response Time
- CPU Utilization
- Throughput
- Per-process execution and timing breakdown

## 🛠️ Tech Stack
- HTML5
- CSS3
- Vanilla JavaScript
- Font Awesome icons
- Google Fonts (Sora and Space Grotesk)

## ▶️ Quick Start
1. Open this folder in VS Code.
2. Launch [index.html](index.html) in your browser, or run with Live Server.
3. Create a process and step through transitions manually or via Auto Run.

No build step or installation is required.

## ⌨️ Keyboard Shortcuts
- N: Create new process
- Right Arrow: Step forward
- Space: Toggle auto run
- Esc: Close custom editor modal

## 🌐 GitHub Pages
1. Push changes to the default branch.
2. In repository settings, enable GitHub Pages from branch root.
3. Open the generated deployment URL.

## 📂 Project Structure
- [index.html](index.html): complete application (UI, style, and logic)
- [README.md](README.md): project documentation

## 👩‍💻 Author
Kashvi Soni

---

<p align="center">
  Built for OS learning, demos, and process scheduling visualization.
</p>
