---
id: linux.nixos-container
title: Nixos Container
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
# nixos-container

> Starts NixOS containers using Linux containers.
> More information: <https://nixos.org/manual/nixos/stable/#ch-containers>.

- List running containers:

`sudo nixos-container list`

- Create a NixOS container with a specific configuration file:

`sudo nixos-container create {{container_name}} --config-file {{nix_config_file_path}}`

- Start, stop, terminate, or destroy a specific container:

`sudo nixos-container {{start|stop|terminate|destroy|status}} {{container_name}}`

- Run a command in a running container:

`sudo nixos-container run {{container_name}} -- {{command}} {{command_arguments}}`

- Update a container configuration:

`sudo $EDITOR /var/lib/container/{{container_name}}/etc/nixos/configuration.nix && sudo nixos-container update {{container_name}}`

- Enter an interactive shell session on an already-running container:

`sudo nixos-container root-login {{container_name}}`

