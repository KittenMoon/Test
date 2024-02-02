```
# install dependencies
pnpm i

# you need the api to run wish importer and wish tally
git clone https://github.com/MadeBaruna/paimon-moe-api
cd paimon-moe-api
docker-compose up -d

# run in dev mode
cp .env.example .env
vi .env
pnpm dev

# export as production static site
pnpm build
```

# License

[MIT](https://github.com/MadeBaruna/paimon-moe/blob/main/LICENSE)

This project is not affiliated with HoYoVerse.
Genshin Impact, game content and materials are trademarks and copyrights of HoYoVerse.
