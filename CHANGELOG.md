# Changelog

## Version 0.3.0 (development)

This release migrates the package to a more palatable Google's Python style guide. A major modification to the package is with casing, all `camelCase` properties, methods, functions and parameters are now `snake_case`.

With respect to the classes,`SingleCellExperiment` now extends `SummarizedExperiment`. Typehints have been updated to reflect these changes.

In addition, docstrings and documentation has been updated to use sphinx's features of linking objects to their types. Sphinx now also documents private and special dunder methods (e.g. `__getitem__`, `__copy__` etc). Intersphinx has been updated to link to references from dependent packages.

Configuration for flake8, ruff and black has been added to pyproject.toml and setup.cfg to be less annoying.

Finally, pyscaffold has been updated to use "myst-parser" as the markdown compiler instead of recommonmark. As part of the pyscaffold setup, one may use pre-commits to run some of the routine tasks of linting and formatting before every commit. While this is sometimes annoying and can be ignored with `--no-verify`, it brings some consistency to the code base.

## Version 0.1

- Initial release of SCE class
- Tests
- Documentation
