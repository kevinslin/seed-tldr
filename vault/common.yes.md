---
id: common.yes
title: 'Yes'
desc: ''
updated: 1623965306217
created: 1623965306217
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# yes

> Output something repeatedly.
> This command is commonly used to answer yes to every prompt by install commands (such as apt-get).
> More information: <https://www.gnu.org/software/coreutils/yes>.

- Repeatedly output "message":

`yes {{message}}`

- Repeatedly output "y":

`yes`

- Accept everything prompted by the `apt-get` command:

`yes | sudo apt-get install {{program}}`

