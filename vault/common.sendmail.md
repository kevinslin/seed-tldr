---
id: common.sendmail
title: Sendmail
desc: ''
updated: 1642441815068
created: 1642441815068
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# sendmail

> Send email from the command-line.
> More information: <https://manned.org/sendmail>.

- Send a message with the content of `message.txt` to the mail directory of local user `username`:

`sendmail {{username}} < {{message.txt}}`

- Send an email from [you@yourdomain.com](mailto:you@yourdomain.com) (assuming the mail server is configured for this) to [test@gmail.com](mailto:test@gmail.com) containing the message in `message.txt`:

`sendmail -f {{you@yourdomain.com}} {{test@gmail.com}} < {{message.txt}}`

- Send an email from [you@yourdomain.com](mailto:you@yourdomain.com) (assuming the mail server is configured for this) to [test@gmail.com](mailto:test@gmail.com) containing the file `file.zip`:

`sendmail -f {{you@yourdomain.com}} {{test@gmail.com}} < {{file.zip}}`

