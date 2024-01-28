# pyright mirror

Mirror of pyright for pre-commit with conda as a language.

For pre-commit: see [here](https://github.com/pre-commit/pre-commit)

For ansible-lint: see [here](https://github.com/microsoft/pyright)

## Using pyright with pre-commit and conda:

Add this to your `.pre-commit-config.yaml`

```yaml
 - repo: https://github.com/quantco/pre-commit-mirrors-pyright
   rev: ''  # Use the sha / tag you want to point at
   hooks:
     - id: pyright-conda
```
