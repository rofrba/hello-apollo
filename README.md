# Getting started with Apollo Server 4

This is the complete code from [Get started with Apollo Server](https://www.apollographql.com/docs/apollo-server/v4/getting-started).

## Run locally



TEST
```shell
npm install
# agregamos
"build": "npm run compile"
"lint": "eslint . --ext js,jsx --report-unused-disable-directives --max-warnings 0",
# modificamos
npm start

npm init @eslint/config
```

El package.json deberia quedar algo asi
```json

{
  {
  "name": "hello-apollo",
  "version": "1.0.0",
  "description": "An example of getting started with the AS4 alpha",
  "main": "dist/index.js",
  "type": "module",
  "scripts": {
    "postinstall": "npm run compile",
    "build": "npm run compile",
    "lint": "eslint . --ext js,jsx --report-unused-disable-directives --max-warnings 0",
    "compile": "tsc",
    "start": "node ./dist/index.js"
  },
  "keywords": [],
  "author": "",
  "license": "ISC",
  "dependencies": {
    "@apollo/server": "^4.1.0",
    "graphql": "^16.6.0",
    "lint": "^0.8.19",
    "typescript": "^4.7.4"
  },
  "devDependencies": {
    "@types/node": "^18.6.3",
    "@typescript-eslint/eslint-plugin": "^7.3.0",
    "@typescript-eslint/parser": "^7.3.0",
    "eslint": "^8.57.0"
  }
}


```

