---
id: linux.homeshick
title: Homeshick
desc: ''
updated: 1615655543102
created: 1615655543102
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# homeshick

> Synchronize Git dotfiles.
> More information: <https://github.com/andsens/homeshick/wiki>.

- Create a new castle:

`homeshick generate {{castle_name}}`

- Add a file to your castle:

`homeshick track {{castle_name}} {{path/to/file}}`

- Go to a castle:

`homeshick cd {{castle_name}}`

- Clone a castle:

`homeshick clone {{github_username}}/{{repository_name}}`

- Symlink all files from a castle:

`homeshick link {{castle_name}}`

