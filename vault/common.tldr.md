---
id: common.tldr
title: Tldr
desc: ''
updated: 1615663978736
created: 1615663978736
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# tldr

> Displays simple help pages for command-line tools, from the tldr-pages project.
> More information: <https://tldr.sh>.

- Get typical usages of a command (hint: this is how you got here!):

`tldr {{command}}`

- Show the tar tldr page for Linux:

`tldr -p {{linux}} {{tar}}`

- Get help for a Git subcommand:

`tldr {{git-checkout}}`

- Update local pages (if the client supports caching):

`tldr -u`

