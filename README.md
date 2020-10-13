# [Web] Happy
[![GitHub Workflow Status](https://img.shields.io/github/workflow/status/DiegoVictor/happy-web/CI?logo=github&style=flat-square)](https://github.com/DiegoVictor/happy-web/actions)
[![react](https://img.shields.io/badge/reactjs-16.13.1-61dafb?style=flat-square&logo=react)](https://reactjs.org/)
[![styled-components](https://img.shields.io/badge/styled_components-5.2.0-db7b86?style=flat-square&logo=styled-components)](https://styled-components.com/)
[![eslint](https://img.shields.io/badge/eslint-6.8.0-4b32c3?style=flat-square&logo=eslint)](https://eslint.org/)
[![airbnb-style](https://flat.badgen.net/badge/style-guide/airbnb/ff5a5f?icon=airbnb)](https://github.com/airbnb/javascript)
[![jest](https://img.shields.io/badge/jest-24.9.0-brightgreen?style=flat-square&logo=jest)](https://jestjs.io/)
[![coverage](https://img.shields.io/codecov/c/gh/DiegoVictor/happy-web?logo=codecov&style=flat-square)](https://codecov.io/gh/DiegoVictor/happy-web)
[![MIT License](https://img.shields.io/badge/license-MIT-green?style=flat-square)](https://github.com/DiegoVictor/happy-web/blob/master/LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)<br>

This web version allow users to look for orphanages near from yourself.

## Table of Contents
* [Screenshots](#screenshots)
* [Installing](#installing)
* [Usage](#usage)
* [Running the tests](#running-the-tests)
  * [Coverage Report](#coverage-report)

# Screenshots
Click to expand.<br>
<img src="https://raw.githubusercontent.com/DiegoVictor/happy-web/master/screenshots/landing.png" width="49%"/>
<img src="https://raw.githubusercontent.com/DiegoVictor/happy-web/master/screenshots/map.png" width="49%"/>

# Installing
Easy peasy lemon squeezy:
```
$ yarn
```
Or:
```
$ npm install
```
> Was installed and configured the [`eslint`](https://eslint.org/) and [`prettier`](https://prettier.io/) to keep the code clean and patterned.

# Usage
To start the app run:
```
$ yarn start
```
Or:
```
npm run start
```

# Running the tests
[Jest](https://jestjs.io) was the choice to test the app, to run:
```
$ yarn test
```
Or:
```
$ npm run test
```

## Coverage Report
To generate/update the coverage report:
```
$ yarn test:coverage
```
Or:
```
$ npm run test:coverage
```
> You can see the coverage report inside `tests/coverage`.
