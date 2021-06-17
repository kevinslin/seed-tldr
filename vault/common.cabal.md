---
id: common.cabal
title: Cabal
desc: ''
updated: 1623965016115
created: 1623965016115
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# cabal

> Command-line interface to the Haskell package infrastructure (Cabal).
> Manage Haskell projects and Cabal packages from the Hackage package repository.
> More information: <https://cabal.readthedocs.io/en/latest/intro.html>.

- Search and list packages from Hackage:

`cabal list {{search_string}}`

- Show information about a package:

`cabal info {{package_name}}`

- Download and install a package:

`cabal install {{package_name}}`

- Create a new Haskell project in the current directory:

`cabal init`

- Build the project in the current directory:

`cabal build`

- Run tests of the project in the current directory:

`cabal test`

