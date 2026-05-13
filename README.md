![NPM Version](https://img.shields.io/npm/v/%40xdevsoftware%2Fvaadin-usage-statistics-opt-out)

# vaadin-usage-statistics-opt-out

## Why does this exits?

So that one can write into their `pnpm-workspace.yaml`:
```yaml
overrides:
  "@vaadin/vaadin-usage-statistics": "npm:@xdevsoftware/vaadin-usage-statistics-opt-out@<version>"
```
without breaking the build
