# F.Crack Player 🎵

A sleek, modern, and highly customizable desktop music player built with Python and `customtkinter`. F.Crack Player is designed to offer a smooth audio experience with a stunning dark neon aesthetic and seamless Windows integration. 

This repository contains the complete source code, including the music player application, the portable/system compilation scripts, and a smart, bilingual Windows installer.

## ✨ Features

* **Modern User Interface:** Built with `customtkinter` featuring a symmetrical layout, dark mode by default, and customizable neon color themes.
* **Format Support:** Plays popular audio formats (.mp3, .wav, .flac, .ogg, etc.).
* **Smart Installer & Uninstaller:** Comes with a custom-built installer (`installer.py`) that supports both **Full System Installation** (with Start Menu shortcuts and registry setup) and **Portable Extraction**.
* **Windows OS Detection:** The installer automatically handles file associations gracefully across Windows 7, Windows 10, and Windows 11.
* **Bilingual Setup:** The installation process supports both English and Spanish, adapting to the user's preference and OS language automatically.

## 🛠️ Built With

* **Python 3**
* **[CustomTkinter](https://github.com/TomSchimansky/CustomTkinter):** For the modern GUI.
* **PyInstaller:** For compiling the executable files and generating the setup packages.

## 🚀 Getting Started

If you want to run the player from the source code or build the installer yourself:

### Prerequisites
Make sure you have Python installed and install the required dependencies:
```bash
pip install customtkinter pynput mutagen pillow
