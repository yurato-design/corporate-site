# 株式会社Sens｜コーポレートサイト（デモ）

架空企業「株式会社Sens」のコーポレートサイトを想定して制作したデモサイトです。  
企業ロゴ、レイアウト設計、HTML/CSSコーディング、OGP設定、レスポンシブ対応、GitHub Pages公開まで一貫して制作したポートフォリオ用プロジェクトです。  
実務的な企業サイトの構成を踏まえ、シンプルで信頼感のあるデザインを意識しています。

---

## 🔗 Repository  
https://github.com/yurato-design/corporate-site

## 🌐 Demo  
https://yurato-design.github.io/corporate-site/

---

## 📸 サイト概要  
本サイトは企業サイトの基本構成を踏まえ、以下の4ページで構成されています。

- **TOP（index.html）**  
  企業紹介、サービス紹介、ニュース、会社概要への導線を配置。

- **ニュース一覧（news.html）**  
  最新情報を掲載するリストページ。

- **会社概要（company.html）**  
  企業情報（所在地・代表者・事業内容など）を掲載。

- **404ページ（404.html）**  
  存在しないページにアクセスした際のエラーページ。

---

## 🛠 使用技術

### Frontend  
- HTML5  
- CSS3（Flexbox / メディアクエリ）  
- Google Fonts（Noto Sans JP / Catamaran）  
- レスポンシブデザイン（スマホ対応）  
- OGP設定（SNSシェア最適化）

### Assets  
- 企業ロゴ  
- サービス紹介画像  
- OGP画像（1200×630px）  
- favicon（SVG）

---

## 📁 ディレクトリ構成
```
corporate-site/
├── index.html
├── news.html
├── company.html
├── 404.html
├── robots.txt
├── sitemap.xml
├── css/
│   ├── reset.css
│   └── style.css
└── images/
    ├── logo.png
    ├── cover_read.png
    ├── service_01.jpg
    ├── service_02.jpg
    ├── service_03.jpg
    ├── footer_logo.png
    └── favicon.svg
```

---

## 🎨 デザインのポイント

- **信頼感のあるシンプルな構成**  
  企業サイトとして必要な情報を整理し、視認性を重視したデザイン。

- **3カラムのサービス紹介**  
  企業の事業内容をわかりやすく伝えるためのレイアウト。

- **スマホ最適化**  
  レスポンシブ対応で、スマホでも読みやすい構成に調整。

- **統一されたヘッダー／フッター**  
  全ページで共通化し、企業サイトとしての一貫性を確保。

---

## 🔍 SEO / 運用設定

### robots.txt
```
User-agent: *
Allow: /

Sitemap: https://yurato-design.github.io/corporate-site/sitemap.xml
```

### sitemap.xml
```
<?xml version="1.0" encoding="UTF-8"?>
<urlset xmlns="http://www.sitemaps.org/schemas/sitemap/0.9">

  <url>
    <loc>https://yurato-design.github.io/corporate-site/index.html</loc>
    <priority>1.0</priority>
  </url>

  <url>
    <loc>https://yurato-design.github.io/corporate-site/news.html</loc>
  </url>

  <url>
    <loc>https://yurato-design.github.io/corporate-site/company.html</loc>
  </url>

  <url>
    <loc>https://yurato-design.github.io/corporate-site/404.html</loc>
  </url>

</urlset>
```

---

## 🔧 今後の改善案（任意）

- ニュース詳細ページの追加  
- サービス紹介ページの追加  
- アニメーションやスクロール演出  
- CMS（microCMS / Contentful）との連携  
- 多言語対応（日本語 / 英語）

---

## 📜 ライセンス  
本プロジェクトは個人制作のポートフォリオ用です。  
画像素材の無断転載はご遠慮ください。