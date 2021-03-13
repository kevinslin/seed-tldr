---
id: common.hunspell
title: Hunspell
desc: ''
updated: 1615655543063
created: 1615655543063
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# hunspell

> Check spelling.
> More information: <https://hunspell.github.io/>.

- Check the spelling of a file:

`hunspell {{path/to/file}}`

- Check the spelling of a file with the en_US dictionary:

`hunspell -d {{en_US}} {{path/to/file}}`

- List misspelled words in a file:

`hunspell -l {{path/to/file}}`

