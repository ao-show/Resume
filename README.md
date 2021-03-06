# 業務経歴書

## 基本情報

|key|value|
|----|----|
|名前|青松 聖弥(あおまつ しょうや)|
|性別|男性|
|年齢|26歳|
|エンジニア歴|約4年|
|主な活動拠点|大分県|
|趣味|ゲーム、ドライブ、カラオケなど|
|所持資格|基本情報技術者試験、AWS SAA(939/1000で合格)|
|Qiita|[@ao-show](https://qiita.com/ao-show)|

## 詳細情報

- 2017年4月に地方SIerへ新卒入社し、2021年5月よりフリーランスエンジニアとして活動しています。
- クラウドアーキテクチャの設計・構築、Webアプリケーションのバックエンド開発をメインとしています。
- 明るい性格でコミュニケーション能力は高い方だと自負しており、業務に関すること・ないこと問わず、人と話すことが好きです。
- クラウド環境におけるWebアプリケーション開発や新しい技術を使った効率化、サーバレス化などが自分の価値を最も発揮出来ると考えています。

## スキル

### 言語

Ruby | Python | Go | Java | C# | PHP | JavaScript | TypeScript | VB.NET

### フレームワーク

jQuery | .NET Framework | Spring Framework | React(自己学習中)

### データベース

PostgreSQL | Oracle | SQL Server

### AWS

Athena | CloudWatch | CodeCommit | CodeBuild | CodeDeploy | CodePipeline | DynamoDB | EC2 | ECR | ECS(Fargate) | EFS | IAM | Kinesis | Lambda | S3 | SNS | SQS | VPC | X-Ray

### その他

Docker | Vagrant | nginx | Apache | IIS | Webpack | REST API | GraphQL(自己学習中)

## 業務経歴

### 車両データの収集および解析システム　開発・運用(2019/02〜2021/04 : 27ヶ月間)

【概要】

- 某自動車メーカー様が利用するシステムで、自動車の次期モデル開発に役立てたり、現行車両における改善点の把握などを目的としたシステム。
- 検証対象の車両に専用の車載機が搭載されており、その車載機からAWS S3に向けて車両データが送信される。
- AWS S3に蓄積された車両データをもとに、ETL処理を行うバッチ(以下ETLバッチ)によってデータを変換。先述した目的のため、変換後のデータをWebアプリケーションによって可視化する。

【言語】

- Python 3.7
- Ruby 2.7
- Go 1.11
- PHP 7.2
- TypeScript
- CSS
- HTML

【その他技術など】

- AWS
- Docker
- Apache
- Git

【担当業務】

- 前提として本件はWebアプリケーション担当とETLバッチ担当の2つに分かれているが、自分は主にETLバッチ側を担当していた。ETLバッチ側の作業内容としては、Webアプリケーション側の新規機能や画面追加に伴うバッチの修正であったり、バッチの高速化、属人性の排除などの作業を行った。また、アサインされた当初はDevOpsの仕組みが導入されていなかったため、CodeCommit + CodePipeline + CodeBuild + CodeDeployを使ってCI/CDを構築し、以後のメンテナンスも担当した。
- 蓄積された車両データの新たな活用方法や既存システムで改善すべき点、追加したほうが良い機能などを資料にまとめ、2週間に1回開催される定例会にてご担当者様へ説明。

【コメント】

- 本件で使用する言語やAWS、Linuxなどの全てが未経験の状態でアサインとなったが、1ヶ月で基本的な知識や操作などを習得。以後はETLバッチ側をほぼ一人で担当しつつ、手が空いた際にはWebアプリケーション側の改修に回るなどし、自分の持つ知識や技術、経験をフルコミットすることでチームに貢献した。
- システムをより良いものにすべく、チーム内やご担当者様へ向けて積極的に自分の考えや意見を伝え、システムを改善していった。中でも印象に残っているものはETLバッチの高速化で、ロジックの改善に加えて言語をRubyからGoへマイグレーションすることで、1車両あたりにおけるETL処理時間を約1/6に改善した。同時に費用面も削減され、ご担当者様から高い評価をいただいた。その他にもCI/CDの導入やETLバッチのサーバレス化などの案が採用され、本システムに導入した。

### 電子カルテパッケージ カスタマイズ(2018/07〜2019/01 : 7ヶ月間)

【概要】

- 病院で使用される電子カルテがパッケージ化されており、各病院の要望に応じてパッケージをカスタマイズして納品。

【言語】

- C#
- JavaScript
- CSS
- HTML

【その他技術など】

- WPF
- SQL Server

【担当業務】

- WPFによって作られた電子カルテを改修、テストして納品。フロントエンド、バックエンド問わず自分一人で改修対応を行った。

【コメント】

- 本件の開発担当は自分のみで周りに技術面で相談出来る相手がいない状況であったが、コーディング～納品までの一連の作業を完了させた。初めて一人で一通りの作業を行ったことで、自分の技術力が通用することを実感し、責任感をもって最後までやり遂げる人間である ということを周りにアピールすることが出来た。

### 自動車運転見守りサービス 新規開発(2017/12〜2018/06 : 7ヶ月間)

【概要】

- ご家族に自動車の運転が未熟な人や高齢者がいる人向けのサービスで、ご家族の人が危険運転をしていないか遠隔で監視出来るシステム。
- 車両の速度や揺れ、アラートなどの情報がAzure上に送信され、そのデータをもとに、運転評価を表すレーダーチャートや走行軌跡が描画されたマップなどを閲覧出来るWebアプリケーションを提供。

【言語】

- C#
- JavaScript
- CSS
- HTML

【その他技術など】

- Azure
- IIS
- SQL Server

【担当業務】

- フロントエンド周りとテスト実施をメインで担当し、一部バックエンド側も担当した。

【コメント】

- コーディングをメインで担当するのは本件が初めてということもあり、アサインされて間もなくは周りからサポートを受けることが多くあったが、書籍やインターネットの情報、あるいは周りのメンバーへ積極的に質問などすることで、徐々に自分で考えてコーディングが出来るようになったことを実感。
- メンバー内にグラフのライブラリについて精通している者がいなく、自分が主体となってライブラリの選定を担当した。各ライブラリの公式ドキュメント(英語)などを読んで、やりたいことが実現出来るかどうかを検討し、チーム内のメンバーに情報を展開。ここでも自らが持つ積極性を発揮した。

### 高速道路の工事規制支援システム 新規開発(2017/04〜2017/11 : 8ヶ月間)

【概要】

- 高速道路運営会社様向けのBtoB案件で、高速道路における工事規制、工事通行止めなどの情報を登録・編集出来るシステムの新規開発。

【言語】

- Java 8.x
- JavaScript
- CSS
- HTML

【その他技術など】

- Spring Boot
- Oracle
- PostgreSQL

【担当業務】

- 単体・結合テスト仕様書の作成やテスト実施をメインで担当。HTMLやCSS、JavaScriptなどのフロントエンド周りも一部担当した。

【コメント】

- テスト仕様書の作成やテスト実施、デバッグなどの与えられた作業をこなしつつ、空いた時間で他人のソースコードを見たりネットで調べたりすることでプログラミングについて学習した。プロジェクト自体が忙しかったこともあってサーバサイド側のコーディングは担当させてもらえなかったが、学習した内容や自分が出来ることを周りに積極的にアピールし、フロントエンド側を一部任せてもらうことができた。自らが持つ積極性やコミュニケーション能力の高さを発揮した。
