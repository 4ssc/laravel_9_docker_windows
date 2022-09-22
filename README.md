# laravel_9_docker_windows
## 環境情報
- Windows 10 Pro 21H2
- Docker 4.12.0 (85629)

```
git clone https://github.com/4ssc/laravel_9_docker_windows.git
```
## 使用方法
### Dockerビルド
```
docker-compose up -d --build
```
### phpコンテナに入る
```
docker compose exec php bash
```
### Laravel 9のインストール
```
composer create-project --prefer-dist "laravel/laravel=9.*" .
```
### 表示確認
http://localhost:8080/

## 参考サイト
https://qiita.com/hinako_n/items/f15646ea548bcdc8ac6c
