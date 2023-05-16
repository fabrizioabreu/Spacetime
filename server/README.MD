## Tecnologias
- [x] Back-end
	- [x] Node.js
	- [x] TypeScript + TSX
	- [x] Fastify (Framework)
	- [x] ESLint
	- [x] Prisma + SQLite

- [ ] Mobile
	- [ ] Expo
	- [ ] NativeWind
	- [ ] ESLint + Prettier Tailwind

## Getting Started
```bash
npm run dev
```

## Bibliotecas e comandos utilizados
```sh
npm init -y
npm i typescript -D
npm i @types/node -D
npx tsc --init
npm i tsx -D
npm i fastfy
npm install eslint -D
npm i @rocketseat/eslint-config -D
npm i prisma -D
npx prisma init --datasource-provider SQLite
npx prisma migrate dev
# "abre no seu navegador um DB"
npx prisma studio 
# "Acessar o DB de dentro da aplicação"
npm i @prisma/client 
```