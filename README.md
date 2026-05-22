# Bambuddy – Home Assistant Add-on

This repository provides a simple Home Assistant App that runs the official **Bambuddy** Docker image inside Home Assistant OS.

Bambuddy is a local companion app for Bambu Lab 3D printers, offering print management, spool tracking, AMS monitoring, notifications, and more.

---

## 🚀 Features
- Runs the official `ghcr.io/maziggy/bambuddy` image
- Exposes Bambuddy on port **8000**

---

## 📦 Installation

1. Open **Home Assistant**  
2. Go to **Settings → Apps → Install App**  
3. Click the menu (⋮) in the top-right corner  
4. Select **Repositories**  
5. Add this repository URL: https://github.com/ElBarto333/hass-addons
6. The **Bambuddy** add-on will appear in the store  
7. Install it and start the App  
8. Open the UI via **"http://[YOUR-HASS-IP]:8000"** → Bambuddy will open
9. Start the Bambuddy configuration

---

## 📝 Notes

- Ingress is intentionally disabled because Bambuddy does not support iframe embedding.
- Make sure port **8000** is enabled in the add-on configuration panel.

---

## 🧡 Credits

All credit for Bambuddy goes to the original project:  
**[Bambuddy](https://bambuddy.cool)**

**[GitHub](https://github.com/maziggy/bambuddy)**

This repository only provides a Home Assistant add-on wrapper.
