---
id: setup
title: Set Up React Application
sidebar_label: Set Up React application
---

## Prerequisites

1.  Yarn Package Manager

- This guide will use `yarn` for package management.
- [Yarn installation for Mac](https://yarnpkg.com/lang/en/docs/install/#mac-stable)
- [Yarn installation for Windows](https://yarnpkg.com/lang/en/docs/install/#windows-stable)

2.  A modern browser like Chrome or Firefox with React DevTools installed.

- [Firefox React DevTools](https://addons.mozilla.org/en-US/firefox/addon/react-devtools/)
- [Chrome React DevTools](https://chrome.google.com/webstore/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi?hl=en)

3. Knowledge of JavaScript and ES6 syntax is helpful

## Create React Application

`create-react-app`, is a way to quickly create the foundation for modern, React applications and is officially supported by React maintainers.

Create a new React project with `create-react-app` by running the following command in your terminal:

```
yarn create react-app exploration-app
```

This will create a folder named `exploration-app`in the directory that you run the above command in. Inside of the `exploration-app` directory will be a fully-functional, bare bones React application.

You should be able to view the React app you just created by typing the following commands which switches the `exploration-app` directory and then starts the server.

```
cd exploration-app
yarn start
```

_Explore the Create-React-App Docs_ [here](https://facebook.github.io/create-react-app/)
