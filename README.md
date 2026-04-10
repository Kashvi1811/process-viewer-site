# Process State Visualizer

<p align="center">
  <strong>An interactive Operating System process-state simulation with live scheduling analytics.</strong>
</p>

<p align="center">
  🚀 Visual • 🎯 Beginner-friendly • 📊 Metrics-driven • ⚙️ Customizable
</p>

## ✨ Overview
Process State Visualizer is a single-page web app that helps learners understand how an OS process moves through states like NEW, READY, RUNNING, WAITING, and TERMINATED.

It combines animated state transitions, scheduler controls, timeline visualization, and per-process statistics in one clean interface.

## 🧩 Key Features
- 🟦 Live Process Lifecycle lanes (NEW → READY → RUNNING → WAITING → TERMINATED)
- ⏯️ Manual and automatic simulation controls (Step Forward / Auto Run)
- 🧹 Quick Clear All action for instant reset
- 🧪 Custom Process Editor with presets + JSON builder
- ⚙️ Scheduler support: Round Robin and FCFS
- ⌛ Adjustable Round Robin quantum
- 📈 CPU Timeline with process-wise transition slices
- 📝 Activity Log with readable timestamps
- 📊 Process Statistics panel (overall + per-process metrics)
- 👁️ Simple Mode for reduced visual clutter

## 🧮 Metrics Included
- Average Waiting Time
- Average Turnaround Time
- Average Response Time
- CPU Utilization
- Throughput
- Per-process WT / RT / TAT and executed slices

## 🛠️ Tech Stack
- HTML5
- CSS3
- Vanilla JavaScript
- Font Awesome (icons)
- Google Fonts (Sora + Space Grotesk)

## ▶️ Run Locally
1. Open this folder in VS Code.
2. Open [index.html](index.html) in a browser (or use Live Server).

No build step or dependency installation is required.

## 🧭 Quick Usage
1. Click New Process.
2. Use Step Forward for manual transitions or Auto Run for continuous simulation.
3. Expand Advanced Controls for scheduler and speed tuning.
4. Open Custom Process to define your own transition flow.
5. Observe CPU Timeline, Activity Log, and Process Statistics.

## ⌨️ Keyboard Shortcuts
- N: New Process
- Right Arrow: Step Forward
- Space: Toggle Auto Run
- Esc: Close Custom Process modal

## 🌐 GitHub Pages Deployment
If this repository is connected to GitHub Pages:
1. Push updates to the default branch.
2. In GitHub repository settings, enable Pages from the branch root.
3. Open the generated Pages URL.

## 📂 Project Structure
- [index.html](index.html): Full application (UI, styling, and logic)
- [README.md](README.md): Project documentation

## 👩‍💻 Author
Kashvi Soni

---

<p align="center">
  Built for OS learning, demos, and process scheduling visualization.
</p>
