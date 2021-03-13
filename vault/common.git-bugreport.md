---
id: common.git-bugreport
title: Git Bugreport
desc: ''
updated: 1615655543057
created: 1615655543057
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# git bugreport

> Captures debug information from the system and user, generating a text file to aid in the reporting of a bug in Git.

- Create a new bugreport file in the current directory:

`git bugreport`

- Create a new bugreport file in the specified directory, creating it if it does not exist:

`git bugreport --output-directory {{path/to/directory}}`

- Create a new bugreport file with the specified filename suffix in `strftime` format:

`git bugreport --suffix {{%m%d%y}}`

