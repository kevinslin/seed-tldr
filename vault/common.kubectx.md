---
id: common.kubectx
title: Kubectx
desc: ''
updated: 1623965306194
created: 1623965306194
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# kubectx

> Utility to manage and switch between `kubectl` contexts.
> More information: <https://github.com/ahmetb/kubectx>.

- List the contexts:

`kubectx`

- Switch to a named context:

`kubectx {{name}}`

- Switch to the previous context:

`kubectx -`

- Delete a named context:

`kubectx -d {{name}}`

