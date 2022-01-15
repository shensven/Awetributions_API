# Awetributions API

[![](https://img.shields.io/github/license/shensven/Awetributions_API)](./LICENSE)
[![](https://img.shields.io/github/package-json/dependency-version/shensven/Awetributions_API/egg)](./package.json)
[![](https://img.shields.io/github/package-json/dependency-version/shensven/Awetributions_API/egg-scripts)](./package.json)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/6dce034be92946f89d8d21cce0b57c6f)](https://app.codacy.com/gh/shensven/Awetributions_API?utm_source=github.com&utm_medium=referral&utm_content=shensven/Awetributions_API&utm_campaign=Badge_Grade_Settings)

A RESTful API for [Awetributions](https://github.com/shensven/Awetributions) using TypeScript & [Egg.js](https://github.com/eggjs/egg/)

## Quick Start

### Requirement

- Node.js 8.x
- Typescript 3.0+

### npm Scripts

- Use `npm run lint` to check code style
- Use `npm test` to run unit test
- Use `npm run clean` to clean compiled js at development mode once

### Development

```bash
npm install
npm run dev
open http://localhost:7001/
```

Don't tsc compile at development mode, if you had run `tsc` then you need to `npm run clean` before `npm run dev`.

### Deploy

```bash
npm run tsc
npm start
```

## License

[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fshensven%2FAwetributions_API.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2Fshensven%2FAwetributions_API?ref=badge_large)
