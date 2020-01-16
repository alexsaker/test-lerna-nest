# LERNA

[![lerna](https://img.shields.io/badge/maintained%20with-lerna-cc00ff.svg)](https://lerna.js.org/)

## Adding lerna to nodejs global scope

```
npm i -g lerna
```

## Init commitzen friendly environment

```
npm i -g commitzen
npx commitizen init cz-lerna-changelog --save-dev --force --save-exact
npm i semantic-release --save-dev
```

## Adding changes

```
git add .
npx git-cz # Creating bot readable commit message
lerna version [major | minor | patch | premajor | preminor | prepatch | prerelease] --conventional-commits
```

## Serving NestJs servers

```
lerna run start:dev
```

Checkout urls: http://localhost:4000/ && http://localhost:4001/
