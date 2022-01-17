---
id: linux.nixos-option
title: Nixos Option
desc: ''
updated: 1642441815105
created: 1642441815105
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# nixos-option

> Inspect a NixOS configuration.
> More information: <https://nixos.org/manual/nixos/stable/index.html#sec-modularity>.

- List all subkeys of a given option key:

`nixos-option {{option_key}}`

- List current boot kernel modules:

`nixos-option boot.kernelModules`

- List authorized keys for a specific user:

`nixos-option users.users.{{username}}.openssh.authorizedKeys.{{keyFiles|keys}}`

- List all remote builders:

`nixos-option nix.buildMachines`

- List all subkeys of a given key on another NixOS configuration:

`NIXOS_CONFIG={{path_to_configuration.nix}} nixos-option {{option_key}}`

- Show recursively all values of a user:

`nixos-option -r users.users.{{user}}`

