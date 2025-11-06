Configuration
=============

Run Statistics
--------------
    ruff --statistics



Configuration
-------------
Ruff can be configured via pyproject.toml or if none
it'll look for ruff.toml::

    $ pyproject.toml

    [tool.ruff]
    exclude = ["migrations/*"]

    [tool.ruff.lint]
    select = ["I"]
    ignore = ["E501"]
