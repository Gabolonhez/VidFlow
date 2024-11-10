
# VidFlow

O VidFlow é uma plataforma de compartilhamento de vídeos.

![Captura de tela do Vidflow.](./vidflow.png)

## 🔨 Funcionalidades
- [x] `Busca de vídeos`: Vídeos são buscados por uma API
- [x] `Modos`: Possui modo escuro e modo claro
- [X] `Botôes`: Possuem botões interativos

## ✔️ Tecnologias utilizadas

- HTML, CSS e JavaScript
- JSON Server

## Link do Figma

[Acesse o Figma do Vidflow](https://www.figma.com/file/UbPLETdOLAuQk6G09HUtnZ/VidFlow-%7C-Acessibilidade?node-id=0%3A1&mode=dev)

## 👨‍💻 Colaboradores

| [Gabriel Bolonhez Felipe](https://github.com/Gabolonhez) |

## 🛠️ Abrir e rodar o projeto

Após baixar ou clonar o projeto deste repositório, você precisa ter o [Node.js](https://nodejs.org/) e o [`json-server`](https://www.npmjs.com/package/json-server) instalados.

Caso não tenha o `json-server` instalado globalmente, execute o seguinte comando:

```bash
npm install -g json-server@0.17.4
```

Com o Node.js e o `json-server` instalados, execute o seguinte comando para disponibilizar a API local de vídeos:

```bash
json-server --watch backend/videos.json
```

Em seguida, abra o `index.html` no navegador e o VidFlow já pode ser visualizado!
