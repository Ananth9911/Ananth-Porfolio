# ⚡ Ananth | Portfolio

> **"Building scalable systems and analyzing data at high velocity."**

[![Live Demo](https://img.shields.io/badge/Live_Site-00f260?style=for-the-badge&logo=github&logoColor=black)](https://ananth9911.github.io) 
[![Status](https://img.shields.io/badge/System-Online-4ADE80?style=flat-square)](https://ananth9911.github.io)
[![Design](https://img.shields.io/badge/Design-Glassmorphism-blueviolet?style=flat-square)](https://ananth9911.github.io)

---

## 🚀 About The Project

This is not just a static HTML page. It is a **"Headless" Portfolio System** designed to track my engineering velocity in real-time.

Most portfolios are static and outdated the moment they are deployed. This system connects to a **Python Automation Engine** that reads my daily problem-solving logs, processes the data, and pushes live updates to the UI without me touching a single line of frontend code.

### ✨ Key Features
- **GPU-Accelerated UI:** 60FPS animations using optimized CSS transforms.
- **Spotlight Interaction:** JavaScript-driven "flashlight" hover effects (CRED-inspired).
- **Live Telemetry:** Integrates with GitHub APIs to display real-time commit history.
- **Dark Mode Native:** Designed for developer ergonomics with high-contrast data visualization.

---

## ⚙️ The Automation Architecture

I treat my career growth like a production system. 

1.  **Ingestion:** I log daily DSA problems (LeetCode/Codechef) into a raw data stream (CSV).
2.  **Processing:** A Python script (`paint_graph.py`) parses the data, calculates streak metrics, and generates visualization assets (Pie Charts).
3.  **Deployment:** The script commits to a "Headless" repository (`daily-coding-log`), triggering a GitHub paint update.
4.  **Presentation:** This portfolio fetches the generated assets and displays them as a "Mission Control" dashboard.

---

## 🛠️ Tech Stack

| Component | Technology | Use Case |
| :--- | :--- | :--- |
| **Frontend** | HTML5, CSS3 | Semantic structure & Glassmorphism UI |
| **Interaction** | Vanilla JavaScript | Mouse-tracking spotlight effects |
| **Automation** | Python (Pandas/Matplotlib) | Data processing & Asset generation |
| **CI/CD** | GitHub Pages |
