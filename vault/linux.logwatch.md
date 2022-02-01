---
id: linux.logwatch
title: Logwatch
desc: ''
updated: 1642441815101
created: 1642441815101
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# logwatch

> Summarizes many different logs for common services (e.g. apache, pam_unix, sshd, etc.) in a single report.
> More information: <https://manned.org/logwatch>.

- Analyze logs for a range of dates at a certain level of detail:

`logwatch --range {{yesterday|today|all|help}} --detail {{low|medium|others}}'`

- Restrict report to only include information for a selected service:

`logwatch --range {{all}} --service {{apache|pam_unix|etc}}`

