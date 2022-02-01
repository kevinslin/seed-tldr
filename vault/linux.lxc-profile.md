---
id: linux.lxc-profile
title: Lxc Profile
desc: ''
updated: 1642441815102
created: 1642441815102
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# lxc profile

> Manage profiles for LXD containers.
> More information: <https://linuxcontainers.org/lxd/docs/master/profiles>.

- List all available profiles:

`lxc profile list`

- Show the configuration of a specific profile:

`lxc profile show {{profile_name}}`

- Edit a specific profile in the default editor:

`lxc profile edit {{profile_name}}`

- Edit a specific profile importing the configuration values from a file:

`lxc profile edit {{profile_name}} < {{config.yaml}}`

- Launch a new container with specific profiles:

`lxc launch {{container_image}} {{container_name}} --profile {{profile1}} --profile {{profile2}}`

- Change the profiles of a running container:

`lxc profile assign {{container_name}} {{profile1,profile2}}`

