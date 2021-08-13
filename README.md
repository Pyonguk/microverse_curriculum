![](https://img.shields.io/badge/Microverse-blueviolet)

# Curriculum Mobile Version

> First 2 sections of the curriculum.

![screenshot](./app_screenshot.png)

**Since is a mobile version please change the adaptive design view width bellow 800px.**

## Built With

- HTML & CSS
- Linters
- Node.js
- JSON

## Live Demo

[Live Demo Link](https://pyonguk.github.io/microverse_curriculum/)


## Getting Started

To get a local copy up and running follow these steps.

### Prerequisites

Download and Install Node.js [here](https://nodejs.org/es/).

### Setup

Set-up HTML&CSS linters at GitHub Action and at your Local [here](https://github.com/microverseinc/linters-config/tree/master/html-css).

### Install & Usage

#### [Webhint](https://webhint.io/)

A customizable linting tool that helps you improve your site's accessibility, speed, cross-browser compatibility, and more by checking your code for best practices and common errors.

1. Run
   ```
   npm install --save-dev hint@6.x
   ```
   *not sure how to use npm? Read [this](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm).*
2. Copy [.hintrc](.hintrc) to the root directory of your project.
3. **Do not make any changes in config files - they represent style guidelines that you share with your team - which is a group of all Microverse students.**
   - If you think that change is necessary - open a [Pull Request in this repository](../README.md#contributing) and let your code reviewer know about it.
4. Run
   ```
   npx hint .
   ```
5. Fix validation errors.

#### [Stylelint](https://stylelint.io/)

A mighty, modern linter that helps you avoid errors and enforce conventions in your styles.

1. Run

   ```
   npm install --save-dev stylelint@13.x stylelint-scss@3.x stylelint-config-standard@21.x stylelint-csstree-validator@1.x
   ```

   *not sure how to use npm? Read [this](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm).*

2. Copy [.stylelintrc.json](./.stylelintrc.json) to the root directory of your project.
3. **Do not make any changes in config files - they represent style guidelines that you share with your team - which is a group of all Microverse students.**
   - If you think that change is necessary - open a [Pull Request in this repository](../README.md#contributing) and let your code reviewer know about it.
4. Run `npx stylelint "**/*.{css,scss}"` on the root of your directory of your project.
5. Fix linter errors.
6. **IMPORTANT NOTE**: feel free to research [auto-correct options for Stylelint](https://stylelint.io/user-guide/cli#autofixing-errors) if you get a flood of errors but keep in mind that correcting style errors manually will help you to make a habit of writing a clean code!

## Authors

👤 **Author1**

- GitHub: [@Pyonguk](https://github.com/Pyonguk)

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](../../issues/).

## Show your support

Give a ⭐️ if you like this project!

## Acknowledgments

- Thanks to [Microverse](https://github.com/microverseinc) for the readme template and linters config.

## 📝 License

This project is [MIT](./MIT.md) licensed.

