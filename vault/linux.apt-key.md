---
id: linux.apt-key
title: Apt Key
desc: ''
updated: 1615663978741
created: 1615663978741
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# apt-key

> Key management utility for the APT Package Manager on Debian and Ubuntu.

- List trusted keys:

`apt-key list`

- Add a key to the trusted keystore:

`apt-key add {{public_key_file.asc}}`

- Delete a key from the trusted keystore:

`apt-key del {{key_id}}`

- Add a remote key to the trusted keystore:

`wget -qO - {{https://host.tld/filename.key}} | apt-key add -`

- Add a key from keyserver with only key id:

`apt-key adv --keyserver {{pgp.mit.edu}} --recv {{KEYID}}`

