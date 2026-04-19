# Contributing to mantler-docs

Thanks for helping improve the Mantler documentation.

## Development setup

1. Fork and clone the repository.
2. Install dependencies:

```bash
npm install
```

3. Run local development:

```bash
npm run dev
```

The site is available at `http://localhost:3000`.

## Content

Documentation pages live in `content/docs/` as MDX files. Navigation order is controlled by `meta.json` in each directory.

## Before opening a pull request

- Run a build to verify nothing is broken:

```bash
npm run build
```

- Keep PRs focused and include context in the description.

## Code of conduct

By participating, you agree to follow the project [Code of Conduct](./CODE_OF_CONDUCT.md).
