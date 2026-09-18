# EzPTable

> An interactive periodic table in a single HTML file — neumorphism + glassmorphism, 4 languages, temperature simulation, and 3D element cards.

**🌐 Language / 语言 / 語言 / 言語:**
[**English**](README.md) ·
[简体中文](README.zh-CN.md) ·
[繁體中文](README.zh-TW.md) ·
[日本語](README.ja.md)

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| 🧪 **Complete Element Data** | All 118 elements with atomic mass, melting/boiling points, electronegativity, electron configuration, density, discovery year, and more |
| 🌡️ **Temperature Simulation** | Drag the slider (−273°C → 6000°C) to see each element's phase (solid / liquid / gas) update in real time |
| 🎨 **Dual Aesthetic** | Neumorphic shadows + glassmorphic glow, with one-click light/dark theme toggle |
| 🌐 **4 Languages** | Simplified Chinese, Traditional Chinese, English, Japanese — UI and element names switch together |
| 🔍 **Search & Filter** | Search by name, symbol, or atomic number; filter by category (alkali metals, halogens, etc.) |
| 🎴 **3D Interactive Cards** | Click any element to open a detail card with mouse / touch / gyroscope-driven 3D tilt and glare |
| ⚛️ **Atom Animation** | Dynamic electron shell rendering in the detail card, with independently rotating orbits |
| 📱 **Responsive Design** | Adapts to desktop, tablet, and mobile, with auto-scaling card sizes |
| 🚀 **Zero Dependencies** | No build tools, no npm packages — just CDN-hosted fonts and icons |

---

## 🖼️ Demo

**Live demo:** https://VVinCentZhang.github.io/EzPTable/EzPTable.html

> Enable GitHub Pages in **Settings → Pages → Source: `main` branch** to activate.

---

## 🚀 Getting Started

1. Download or clone this repository
2. Open `EzPTable.html` in any modern browser
3. Done ✅

```bash
git clone https://github.com/VVinCentZhang/EzPTable.git
cd EzPTable
open EzPTable.html          # macOS
# or: start EzPTable.html     (Windows)
# or: xdg-open EzPTable.html  (Linux)
```

---

## 🕹️ Controls

- **Switch language** — Click the `简 / 繁 / EN / 日` buttons in the header
- **Switch theme** — Click the 🌙 / ☀️ icon in the top-right corner
- **Adjust temperature** — Drag the temperature slider, or use the `−273°C` / `Room` / `Reset` shortcuts
- **Color by phase** — Toggle the switch on the right of the temperature panel; card colors follow the phase
- **Search elements** — Type a name, symbol, or atomic number into the search box
- **Filter by category** — Click a category chip (e.g. `Halogen`); click again to clear
- **View details** — Click any element card to open the detail panel with the atom animation

---

## 🧰 Tech Stack

- Pure **HTML + CSS + JavaScript** — no frameworks, no build step
- **CSS Grid** for the periodic table layout
- **CSS variables** for theming and card colors
- **3D Transform** + `requestAnimationFrame` for tilt and glare animation
- **`DeviceOrientationEvent`** for mobile gyroscope support
- **Fonts:** [Noto Sans SC](https://fonts.google.com/noto/specimen/Noto+Sans+SC), [Space Mono](https://fonts.google.com/specimen/Space+Mono)
- **Icons:** [Font Awesome Free](https://fontawesome.com/) (CC BY 4.0)

---

## 📂 Project Structure

```
EzPTable/
├── EzPTable.html       # Everything lives in this single file
├── README.md           # English (default)
├── README.zh-CN.md     # 简体中文
├── README.zh-TW.md     # 繁體中文
├── README.ja.md        # 日本語
├── LICENSE
└── .gitignore
```

---

## 🌐 Browser Compatibility

| Browser | Version |
|---------|---------|
| Chrome / Edge | 88+ |
| Firefox | 85+ |
| Safari | 14+ |

> Mobile gyroscope requires an HTTPS environment and user permission.

---

## 🤝 Contributing

Issues and pull requests are welcome!

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## ⭐ Star History

If this project helps you, please give it a star ⭐

---

**Made with ❤️ as a single HTML file.**