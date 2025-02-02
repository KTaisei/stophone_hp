# 技術スタック

このサイトはAstroを中心に構築されており、シンプルかつ高速なウェブ体験を提供するための最新技術を採用しています。以下に、プロジェクトで使用されている主要な技術スタックをまとめます。

---

## フロントエンド

### 1. **Astro**
- フレームワーク: Astroは、コンテンツ優先の静的サイト生成フレームワークです。
- 特徴:
  - 静的ファイル生成による高速表示。
  - 組み込みのMarkdownサポート。
  - コンポーネント駆動型開発のサポート（React, Vue, Svelte, etc.）。

### 2. **Tailwind CSS**
- CSSフレームワーク: ユーティリティファーストのCSSフレームワーク。
- 特徴:
  - クラスベースで簡単にデザインを作成。
  - Tailwind Typographyプラグインを使用して、Markdownコンテンツのスタイリングを最適化。

---

## バックエンド（ビルド時）

### 1. **Node.js**
- 環境: Astroのビルドプロセスや開発サーバーの動作に使用。

### 2. **Markdown**
- コンテンツ: ブログ記事やドキュメントはMarkdown形式で作成。
- 特徴: シンプルな構造とコンテンツ管理のしやすさ。

---

## デプロイ

### 1. **GitHub Pages**
- ホスティングサービス: GitHub Pagesを使用して静的サイトをホスティング。
- 特徴:
  - GitHubリポジトリとの統合。
  - 自動デプロイワークフロー。

### 2. **GitHub Actions**
- CI/CDツール: コードの変更を検出し、ビルドとデプロイを自動化。
- 特徴:
  - プッシュ時の自動ビルド。
  - Astroによる静的ファイル生成とGitHub Pagesへのデプロイ。

---

## プラグイン

### 1. **Tailwind Typography**
- Markdownのデザインを洗練させるためのプラグイン。
- 特徴:
  - 見出し、リスト、リンク、コードブロックなどの一貫したスタイル。

---

## 開発ツール

### 1. **VS Code**
- IDE: コード編集に使用。
- 特徴: 拡張機能によるカスタマイズ性。

### 2. **ESLint & Prettier**
- コード品質ツール: 一貫したコードスタイルを維持。
- 特徴: 自動フォーマットとエラー検出。

---

## デザイン

### 1. **レスポンシブデザイン**
- Tailwind CSSを活用して、スマートフォンやタブレットなどのさまざまなデバイスに対応。

### 2. **シンプルで直感的なUI**
- カードレイアウトや分かりやすいナビゲーションを採用。
- ユーザーが目的の情報にすぐアクセスできる構造。

---

## 特徴的な機能

- Markdownコンテンツを美しく表示するカスタムデザイン。
- 高速なビルドプロセスと静的サイト生成。
- ユーザーの視覚的な体験を向上させるための詳細なCSS設計。

---

## 今後の予定

- コンテンツ管理システム（CMS）の導入。
- 検索機能やフィードバックフォームの実装。
- パフォーマンス最適化のさらなる追求。

---

この技術スタックにより、シンプルかつ効率的な開発を実現し、スケーラブルなウェブサイトを提供しています。
