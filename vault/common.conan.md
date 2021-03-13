---
id: common.conan
title: Conan
desc: ''
updated: 1615663978703
created: 1615663978703
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# conan

> The open source, decentralized and multi-platform package manager to create and share all your native binaries.
> More information: <https://conan.io/>.

- Install packages based on `conanfile.txt`:

`conan install {{.}}`

- Install packages and create configuration files for a specific generator:

`conan install -g {{generator}}`

- Install packages, building from source:

`conan install {{.}} --build`

- Search for locally installed packages:

`conan search {{package}}`

- Search for remote packages:

`conan search {{package}} -r {{remote}}`

- List remotes:

`conan remote --list`

