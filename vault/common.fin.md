---
id: common.fin
title: Fin
desc: ''
updated: 1615663978709
created: 1615663978709
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# fin

> Docksal command line utility.
> More information: <https://docs.docksal.io/fin/fin/>.

- Start the project in the current directory:

`fin project start`

- Stop the project in the current directory:

`fin project stop`

- Open a shell into a specific container:

`fin bash {{container_name}}`

- Display logs of a specific container:

`fin logs {{container_name}}`

- Display logs of a specific container and follow the log:

`fin logs -f {{container_name}}`
