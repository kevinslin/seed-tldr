---
id: common.conda
title: Conda
desc: ''
updated: 1642441815004
created: 1642441815004
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# conda

> Package, dependency and environment management for any programming language.
> Some subcommands such as `conda create` have their own usage documentation.
> More information: <https://github.com/conda/conda>.

- Create a new environment, installing named packages into it:

`conda create --name {{environment_name}} {{python=3.9 matplotlib}}`

- List all environments:

`conda info --envs`

- Load an environment:

`conda {{activate environment_name}}`

- Unload an environment:

`conda {{deactivate}}`

- Delete an environment (remove all packages):

`conda remove --name {{environment_name}} --all`

- Install packages into the current environment:

`conda install {{python=3.4 numpy}}`

- List currently installed packages in current environment:

`conda list`

- Delete unused packages and caches:

`conda clean --all`

