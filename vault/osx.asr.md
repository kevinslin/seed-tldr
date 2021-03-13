---
id: osx.asr
title: Asr
desc: ''
updated: 1615655543112
created: 1615655543112
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
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

