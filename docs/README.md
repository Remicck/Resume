# 職務経歴書

## 基本情報

|key|value|
|---|---|
|氏名|川合 理規|
|生年月日| 1990-04-21|
|GitHub| [Remicck \| GitHub)](https://github.com/Remicck)|
|Twitter| [@Ricckn](https://twitter.com/Ricckn) |
|note|[Riki Kawai \| note](https://note.com/remicck/) |
|Zenn|[Remicck \| Zenn](https://zenn.dev/remicck)|

---

## 職務要約

シニアレベルのフルスタックエンジニアであり、プロジェクトマネージャーとしても豊富な経験を持つ。  
主にPHP, MySQL, TypeScript, React.js, Next.jsを用いた開発を担当。これまでに2億円規模のプロジェクトの管理を行い、最大で12名のチームを率いた。  
2020年からエンジニアチームのマネージャーを務め、マネジメント業務として評価・採用面の拡充や、社内ソフトウェアのOSS版のPdMも経験。AWSとLinux環境での運用管理、IAM管理業務にも精通している。

---

## 保有スキル

- 言語
  - 日本語
  - 英語（リーディング少々）
- 資格
  - 自動車免許（普通、ゴールド）

---

## 技術スタック

### 言語

- HTML
- CSS / SCSS
- JavaScript
- TypeScript
- PHP
- GoLang（少しだけ）
- C#（少しだけ）
- Node.js
- Swift（iOSハイブリッドアプリでのPush通知受信関係）
- SQL等
  - MySQL
  - PostgreSQL
  - MongoDB
  - ※CRM開発で想定されるRDBのSQLはおおむね手書き可能
    - SQLの高速化についても経験多数
    - 障害対応についても複数経験あり

### フレームワーク・その他

- FrontEnd
  - React
  - Next.js
  - Vue.js（v2を少しだけ）
  - Vuetfy（少しだけ）
  - Tauri
  - jQuery
- BackEnd
  - Laravel
  - FuelPHP
  - .NETASP
  - Supabase
  - Firebase

### その他スキル

- ServerSide
  - Linuxサーバー（Ubuntu, Amazon Linux, CentOS, RaspberryPi自宅サーバー）
    - Apache
    - nginx
    - pm2
    - MySQL
    - Postgresql（Row Level Securityを含む）
    - ElasticSearch
    - BullMQ（Task Queueing）
  - Docker
  - KVM
  - AWS ECS（App, Worker(BullMQ), Gotenberg）
  - Metabase
- Network
  - 移転に伴う社内ネットワーク構築
  - VPN設定
  - 自宅サーバー関係（Raspberry Pi、Windows）
  - 社内開発サーバー整備（KVM）
- PM
  - 2億規模のWebアプリケーション受託開発のPM（平時5人/月、最大12人）
  - その他CRM導入に伴う要件定義からメンバーの管理周り、折衝ごと全般
- Management
  - エンジニアチーム マネージャー職歴（2020〜）
  - 中途採用（エンジニア採用）
- PdM
  - 社内ソフトウェアのOSS版PdM（2020〜2022）
  - 社内新規開発アプリケーションPdM（2022～）
- コンサルティング
  - プロセスマップの作成
  - 要求機能一覧の作成
- 営業（※小規模の会社に居たため）
  - プリセールス
  - 契約書関係（NDA、基本契約、個別契約、業務提携契約周りの経験）
- Other
  - AWS上にWebアプリケーションの実行環境を構築
    - EC2 ＋ RDS ＋ Redis ＋ OpenSearchを使ったReact.js ＋ PHP ＋ MySQL環境
    - Lambdaを使ったS3 → Lambda → SessionManager → EC2 → CSVインポートによる基幹システム連携
    - Amazon SNSを使ったiOS向けPush通知環境実装（PHPからのPush通知実装）
  - Firebase Cloud Messagingを用いたWebPush実装
  - IAM管理業務
  - iOSの開発、アプリ更新
  - Tauriを用いたWindowsアプリケーションの開発（[Remicck/noshi_generator](https://github.com/Remicck/noshi_generator)）

---

## 職務経歴詳細

### Thinkingreed株式会社（2018/04 〜 現在）

- 2018.04 ~ : システムエンジニア
- 2020.04 ~ : エンジニアリングチームマネージャー
- 2022.04 ~ : エンジニアリングチーム 製品開発グループ マネージャー

#### F-RevoCRM導入（複数実績）

- 職務：PM
- 業務：要件定義、設計、実装、テスト、保守

下に記述するの業種に対するF-RevoCRM導入のための要件定義、設計、開発を担当する。  
おおむね週1回の定例会を通し、2〜4か月間のプロジェクトを担当。

- 中古厨房機器販売会社、SFA導入（PM：軽微なカスタマイズ開発）
- 中堅建材会社SFAツール、SalesForceリプレイス案件（SubPM：CSV基幹システム連携、Office365カレンダー連携、独自画面実装）
- 学習塾ユーザー向け授業管理ツール（PM：学習塾向けの講師・生徒・保護者向けポータルサイトの導入）
- 一般財団法人架電業務向けCRMカスタマイズ開発（PM：Amazon ConnectとのClick To Call連携を含む導入）
- 携帯販売会社SFA業務向けCRM導入支援（SubPM：設定、カスタマイズ開発の実施）
- クラウドCTI販売ベンダー様向け、SFA導入（PM：軽微なカスタマイズ開発）

どの会社様についても、既存業務を大きく変えることなくシステム導入を成功させた。

#### F-RevoCRMをバックエンドに用いた大規模SFA開発

- 職務：PM
- 業務：要件定義、設計、実装、テスト、保守

食品販売会社SFAツールリプレイス案件として、提案のプレゼンから簡易的な業務コンサルティングによるプロセスマップの作成、その他PMとして予算管理・人員管理・進捗管理を行い2023年5月にリリース。  
現在も追加機能開発として設計・開発を行いつつ、保守対応を行う。

2000人の営業員が全員毎日利用しており、日々入力を行っている。

役割はPMで、開発した範囲は以下の範囲のみとなる。

- 初期のフロントエンドリポジトリの設計、プロジェクト作成
- iOSアプリケーションのPush通知受取部分
- Amazon S3 ＋ Lambda + CSV連携の連携基盤の実装
- Azure ADを用いたSSOログイン認証部分と、そのAPI実装
- React.js部分の一部の画面の実装（Chart.jsを用いたグラフ表示、ハーフモーダルUIを用いた商品詳細画面）
- AWS上に展開されるインフラ構築のネットワーク部分を除いたすべての範囲
- 一部APIの実装＋不具合修正
- SQL高速化作業全般
- その他、SFAアプリケーション内画面の実装とバグ取り作業等を実施

PMとしての要件定義期間、コンサル業務にも従事。

- （受注前）100ページ超の提案資料作成
- （受注前）2時間の提案と、Figmaを用いたモックアップ、デモの披露
- 業務理解のための営業同行（※計4回）
- プロセスマップの作成
- 要求機能一覧の作成

#### OSS版F-RevoCRMのPdM

- 職務：PdM
- 業務：実装、テスト、PRレビュー

GitHub上に展開されているF-RevoCRMのIssue管理、PR管理を実施。  
個人としてもPRを作成し、部分的に修正を実施するとともに、3か月に1回のリリースについて主導。

#### 自社製品開発

- 職務：PdM以下すべて
- 業務：企画、設計、実装、マーケティング、ディレクション

新製品のPoC向け実装の実施中。  
アーキテクチャの選定から、PoCに必要な範囲の選定、実装を行う。

使用技術は以下。

- Next.js(TypeScript)
- TailwindCSS
- MUI(Material UI)
- Supabase
- Prisma.js
- Jest
- Vercel

#### 自社製品開発（CRM連動ポータル開発）

- 職務：PdM以下すべて
- 業務：企画、設計、実装

CRMの情報をエンドのお客様に部分的に閲覧させることが可能な「カスタマーポータル」の、新バージョン実装。  
Shadcn＋Tailwindcssを用いたデザインの実装、axiosでのAPIのつなぎ込みを実現。

使用技術は以下。

- Next.js(TypeScript)
- NextAuth（Credential Providerにて、外部APIで認証）
- TailwindCSS
- Shadcn
- Jest
- F-RevoCRM（新REST APIと、PHP, MySQLによる追加API実装）
- Docker

### 株式会社Threerings（2014 年 05 月〜 2018 年 03 月）

#### Amazon Red Shiftを用いたID-POSデータの分析システム開発

- 職務：ディレクター
- 業務：要件定義、設計、テスト

IDPosを用いた分析サービスの開発に、PMOとして従事  
各種サービス連携やインポート、ワイヤーフレーム＋レポーティングの表示形式についての知見を得る。

#### 新規事業のWebサービス開発

- 職務：サブPM
- 業務：要検定義、設計、開発（フロント）、テスト、リリース、保守

- インフラをAWSに、PHP, MySQLを用いたWebサービスの主にフロント側を開発として参加
- 事業立ち上げの初期からサブPMとしても活動し、新規事業としての提案力や要件定義、タスク管理、スケジューリングなどを経験
- 実装面ではデザインカンプのHTML組み込み＋バックエンドとのつなぎ込みの実装
- 一部FuelPHPを用いたバックエンド側の開発も兼任

#### 光コラボサービスの企画・開発

- 職務：サブPM＋ソフトウェアエンジニア
- 業務：要検定義、設計、開発（フロント）、テスト、リリース、保守

- 光コラボのサービスとして、会員特典部分の専用Webサイトの実装
- 動画アーカイブ機能の実装として、ログインユーザーのみが閲覧可能な動画配信Webサービスを開発
- Vimeoのドメイン認証を利用

#### Office365 Outlookカレンダー連携、カレンダーアプリケーション実装

- 職務：サブPM＋ソフトウェアエンジニア
- 業務：要検定義、設計、開発（フロント）、テスト、リリース、保守

- .NET ASP（C#）を利用し、Office365のカレンダーを、リソースカレンダーベースにして表示するアプリケーションの実装

#### 星取表作成

- 職務：PM＋ソフトウェアエンジニア
- 業務：要検定義、設計、開発（フロント）、テスト、リリース、保守

- 商品の納品実績等取得可能なデータベースから、特定領域の星取表を生成するツールの実装

使用技術は以下。

- FuelPHP
- MySQL
- jQuery
- Sass
- AWS Windows Server(IIS)

### 業務外

#### Image Data Extractor - AI統合データ抽出プラットフォーム（2024/06 〜 現在）

- 職務：PdM・フルスタックエンジニア
- 業務：アーキテクチャ設計、実装

**プロジェクト概要**  
画像からAIを活用してデータを自動抽出し、外部システムにWebhook送信する法人向けBtoB SaaSプラットフォーム。レシート、名刺、各種帳票を撮影するだけで、事前定義したJSON形式のデータに変換・自動送信する業務自動化システム。

**主要技術スタック**
- **フロントエンド**: Next.js 15 (App Router) + React 19 + TypeScript (strict mode)
- **バックエンド**: Next.js API Routes + Prisma ORM + PostgreSQL
- **認証**: NextAuth.js (マルチテナント対応)
- **AI統合**: Google GenAI API (Gemini)
- **UI/UX**: Tailwind CSS 4 + Shadcn/ui
- **開発環境**: Docker + pnpm + Biome (リンター/フォーマッター)
- **テスト**: Playwright (E2E)

**実装した主要機能**
- マルチテナント対応認証システム（階層ロール管理：SYSTEM_ADMIN/ADMIN/USER）
- リアルタイム画像解析・データ抽出機能（Google GenAI API統合）
- 柔軟なテンプレート作成システム（JSONスキーマエディタ）
- Webhook連携（外部システム自動送信・リトライ機能）
- 管理者向けダッシュボード（テナント統計・ユーザー管理）
- データエクスポート機能（CSV出力）
- 権限ベースアクセス制御（リソースレベル認可）

**開発体制・技術的挑戦**
- チーム規模：1名（+ Claude Code）
- 最新技術スタック採用（Next.js 15, React 19リリース直後に導入）
- TypeScript strict mode + Biome導入による高品質コード維持
- マルチテナント設計でのデータ分離・セキュリティ確保
- AI API統合における精度向上・エラーハンドリング最適化
- Prisma ORM + PostgreSQL JSON型活用による柔軟なスキーマ設計

**成果・学習内容**
- 最新Next.js App Router完全対応アプリケーション構築
- AI統合Webアプリケーションの企画・設計・実装経験
- マルチテナントSaaSアーキテクチャの設計・実装スキル習得
- モダンフロントエンド技術（React 19, TypeScript strict mode）の実践活用
- Biome等の最新開発ツール導入による開発効率向上

#### QRコードスキャナー ＋ 実績取り込みDB

- 職務：PM
- 業務：要検定義、設計、開発、テスト、リリース、保守

- キーエンス製Android型QRコードスキャナーを使い、伝票番号を取得、各種入力を行いDBに保存するアプリケーションの実装
- 住宅向け建材製造工場にて利用中
- ダッシュボード機能も作成し、現在はダッシュボード画面を全画面にして工場内のモニターに表示、現在の実績を表示している

- 使用技術：Next.js + TypeScript + Prisma.js + MySQL + Amazon Lightsail + Mackerel
