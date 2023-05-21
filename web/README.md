## D-1 Tecnologias
- [x] Front-end
	- [x] React + Next.js
	- [x] Conceitos
		- [x] Componentes
		- [x] Propriedades
		- [x] Roteamentos
	  - [x] TailwindCSS
	- [x] ESLint + Prettier Tailwind

## D-2 Layout
- [x] Front-end
	- [x] Configuração da fonte
	- [x] Estrutura visual da Home
		- [x] Blur background
		- [x] Stripes
	- [x] Lista de memórias vazia
	- [x] Perfil do uuário
	- [x] Seção Hero
	- [x] Copyright

## D-3 Autenticação & Upload 1/2
- [x] Front-end Web
	- [x] Fluxo de autenticação
	- [x] Configuração Github OAuth
	- [x] Obtendo Github code web

## D-3 Autenticação & Upload 2/2
- [x] Front-end Web
	- [x] Salvando token nos cookies
	- [x] Exibindo perfil do usuário

## D-4 Upload & Nova memória 
- [x] Front-end Web
	- [x] Definindo layout das rotas
	- [x] Rota de logout
	- [x] Página de nova memória
	- [x] Middleware de autenticação

## D-5 Criação e listagem 1/2
- [x] Front-end Web
	- [x] Preview da mídia
	- [x] Criando nova memória

## D-5 Criação e listagem 2/2
- [x] Front-end Web
	- [x] Layout da listagem
	- [x] Buscando memórias da API

## Figma
[Figma](https://www.figma.com/file/cIIfqjsyUedRq0wpZysbR1/C%C3%A1psula-do-tempo-%E2%80%A2-Trilha-Ignite-(Community)?type=design&node-id=1-4&t=jkxUSDfxuQcFy2OD-0)

## Getting Started
First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```
Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.


## Bibliotecas e comandos utilizados
```sh
npm i @rocketseat/eslint-config -D
npm i prettier-plugin-tailwindcss -D 

# Pagote de ícones
npm i lucide-react

npm i axios

# Extrair informações do token
npm i jwt-decode

# Colocar Css no checkbox
# https://github.com/tailwindlabs/tailwindcss-forms
npm install -D @tailwindcss/forms

# facilita buscar o cookie dentro de document.cookie
npm i js-cookie

# Usado para manipular datas
npm i dayjs
```