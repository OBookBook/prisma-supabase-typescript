# prisma-supabase-typescript

## npm

```shell
npm init
npm i -D typescript @types/node vite-node prisma @prisma/client argon2
npx tsc --init
```

# Tips

## Prisma

```shell
npx prisma init
npx prisma migrate dev --name init
```

## Supabase CLI

```shell
npx supabase init
npx supabase start
npx supabase stop
npx supabase db reset
```

## Docker

```shell
# 全てのコンテナを停止
docker stop $(docker ps -aq)
# 全てのコンテナを削除
docker rm $(docker ps -aq)
# 全てのイメージを削除する
docker rmi $(docker images -q)
# 全てのボリュームを削除する
docker volume rm $(docker volume ls -q)
```
