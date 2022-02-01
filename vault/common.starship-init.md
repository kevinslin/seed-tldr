---
id: common.starship-init
title: Starship Init
desc: ''
updated: 1642441815071
created: 1642441815071
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# starship init

> Print shell integration code for starship.
> More information: <https://starship.rs>.

- Display the subcommand help:

`starship init --help`

- Print the starship integration code for the specified shell:

`starship init {{bash|elvish|fish|ion|powershell|tcsh|zsh}}`

- Append the `starship` integration code to `~/.bashrc`:

`starship init {{bash}} >> {{~/.bashrc}}`

- Append the `starship` integration code to `~/.zshrc`:

`starship init {{zsh}} >> {{~/.zshrc}}`

