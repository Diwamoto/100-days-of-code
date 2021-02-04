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

### Day5~8: 2021/1/7 ~ 2021/1/11, 金〜月

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

### Day 9: 2021/1/12, 火曜日

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


### Day 10: 2021/1/13, 水曜日 

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

### Day 11: 2021/1/14, 木曜日 

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

### Day 12: 2021/1/15, 金曜日

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

### Day 13: 2021/1/17, 日曜日

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

### Day 14: 2021/1/18, 月曜日

**Today's Progress**: 
<blockquote class="twitter-tweet"><p lang="ja" dir="ltr"><a href="https://twitter.com/hashtag/100DaysOfCode?src=hash&amp;ref_src=twsrc%5Etfw">#100DaysOfCode</a> 14日目<br>ユーザのCRUDがようやく完成してコミットできた。<br>毎日コードは書いていたのに進捗が生めなかったことが悔しかったが、一回CRUDを作ってしまえば他のモデルにもコピーできる。明日は必要テーブル全部に適用しよう。</p>&mdash; Diwamoto (@Diwamoto_) <a href="https://twitter.com/Diwamoto_/status/1351172263538778119?ref_src=twsrc%5Etfw">January 18, 2021</a></blockquote>

**Thoughts**:
一つAPIが完成した。Oauthはできてないが、とりあえずurlからdbを操作できる状態まで動かした。
Oauthに関しては、どういう認証をすれば良いか考えている。そもそもAPIは外部に公開するつもりはないので、AWSの内部サーバーとして
構築してしまえば認証問題は一度考えなくても良いのではないかと思っている。
とりあえず、バックエンドを早く作って全く触れていないフロントにも取り組みたい。

**Link(s) to work**
[【MySQL】auto_increment（オートインクリメント）の連番状態をリセット（初期化）する - Qiita](https://qiita.com/sola-msr/items/d6c70995ddd95361dda7)
[【Go】基本文法③(ポインタ・構造体) - Qiita](https://qiita.com/k-penguin-sato/items/62dfe0f93f56e4bf9157#%E6%A7%8B%E9%80%A0%E4%BD%93%E3%81%AE%E5%9F%8B%E3%82%81%E8%BE%BC%E3%81%BF)
[Go言語で「embedded で継承ができる」と思わないほうがいいのはなぜか？ - Qiita](https://qiita.com/Maki-Daisuke/items/511b8989e528f7c70f80)
[Golangのローカルのタイムゾーンが決まる仕組みと指定方法 - Qiita](https://qiita.com/imamura_sh/items/a080975c6c7e23498944)
[Go言語のエラーハンドリングについて ～panic編～ - Qiita](https://qiita.com/nayuneko/items/9534858156dfd50b43fb)[Go言語のエラーハンドリングについて ～panic編～ - Qiita](https://qiita.com/nayuneko/items/9534858156dfd50b43fb)

### Day 15: 2021/1/19, 火曜日

**Today's Progress**: 
<blockquote class="twitter-tweet"><p lang="ja" dir="ltr"><a href="https://twitter.com/hashtag/100DaysOfCode?src=hash&amp;ref_src=twsrc%5Etfw">#100DaysOfCode</a> 15日目<br>ユーザのCRUDが完成したので、他のテーブルの処理を共通化する為にいろいろ調べて、interfaceがわからずつまづき。現状は同名・内部変数の方だけ違うCreate()等が乱立してるのでもう少しリファクタリングをする必要がありそう。後TableDrivenTestの思想を得た。明日実装する。</p>&mdash; Diwamoto (@Diwamoto_) <a href="https://twitter.com/Diwamoto_/status/1351552580137074696?ref_src=twsrc%5Etfw">January 19, 2021</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

**Thoughts**:
1つモデルを実装したので、よしこれをコピーしようとしていろいろ調べて、どう考えても`model.GetUser()`だったり`model.GetProfile()`が並ぶのはすごく面倒なので、
{〇〇モデル}.Get()でやるように頑張ろうとして、interfaceの概念が分からず、詰まってしまった。一つの共通モデルを実装して、その取得テーブル名を変更したモデルを作ろうと思ったのだが、go言語は暗黙の方変換をやらないのでうまくいかず。結局Create()等の乱立になってしまった。
明日はTableDrivenTestの実装をやる。

**Link(s) to work**
[初心者に送りたいinterfaceの使い方Golang. # Intro | by Takahito Yamada | Since I want to start “blog” that looks like men do, I do start. | Medium](https://medium.com/since-i-want-to-start-blog-that-looks-like-men-do/%E5%88%9D%E5%BF%83%E8%80%85%E3%81%AB%E9%80%81%E3%82%8A%E3%81%9F%E3%81%84interface%E3%81%AE%E4%BD%BF%E3%81%84%E6%96%B9-golang-48eba361c3b4)
[Goで見かける構造体パターン - Qiita](https://qiita.com/taizo/items/7e47f505ed0d96747ba2)
[Golangでtestingことはじめ（2）〜テストにおける共通処理〜 - DeNA Testing Blog](https://swet.dena.com/entry/2018/01/22/120155)

### Day 16: 2021/1/20, 水曜日

**Today's Progress**: 
<blockquote class="twitter-tweet"><p lang="ja" dir="ltr"><a href="https://twitter.com/hashtag/100DaysOfCode?src=hash&amp;ref_src=twsrc%5Etfw">#100DaysOfCode</a> 16日目<br>ユーザのテストをTableDrivenTestに全て書き換えた。<br>ユーザのリファクタリングがある程度できたので、他のテーブルに書き写そうとしたら、TestMain()が共有できないことに気付き、テスト用のデータベースの初期化に悩まされる。<br>バックエンド完成までもう少し、頑張る。</p>&mdash; Diwamoto (@Diwamoto_) <a href="https://twitter.com/Diwamoto_/status/1352067299528720385?ref_src=twsrc%5Etfw">January 21, 2021</a></blockquote>

**Thoughts**:
Userのテストを全てTableDrivenTestに書き換えた。テストコードが増えたが、今後の管理には役立ちそう。
それはそうと、テストをまわすと毎回データベースコンテナから接続を拒絶する旨の通知がくる。どうにかしないと。


**Link(s) to work**
[go — Go構造体にデフォルト値を設定する方法](https://www.it-swarm-ja.tech/ja/go/go%E6%A7%8B%E9%80%A0%E4%BD%93%E3%81%AB%E3%83%87%E3%83%95%E3%82%A9%E3%83%AB%E3%83%88%E5%80%A4%E3%82%92%E8%A8%AD%E5%AE%9A%E3%81%99%E3%82%8B%E6%96%B9%E6%B3%95/824338261/)
[goのtesting.Mを使った関数がpackage単位のfixtureとして使えるか調べてみる - podhmo’s diary](https://pod.hatenablog.com/entry/2018/03/18/202020)
[Goのスコープについて考えてみよう #golang - Qiita](https://qiita.com/tenntenn/items/ac5940dfbca703183fdf)
[Goのグローバル変数とスコープでハマった話 - Qiita](https://qiita.com/UHNaKZ/items/637cb3e1c538d8e63ee2)

### Day 17: 2021/1/21, 木曜日

**Today's Progress**: 
<blockquote class="twitter-tweet"><p lang="ja" dir="ltr"><a href="https://twitter.com/hashtag/100DaysOfCode?src=hash&amp;ref_src=twsrc%5Etfw">#100DaysOfCode</a> 17日目<br>データベースの接続用の構造体をシングルトン実装に<br>することでデータベースの初期化を何回も起こらないように変更できた。さらにテスト毎にまっさらなデータベースですっきりできるようにした。他のテーブルについても少しづつ実装ができてきた。完成が見えてきた！！！</p>&mdash; Diwamoto (@Diwamoto_) <a href="https://twitter.com/Diwamoto_/status/1352250552470495235?ref_src=twsrc%5Etfw">January 21, 2021</a></blockquote>

**Thoughts**:
前々から少しづつデザインパターンの勉強をしていたのだが、ようやく実際に使える時がきた。
テストの際に使用するデータベースがずっと接続を拒否するメッセージを出していた→テストの際に、一度データベースの接続を閉じる前にもう一度開いてしまっていた
ところがあったため、データベースの接続オブジェクトをシングルトンにして、二回以上接続できないようにすることができた。
さらに、データベースを毎回初期化することでまっさらな状態でテストを行って終わったら全て破棄するといういい状態に持ってくることができた。

**Link(s) to work**
[Golangで、デザインパターン「Singleton」を学ぶ - Qiita](https://qiita.com/ttsubo/items/2498bf77f81b6ed23198)


### Day 18: 2021/1/22, 金曜日

**Today's Progress**: 
<blockquote class="twitter-tweet"><p lang="ja" dir="ltr"><a href="https://twitter.com/hashtag/100DaysOfCode?src=hash&amp;ref_src=twsrc%5Etfw">#100DaysOfCode</a> 18日目<br>モデルのCRUDは完成したのでコードを別モデルに写して処理をちょこっと変えてテストを書いて通してコミットするという動作を4回繰り返して全テーブル実装し終わった！<br>終わったということでとりあえずバックエンドは置いといて、明日からvueでフロントの実装をやる！</p>&mdash; Diwamoto (@Diwamoto_) <a href="https://twitter.com/Diwamoto_/status/1352632435322703873?ref_src=twsrc%5Etfw">January 22, 2021</a></blockquote>

**Thoughts**:
バックエンドの実装が一区切りついた！感想としては、思ったより簡単だった。goの設計が本当にわかりやすく、コンパイラ言語でありながらスクリプト言語の開発速度を持っているというのがよくわかった。
次はこの作ったAPIを使ってフロントを作っていく。こっからだ。。

**Link(s) to work**
[逆引きGolang (正規表現)](https://ashitani.jp/golangtips/tips_regexp.html)
[validator - GoDoc](https://godoc.org/gopkg.in/go-playground/validator.v9)


### Day 19: 2021/1/25, 月曜日

**Today's Progress**: 
<blockquote class="twitter-tweet"><p lang="ja" dir="ltr"><a href="https://twitter.com/hashtag/100DaysOfCode?src=hash&amp;ref_src=twsrc%5Etfw">#100DaysOfCode</a> 19日目<br>土日は別件で忙しくてコードをかけなかった、、、今日からフロントの実装に取り掛かろうとvueの環境を構築してみてすごく訳わからんになっていた。<br>CORSなんていう言葉も出てきてえらいこっちゃとなってしまっていた。落ち着いて、APIから情報は取れたので焦らず勉強する。</p>&mdash; Diwamoto (@Diwamoto_) <a href="https://twitter.com/Diwamoto_/status/1353713822238797824?ref_src=twsrc%5Etfw">January 25, 2021</a></blockquote> 

**Thoughts**:
バックエンドが終わったので、フロントの実装に取り掛かるためにvueの環境をつくってみたが、そこから先がまるで進まなかった。
知らない知識が多すぎて、いきなりコードを書ける状態にはなっていなかった。
明日以降はいったんデータのやりとりを忘れてデザインを優先して作って行こうと思う。


**Link(s) to work**
[Vuetifyに入門する - Qiita](https://qiita.com/azukiazusa/items/16ebffd361af8fa58333)
[はじめに — Vue.js](https://jp.vuejs.org/v2/guide/index.html)
[Vuetify — A Material Design Framework for Vue.js](https://vuetifyjs.com/ja/)
[axios を利用した API の使用 — Vue.js](https://jp.vuejs.org/v2/cookbook/using-axios-to-consume-apis.html)
[Vue.jsとAxiosなら驚くほど簡単に作れる！外部APIを使ったWebアプリの実例 – WPJ](https://www.webprofessional.jp/fetching-data-third-party-api-vue-axios/)
[Vue CLIで作成したプロジェクトで起動する開発サーバーのポート番号を変更する | Developers.IO](https://dev.classmethod.jp/articles/change-vue-project-devserver-port/)
[【Vue.js】Vue CLIでaxiosを使う方法 - Qiita](https://qiita.com/yuta-38/items/eb4ccf5b884d12db0a90)
[echoとginでCORS対応するときの違いについて - Qiita](https://qiita.com/MasashiFujiike/items/7844150ce75d71a417ad)

### Day 20: 2021/1/26, 火曜日

**Today's Progress**: 
<blockquote class="twitter-tweet"><p lang="ja" dir="ltr"><a href="https://twitter.com/hashtag/100DaysOfCode?src=hash&amp;ref_src=twsrc%5Etfw">#100DaysOfCode</a> 20日目<br>フロントの環境がよくわからなかったので作り直した。<br>material designのためにvuetifyいれて、オートリロードのためにbrowser-syncを入れてとりあえず環境にはとても満足。<br>なにから初めたらいいかわからん状態になっているので明日くらいまではいじいじする感じになると思う。</p>&mdash; Diwamoto (@Diwamoto_) <a href="https://twitter.com/Diwamoto_/status/1354093981240590343?ref_src=twsrc%5Etfw">January 26, 2021</a></blockquote> 

**Thoughts**:
フロントの環境ができず、苦戦していた時にCIを導入することを忘れていたので、さくっとTravisCIを導入した。
設定をレポジトリにあげるだけで勝手にテストを回してくれるのでありがたい。
また、フロントの環境の絶対条件として、自動コンパイルとオートリロードは絶対欲しかったのだが、
vue-cliのプラグインを導入することでなんとか達成することができた。
明日もまずはいじってみて、実装に必要な知識を得ようと思う。

**Link(s) to work**
[【Rails】Travis CIを導入してdb:createで詰まったこと - Qiita](https://qiita.com/yamato1491038/items/4ff29867b87c5cc98e6f)
[Travis CI Tutorial - Travis CI](https://docs.travis-ci.com/user/tutorial/)
[App-barコンポーネント — Vuetify](https://vuetifyjs.com/ja/components/app-bars/#section-4f7f304465b9)
[vue-cli-plugin-browser-sync  -  npm](https://www.npmjs.com/package/vue-cli-plugin-browser-sync)
[【Vue.js】ボタンで学ぶ単一ファイルコンポーネントの基礎](https://b1tblog.com/2019/10/03/vue-button/)
[vuetifyjs + BrowserSync(lite-server)による変更のブラウザ同期 - Qiita](https://qiita.com/reireias/items/683d081780c31eaada2e)
[GulpではじめるVue.js（最小構成） - Qiita](https://qiita.com/yaaah93/items/be5a506a583b6cd17d68)
### Day 21: 2021/1/28, 木曜日

**Today's Progress**: 
<blockquote class="twitter-tweet"><p lang="ja" dir="ltr"><a href="https://twitter.com/hashtag/100DaysOfCode?src=hash&amp;ref_src=twsrc%5Etfw">#100DaysOfCode</a> 21日目<br>昨日の夜見ていて気になったのでbasercmsのcake4系化プロジェクトに参加した。環境構築で詰まったところがあったのでいくつかまとめてプルリクを投げた。<br>ローカル開発環境についてまだまだ極めるところがありそう、、とりあえずいっぱいテスト書いて貢献するぞ</p>&mdash; Diwamoto (@Diwamoto_) <a href="https://twitter.com/Diwamoto_/status/1354454923019051010?ref_src=twsrc%5Etfw">January 27, 2021</a></blockquote>

**Thoughts**:
baserのcake4化プロジェクト、コードネーム「ucmitz」に参加した。
baserは扱っていたし、cake4は一度アプリを作ったことがあるので
とりあえず環境構築でいくつか詰まったのでプルリクを投げた。
issueをみた感じ、あんまりわからなかったので、とりあえずテストを書いて貢献しよう。

**Link(s) to work**
[GitHub - baserproject/ucmitz](https://github.com/baserproject/ucmitz)

### Day 22: 2021/1/29, 金曜日

**Today's Progress**: 
<blockquote class="twitter-tweet"><p lang="ja" dir="ltr"><a href="https://twitter.com/hashtag/100DayOfCode?src=hash&amp;ref_src=twsrc%5Etfw">#100DayOfCode</a> 22日目<br>今日はフロントのトップページ作ってた。<br>基本がなってないからもうmacの画面で見るのとモニターで見るのでスタイルが崩れてしまっていて泣いた。<br>とりあえずトップページができたらデプロイしようかなぁ</p>&mdash; Diwamoto (@Diwamoto_) <a href="https://twitter.com/Diwamoto_/status/1354809933036806147?ref_src=twsrc%5Etfw">January 28, 2021</a></blockquote> 

**Thoughts**:
今日はvuejsに戻って、フロントの実装を始めた。デザインは知識が全くなく、基本がわかってないので、いろんなサイトを見てカッコ良さそうなサイトを真似した。
vuetifyのスタイリングの感覚が微妙にbootstrapの感覚と違う為、macの画面とモニターの画面で全然違った。おそらく、vuetifyのレイアウトシステム自体がSPAを作るのにはいいが、
トップページなどの単一のサイトを作るのには少し不向きな気がする。
とりあえず簡潔に作って、実際のシステム制作に早く入ろう。


**Link(s) to work**
[Vue.jsメモ：属性、ループ内呼び出し、など - Qiita](https://qiita.com/asaokamei/items/6afa7e2f33207d041588)
[Vueのv-forディレクティブの書き方・使い方について解説 | ELOOP（イーループ） - 開発課題に取り組んで身につける実践型プログラミング学習サービス](https://www.e-loop.jp/knowledges/9/)
[Vuetify.js 2.2のGridSystemについて - Qiita](https://qiita.com/rubytomato@github/items/07fe07e64482f8f03ef3)
[レスポンシブの基本、メディアクエリの書き方 | それからデザイン スタッフブログ](https://sole-color-blog.com/blog/71/)

### Day 23: 2021/1/30, 土曜日

**Today's Progress**: 
<blockquote class="twitter-tweet"><p lang="ja" dir="ltr"><a href="https://twitter.com/hashtag/100DaysOfCode?src=hash&amp;ref_src=twsrc%5Etfw">#100DaysOfCode</a> 23日目<br>午前中はlamp環境を見直そうということでdockerimageとalpineとビルドログをみてうなってました<br>午後はvueに戻ったが、かなりレガシーなやり方で作ってたトップページのレスポンシブを保つのに苦戦している。<br>トップだけは普通にhtmlをちゃんと書いて作った方が良さそう、、、</p>&mdash; Diwamoto (@Diwamoto_) <a href="https://twitter.com/Diwamoto_/status/1355200441735237633?ref_src=twsrc%5Etfw">January 29, 2021</a></blockquote>

**Thoughts**:
ucmitzの環境が、vagrantのosにcentosを使用しており、そのカーネルが古いせいでビルドに失敗していたので、osにdocker用のosであるbargeを採用してもらおうと
vagrantfileをいじっていたがあまりうまく行かなかったのでやめた。
午後はvueに戻って、トップページをレスポンシブに対応しようとしてあんまりできなかった。
きちんとrowcolで書かないと実装できなさそう。


**Link(s) to work**
[Vuetify.js 2.2のGridSystemについて - Qiita](https://qiita.com/rubytomato@github/items/07fe07e64482f8f03ef3)
[レスポンシブの基本、メディアクエリの書き方 | それからデザイン スタッフブログ](https://sole-color-blog.com/blog/71/)
[【CSS3】transition でプロパティを複数指定する書き方 - ハンドルネームの由来は乳製品好きから](https://becolomochi.hatenablog.com/entry/2017/12/27/160330)
[Vue.jsでスクロールを検知する - Qiita](https://qiita.com/SatoTakumi/items/d88df8afae82c53d2d2a)
[Vue & Vuetifyでバリデーション付きのフォームを作ってみる - Qiita](https://qiita.com/tekunikaruza_jp/items/0a68d86084d961d632ac)

### Day 24: 2021/1/31, 日曜日

**Today's Progress**: 
<blockquote class="twitter-tweet"><p lang="ja" dir="ltr"><a href="https://twitter.com/hashtag/100DaysOfCode?src=hash&amp;ref_src=twsrc%5Etfw">#100DaysOfCode</a> 24日目<br>今日は一時間くらいしか勉強の時間が取れなかった、<br>とりあえずヘッダーをcssの勉強かねてvueを用いつつちゃんと書き直した。<br>トップに時間取られても意味ないし、結構いい感じになったのでこのくらいでやめておく。<br>明日からはちゃんとログイン画面作ります！！！</p>&mdash; Diwamoto (@Diwamoto_) <a href="https://twitter.com/Diwamoto_/status/1355561011344928773?ref_src=twsrc%5Etfw">January 30, 2021</a></blockquote> 

**Thoughts**:
今日はあまり時間が取れなかったが、トップページのcssとかをちゃんと直してレスポンシブ対応させた。
最低限の動きもあるし、とりあえず先に行こうと思う。
早いところフロントとバックエンドの実装に進みたい。

**Link(s) to work**
[Vuetify.js 2.2のGridSystemについて - Qiita](https://qiita.com/rubytomato@github/items/07fe07e64482f8f03ef3)
[レスポンシブの基本、メディアクエリの書き方 | それからデザイン スタッフブログ](https://sole-color-blog.com/blog/71/)
[【CSS3】transition でプロパティを複数指定する書き方 - ハンドルネームの由来は乳製品好きから](https://becolomochi.hatenablog.com/entry/2017/12/27/160330)
[Vue.jsでスクロールを検知する - Qiita](https://qiita.com/SatoTakumi/items/d88df8afae82c53d2d2a)
[Vue & Vuetifyでバリデーション付きのフォームを作ってみる - Qiita](https://qiita.com/tekunikaruza_jp/items/0a68d86084d961d632ac)