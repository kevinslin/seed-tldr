---
id: common.pyenv-virtualenv
title: Pyenv Virtualenv
desc: ''
updated: 1615663978731
created: 1615663978731
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
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

