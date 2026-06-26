# Project: Oxc Playground

## Commands

### Development

```bash
pnpm dev        # Start Vite dev server
```

### Build

```bash
pnpm build      # Run TypeScript checks and build with Vite
```

### Preview

```bash
pnpm preview    # Preview production build locally
```

### Code Quality

```bash
pnpm lint       # Run oxlint
pnpm fmt        # Run oxfmt formatter
```

## Project Info

- Node requirement: >=22.18.0
- Package manager: pnpm@11.0.4
- Uses git hooks for pre-commit linting

<!--VITE PLUS START-->

# Using Vite+, the Unified Toolchain for the Web

This project is using Vite+, a unified toolchain built on top of Vite, Rolldown, Vitest, tsdown, Oxlint, Oxfmt, and Vite Task. Vite+ wraps runtime management, package management, and frontend tooling in a single global CLI called `vp`. Vite+ is distinct from Vite, and it invokes Vite through `vp dev` and `vp build`. Run `vp help` to print a list of commands and `vp <command> --help` for information about a specific command.

Docs are local at `node_modules/vite-plus/docs` or online at https://viteplus.dev/guide/.

## Review Checklist

- [ ] Run `vp install` after pulling remote changes and before getting started.
- [ ] Run `vp check` and `vp test` to format, lint, type check and test changes.
- [ ] Check if there are `vite.config.ts` tasks or `package.json` scripts necessary for validation, run via `vp run <script>`.
- [ ] If setup, runtime, or package-manager behavior looks wrong, run `vp env doctor` and include its output when asking for help.

<!--VITE PLUS END-->
