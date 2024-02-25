# プロダクト名 551ゲーム
<!-- プロダクト名に変更してください -->


<!-- プロダクト名・イメージ画像を差し変えてください -->


## チーム名
チームF あんしば
<!-- チームIDとチーム名を入力してください -->


## 背景・課題・解決されること
　テーマ「関西をいい感じに」に対して，関西のこと(食べ物，観光地，文化)をもっと知ってもらわないと考えた．  
　「比叡山の延暦寺」これはどこにあるのか聞かれてもすぐ答えれる人は意外と少ない．にゅう麺の発祥が奈良県である事．これも多くの人は知らないだろう．たくさんの魅力があるのにその魅力を知っている人が少ないということ関西としての大きなマイナスになっていると考えた．  
　このような課題点を私たちはシンプルであり関西に馴染みのある形を取り入れたゲームを通して，解決しようと考えた．  
   
解決すべきは  
**関西の魅力をもっと多くの人に知ってもらう!!**

<!-- テーマ「関西をいい感じに」に対して、考案するプロダクトがどういった(Why)背景から思いついたのか、どのよう(What)な課題があり、どのよう(How)に解決するのかを入力してください -->


## プロダクト説明
551ゲームというオリジナルな2択選択ゲームを作成した．  
551ゲームとはゲームを楽しんでもらうことはもちろんだが，ゲームを通して関西の食べ物や文化などをより知ってもらうことが目的である．

プレイヤーに楽しさややりごたえを提供するために，コレクション機能を多数追加した．  
<!-- 開発したプロダクトの説明を入力してください -->


## 操作説明・デモ動画
[デモ動画はこちら](https://www.youtube.com/watch?v=_FAA15ARmas)
<!-- 開発したプロダクトの操作説明について入力してください。また、操作説明デモ動画があれば、埋め込みやリンクを記載してください -->
アプリインストール後の初回起動はユーザーの名前の入力画面になる．  
二回目以降のアプリ起動はゲームのタイトル画面になる．  

タイトル画面からはゲームのホーム画面へ遷移する．
画面の下にはショップ、図鑑、装飾、説明の画面への遷移ボタンが存在する．  
詳細は後程説明する．  

**ゲームの説明**  
上の左右矢印で出題する問題のジャンル，食べ物や建物などを選択することができる．  
下の左右矢印で正解の問題範囲を選択することができる．  
(例：関西全域を選択すると，関西のものが問題で出題された時は「あるとき～」ボタンをクリックすると正解になる．しかし，大阪を選択すると，大坂のものが問題で出題された時のみ「あるとき～」ボタンをクリックすると正解になる．)

ジャンルと場所が選択できたらスタートボタンを押そう。。
先ほどの選択がジャンル：全て、場所：関西全域だとして説明するね．  
まず問題や10問出題されるよ．  
関西のものが出題されると「あるとき」が正解で「ないときぃ」が不正解  
関西以外のものが出題されると「あるとき」が不正解で「ないときぃ」が正解になる．
  
 

正解，不正解で関西お馴染みのリアクションがでてくるよ．(画面をタップ)  
そのあと問題に出たものの詳細説明が出てくる．  

10問終わると結果が表示される．  
  
結果画面で関西コイン(ゲーム内マネー)とカードが入手できる．  
ゲームの説明以上  

  
**ショップの説明**
  まだ手に入れていないカード，称号，背景を購入できる．
  カードに関しては問題として出たことのあるカードだけを購入できる．
  まだ，ゲーム内で一度も出会ってないもののカードは買えないから，カードを集めるためにたくさん遊んでください．
  値段に関しては独断と偏見でつけているので，気にしないでください．




## 注力したポイント
551ゲームでは2択ゲームが主な機能だが，関西の各地や文化を紹介したカードのコレクションや，関西弁をベースとしたユーザの名前の肩書きを集められ，名前の前につけて遊ぶ機能，関西の各地をモチーフにしたゲーム画面の背景集めなど，様々な要素から関西を知ることで楽しく遊べるようにしたことがポイントである．    
バックエンドでは実用面も考えてデータベースをPaaS上にデプロイしたことで実際にアプリストアに掲載した際に，ユーザごとにデータを分けられることを考慮して制作した．今後アップデートを通して関西のデータを増やしたり，ユーザのランキング，対戦機能を追加するためのテーブルの属性を増やすことも可能である．  
フロントエンドは全体的にポップなデザインにし，所々に関西を表現している部分が実装されている．関西在住の人には馴染み深いデザインにし，関西以外の人には関西の雰囲気をアプリで感じてもらうことで関西を知ってもらえることを期待している．    
UIの観点ではバックで処理している時間をプログレスバーで表示することでユーザがあとどれ位待てばいいかを可視化することや,単純な操作をすることにこだわり,利用者が操作するのに困らないように工夫した.  
ゲーム性では出題するジャンル(食べ物,建物,文化など)毎に分けて出題すること,関西全域かどうかを当てるのではなく,大阪のものか京都のものかなど,各府県のものがどうかをあてるようなゲームモードも実装した.
また，このゲームは問題数を10問としていて，短い時間で楽しむことができ，移動中や待ち時間に遊べることで知らない関西を手軽に感じることが可能である．  
さらに，関西の各部分を紹介したカードにも注目してほしい．各府県をモチーフにしたデザインや文字フォントにし，詳細な説明もクスッと笑ってもらえるように工夫している．
このアプリを通して関西をええ感じにできることを実際に遊んで感じてもらいたい．
  

## 使用技術
**開発環境:** Android Studio

**クライアントサイド**
- フロントエンド: XML
- バックエンド: Java(17.07)

**サーバーサイド**
- 使用言語: Python(3.11.7)
- フレームワーク: Django REST Framework (DRF)(3.13.1)
- データベース: PostgreSQL

**デプロイ**
- PaaS: Render
(デプロイしたAPI(DRFで作成したDB通信用)からデータを取得し，クライアントサイドで使用．)



            

<!--
markdownの記法はこちらを参照してください！
https://docs.github.com/ja/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax
-->
