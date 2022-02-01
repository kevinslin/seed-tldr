---
id: linux.pridecat
title: Pridecat
desc: ''
updated: 1642441815108
created: 1642441815108
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pridecat

> Like cat but more colorful :).
> More information: <https://github.com/lunasorcery/pridecat>.

- Print the contents of a file in pride colors to the standard output:

`pridecat {{file}}`

- Print contents of a file in trans colors:

`pridecat {{file}} --{{transgender|trans}}`

- Alternate between lesbian and bisexual pride flags:

`pridecat {{file}} --lesbian --bi`

- Print contents of a file with the background colors changed:

`pridecat {{file}} -b`

- List directory contents in pride flag colors:

`ls | pridecat --{{flag}}`

