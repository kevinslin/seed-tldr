---
id: common.pueue-completions
title: Pueue Completions
desc: ''
updated: 1642441815061
created: 1642441815061
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pueue completions

> Generates shell completion files for Bash, Elvish, Fish, PowerShell, and Zsh.
> More information: <https://github.com/Nukesor/pueue>.

- Generate completions for Bash:

`sudo pueue completions bash {{/usr/share/bash-completion/completions/pueue.bash}}`

- Generate completions for zsh:

`sudo pueue completions zsh {{/usr/share/zsh/site-functions}}`

- Generate completions for fish:

`sudo pueue completions fish {{/usr/share/fish/completions}}`

