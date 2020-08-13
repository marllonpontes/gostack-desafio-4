<div align="center">
  <img alt="GoStack"
    src="https://storage.googleapis.com/golden-wind/bootcamp-gostack/header-desafios.png"
  />
</div>

<h2 align="center">
   Desafio 04: Conceitos do React Native
</h2>

<p align="center">
  <img alt="language version" src="https://img.shields.io/badge/React%20Native-v_0.62.1-339933?logo=react">
  <img alt="language version" src="https://img.shields.io/badge/Yarn-v_1.22.4-2C8EBB?logo=Yarn">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/marllonpontes/gostack-desafio-4">
</p>

<hr/>

<p align="center">
  <a href="#rocket-sobre-o-desafio">Sobre o desafio</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-funcionalidades">Funcionalidades</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#computer-execute-o-projeto">Execute o projeto</a>
</p>

## :rocket: Sobre o desafio

Nesse desafio, você deve criar uma aplicação para treinar o que você aprendeu até agora no React Native!

Agora você deve continuar desenvolvendo a aplicação que irá armazenar repositórios do seu portfólio, que você já desenvolveu o backend utilizando o Node.js, e no último desafio em ReactJS.

## 🔥 Funcionalidades

Neste projeto, as rotas foram implementadas usando métodos HTTP:
- **`Listar os repositórios da sua API`**: Deve ser capaz de criar uma lista de todos os repositórios que estão cadastrados na sua API com os campos **title**, **techs** e número de curtidas seguindo o padrão `${repository.likes} curtidas`, apenas alterando o número para ser dinâmico.

- **`Curtir um repositório listado da API`**: Deve ser capaz de curtir um item na sua API através de um botão com o texto **Curtir** e deve atualizar o número de likes na listagem no mobile.

## ⚙ Tecnologias

* __React Native__
* Yarn
* Jest

## :computer: Execute o projeto

Clone este repositório:

```bash
$ git clone https://github.com/marllonpontes/gostack-desafio-4
```

Mova-se para diretório da aplicação:

```bash
$ cd gostack-desafio-4
```

Para instalar as dependências execute:

```bash
yarn install
```

E para iniciar o app:

```bash
react-native run-android
```