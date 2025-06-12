# Rails 8 Study

Ruby on Rails学習用リポジトリ

## 環境
- Ruby 3.x
- Rails 8.x
- MySQL
- Docker

## 参考書籍
- Ruby on Rails アプリケーションプログラミング（Rails 7をベースに Rails 8で実装）

## セットアップ手順
1. 必要な環境変数を`.env`に設定します。例:

   ```env
   RAILS_PORT=3001
   MYSQL_POOT=3306
   MYSQL_DB=sample_app
   MYSQL_USER=root
   MYSQL_ROOT_PASSWORD=password
   ```

2. Dockerイメージをビルドします。

   ```sh
   docker compose build
   ```

3. コンテナを起動します。

   ```sh
   docker compose up
   ```

4. ブラウザで `http://localhost:$RAILS_PORT` にアクセスして動作を確認します。
