# renovate-pre-commit-hooks
pre-commit-hooks for renovate

A simple hook for [pre-commit](pre-commit.com) to validate your `renovate.json`.

## Howto

Install `pre-commit` and add

```yaml
repos:
  - repo: https://github.com/killermoehre/renovate-pre-commit-hooks
    rev: 1.0.0
    hooks:
      - id: renovate-config-validator
```

to your `.pre-commit-config.yaml`.
