<p align="center">
  <a href="https://github.com/w8bdcr-official/W8BDCR-NestJS-Starter" target="_blank"><img src="assets/logo.png" width="120" alt="W8BDCR Logo" /></a>
</p>

  <p align="center">A progressive <a href="http://nodejs.org" target="_blank">Node.js</a> framework for building efficient and scalable server-side applications.</p>
    <p align="center">
<a href="LICENSE" target="_blank"><img src="https://img.shields.io/badge/License-MIT-22c55e.svg" alt="License: MIT" /></a>
<a href="https://nestjs.com/" target="_blank"><img src="https://img.shields.io/badge/NestJS-9.x-22c55e.svg" alt="NestJS 9" /></a>
<a href="https://www.typescriptlang.org/" target="_blank"><img src="https://img.shields.io/badge/TypeScript-4.7-22c55e.svg" alt="TypeScript 4.7" /></a>
<a href="https://nodejs.org/" target="_blank"><img src="https://img.shields.io/badge/Node.js-18%2B-22c55e.svg" alt="Node.js 18+" /></a>
  </p>

## Description

W8BDCR NestJS Starter is a TypeScript starter repository for building server-side applications with [NestJS](https://nestjs.com) — a progressive Node.js framework. It comes with a working example out of the box: a `GET /` endpoint wired through a controller and a service, so you can run it, see it answer, and start building on top of it right away.

It runs on Express, the default HTTP adapter, and ships with unit and e2e tests, ESLint and Prettier configured, so the project stays clean as it grows.

## Quick start

```bash
git clone https://github.com/w8bdcr-official/W8BDCR-NestJS-Starter.git
cd W8BDCR-NestJS-Starter
npm install
npm run start:dev
```

Open http://localhost:3000 — you will see:

```
Hello from W8BDCR!
```

## What's included

| What | Where |
| --- | --- |
| `GET /` endpoint | `src/app.controller.ts` |
| Business logic | `src/app.service.ts` |
| Root module | `src/app.module.ts` |
| Bootstrap (port 3000) | `src/main.ts` |
| Unit test | `src/app.controller.spec.ts` |
| End-to-end test | `test/app.e2e-spec.ts` |
| Lint + format | ESLint, Prettier |

## Running the app

```bash
# development - watch mode
$ npm run start:dev

# development - debug & watch mode
$ npm run start:debug

# production mode
$ npm run start
```

## Test

```bash
# unit tests
$ npm run test

# e2e tests
$ npm run test:e2e

# test coverage
$ npm run test:cov
```

## Support

W8BDCR NestJS Starter is an MIT-licensed open source project by W8BDCR.

- Telegram - [https://t.me/W8BDCR](https://t.me/W8BDCR)
- GitHub - [https://github.com/w8bdcr-official](https://github.com/w8bdcr-official)

## Stay in touch

- Author - W8BDCR
- Telegram - [https://t.me/W8BDCR](https://t.me/W8BDCR)
- GitHub - [https://github.com/w8bdcr-official/W8BDCR-NestJS-Starter](https://github.com/w8bdcr-official/W8BDCR-NestJS-Starter)

## License

W8BDCR NestJS Starter is [MIT licensed](LICENSE).
