# tane works

ブラウザで楽しめる作品を紹介する静的サイトです。

## 編集

- `index.html`: 作品の順序・リンク・紹介文・デザイン
- `images/`: 作品サムネイル

作品カードは `<a class="card">` 全体を移動・複製して編集します。
画像を書き換えたら、ブラウザを再読み込みして確認してください。

## ローカル確認

このフォルダーで `python -m http.server 8765 --bind 127.0.0.1` を実行し、
http://127.0.0.1:8765/ を開きます。終了は Ctrl+C。
`index.html` を直接開いて確認することもできます。

## 公開・更新

GitHub Pages の公開元は `main` ブランチの `/ (root)` です。
公開先: https://omochi7777.github.io/tanework/

変更したファイルを確認してからコミット・pushするとサイトに反映されます。

```powershell
git status
git add index.html images README.md
git commit -m "Update portfolio"
git push
```

Claudeの作品は、共有設定やログイン状態によって閲覧できない場合があります。
