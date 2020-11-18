<h3 align="center">
    <img alt="Logo" title="#logo" width="300px" src=".github/logo.png">
    <br><br>
    <b>Recycle! help the environment!</b> 
</h3>

<p align="center">
  <a href="https://rocketseat.com.br">
    <img alt="Made by Rocketseat" src="https://img.shields.io/badge/made%20by-Rocketseat-%237519C1">
  </a>
  <a>
  <img alt="License" src="https://img.shields.io/github/license/gabrielnogueiralt/ecoleta?color=%237519C1">
</p>

# Index

- [About](#about)
- [Documentation](#cocumentation)
- [Technologies used](#technologies-used)
- [How to use](#how-to-use)
- [How to contribute](#how-to-contribute)

<a id="about"></a>

## :bookmark: About

The <strong>Ecoleta</strong> is a Web and Mobile application to help people find collection points for recycling.

This application was built on the trail <strong>Booster</strong> of <strong>Next Level Week</strong> distributed by [Rocketseat](https://rocketseat.com.br/). The idea of creating an application focused on the environment arose from the coincidence of the course date and the date of the <strong>environment week</strong>

<a id="documentation"></a>

## :books: Documentation

To reinforce some concepts and record commands that are difficult to remember I made a small **[DOCUMENTATION](DOCUMENTATION.md)** to help anyone who is starting with **TypeScript**, **Node**, **ReactJS** e **React Native**.

<a id="technologies-used"></a>

## :rocket: Technologies used

The project was developed using the following technologies

- [TypeScript](https://www.typescriptlang.org/)
- [Node.js](https://nodejs.org/en/)
- [ReactJS](https://reactjs.org/)
- [React Native](https://reactnative.dev/)

<a id="how-to-use"></a>

## :fire: How to use

- ### **Prerequisites**

  - It is ** necessary ** to have the **[Node.js](https://nodejs.org/en/)** installed on the machine
  - Also, it is ** necessary ** to have a package manager **[NPM](https://www.npmjs.com/)** or **[Yarn](https://yarnpkg.com/)**.
  - Finally, it is ** essential ** to have the **[Expo](https://expo.io/)** globally installed on the machine

1. Make a clone :

```sh
  $ git clone https://github.com/gabrielnogueiralt/ecoleta.git
```

2. Running the Application:

```sh
  # Install the dependencies
  $ npm install

  ## Create the database
  $ cd server
  $ npm run knex:migrate
  $ npm run knex:seed

  # Start the API
  $ npm run dev

  # Launch the web application
  $ cd web
  $ npm start

  # Launch the mobile application
  $ cd mobile
  $ npm start
```

<a id="how-to-contribute"></a>

## :recycle: How to contribute

- Fork this repository,
- Create a branch with your feature: `git checkout -b my-feature`
- Commit your changes: `git commit -m 'feat: My new feature'`
- Push your branch: `git push origin my-feature`

## :mortar_board: Who taught?

The classes were taught by **[Mayk Brito]** in classes of **Next Level Week**.

## :memo: License

This project is under the MIT license. See the archive [LICENSE](LICENSE.md) for more details.

---

<h4 align="center">
    Done with 💜 by <a href="https://www.linkedin.com/in/gabriel-n-132451122/" target="_blank">Gabriel Nogueira</a>
</h4>
