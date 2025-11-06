Getting Started
===============

Installation
------------
::

    pip install ruff


Run it!
-------
Go to the project directory and run the following command::

    ruff .


Check Rules
-----------
Each of the violations will be listed once we run the ruff check command.
And each of the violations will have a code associated with it.::

    ruff rule {CODE}


Show source
-----------
In ruff, we can also show the soure of the offending code.::

    ruff --show-source


Show Sublinters that Ruff Implements
-------------------------------------
::

    ruff linter
    ruff --select {CODE}



Format and check a file
------------------------
::

    ruff check {file_path}
    ruff format {file_path}    

    --fix # Lint all files in the current directory, and fix any fixable errors.
    --watch # Lint all files in the current directory, and re-lint on change

