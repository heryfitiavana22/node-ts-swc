# Node-TS-swc

A starter for NodeJS with TypeScript using SWC for faster transpilation.

## Features

- Faster compilation and building with SWC

## TypeScript with SWC

First, install `@swc/core` :

```bash
  npm install @swc/core
```

Then add the following to your tsconfig.json.

```json
{
  "ts-node": {
    "swc": true
  }
}
```

## Usage

Clone this repository

```bash
  git clone https://github.com/heryfitiavana22/node-ts-swc.git
  cd node-ts-swc
```

Install dependencies

```bash
  npm i
```

Development usage

```bash
  npm run dev
```

For production

```bash
  npm run build
```

## Related

[SWC (Speedy Web Compiler)](https://github.com/swc-project/swc)

[TypeScript](https://github.com/Microsoft/TypeScript)

[Node](https://github.com/nodejs/node)