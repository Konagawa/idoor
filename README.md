# [I Door(アイディア)]

## サービス概要
ランダムワードから生まれたフレーズから、新しいアイディアを連想できるアプリ

## 想定されるユーザー層
アプリ開発、企画考案、トークデッキ（話題）作成等々のアイディア出しに困っている人。

## サービスコンセプト
開け！閃きの扉！   
アイディア出しを行うことは、PF作成時のみならず、多くの方に様々なケースで訪れるもの。   
しかし自分１人の力だけでは、どうしても広い視野を持って考えることが難しくなってしまい、   
大きな関門になることが多いポイントにもなっています。   
このアプリでは自分では思いつかないようなワードから奇跡的に生まれたフレーズと邂逅し、   
閃きの機会を効率的に増やすことができるアプリです。   
又、突飛なフレーズからついクスッと笑ってしまうことができる一種のエンターテイメント性も持ち合わせており、   
考えすぎて煮詰まってしまった時の、気分転換にも利用していただきたいと思います。   

## 使用技術
###  バックエンド
* Ruby3.1.2
* Ruby on Rails 7.0.4
###  フロントエンド
* JavaScript
* Tailwind CSS
###  インフラ
* Heroku

##  想定しているロジック（メイン機能）
トップページから考案したいジャンルを選択する　　　
→画面上の検索ボタンを押す   
→画面上にDBに保存されたワードが3つ出力される   
→表示された３つのワードを１文として、保存するか（ログイン時のみ）、新たにワードを生み出すか選択する   

## 実装を予定している機能
### MVP
* ログイン画面　※未ログインでも機能を制限して使用可能にする
* ジャンル分け作成
* お気に入り機能　※ログイン時のみ
 * ランダム生成された1文をお気に入り登録できる機能
* アイデア記録機能　※ログイン時のみ
 * お気に入りした1文に 思いついたアイディアをメモする機能
* 問い合わせ機能
* 管理者機能

### その後の機能
* googleログイン
* X投稿機能
* UX強化
  * 新規登録するか、未登録のまま操作するかを選択するポップアップを表示させる
  * ジャンルの拡充
  * ワード数の調整　※３ワードだけでなく、増減できるようにする 
  * オリジナルワード登録機能 ※フレーズに必ず加えたいワードを自分で作成できる機能
