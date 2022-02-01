---
id: common.doctl-balance
title: Doctl Balance
desc: ''
updated: 1642441815010
created: 1642441815010
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# doctl balance

> Show the balance of a Digital Ocean account.
> More information: <https://docs.digitalocean.com/reference/doctl/reference/balance/>.

- Get balance of the account associated with the current context:

`doctl balance get`

- Get the balance of an account associated with an access token:

`doctl balance get --access-token {{access_token}}`

- Get the balance of an account associated with a specified context:

`doctl balance get --context`

