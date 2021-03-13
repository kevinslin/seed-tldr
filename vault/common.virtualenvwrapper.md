---
id: common.virtualenvwrapper
title: Virtualenvwrapper
desc: ''
updated: 1615655543091
created: 1615655543091
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# virtualenvwrapper

> Group of simple wrapper commands for Python's `virtualenv` tool.
> More information: <http://virtualenvwrapper.readthedocs.org>.

- Create a new Python `virtualenv` in `$WORKON_HOME`:

`mkvirtualenv {{virtualenv_name}}`

- Create a `virtualenv` for a specific Python version:

`mkvirtualenv --python {{/usr/local/bin/python3.8}} {{virtualenv_name}}`

- Activate or use a different `virtualenv`:

`workon {{virtualenv_name}}`

- Stop the `virtualenv`:

`deactivate`

- List all virtual environments:

`lsvirtualenv`

- Remove a `virtualenv`:

`rmvirtualenv {{virtualenv_name}}`

- Get summary of all virtualenvwrapper commands:

`virtualenvwrapper`

