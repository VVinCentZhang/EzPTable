# EzPTable

[**English**](https://github.com/VVinCentZhang/EzPTable/blob/main/README.md) · [简体中文](https://github.com/VVinCentZhang/EzPTable/blob/main/README.zh-CN.md) · [繁體中文](https://github.com/VVinCentZhang/EzPTable/blob/main/README.zh-TW.md) · [日本語](https://github.com/VVinCentZhang/EzPTable/blob/main/README.ja.md)

> An interactive periodic table of elements featuring a neumorphic visual design, multi-language support, and a full-screen 3D atomic orbital cloud.

EzPTable is a **single-file, zero-build** web application. All data, styles, and logic live inside one HTML file — open it directly in a browser or serve it from any static host, no installation required.

---

## ✨ Features

| Feature | Description |
| --- | --- |
| 🧪 **Full Element Data** | All 118 elements with atomic number, mass, electron configuration, electronegativity, melting/boiling points, density, discovery year, and oxidation states |
| 🌐 **Multi-language** | English, Simplified Chinese, Traditional Chinese, and Japanese — switchable on the fly |
| 🎨 **Dual Themes** | Neumorphic light and dark themes with a smooth circular-reveal transition |
| 🌡️ **Temperature Slider** | Drag from −273 °C up to 6000 °C and watch element states update in real time |
| 🎯 **Category Filtering** | Filter by category (alkali metal, noble gas, lanthanide, actinide, …) |
| 🔍 **Instant Search** | Search by element name, symbol, or atomic number |
| ⭐ **Favorites** | Drag elements onto the folder to save them; swipe left or right-click to remove; hold the clear button to wipe the list |
| 🔖 **Element Details** | A modal with 3D tilt, dynamic glare, and an animated electron-shell diagram — gyroscope support on mobile |
| ⚛️ **Atomic Orbital Cloud** | A full-screen 3D viewer of electron probability density, covering 30 orbitals (n = 1–4), with 10 color palettes and synchronized dark/light theming |
| ☕ **Coffee Button** | A playful sling-shot button that reveals a support modal |

---

## 🚀 Live Demo

👉 **<https://VVinCentZhang.github.io/EzPTable/EzPTable.html>**

---

## 🎮 How to Use

### Periodic Table

- **Search** — type into the search box to filter by name, symbol, or atomic number
- **Switch language** — click 简 / 繁 / EN / 日 in the header
- **Toggle theme** — click the sun/moon icon; a circular reveal expands from the button
- **Adjust temperature** — drag the slider to see phases update; use **−273 °C**, **Room**, or **Reset** shortcuts
- **Color by state** — toggle the "Color by state" switch to shade cards by solid / liquid / gas
- **Filter by category** — click any chip in the legend row
- **View details** — click any element card; the modal tilts in 3D as you move the cursor
- **Manage favorites** — drag an element onto the folder to save it; swipe left or right-click a chip to remove it; with 3+ items, hold the trash button to clear all

### Atomic Orbital Cloud

- **Open** — click the orbit icon in the header
- **Select an orbital** — choose from the panel at the bottom; groups are sorted by principal quantum number *n*
- **Switch palette** — click any of the 10 color swatches in the top-right corner
- **Switch theme** — click the sun/moon button; the periodic table theme follows in sync
- **Rotate / zoom** — drag to rotate, scroll or pinch to zoom; the view auto-rotates slowly

---

## 🛠 Tech Stack

- **Vanilla JavaScript** — no frameworks, no build step
- **CSS Neumorphism** — soft-shadow design language
- **CSS Grid** — for the periodic table layout
- **Three.js** *(dynamically imported via CDN)* — for the atomic orbital cloud
- **Font Awesome** — icons
- **Google Fonts** — Noto Sans SC & Space Mono

---

## 📁 Project Structure

```
EzPTable/
├── EzPTable.html      # Main application (periodic table + atomic orbital cloud)
├── README.md          # English documentation
├── README.zh-CN.md    # Simplified Chinese documentation
├── README.zh-TW.md    # Traditional Chinese documentation
├── README.ja.md       # Japanese documentation
└── LICENSE            # MIT License
```

---

## 💻 Local Development

No build tools or dependencies required. Simply clone and open:

```bash
git clone https://github.com/VVinCentZhang/EzPTable.git
cd EzPTable
# Open EzPTable.html directly in your browser, or serve locally:
python3 -m http.server 8000
# Then visit http://localhost:8000/EzPTable.html
```

---

## 🌐 Browser Support

| Browser | Supported |
| --- | --- |
| Chrome / Edge | ✅ Latest |
| Firefox | ✅ Latest |
| Safari (macOS / iOS) | ✅ Latest |
| Mobile browsers | ✅ Responsive layout |

The atomic orbital cloud requires **WebGL** and a modern browser. On devices without WebGL support, the periodic table itself still works fully.

---

## 📄 License

Released under the **MIT License**. See [LICENSE](LICENSE) for details.

---

## 🙏 Acknowledgements

- Element data compiled from public chemistry references
- Icons by [Font Awesome](https://fontawesome.com/)
- Fonts by [Google Fonts](https://fonts.google.com/)
- 3D rendering by [Three.js](https://threejs.org/)

---

⭐ If you find this project useful, consider giving it a star!