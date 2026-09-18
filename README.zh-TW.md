# EzPTable

> 一個單檔案 HTML 實作的互動式元素週期表 —— 新擬態 + 玻璃擬態、四語言支援、溫度模擬、3D 元素卡片。

[English](README.md) · [简体中文](README.zh-CN.md) · [**繁體中文**](README.zh-TW.md) · [日本語](README.ja.md)

---

## ✨ 功能特色

| 功能 | 說明 |
|------|------|
| 🧪 **完整元素資料** | 涵蓋 1–118 號元素，包含原子量、熔點、沸點、電負性、電子構型、密度、發現年份等 |
| 🌡️ **溫度模擬** | 拖曳滑桿（−273°C → 6000°C），即時顯示每種元素在對應溫度下的物態（固 / 液 / 氣） |
| 🎨 **雙重視覺風格** | 新擬態陰影 + 玻璃擬態光暈，支援淺色 / 深色主題一鍵切換 |
| 🌐 **四語言支援** | 简体中文、繁體中文、English、日本語，介面與元素名稱同步切換 |
| 🔍 **搜尋與篩選** | 支援依元素名稱、符號、原子序搜尋，也可依分類（鹼金屬、鹵素等）篩選 |
| 🎴 **3D 互動卡片** | 點擊元素彈出詳情卡，滑鼠 / 觸控 / 重力感應驅動 3D 傾斜與高光效果 |
| ⚛️ **原子結構動畫** | 詳情卡內動態繪製電子層分布，各軌道獨立旋轉 |
| 📱 **響應式設計** | 桌機、平板、手機自適應，行動端卡片尺寸自動縮放 |
| 🚀 **零依賴** | 無需建置工具、無 npm 套件，僅透過 CDN 引入字型與圖示 |

---

## 🖼️ 線上預覽

**Live Demo:** https://VVinCentZhang.github.io/EzPTable/

> 根路徑會自動跳轉到 `EzPTable.html`。
> 若尚未開啟，請到 **Settings → Pages → Source: `main` 分支** 中啟用 GitHub Pages。

---

## 🚀 快速開始

### 方式一：線上開啟

直接造訪 👉 https://VVinCentZhang.github.io/EzPTable/

### 方式二：本機執行

1. 下載或複製本倉庫
2. 用任意現代瀏覽器開啟 `EzPTable.html`
3. 完成 ✅

```bash
git clone https://github.com/VVinCentZhang/EzPTable.git
cd EzPTable
open EzPTable.html          # macOS
# 或: start EzPTable.html     (Windows)
# 或: xdg-open EzPTable.html  (Linux)
```

---

## 🕹️ 操作指南

- **切換語言** —— 點擊頂部「简 / 繁 / EN / 日」按鈕
- **切換主題** —— 點擊右上角 🌙 / ☀️ 圖示
- **調整溫度** —— 拖曳溫度滑桿，或點擊「−273°C」「室溫」「重設」快捷鍵
- **依物態著色** —— 開啟溫度面板右側的開關，卡片顏色隨物態變化
- **搜尋元素** —— 在搜尋框輸入元素名稱、符號或原子序
- **依分類篩選** —— 點擊分類標籤（如「鹵素」），再次點擊取消篩選
- **查看詳情** —— 點擊任意元素卡片，彈出包含原子動畫的詳情面板

---

## 🧰 技術棧

- 純 **HTML + CSS + JavaScript**，無框架、無建置步驟
- **CSS Grid** 建構週期表版面
- **CSS 變數** 實現主題切換與卡片配色
- **3D Transform** + `requestAnimationFrame` 實現傾斜與光澤動畫
- **`DeviceOrientationEvent`** 實現行動端重力感應
- **字型：** [Noto Sans SC](https://fonts.google.com/noto/specimen/Noto+Sans+SC)、[Space Mono](https://fonts.google.com/specimen/Space+Mono)
- **圖示：** [Font Awesome Free](https://fontawesome.com/)（CC BY 4.0）

---

## 📂 專案結構

```
EzPTable/
├── EzPTable.html       # 主程式 —— 元素週期表
├── index.html          # 重定向頁 → EzPTable.html
├── README.md           # English (default)
├── README.zh-CN.md     # 简体中文
├── README.zh-TW.md     # 繁體中文
├── README.ja.md        # 日本語
├── LICENSE
└── .gitignore
```

---

## 🌐 瀏覽器相容性

| 瀏覽器 | 版本 |
|--------|------|
| Chrome / Edge | 88+ |
| Firefox | 85+ |
| Safari | 14+ |

> 行動端重力感應功能需 HTTPS 環境與使用者授權。

---

## 🤝 貢獻

歡迎提交 Issue 或 Pull Request！

1. Fork 本倉庫
2. 建立特性分支（`git checkout -b feature/amazing-feature`）
3. 提交變更（`git commit -m 'Add some amazing feature'`）
4. 推送分支（`git push origin feature/amazing-feature`）
5. 發起 Pull Request

---

## 📄 授權條款

本專案採用 [MIT License](LICENSE) 開源。

---

## ⭐ Star History

如果這個專案對你有幫助，歡迎給個 Star ⭐

---

**Made with ❤️ as a single HTML file.**