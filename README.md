# Punch Kick Duck Bot (YOLOv8)

![Python](https://img.shields.io/badge/Python-3.8%2B-blue) ![YOLOv8](https://img.shields.io/badge/AI-YOLOv8-green) ![Platform](https://img.shields.io/badge/Platform-Windows-lightgrey)

An automated bot for the game **Punch Kick Duck** that uses computer vision (YOLOv8) to detect enemies and react instantly. This script is designed to run on Windows and interacts directly with the BlueStacks Android emulator.

## 🚀 Features

* **Real-time Object Detection:** Uses a custom trained YOLOv8 model to identify enemies.
* **Auto-Reaction:** Automatically inputs punches, kicks, or ducks based on the enemy type detected.
* **Windows Optimized:** Tailored for Windows screen capture and input simulation.

> **⚠️ Performance Note:**
> The bot is currently optimized and tested to clear **Levels 1 through 4** in **easy** mode. 
> As the game difficulty increases the action speed of the enemy significantly, the bot may struggle to react in time with other difficulty

## 📋 Prerequisites

Before running the bot, ensure you have the following installed:

1.  **Operating System:** Windows 10 or 11.
2.  **Python:** Version 3.8 or higher.
3.  **BlueStacks Emulator:** You must have [BlueStacks 5](https://www.bluestacks.com/) (or similar) installed.
4.  **GPU (Optional):** NVIDIA GPU with CUDA support is recommended for faster detection, but CPU will work (slower).

## 🛠️ Installation

1.  **Clone the Repository**
    ```bash
    git clone [https://github.com/WoodMMK/punch-kick-duck-bot.git](https://github.com/WoodMMK/punch-kick-duck-bot.git)
    cd punch-kick-duck-bot
    ```

2.  **Create a Virtual Environment (Recommended)**
    ```bash
    python -m venv venv
    .\venv\Scripts\activate
    ```

3.  **Install Dependencies**
    ```bash
    pip install -r requirements.txt
    ```

## ⚙️ Configuration & Setup

### 1. BlueStacks Setup
**Crucial Step:** This bot relies on screen capture.
* Open BlueStacks and launch **Punch Kick Duck**.
* Ensure the emulator window is **active** and visible on your primary screen.

## 🎮 How to Run

1.  Start the game in BlueStacks and start a level.
2.  Run the main script:
    ```bash
    python app.py
    ```
3.  **To Stop:** Press `q` in the terminal to stop the bot.

## ⚠️ Disclaimer
This software is for educational purposes only. Using automation tools in games may violate the Terms of Service of the game or the emulator. Use at your own risk.

---
