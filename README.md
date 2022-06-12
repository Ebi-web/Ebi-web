# インターン

## Sprinters:パーソルキャリア (2022年6月)

### 概要
パーソルの開発組織で実際に使われている「確かなニーズのある開発事業を最速で立ち上げユーザーテストまで行う」手法である[デザインスプリント](https://www.i3design.jp/in-pocket/8958) の実践。この中でチームリーダーを務め、それに徹することを意識し以下のような点でチームに貢献した。

- 議論が迷走しないよう事前に議論の進め方(全体像)を共有してから議論を始める
- メンバーの強みが埋もれないよう、発言の少ないメンバーに意見を求める
- 分業できるところは積極的に分業して作業効率を上げる

## merpay QA Training Camp(2022年5月)

### 概要
merpayで用いられている様々な品質保証技術の基本や開発組織作りに関する講義やその実践

## T4INDUSTRIES(2021年~2022年)

### 概要
B向けの日本初・マーケティングサービスにおける新規開発・保守運用
サービスサイト: https://rox-message.jp/

### 使用技術
- Docker,PHP8.0,Laravel8,Vue.js,MySQL8.0,REST_API,Github_Actions
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

### Firebase
- Firebase Auth
</p>

# My Status

<a href='https://github.com/anuraghazra/github-readme-stats'>
  <img align='center' src='https://github-readme-stats.vercel.app/api?username=Ebi-web&count_private=true&show_icons=true&theme=tokyonight'>
 </a>

# Qualifications
- ITパスポート試験 (2021/5/19取得)
- 基本情報技術者
- TOEFL iBT 93点
