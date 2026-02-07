# Hello Antigravity 🐾

OpenClawのAntigravityモデルが生成したデモWebサイトです。サイバーパンク風のビジュアルと、AIを活用した自己進化型インターフェースを特徴としています。

## 🌐 デモ

GitHub Pagesでホスティングされています:  
👉 **https://mokuda-sx.github.io/hello-antigravity/**

## 📁 ファイル構成

```
hello-antigravity/
├── index.html       # メインページ（Hello World + 名言表示）
├── multiverse.html  # 自己進化型インターフェース（AI統合）
├── bg.png           # 静的背景画像
├── bg_anim.webp     # アニメーション付き背景（サイバーパンク風）
└── README.md        # このファイル
```

## 🔧 各ファイルの役割

### `index.html`
- **概要**: ランディングページ
- **機能**:
  - 「Hello World from OpenClaw Antigravity」のグラデーションタイトル
  - ネオンスタイルの「Click Me」ボタン
  - クリックでランダムなプログラマー名言を日本語で表示
  - Self-Evolving Interfaceへのリンク
- **デザイン**: グラスモーフィズム、フローティングアニメーション、ネオングロー効果

### `multiverse.html`
- **概要**: AIが自己進化するインターフェースのデモ
- **機能**:
  - OpenAI APIを使用した自律的UI生成
  - ニューラルネットワーク風のビジュアライゼーション
  - マルチユニバース（並列世界）のシミュレーション
  - リアルタイム思考ログ表示
- **特徴**: APIキーはlocalStorageに保存（セキュア）

### `bg.png` / `bg_anim.webp`
- ComfyUIで生成されたサイバーパンク風の背景画像
- `bg_anim.webp`: アニメーション付きWebP形式

## 🛠 技術スタック

- **HTML5** - セマンティックマークアップ
- **CSS3** - カスタムプロパティ、アニメーション、グラスモーフィズム
- **JavaScript (Vanilla)** - DOM操作、イベント処理
- **OpenAI API** - 自己進化型インターフェースで使用（オプション）
- **ComfyUI** - 背景画像生成

## 🚀 使い方

### ローカルで実行

```bash
# リポジトリをクローン
git clone https://github.com/mokuda-sx/hello-antigravity.git
cd hello-antigravity

# 任意のHTTPサーバーで起動
python -m http.server 8000
# または
npx serve .
```

ブラウザで `http://localhost:8000` にアクセス。

### Self-Evolving Interfaceを使う

1. `index.html`の「🧠 Self-Evolving Interface」ボタンをクリック
2. OpenAI APIキーを入力（localStorageに保存されます）
3. 「START」ボタンでAIによる自己進化を開始

## ✨ 特徴

- 🎨 **サイバーパンク美学** - ネオングロー、ダークテーマ
- 🤖 **AI統合** - OpenAI APIによる動的UI生成
- 📱 **レスポンシブ** - モバイル対応
- ⚡ **軽量** - フレームワーク不使用、純粋なHTML/CSS/JS

## 📜 ライセンス

MIT License

---

*Built with 🐾 by OpenClaw Antigravity*
