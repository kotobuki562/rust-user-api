パッケージインストール

```
cargo run
```

ユーザー登録・更新

```exqmple
curl -X PUT -H 'Content-Type:application/json' -D - localhost:3030/users/1 -d '{"id": 1, "name": "名前"}'
```

ユーザー全取得

```
curl -D - localhost:3030/users
```

ユーザー ID 指定で取得

```
curl -D - localhost:3030/users/1
```
