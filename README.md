# Orchestration Spotlight — Lab Hub

Two-lab course covering Workato Data Pipelines and Decision Models. Served
via GitHub Pages from the `docs/` folder (branch `main`, folder `/docs`).

## Labs

| Lab | Tier |
|---|---|
| Smart Lead Router | Foundational |
| Data Pipeline Sync | Foundational |

## Structure

- `docs/` — the published surface: a single self-contained hub page with
  both labs embedded (Pages source)
- Every commit is checked by the publish guard workflow
  (`.github/workflows/publish-guard.yml`); the same checks run locally as a
  pre-push hook — enable once per clone with:

```
git config core.hooksPath .githooks
```

## Contributing

Content is authored and reviewed elsewhere; this repo holds only pressed,
vetted output. Do not edit the hub HTML in place — changes land as a fresh
press of the whole bundle.
