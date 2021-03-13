---
id: common.conda
title: Conda
desc: ''
updated: 1615663978703
created: 1615663978703
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# conda

> Package, dependency and environment management for any programming language.
> More information: <https://github.com/conda/conda>.

- Create a new environment, installing named packages into it:

`conda create --name {{environment_name}} {{python=2.7 matplotlib}}`

- List all environments:

`conda info --envs`

- Load or unload an environment:

`conda {{activate|deactivate}} {{environment_name}}`

- Delete an environment (remove all packages):

`conda remove --name {{environment_name}} --all`

- Search conda channels for a package by name:

`conda search {{package_name}}`

- Install packages into the current environment:

`conda install {{python=3.4 numpy}}`

- List currently installed packages in current environment:

`conda list`

- Delete unused packages and caches:

`conda clean --all`
