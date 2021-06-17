---
id: common.moro
title: Moro
desc: ''
updated: 1623965016137
created: 1623965016137
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# moro

> Track work time.
> More information: <https://moro.js.org>.

- Invoke `moro` without parameters, to set the current time as the start of the working day:

`moro`

- Specify a custom time for the start of the working day:

`moro hi {{09:30}}`

- Invoke `moro` without parameters a second time, to set the current time at the end of the working day:

`moro`

- Specify a custom time for the end of the working day:

`moro bye {{17:30}}`

- Add a note on the current working day:

`moro note {{3 hours on project Foo}}`

- Show a report of time logs and notes for the current working day:

`moro report`

- Show a report of time logs and notes for all working days on record:

`moro report --all`

