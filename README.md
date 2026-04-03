# headache-rapport

頭痛・めまい専門整体院向けのランディングページです。

## ファイル構成

- `index.html`: LP本体
- `assets/achievement-text.svg`: 実績テキスト画像
- `assets/cta-button-placeholder.svg`: CTAボタン画像

## ローカルで確認

このリポジトリ直下で任意の静的サーバーを起動し、`index.html` を表示してください。

例:

```bash
python3 -m http.server 8000
```

ブラウザで `http://localhost:8000` を開きます。

## GitHub Pagesで公開

1. リポジトリの `Settings` を開く
2. `Pages` を選択
3. `Build and deployment` の `Source` を `Deploy from a branch` に設定
4. Branch は `main` / Folder は `/ (root)` を選んで保存
5. 数分後に発行される公開URLへアクセス