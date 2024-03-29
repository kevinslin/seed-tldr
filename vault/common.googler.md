---
id: common.googler
title: Googler
desc: ''
updated: 1642441815030
created: 1642441815030
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# googler

> Search Google from command-line.
> More information: <https://github.com/jarun/googler>.

- Search Google for a keyword:

`googler {{keyword}}`

- Search Google and open the first result in web browser:

`googler -j {{keyword}}`

- Show N search results (default 10):

`googler -n {{N}} {{keyword}}`

- Disable automatic spelling correction:

`googler -x {{keyword}}`

- Search one site for a keyword:

`googler -w {{site}} {{keyword}}`

- Show Google search result in JSON format:

`googler --json {{keyword}}`

- Perform in-place self-upgrade:

`googler -u`

- For more help in interactive mode:

`?`

