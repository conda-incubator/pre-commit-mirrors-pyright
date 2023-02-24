Pyright(-conda) mirror
======================

Mirror of pyright for pre-commit with conda as a language.

For pre-commit: see https://github.com/pre-commit/pre-commit For pyright: see https://github.com/microsoft/pyright

### Using pyright with pre-commit and conda:

Add this to your `.pre-commit-config.yaml`

```yaml
 - repo: https://github.com/Quantco/pre-commit-mirrors-pyright
   rev: ''  # Use the sha / tag you want to point at
   hooks:
     - id: pyright-conda
```
