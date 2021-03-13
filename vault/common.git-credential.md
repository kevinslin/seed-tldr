---
id: common.git-credential
title: Git Credential
desc: ''
updated: 1615655543058
created: 1615655543058
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
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

