# Curriculum Vitae

## 基本情報

|key|value|
|-------|--------|
|名前|海老澤俊明|
|居住地|埼玉県桶川市|
|Twitter|[@eng_toshiaki](https://twitter.com/eng_toshiaki)|
|Qiita|[@EbiTT](https://qiita.com/EbiTT)|
|Portfolio|[Google Slide](https://docs.google.com/presentation/d/1EE7jD9pdZupcJr4AZowyyCcpztgFQ-a3gUj2hbYslv8/edit?usp=sharing)|
|英語力|TOEFL iBT93点(英検準１級相当)|
|好きな英語|イギリス英語🇬🇧|
|資格|応用情報技術者|

## CARTA HOLDINGS: Treasure【開発/現在参加中】(2022年8月)

### 概要
React,Goの講義の後、チーム開発と成果物の発表を行うもの。

### 使用技術
React,Swagger,Golang,PostgreSQL,Makefile(他追加予定)

### チーム開発での担当・工夫・学んだこと

(追加予定)

## React部屋【Next.js/TypeScript】(2022年5月~)

### 概要
タスクの依存関係も登録できるタスク管理アプリを学生チームで開発したもの

### 使用技術
- Docker,TypeScript,React,Redux,Next.js,Mantine,EsLint,prettier,husky,vercel,Github Actions
- 今後使用予定: Golang,GraphQL,Apollo Client,AWS App Runner, PlanetScale

### 担当
チームリーダー兼エンジニアとして、要件定義、技術調査・選定、開発環境構築、画面設計、Reactによるフロントエンドの実装の一部を担当。具体的には下記。

- Next.js+TypeScript+Functional Componentを使ったフロントエンドの実装
- Mantine, FlowbiteなどのUIライブラリの選定とUI作成
- Redux,Jotai,Recoilなどの状態管理ライブラリの調査と選定
- Docker, docker-composeを使った開発環境の構築
- タスク管理アプリとしての新規性を担保した要件定義

### 工夫・取り組み
ReactとTypeScriptでの開発はいずれも初体験でありReact Hooksの理解はハードルが高かったが公式ドキュメントやUdemyなどを地道に調べベストプラクティスを素早く習得した。また、テーマがタスク管理アプリということでいかに新規性を出すかに腐心した結果、「タスクの親子関係を踏まえて家族単位でタスクを登録できること」「タスク全体に対する現在の達成度やスケジュール感を把握しやすくすること」という2点を採択し要件定義を行った。加えて普段はバックエンドがメインのためフロントエンドのUI作成作業は慣れなかったが、Mantineによる直感的なUIを実現。

## Sprinters:パーソルキャリア【企画開発】 (2022年6月)

### 概要
パーソルの開発組織で実際に使われている「確かなニーズのある開発事業を5日で立ち上げユーザーテストまで行う」手法である[デザインスプリント](https://www.i3design.jp/in-pocket/8958) の実践とUpper Managementへの発表。5チーム中2位を獲得。

### 担当・取り組み
この中でチームリーダーを務め、それに徹することを意識し以下のような点でチームに貢献した。

- 議論が迷走しないよう事前に議論の進め方(全体像)を共有してから議論を始める
- メンバーの強みが埋もれないよう、発言の少ないメンバーに積極的に意見を求める
- 分業できるところは積極的に分業して作業効率を上げる

### 利用ツール
Miro, Figma(プロトタイプ作成に使用)

## merpay QA Training Camp【品質保証】(2022年5月)

### 概要
merpayで用いられている様々な品質保証技術の基本や開発組織作りに関する講義やその実践。

### 工夫・取り組み
この中で組み合わせテストケース数を統計的に10%まで削減するPICTを学習した。他の開発においてテストケースの組み合わせが膨大になってしまう箇所にこれを適用し効率的なテストの実行に貢献した。

## T4INDUSTRIES【PHP/Laravel/Vue.js/Fargate】(2021年~2022年)

### 概要
B向けの日本初SNSマーケティングサービスにおける新規開発・保守運用
サービスサイト: https://rox-message.jp/

### 使用技術
- Docker,PHP8.0,Laravel8,Vue.js,MySQL8.0,REST API,Github Actions
- AWSは以下の通り CloudWatchLogs/ALB/ECS/Fargate/ECR/CodePipeline/S3/Cloudfront/EC2/RDS/VPC/CloudTrail/EventBridge

### 担当
バックエンド(一部フロントエンドも)エンジニアの1人目として初期からプロジェクトに入り、外部APIやその他の技術調査、画面設計、DB設計、Vue.jsによるフロントエンドの実装の一部、Laravelによるバックエンドの実装、AWSの各種サービスを用いた機能の構築/運用等を担当。また、社会人エンジニアの方とのチーム開発であった。具体的には下記。

- Laravelを用いたCRUDなどの基本的なAPI開発
- Vue.js, Typescript,Composition APIでのコンポーネント作成
- 各種外部APIの調査
- 外部APIを利用したキーワード検知機能を持つDM自動返信基盤の構築と高速化
- Laravel-enumによる拡張性を考慮した権限管理機能の実装
- Git-flowイメージに基づいたGitブランチ管理
- 管理ドメインごとに分けたDockerコンテナの設計
- local,dev,stg,prod環境を切り分けた上での運用
- ECS Fargate, EventBridge, CloudTrailを用いたDM配信基盤の構築と証跡管理
- Github ActionsとCodePipeline,ECS,ECRを用いたCI/CDの運用
- supervisorを用いたDM配信基盤の安定化
- AWS Budegt Explorerに基づいたコスト最適化
- ドメインモデルをはじめとするドメイン駆動設計の導入による保守性の向上
- PHPUnitによるユニットテスト
- バッチプログラムの開発と実行基盤の構築

### 工夫・取り組み
本格的な開発の現場はこれが初めてであり、あらゆる技術が初体験だった。特にGithub Actions, CodePipelineとECS Fargateを用いたCI/CDに関しては、Docker自体初めてな上に難度が高く情報も少なかったが、各種書籍やネット情報を地道に調査して運用に必要な知識を素早く習得した。設計分野では未経験から書籍などを参考にしながらドメインモデルをはじめとするドメイン駆動設計を積極的に実装し、保守性の向上に寄与した。また、外部のAPIのChangelogをRSS登録して自主的にまとめて、開発途中で得られた知見を付け加えたNotionを独自に社内に公開し新機能の立案や修正点の早期発見などに大きく貢献できた。

# Skills(開発経験のあるもののみ)

## 言語系
- PHP
- Python3
- Ruby
- JS/TS
- Go(個人開発にて使用予定)

## ライブラリ・フレームワーク
- Laravel(6.xと8.x)
- Streamlit
- Rails
- GraphQL
- Vue.js
- React(個人開発にて使用中)
- Tailwind CSS(個人開発にて使用中)
- Jest(個人開発にて使用中)
- Eslint(個人開発にて使用中)
- Bootstrap
- PHPUnit

## OS
- Linux
- Windows
- Mac

## ミドルウェア
- Apache
- Nginx
- MySQL
- PostgreSQL

## エディタ・IDE
- VSCode
- PhpStorm
- RubyMine
- PyCharm Professional

## クラウド・他
### AWS
- EC2
- ECS Fargate
- Application Lord Balancer
- RDS
- Route53
- ACM
- Lambda
- SNS
- DynamoDB
- IAM
- VPC
- CloudTrail
- S3
- CloudFront
- CloudWatchLogs
- ECR
- CodePipeline
- EventBridge
### 他
- Github Actions(CI)
- vercel

### Firebase
- Firebase Auth
</p>

# My Status

<a href='https://github.com/anuraghazra/github-readme-stats'>
  <img align='center' src='https://github-readme-stats.vercel.app/api?username=Ebi-web&count_private=true&show_icons=true&theme=tokyonight'>
 </a>
