---
id: osx.afinfo
title: Afinfo
desc: ''
updated: 1615655543112
created: 1615655543112
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# afinfo

> Audio file metadata parser for OS X.
> Built-in command of OS X.

- Display info of a given audio file:

`afinfo {{path/to/file}}`

- Print a one line description of the audio file:

`afinfo -b {{path/to/file}}`

- Print metadata info and contents of the audio file's InfoDictionary:

`afinfo -i {{path/to/file}}`

- Print output in xml format:

`afinfo -x {{path/to/file}}`

- Print warnings for the audio file if any:

`afinfo --warnings {{path/to/file}}`

- Display help for full usage:

`afinfo -h`

