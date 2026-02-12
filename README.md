# EC2 Web Server Practice

公開サイト：
https://mugi-cloud.github.io/ec2-web-practice/

AWS EC2上にWebサーバーを構築し、GitHub Pagesで公開した実践プロジェクトです。

## 構成

- Cloud：AWS
- Service：EC2 (t3.micro)
- OS：Amazon Linux 2023
- Web Server：Apache
- Region：ap-northeast-1 (Tokyo)

## 実施内容

1. EC2インスタンス作成
2. セキュリティグループ設定（HTTP許可）
3. Apacheインストール・起動
4. index.html作成
5. GitHubへアップロード
6. GitHub Pagesで公開

## 使用コマンド（一部）

sudo yum install httpd -y
sudo systemctl start httpd
sudo systemctl enable httpd

## 公開URL

https://mugi-cloud.github.io/ec2-web-practice/

## 学習ポイント

- EC2の基本操作
- Linuxコマンド操作
- Webサーバー構築の流れ
- クラウド環境での公開までの一連の手順

## 作成者

Mugi

## 感想
初めてAWS EC2を使用し、Linuxコマンドでサーバー構築を行いました。これまではクラウドの利用経験がなく、課金面への不安もありましたが、実際に操作することでしくみを理解することができました。
自分でwebサイトを公開できたことで、クラウドサービスへの理解が深まり、学習の楽しさを実感しました。
また、インスタンス停止することで不要な課金を防げることを学び、クラウドのコスト管理が重要であることも理解しました。

## 今後やる予定のこと

・独自ドメイン設定  
・HTTPS化（SSL）  
・Nginx構築  
