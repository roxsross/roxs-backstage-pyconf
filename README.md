## What do you need?

If you want follow our workshop, you'll need

- [Nodejs](https://nodejs.org/en/download)
- npm and npx, both are included in NodeJS
- some IDE or Code Editor, we'll use [VSC](https://code.visualstudio.com/Download)

Optional installation

- [yarn](https://yarnpkg.com/getting-started/install)

## Optional requirements

for an e2e experience you'll need

- A Github account.
- A Github's personal access token. check more about it [here](https://docs.github.com/en/enterprise-server@3.9/authentication/keeping-your-account-and-data-secure/managing-your-personal-access-tokens)

Set your personal access token in `./app-config.local.yaml`

```yml
integrations:
  github:
    - host: github.com
      token: your_personal_access_token_goes_here
```

## What do you must know?

Its very easy, but, we'll use yaml sintax. Check this [link](https://onthedock.github.io/post/170525-introduccion-a-yaml/) and learn more about yaml

## Usage Guide

```sh
yarn install
yarn dev
```
> The last command opens the app in [localhost:3000](http://localhost:3000)



