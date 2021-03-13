---
id: common.pyenv-virtualenv
title: Pyenv Virtualenv
desc: ''
updated: 1615655543080
created: 1615655543080
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# pyenv virtualenv

> Create virtual environments based on one's installed Python distributions.
> More information: <https://github.com/pyenv/pyenv-virtualenv>.

- Create a new Python 3.6.6 virtual environment:

`pyenv virtualenv {{3.6.6}} {{virtualenv_name}}`

- List all existing virtual environments:

`pyenv virtualenvs`

- Activate a virtual environment:

`pyenv activate {{virtualenv_name}}`

- Deactivate the virtual environment:

`pyenv deactivate`

