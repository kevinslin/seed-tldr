---
id: common.leave
title: Leave
desc: ''
updated: 1615663978721
created: 1615663978721
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# leave

> Remind when it's time to leave.
> To remove reminders use `kill $(pidof leave)`.

- Set a reminder at a given time:

`leave {{time_to_leave}}`

- Remind to leave at noon:

`leave {{1200}}`

- Set a reminder in a specific amount of time:

`leave +{{amount_of_time}}`

- Remind to leave in 4 hours and 4 minutes:

`leave +{{0404}}`
