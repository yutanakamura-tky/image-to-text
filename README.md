# How to use this

1. Install Poetry:

```sh
curl -sSL https://raw.githubusercontent.com/python-poetry/poetry/master/get-poetry.py | python -
```

2. Install packages using Poetry:

```sh
cd /path/to/project
poetry install
```

3. Fill the blank in `pyproject.toml` with your favorite project name: 

```sh
vi /path/to/project/pyproject.toml
```

```toml
(pyproject.toml)

[tool.poetry]
name = "" # REPLACE WITH YOUR FAVORITE PROJECT NAME
...
```

Then update your project:

```sh
poetry update
```

4. Install pre-commit hook:

```sh
cd /path/to/project
pre-commit install
```
