---
id: common.transcrypt
title: Transcrypt
desc: ''
updated: 1642441815077
created: 1642441815077
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# transcrypt

> Transparently encrypt files within a Git repository.
> More information: <https://github.com/elasticdog/transcrypt>.

- Initialize an unconfigured repository:

`transcrypt`

- List the currently encrypted files:

`git ls-crypt`

- Display the credentials of a configured repository:

`transcrypt --display`

- Initialize and decrypt a fresh clone of a configured repository:

`transcrypt --cipher={{cipher}}`

- Rekey to change the encryption cipher or password:

`transcrypt --rekey`

