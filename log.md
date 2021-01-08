# 100 Days Of Code - Log

### Day 1: 2021/1/4, Monday

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

### Day 2: 2021/1/5, Tuesday 

**Today's Progress**: 
<blockquote class="twitter-tweet"><p lang="ja" dir="ltr"><a href="https://twitter.com/hashtag/100DaysOfCode?src=hash&amp;ref_src=twsrc%5Etfw">#100DaysOfCode</a> 2日目<br>一昨日はできなかったのでとりあえず今日は一時間超えてもvueが動くところまでやった。<br>結果としてはnodeのインストールに苦戦しただけでvueが動いてspaとして機能するところまでは出来上がった。<br>今日はcakeでプロジェクト作ってモデルのCRUD作るところまでやる。</p>&mdash; Diwamoto (@Diwamoto_) <a href="https://twitter.com/Diwamoto_/status/1346701699751112705?ref_src=twsrc%5Etfw">January 6, 2021</a></blockquote>

**Thoughts**:
vueのSPAを動かすところまでできた。nodeのバージョンが結構頻繁にアップデートされてるせいかわからなかったけど最新版のnodeでは
vue-cliが動かなかったので動くバージョン探しに手間取った。とりあえず記事のバージョンに合わせることで一応は動いた。
SPAはどんなものかは大体わかったので次はcakeでモデルとAPI作って、vueでCRUDできるところまで頑張る。目標は一機能ごとに二日。

**Link(s) to work**
1. [【Vue.js】爆速でSPAを作る](https://qiita.com/nagimaruxxx/items/8fc59a5ca05bb91bfe1f)

### Day 3: 2021/1/6, Tuesday 

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

### Day 4: 2021/1/7, Tuesday 

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


