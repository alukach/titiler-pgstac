# Development - Contributing

Issues and pull requests are more than welcome: https://github.com/stac-utils/titiler-pgstac/issues

**dev install**

```bash
$ git clone https://github.com/stac-utils/titiler-pgstac.git
$ cd titiler
$ pip install pre-commit -e .["test"]
```

This repo is set to use `pre-commit` to run *isort*, *flake8*, *pydocstring*, *black* ("uncompromising Python code formatter") and mypy when committing new code.

```bash
$ pre-commit install
```
