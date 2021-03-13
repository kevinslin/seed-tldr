---
id: common.msmtp
title: Msmtp
desc: ''
updated: 1615655543072
created: 1615655543072
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# msmtp

> An SMTP client.
> It reads text from standard input and sends it to an SMTP server.
> More information: <https://marlam.de/msmtp>.

- Send an email using the default account configured in `~/.msmtprc`:

`echo "{{Hello world}}" | msmtp {{to@example.org}}`

- Send an email using a specific account configured in `~/.msmtprc`:

`echo "{{Hello world}}" | msmtp --account={{account_name}} {{to@example.org}}`

- Send an email without a configured account. The password should be specified in the `~/.msmtprc` file:

`echo "{{Hello world}}" | msmtp --host={{localhost}} --port={{999}} --from={{from@example.org}} {{to@example.org}}`

