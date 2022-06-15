# apache-vim-docker

## 基本コマンド一覧

```
########イメージの操作########
#イメージ一覧を表示
docker images

#Docker Hubからイメージを取得
docker pull {イメージ名}

#Dockerfileからイメージを作成
docker build {Dockerfileのパス}

#イメージを削除
docker rmi {イメージID}


########コンテナの操作########
#コンテナ一覧を表示
docker ps -a

#コンテナを作成
docker create {イメージ名}

#コンテナを起動
docker start {コンテナ名} 

#コンテナを停止
docker stop {コンテナ名}

#コンテナを削除
docker rm {コンテナ名} 

#イメージを取得、コンテナを作成、コンテナを起動
docker run {イメージ名}


########その他の操作########
#コンテナにログイン
docker exec -it {コンテナ名} bash
```
