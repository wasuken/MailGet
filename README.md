# MailGet
始め

その名の通りMailをGetしていろいろやるツール

<h1>更新履歴</h1>

<h2>2016年</h2>

<h3>2月</h3>

2日
ここに追加。
でも追加する前から作成はしてた。
ここまでで　Gmailから取得可能な処理とYahooメールから取得可能な処理を作成というかほぼパクった。
それぞれもう片方からは取得できないので困っていた。

4日
GmailとYahooメール両方できるようにした。　と言っても、それぞれの処理に使用するMailサーバによって
処理を分けてるだけだから根本的には解決していない。
故にかなり強引だからもっとコードの少ない方法で処理したかった。

6日
アカウント管理実装。
一応暗号化してるので多分ばれない　　多分。


<h2>MailChecker機能</h2>
メールに接続するとそのアカウントの件数を監視して
増えたら通知してくれる機能。　　故に監視時間の間に増えて、その後削除されるとなんも通知してくれない。

2月28日現在通知まではできている

次に実装したい機能は
・複数機能の監視
・ログの蓄積
・ログ見てなかった場合の通知アイコンの変更（なくてもいい）
・ContextMenuの実装
