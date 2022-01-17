---
id: common.keychain
title: Keychain
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
# keychain

> Re-use ssh-agent and/or gpg-agent between logins.
> More information: <http://funtoo.org/Keychain>.

- Check for a running ssh-agent, and start one if needed:

`keychain`

- Also check for gpg-agent:

`keychain --agents "{{gpg,ssh}}"`

- List signatures of all active keys:

`keychain --list`

- List fingerprints of all active keys:

`keychain --list-fp`

- Add a timeout for identities added to the agent, in minutes:

`keychain --timeout {{minutes}}`

