---
id: common.wapm
title: Wapm
desc: ''
updated: 1615663978739
created: 1615663978739
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# wapm

> The WebAssembly package manager.
> More information: <https://wapm.io/help/reference>.

- Interactively create a new `wapm.toml` file:

`wapm init`

- Download all the packages listed as dependencies in `wapm.toml`:

`wapm install`

- Download a specific version of a package and add it to the list of dependencies in wapm.toml:

`wapm install {{package_name}}@{{version}}`

- Download a package and install it globally:

`wapm install --global {{package_name}}`

- Uninstall a package and remove it from the list of dependencies in `wapm.toml`:

`wapm uninstall {{package_name}}`

- Print a tree of locally-installed dependencies:

`wapm list`

- List top-level globally installed packages:

`wapm list --global`

- Execute a package command using the Wasmer runtime:

`wapm run {{command_name}} {{arguments}}`

