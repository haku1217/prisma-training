
Prisma2のmigrate版のお試し

```sh
npm install
docker-compose up -d
npx prisma migrate save --name init --experimental 
npx prisma migrate up --experimental 
npx prisma generate
```

```sh
npm run script
```