---
id: common.ghcup
title: Ghcup
desc: ''
updated: 1623965016126
created: 1623965016126
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ghcup

> Haskell toolchain installer.
> Install, manage, and update Haskell toolchains.
> More information: <https://gitlab.haskell.org/haskell/ghcup-hs>.

- Start the interactive TUI:

`ghcup tui`

- List available GHC/cabal versions:

`ghcup list`

- Install the recommended GHC version:

`ghcup install ghc`

- Install a specific GHC version:

`ghcup install ghc {{version}}`

- Set the currently "active" GHC version:

`ghcup set ghc {{version}}`

- Install cabal-install:

`ghcup install cabal`

- Update `ghcup` itself:

`ghcup upgrade`

