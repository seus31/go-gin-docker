# Golang Gin Docker Sample


## Overview

Golang + Gin + Dockerでの開発環境の構築


## Requirement

Docker


## Usage

- `git clone`をしてソースコードを取得する
- `docker-compose buid`を実行する
- `docker-compose run --rm app air init`を実行し、`.air.yoml`を作成するする
- `docker-compose run --rm app go mod tidy`を実行して依存関係を解決する
- `docker-compose up -d`で環境を立ち上げる
- `curl http://localhost:3000/ping` でアクセス確認する


## Author

[SEUS31](https://github.com/seus31)


## Licence

[MIT](https://github.com/tcnksm/tool/blob/master/LICENCE)
