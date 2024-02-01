# pyright pre-commit hook

pre-commit hook of pyright with conda as a `language` / package manager.

For pre-commit: see [here](https://github.com/pre-commit/pre-commit)

For pyright: see [here](https://github.com/microsoft/pyright)

## Using pyright with pre-commit and conda:

Add this to your `.pre-commit-config.yaml`

```yaml
 - repo: https://github.com/quantco/pre-commit-mirrors-pyright
   rev: ''  # Use the sha / tag you want to point at
   hooks:
     - id: pyright-conda
```
