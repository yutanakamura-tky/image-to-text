# How to use this

1. Install Poetry:

```
curl -sSL https://raw.githubusercontent.com/python-poetry/poetry/master/get-poetry.py | python -
```

2. Install packages using Poetry:

```
cd /path/to/project
poetry install
```

3. Fill the blank in `pyproject.toml` with your favorite project name: 

```
vi /path/to/project/pyproject.toml
```

4. Install pre-commit hook:

```
cd /path/to/project
pre-commit install
```
