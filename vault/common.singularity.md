---
id: common.singularity
title: Singularity
desc: ''
updated: 1623965306210
created: 1623965306210
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# singularity

> Manage Singularity containers and images.

- Download a remote image from Sylabs Cloud:

`singularity pull --name {{image.sif}} {{library://godlovedc/funny/lolcow:latest}}`

- Rebuild a remote image using latest Singularity image format:

`singularity build {{image.sif}} {{docker://godlovedc/lolcow}}`

- Start a container from an image and get a shell inside of it:

`singularity shell {{image.sif}}`

- Start a container from an image and run a command:

`singularity exec {{image.sif}} {{command}}`

- Start a container from an image and execute the internal runscript:

`singularity run {{image.sif}}`

- Build a singularity image from a recipe file:

`sudo singularity build {{image.sif}} {{recipe}}`

