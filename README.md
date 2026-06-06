# Gothic 1 Remake lock picking assistant

An interactive web-based simulator and solver for lock picking puzzles. This tool allows you to configure complex interdependencies between mechanism discs and instantly calculates the shortest path to solve the puzzle using a Breadth-First Search (BFS) algorithm.

## 🚀 Features

* **Dynamic Disc Builder:** Supports lock mechanisms ranging from 3 to 8 discs.
* **Flexible Connection Mapping:** Easily map dependencies between discs (e.g., turning Disc 1 right triggers Disc 3 to turn left/right).
* **Interactive Step-by-Step Locking Process:** The generated solution log is completely clickable. Clicking any step highlights it and automatically updates the sliders to show the exact state of the mechanism at that specific moment.
* **Persistent Storage (`localStorage`):** Your current disc count, slider positions, and mapped connections are saved automatically so you won't lose your progress upon refreshing the page.
* **Clean & Lightweight UI:** Built with zero external dependencies or heavy libraries. Features a sleek, responsive dark-mode layout optimized for quick navigation.

## 🛠️ Tech Stack

* HTML5 (Semantic elements and input controls)
* CSS3 (Grid Layout, custom range slider styling, and responsive design)
* Pure JavaScript (Vanilla JS, BFS Algorithm)

## 📦 Getting Started

This project is completely serverless and lightweight. It does not require any build tools, compilers, or package managers (like npm).

1. Clone the repository or simply download the `index.html` file:
```bash
  git clone https://github.com/sogarez-cpu/gothic-lock-cracker.git
```
Open the index.html file directly in any modern web browser (Chrome, Firefox, Edge, Safari).

💡 How to Use
Set the Size: Choose the number of discs your lock has from the dropdown.

Map the Links: Use the selectors next to each disc to add connections (e.g., Disk 1 🡆 triggers Disk 3 🡄). Click + to add the link.
Set the Initial State: Drag the sliders to match the current positions of the discs on your screen.

Solve: Click "Crack it!".
Simulate: Click through the step-by-line solution steps in the right panel to watch the lock calibrate in real-time. The goal is achieved when all discs hit the center position (4).
