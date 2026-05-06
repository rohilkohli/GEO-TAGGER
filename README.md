<div align="center">

# 🗺️ GEO-TAGGER

### Professional Geo-Tag & Chainage Watermark Generator

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Open%20App-6366f1?style=for-the-badge&logo=googlechrome&logoColor=white)](https://rohilkohli.github.io/GEO-TAGGER/)
[![License](https://img.shields.io/badge/License-MIT-34d399?style=for-the-badge)](LICENSE)
[![Pure HTML](https://img.shields.io/badge/Built%20With-HTML%20%7C%20CSS%20%7C%20JS-f97316?style=for-the-badge&logo=html5&logoColor=white)](index.html)
[![No Dependencies](https://img.shields.io/badge/Dependencies-None-a78bfa?style=for-the-badge)](index.html)

> **Stamp precise geo-location or chainage data directly onto your images — fully customisable, entirely in-browser. Zero uploads, zero servers, zero tracking.**

---
<p align="center">
  <img src="https://raw.githubusercontent.com/rohilkohli/GEO-TAGGER/main/Screenshot_6-5-2026_132458_rohilkohli.github.io.jpeg" width="400" alt="Main Interface">
  <img src="https://raw.githubusercontent.com/rohilkohli/GEO-TAGGER/main/Screenshot_6-5-2026_132746_rohilkohli.github.io.jpeg" width="400" alt="Watermark Output">
</p>

<p align="center">
  <em>Dark mode Interface (left) and Light Mode Interface (right)</em>
</p>

</div>

---

## ✨ Features

| Feature | Description |
|---|---|
| 📍 **Geo-Tag Mode** | Embeds Latitude, Longitude, Elevation, Accuracy, Date, Time & Notes |
| 📏 **Chainage Mode** | Embeds chainage number (e.g. `C123+45.67`), date, and time |
| 🎯 **Auto Location** | One-click GPS location retrieval via the browser Geolocation API |
| 🕐 **Auto Timestamp** | One-click current date & time insertion |
| 🎨 **Full Style Control** | Font family, size, colour, line spacing, box colour, opacity, padding |
| 📐 **Flexible Positioning** | Place watermark at any corner (TL, TR, BL, BR) |
| 📦 **Box Sizing** | Set box width and height manually or let it auto-size to content |
| 🔒 **100 % Client-Side** | Nothing leaves your device — all processing happens in the browser |
| 💾 **Lossless Export** | Downloads as PNG to preserve watermark quality |
| 📱 **Responsive UI** | Works on desktop, tablet, and mobile |

---

## 🚀 Quick Start

### Option A — Use the Live App
Click the badge above or go to:
```
https://rohilkohli.github.io/GEO-TAGGER/
```

### Option B — Run Locally
```bash
# Clone the repository
git clone https://github.com/rohilkohli/GEO-TAGGER.git

# Navigate into it
cd GEO-TAGGER

# Open in your browser (no build step needed!)
open index.html         # macOS
xdg-open index.html     # Linux
start index.html        # Windows
```

> **No Node, no npm, no build tools required.** It's a single HTML file — just open and use.

---

## 🖼️ How to Use

```
Step 1 ──► Upload your image (PNG, JPG, WEBP)
Step 2 ──► Choose a mode: Geo-Tag or Chainage
Step 3 ──► Enter watermark details (or auto-fetch location/time)
Step 4 ──► Customise the style to match your brand
      ──► Preview updates in real time
      ──► Click "Download Watermarked Image"
```

### Geo-Tag Mode
Fill in **Latitude**, **Longitude**, **Elevation**, and **Accuracy** manually, or press **📡 Pick Location Automatically** to read your device's GPS. Add a custom **Note** for any additional context.

### Chainage Mode
Enter a **Chainage Number** in any format (e.g. `CH 0+500`, `C123+45.67`). Add a **Date** and **Time** — or auto-fill them with one click.

---

## 🎨 Style Options Reference

| Control | Range / Options | Default |
|---|---|---|
| Font Family | Inter, Roboto Mono, Arial, Georgia, +10 more | Inter |
| Font Size | 10 – 60 px | 24 px |
| Text Colour | Any hex colour | `#FFFFFF` |
| Line Spacing | 1.0 × – 2.0 × | 1.2 × |
| Box Colour | Any hex colour | `#000000` |
| Box Opacity | 10% – 100% | 50% |
| Box Width | 10 – 10 000 px | 200 px |
| Box Height | 0 (auto) – 1000 px | 0 (auto) |
| Vertical Padding | 0 – 50 px | 10 px |
| Position | TL, TR, BL, BR | Bottom-Left |

---

## 🗂️ Project Structure

```
GEO-TAGGER/
└── index.html   # The entire application (HTML + CSS + JS, single file)
└── README.md    # This file
```

The app intentionally lives in a **single self-contained file** — making it trivially easy to host on GitHub Pages, share as an attachment, or embed anywhere.

---

## 🌐 Browser Support

| Browser | Supported |
|---|---|
| Chrome / Edge 90+ | ✅ Full support |
| Firefox 90+ | ✅ Full support |
| Safari 15+ | ✅ Full support |
| Mobile Chrome / Safari | ✅ Full support |

> **Note:** The Geolocation auto-pick feature requires HTTPS or `localhost`. It will not work over plain HTTP on a remote host.

---

## 🤝 Contributing

Contributions are welcome! To get started:

```bash
# 1. Fork the repo on GitHub
# 2. Clone your fork
git clone https://github.com/YOUR_USERNAME/GEO-TAGGER.git

# 3. Create a feature branch
git checkout -b feature/my-awesome-improvement

# 4. Make your changes to index.html
# 5. Test in multiple browsers

# 6. Commit and push
git add .
git commit -m "feat: add my awesome improvement"
git push origin feature/my-awesome-improvement

# 7. Open a Pull Request on GitHub
```

**Please ensure:**
- All JavaScript IDs and function signatures remain backward-compatible
- The app still works offline (no new CDN dependencies)
- Changes are tested on both desktop and mobile viewports

---

## 📄 License

This project is licensed under the **MIT License**.  
Feel free to use, modify, and distribute it — a credit or star ⭐ is always appreciated!

---

<div align="center">

Made with ❤️ by [Rohil Kohli](https://github.com/rohilkohli)

**If you find this useful, please ⭐ the repo!**

</div>
