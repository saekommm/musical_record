# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...


# Musical Record
## サービス概要
- 観劇したミュージカルを記録するサービス
- ミュージカルに特化したSNSのようなサービス

## メインのターゲットユーザー
- ミュージカル好きの方（特に劇団四季）
- 観劇したミュージカルを記録しておきたい方

## ユーザーが抱える課題
現状、観劇したミュージカルを管理する方法は、パンフレットへの書き込みやキャスト表を写真に残しておくなど、
アナログの方法しかない。

## 解決方法
観劇したミュージカルを簡単に記録しておける。
キャストごとに観劇したミュージカルをまとめておける。

## 実装予定の機能（以下の例は実際のアプリの機能から一部省略しています）
* 一般ユーザー
  - 新規ユーザー登録
  - ユーザーログイン機能
  - ユーザーパスワードリセット機能
  - プロフィール編集機能
  - Twitterログイン機能
  - 観劇したミュージカルの記録機能（感想等も記録可）
  - 観劇したミュージカルの一覧表示
  - キャストごとの観劇済みミュージカルの表示機能
  - 記録のTwitter投稿機能
  - ミュージカルの作成、編集、削除機能

* 管理ユーザー
  - ミュージカル一覧管理機能
  - 管理ユーザーの一覧、詳細、作成、編集、削除

* 実装検討中の機能
  - ユーザーのフォロー機能
  - タイムライン表示機能
  - 記録のいいね、コメント機能

## なぜこのサービスを作りたいのか？
私は、気に入ったミュージカルは何度も繰り返し見にいくくらいミュージカルが大好きです。ミュージカルは見るた
びにキャストが変わることが多く（日替わり、週替わりなど）、観劇したミュージカルを記録して、いつ誰のミュー
ジカルを見たのか、一目でわかるようにしておきたいと常々思っています。
また、ミュージカル好きの知人が、パンフレットに付箋を付けて記録しているということを聞き、同じように記録し
ておきたい方が多くいると感じ、このサービスを作りたいと思いました。

## スケジュール
企画〜技術調査：12/15〆切
README〜ER図作成：12/25 〆切
メイン機能実装：12/25 - 2/15
β版をRUNTEQ内リリース（MVP）:2/28〆切
本番リリース：3月中旬

### 画面遷移図
Figma：https://www.figma.com/file/cpThtYkaAE0GZAmyCyECCG/PF?node-id=0%3A1&t=g3c3xkVXFK74DK6I-1

### ER図
drawio：https://drive.google.com/file/d/1gVvp7Da_T0EFCvaR5F-OtO4vg0vjG72A/view?usp=sharing