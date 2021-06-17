---
id: common.home-manager
title: Home Manager
desc: ''
updated: 1623965306192
created: 1623965306192
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# home-manager

> Manage a user environment using Nix.
> More information: <https://github.com/rycee/home-manager>.

- Activate the configuration defined in `~/.config/nixpkgs/home.nix`:

`home-manager build`

- Activate the configuration and switch to it:

`home-manager switch`

