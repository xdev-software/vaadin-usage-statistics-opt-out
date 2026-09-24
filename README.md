[![NPM Version](https://img.shields.io/npm/v/%40xdevsoftware%2Fvaadin-usage-statistics-opt-out)](https://www.npmjs.com/package/@xdevsoftware/vaadin-usage-statistics-opt-out)

# vaadin-usage-statistics-opt-out

> [!IMPORTANT]
> As of 2026-09 this is no longer needed because
> * usage-statistics is only required for dev
> * Vaadin now ships a bundle out of the box that does not execute a NPM install
> * It can be fully controlled from Flow's side

## Why does this exits?

So that one can write into their `pnpm-workspace.yaml`:
```yaml
overrides:
  "@vaadin/vaadin-usage-statistics": "npm:@xdevsoftware/vaadin-usage-statistics-opt-out@<version>"
```
without breaking the build
