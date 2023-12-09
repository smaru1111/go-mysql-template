# go-mysql-template

Go(GORM + Gin) + MySQL の API サーバーのテンプレート

## 使いかた

```
docker-compose up -d
docker-compose exec app sh
```

```
go run main.go
```

postman とかで、`POST localhost:8080/memos` に以下の JSON を送ると、DB に保存される。

```json
{
  "content": "content"
}
```

localhost:8080/memos にアクセスすると、DB の中身が表示される。
