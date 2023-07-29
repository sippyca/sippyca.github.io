# TypeScript

## Hello World!

### Prerequisites

Setup a TypeScript & NodeJS development environment

```
mkdir typescript_helloworld
cd typescript_helloworld
code .
```
Create a src/index.ts file

```ts
let greeting: string = "Hello World!";
​
console.log(greeting);
```

Create the tsconfig.json

```
tsc --init
```

Edit some settings

```ts
"rootDir": "./src",
"outDir": "./dist",
"removeComments": true,
"noEmitOnError": true,
```

Compile
```
tsc
```

Run the code
```
node dist/index.js
```