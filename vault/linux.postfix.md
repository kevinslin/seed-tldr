---
id: linux.postfix
title: Postfix
desc: ''
updated: 1623965016167
created: 1623965016167
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# postfix

> Postfix mail transfer agent (MTA) control program.
> See also `dovecot`, a mail delivery agent (MDA) that integrates with Postfix.
> More information: <http://postfix.org>.

- Check the configuration:

`sudo postfix check`

- Check the status of the Postfix daemon:

`sudo postfix status`

- Start Postfix:

`sudo postfix start`

- Gracefully stop Postfix:

`sudo postfix stop`

- Flush the mail queue:

`sudo postfix flush`

- Reload the configuration files:

`sudo postfix reload`

