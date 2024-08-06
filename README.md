# YjsBasedSimpleGraphCollab
# 沖電気のSA環境の作成

# codespacesの起動

# zipファイルのアップロード

```
# upload後
$ unzip 


# y-websocketのセットアップ・実行（サーバ）

CLIにて以下のコマンドを実行する。

```bash
# y-websocketのセットアップ
$ git clone --depth=1 https://github.com/yjs/y-websocket.git
$ cd y-websocket
$ npm install
# DBディレクトリの作成
$ export YPERSISTENCE=./dbDir
$ npm run start
```
いかが表示されていればOK

<img width="479" alt="2024-08-05_14h04_12" src="https://github.com/user-attachments/assets/dd3b2c73-41c3-4b7f-a3c3-8a230f010424">

# SAクライアントの実行

CLIにて以下を実行（Gitlabへの要アクセス権）ディレクトリ内にzipを準備

## gitコマンドで取得できる場合

```bach
$ git clone https://analyticspf.yakushite.net/gitlab/SemanticAuthoring/yjs-based-simple-graph.git
$ cd yjs-based-simple-graph
$ npm install
$ npm run start
```

## tar.gzファイルを使用する場合

```bach
$ tar zxvf yjs-based-simple-graph-master.tar.gz
$ cd yjs-based-simple-graph-master
$ npm install
$ npm run start
```

実行後にブラウザを開くかを尋ねられるので開くを選択。選択しても何も表示されないので
アクセスしたURLの末尾に ```/YjsBasedSimpleGraphCollab```を追記してリロードする。

## 例
下記の場合には
http://localhost:3000

以下のURLへアクセスする
https://localhost:3000/YjsBasedSimpleGraphCollab

