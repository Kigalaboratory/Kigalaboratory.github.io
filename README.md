# README.md
# スーパーすごいプロジェクト Wiki

このリポジトリは、プロジェクトのWikiサイトのソースコードを含んでいます。

## 📁 ディレクトリ構造

```
├── index.html              # メインページ
├── pages/                  # 各Wikiページ
├── assets/                 # 静的リソース
│   ├── css/               # スタイルシート
│   ├── js/                # JavaScript
│   └── images/            # 画像
├── data/                  # 設定データ
└── _config.yml            # GitHub Pages設定
```

## 🚀 ローカル開発

```bash
# リポジトリをクローン
git clone https://github.com/YOUR_USERNAME/YOUR_REPOSITORY.git
cd YOUR_REPOSITORY

# ローカルサーバーを起動
python -m http.server 8000
# または
npx http-server
```

## 🌐 GitHub Pages

このサイトはGitHub Pagesでホストされています：
https://YOUR_USERNAME.github.io/YOUR_REPOSITORY

## 📝 ページの追加

新しいページを追加するには：

1. `pages/` フォルダに新しいHTMLファイルを作成
2. `data/navigation.json` にナビゲーションエントリを追加
3. 変更をコミット・プッシュ

## 🎨 カスタマイズ

- CSS: `assets/css/main.css`
- JavaScript: `assets/js/main.js`
- 設定: `data/config.json`
- ナビゲーション: `data/navigation.json`

## 📄 ライセンス

このプロジェクトは MIT ライセンスの下で公開されています。