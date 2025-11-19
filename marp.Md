---
title: 散らかリアル — 資料まとめ
author: あなた
marp: true
slide: true
paginate: true
theme: default
style: |
  section.slide footer {
    text-align: right;
    font-size: 1.2em;
    color: #666;
    font-weight: bold;
    padding-right: 40px;
    padding-bottom: 20px;
  }
  section.demo-slide {
    text-align: center;
    display: flex !important;
    justify-content: center;
    align-items: center;
  }
  section.demo-slide h1 {
    font-size: 3em !important;
  }
  section.center-middle {
    display: flex !important;
    flex-direction: column;
    justify-content: center;
    text-align: center;
  }

---

# 散らかリアル

## チームこってり地獄会

---

# 散らかリアルの背景
現在の主要な情報源であるYouTubeなどの動画コンテンツは、「動画映え」を優先した非現実的で生活感の薄い部屋の事例が多くを占めています。

このため、ユーザーが最も必要としている以下の情報が不足しており、実際の掃除や模様替えの参考になりにくいという課題が発生しています。

---
# というと...？
- リアルなビフォー（散らかった状態） : 実際に生活している人々の「散らかった状態」の悩みや課題が共有されていない。

- 生活に根ざした改善アイデア : 理想的なインテリアではなく、「狭い部屋での収納術」「ズボラでも続く片付け習慣」など、現実的な生活環境で実践できる実用的なアイデアが少ない。

---

# どういう話が出たか

<div style="display: grid; grid-template-columns: 1fr 1.2fr; gap: 30px; align-items: center; text-align: left;">

<div style="text-align: center;">
</div>

<div style="font-size: 0.8em;">

**① "自分の部屋"に当てはまらない**
* 「YouTubeでみても自分の部屋のフォーマットに合わない」
* 「収納グッズを買ってもイメージと違う」

**② 悩みを"言葉"にできない**
* 「レイアウトで困っていることを言語化できない」
* 「だから検索できず、とりあえず押し入れにしちゃう」

**③ "見られない"からこそ、、、**
* 「部屋に人が入ってこないなら『これで良くね精神』が出てしまう」
* 「場所を決めていても、しまうのがめんどくさい」

</div>
</div>

<div style="margin-top: 30px; text-align: center; font-weight: bold;">

---

## 綺麗な「理想」ではなく、この「現実」を共有する場が必要

---
# 想定基本機能
- 画像投稿
- プロフィール編集
- コミュニティ機能
  - 5段階のスター評価システム（★4.2など）
  - コメント機能
  - 「プロフィールを編集」

---

# 現在の基本機能
- googleログイン
- プロフィール機能 ニックネーム、自己紹介、アイコン
- 汚部屋投稿機能

の3つを実装しています。

---

# デモ

---

# 技術スタック
## - Frontend
- React (TypeScript)

## - Backend
- Spring Boot (Kotlin)

## - DB / Infra
- PostgreSQL
- Docker

---
# ご清聴ありがとうございました