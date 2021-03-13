---
id: common.rsstail
title: Rsstail
desc: ''
updated: 1615663978733
created: 1615663978733
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# rsstail

> `tail` for RSS feeds.
> More information: <https://github.com/gvalkov/rsstail.py>.

- Show the feed of a given url and wait for new entries appearing at the bottom:

`rsstail -u {{url}}`

- Show the feed in reverse chronological order (newer at the bottom):

`rsstail -r -u {{url}}`

- Include publication date and link:

`rsstail -pl -u {{url}}`

- Set update interval:

`rsstail -u {{url}} -i {{interval_in_seconds}}`

- Show feed and exit:

`rsstail -1 -u {{url}}`

