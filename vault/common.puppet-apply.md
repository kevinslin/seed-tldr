---
id: common.puppet-apply
title: Puppet Apply
desc: ''
updated: 1642441815062
created: 1642441815062
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# puppet apply

> Apply Puppet manifests locally.
> More information: <https://puppet.com/docs/puppet/7/man/apply.html>.

- Apply a manifest:

`puppet apply {{path/to/manifest}}`

- Execute puppet code:

`puppet apply --execute {{code}}`

- Use a specific module and hiera config file:

`puppet apply --modulepath {{path/to/directory}} --hiera_config {{path/to/file}} {{path/to/manifest}}`

