簡易的な Python3 と Jupyter による開発環境です。
以下のライブラリを使用可能です。

* numpy 
* pandas 
* matplotlib 
* pytorch

## 利用手順

* リポジトリをクローン

```
$ git clone -b develop https://github.com/hasujapan/python3-docker.git
$ cd python3-docker
```

* コンテナをビルド、起動

```
$ docker-compose up --build
```

* Jupyter 接続確認

```
http://localhost:8888/
```