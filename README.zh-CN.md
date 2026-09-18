# EzPTable

> 一个单文件 HTML 实现的交互式元素周期表 —— 新拟态 + 玻璃拟态、四语言支持、温度模拟、3D 元素卡片。

**🌐 Language / 语言 / 語言 / 言語:**
[English](README.md) ·
[**简体中文**](README.zh-CN.md) ·
[繁體中文](README.zh-TW.md) ·
[日本語](README.ja.md)

---

## ✨ 功能特性

| 功能 | 说明 |
|------|------|
| 🧪 **完整元素数据** | 覆盖 1–118 号元素，包含原子量、熔点、沸点、电负性、电子构型、密度、发现年份等 |
| 🌡️ **温度模拟** | 拖动滑杆（−273°C → 6000°C），实时显示每种元素在对应温度下的物态（固 / 液 / 气） |
| 🎨 **双重视觉风格** | 新拟态阴影 + 玻璃拟态光晕，支持浅色 / 深色主题一键切换 |
| 🌐 **四语言支持** | 简体中文、繁體中文、English、日本語，界面与元素名称同步切换 |
| 🔍 **搜索与筛选** | 支持按元素名称、符号、原子序数搜索，也可按分类（碱金属、卤素等）筛选 |
| 🎴 **3D 交互卡片** | 点击元素弹出详情卡，鼠标 / 触屏 / 重力感应驱动 3D 倾斜与高光效果 |
| ⚛️ **原子结构动画** | 详情卡内动态绘制电子层分布，各轨道独立旋转 |
| 📱 **响应式设计** | 桌面、平板、手机自适应，移动端卡片尺寸自动缩放 |
| 🚀 **零依赖** | 无需构建工具、无 npm 包，仅通过 CDN 引入字体与图标 |

---

## 🖼️ 在线预览

**Live Demo:** https://VVinCentZhang.github.io/EzPTable/EzPTable.html

> 在 **Settings → Pages → Source: `main` 分支** 中开启 GitHub Pages 即可访问。

---

## 🚀 快速开始

1. 下载或克隆本仓库
2. 用任意现代浏览器打开 `EzPTable.html`
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

- **切换语言** —— 点击顶部「简 / 繁 / EN / 日」按钮
- **切换主题** —— 点击右上角 🌙 / ☀️ 图标
- **调整温度** —— 拖动温度滑杆，或点击「−273°C」「室温」「重置」快捷键
- **按物态着色** —— 打开温度面板右侧的开关，卡片颜色随物态变化
- **搜索元素** —— 在搜索框输入元素名称、符号或原子序数
- **按分类筛选** —— 点击分类标签（如「卤素」），再次点击取消筛选
- **查看详情** —— 点击任意元素卡片，弹出包含原子动画的详情面板

---

## 🧰 技术栈

- 纯 **HTML + CSS + JavaScript**，无框架、无构建步骤
- **CSS Grid** 构建周期表布局
- **CSS 变量** 实现主题切换与卡片配色
- **3D Transform** + `requestAnimationFrame` 实现倾斜与光泽动画
- **`DeviceOrientationEvent`** 实现移动端重力感应
- **字体：** [Noto Sans SC](https://fonts.google.com/noto/specimen/Noto+Sans+SC)、[Space Mono](https://fonts.google.com/specimen/Space+Mono)
- **图标：** [Font Awesome Free](https://fontawesome.com/)（CC BY 4.0）

---

## 📂 项目结构

```
EzPTable/
├── EzPTable.html       # 全部代码集中于此单文件
├── README.md           # English (default)
├── README.zh-CN.md     # 简体中文
├── README.zh-TW.md     # 繁體中文
├── README.ja.md        # 日本語
├── LICENSE
└── .gitignore
```

---

## 🌐 浏览器兼容性

| 浏览器 | 版本 |
|--------|------|
| Chrome / Edge | 88+ |
| Firefox | 85+ |
| Safari | 14+ |

> 移动端重力感应功能需 HTTPS 环境且用户授权。

---

## 🤝 贡献

欢迎提交 Issue 或 Pull Request！

1. Fork 本仓库
2. 创建特性分支（`git checkout -b feature/amazing-feature`）
3. 提交改动（`git commit -m 'Add some amazing feature'`）
4. 推送分支（`git push origin feature/amazing-feature`）
5. 发起 Pull Request

---

## 📄 许可证

本项目采用 [MIT License](LICENSE) 开源。

---

## ⭐ Star History

如果这个项目对你有帮助，欢迎点个 Star ⭐

---

**Made with ❤️ as a single HTML file.**