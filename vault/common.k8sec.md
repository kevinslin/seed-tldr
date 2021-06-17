---
id: common.k8sec
title: K8sec
desc: ''
updated: 1623965016134
created: 1623965016134
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# k8sec

> Command-line interface tool to manage Kubernetes secrets.
> More information: <https://github.com/dtan4/k8sec>.

- List all secrets:

`k8sec list`

- List a specific secret as a base64-encoded string:

`k8sec list {{secret_name}} --base64`

- Set a secret's value:

`k8sec set {{secret_name}} {{key=value}}`

- Set a base64-encoded value:

`k8sec set --base64 {{secret_name}} {{key=encoded_value}}`

- Unset a secret:

`k8sec unset {{secret_name}}`

- Load secrets from a file:

`k8sec load -f {{path/to/file}} {{secret_name}}`

- Dump secrets to a file:

`k8sec dump -f {{path/to/file}} {{secret_name}}`

