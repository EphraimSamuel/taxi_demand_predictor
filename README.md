# TAXI DEMAND PREDICTOR SERVICE

## Steps to re-generate virtual environment as in official repo

### 1. Remove the virutal env created by Poetry
```
$ poetry env remove python
```

### 2. Remove the `poetry.lock` file
This way we force Poetry to resolve all Python package dependencies from scratch.
```
$ rm poetry.lock
```

### 3. Install dependencies from the `pyproject.toml`
```
$ poetry install
```

## Further comments
### Remove `data/` folder from git tracking
In 2 steps:
1. `git rm -rf data/`
2. Add a new line to your .gitignore file

### Remove `src/__pycache__` folder from git tracking
Again, in 2 steps:

1. `git rm -rf src/__pycache__/`
2. Add a new line to your .gitignore file


