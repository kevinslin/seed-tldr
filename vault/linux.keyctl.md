---
id: linux.keyctl
title: Keyctl
desc: ''
updated: 1642441815100
created: 1642441815100
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# keyctl

> Manipulate the Linux kernel keyring.
> More information: <https://manned.org/keyctl>.

- List keys in a specific keyring:

`keyctl list {{target_keyring}}`

- List current keys in the user default session:

`keyctl list {{@us}}`

- Store a key in a specific keyring:

`keyctl add {{type_keyring}} {{key_name}} {{key_value}} {{target_keyring}}`

- Store a key with its value from standard input:

`echo -n {{key_value}} | keyctl padd {{type_keyring}} {{key_name}} {{target_keyring}}`

- Put a timeout on a key:

`keyctl timeout {{key_name}} {{timeout_in_seconds}}`

- Read a key and format it as a hex-dump if not printable:

`keyctl read {{key_name}}`

- Read a key and format as-is:

`keyctl pipe {{key_name}}`

- Revoke a key and prevent any further action on it:

`keyctl revoke {{key_name}}`

