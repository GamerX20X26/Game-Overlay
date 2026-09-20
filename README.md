<img width="800" height="500" alt="Screenshot 2026-09-18 185333" src="https://github.com/user-attachments/assets/38edbe3a-0ba2-4b29-b3b8-58b063022966" />

# Game Overlay

A lightweight, controller-friendly Metro-style launcher overlay built with C# and WPF. Designed specifically for living room PCs, couch gaming setups, and handhelds, **Game-Overlay** provides a quick, Xbox Series X-inspired dashboard UI to launch modern games and emulators like **Minecraft** or **xemu** without touching a mouse.

---

## Features

* **Xbox Series X Inspired Aesthetic:** Minimalist, dark-mode Metro layout optimized for TV and desktop screens.
* **Controller Native:** Built-in XInput polling for smooth, zero-latency controller navigation.
* **Graphical Button UI:** Visual, colored Xbox-style circular buttons for clear navigation ($A$, $B$, $X$).
* **Dynamic Icon Extraction:** Uses native Windows system icons pulled directly from target executables.
* **Lightweight & Portable:** JSON-backed configuration (`config.json`) requiring zero installation overhead.

---

## Controls

| Controller Input | Action |
| :--- | :--- |
| <span style="color:#2ecc71;">**[ A ]**</span> | **Select / Launch** selected application |
| <span style="color:#e74c3c;">**[ B ]**</span> | **Exit** / Close overlay |
| <span style="color:#3498db;">**[ X ]**</span> | **Configure** / Direct executable file paths |

---

## Getting Started

1. Download the latest release (`Game Overlay win x64.exe`, `Game Overlay win x86.exe`, or `Game Overlay arm64.exe`) from the [Releases](../../releases) page.
2. Run the downloaded executable (e.g., `Game Overlay win x64.exe`).
3. Press the **X** button on your controller to set up executable file paths for your games or emulators.
4. Settings persist automatically to `config.json` in the same directory.

---

## Building from Source

### Prerequisites
* Windows 10 / 11
* .NET SDK 10.0 or later
* Visual Studio 2022+ with WPF workload installed

### Build Steps
1. Clone the repository:
   ```bash
   git clone [https://github.com/GamerX20X26/Game-Overlay.git](https://github.com/GamerX20X26/Game-Overlay.git)
