---
id: common.pickle
title: Pickle
desc: ''
updated: 1642441815057
created: 1642441815057
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pickle

> A PHP extension installer based on Composer.
> More information: <https://github.com/FriendsOfPHP/pickle>.

- Install a specific PHP extension:

`pickle install {{extension_name}}`

- Convert an existing PECL extension configuration to a Pickle configuration file:

`pickle convert {{path/to/directory}}`

- Validate a PECL extension:

`pickle validate {{path/to/directory}}`

- Package a PECL extension for release:

`pickle release {{path/to/directory}}`

