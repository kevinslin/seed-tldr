---
id: common.buzzphrase
title: Buzzphrase
desc: ''
updated: 1642441815000
created: 1642441815000
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# buzzphrase

> Node.js command-line tool to output a random buzzphrase.
> More information: <https://github.com/atomantic/buzzphrase>.

- Generate a string of three random phrases containing an adjective, a past tense verb and a plural noun:

`buzzphrase`

- Output a phrase formatted as [i]mperative verb + past tense [v]erb + [a]djective + plural [N]oun:

`buzzphrase {{'{i} {v} {a} {N}'}}`

- Output 4 phrases formatted as present participle [V]erb + [a]djective + singular [n]oun + [f]inal:

`buzzphrase {{4 '{V} {a} {n} {f}'}}`

