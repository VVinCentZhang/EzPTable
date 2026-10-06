# EzPTable

[English](https://github.com/VVinCentZhang/EzPTable/blob/main/README.md) · [**简体中文**](https://github.com/VVinCentZhang/EzPTable/blob/main/README.zh-CN.md) · [繁體中文](https://github.com/VVinCentZhang/EzPTable/blob/main/README.zh-TW.md) · [日本語](https://github.com/VVinCentZhang/EzPTable/blob/main/README.ja.md)

> 一款采用新拟态视觉风格、支持多语言交互、内置全屏 3D 原子轨道云的元素周期表。

EzPTable 是一个 **单文件、零构建** 的网页应用。所有数据、样式与逻辑都封装在一个 HTML 文件里 —— 直接用浏览器打开，或部署到任意静态托管服务，无需任何安装。

---

## ✨ 功能特性

| 功能 | 说明 |
| --- | --- |
| 🧪 **完整元素数据** | 收录全部 118 种元素，包含原子序数、原子量、电子构型、电负性、熔点、沸点、密度、发现年份与氧化态 |
| 🌐 **多语言** | 简体中文、繁體中文、English、日本語 四种语言实时切换 |
| 🎨 **双主题** | 新拟态浅色 / 深色主题，切换时带圆形扩散动画 |
| 🌡️ **温度滑块** | 从 −273 °C 拖到 6000 °C，元素物态实时变化 |
| 🎯 **分类筛选** | 按类别筛选元素（碱金属、稀有气体、镧系、锕系……） |
| 🔍 **即时搜索** | 支持按元素名、符号或原子序数搜索 |
| ⭐ **收藏夹** | 拖拽元素到文件夹即可收藏；左滑或右键移除；长按清空按钮一键清空 |
| 🔖 **元素详情** | 详情弹窗支持 3D 倾斜、动态高光与电子层动画；移动端支持陀螺仪 |
| ⚛️ **电子轨道云** | 全屏 3D 电子概率密度查看器，涵盖 30 个轨道（n = 1–4），10 套配色方案，日 / 夜间主题同步 |
| ☕ **打赏按钮** | 弹弓式交互按钮，弹出收款码弹窗 |

---

## 🚀 在线演示

👉 **<https://VVinCentZhang.github.io/EzPTable/EzPTable.html>**

---

## 🎮 操作指南

### 元素周期表

- **搜索** —— 在搜索框输入元素名、符号或原子序数进行筛选
- **切换语言** —— 点击顶栏的 简 / 繁 / EN / 日
- **切换主题** —— 点击太阳 / 月亮图标，圆形扩散动画从按钮处展开
- **调节温度** —— 拖动滑块查看物态变化；使用 **−273 °C**、**室温**、**重置** 快捷按钮
- **按物态着色** —— 打开「按物态着色」开关，卡片按固体 / 液体 / 气体着色
- **按分类筛选** —— 点击图例行中的分类标签
- **查看详情** —— 点击任意元素卡片，弹窗会随鼠标移动产生 3D 倾斜
- **管理收藏** —— 拖动元素到文件夹即可收藏；左滑或右键收藏项移除；收藏 ≥ 3 项时，长按垃圾桶按钮清空

### 电子轨道云

- **打开** —— 点击顶栏的轨道图标
- **选择轨道** —— 在底部面板中按主量子数 *n* 分组选择轨道
- **切换配色** —— 点击右上角 10 个色块中的任意一个
- **切换主题** —— 点击太阳 / 月亮按钮，元素周期表主题会同步跟随
- **旋转 / 缩放** —— 拖拽旋转视角，滚轮或双指缩放；视角会自动缓慢旋转

---

## 🛠 技术栈

- **原生 JavaScript** —— 无框架、无构建步骤
- **CSS 新拟态（Neumorphism）** —— 柔和阴影设计语言
- **CSS Grid** —— 用于元素周期表网格布局
- **Three.js** *（通过 CDN 动态导入）* —— 用于电子轨道云
- **Font Awesome** —— 图标
- **Google Fonts** —— Noto Sans SC 与 Space Mono

---

## 📁 项目结构

```
EzPTable/
├── EzPTable.html      # 主程序（元素周期表 + 电子轨道云）
├── README.md          # 英文说明文档
├── README.zh-CN.md    # 简体中文说明文档
├── README.zh-TW.md    # 繁体中文说明文档
├── README.ja.md       # 日文说明文档
└── LICENSE            # MIT 许可证
```

---

## 💻 本地运行

无需任何构建工具或依赖，克隆后直接打开即可：

```bash
git clone https://github.com/VVinCentZhang/EzPTable.git
cd EzPTable
# 直接用浏览器打开 EzPTable.html，或本地起服务：
python3 -m http.server 8000
# 然后访问 http://localhost:8000/EzPTable.html
```

---

## 🌐 浏览器兼容性

| 浏览器 | 支持情况 |
| --- | --- |
| Chrome / Edge | ✅ 最新版 |
| Firefox | ✅ 最新版 |
| Safari（macOS / iOS） | ✅ 最新版 |
| 移动端浏览器 | ✅ 响应式布局 |

电子轨道云需要 **WebGL** 与现代浏览器支持。若设备不支持 WebGL，元素周期表本身仍可正常使用。

---

## 📄 许可证

本项目基于 **MIT 许可证** 开源，详见 [LICENSE](LICENSE)。

---

## 🙏 致谢

- 元素数据整理自公开化学参考资料
- 图标来自 [Font Awesome](https://fontawesome.com/)
- 字体来自 [Google Fonts](https://fonts.google.com/)
- 3D 渲染由 [Three.js](https://threejs.org/) 提供

---

⭐ 如果这个项目对你有帮助，欢迎点个 Star！