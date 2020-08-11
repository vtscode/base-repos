![React Logo](https://github.com/vercel/vercel/blob/master/packages/frameworks/logos/react.svg)

# React Example

This directory is a brief example of a [React](https://reactjs.org/) app with [Serverless Functions](https://vercel.com/docs/v2/serverless-functions/introduction) that can be deployed with Vercel and zero configuration.

## Deploy and setup
- Setup from importing from CRA (create react app) from vercel
[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/import/project?template=https://github.com/vercel/vercel/tree/master/examples/create-react-app-functions)
- Setup package json with newer/lastest version of react, react-dom, react-scripts
- Replace on src folder with your code, when push to `master` or `main` branch, it will automatically building to Continous Integration (CI)
- [Riventus vercel app](https://riventus.vercel.app)
<!-- ## Deploy Your Own
Deploy your own React project, along with Serverless Functions, with Vercel.
_Live Example: https://create-react-app.now-examples.now.sh/_ -->

### How We Created This Example

To get started with React, along with [Serverless Functions](https://vercel.com/docs/v2/serverless-functions/introduction), with Vercel, you can use the [Create-React-App CLI](https://reactjs.org/docs/create-a-new-react-app.html#create-react-app) to initialize the project:

```shell
$ npx create-react-app my-app
```

### Deploying From Your Terminal

You can deploy your new React project, along with [Serverless Functions](https://vercel.com/docs/v2/serverless-functions/introduction), with a single command from your terminal using [Vercel CLI](https://vercel.com/download):

```shell
$ vercel
```
