# bolus-wizard

[![Release](https://img.shields.io/github/v/release/bhjelmar/bolus-wizard)](https://img.shields.io/github/v/release/bhjelmar/bolus-wizard)
[![Build status](https://img.shields.io/github/workflow/status/bhjelmar/bolus-wizard/merge-to-main)](https://img.shields.io/github/workflow/status/bhjelmar/bolus-wizard/merge-to-main)
[![codecov](https://codecov.io/gh/bhjelmar/bolus-wizard/branch/main/graph/badge.svg)](https://codecov.io/gh/bhjelmar/bolus-wizard)
[![Commit activity](https://img.shields.io/github/commit-activity/m/bhjelmar/bolus-wizard)](https://img.shields.io/github/commit-activity/m/bhjelmar/bolus-wizard)
[![Docs](https://img.shields.io/badge/docs-gh--pages-blue)](https://bhjelmar.github.io/bolus-wizard/)
[![Code style with black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)
[![Imports with isort](https://img.shields.io/badge/%20imports-isort-%231674b1)](https://pycqa.github.io/isort/)
[![License](https://img.shields.io/github/license/bhjelmar/bolus-wizard)](https://img.shields.io/github/license/bhjelmar/bolus-wizard)

Automatically calculate your optimal bolus.

- **Github repository**: <https://github.com/bhjelmar/bolus-wizard/>
- **Documentation** <https://bhjelmar.github.io/bolus-wizard/>

## Getting started with your project

First, create a repository on GitHub with the same name as this project, and then run the following commands:

``` bash
git init -b main
git add .
git commit -m "init commit"
git remote add origin git@github.com:bhjelmar/bolus-wizard.git
git push -u origin main
```

Finally, install the environment and the pre-commit hooks with 

```bash
make install
```

You are now ready to start development on your project! The CI/CD
pipeline will be triggered when you open a pull request, merge to main,
or when you create a new release.

To finalize the set-up for publishing to PyPi or Artifactory, see
[here](https://fpgmaas.github.io/cookiecutter-poetry/features/publishing/#set-up-for-pypi).
For activating the automatic documentation with MkDocs, see
[here](https://fpgmaas.github.io/cookiecutter-poetry/features/mkdocs/#enabling-the-documentation-on-github).
To enable the code coverage reports, see [here](https://fpgmaas.github.io/cookiecutter-poetry/features/codecov/).

## Releasing a new version

- Create an API Token on [Pypi](https://pypi.org/).
- Add the API Token to your projects secrets with the name `PYPI_TOKEN` by visiting 
[this page](https://github.com/bhjelmar/bolus-wizard/settings/secrets/actions/new).
- Create a [new release](https://github.com/bhjelmar/bolus-wizard/releases/new) on Github. 
Create a new tag in the form ``*.*.*``.

For more details, see [here](https://fpgmaas.github.io/cookiecutter-poetry/releasing.html).

---

Repository initiated with [fpgmaas/cookiecutter-poetry](https://github.com/fpgmaas/cookiecutter-poetry).