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
主にPHP, MySQL, TypeScript, React.js, Next.jsを用いた開発を担当。これまでに1億円規模のプロジェクトの管理を行い、最大で12名のチームを率いた。  
2020年からエンジニアチームのマネージャーを務め、マネジメント業務として評価・採用面の拡充や、社内ソフトウェアのOSS版のPdMも経験。AWSとLinux環境での運用管理、IAM管理業務にも精通している。

---

## 保有スキル

- 言語
  - 日本語
  - 英語（リーディング少々）
- 資格
  - 自動車免許（普通）

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
  - Postgresql
  - MongoDB

### フレームワーク・その他

- frontend
  - React.js
  - Next.js
  - Vue.js（v2を少しだけ）
  - Vuetfy（少しだけ）
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
  - Docker
  - KVM
- Network
  - 移転に伴う社内ネットワーク構築
  - VPN設定
  - 自宅サーバー関係（Raspberry Pi、Windows）
  - 社内開発サーバー整備（KVM）
- PM
  - 1億規模のWebアプリケーション受託開発のPM（平時5人/月、最大12人）
- Management
  - エンジニアチーム マネージャー職歴（2020～）
- PdM
  - 社内ソフトウェアのOSS版PdM（2020～2022）
- Other
  - AWS上にWebアプリケーションの実行環境を構築
    - EC2 ＋ RDS ＋ Redis ＋ OpenSearchを使ったReact.js ＋ PHP ＋ MySQL環境
    - Lambdaを使ったS3 → Lambda → SessionManager → EC2 → CSVインポートによる機関システム連携
    - Amazon SNSを使ったiOS向けPush通知環境実装（PHPからのPush通知実装）
  - IAM管理業務
  - iOSの開発、アプリ更新

---

## 職務経歴詳細

### Thinkingreed株式会社（2018/04 〜 現在）

#### F-RevoCRM導入（複数実績）

- 職務：PM
- 業務：要件定義、設計、実装、テスト、保守

下に記述するの業種に対するF-RevoCRM導入のための要件定義、設計、開発を担当する。  
概ね週1回の定例会を通し、2～4ヶ月間のプロジェクトを担当

- 中古厨房機器販売会社、SFA導入（PM：軽微なカスタマイズ開発）
- 中堅建材会社SFAツール、SalesForceリプレイス案件（SubPM：CSV基幹システム連携、Office365カレンダー連携、独自画面実装）
- 学習塾ユーザー向け授業管理ツール（PM：学習塾向けの講師・生徒・保護者向けポータルサイトの導入）
- 一般財団法人向け架電業務向けF-RevoCRMカスタマイズ開発（PM：Amazon ConnectとのClick To Call連携を含む導入）
- 携帯販売会社様向けF-RevoCRM導入支援（SubPM：設定、カスタマイズ開発の実施）
- クラウドCTI販売ベンダー様向け、SFA導入（PM：軽微なカスタマイズ開発）

どの会社様についても、既存業務を大きく変えることなくシステム導入を成功させた。

#### F-RevoCRMをバックエンドに用いた大規模SFA開発

- 職務：PM
- 業務：要件定義、設計、実装、テスト、保守

某大手食品販売会社様向けSFAツールリプレイス案件として、提案のプレゼンから簡易的な業務コンサルティングによるプロセスマップの作成、その他PMとして予算管理・人員管理・進捗管理を行い2023年5月にリリース。  
現在も追加機能開発として設計・開発を行いつつ、保守対応を行う。

600人の営業員が全員毎日利用しており、日々入力を行っている。  
最終的に2000人弱のユーザーが対象となる予定。

役割はPMで、開発した範囲は以下の範囲のみとなる。
- 初期のプロジェクト作成
- iOSアプリケーションのPush通知部分
- Amazon S3 ＋ Lambda + CSV連携のレン計器盤の実装
- Azure ADを用いたSSOログイン印象部分と、そのAPI実装
- React.js部分の一部の画面の実装（Chart.jsを用いたグラフ表示、ハーフモーダルUIを用いた商品詳細画面）
- AWS上に展開されるインフラ構築のネットワーク部分を除いたすべての範囲

#### OSS版F-RevoCRMのPdM

- 職務：PdM
- 業務：実装、テスト、PRレビュー

GitHUb上に展開されているF-RevoCRMのIssue管理、PR管理を実施。  
個人としてもPRを作成し、部分的に修正を実施するとともに、3ヶ月に1回のリリースについて主導。

### 株式会社Threerings（2014 年 05 月～ 2018 年 03 月）

#### Amazon Red Shiftを用いたID-POSデータの分析システム開発

- 職務：ディレクター
- 業務：要件定義、設計、テスト

#### 新規事業のWebサービス開発

- 職務：サブPM
- 業務：要検定義、設計、開発（フロント）、テスト、リリース、保守

- インフラをAWSに、PHP, MySQLを用いたWebサービスの主にフロント側を開発として参加
- 事業立ち上げの初期からサブPMとしても活動し、新規事業としての提案力や要件定義、タスク管理、スケジューリングなどを経験
- 実装面ではデザインカンプのHTML組み込み＋バックエンドとのつなぎ込みの実装
- 一部FuelPHPを用いたバックエンド側の開発も兼任

#### 光コラボサービスの企画・開発

- 職務：サブPM
- 業務：要検定義、設計、開発（フロント）、テスト、リリース、保守

- 光コラボのサービスとして、会員特典部分の専用Webサイトの実装
- 動画アーカイブ機能の実装として、ログインユーザーのみが閲覧可能な動画配信Webサービスを開発

### 業務外

#### QRコードスキャナー ＋ 実績取り込みDB

- 職務：PM
- 業務：要検定義、設計、開発、テスト、リリース、保守

- キーエンス製Android型QRコードスキャナーを使い、伝票番号を取得、各種入力を行いDBに保存するアプリケーションの実装
- 住宅向け建材製造工場にて利用中
- ダッシュボード機能も作成し、現在はダッシュボード画面を全画面にして工場内のモニターに表示、現在の実績を表示している

- 使用技術：Next.js + TypeScript + Prisma.js + MySQL + Amazon Lightsail + Mackerel
