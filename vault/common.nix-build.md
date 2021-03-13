---
id: common.nix-build
title: Nix Build
desc: ''
updated: 1615655543074
created: 1615655543074
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# nix-build

> Build a Nix expression.
> More information: <https://nixos.org/releases/nix/latest/manual#sec-nix-build>.

- Build a Nix expression:

`nix-build --attr {{expression_name}}`

- Build a sandboxed Nix expression (on non-nixOS):

`nix-build --attr {{expression_name}} --option sandbox true`

