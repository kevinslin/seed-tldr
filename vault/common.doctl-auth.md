---
id: common.doctl-auth
title: Doctl Auth
desc: ''
updated: 1645138900893
created: 1645138900893
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# doctl auth

> Authenticate doctl with one or more API tokens.
> More information: <https://docs.digitalocean.com/reference/doctl/reference/auth/>.

- Open a prompt to enter an API token and label its context:

`doctl auth init --context {{token_label}}`

- List authentication contexts (API tokens):

`doctl auth list`

- Switch contexts (API tokens):

`doctl auth switch --context {{token_label}}`

- Remove a stored authentication context (API token):

`doctl auth remove --context {{token_label}}`

- Show available commands:

`doctl auth --help`

