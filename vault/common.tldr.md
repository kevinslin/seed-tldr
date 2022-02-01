---
id: common.tldr
title: Tldr
desc: ''
updated: 1642441815076
created: 1642441815076
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# tldr

> Displays simple help pages for command-line tools, from the tldr-pages project.
> More information: <https://tldr.sh>.

- Show the tldr page for a command (hint: this is how you got here!):

`tldr {{command}}`

- Show the tldr page for `cd`, overriding the default platform:

`tldr -p {{android|linux|osx|sunos|windows}} {{cd}}`

- Show the tldr page for a subcommand:

`tldr {{git-checkout}}`

- Update local pages (if the client supports caching):

`tldr -u`

