<h3 align="center">
  Aplicação para criação gerenciamento de carrinho de compras: Projeto REACT NATIVE
</h3>

<p align="center">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/ejcosta12/studying-relations-database?style=flat-square">
  <img alt="javaScript" src="https://img.shields.io/github/languages/top/ejcosta12/studying-relations-database">
  <img alt="Size" src="https://img.shields.io/github/repo-size/ejcosta12/studying-relations-database">
</p>

## Sobre
Versão mobile de aplicação para adicionar produtos em carrinho de compras com manipulação da quantidade de cada produto e atualização do preço total. Neste sistema foram abordados Async Storage e Context API.

### Tecnologias

- React Native
- Axios
- Styled Components

### Scripts CLI

#### yarn
Instalação de todas as dependências necessárias.

#### yarn json-server server.json -p 3333
Este projeto foi criado com o Json Server para fornecimento de dados Fake API. A configuração default está no endereço localhost, caso vá utilizar outro endereço IP para
testes no ambiente de desenvolvimento utilize o comando:
```yarn json-server server.json -p 3333 -H 192.168.0.2```
192.168.0.2 é um endereço de exemplo. Será necessário alterar a baseURL de acesso em src\services\api.ts.

#### yarn android OU yarn android OU yarn start
Dependendo da vizualização em dispositivo físico ou emulador, utilize um dos comandos.
