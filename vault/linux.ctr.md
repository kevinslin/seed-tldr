---
id: linux.ctr
title: Ctr
desc: ''
updated: 1615663978743
created: 1615663978743
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ctr

> Manage Containerd containers and images.
> More information: <https://containerd.io>.

- List all containers (running and stopped):

`ctr containers list`

- List all images:

`ctr images list`

- Pull an image:

`ctr images pull {{image}}`

- Tag an image:

`ctr images tag {{souce_image}}:{{source_tag}}  {{target_image}}:{{target_tag}}`

