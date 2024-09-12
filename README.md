Aqui está a tradução do texto para o português:

# Tutorial Javascript do SDK de Reprodução Web

Este repositório contém o código-fonte para o [Guia do SDK de Reprodução Web](https://developer.spotify.com/documentation/web-playback-sdk/guide/).

## Usando suas próprias credenciais

Você precisará registrar seu aplicativo e obter suas próprias credenciais no
[Dashboard do Spotify para Desenvolvedores](https://developer.spotify.com/dashboard/)

Para isso, acesse o seu Dashboard do Spotify para Desenvolvedores, crie sua
aplicação e registre o seguinte URI de callback:

`http://localhost:3000/auth/callback`

Depois de criar o aplicativo, crie um arquivo chamado `.env` na pasta raiz
do repositório com suas credenciais do Spotify:

```bash
SPOTIFY_CLIENT_ID='meu_client_id'
SPOTIFY_CLIENT_SECRET='meu_client_secret'
```

## Instalação

Esses exemplos rodam no Node.js. No
[site](http://www.nodejs.org/download/) você pode encontrar instruções sobre como
instalá-lo.

Uma vez instalado, clone o repositório e instale as dependências executando:

```bash
npm install
```

## Executando o exemplo

Inicie tanto o cliente quanto o servidor com o seguinte comando:

```bash
npm run dev
```

O aplicativo React iniciará em `http://localhost:3000`