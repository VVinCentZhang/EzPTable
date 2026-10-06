# EzPTable

[English](https://github.com/VVinCentZhang/EzPTable/blob/main/README.md) · [简体中文](https://github.com/VVinCentZhang/EzPTable/blob/main/README.zh-CN.md) · [**繁體中文**](https://github.com/VVinCentZhang/EzPTable/blob/main/README.zh-TW.md) · [日本語](https://github.com/VVinCentZhang/EzPTable/blob/main/README.ja.md)

> 一款採用新擬態視覺風格、支援多語言互動、內建全螢幕 3D 原子軌道雲的元素週期表。

EzPTable 是一個 **單檔案、零建置** 的網頁應用。所有資料、樣式與邏輯都封裝在一個 HTML 檔案裡 —— 直接用瀏覽器開啟，或部署到任意靜態託管服務，無需任何安裝。

---

## ✨ 功能特性

| 功能 | 說明 |
| --- | --- |
| 🧪 **完整元素資料** | 收錄全部 118 種元素，包含原子序數、原子量、電子組態、電負度、熔點、沸點、密度、發現年份與氧化態 |
| 🌐 **多語言** | 簡體中文、繁體中文、English、日本語 四種語言即時切換 |
| 🎨 **雙主題** | 新擬態淺色 / 深色主題，切換時帶圓形擴散動畫 |
| 🌡️ **溫度滑桿** | 從 −273 °C 拖到 6000 °C，元素物態即時變化 |
| 🎯 **分類篩選** | 依類別篩選元素（鹼金屬、稀有氣體、鑭系、錒系……） |
| 🔍 **即時搜尋** | 支援依元素名、符號或原子序數搜尋 |
| ⭐ **收藏夾** | 拖曳元素到資料夾即可收藏；左滑或右鍵移除；長按清空按鈕一鍵清空 |
| 🔖 **元素詳情** | 詳情彈窗支援 3D 傾斜、動態高光與電子層動畫；行動端支援陀螺儀 |
| ⚛️ **電子軌道雲** | 全螢幕 3D 電子機率密度檢視器，涵蓋 30 個軌道（n = 1–4），10 套配色方案，日 / 夜間主題同步 |
| ☕ **贊助按鈕** | 彈弓式互動按鈕，彈出收款碼視窗 |

---

## 🚀 線上展示

👉 **<https://VVinCentZhang.github.io/EzPTable/EzPTable.html>**

---

## 🎮 操作指南

### 元素週期表

- **搜尋** —— 在搜尋框輸入元素名、符號或原子序數進行篩選
- **切換語言** —— 點擊頂欄的 简 / 繁 / EN / 日
- **切換主題** —— 點擊太陽 / 月亮圖示，圓形擴散動畫從按鈕處展開
- **調節溫度** —— 拖曳滑桿查看物態變化；使用 **−273 °C**、**室溫**、**重置** 快捷按鈕
- **依物態著色** —— 開啟「依物態著色」開關，卡片依固體 / 液體 / 氣體著色
- **依分類篩選** —— 點擊圖例列中的分類標籤
- **檢視詳情** —— 點擊任意元素卡片，彈窗會隨滑鼠移動產生 3D 傾斜
- **管理收藏** —— 拖曳元素到資料夾即可收藏；左滑或右鍵收藏項移除；收藏 ≥ 3 項時，長按垃圾桶按鈕清空

### 電子軌道雲

- **開啟** —— 點擊頂欄的軌道圖示
- **選擇軌道** —— 在底部面板中依主量子數 *n* 分組選擇軌道
- **切換配色** —— 點擊右上角 10 個色塊中的任意一個
- **切換主題** —— 點擊太陽 / 月亮按鈕，元素週期表主題會同步跟隨
- **旋轉 / 縮放** —— 拖曳旋轉視角，滾輪或雙指縮放；視角會自動緩慢旋轉

---

## 🛠 技術棧

- **原生 JavaScript** —— 無框架、無建置步驟
- **CSS 新擬態（Neumorphism）** —— 柔和陰影設計語言
- **CSS Grid** —— 用於元素週期表網格佈局
- **Three.js** *（透過 CDN 動態匯入）* —— 用於電子軌道雲
- **Font Awesome** —— 圖示
- **Google Fonts** —— Noto Sans SC 與 Space Mono

---

## 📁 專案結構

```
EzPTable/
├── EzPTable.html      # 主程式（元素週期表 + 電子軌道雲）
├── README.md          # 英文說明文件
├── README.zh-CN.md    # 簡體中文說明文件
├── README.zh-TW.md    # 繁體中文說明文件
├── README.ja.md       # 日文說明文件
└── LICENSE            # MIT 授權條款
```

---

## 💻 本機執行

無需任何建置工具或相依套件，複製後直接開啟即可：

```bash
git clone https://github.com/VVinCentZhang/EzPTable.git
cd EzPTable
# 直接用瀏覽器開啟 EzPTable.html，或本機起服務：
python3 -m http.server 8000
# 然後瀏覽 http://localhost:8000/EzPTable.html
```

---

## 🌐 瀏覽器相容性

| 瀏覽器 | 支援情況 |
| --- | --- |
| Chrome / Edge | ✅ 最新版 |
| Firefox | ✅ 最新版 |
| Safari（macOS / iOS） | ✅ 最新版 |
| 行動端瀏覽器 | ✅ 響應式佈局 |

電子軌道雲需要 **WebGL** 與現代瀏覽器支援。若裝置不支援 WebGL，元素週期表本身仍可正常使用。

---

## 📄 授權條款

本專案基於 **MIT 授權條款** 開源，詳見 [LICENSE](LICENSE)。

---

## 🙏 致謝

- 元素資料整理自公開化學參考資料
- 圖示來自 [Font Awesome](https://fontawesome.com/)
- 字體來自 [Google Fonts](https://fonts.google.com/)
- 3D 渲染由 [Three.js](https://threejs.org/) 提供

---

⭐ 如果這個專案對你有幫助，歡迎給個 Star！