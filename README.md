## はじめに
練習で作成したDockerfileをまとめたリポジトリです。
今後、Docker composeのコマンドまで行う予定です。

## Dockerfileの種類
.
├── httpd
├── my-db
├── rproxy
├── sample-dockerfile
├── ubuntu-ping
└── web

- httpd: データボリュームを紐づけたapacheイメージ
- my-db: MySQLを利用したイメージ
- rproxy: リバースプロキシとしてngixnを利用したイメージ。webとセットで利用する。
- sapmle-dockerfile: Dockerfileのサンプル
- ubuntu-ping: ubuntuにpingをインストールしたイメージ
- web: port80未開放のapache。rproxyをリバースプロキシとして利用する。

## 参考書籍
- [自宅ではじめるDocker入門](https://www.kohgakusha.co.jp/books/detail/978-4-7775-2072-5)
