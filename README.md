### Hi there 👋

<!--
**fugithora812/fugithora812** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->


# スキル

業務で扱った技術を列挙。

Golang, Python, Django, PostgreSQL, Git, Docker, Docker Compose, JavaScript, TypeScript, jQuery,  
Ruby on Rails, MySQL, React, OpenAPI, Github Actions, Google Cloud(GCE, GKE, CloudRun etc..)

<!-- # スキル

## 言語等

Python | Golang | HTML | CSS | JavaScript | jQuery | TypeScript

## フレームワーク等

Flask
Django
Node.js
Express
Travis CI
pybabel
RDB/NoSQL
MySQL | PostgreSQL | SQL Server

## クラウド

- AWS
    - EC2 | VPC

## SaaS/PaaS

- GitHub -->

# 主な業務経歴

## 学術研究支援サービス（2021年５月～）

### プロジェクト概要

すでにサービスインしている、お客様の各種サービス間でデータ連携が十分になされていないという課題があり、その問題解決および、サービス全体の社会的価値向上のためのプロジェクト。目的に照らした具体的な機能提案やOSSを利用したプロトタイプの作成、およびプロジェクトリーダーとしてチームの進捗管理を担当した。

### 使用技術

Golang, Docker, Git, PostgreSQL, jQuery, JavaScript

### 発揮したバリュー

本プロジェクトに配属されてから、Go言語のコードを初めて読むことになったが、持ち前の学習力・調査力を活かし、利用するOSSが現状どのような機能を持っているか把握し、懸念点等とも合わせて報告した。また、お客様と頻繁にコミュニケーションをとることで認識齟齬による手戻りを最小限にした結果、お客様がプロトタイプとして求める機能を予定より２週間ほど早く実装できた。2021年12月～は、関連プロジェクトの状況の変化もあり、プロジェクトリーダーとしてチームの進捗管理も兼務。

## 学術研究データ管理サービスの拡張（2021年１月～４月）

### プロジェクト概要

既に運用が始まっている、学術研究データ管理のためのWebサービスで、顧客満足度を向上させるための機能拡充を目的としたプロジェクト。サービスのソースコードとしてはOSSをベースにし、独自の諸機能を実装。開発体制としてはGM、PLと、私を含めた開発メンバ２人の、計４人による小規模なプロジェクトだった。

### 使用技術

Python, Django, Git, Docker, Docker Compose, TypeScript

### 発揮したバリュー

Python、Docker、Git、TypeScriptについては業務外で学習した経験があったため、配属初日からプロジェクト状況を伺いつつ実装に着手した。経験豊富な先輩との開発ということもあり、私１人では解決できないエラーは質問させていただきながら、コーティングを進めた。当初はDjangoを用いたバックエンドのみの担当という予定だったが、実装スピードの早さを評価いただき、配属３か月目にはEmber.js+TypeScriptを用いたフロントエンドの実装にも、一部関わらせていただいた。

## 採用DXサービス開発チームにジョイン（2022年４月〜）

22年４月より、採用DXサービス「[harutaka](https://harutaka.jp/)」開発チームにジョイン。

### 〜22年８月　Google Cloud上のインフラリソース管理・運用

当時のリードエンジニアの下、Google Cloudで構築したアプリケーションインフラの管理、運用に従事。

- 実施した施策
  - コスト削減の観点から、時間帯ごとの利用実態に沿ってGKEのHPA幅を拡大・縮小させる
  - アプリケーションへの新規機能の実装に伴う、インフラリソースの新規定義（GKE, Cloud Build）  
  他

### 22年８月〜　新規機能開発を担当

- 実施した施策
  - 実施した面接の文字起こしに対し自動的にカテゴリ分類する機能（「構造化議事録」機能）
    - フロントエンドにおける初期実装、およびQA工程におけるバグ対応に従事。(React w/ Typescript)
  - harutakaと外部ライブツールとの連携機能の開発
    - アプリケーションにおける連携機能設計から初期実装までを担当。(Rails)
    - またアプリケーションに既存の解析機能の、連携に伴うロジック改修を実施。(Golang, Python)
  - 「構造化議事録」機能の拡張  
    （リアルタイムに起こした文字起こしだけでなく、過去の録画に対して後から起こした文字起こしにも適用する）
    - PdMとの仕様すり合わせ、およびそれに沿った実装を担当。（Rails）

## 図版収集・構成ツールの開発（2022年12月〜）

Webメディア「[松岡正剛の千夜千冊](https://1000ya.isis.ne.jp/)」編集チームからの依頼で、彼らが使用する図版収集・構成ツールを２人体制で開発。

- https://github.com/fugithora812/ut_pictura_poesis_frontend
- https://github.com/fugithora812/ut_pictura_poesis_apidoc
- （バックエンド側は共同開発者が構築し、合議の上privateリポジトリとしている）

### 2022年12月〜　初期開発

- 実施した施策
  - 利用技術の選定
    - フロントエンドは開発体験・後々のコード保守を鑑みてビルドツールにVite, 言語としてTypescriptを採用。フレームワークは実務で経験があったReactを選択。また、リポジトリ内でのコーディングスタイルをなるべく統一するためeslint, prettierを導入し、Github Actionsと組み合わせてCIが回せるように構築した。
    - また主に共同開発者が作業するバックエンド側のインターフェース整合性を保つため、スキーマ駆動開発を提案・導入。OpenAPIを利用した「apidoc」を構築し、BE/FE間のAPI定義のずれが起こりにくくした。
  - フロントエンド 初期実装
    - react-router-domを利用したページ遷移の実装
    - ツール上に収集した画像をドラッグ＆ドロップで並びかえる機能の実装
    - [Firebase](https://firebase.google.com/?hl=ja)を用いたログイン機能の実装
