---
id: common.haxelib
title: Haxelib
desc: ''
updated: 1642441815032
created: 1642441815032
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# haxelib

> Haxe Library Manager.
> More information: <https://lib.haxe.org/>.

- Search for a Haxe library:

`haxelib search {{keyword}}`

- Install a Haxe library:

`haxelib install {{libname}}`

- Install a specific version of a Haxe library:

`haxelib install {{libname}} {{version}}`

- Upgrade all installed Haxe libraries:

`haxelib upgrade`

- Install the development version of a library from a Git repository:

`haxelib git {{libname}} {{git_url}}`

- Uninstall a Haxe library:

`haxelib remove {{libname}}`

- Print a tree of locally installed Haxe libraries:

`haxelib list`

