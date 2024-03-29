---
id: linux.nixos-rebuild
title: Nixos Rebuild
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
# nixos-rebuild

> Reconfigure a NixOS machine.
> More information: <https://nixos.org/nixos/manual/#sec-changing-config>.

- Build and switch to the new configuration, making it the boot default:

`sudo nixos-rebuild switch`

- Build and switch to the new configuration, making it the boot default and naming the boot entry:

`sudo nixos-rebuild switch -p {{name}}`

- Build and switch to the new configuration, making it the boot default and installing updates:

`sudo nixos-rebuild switch --upgrade`

- Rollback changes to the configuration, switching to the previous generation:

`sudo nixos-rebuild switch --rollback`

- Build the new configuration and make it the boot default without switching to it:

`sudo nixos-rebuild boot`

- Build and activate the new configuration, but don't make a boot entry (for testing purposes):

`sudo nixos-rebuild test`

- Build the configuration and open it in a virtual machine:

`sudo nixos-rebuild build-vm`

