<h1 align="center">
	BE THE HERO
</h1>

<p align="center">
	<a href="https://pt-br.reactjs.org/">
		<img src="https://img.shields.io/static/v1?label=react&message=front-end&color=61DAFB&style=flat&logo=REACT" />	
	</a>
	<a href="https://reactnative.dev/">
		<img src="https://img.shields.io/static/v1?label=react-native&message=mobile&color=61DAFB&style=flat&logo=REACT" />
	</a>
	<a href="https://nodejs.org/en/">
		<img src="https://img.shields.io/static/v1?label=node%20js&message=back-end&color=76d04b&style=flat&logo=node.js" />
	</a>
	<a href="https://developer.mozilla.org/pt-BR/docs/Aprender/JavaScript">
		<img src="https://img.shields.io/static/v1?label=javascript&message=language&color=f7df1e&style=flat&logo=JavaScript" />
	</a>
	<br/>
	<a href="https://rocketseat.com.br/">
		<img src="https://img.shields.io/static/v1?label=made%20by&message=rocketseat&color=7159c1&style=for-the-badge"/>	
	</a>
	<br/>
</p>

> Status do Projeto: Concluido :heavy_check_mark:

### Tópicos
- [Descrição do projeto](#clipboard-descrição-do-projeto)
- [Pré-requisitos](#point_right-pré-requisitos)
- [Como rodar a aplicacão](#arrow_forward-como-rodar-a-aplicacão)
- [Database](#floppy_disk-database)
- [Licença](#memo-licença)


## :clipboard: Descrição do projeto

O projeto <strong>Be The Hero</strong> é uma aplicação Web e Mobile que ajuda ong's a divulgarem situações que elas precisam de arrecadações.
Desta formas as pessoas podem visualizar e contriuir ajudam alguém.

Aplicação foi desenvolvida na <strong>OmniStack 11</strong> organizada pela :rocket: [Rocketseat](https://rocketseat.com.br/).

## :point_right: Pré-requisitos

:warning: [Node](https://nodejs.org/en/download/)

:warning: [Yarn](https://classic.yarnpkg.com/pt-BR/docs/install/#windows-stable) 

## :arrow_forward: Como rodar a aplicacão
No terminal, clone o projeto:
```
git clone https://github.com/Ariosmaia/be-the-hero.git
```

Entre na pasta de cada projeto:

<br/>

 :gear: <strong>Back-end</strong>
 
```
cd backend-node
```
   - Instale as dependencias:
```
npm install
```
  - Execute a aplicação
```
npm run dev
```
<br/>

 :computer:<strong>Web</strong>
	
```
cd frontend-react
```
   - Instale as dependencias:
```
yarn
```
  - Execute a aplicação
```
yarn start
```
<br/>

 :iphone: <strong>Mobile</strong>
	
 > :exclamation: Para rodar a aplicação mobile é necessário ter o expo instaldo globalmente:
 > [Ver documentação](https://docs.expo.io/)
 >
 > ```
 > npm install expo-cli --global
 > ```
 
```
cd mobile-react-native
```
   - Instale as dependencias:
```
yarn
```
  - Execute a aplicação
```
yarn start
```

## :floppy_disk: Database
 - Banco de dados SQLite
 - Rodar as migratios para gerar o bando de dados automaticamente:
 ```
 npm run knex:migrate
 ```
 
 ## :memo: Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](https://github.com/Ariosmaia/be-the-hero/blob/master/LICENSE) para mais detalhes.
