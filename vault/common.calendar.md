---
id: common.calendar
title: Calendar
desc: ''
updated: 1615663978702
created: 1615663978702
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# calendar

> Display upcoming events from a calendar file.

- Show events for today and tomorrow (or the weekend on Friday) from the default calendar:

`calendar`

- Look [A]head, showing events for the next 30 days:

`calendar -A {{30}}`

- Look [B]ack, showing events for the previous 7 days:

`calendar -B {{7}}`

- Show events from a custom calendar [f]ile:

`calendar -f {{path/to/file}}`

