---
id: common.buku
title: Buku
desc: ''
updated: 1623965306176
created: 1623965306176
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# buku

> Command-line browser-independent bookmark manager.
> More information: <https://github.com/jarun/Buku>.

- Display all bookmarks matching "keyword" and with "privacy" tag:

`buku {{keyword}} --stag {{privacy}}`

- Add bookmark with tags "search engine" and "privacy":

`buku --add {{https://example.com}} {{search engine}}, {{privacy}}`

- Delete a bookmark:

`buku --delete {{bookmark_id}}`

- Open editor to edit a bookmark:

`buku --write {{bookmark_id}}`

- Remove "search engine" tag from a bookmark:

`buku --update {{bookmark_id}} --tag {{-}} {{search engine}}`

