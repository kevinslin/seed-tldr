---
id: common.phpstan
title: Phpstan
desc: ''
updated: 1615663978730
created: 1615663978730
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# phpstan

> A PHP static analysis tool to discover bugs in code.
> More information: <https://github.com/phpstan/phpstan>.

- Display available options for analysis:

`phpstan analyse --help`

- Analyse the specified space-separated directories:

`phpstan analyse {{path/to/directory}}`

- Analyse a directory using a configuration file:

`phpstan analyse {{path/to/directory}} --configuration {{path/to/config}}`

- Analyse using a specific rule level (0-7, higher is stricter):

`phpstan analyse {{path/to/directory}} --level {{level}}`

- Specify an autoload file to load before analysing:

`phpstan analyse {{path/to/directory}} --autoload-file {{path/to/autoload_file}}`

- Specify a memory limit during analysis:

`phpstan analyse {{path/to/directory}} --memory-limit {{memory_limit}}`

