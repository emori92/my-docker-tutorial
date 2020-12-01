## はじめに
練習で作成したDockerfileをまとめたリポジトリです。

## Dockerfileの種類
- sample-dockerfile: Dockerfileのサンプル
- ubuntu-ping: ubuntuにpingをインストールしたイメージ
- httpd: データボリュームを紐づけたapacheイメージ
- web: port80未開放のapache。rproxyをリバースプロキシとして利用する。
- rproxy: リバースプロキシとしてngixnを利用したイメージ。webとセットで利用する。
- my-db: MySQLを利用したイメージ。phpmyadmin、Wordpress、Redmineを起動できるようにします。
- compose-test: 初めてのdocker-compose。ubuntuを起動する。
- compose-6-3-1: 参考書籍の6章3節1項の、apacheをdocker-composeで起動する。
- compose-6-3-2: 参考書籍の6章3節2項の、rproxyとwebで作成したDockerfileからdocker-compose。
- compose-6-4: 参考書籍の6章4節で、docker-composeのみでMySQL、myphpadmin、Wordpress、Redmineを構築する。

## 参考書籍
- [自宅ではじめるDocker入門](https://www.kohgakusha.co.jp/books/detail/978-4-7775-2072-5)
