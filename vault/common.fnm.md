---
id: common.fnm
title: Fnm
desc: ''
updated: 1642441815018
created: 1642441815018
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# fnm

> Fast Node.js version manager.
> Install, uninstall or switch between Node.js versions.
> More information: <https://github.com/Schniz/fnm>.

- Install a specific version of Node.js:

`fnm install {{node_version}}`

- List all available Node.js versions and highlight the default one:

`fnm ls`

- Use a specific version of Node.js in the current shell:

`fnm use {{node_version}}`

- Set the default Node.js version:

`fnm default {{node_version}}`

- Uninstall a given Node.js version:

`fnm uninstall {{node_version}}`

