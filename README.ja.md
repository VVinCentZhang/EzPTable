# EzPTable

> 単一 HTML ファイルで作られたインタラクティブな周期表 —— ニューモーフィズム + グラスモーフィズム、4 言語対応、温度シミュレーション、3D 元素カード。

[English](README.md) · [简体中文](README.zh-CN.md) · [繁體中文](README.zh-TW.md) · [**日本語**](README.ja.md)

---

## ✨ 機能一覧

| 機能 | 説明 |
|------|------|
| 🧪 **完全な元素データ** | 1〜118 番の全元素を収録。原子量・融点・沸点・電気陰性度・電子配置・密度・発見年などを含む |
| 🌡️ **温度シミュレーション** | スライダー（−273°C → 6000°C）をドラッグすると、各元素の状態（固体 / 液体 / 気体）がリアルタイムで更新 |
| 🎨 **2 つのデザイン** | ニューモーフィズムの影 + グラスモーフィズムの光沢。ライト / ダークテーマをワンクリックで切替 |
| 🌐 **4 言語対応** | 簡体字中国語・繁体字中国語・英語・日本語。UI と元素名が連動して切り替わる |
| 🔍 **検索とフィルター** | 元素名・記号・原子番号で検索。カテゴリ（アルカリ金属、ハロゲンなど）での絞り込みも可能 |
| 🎴 **3D インタラクティブカード** | 元素をクリックすると詳細カードが開き、マウス / タッチ / ジャイロで 3D 傾斜とハイライトが動く |
| ⚛️ **原子構造アニメーション** | 詳細カード内で電子殻を動的に描画。各軌道が独立して回転 |
| 📱 **レスポンシブ対応** | デスクトップ・タブレット・スマホに対応。モバイルではカードサイズが自動縮小 |
| 🚀 **依存ゼロ** | ビルドツール不要、npm パッケージ不要。CDN 経由のフォントとアイコンのみ |

---

## 🖼️ デモ

**Live Demo:** https://VVinCentZhang.github.io/EzPTable/

> ルート URL は自動的に `EzPTable.html` へリダイレクトされます。
> 未設定の場合は **Settings → Pages → Source: `main` ブランチ** で GitHub Pages を有効にしてください。

---

## 🚀 使い方

### 方法 1：オンラインで開く

👉 https://VVinCentZhang.github.io/EzPTable/ にアクセス

### 方法 2：ローカルで実行

1. このリポジトリをダウンロードまたはクローン
2. 任意のモダンブラウザで `EzPTable.html` を開く
3. 完了 ✅

```bash
git clone https://github.com/VVinCentZhang/EzPTable.git
cd EzPTable
open EzPTable.html          # macOS
# または: start EzPTable.html  (Windows)
# または: xdg-open EzPTable.html  (Linux)
```

---

## 🕹️ 操作方法

- **言語切替** —— 上部の「简 / 繁 / EN / 日」ボタンをクリック
- **テーマ切替** —— 右上の 🌙 / ☀️ アイコンをクリック
- **温度調整** —— 温度スライダーをドラッグ、または「−273°C」「室温」「リセット」ボタンを使用
- **状態で着色** —— 温度パネル右側のスイッチをオンにすると、カードの色が状態に応じて変化
- **元素検索** —— 検索ボックスに元素名・記号・原子番号を入力
- **カテゴリで絞り込み** —— カテゴリタグ（例：「ハロゲン」）をクリック、再度クリックで解除
- **詳細表示** —— 任意の元素カードをクリックすると、原子アニメーション付きの詳細パネルが開く

---

## 🧰 技術スタック

- 純粋な **HTML + CSS + JavaScript**、フレームワーク不使用、ビルド不要
- **CSS Grid** による周期表レイアウト
- **CSS 変数** によるテーマ切替とカード配色
- **3D Transform** + `requestAnimationFrame` による傾斜・光沢アニメーション
- **`DeviceOrientationEvent`** によるモバイルジャイロ対応
- **フォント：** [Noto Sans SC](https://fonts.google.com/noto/specimen/Noto+Sans+SC)、[Space Mono](https://fonts.google.com/specimen/Space+Mono)
- **アイコン：** [Font Awesome Free](https://fontawesome.com/)（CC BY 4.0）

---

## 📂 プロジェクト構成

```
EzPTable/
├── EzPTable.html       # メインアプリ —— 周期表
├── index.html          # リダイレクトページ → EzPTable.html
├── README.md           # English (default)
├── README.zh-CN.md     # 简体中文
├── README.zh-TW.md     # 繁體中文
├── README.ja.md        # 日本語
├── LICENSE
└── .gitignore
```

---

## 🌐 ブラウザ互換性

| ブラウザ | バージョン |
|----------|-----------|
| Chrome / Edge | 88+ |
| Firefox | 85+ |
| Safari | 14+ |

> モバイルのジャイロ機能は HTTPS 環境とユーザー許可が必要です。

---

## 🤝 コントリビュート

Issue や Pull Request をお待ちしています！

1. リポジトリを Fork
2. フィーチャーブランチを作成（`git checkout -b feature/amazing-feature`）
3. 変更をコミット（`git commit -m 'Add some amazing feature'`）
4. ブランチへプッシュ（`git push origin feature/amazing-feature`）
5. Pull Request を作成

---

## 📄 ライセンス

本プロジェクトは [MIT License](LICENSE) の下で公開されています。

---

## ⭐ Star History

このプロジェクトが役に立ったら、ぜひ Star をお願いします ⭐

---

**Made with ❤️ as a single HTML file.**