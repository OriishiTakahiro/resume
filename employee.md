## 株式会社hacomono

2025.02~現在 

<details>
<summary>転職の経緯</summary>

アイデミーでは開発をリードする形でビジネス視点を持ってアプリケーションからインフラまで幅広く携わることができました。  
その中で自分のコアとしたい領域はインフラだということを再認識し、もう一度深く突き詰めたいと考えるようになりました。  
ただ自分の技術的指向性と当時のアイデミーの事業フェイズに不一致が見え始めてきたこともあり、転職を決意しました。  
hacomonoでは事業拡大のボトルネックとなるインフラの課題があり新しいプラットフォーム基盤の模索をしており、事業とともにインフラを成長させていくフェイズを体験できると確信して入社しました。  
</details>

### プラットフォームグループ

hacomonoを支えるプラットフォーム基盤の開発と運用を担っています。

## 株式会社アイデミー

2022.07~2025.01


<details>
<summary>転職の経緯</summary>

DMM.comではインフラの構築と運用について深く身につけることができました。  
一方でビジネスとしての視点やアプリケーション開発者としての視点がないと感じ、直接顧客と対話してアプリケーションからインフラまで広く携われる環境を求めて転職いたしました。
</details>

### 新規事業部 Lab Bankグループ

2023.09~2025.01

Lab Bankの開発チームが新しく創設された新規事業部に移転し、引き続き開発を進めていました。  
引き続きインフラの開発と運用をメインとして、実装機能の設計やタスク管理などのPMも担っていました。  

極めて機密性の高いデータを扱うマルチテナントSaaSであるため、テナント分離性を非常に高く保っていました。
しかし運用していく中でインフラコストが嵩んでしまい、粗利率を圧迫していたためアーキテクチャを変更してコスト削減を実施しました。

また蓄積したデータを用いて機械学習モデルの学習や予測を行う機能を開発するなど、優先度や実装コストを比較しながら開発を進めていました。

- インフラ
    - ECS
    - Aurora
    - Private Link
    - Cognito
    - AWS Batch
- バックエンド
    - Node.js (fastify)
    - GraphQL
    - FastAPI
    - zod
    - Knex.js
- 機械学習
    - FastAPI
    - RightGBM
    - polars
    - SQLAlchemy
    - Pydantic

### Modeloy Engineering事業部

2022.07~2023.06

DX伴走サービス[Modeloy](https://www.modeloy.ai)にエンジニアとし従事していました。  
お客様と要件を擦り合わせながらインフラストラクチャ~フロントエンドまでフルスタックに開発していました。  
- AWS ECS
- React.js
- Python
- SQL Server

化学業界向けのデータ蓄積・活用SaaSである[Lab Bank](https://labbank.jp)の開発に従事しました。  
プロダクトの要件定義から画面デザイン、インフラ設計、開発から進捗管理までを行いました。  
初めてのプロダクトデザインやチームのリードを経験しました。  
マルチテナントSaaSの構築、DBは顧客が管理しアプリケーションは自社が管理するという特殊な形態、顧客が自由にDBスキーマを構築できるという柔軟性の高さなど、技術的挑戦も多かったです。  
インフラ運用を最適化するためのTerraformの設計については[Zennにも投稿](https://zenn.dev/aidemy/articles/eaed2ad54b55ca)しております。  

また引き続きModeloyで他案件への技術的支援や商談への出席なども同時に行っていました。  
- インフラ
    - ECS
    - Aurora
    - Private Link
    - Cognito
- バックエンド
    - Node.js (fastify)
    - GraphQL

## 合同会社DMM.com

2020.04~2022.06

<details>
<summary>就職の経緯</summary>

大学院の研究でネットワークに携わり、コードを書くだけでなくインフラを設計・構築することに興味を持ちました。  
その後インターンシップを通じてクラウドインフラやIaCという概念を知り、より興味を深めました。  
非常に大きなトラフィックを扱っており、事業内容もユニークなDMM.comへの入社を決めました。  
</details>

### 検索アプリケーショングループ

2020.04~2022.06

3ヶ月の新卒研修の後、社内の複数サービスが利用する検索エンジンを開発・運用するチームを希望し、希望通り配属されました。  
モチベーションは技術的に学びが多く、挑戦し甲斐のある環境だと感じたからです。  
- 大規模なインフラストラクチャに携わりたかったこと
- ステートフルなKubernetes基盤という挑戦的な環境に魅力を感じたこと

オンプレで稼働していた検索システムをAWSに移行するプロジェクトでした。  
私が参画した時点では半分程度移行が済んでおり、残り半分の移行に携わりました。  
社会人として初めて仕事に携わる中で、以下のような貴重な経験をさせていただきました。  
- Kubernetesのコンポーネントの設計・構築
- 試験の実施
- ドキュメントの更新や検索を止めずにオンプレ-\>AWSへ移行する手順の設計・実施

特に移行手順に関してはダウンタイムが発生するとお客様への影響が大きいため、他部署の方と綿密にやり取りをしながら念入りに設計しました。  
DNSでの向き先を切り替えつつ、DNSキャッシュの時間を考慮したり、すぐに切り戻しを可能な設計にしました。  

[プロジェクトの記事](https://inside.dmm.com/entry/2021/01/19/DMMSearchAWS)

またゼロベースでの新規開発もさせていただきました。  
Terraformでのインフラ、Kubernetesの各リソースの開発に一気通貫で携わらせていただきました。  
IRSAやIAMなどセキュアな環境を実現する手法やベストプラクティスを身につけることができました。  
また障害の影響範囲が大きいシステムだったので、堅牢性を保証するための様々なノウハウを習得しました。  
- オートスケールの挙動を調査するためにOSSのコードリーディング
- Locustを用いた負荷試験を実施
- LitmusChaosを用いたカオスエンジニアリングの実施
- Datadogの監視