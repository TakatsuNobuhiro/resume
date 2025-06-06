# 職務経歴書

## 基本情報

| 氏名     | 高津亘宏                                                       |
| -------- | -------------------------------------------------------------- |
| 生年月日 | 1998/06/22                                                     |
| GitHub   | [TakatsuNobuhiro](https://github.com/TakatsuNobuhiro)          |
| Wantedly | [takatsunobuhiro](https://www.wantedly.com/id/takatsunobuhiro) |
| YOUTRUST | [tk2](https://youtrust.jp/users/tk2)                           |

### 最近の興味

LLM× プロダクト開発の限界に挑戦中。
LLM をプロダクトに組み込むことと、LLM を用いて少ない工数で開発することに興味があります。

### 出来ること

インフラからフロントまで幅広く対応可能です。
GCP と AWS 両方に精通しているため、クラウドの技術選定も得意です。
Typescript,Python を中心とした AI 駆動開発で少ない工数で Web 開発をまるっと出来ます。
広く浅く様々な技術に触れた経験があるので、経験が浅い技術でも LLM に聞いたり公式ドキュメントを読みながらキャッチアップ可能です。

## 主な運営サービス

- [フットサル戦術メディアフットテック](https://futsal.tech/)
- [フットサル戦術ボード(web 版)](https://board.futsal.tech/)
- [フットサル戦術ボード(App 版 React Native で開発)](https://apps.apple.com/jp/app/%E3%83%95%E3%83%83%E3%83%88%E3%82%B5%E3%83%AB%E6%88%A6%E8%A1%93%E3%83%9C%E3%83%BC%E3%83%89/id6741555702)

※代表的なサービスのみ記載

## 経歴要約

在学中に Web 開発を独学し、オンライン新歓アプリを個人開発してリリース。インターン経験を積むために 1 年休学し、2020 年 10 月に受託開発企業である株式会社アクセルユニバースに入社。2021 年 7 月に株式会社 TORICO に移り、漫画全巻ドットコムの PHP→Django+Nuxt.js リプレイスを担当。その後、電子マンガサービス「スキマ」の開発に従事し、ポイントシステムの導入と交換機能を一人で実装。2023 年 4 月から 2024 年 12 月まで合同会社 DMM.com のオンラインサロン開発部アーキテクトチームで勤務し、サロン開設審査の AI 自動化やマイクロサービス化などの大規模開発を経験。2024 年 4 月からは Resource 株式会社でマーケットプレイス「ISSUE」の開発に副業として参画し、2024 年 8 月から 11 月には株式会社 Hanji で学習支援アプリのサーバーサイド開発も担当。2025 年 1 月より個人事業主として独立し、複数案件を掛け持ち＆受託開発で活動中。

## 得意な技術

- TypeScript
- React.js, Next.js
- Python（大学の授業から使用）
- SQL, DB 全般
- クラウドインフラ全般（Associate 資格 GCP, AWS 両方保持）

## 取得資格

| 資格名                                        | 取得時期      |
| --------------------------------------------- | ------------- |
| Associate Cloud Engineer                      | 2023 年 7 月  |
| 基本情報技術者試験                            | 2022 年 10 月 |
| AWS Certified Solutions Architect - Associate | 2022 年 8 月  |
| AWS Certified Cloud Practitioner              | 2022 年 7 月  |

## Resource 株式会社（2024 年 04 月～現在、副業）

### 概要

企業とエンジニアのマーケットプレイス「ISSUE」の開発（新規機能開発＋保守運用）

### 業務内容

- メッセージ送信時のテンプレート機能
- 職務経歴書から主要データ抽出（OCR+LLM）
- 最寄り駅からユーザーを検索する機能
- 予算管理機能
- 面談評価機能

### 使用技術

- Next.js, TypeScript
- Firebase（Cloud Functions, Firebase Authentication, Cloud Storage, Firestore）
- Elasticsearch
- Docker
- GCP

### 主な開発実績

- メッセージ送信時のテンプレート機能
- 職務経歴書から主要データ抽出（OCR+LLM）
- 最寄り駅からユーザーを検索する機能
- 予算管理機能
- 面談評価機能
- デプロイフローの改善：各々のローカルから少数の dev 環境へのデプロイコマンド実行時に発生していたコンフリクトを解消するため、デプロイコマンド実行時に Slack に通知される仕組みを構築し、環境の使用状況を可視化
- Sentry のログ基盤整備：どの環境で、どのユーザーが、どの URL でエラーが発生したかを明確に把握できるよう改善
- ローカル開発環境の整備：開発者間でのデータ競合を防ぐため Firebase Emulator を導入し、Docker で Elasticsearch+Kibana を立ち上げられる環境を構築

## 株式会社 Hanji（2024 年 8 月〜2024 年 11 月 副業）

### 概要

ユーザーが送信した問題の写真に対して、解答やヒントを提供するアプリ（https://knock-snap.jp/）のサーバーサイド開発を担当。
評価システムが存在しないため、アルゴリズムや LLM を変更後に精度向上を測定できないという課題がありました。そこで、Langsmith を導入して Agent の評価システムを構築し、問題を解決しました。

### 使用技術

- Python, FastAPI
- LLM（Gemini, OpenAI, Claude）
- Langsmith

## 合同会社 DMM.com オンラインサロン開発部（2023 年 4 月〜2024 年 12 月 正社員）

### サロン開設審査 AI レギュレーションチェックによる自動化

#### 概要

オンラインサロンを開設するたびに入会ページを 50 項目以上のレギュレーションに違反していないか人間が目視でチェックしていて工数がかかることが課題になっていたため、LLM によって自動化しました。

#### 使用技術

- Python, LangChain
- Lambda
- AzureOpenAI

### DMM オンラインサロンのリアーキテクト、マイクロサービス化

#### 概要

サービスをローンチして 7 年目にして技術的負債を解消するためフルリプレースプロジェクト（マイクロサービスを見据えたモジュラモノリス化）が発足し、それを推進するアーキテクトチームに所属し、インフラからフロントエンドまでフルスタックに開発。

#### 開発体制

スクラム開発

チームのメンバー：6 名

#### 実績、業務内容

- サーバーレスアーキテクチャのデータ移行基盤の作成
- リプレイス先の新サービスの開発（バックエンド、BFF、フロントエンド）

#### 詳細な内容、発揮したバリュー

モノリスなサービスをマイクロサービス化するのに伴い、新 DB に全て移行することにしました。AWS MSK+Lambda でリアルタイム旧 DB の変更を検知し、新 DB に書き込み（Insert or Update）を行う仕組みをサーバーレスで作成しました。新 DB の設計はドメイン駆動設計を元にデータベースを分割し、適切に正規化を行いました。

リプレイス先のシステムはモジュラモノリス＋マイクロサービスアーキテクチャで開発し、DDD（ドメイン駆動設計）で適切にサービスを分割し Golang+gRPC で開発しました。BFF は Node.js, Fastify, TypeScript, GraphQL で開発しスキーマ設計から一貫して行いました。フロントエンドは Next.js（App router）+Pandacss で開発しました。

ただリプレイスするだけでなく、ユーザーに届けたい価値やビジネス的な観点を考えながらデザイナーと壁打ちしてリプレイスに伴い画面や機能もアップデートさせていきました。

このプロジェクトを通して今まで経験したことがなかった Golang, gRPC, GraphQL, Terraform などのモダンな技術やスクラム開発を経験することができました。

#### 参考記事

- https://inside.dmm.com/articles/salon-neon/
- https://inside.dmm.com/articles/salon-datebase-migration/
- https://inside.dmm.com/articles/salon-datebase-migration-challenges/
- https://inside.dmm.com/articles/salon-neon-protobuf-docusaurus/
- https://inside.dmm.com/articles/salon-neon-stack/

#### 使用技術

##### 新基盤（Microservices + Modular Monolith）

- 言語：Go
- ビルド：Bazel
- IDL：Protocol Buffers
- IPC：gRPC
- アーキテクチャ：オニオンアーキテクチャ

##### BFF

- 言語/フレームワーク：Node.js, Fastify
- IDL：Protocol Buffers, GraphQL
- IPC：gRPC, GraphQL
- アーキテクチャ：オニオンアーキテクチャ

##### Frontend

- 言語/フレームワーク：Next.js, TypeScript

##### クラウドインフラ・ツール等

- モニタリング：NewRelic
- オーケストレーション：ECS Fargate
- 構成管理：Terraform
- CI：CircleCI, GitHub Actions

##### DB 同期（サーバーレスアーキテクチャ）

- StepFunction, Lambda, ECS, EventBridge

##### 現（旧）システム

- フロントエンド：React, Redux, Redux-Saga, TypeScript
- サーバーサイド：Laravel, Zend Framework
- インフラ：Elastic Beanstalk, Aurora MySQL, Elemental MediaLive
- その他：Firebase, Sentry, NewRelic, CircleCI, Bitrise

## 新卒研修(2023 年 4 月~8 月)

第二新卒で入社したため、希望の元新卒に混じって研修を受けさせて頂きました。
今まで触ったことなかった技術(Golang, GCP, Terraform, React.js, Next.js etc)がキャッチアップでき、体系的なエンジニアリングの基礎を身につけることができました。
![新卒研修](https://lh3.googleusercontent.com/ODbZ5ZiqkYNZCb5Z-ys2tK1tofG6MocY7Cb_6HZImL23N5yzx17MmoWOr65578zhgfefKtsvSW5Qhhu7K8-OYtqbVyJQTVUMiS1cxzdM7c__DD2whMzz7CIggdFdRbUfHVWQBlfqS2TiBlREa9azdS8)

### 参考記事

https://inside.dmm.com/articles/engineer-training-2023/

## 株式会社 TORICO（2021 年 7 月〜2022 年 10 月 正社員＋インターン）

### スキマの開発（2022 年 10 月〜2023 年 3 月）

#### 概要

スキマという無料で電子漫画を読めるサービスの新規開発プロジェクトであるポイントサイト化を担当しました。

#### 背景

7 年以上前にローンチしたスキマというサービスは近年売上が低迷していたため、漫画を読んでポイントを貯めて交換できるポイ活アプリへシフトすることが役員会議によって決まりました。

#### チーム構成＆担当領域

2 人（自分＋アプリ開発エンジニア）

要件定義から設計、実装、リリース、ビジネス的な価値を提供するところまですべて担当

#### 内容

既存のコインの概念を有償コイン → コイン（そのまま）＆無償コイン → ポイントへ変更し、ポイントをドットマネー経由で 50 種類以上の商品と交換できるようにしました。

##### 交換機能のフロントエンドの実装

いきなり作り始めるのではなく、ドットマネーの仕様書を読み込んだ上で Figma でモックを作成しビジネスサイドとイメージを共有しながら不確実性を押し下げていきました。

##### 交換機能のバックエンドの実装

- セキュリティチェック
- トランザクション処理
- 交換ログ
- テストコード

を長期的なサービス運用を考えながら実装しました。これらをすべて一人で自走して実装し、リリース期日までに間に合わせました。

サービスローンチ後はビジネスサイドに追いたい数値（KPI）を話し合って Redash を作成しました。

##### その後の運用を考慮した実装

交換先商品一覧の情報が変更され次第先方から差分が送られてくる仕様だったので、ビジネスサイドの方でいつでも変更できるようにスプレッドシートと連携し、スプレッドシートに交換先商品の情報を登録すれば自動で RDS にデータが登録される仕組みを作りました。また、その管理ツールの追加方法のマニュアルや、デバッグ用に交換ログまわりを調査する際のマニュアルも作成しました。

リリース後お問い合わせがいくつか届いたのでそれに基づいて説明ページを設けたり、よくある質問の増設を行いました。

#### 使用した技術

- フロントエンド：Vue.js(2), Nuxt.js(2), Vuetify, TypeScript, Figma
- バックエンド：Python(3.8), Django(3), MySQL(8)
- インフラ：AWS, Docker, Redis

### 漫画全巻ドットコムの開発（2021 年 7 月〜2022 年 10 月）

#### 概要

株式会社 TORICO（当時マザーズ上場）で漫画全巻ドットコムの開発に 1 年従事し、新規機能開発、不具合調整、リプレース業務を行いました。
（リプレース業務は元々 PHP + Smarty で書かれていたものを脆弱性や保守性の観点から Django(Python) + Nuxt.js(TypeScript)でリプレースするプロジェクト）

#### 実績、業務内容

- 電子商品一覧ページ、トップページ、お問い合わせページのリニューアル
- 商品詳細モーダル、並び替えボタン、領収書ダウンロード機能の開発
- 不具合調整、パフォーマンス・チューニング

#### 詳細な内容、発揮したバリュー

リプレース業務では PHP のコードをそのまま書き写すのではなく、マーケティングチームにヒアリングした上で必要な機能、改善点を洗い出し、よりユーザーが使いやすいプロダクトにするよう心がけました。非機能要件では SQL のパフォーマンスチューニングや抽象化（リファクタリング）を意識し、単体テスト、統合テストも書きました。バックエンドのみならずフロントエンドも一貫して開発し、SEO 対策や UIUX も意識して開発しました。電子商品詳細モーダルは PHP のときには無かったが、ユーザビリティの観点で自分で考えて実装し、商品の並び替えボタン等も設置しました。
自分がリプレイスした後、電子無料ページの検索順位が上昇したことにより流入数が大幅に上昇し、電子商品の売上が年次で平均 1.3 倍に増加しました。

#### 使用技術

- フロントエンド：Vue.js(2), Nuxt.js(2), TypeScript
- バックエンド：Python(3.8), Django(3), MySQL(5.8)
- インフラ：AWS, Docker, Redis

## 株式会社アクセルユニバース（2020 年 10 月〜2021 年 6 月 インターン）

### 業務内容

- 社内研修（リーダブルコード、Web の仕組み、DB 設計、オブジェクト指向、データベースとアルゴリズム、Rails チュートリアル、AWS（VPC、EC2、S3））
- Ruby on Rails での API の開発（giftee の e 街ギフト）
- 社内業務効率化ツールの開発
- AWS 保守
- 軽微な UI、バグ改修
- SEO コンサル、内部対策

### 使用技術

- フロントエンド：Vue.js(2), Javascript
- バックエンド：Ruby on Rails(6), MySQL(8)
- インフラ：AWS
