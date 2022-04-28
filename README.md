<h1 align="center">
  Eslint/Prettier For Typescript Projects
</h1>

<p align="center">
  <a href="https://www.linkedin.com/in/paulo-henrique-89b148166/"><img alt="Made by" src="https://img.shields.io/badge/made%20by-Paulo%20Henrique-blue"></a>
  <a href="https://github.com/prettier/prettier">
    <img alt="prettier" src="https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square" />
  </a>
  <a href="https://eslint.org/">
    <img alt="eslint" src="https://img.shields.io/badge/code%20lint-eslint-blue" />
  </a>
</p>

## 💻 What it does

This is a setup about linting your typescript code based with Eslint and Prettier.

Eslint is the one which has tons of rules for you to write a javascript code with best practices.

Prettier on the order hand, organize your code as simples as it can leave more organizable and understandable with respect of things order.

### Requirements

- [Node.js](https://nodejs.org/en/)
- [Yarn](https://classic.yarnpkg.com/) or [npm](https://www.npmjs.com/)


## 😏 Eslint 
In project folder run the follow command:
```bash
# Npm users
$ npm run -D @boostedp/eslint-config

# Yarn users
$ yarn add @boostedp/eslint-config -D
```

Create a file .eslintrc.json and add my plugin inside extends array
``` json
{
  "extends": ["@boostedp"]
}
```

After done theses steps go ahead and write 🚀

## 😉 Prettier
In project folder run the follow command:
```bash
# Npm users
$ npm run -D @boostedp/prettier

# Yarn users
$ yarn add @boostedp/prettier -D
```

Create a file .prettierrc.js and add these lines of codes.

```js
const prettierPlugin = require("@bootsedp/prettier");

module.exports = {
  ...prettierPlugin
};
```

## 🧐 Remember

You can override eslint and prettier rules, feel free to do it! Look at these docs.

- [Prettier](https://prettier.io/docs/en/options.html)
- [Eslint](https://eslint.org/docs/rules/)

---

<p align="center">
  Made by <a href="https://www.linkedin.com/in/paulo-henrique-89b148166/">Paulo Henrique</a> 🎸
</p>