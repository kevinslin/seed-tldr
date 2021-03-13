---
id: common.calendar
title: Calendar
desc: ''
updated: 1615655543047
created: 1615655543047
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
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

