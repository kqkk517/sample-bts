# sample-bts

### 使い方

- 以下コマンドを実行

```bash
$ docker-compose build
$ docker-compose pull
$ docker-compose up -d
```

- アクセス URL：https://localhost:3000

### Github チーム開発手順メモ

```bash
$ git remote add upstream https://github.com/kqkk517/sample-bts.git
$ git fetch upstream
$ git checkout -b develop upstream/develop
$ git branch
$ git push origin develop
$ git remote remove upstream

$ git add -A
$ git commit -m "Initial"
$ git push --set-upstream origin develop
```
