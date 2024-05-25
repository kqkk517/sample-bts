# sample-bts


```bash
git remote add upstream https://github.com/kqkk517/sample-bts.git
git fetch upstream
git checkout -b develop upstream/develop
git branch
git push origin develop
git remote remove upstream

git add -A
git commit -m "Initial"
git push --set-upstream origin develop
```

## how to migration
```bash
docker compose exec api-server bash
cd /opt/api-server 
alembic upgrade head
```
