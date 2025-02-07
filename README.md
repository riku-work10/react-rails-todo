### git cloneする
```
git clone git@github.com:[自分のURL]
```

### .env.localを作成する  クローンするとなぜか消えてしまうため
```
touch frontend/.env.local
touch backend/.env/local
```

### ビルドする
```
docker compose build
```

### 起動
```
docker compose up
```

### データベース作成
```
docker compose exec back rails db:create
```


###　マイグレーションの実施！　今回のはマイグレーションデータが入っているから
```
docker compose exec back rails db:create
```

### http://localhost:8000とhttp://localhost:3000で動作確認する
