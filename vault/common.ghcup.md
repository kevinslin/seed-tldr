---
id: common.ghcup
title: Ghcup
desc: ''
updated: 1615655543056
created: 1615655543056
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
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

