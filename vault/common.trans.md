---
id: common.trans
title: Trans
desc: ''
updated: 1623965306213
created: 1623965306213
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# trans

> Translate Shell is a command-line translator.
> More information: <https://github.com/soimort/translate-shell>.

- Translate a word (language is detected automatically):

`trans "{{word_or_sentence_to_translate}}"`

- Get a brief translation:

`trans --brief "{{word_or_sentence_to_translate}}"`

- Translate a word into french:

`trans :{{fr}} {{word}}`

- Translate a word from German to English:

`trans {{de}}:{{en}} {{Schmetterling}}`

- Behave like a dictionary to get the meaning of a word:

`trans -d {{word}}`

