# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version
    ruby 2.3.1p112 (2016-04-26 revision 54768) [x86_64-darwin16]
* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

## モデル設計
- Author
  - gem deviseを使って作る
  - 外部からユーザー登録は出来ないようにする

- Post
  - ブログ記事
  - Authorモデルが管理画面にログインすることによって投稿可能になる
  - マークダウン記法を使って作成できるようにしたい
  - 画像も投稿できるできるようにする
  - ソースコードも投稿できるようにする

- Comment
  - 未ログインユーザーでも投稿できるようにする
  - ハンドルネームとメールアドレスも同時に登録可能
  - ログインユーザーは自動的に自分のユーザー名で投稿することができる
