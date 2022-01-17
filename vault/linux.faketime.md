---
id: linux.faketime
title: Faketime
desc: ''
updated: 1642441815094
created: 1642441815094
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# faketime

> Fake the system time for a given command.
> More information: <https://manned.org/faketime>.

- Fake the time to this evening, before printing the result of `date`:

`faketime '{{today 23:30}}' {{date}}`

- Open a new `bash` shell, which uses yesterday as the current date:

`faketime '{{yesterday}}' {{bash}}`

- Simulate how a program would act next Friday night:

`faketime '{{next Friday 1 am}}' {{path/to/program}}`

