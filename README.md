## はじめに
練習で作成したDockerfileをまとめたリポジトリです。

## Dockerfileの種類
- sapmle-dockerfile: Dockerfileのサンプル
- ubuntu-ping: ubuntuにpingをインストールしたイメージ
- httpd: データボリュームを紐づけたapacheイメージ
- web: port80未開放のapache。rproxyをリバースプロキシとして利用する。
- rproxy: リバースプロキシとしてngixnを利用したイメージ。webとセットで利用する。
- my-db: MySQLを利用したイメージ。phpmyadmin、Wordpress、Redmineを起動できるようにします。

## 参考書籍
- [自宅ではじめるDocker入門](https://www.kohgakusha.co.jp/books/detail/978-4-7775-2072-5)
