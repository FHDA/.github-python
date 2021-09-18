# FHDA Python package template

This is for developer build python package, script quick. 
You may need to edit `setup.py` or `Makefile` after your create the repository.

## Quick start

1. Choose your project/package name
2. Create a folder under your repository name as your package name you choose in previous step
3. Modify the `setup.py` for your package name, or if you decide not use `setup.py`, change the
    `Makefile` instead
4. Now you should be good to go

> Suggestion: create a virtual environment for different repository you are working  

## Features

- pre-configured setup for CI with Github workflow
  - Python formatting check
  - Python linter check
  - Shell check
  - Shell test
  - Commit message with conversational commit check
- Makefile automating some dependencies stacks
  - Formating
    - black
  - Linter
    - pylint
    - pycodestyle
    - flake8
    - mypy
    - pytype
    - shellcheck
    - shelltest
  - Develop mode
  - Version update
  - `pip-tools` for python package dependency
- pre-configured pre-commit hook
  - pre-push
  - commit-msg
  - pre-commit
- pre-configured dependabot
