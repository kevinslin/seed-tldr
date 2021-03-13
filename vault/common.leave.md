---
id: common.leave
title: Leave
desc: ''
updated: 1615655543067
created: 1615655543067
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
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

