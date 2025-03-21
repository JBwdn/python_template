# python_template
General purpose template for installable python projects

Now uses `uv` to manage the environment!

## Installation

```bash
uv run demo-script  # THATS ALL!
```

## Usage

### Importing and using code

```python
# Import the package and run some included function:

from package import scripts
scripts.demo.main()
```

### Running pre-commit hooks

Requires a system installation of pre-commit.

```bash
# Run all the hooks:
pre-commit run --all-files
```

### Running tests

```bash
# Pytest will find all files with the name "test_*.py" or "*_test.py" and run them:

uv run pytest
```
