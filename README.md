baby-steps-ubuntu-env_on_docker
====

「Pythonで学ぶ強化学習」のスクリプト実行用環境のDockerfileです.  
OS : mac Mojave 10.14.4  

## Description

構成

- Dockerfile : Dockerfile
- into_container/ : コンテナ内にコピーするファイルを入れるディレクトリ
- build.sh : DockerfileをDockerimageにbuildするスクリプト
- run.sh : Dockerimageからコンテナを起動するスクリプト

各種バージョン
- python==3.5
- tensorflow==1.12.0
- 他の詳細は into_container/requirements.txtを参照

## Version
latest : baby-steps-env:1.0

1.0 &emsp; 2019/04/08 新規作成  

## Install

### dockerのインストールと設定

### リポジトリをクローン
```git
https://github.com/kinziro/baby-steps-mac-env_on_docker.git
```

## Usage

### 設定
1. run.shの「'localdir'」を自分のリポジトリを置いているディレクトリに変更

### コンテナ内のユーザー
- user : developer
- password : P@ssw0rd

### ビルド
```build.sh
$ sh build.sh
```

### コンテナ起動
```run.sh
$ sh run.sh
```

## Contribution

## Licence

## Author

