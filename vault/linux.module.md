---
id: linux.module
title: Module
desc: ''
updated: 1615663978750
created: 1615663978750
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# module

> Modify a users' environment using the module command.
> More information: <https://lmod.readthedocs.io/en/latest/010_user.html>.

- Display available modules:

`module avail`

- Search for a module by name:

`module spider {{module_name}}`

- Load a module:

`module load {{module_name}}`

- Display loaded modules:

`module list`

- Unload a specific loaded module:

`module {{module_name}}`

- Unload all loaded modules:

`module purge`

