# vaadin-usage-statistics-opt-out

## Why does this exits?

So that one can write into their `pnpm-workspace.yaml`:
```yaml
overrides:
  "@vaadin/vaadin-usage-statistics": "npm:@xdevsoftware/vaadin-usage-statistics-opt-out@1.0.2"
```
without breaking the build
