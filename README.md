# PROJECT TEMPLATE

## Getting started

### NPM Details

#### Installing and linking all dependencies for all the packages

```
npm run install
```

#### Run tests and lint files

```
npm run test     // unit tests
npm run lint     // lint js and css
```

As any npm run or npm task you can add modifiers to it to adjust your needs. These are some possibilities with jest unit tests.

```
npm run test --watch     // watching the modified files
npm run test --watchAll  // watch all files in the repo
npm run test --coverage  // run tests with coverage
```

#### To start all the dev environment

```
npm run start
```

#### Scritps

```
npm run check:node:version
```

## Suggested plugins for IDEs

### VSCode

-   ESLint
-   Prettier - Code formatter (Remember to turn on "Format on Save" under Project Preference)
-   Jest
