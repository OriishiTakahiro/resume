# resume

## Contact

連絡をいただける際にはTwitterにお願いします
- [Twitter](https://twitter.com/hetare70914)
- [ブログ](https://takahiro0914.hatenablog.com)
- [GitHub](https://github.com/OriishiTakahiro)

## 技術スタック

### インフラストラクチャ

- AWSでの開発・運用 (2020.07~)
    - VPC - EKSまで一気通貫で構築
    - EKS, MSK, ECS, EC2, ALB, Route53
    - Locustを用いた負荷試験
    - LitmusChaosを用いたカオスエンジニアリング
- TerraformでのIaC (2020.07~2022.06)
    - AWSのインフラ構築
- Datadogの監視 (2020.07~2022.06)
    - Kubernetes基盤への導入
    - ログの設計・実装
    - アラートの設計・実装
    - ダッシュボードの設計・実装
- GCPでの開発・運用 (2020.11~2022.06)
    - GKE上で稼働するアプリケーションの整備
    - Datadogでの監視の整備
    - locustを用いた負荷試験
- AtlasDB (2021.8)
    - セキュアなネットワーク設計
    - 環境構築

### フロントエンド

- ReactJSでのアプリケーション開発 (2022.07~)

### バックエンド

- Scalaでのアプリケーション開発 (2020.07~2022.06)
- NodeJSでのアプリケーション開発 (2020.07~2022.06)
- Pythonでのアプリケーション開発 (2022.07~)

### 開発環境

- CircleCI
- Docker

## 職歴

## 株式会社アイデミー
2022.07~

転職のモチベーションは機能開発ができる環境に身を置きたかったこと、技術領域が偏ってしまっており、幅を広げたかったことです。
また直接接しているお客様に価値を提供して喜んでもらえる環境であることも大きな魅力でした。

DX伴走サービスにエンジニアとして携わっています。
お客様と要件を擦り合わせながらインフラストラクチャ~フロントエンドまでフルスタックに開発しております。

## 株式会社アイデミー (業務委託)
2020.11~2022.06

### 業務内容

- ログや監視の設計と構築
- CosmoDBからAtlasDBへの移行に向けての調査や設計

[プロジェクトの記事](https://alms.dev/entry/2022/03/01/120000)


## 合同会社DMM.com
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
