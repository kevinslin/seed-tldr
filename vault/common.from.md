---
id: common.from
title: From
desc: ''
updated: 1615663978710
created: 1615663978710
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# from

> Prints mail header lines from the current user's mailbox.
> More information: <https://mailutils.org/manual/html_chapter/Programs.html#frm-and-from>.

- List mail:

`from`

- Display the number of messages stored:

`from --count`

- List mail in the specified mailbox directory:

`MAIL={{path/to/mailbox}} from`

- Print the mail from the specified address:

`from --sender={{me@example.com}}`

