# Hardware Gremlins by ZeroPulse

<p align="left">
  <a href="https://github.com/steventa2024-lgtm/Hardware-Gremlins/releases/latest"><img src="https://img.shields.io/github/v/release/steventa2024-lgtm/Hardware-Gremlins?color=00e5ff&style=flat-square&label=Release" alt="Release"></a>
  <img src="https://img.shields.io/badge/platform-Windows%2010%20%7C%2011%20(64--bit)-5c6bc0?style=flat-square" alt="Platform">
  <img src="https://img.shields.io/badge/telemetry-zero%20%2F%20100%25%20offline-10b981?style=flat-square" alt="Offline">
  <a href="https://hardware-gremlins.vercel.app"><img src="https://img.shields.io/badge/web-live%20portal-cyan?style=flat-square" alt="Website"></a>
</p>

Hardware Gremlins is a zero-overhead Windows desktop companion suite. Two reactive companions—**Purp** and **Volt**—float above your desktop workspaces and fullscreen applications, monitoring your system's hardware performance with real-time autonomous facial expressions and animations.

---

### 🌐 Live Portal & Interactive Simulation
Test each pet's load behavior, inspect reactive shaders, and view dynamic telemetry bars directly in your browser:  
👉 **[hardware-gremlins.vercel.app](https://hardware-gremlins.vercel.app)**

---

### 👾 Companion Fleet Roster

| Pet | Subsystem | Metrics Monitored | Reactive Behaviors |
| :--- | :--- | :--- | :--- |
| **Purp** | **GPU** | VRAM usage, Core Temps, Fan Saturation | Floats comfortably at idle, shows dynamic squinting under 3D boost, sweats under heavy renders, and panics during Out-of-Memory (OOM) states. |
| **Volt** | **CPU** | Core Threads, CPU Load %, Thermals | Cruising animations on base clock, focused expression during hyper-threading workloads, and emergency kernel-panic jitter when throttled. |

---

### 🕹️ Desktop Gestures & Controls

| Action | Control | Description |
| :--- | :--- | :--- |
| **Move** | `Left-Click + Drag` | Reposition either pet anywhere across multi-monitor setups. |
| **Pin / Topmost** | `Double-Click` | Pins the pet permanently above borderless games and fullscreen applications. |
| **Unpin** | `Triple-Click` | Drops the pet back to standard desktop layer. |
| **Diagnostics Menu** | `Right-Click` | Opens the native context menu to toggle the speech bubble, reset coordinates, or shut down the fleet. |

---

### ⚡ Autonomous Simulation States

* **❄️ Idle:** Low load, resting animations, cyan/emerald calm visor states.
* **⚡ Boost:** Elevated clock speeds, angled focus eyes, dynamic thermal warning badges.
* **🔥 Heavy Load:** High saturation (>80%), sweat drop indicators, physical chassis vibration.
* **💥 Limit / OOM:** 100% thread exhaustion or VRAM overrun, 90-degree distress tilt, and visual glitch shader passes.

---

### 🔒 Privacy & Architecture

* **Zero-Network Policy:** Hardware Gremlins contains no outbound networking libraries, tracking analytics, external logging, or cloud sync.
* **Local Kernel Polling:** Metrics are queried locally via native Windows APIs, delta thread counters, and local `nvidia-smi` queries.
* **Hardened Sandbox:** DevTools, external navigation, popup windows, and webviews are disabled within the client runtime.

---

### 📥 Installation & Setup

1. Download **[Hardware-Gremlins-Setup.exe](https://github.com/steventa2024-lgtm/Hardware-Gremlins/releases/latest)**.
2. Run the one-click installer. Shortcuts will be created on your Desktop and Start Menu.
3. Both pets will spawn in the lower-right corner of your primary display.

> **Note on Windows SmartScreen:**  
> Because this is an independent utility without an enterprise EV code-signing certificate, Windows SmartScreen may present a blue prompt on first run. Click **More info** $\rightarrow$ **Run anyway** to initialize.

---

### ⚖️ License & Attribution
© 2026 ZeroPulse. Developed for personal and public desktop hardware monitoring.
