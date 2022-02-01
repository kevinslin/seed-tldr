---
id: common.git-secret
title: Git Secret
desc: ''
updated: 1642441815026
created: 1642441815026
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# git secret

> Bash tool which stores private data inside a Git repository.
> More information: <https://github.com/sobolevn/git-secret>.

- Initialize `git-secret` in a local repository:

`git secret init`

- Grant access to the current Git user's email:

`git secret tell -m`

- Grant access by email:

`git secret tell {{email}}`

- Revoke access by email:

`git secret killperson {{email}}`

- List emails with access to secrets:

`git secret whoknows`

- Register a secret file:

`git secret add {{path/to/file}}`

- Encrypt secrets:

`git secret hide`

- Decrypt secret files:

`git secret reveal`

