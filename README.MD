
Run these commands before starting the project:

Install code formatters and linters:
```bash
pip install black flake8 isort mypy pre-commit
```

Install the pre-commit hooks to run at each commit:
```bash
pre-commit install
```

(Optional) Run precommit for all files:
```bash
pre-commit run --all-files
```

These tools help you enforce consistent code quality and catch 
potential errors before they are commited. 
They can feel annoying at first though.