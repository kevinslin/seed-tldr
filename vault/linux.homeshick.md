---
id: linux.homeshick
title: Homeshick
desc: ''
updated: 1623965016162
created: 1623965016162
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
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

