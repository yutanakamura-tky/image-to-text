# What's this?

This is a template repository customized for quick set up of research projects.

# Requirements

- Python => 3.8
- Rye 0.33.0

# How to use this

1. Install Rye:

```sh
curl -sSf https://rye.astral.sh/get | bash
```

2. Add Shims to Path & add shell completion:

```sh
echo 'source "$HOME/.rye/env"' >> ~/.profile
mkdir -p ~/.local/share/bash-completion/completions
rye self completion > ~/.local/share/bash-completion/completions/rye.bash
source ~/.bashrc
```

3. Update `pyproject.toml` with your favorite project name: 

```sh
vi /path/to/project/pyproject.toml
```

```
(pyproject.toml)

[project]
name = "template"  # Replace with your project name
```

4. Install packages using Poetry:

```sh
cd /path/to/project
rye sync
```

5. Install pre-commit hook:

```sh
cd /path/to/project
pre-commit install
```
