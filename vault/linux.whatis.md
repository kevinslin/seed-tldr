---
id: linux.whatis
title: Whatis
desc: ''
updated: 1615655543111
created: 1615655543111
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# whatis

> Display one-line descriptions from manual pages.

- Display a description from a man page:

`whatis {{command}}`

- Don't cut the description off at the end of the line:

`whatis --long {{command}}`

- Display descriptions for all commands matching a glob:

`whatis --wildcard {{net*}}`

- Search man page descriptions with a regular expression:

`whatis --regex '{{wish[0-9]\.[0-9]}}'`

