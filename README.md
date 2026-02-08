# Squid Runner Game

ブラウザで遊べる 1 ファイル構成のランゲームです。

## ローカルで起動

`index.html` をブラウザで開くだけで動きます。

## GitHub Pages で公開（最短）

1. GitHub で新しい公開リポジトリを作成（例: `squid-runner-game`）
2. このフォルダで以下を実行

```bash
git add .
git commit -m "Initial release"
git remote add origin https://github.com/<YOUR_NAME>/squid-runner-game.git
git push -u origin main
```

3. GitHub の `Settings` -> `Pages`
4. `Build and deployment` の `Source` を `Deploy from a branch` に設定
5. `Branch` を `main` / `/ (root)` にして保存

数十秒から数分で公開されます。
公開 URL 例:
`https://<YOUR_NAME>.github.io/squid-runner-game/`

## 公開前チェック

- PC とスマホ両方で操作確認
- 音量バランス（SE/BGM）確認
- Safari で音が鳴るか確認（初回タップ後）
