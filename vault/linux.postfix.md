---
id: linux.postfix
title: Postfix
desc: ''
updated: 1615655543107
created: 1615655543107
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
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

