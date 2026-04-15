# REPLAY — リプレイ（再生）

アニメ作品「REPLAY」のコンセプトティザーサイトです。

## 概要

> 近未来。人は「記録」を売ることができるようになった。
> 思い出、夢、家族、才能——すべてはデータとして保存され、誰かが買うことができる。
> これは、失われた記憶と、それを受け取った人たちの、音楽でつながる"再生"の物語。

## ファイル構成

```
replay/
├── index.html        ← メインページ
├── assets/
│   ├── mirco.jpg     ← 主人公キャラクター画像
│   └── theme.mp3     ← テーマソング
└── README.md
```

## 使い方

### ローカルで開く
```bash
# そのままブラウザで開くだけでOK
open index.html
```

> ⚠️ 音楽はブラウザのセキュリティ制限で、ローカルでは自動再生されない場合があります。
> その場合は `▶` ボタンを押すか、下記のローカルサーバーを使ってください。

```bash
# Python でローカルサーバーを立てる場合
python3 -m http.server 8080
# → http://localhost:8080 を開く
```

### GitHub Pages で公開する
1. このリポジトリを GitHub にプッシュ
2. Settings → Pages → Source: `main` ブランチ / `/ (root)` を選択
3. 数分後に `https://<username>.github.io/<repo>/` で公開されます

## 技術スタック

- HTML / CSS / JavaScript（フレームワークなし）
- Web Audio API（リアルタイム音声ビジュアライザー）
- Canvas API（パーティクル背景）
- Google Fonts（Cormorant Garamond / Shippori Mincho / Noto Serif JP）

## ストーリー

| シーン | 内容 |
|--------|------|
| Opening | タイトル・世界観の提示 |
| World | 記録市場の社会描写 |
| mirco | 主人公キャラクター紹介 |
| Daily Life | 空っぽの日常ルーティン |
| Guitar | ギターで涙が流れる転機 |
| Discovery | 3人がmircoを探していることの発覚 |
| Encounter | 3人との出会い・それぞれのセリフ |
| Resolution | mircoの決意の言葉 |
| Finale | フィナーレ・再生のメッセージ |
