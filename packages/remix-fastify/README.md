# Remix Fastify

Use [Remix](https://remix.run) with [Fastify](http://fastify.io)

## Installation

```sh
npm i @mcansh/remix-fastify
yarn add @mcansh/remix-fastify
pnpm i @mcansh/remix-fastify
```

## Quick Start

1. `npx create-remix@latest --template express`
2. [install](#installation) this
3. remove `compression`, `express`, `morgan`, `nodemon`
4. rename your `server.js` to `server.ts` with the following [https://github.com/mcansh/remix-fastify/blob/main/example/server.ts](https://github.com/mcansh/remix-fastify/blob/1a2819f03e448a79e06e98f37f87c6e7fa8d243e/example/server.ts) - or change the imports to be `require` instead
5. add `server: "server.ts"` to remix.config.js

## Example

checkout the example usage in [./example/server.ts](https://github.com/mcansh/remix-fastify/tree/1a2819f03e448a79e06e98f37f87c6e7fa8d243e/example)
