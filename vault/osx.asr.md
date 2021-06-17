---
id: osx.asr
title: Asr
desc: ''
updated: 1623965016172
created: 1623965016172
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# asr

> Restore (copy) a disk image onto a volume.
> The command name stands for Apple Software Restore.

- Restore a disk image to a target volume:

`sudo asr restore --source {{image_name}}.dmg --target {{path/to/volume}}`

- Erase the target volume before restoring:

`sudo asr restore --source {{image_name}}.dmg --target {{path/to/volume}} --erase`

- Skip verification after restoring:

`sudo asr restore --source {{image_name}}.dmg --target {{path/to/volume}} --noverify`

- Clone volumes without the use of an intermediate disk image:

`sudo asr restore --source {{path/to/volume}} --target {{path/to/cloned_volume}}`

