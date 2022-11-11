# node-chat
# How to Run
1. Clone this repository.
2. Create a `nn-chat-db` directory one level up
3. Start Docker and run the server with the following commands.
```bash
docker-compose up -d
docker-compose exec app bash
yarn install
node index.js
```

# 起動方法
1. このリポジトリをクローン
2. ひとつ上の階層のディレクトリに `nn-chat-db` ディレクトリを作成
3. 以下のコマンドで Docker を起動し、サーバーを実行
```bash
docker-compose up -d
docker-compose exec app bash
yarn install
node index.js
```