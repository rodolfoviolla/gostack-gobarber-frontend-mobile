<h1 align="center">
  <img
     alt="logotipo do GoBarber"
     title="GoBarber Logo"
     src="./assets/README-logo.png"
     width=200
     height=200
   />
</h1>
<h3 align="center">
  Controle a agenda de sua barbearia com estilo 🧔
</h3>
<p align="center">(Aplicação desenvolvida durante o Bootcamp GoStack da Rocketseat)</p>
<p align="center">
  <br />
  
  <a href="#">
    <img alt="React Native" src="https://img.shields.io/badge/-ReactNative-61DAFB?style=flat&logo=React&logoColor=white">
  </a>
  
  <a href="#">
    <img alt="TypeScript" src="https://img.shields.io/badge/-TypeScript-007acc?style=flat&logo=TypeScript">
  </a>
  
  <a href="https://github.com/rodolfoviolla/gostack-gobarber-frontend-mobile/blob/master/LICENSE">
    <img alt="GitHub license" src="https://img.shields.io/github/license/rodolfoviolla/gostack-gobarber-frontend-mobile">
  </a>
</p>

<p align="center">
  <a href="#features">Features</a> •
  <a href="#pr%C3%A9-requisitos">Pré-requisitos</a> • 
  <a href="#rodar-a-aplica%C3%A7%C3%A3o-localmente">Rodar a aplicação localmente</a> • 
  <a href="#tecnologias">Tecnologias</a> • 
  <a href="#autor">Autor</a> • 
  <a href="#licen%C3%A7a">Licença</a>
</p>

<p align="center">
  <img width="378" height="672" src="./assets/AppDemoGif.gif" alt="Demo">
</p>

<p align="center">
  <img width="290" height="515" src="./assets/01-Splash.png" alt="Splash">
  <img width="290" height="515" src="./assets/02-Login.png" alt="Login">
  <img width="290" height="515" src="./assets/03-SignUp.png" alt="SignUp">
</p>

### Features

- [X] Cadastro de usuário
 - [X] Cadastro de novo usuário
 - [ ] Recuperação senha de usuário já cadastrado (Em desenvolvimento...)
 - [X] Alteração de avatar e dados do perfil
- [x] Login / Logout
 - [X] Acesso à funcionalidades de criação e consulta apenas por usuário logado
- [X] Consulta de agendamentos apenas do usuário logado

### Pré-requisitos

Você vai precisar ter instalado em sua máquina as seguintes ferramentas:
[Git](https://git-scm.com) e [Yarn](https://classic.yarnpkg.com/pt-BR/)
É bom ter um editor para trabalhar com o código como [VSCode](https://code.visualstudio.com/)

Além disso, serão necessárias algumas instalações, como o Android Studio. [Neste documento](https://react-native.rocketseat.dev/), preparado pela Rocketseat, estão os passos necessários.

### Rodar a aplicação localmente

Para rodar a aplicação, você precisa rodar o [back-end em Node.js](https://github.com/rodolfoviolla/gostack-gobarber-backend) localmente na porta 3333

Após rodar o back-end, siga os seguintes passos:

```bash
# Clone do repositório do front-end mobile (fora da pasta do back-end)
$ git clone <https://github.com/rodolfoviolla/gostack-gobarber-frontend-mobile>

# Acesse a pasta do projeto no teminal/cmd
$ cd gostack-gobarber-frontend-mobile

# Instale as dependências
$ yarn

# Conecte um celular/emulador Android e realize o buid executando
$ yarn android
```
ou
```bash
# Conecte um celular/emulador iOS e realize o buid executando
$ yarn ios
```
Para rodar a aplicação após o build
```bash
# Execute a aplicação em modo de desenvolvimento
$ yarn start
```

### Tecnologias

As seguintes ferramentas foram usadas na construção do projeto:

- [React Native](https://reactnative.dev/)
- [TypeScript](https://www.typescriptlang.org/)

### Autor
---

<p>
  <a href="#">
    <img src="https://avatars1.githubusercontent.com/u/64096832?s=460&u=b785643ea39e67bb0f05c9f4d43e478b7029c807&v=4" height="100px" width="100px" style="border-radius:50px" alt=""/>
    <br />
    <sub><b>Rodolfo Della Violla</b></sub>
  </a>

  <p>
    <a href="https://www.linkedin.com/in/rodolfoviolla/">
      <img alt="LinkedIn" src="https://img.shields.io/badge/-LinkedIn-%237159c1?style=flat&logo=linkedin">
    </a>
    <a href="https://twitter.com/RodolfoViolla">
      <img alt="Twitter" src="https://img.shields.io/badge/-Twitter-%237159c1?style=flat&logo=twitter">
    </a>
    <a href="mailto:rodolfo.violla@gmail.com">
      <img alt="Gmail" src="https://img.shields.io/badge/-Email-%237159c1?style=flat&logo=gmail">
    </a>
  </p>
</p>

## Licença

Este projeto esta sobe a licença [MIT](./LICENSE.md).
