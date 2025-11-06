Configuration
=============



Pre-commit configuration
-------------------------
* create a file named ``.pre-commit-config.yaml``
* generate a basic config using ``pre-commit sample-config``


Our configuration
-----------------
::

    repos:
    - repo: https://github.com/pre-commit/pre-commit-hooks
      rev: v3.2.0
      hooks:
      - id: trailing-whitespace
      - id: end-of-file-fixer
      - id: check-yaml
      - id: check-added-large-files
 
    - repo: https://github.com/astral-sh/ruff-pre-commit
      rev: v0.14.3
      hooks:
      - id: ruff-check


Install the pre-commit hooks
----------------------------
::
    
        pre-commit install



Viola!
------
Pre-commit will run wen you commit code. If any of the hooks fail, the commit will be aborted.
