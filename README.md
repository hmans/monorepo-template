# Monorepo Template

This is my monorepo template. It comes preconfigured with:

- Uses pnpm workspaces
- TypeScript support
- Tests with Jest
- Building with Preconstruct
- A `packages` directory for packages, and `apps` for apps (examples, demos, ...)
- Support for TurboRepo (configured to peacefully coexist with Preconstruct's `dev` mode)
- Changelog and release management via Changesets
- GitHub Actions for CI and release management

Stuff that's missing:

- [ ] Add example package
- [ ] Import root `tsconfig.json` into `packages`
- [ ] eslint

## Configuration

After forking and cloning this template repository, you may want to make the following configuration changes:

- Configure `NPM_TOKEN` for GitHub Actions
- Remove/change `.github/FUNDING.yml`
- Set up TurboRepo cache and remote cache
- Delete/modify `example-package`
