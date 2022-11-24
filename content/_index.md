+++
title = "Spotify Stats"
outputs = ["Reveal"]
+++

<style type="text/css">
  .reveal h1,
  .reveal h2,
  .reveal h3,
  .reveal h4,
  .reveal h5,
  .reveal h6 {
    text-transform: none;
  }
  .reveal {
    font-size: 2em;
  }
</style>

# Spotify Stats
### Team Ras

---
## 概要
<img src='stats.png' width="30%">

---

## 制作の経緯

<img src='books.png' width="40%">

---

<img src='books2.png' width="40%">

---

## 取得できるデータ(一部)
- 最も聴いている曲のランキング
- 最も聴いているアーティストのランキング
- 最も聴いているジャンルのランキング
- ランキング上位曲の平均BPM
- ランキング上位曲のキーの最頻値
- 曲が持つユーザー属性
- 上記データとトップチャートのデータを比較
---

## 使用技術
- JavaScript
- Next.js
- NextAuth.js
- Vercel
- Firebase(Firestore)
- Spotify Web API
- Tailwind CSS

---

## 苦労した点と現状の問題
- 当初はPHP/Laravel+VPSで開発していたが，ホスティングサービスであるVercel+Next.jsのエコシステムが魅力的だったので言語をJSに変更した
- アルバムなど画像の多いサイトになるので，高度な画像の最適化を行ってくれる点でもNext.jsを使いたかった
- Next.jsの学習コストが想定していたより高く，機能を実現するまでに時間がかかった
- JSからDBを使用するベストプラクティスがわからなかったため，バックエンドの開発が遅れた
- APIをパブリックで利用するためには**完成したサイト**が必要で，ユーザーはまだ利用できない

--- 

ご清聴ありがとうございました.
