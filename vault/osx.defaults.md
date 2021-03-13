---
id: osx.defaults
title: Defaults
desc: ''
updated: 1615655543113
created: 1615655543113
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
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

