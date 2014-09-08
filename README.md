プログラミング演習講義メモ
=========================

## 第十八回以降

- グループで課題に着手

## 課題提出について

基本的には各チームのリポジトリを確認します。チュートリアルの実装および試験の担当以外の方々についてはリポジトリの README.md に取組みに関する情報を取り纏めて下さい。これをもって成果物とし、その情報を元に課題の評価としますので、担当者の名前も付けておいてください。

Rails4 のチュートリアルが完了したら Heroku に push しておいてください。URL は README などに記載のこと。

## 第二十五回 4 コマ

## 第二十四回 4 コマ

## 第二十三回 (2014.9.10) 4 コマ

## 第二十二回 (2014.9.8) 4 コマ

## 第二十一回 (2014.9.5) 4 コマ

## 第二十回 (2014.9.3) 3 コマ

## 第十九回 (2014.8.27) 3 コマ

リモートリポジトから clone してテストを実行する方法

    $ git clone <project>
    $ bundle install --without production
    $ bundle exec rake db:migrate
    $ bundle exec rake db:test:prepare
    $ bundle exec rspec spec/

また、ブランチをリモートから取得する方法は以下です。

    $ git fetch orign
    $ git checkout <branch>


## 第十八回 (2014.8.25) 4 コマ

- 役割分担決めてもらいます
- 課題設定してもらいます
- リポジトリを作成してもらいます
- 可能であれば pull request の練習をしてみてください

## リポジトリ

- [提出用リポジトリ](https://github.com/DevelopmentPractice201405/DevelopmentPractice201405/blob/master/ripositories.md)

## チュートリアル提出について

週末 (8.22) までの成果を GitHub に push してください。

## 第十七回 (2014.8.21) 4 コマ

チーム分けについて発信の予定です。

- 1 : アラカキ イマズ シマブクロ クバ

- 2 : サワムラ タバ ヤスムラ ヤマウチ

- 3 : イゲイ オオシロ マタヨシ ムラカミ

- 4 : カネシマ カワミツ カワヒラ シオヒラ チナ

## 第十六回 (2014.8.18) 4 コマ

### 演習問題について

11 章を終えた者は 5 章以降の演習問題に着手願います。例えば 5 章の演習 5.6.1 に着手するとします。まず 5 章の branch が存在するかを確認します。

    $ git branch

filling-in-layout という branch が存在することを確認したらその branch を checkout します。

    $ git checkout filling-in-layout

そしてそこからさらに branch します。

    $ git checkout -b 5-6-1

この branch に実装を盛り込んで動作確認が正常であれば commit を作ります。

    $ git add .
    $ git commit -m '5-6-1'

GitHub に issue を作って pull request してみても良いかもしれません。次の課題に着手する時には一旦元の branch に戻ります。

    $ git checkout filling-in-layout

ここから次の演習の branch を作ります。

    $ git checkout -b 5-6-2

提出については面倒ですが全ての branch を GitHub に push してください。

## 第十五回 (2014.8.15) 3 コマ

課題について

- Rails4 で最初から
- 4、5 人のグループですすめる 
- 2 名で試験と実装
- 他のものはレビュや演習、追加課題、github 操作など
- GitHub の issue とか pull request など積極的に使う
 - push の場面では pull request
 - 不具合発生時の issue tracker の積極利用
- 追加課題
 - 機能追加 (mashup)
 - Docker でインフラ
  - デバッグの方法確認
  - resque で非同期処理 (API 通信)
  - Heroku


## 第十四回 (2014.8.13) 4 コマ

以降については他の先生も入ってすすめているようですので、個別に進捗確認と問題処理をする形ですすめていきます。

## 第十三回 (2014.8.6) 3 コマ

- [第9章 ユーザーの更新・表示・削除](http://railstutorial.jp/chapters/updating-showing-and-deleting-users?version=3.2#top)

## 課題

第十三回実施時点で [第8章 サインイン、サインアウト](http://railstutorial.jp/chapters/sign-in-sign-out?version=3.2#top) を完了させた状態にしておくこと。評価対象の課題とし、済ませていないものについては「不可」の評価とします。

また、質問などは [issue](https://github.com/DevelopmentPractice201405/DevelopmentPractice201405/issues) を使ってやりとりが可能ですので、積極的に使っていって下さい。よろしくお願いします。

## 第十二回 (2014.7.16) 4 コマ

7 章を完了したものは以下に着手してください。

- [第8章 サインイン、サインアウト](http://railstutorial.jp/chapters/sign-in-sign-out?version=3.2#top)

## 第十一回 (2014.7.4) 4 コマ

- [第7章 ユーザー登録](http://railstutorial.jp/chapters/sign-up?version=4.0#top)

## 第十回 (2014.6.27) 4 コマ

- [第6章 ユーザーのモデルを作成する](http://railstutorial.jp/chapters/modeling-users?version=4.0#top)

リポジトリの報告をお願いします。

- ヤマウチさん

## 第九回 (2014.6.25) 4 コマ

- [第5章 レイアウトを作成する](http://railstutorial.jp/chapters/filling-in-the-layout?version=3.2#top)

リポジトリの報告をお願いします。

- ヤマウチさん
- シマブクロさん

## 第八回 (2014.6.18) 4 コマ

- [第四章 Rails風味のRuby](http://railstutorial.jp/chapters/rails-flavored-ruby?version=3.2#top) が継続

リポジトリの登録および報告をお願いします。

## 第七回 (2014.6.9) 4 コマ

- [第三章 ほぼ静的なページの作成](http://railstutorial.jp/chapters/static-pages?version=3.2#top) から着手
- [プログラミング演習のグループ](https://github.com/DevelopmentPractice201405) にリポジトリを作成し、そこに成果物を push して頂きます
  - このリポジトリが成績に直結していると考えてください

## 第六回 (2014.6.6) 4 コマ

- 前提として以下の節を完了していること
  - [1.2](http://railstutorial.jp/chapters/beginning?version=3.2#sec-the_first_application)
  - [1.3](http://railstutorial.jp/chapters/beginning?version=3.2#sec-version_control)
- [Heroku](http://www.heroku.com) のアカウント取得しておいてください
  - ssh 鍵の登録も必要です
  - [heroku toolbelt](http://toolbelt.heroku.com) の導入も必要です

以下のコマンド入力が必要と思われます。

        $ wget https://toolbelt.heroku.com/install-ubuntu.sh
        $ bash install-ubuntu.sh

- [1.4 デプロイする](http://railstutorial.jp/chapters/beginning?version=3.2#sec-deploying) から開始
- [第二章 デモアプリケーション](http://railstutorial.jp/chapters/a-demo-app?version=3.2#top) 終了


## 第五回 (2014.5.28) 3 コマ

- [RailsTutorial](http://railstutorial.jp) 着手
  - 対象となる Rails のバージョンは 3.2 としていますので注意して下さい
  - 実質 [ここ](http://railstutorial.jp/chapters/beginning?version=3.2#sec-the_first_application) からとなる予定。
  - [1.2](http://railstutorial.jp/chapters/beginning?version=3.2#sec-the_first_application)
  - [1.3](http://railstutorial.jp/chapters/beginning?version=3.2#sec-version_control)

## 第四回 (2014.5.22) 4 コマ

- vimtutor 演習
- Git および Github 演習
  - [Git Handson](https://github.com/yamanetoshi/Git-Handson/blob/master/tutorial.md)
  - [Git でやり直す方法](https://github.com/yamanetoshi/Git-Handson/blob/master/retry.md)

- ssh 鍵の作成と GitHub への登録など

## 第三回 (2014.5.14) 3 コマ

- Bourne Shell 自習テキストに関する課題発表
  - [発表メモ](./20140514.md) 
- rvm, ruby, rails 導入
  - [開発環境設定資料](https://github.com/DevelopmentPractice201308/material/blob/master/installation.md)
  - http://blog.opensquare.jp/?p=1667
  - http://blog.sudobits.com/2012/05/02/how-to-install-ruby-on-rails-in-ubuntu-12-04-lts/

## 第二回 (2014.5.12) 3 コマ

- Bourne Shell 自習テキスト
  - https://github.com/yamanetoshi/BashSelfStudyText

上記資料は何度も目を通してみて下さい。

## 第一回 (2014.5.8) 2 コマ

- virtualbox 導入
- Ubuntu 13.04 導入
- sublime text 2 の導入
  - http://blog.lindwurm.biz/2013/04/how-to-install-sublime.html
- 次回、Bourne Shell 自習テキストから再開

