# laravel-todo-app

## 開発環境

[こちらの記事](https://qiita.com/ucan-lab/items/17c806973e69792ada99)を参考に作成。

### 起動

```
docker-compose up -d
open http://127.0.0.1:10080
```

#### Laravelビルドインサーバーを使いたい場合

```
docker-compose exec app php artisan serve --host 0.0.0.0
open http://127.0.0.1:18000
```

#### MySQLに接続

```
docker-compose exec db bash -c 'mysql -uroot -p${MYSQL_PASSWORD} ${MYSQL_DATABASE}'
```
