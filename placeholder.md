# プレースホルダー

## オンライン飲み会

Zoomとかで雑にやりましょう

###　アルコール依存症のリスク

終電とかないし、いくらでも飲めちゃうので、アルコール依存症には注意しましょう。

<!--
とりあえずどこに入れるか迷ったらここに書いてくださいー

-->

## アンチパターン集

臨時休校することが突然決まり、子育て世代からは悲鳴が上がっていました。これまでに例のない状況なので、リモートワークが急遽できるようになったけれど、環境や制度が整っておらず、アンチパターンに陥ったというケースをいくつか取り上げてみます。

### セキュリティの境界線

会社からノートPCが支給され、VPN とリモートデスクトップで社内に接続します。セキュリティの問題でクラウドサービスは使えないため、人気のチャットツールであるSlackは利用できないことになっています。すべての連絡をメールでやりとりするのは大変なので、オープンソースの Rocket.Chat を使ってチャット環境を構築しました。自社内にオンプレミスで利用できます。

一方、Web会議にはZoomを使うことになりました。Skypeよりも通話が安定し、環境設定が不要だからということです。会社のPCから接続するとネットワークに不可がかかるため、個人PCからZoomへのアクセスも許可されました。SlackはNGなのに、ZoomはOK？境界線がよくわかりません。

### 勤怠状況のエビデンス

上司に始業と終業のタイミングにメールで報告します。メールの送信時間がエビデンスとして残るので、送信したメールを印刷して提出するという運用方法になりました。紙で提出するために月初にわざわざ出勤しなければなりません。会社に信頼されていないのでしょうか？

### 子どもと仕事は無理ゲー

家族とずっと一緒に過ごすので、孤独は感じないのですが集中力が続きません。雨の日は外で体を動かすことができないので、家でリングフィットアドベンチャーをする我が子。「いいね！」「輝いてるよ！」とほめてくる横で働く私。子どもの勉強をみたり、昼食を用意したりする自分をほめてほしいですよね。

### 最後に

通勤時間がなくなり、家族と過ごせる時間が増え、リモートワークしてよかったなと思う反面、対面で会話しないことによる認識のずれや、労務管理やセキュリティに対する課題があることがわかってきました。今回の状況を考慮しながら、会社や社会全体の取り組みが改善されていくことを期待しています。
