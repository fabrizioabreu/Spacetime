  ## D-1 Tecnologias
- [x] Mobile
	- [x] Expo	https://docs.expo.dev/
	- [x] NativeWind
	- [x] ESLint + Prettier Tailwind

  ## D-2 Layout
- [x] Mobile
	- [x] Configuração da fonte
  - [x] Blur background
  - [x] Stripes
  - [x] Seção Hero
	- [x] Copyright

## D-3 Autenticação & Upload
- [x] Mobile
	- [x] Instalação do expo-auth-session
	- [x] Configuração Github OAuth (Expo)
	- [x] Obtendo Github code mobile
	- [x] Salvando token no secure store
	- [x] Navegando usuário
	- [x] Utilizando Expo Router

## D-4 Upload & Nova memória
- [x] Mobile
	- [x] Definindo layout das rotas
	- [x] Personalizando rota inicial do app
	- [x] Página de nova memória

  ## Getting Started
```bash
npm run start
npm run android
```

## Instalar Android Studio
- https://react-native.rocketseat.dev/android/windows
- https://react-native.rocketseat.dev/virtual-devices/android-emulator#iniciando-o-emulador

  ## Bibliotecas utilizadas
```sh
# https://www.nativewind.dev/quick-starts/expo
npm i nativewind
npm i tailwindcss -D
npx tailwindcss init

npm i eslint @rocketseat/eslint-config -D
npm i prettier-plugin-tailwindcss -D

# Instalando fontes
npx expo install @expo-google-fonts/roboto @expo-google-fonts/bai-jamjuree expo-font

# Instalando Biblioteca para poder importar svg
# https://docs.expo.dev/ui-programming/using-svgs/
npx expo install react-native-svg
npm i -D react-native-svg-transformer

# Limpar o cache
npx expo start --clear

# Autenticação OAuth no Mobile
# https://docs.expo.dev/versions/latest/sdk/auth-session/
npx expo install expo-auth-session expo-crypto

npm i axios

# Forma de trabalhar com cache no mobile
# https://docs.expo.dev/versions/latest/sdk/securestore/
npx expo install expo-secure-store

# Funcionalidade de rotas igual ao NextJs
# https://expo.github.io/router/docs/#getting-started
npx expo install expo-router react-native-safe-area-context react-native-screens expo-linking expo-constants expo-status-bar

```