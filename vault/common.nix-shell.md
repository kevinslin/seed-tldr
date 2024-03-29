---
id: common.nix-shell
title: Nix Shell
desc: ''
updated: 1642441815051
created: 1642441815051
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# nix-shell

> Start an interactive shell based on a Nix expression.
> More information: <https://nixos.org/manual/nix/stable/#sec-nix-shell>.

- Start with nix expression in `shell.nix` or `default.nix` in the current directory:

`nix-shell`

- Run shell command in non-interactive shell and exit:

`nix-shell --run "{{command}} {{command_arguments}}"`

- Start with expression in `default.nix` in the current directory:

`nix-shell {{default.nix}}`

- Start with packages loaded from nixpkgs:

`nix-shell --packages {{package_name_1}} {{package_name_2}}`

- Start with packages loaded from specific nixpkgs revision:

`nix-shell --packages {{package_names}} -I nixpkgs={{https://github.com/NixOS/nixpkgs/archive/nixpkgs_revision.tar.gz}}`

- Evaluate rest of file in specific interpreter, for use in `#!-scripts` (see <https://nixos.org/manual/nix/stable/#use-as-a-interpreter>):

`nix-shell -i {{interpreter}} --packages {{package_names}}`

