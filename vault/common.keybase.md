---
id: common.keybase
title: Keybase
desc: ''
updated: 1642441815038
created: 1642441815038
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# keybase

> Key directory that maps social media identities to encryption keys in a publicly auditable manner.
> More information: <https://keybase.io/docs/command_line>.

- Follow another user:

`keybase follow {{username}}`

- Add a new proof:

`keybase prove {{service}} {{service_username}}`

- Sign a file:

`keybase sign --infile {{input_file}} --outfile {{output_file}}`

- Verify a signed file:

`keybase verify --infile {{input_file}} --outfile {{output_file}}`

- Encrypt a file:

`keybase encrypt --infile {{input_file}} --outfile {{output_file}} {{receiver}}`

- Decrypt a file:

`keybase decrypt --infile {{input_file}} --outfile {{output_file}}`

- Revoke current device, log out, and delete local data:

`keybase deprovision`

