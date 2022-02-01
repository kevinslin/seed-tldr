---
id: common.abduco
title: Abduco
desc: ''
updated: 1642441814991
created: 1642441814991
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# abduco

> Terminal session manager.
> More information: <http://www.brain-dump.org/projects/abduco/>.

- List sessions:

`abduco`

- Attach to a session, creating it if it doesn't exist:

`abduco -A {{name}} {{bash}}`

- Attach to a session with `dvtm`, creating it if it doesn't exist:

`abduco -A {{name}}`

- Detach from a session:

`Ctrl + \`

- Attach to a session in read-only mode:

`abduco -Ar {{name}}`

