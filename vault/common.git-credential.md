---
id: common.git-credential
title: Git Credential
desc: ''
updated: 1642441815023
created: 1642441815023
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# git credential

> Retrieve and store user credentials.
> More information: <https://git-scm.com/docs/git-credential>.

- Display credential information, retrieving the username and password from configuration files:

`echo "{{url=http://example.com}}" | git credential fill`

- Send credential information to all configured credential helpers to store for later use:

`echo "{{url=http://example.com}}" | git credential approve`

- Erase the specified credential information from all the configured credential helpers:

`echo "{{url=http://example.com}}" | git credential reject`

