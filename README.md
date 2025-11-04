# Present Ruff

A presentation about improving Developer Experience using Ruff and Pre-Commit.

## Prerequisites

- Python 3.7 or higher
- pip (Python package installer)

## Installation

Install the required dependencies:

```bash
pip install sphinx sphinx-revealjs
```

## Building the Presentation

To build the presentation, run:

```bash
make revealjs
```

This will generate the presentation in the `_build/revealjs` directory.

## Viewing the Presentation

After building, open the generated HTML file in your web browser:

```bash
open _build/revealjs/index.html
```

Or on Linux:

```bash
xdg-open _build/revealjs/index.html
```

Or simply navigate to `_build/revealjs/index.html` in your file browser and open it with your preferred web browser.

## Other Make Targets

To see all available build targets:

```bash
make help
```

## Cleaning Build Files

To remove built files:

```bash
make clean
```

## Project Structure

- `index.rst` - Main presentation file
- `_section/` - Directory containing presentation sections
- `conf.py` - Sphinx configuration file
- `_build/` - Generated output directory (created after building)
