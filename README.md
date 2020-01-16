# LERNA

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
