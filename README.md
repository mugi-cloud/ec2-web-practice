# AWS EC2 Web Server Project

## 概要
AWS EC2上にWebサーバー（Apache）を構築し、インターネットからアクセス可能なWebページを公開しました。  
クラウド環境でのサーバー構築から公開までの一連の流れを実践的に学ぶことを目的としたプロジェクトです。

公開サイト：
https://mugi-cloud.github.io/ec2-web-practice/

---

## 構成
- Cloud：AWS
- Service：EC2（t3.micro）
- OS：Amazon Linux 2023
- Web Server：Apache
- Region：ap-northeast-1（Tokyo）

---

## 実装内容
1. EC2インスタンス作成
2. セキュリティグループ設定（HTTP許可）
3. Apacheのインストールおよび起動
4. index.html作成・配置
5. Elastic IPを設定し固定IPで公開
6. GitHubにコードをアップロード
7. GitHub Pagesで成果物を公開

---

## 工夫した点
- **実際に手を動かして環境構築を行った点**
  - 単なる学習ではなく、Webページ公開まで実施

- **構成を整理し、第三者が理解しやすい形でまとめた点**
  - サイト・READMEともに情報を整理

- **コストを意識した運用**
  - 使用後はEC2を停止
  - Elastic IPを解放し不要な課金を防止

---

## 学習したこと
- EC2の基本操作（起動・接続・停止）
- Linuxコマンド操作
- Webサーバー構築の流れ
- クラウド環境での公開手順
- コスト管理の重要性

---

## 今後の改善
- HTTPS化（SSL対応）
- S3と連携した構成への拡張
- CloudFormationを用いた構成の自動化

---

## 作成者
Mugi
