---
id: common.john
title: John
desc: ''
updated: 1642441815037
created: 1642441815037
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# john

> Password cracker.
> More information: <https://www.openwall.com/john/>.

- Crack password hashes:

`john {{path/to/hashes.txt}}`

- Show passwords cracked:

`john --show {{path/to/hashes.txt}}`

- Display users' cracked passwords by user identifier from multiple files:

`john --show --users={{user_ids}} {{path/to/hashes*}} {{path/to/other/hashes*}}`

- Crack password hashes, using a custom wordlist:

`john --wordlist={{path/to/wordlist.txt}} {{path/to/hashes.txt}}`

- List available hash formats:

`john --list=formats`

- Crack password hashes, using a specific hash format:

`john --format={{md5crypt}} {{path/to/hashes.txt}}`

- Crack password hashes, enabling word mangling rules:

`john --rules {{path/to/hashes.txt}}`

- Restore an interrupted cracking session from a state file, e.g. `mycrack.rec`:

`john --restore={{path/to/mycrack.rec}}`

