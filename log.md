# 100 Days Of Code - Log

### Day 1: 2021/1/4, 月曜日

**Today's Progress**: 
<blockquote class="twitter-tweet"><p lang="ja" dir="ltr"><a href="https://twitter.com/hashtag/100DaysOfCode?src=hash&amp;ref_src=twsrc%5Etfw">#100DaysOfCode</a>　一日目<br>自分のブログとか進捗とか載せるためのサービスを知りたい技術と合わせてcakeとvueでspaつくることにした。<br>RESTAPIとcake+vueの記事読みあさったところで初日は終了。</p>&mdash; Diwamoto (@Diwamoto_) <a href="https://twitter.com/Diwamoto_/status/1345723746858852353?ref_src=twsrc%5Etfw">January 3, 2021</a></blockquote>

**Thoughts**:
今まではcakePHPのviewでフロントを作っていて今回vueでspaを作ろうと思ったのでまずは勉強しようと思って一日目を記事読み漁りに使った。
一応サービス名だけ決めてレポジトリは作った。明日はとりあえずvueで環境構築してそれにcakeを混ぜるところまでが目標。
laravelとvueのspaは記事いっぱいあるけどcakeとvueはなかなか記事がなく苦戦しそう。
ucmitsのためにもcake4とvueを覚えるのは力にしかならないので頑張る
目標は20日で作る


**Link(s) to work**
1. [cakephpでのREST API](https://book.cakephp.org/3/ja/development/rest.html)
2. [0からRESTAPIについて調べてみた](https://qiita.com/masato44gm/items/dffb8281536ad321fb08#:~:text=RESTful%20API(REST%20API)%E3%81%A8,%E3%81%AB%E5%BE%93%E3%81%A3%E3%81%A6%E7%AD%96%E5%AE%9A%E3%81%95%E3%82%8C%E3%81%9F%E3%82%82%E3%81%AE%E3%80%82)
3. [axios を利用した API の使用](https://jp.vuejs.org/v2/cookbook/using-axios-to-consume-apis.html)
4. [CakePHPにVue.jsを導入したい](https://qiita.com/nagimaruxxx/items/1f2a866b833446892f9e)
5. [【Vue.js】爆速でSPAを作る](https://qiita.com/nagimaruxxx/items/8fc59a5ca05bb91bfe1f)

### Day 2: 2021/1/5, 火曜日

**Today's Progress**: 
<blockquote class="twitter-tweet"><p lang="ja" dir="ltr"><a href="https://twitter.com/hashtag/100DaysOfCode?src=hash&amp;ref_src=twsrc%5Etfw">#100DaysOfCode</a> 2日目<br>一昨日はできなかったのでとりあえず今日は一時間超えてもvueが動くところまでやった。<br>結果としてはnodeのインストールに苦戦しただけでvueが動いてspaとして機能するところまでは出来上がった。<br>今日はcakeでプロジェクト作ってモデルのCRUD作るところまでやる。</p>&mdash; Diwamoto (@Diwamoto_) <a href="https://twitter.com/Diwamoto_/status/1346701699751112705?ref_src=twsrc%5Etfw">January 6, 2021</a></blockquote>

**Thoughts**:
vueのSPAを動かすところまでできた。nodeのバージョンが結構頻繁にアップデートされてるせいかわからなかったけど最新版のnodeでは
vue-cliが動かなかったので動くバージョン探しに手間取った。とりあえず記事のバージョンに合わせることで一応は動いた。
SPAはどんなものかは大体わかったので次はcakeでモデルとAPI作って、vueでCRUDできるところまで頑張る。目標は一機能ごとに二日。

**Link(s) to work**
1. [【Vue.js】爆速でSPAを作る](https://qiita.com/nagimaruxxx/items/8fc59a5ca05bb91bfe1f)

### Day 3: 2021/1/6, 水曜日

**Today's Progress**: 
<blockquote class="twitter-tweet"><p lang="ja" dir="ltr"><a href="https://twitter.com/hashtag/100DaysOfCode?src=hash&amp;ref_src=twsrc%5Etfw">#100DaysOfCode</a> 3日目<br>cakeを動かして、ローカル開発環境を整えるところまでやった。<br>その後swaggerでAPIドキュメント書こうと思って思いのほか基本がわかってなかったので再び記事漁りタイム。<br>cakeでAPI組むだけなら簡単なんだけど今後の成長の為にも勉強しないと</p>&mdash; Diwamoto (@Diwamoto_) <a href="https://twitter.com/Diwamoto_/status/1347010399586062336?ref_src=twsrc%5Etfw">January 7, 2021</a></blockquote>

**Thoughts**:
cakeの環境構築までは簡単にできたが、swaggerに苦戦。
とりあえずswaggerわからん状態ではつくれないのでいったん基本構文を学びながらswaggerをちゃんとかけるようになる。
フォルダ分けはbackendフォルダにcake入れて、index.phpからパス通すようにした。
frontに関してはnpm run devやる感じ
とりあえずユーザテーブル作る。


**Link(s) to work**
[Composerを使ってCakePHP環境を楽々構築！(Windows) - Qiita](https://qiita.com/mikoski01/items/db584b40ddea4a56a58f)
[インストール - 4.x](https://book.cakephp.org/4/ja/installation.html)
[CakePHP4 で Swagger3 を使って API ドキュメントを作る - Qiita](https://qiita.com/katsuhiko/items/22511d5ed5eff3e4616a)
[OpenAPI (Swagger) 超入門 - Qiita](https://qiita.com/teinen_qiita/items/e440ca7b1b52ec918f1b)
[SwaggerでRESTful APIの管理を楽にする - Qiita](https://qiita.com/disc99/items/37228f5d687ad2969aa2)
[Swaggerの記法まとめ - Qiita](https://qiita.com/rllllho/items/53a0023b32f4c0f8eabb)
[swagger editor](https://editor.swagger.io/)

### Day 4: 2021/1/7, 木曜日

**Today's Progress**: 
<blockquote class="twitter-tweet"><p lang="ja" dir="ltr"><a href="https://twitter.com/hashtag/100DaysOfCode?src=hash&amp;ref_src=twsrc%5Etfw">#100DaysOfCode</a> 4日目<br>cakeでテーブルつくって、apiを作るのにrest APIを勉強するのに時間を使った。<br>今までは単純にコントローラーでアクセス制御する感じのやつしか作ったことなかったから、httpのステータスコードとメソッドで切替する感じのやつが結構むずい。<br>PUTメソッドとか聞いたことないーー</p>&mdash; Diwamoto (@Diwamoto_) <a href="https://twitter.com/Diwamoto_/status/1347186076851400704?ref_src=twsrc%5Etfw">January 7, 2021</a></blockquote>

**Thoughts**:
apiを作るために勉強することが多すぎる。デザインにも時間を割かなければいけないのに、まだまだ足りていない。
ただ、REST APIを学ぶこと自体はとても面白い。バックエンドとはかくあるべき。みたいな感じ
明日はいったん進捗を止めて、paizaの問題を解くことと本を読むことにする。



**Link(s) to work**
[PUT か POST か PATCH か？ - Qiita](https://qiita.com/suin/items/d17bdfc8dba086d36115)
[REST入門 基礎知識 - Qiita](https://qiita.com/TakahiRoyte/items/949f4e88caecb02119aa)
[RESTful APIのHTTPステータスコード設計 - Qiita](https://qiita.com/NagaokaKenichi/items/eb85b5fbb719d60c6627)
[bakeコマンド - Qiita](https://qiita.com/geechlife/items/4f7d19bd60b797ebb087)
[REST - 3.9](https://book.cakephp.org/3/ja/development/rest.html)
[一番分かりやすい OAuth の説明 - Qiita](https://qiita.com/TakahikoKawasaki/items/e37caf50776e00e733be)

### Day5~9: 2021/1/7 ~ 2021/1/11, 金〜月

**Today's Progress**: 
go言語をかけるようになるためにpaizaでB〜D問を何問か解いた。

**Thoughts**:
とりあえず以前はPHPで書いていたのを全部go言語に移行した。
B問を解いて見た感じでは今のところPHP→goになって不便に思うところはない。
今後WEB系のコードを書く時に実感するんだろうか。。。
とりあえず、コードを書く時に必要だった記事をいかにまとめる

**Link(s) to work**
[Go 言語で標準入力から読み込む競技プログラミングのアレ — 改訂第二版 - Qiita](https://qiita.com/tnoda_/items/b503a72eac82862d30c6)
[golang　文字列→数値、数値→文字列変換 - Qiita](https://qiita.com/quicksort/items/c9522793a941edf074fd)
[Go の命名規則 | micnncim](https://micnncim.com/posts/ja/go-naming-convention)
[Go言語における文字列の「長さ」と「文字数」を取得する処理の違い - Qiita](https://qiita.com/jeijeijei777/items/ab118cbcba246a5df6a5)
[Go言語 for文のサンプル(break/continue) | ITSakura](https://itsakura.com/go-for)
[Go | シングルクオートでは文字列を定義できない - Qiita](https://qiita.com/YumaInaura/items/7538a4f5b9790ae64d56)
[Go言語 if文のサンプル | ITSakura](https://itsakura.com/golang-if)
[Go言語 文字列の一部を取得する(スライス) | ITSakura](https://itsakura.com/golang-slice)
[QuoteとUnquote #golang - tenntenn.dev](https://tenntenn.dev/ja/posts/quote/)
[【Go】基本文法④(配列・スライス) - Qiita](https://qiita.com/k-penguin-sato/items/daad9986d6c42bdcde90)
[golangを基礎から学ぶ　関数編 - Qiita](https://qiita.com/high5/items/4e2580241039c950e1c4)
[Go言語: スライス(配列)の要素を取り出す方法 - Qiita](https://qiita.com/suin/items/0b2a815c815e23468adc)
[GoのSliceをSortする(sort.Sliceとsort.SliceStable) - Qiita](https://qiita.com/Sekky0905/items/2d5ccd6d076106e9d21c)
[Go言語 switch文のサンプル | ITSakura](https://itsakura.com/go-switch)
[【Go入門】Goの基本型 – 論理値型（Boolean types）](https://code-graffiti.com/boolean-types-in-golang/)

### Day 10: 2021/1/12, 火曜日

**Today's Progress**: 
<blockquote class="twitter-tweet"><p lang="ja" dir="ltr"><a href="https://twitter.com/hashtag/100DaysOfCode?src=hash&amp;ref_src=twsrc%5Etfw">#100DaysOfCode</a> 10日目<br>cakePHPで作っていたバックエンドの環境をginで作り直すために環境を整えた。今まではlamp環境で共通の環境を使っていたけど、goで環境を作ろうとすると、全部のコードをビルドしようとしているのか、起動すらおぼつかなかったのでやめた。とりあえず環境作ったところまで。</p>&mdash; Diwamoto (@Diwamoto_) <a href="https://twitter.com/Diwamoto_/status/1349215564569329667?ref_src=twsrc%5Etfw">January 13, 2021</a></blockquote> 

**Thoughts**:
とりあえずPHP→GOに移行完了。
これからweb系のコード書くのにまたPHPだとうまくいくけど、みたいな場合があると思う。
目標は後10日で完成。。。結構キツそう。
記事も書いた。
[dockerでSPAなgin + vue + mysqlの環境をさくっと作った話](https://zenn.dev/diwamoto/articles/e6e4be8728c2e2)
[ginでginをライブリロードさせる時につまづいたこと](https://zenn.dev/diwamoto/articles/95fd920baff64b)

**Link(s) to work**
[ginでginをライブリロードする - Qiita](https://qiita.com/k0kubun/items/64d177ceb9af07dfb78b)
[go-ginでサクッとRESTAPIを構築する - Qiita](https://qiita.com/shiei_kawa/items/eddf48287455380f618f)
[Docker + Go + Gin の開発環境を準備する - Qiita](https://qiita.com/kkeisuke/items/7cd4d5834386666faab3)
[GitHub - gin-gonic/gin: Gin is a HTTP web framework written in Go (Golang). It features a Martini-like API with much better performance — up to 40 times faster. If you need smashing performance, get yourself some Gin.](https://github.com/gin-gonic/gin)


### Day 11: 2021/1/13, 水曜日 

**Today's Progress**: 
<blockquote class="twitter-tweet"><p lang="ja" dir="ltr"><a href="https://twitter.com/hashtag/100DaysOfCode?src=hash&amp;ref_src=twsrc%5Etfw">#100DaysOfCode</a> 11日目<br>curlでアクセスしたginからgormを使ってdbからデータを引っ張り出して取得する、というAPIの一番基本の部分を一日かけて作り上げた。。。<br>簡単なjoinもできたので、今日は要件に必要なテーブルを全部抜き出してモデル作成するところまで頑張ります</p>&mdash; Diwamoto (@Diwamoto_) <a href="https://twitter.com/Diwamoto_/status/1349554189601370112?ref_src=twsrc%5Etfw">January 14, 2021</a></blockquote> 

**Thoughts**:
とりあえずAPI第一歩ができた。今後は増やすだけじゃなくて認証系もやらないといけないな。。。
つまづいたのはgin.H{}でJsonを渡そうとして、どうがんばっても"がエスケープされてしまうせいでAPIとして機能していなかった点。
そもそもjsonを返すだけであれば、gin.H()を使う必要はなかった。PHPのcomposer管理のプロジェクトだと全てのコードがvendorフォルダに
追加されるので元コードが見易かったけど、ginの思想として、ブラウザとサーバでやりとりされる全てのデータにエスケープを挟むだけで
XSSは防げるという考えがあるようなので、どうがんばっても無理だということだった。


**Link(s) to work**
[dockerでSPAなgin + vue + mysqlの環境をさくっと作った話](https://zenn.dev/diwamoto/articles/e6e4be8728c2e2)
[【はじめてのGO】gin + gormでシンプルなCRUDなREST APIを作成する - Qiita](https://qiita.com/daitasu/items/9428220810816972b5d5)
[Goのtimeパッケージチートシート - Qiita](https://qiita.com/wMETAw/items/2c3120d1338c646ecfba)
[GORMガイド | GORM - The fantastic ORM library for Golang, aims to be developer friendly.](https://gorm.io/ja_JP/docs/index.html)
[Go言語 ORMライブラリ GORMの使い方 | taisablog](https://taisablog.com/archives/1572)

### Day 12: 2021/1/14, 木曜日 

**Today's Progress**: 
<blockquote class="twitter-tweet"><p lang="ja" dir="ltr"><a href="https://twitter.com/hashtag/100DaysOfCode?src=hash&amp;ref_src=twsrc%5Etfw">#100DaysOfCode</a> 12日目<br>フォルダ構造をmvcっぽくして、簡単なテストまで書いた。<br>テストを書くのはめっちゃ簡単だったけど、crudの実装時にステップ実行したくなってデバッグ環境を作ろうと下田ころ、docker on vagrant環境だとリモートデバッグがうまく動かないことを発見して環境入れ替え中。。。</p>&mdash; Diwamoto (@Diwamoto_) <a href="https://twitter.com/Diwamoto_/status/1349971739447488512?ref_src=twsrc%5Etfw">January 15, 2021</a></blockquote>

**Thoughts**:
goのデバッグ環境構築について、本当に苦労した。まずは、ginでライブリロードをおこないつつdlvを使ってデバッグのリッスンをしようとしたのだが、ginはコマンドの引数でポートを指定する為、ginのバイナリに引数を付け足しても意味がないことに気がつき、断念。また、vagrant上のdockerコンテナからリッスンしようとすると、デバッグにどうやらSSHの設定等も必要なのでこちらも断念。
いったんdocker for mac環境に映して再挑戦する。

**Link(s) to work**
[Visual Studio Code - "Remote Development" を使って Docker Container on "Vagrant + VirtualBox" のファイルを編集する - Qiita](https://qiita.com/anfangd/items/63ab95a2005cb2d1f196)
[Docker: ホストからコンテナのIPアドレスを取得したい - Qiita](https://qiita.com/suin/items/50033dc60bfba8553395)
[Docker上のGo製Webアプリケーションをリモートデバッグする - Qiita](https://qiita.com/keitakn/items/f46347f871083356149b)
[Visual Studio CodeでGo言語のデバッグ環境を整える - Qiita](https://qiita.com/momotaro98/items/7fbcad57a9d8488fe999)
[GitHub - golang/vscode-go: Go extension for VS Code](https://github.com/golang/vscode-go)
[Golangのデバッガdelveの使い方 - Qiita](https://qiita.com/minamijoyo/items/4da68467c1c5d94c8cd7)
[Go 言語用デバッガー delve を活用する — Think Abstract](https://amasuda.xyz/post/2020-02-12-golang-delve-tips/)
[Debugging Go using Delve, Docker and VS Code | by Mike Kaperys | Medium](https://medium.com/@kaperys/delve-into-docker-d6c92be2f823)

### Day 13: 2021/1/15, 金曜日

**Today's Progress**: 
<blockquote class="twitter-tweet"><p lang="ja" dir="ltr"><a href="https://twitter.com/hashtag/100DaysOfCode?src=hash&amp;ref_src=twsrc%5Etfw">#100DaysOfCode</a> 13日目<br>docker for mac環境に映してやってみたが、どうやらgin(ライブリロード)とdlvの相性が悪そう。<br>とりあえずやめて、vagrant環境に戻して、crudの実装とテストをちゃんと書くようにした。<br>とりあえずはまだデバッグが必要な状態ではないのでまだおいとく。</p>&mdash; Diwamoto (@Diwamoto_) <a href="https://twitter.com/Diwamoto_/status/1350469005455155200?ref_src=twsrc%5Etfw">January 16, 2021</a></blockquote>

**Thoughts**:
vagrant環境に戻して、CRUDの実装を進めた。デバッグができないので、1関数ごとにきちんとテストを書いて関数の安全性を担保するようにした。
他のモデルに関しても書かないといけないのでとりあえず早くUserモデルのCRUDを作って先に進みたい。

**Link(s) to work**
[Go 言語 testing チートシート - Qiita](https://qiita.com/nirasan/items/b357f0ad9172ab9fa19b)
[はじめてのgo test - Qiita](https://qiita.com/marnie_ms4/items/e51cc6d879cc9ad07af3)
[go-playground/validator リクエストパラメータ向けValidationパターンまとめ - Qiita](https://qiita.com/RunEagler/items/ad79fc860c3689797ccc)
[curlコマンドから HTTP POST する方法 - Qiita](https://qiita.com/letsspeak/items/8c7266742371699ab45e)[curlコマンドから HTTP POST する方法 - Qiita](https://qiita.com/letsspeak/items/8c7266742371699ab45e)

### Day 14: 2021/1/16, 土曜日

**Today's Progress**: 
<blockquote class="twitter-tweet"><p lang="ja" dir="ltr"><a href="https://twitter.com/hashtag/100DaysOfCode?src=hash&amp;ref_src=twsrc%5Etfw">#100DaysOfCode</a> 13日目<br>docker for mac環境に映してやってみたが、どうやらgin(ライブリロード)とdlvの相性が悪そう。<br>とりあえずやめて、vagrant環境に戻して、crudの実装とテストをちゃんと書くようにした。<br>とりあえずはまだデバッグが必要な状態ではないのでまだおいとく。</p>&mdash; Diwamoto (@Diwamoto_) <a href="https://twitter.com/Diwamoto_/status/1350469005455155200?ref_src=twsrc%5Etfw">January 16, 2021</a></blockquote>

**Thoughts**:
vagrant環境に戻して、CRUDの実装を進めた。デバッグができないので、1関数ごとにきちんとテストを書いて関数の安全性を担保するようにした。
他のモデルに関しても書かないといけないのでとりあえず早くUserモデルのCRUDを作って先に進みたい。

**Link(s) to work**
[Go 言語 testing チートシート - Qiita](https://qiita.com/nirasan/items/b357f0ad9172ab9fa19b)
[はじめてのgo test - Qiita](https://qiita.com/marnie_ms4/items/e51cc6d879cc9ad07af3)
[go-playground/validator リクエストパラメータ向けValidationパターンまとめ - Qiita](https://qiita.com/RunEagler/items/ad79fc860c3689797ccc)
[curlコマンドから HTTP POST する方法 - Qiita](https://qiita.com/letsspeak/items/8c7266742371699ab45e)[curlコマンドから HTTP POST する方法 - Qiita](https://qiita.com/letsspeak/items/8c7266742371699ab45e)



