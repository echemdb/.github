# Contributing to echemdb

Thank you for your interest in echemdb! Contributions of all kinds are welcome: bug reports, questions, feature ideas, data, documentation and code.

This guide applies to all repositories of the [echemdb community](https://github.com/echemdb). A repository can have its own `CONTRIBUTING.md` with additional, repository-specific instructions. For example, [electrochemistry-data](https://github.com/echemdb/electrochemistry-data/blob/main/CONTRIBUTING.md) explains how to contribute data.

Everyone participating in echemdb is expected to follow our [Code of Conduct](CODE_OF_CONDUCT.md). Please report unacceptable behavior to <conduct@echemdb.org>.

## Questions, bugs, and feature requests

Please use the issue tracker of the repository concerned. Search the existing issues first, check the documentation and make sure you are using the latest version. If you are unsure which repository is the right one, open the issue where you noticed the problem and we will move it.

If your report involves data that could be subject to copyright or an embargo (such as published or unpublished data), please reproduce the problem with a minimal example that does not contain such content. If that is not possible, contact the maintainers at <info@echemdb.org> before sharing any files publicly.

When reporting a bug, please include

- the versions of the package and of Python, your operating system and how you installed the package,
- the command or Python code you ran (a minimal example is best),
- the full error message or traceback, and what you expected to happen instead.

## Contributing code or documentation

All repositories use [pixi](https://pixi.sh) for development. Fork the repository, clone your fork and create a branch:

```sh
git clone https://github.com/<your-username>/<repository>.git
cd <repository>
git checkout -b my-feature
```

The development environment is set up automatically on first use. Most repositories provide these tasks:

```sh
pixi run doctest   # run the doctests
pixi run pytest    # run the tests
pixi run lint      # run pylint, black and isort
pixi run doc       # build the documentation
```

The available tasks are listed in the repository's `pyproject.toml` (or `pixi.toml`), or with `pixi task list`. To run the tests with a specific Python version, select an environment, for example `pixi run -e python-312 doctest`.

We format the code with black and isort and check it with pylint. CI enforces all three, so please run `pixi run lint` before committing. Public functions and classes should have docstrings with examples that serve as doctests.

Then open a pull request against the default branch. Please make sure that

- you added a news entry: copy `doc/news/TEMPLATE.rst` to `doc/news/<your-branch-name>.rst` and fill in the relevant sections (in the website repository, the news directory is `news/` at the top level),
- your change is covered by a test (usually a doctest),
- the documentation is updated, if needed,
- tests and linters pass (CI runs them on all supported Python versions and platforms).

Issues labeled `good first issue` are a good place to start. If you are unsure about anything, open an issue or a draft pull request and ask. We are happy to help.

## License

By contributing, you agree that your contributions are licensed under the license of the repository you contribute to (see its `LICENSE` file).
