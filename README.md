<h1 align="center">
    <img alt="BeTheHero" title="#BeTheHero" src=".images/logo.svg" width="250px" />
</h1>

<p align="center">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/vitormiacri/be-the-hero?color=%2304D361">

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/vitormiacri/be-the-hero">
	
  <a href="https://github.com/vitormiacri/be-the-hero/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/vitormiacri/be-the-hero">
  </a>
</p>
<p align="center">
  <a href="https://insomnia.rest/run/?label=Be%20The%20Hero&uri=https%3A%2F%2Fraw.githubusercontent.com%2Fvitormiacri%2Fbe-the-hero%2Fmaster%2Fbackend%2FInsomnia_requests.json" target="_blank"><img src="https://insomnia.rest/images/run.svg" alt="Run in Insomnia"></a>
</p>
<p align="center">
  <a href="#-project">Project</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#rocket-Technologies">Technologies</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-layout">Layout</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-how-to-use">How to use</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-license">License</a>
</p>

## 💻 Projecto

Este projeto foi desenvolvido durante a semana Omnistack da @Rocketseat.
O Be The Hero visa conectar pessoas interessadas em ajudar ONGs.

<h1 align="center">
    <img alt="Login" title="Login" src=".images/login.png" width="500px" />
</h1>

## Tecnologias

Este projeto foi desenvolvido com as seguintes tecnologias:

- [Node.js](https://nodejs.org/en/)
- [React](https://reactjs.org)
- [React Native](https://facebook.github.io/react-native/)
- [Expo](https://expo.io/)

## Como usar

Para clonar e executar este projeto, você precisa ter instalado o [Git](https://git-scm.com), [Node.js][nodejs] + [Yarn][yarn] installed on your computer.

No terminal execute:

### Executar a API

```bash
# Clone este repositório
$ git clone https://github.com/vitormiacri/be-the-hero be-the-hero

# Entre na pasta backend
$ cd be-the-hero/backend

# Instale as dependências
$ yarn install

# Crie o banco de dados
$ yarn knex migrate:latest

# Execute a API
$ yarn dev
```

### Executar o Frontend

```bash
# Entre na pasta frontend
$ cd be-the-hero/frontend

# Instale as dependências
$ yarn install

# Execute o servidor web
$ yarn start
```

## :memo: License

This project is under the MIT license. See the [LICENSE](LICENSE.md) for details.

---

Made with ♥ by Vitor Morelli :wave: [Get in touch!](https://www.linkedin.com/in/vitor-morelli-miacri-5830b431/)

[nodejs]: https://nodejs.org/
[yarn]: https://yarnpkg.com/
[vc]: https://code.visualstudio.com/
[vceditconfig]: https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig
[vceslint]: https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint
[prettier]: https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode
