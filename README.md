# hoppscotch deploy

## Deploy hoppscotch to your own server

```bash
## clone repo
git clone https://github.com/BRAVO68WEB/hoppscotch-deploy.git

## cd to repo
cd hoppscotch-deploy

## deploy
docker compose up -d

## run migrations
docker exec -it hoppscotch-depoy-hoppscotch-1 /bin/sh
>  pnpx prisma migrate deploy
```

### Docs

- [Deploy Docs](https://docs.hoppscotch.io/documentation/self-host/community-edition/getting-started)

### License

MIT
