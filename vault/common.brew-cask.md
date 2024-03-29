---
id: common.brew-cask
title: Brew Cask
desc: ''
updated: 1642441814999
created: 1642441814999
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# brew cask

> Package manager for macOS applications distributed as binaries.
> More information: <https://github.com/Homebrew/homebrew-cask>.

- Search for formulas and casks:

`brew search {{text}}`

- Install a cask:

`brew cask install {{cask_name}}`

- List all installed casks:

`brew list --cask`

- List installed casks that have newer versions available:

`brew outdated --cask`

- Upgrade an installed cask (if no cask name is given, all installed casks are upgraded):

`brew upgrade --cask {{cask_name}}`

- Uninstall a cask:

`brew cask uninstall {{cask_name}}`

- Uninstall a cask and remove related settings and files:

`brew cask zap {{cask_name}}`

- Display information about a given cask:

`brew cask info {{cask_name}}`

