---
id: osx.defaults
title: Defaults
desc: ''
updated: 1623965306233
created: 1623965306233
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# defaults

> Read and write macOS user configuration for applications.
> More information: <https://ss64.com/osx/defaults.html>.

- Read system defaults for an application option:

`defaults read {{application}} {{option}}`

- Read default values for an application option:

`defaults read -app {{application}} {{option}}`

- Search for a keyword in domain names, keys, and values:

`defaults find {{keyword}}`

- Write the default value of an application option:

`defaults write {{application}} {{option}} {{-type}} {{value}}`

- Speed up Mission Control animations:

`defaults write com.apple.Dock expose-animation-duration -float 0.1`

- Delete all defaults of an application:

`defaults delete {{application}}`

