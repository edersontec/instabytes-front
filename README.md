# InstaBytes (Front-end)

## Índice

- [Sobre o projeto](#sobre-o-projeto)
- [Funcionalidades](#funcionalidades)
- [Tecnologias utilizadas](#tecnologias-utilizadas)
	- [Bibliotecas](#bibliotecas)
- [Pré-requisitos](#pré-requisitos)
- [Como instalar este projeto](#como-instalar-este-projeto)
- [Como usar este projeto](#como-usar-este-projeto)
- [Licença](#licença)
- [Contribuidores](#contribuidores)

## Sobre o projeto

Este projeto é um versão de front-end fornecida durante a Imersão DEV Backend [Alura](https://www.alura.com.br/) feito em Dezembro de 2024. O objetivo deste front-end é consumir a [API](https://github.com/edersontec/instabytes-back) de uma rede social de imagens (intitulado InstaBytes).

## Funcionalidades

- Exibe os posts criados

## Tecnologias utilizadas

- [Node.js](https://nodejs.org/): Ambiente de execução JS no servidor

### Bibliotecas

- [parcel](https://www.npmjs.com/package/parcel): Parcel é um empacotador de aplicações web. [Documentação](https://pt.parceljs.org/)

## Pré-requisitos

- [git](https://git-scm.com/)
- [Node.js e npm](https://nodejs.org/pt)

## Como instalar este projeto

- Clone o repositório: git clone https://github.com/edersontec/instabytes-front.git
- Baixe as dependências: npm install
- Prepare as variáveis de ambiente:
  - O arquivo *env.example* é um arquivo de exemplo para auxiliar na instalação da aplicação, basta preencher as informações
  - Renomeie o arquivo *env.example* para *.env*
  - Altere a variável **API_URL** para indicar a url da API (exemplo: "http://localhost:3000/posts")
- Rode o servidor: npm run dev
- O servidor será iniciado em: http://localhost:8000

## Como usar este projeto

Este front-end é um esboço de rede social de imagens, sua única funcionalidade é exibir os posts criados anteriormente através da API. Acesse o endereço http://localhost:8000 no seu navegador de internet para visualizar os posts criados.

## Licença

Esse projeto está sob licença. Veja o arquivo [LICENÇA](LICENSE) para mais detalhes.

## Contribuidores

Sinta-se livre para para contribuir com o projeto
