Copy the following config into your `.pre-commit-config.yaml` file:

```yaml
-   repo: https://github.com/tamccall/flake8-precommit
    sha: 'c48944200031302e46257adfa8b78e7dd40c85d5'
    hooks:
    -   id: flake8-diff
```

Find more info on pre-commit [here](https://pre-commit.com).

