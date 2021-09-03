A TypeScript starter for Next.js that includes all you need to build amazing projects 🔥

- 🎨 **Tailwind** — A utility-first CSS framework
- 📏 **ESLint** — Pluggable JavaScript linter
- 💖 **Prettier** - Opinionated Code Formatter
- 🐶 **Husky** — Use git hooks with ease
- 📄 **Commitizen** - Conventional commit messages CLI
- 🚓 **Commitlint** - Lint commit messages
- 🖌 **Renovate** - Dependency update tool
- 🚫 **lint-staged** - Run linters against staged git files
- 👷 **PR Workflow** - Run Type Check & Linters on pull requests
- 🗂 **Absolute import** - Import folders and files using the `@` prefix

## 🚀 Getting started

If you prefer you can clone this repository and run the following commands inside the project folder:

1. `npm install` or `yarn`;
2. `yarn dev` or `npm run dev`;

To view the project open `http://localhost:3000`.

## ✍🏻 Before commit
Make sure your commit message follow `@commitlint/config-conventional` style

`(scope): message`

Possible scope values:
```
build
chore
ci
docs
feat
fix
perf
refactor
revert
style
test
```

For example:
```
FIX: some message # fails ❌
fix: some message # passes ✅
```

