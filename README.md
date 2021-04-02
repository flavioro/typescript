# TypeScript

<img src="https://serokell.io/files/0u/0ufu1q21.js-ts.jpg" width="300px">

##Configurations
### 1 - Install typescript
```
yarn add typescript -D
```
### 2 - Inicialize typescript (tsconfig.json)
```
yarn tsc --init
```

### 3 - Build code (javascript)
```
yarn tsc
```

### Tool convert .ts to .js (environment dev)
```
yarn add ts-node-dev -D
```
### Add configuration in package.json
```
  "scripts": {
    "dev": "ts-node-dev --transpile-only --ignore-watch node_modules --respawn src/server.ts"
  },
```
