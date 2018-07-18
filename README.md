# php-docker-sample

- 本リポジトリをgit cloneして取得
- ./setup.sh を実行してtodolistのリポジトリを取得
- docker-compose buildを実行
- docker-compose upを実行
- もう一つのコンソールを立ち上げる
- ./db_setup.sh でデータベースのmigrationを実行
- ブラウザで http://localhost:8080/ を表示

npm installで失敗する時は、
npm ERR! pngquant-bin@4.0.0 postinstall: `node lib/install.js`
apt-get install libpng-dev を行った後、
npm installを行う

