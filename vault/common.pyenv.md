---
id: common.pyenv
title: Pyenv
desc: ''
updated: 1615655543080
created: 1615655543080
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# pyenv

> Switch between multiple versions of Python easily.
> More information: <https://github.com/pyenv/pyenv>.

- List all available commands:

`pyenv commands`

- List all Python versions under the `${PYENV_ROOT}/versions` directory:

`pyenv versions`

- Install a Python version under the `${PYENV_ROOT}/versions` directory:

`pyenv install {{2.7.10}}`

- Uninstall a Python version under the `${PYENV_ROOT}/versions` directory:

`pyenv uninstall {{2.7.10}}`

- Set Python version to be used globally in the current machine:

`pyenv global {{2.7.10}}`

- Set Python version to be used in the current directory and all directories below it:

`pyenv local {{2.7.10}}`

