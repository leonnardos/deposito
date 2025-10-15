# Depósito Interior App

Este projeto é uma aplicação web para gerenciamento de depósitos de fichas em um clube de poker. A aplicação permite que os usuários realizem depósitos utilizando códigos PIX, proporcionando uma experiência de usuário fluida e interativa.

## Estrutura do Projeto

O projeto é organizado da seguinte forma:

```
deposito-interior-app
├── src
│   ├── index.html          # Página principal da aplicação
│   ├── css
│   │   └── styles.css      # Estilos CSS da aplicação
│   ├── js
│   │   ├── app.js          # Script principal da aplicação
│   │   └── api.js          # Funções para chamadas à API
│   └── assets
│       └── images          # Imagens utilizadas na aplicação
├── server
│   ├── app.js              # Ponto de entrada do servidor
│   ├── routes
│   │   └── api.js          # Definição das rotas da API
│   ├── controllers
│   │   └── depositController.js # Lógica de controle para depósitos
│   └── services
│       └── pixService.js    # Lógica de serviço para códigos PIX
├── package.json             # Configuração do npm
└── package-lock.json        # Informações sobre as versões das dependências
```

## Instalação

1. Clone o repositório:
   ```
   git clone <URL_DO_REPOSITORIO>
   ```
2. Navegue até o diretório do projeto:
   ```
   cd deposito-interior-app
   ```
3. Instale as dependências:
   ```
   npm install
   ```

## Uso

Para iniciar a aplicação, execute o seguinte comando:
```
npm start
```

A aplicação estará disponível em `http://localhost:3000`.

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou pull requests.

## Licença

Este projeto está licenciado sob a MIT License. Veja o arquivo LICENSE para mais detalhes.