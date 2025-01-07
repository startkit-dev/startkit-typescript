<h1 align="center">startkit-typescript</h1>

<div align="center">
  <strong>A sane way to start your next Typescript project</strong>
  <p>A type-safe starter project following the latest best practices</p>
</div>

## Features

- ✅ **Bun** package manager and test runner
- ✅ Strict, type-aware linting with **Eslint 9**
- ✅ Consistent code style with **Prettier**
- ✅ **VSCode** default settings and recommended extensions
- ✅ CI/CD via **Github Actions**
- ✅ Ready for publishing to npm

## Getting started

Once you clone the repository, you can run:

```sh
bun install
```

## 🚀 Scripts

| Command                | Action                                      |
| :--------------------- | :------------------------------------------ |
| `bun install`          | Installs dependencies                       |
| `bun dev`              | Run the app in development mode             |
| `bun run build`        | Build the project to .dist directory        |
| `bun run check`        | Run all checks (format, lint, types, tests) |
| `bun run clean`        | Clean build artifacts and cache             |
| `bun run fix`          | Auto-fix formatting and linting issues      |
| `bun run format`       | Format the code with Prettier               |
| `bun run format:check` | Check code format with Prettier             |
| `bun run lint`         | Check code style with ESLint                |
| `bun run outdated`     | Interactive update of dependencies          |
| `bun run typecheck`    | Check TypeScript types                      |
