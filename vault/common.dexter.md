---
id: common.dexter
title: Dexter
desc: ''
updated: 1642441815007
created: 1642441815007
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# dexter

> Tool for authenticating the kubectl users with OpenId Connect.
> More information: <https://github.com/gini/dexter>.

- Create and authenticate a user with Google OIDC:

`dexter auth -i {{client_id}} -s {{client_secret}}`

- Override the default kube config location:

`dexter auth -i {{client_id}} -s {{client_secret}} --kube-config {{sample/config}}`

