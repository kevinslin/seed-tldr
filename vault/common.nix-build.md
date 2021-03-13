---
id: common.nix-build
title: Nix Build
desc: ''
updated: 1615663978726
created: 1615663978726
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# nix-build

> Build a Nix expression.
> More information: <https://nixos.org/releases/nix/latest/manual#sec-nix-build>.

- Build a Nix expression:

`nix-build --attr {{expression_name}}`

- Build a sandboxed Nix expression (on non-nixOS):

`nix-build --attr {{expression_name}} --option sandbox true`

