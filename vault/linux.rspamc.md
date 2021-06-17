---
id: linux.rspamc
title: Rspamc
desc: ''
updated: 1623965016168
created: 1623965016168
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# rspamc

> Command-line client for rspamd servers.

- Train the bayesian filter to recognise an email as spam:

`rspamc learn_spam {{path/to/email_file}}`

- Train the bayesian filter to recognise an email as ham:

`rspamc learn_ham {{path/to/email_file}}`

- Generate a manual report on an email:

`rspamc symbols {{path/to/email_file}}`

- Show server statistics:

`rspamc stat`

