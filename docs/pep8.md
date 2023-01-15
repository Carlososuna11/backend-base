# PEP8 Formatting

## What is PEP8?

> PEP8 is a style guide for Python code. It is a set of rules for writing Python code that is readable by humans.

## Verify your code

### Requirements

- Install Flake8

```terminal
pip install flake8
```

### Command

```terminal
flake8 --exclude=.git,.venv,env,.tox,dist,doc,*egg,build,.vscode,*migrations/*.py,*/local_settings.py .
```
