# mantler-docs

[![CI](https://github.com/Borgels/mantler-docs/actions/workflows/ci.yml/badge.svg)](https://github.com/Borgels/mantler-docs/actions/workflows/ci.yml)
[![CodeQL](https://github.com/Borgels/mantler-docs/actions/workflows/codeql.yml/badge.svg)](https://github.com/Borgels/mantler-docs/actions/workflows/codeql.yml)
[![Release](https://img.shields.io/github/v/release/Borgels/mantler-docs)](https://github.com/Borgels/mantler-docs/releases)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![npm](https://img.shields.io/badge/runtime-nodejs-green)](https://nodejs.org)

Status: initial public release track (`v0.1.x`).

Documentation source for [docs.mantler.ai](https://docs.mantler.ai), built with Fumadocs + Next.js.

```text
At a glance
- What this repo is: docs source (MDX content, navigation, API reference pages).
- What it is not: Mantler runtime/control-plane server code.
- Publishing target: docs.mantler.ai via Vercel.
- Try it locally: npm install && npm run dev
- Open local docs: http://localhost:3000
```

## Quickstart

```bash
npm install
npm run dev
```

## Links

- [Live docs](https://docs.mantler.ai)
- [Getting started](https://docs.mantler.ai/getting-started)
- [Machines](https://docs.mantler.ai/machines)
- [Mantles and compatibility](https://docs.mantler.ai/stacks)
- [API reference](https://docs.mantler.ai/api)

## Content model

Docs content lives under `content/docs/` and navigation order is controlled by `meta.json` files.

## Security

See [SECURITY.md](SECURITY.md).

## License

[MIT](LICENSE)
