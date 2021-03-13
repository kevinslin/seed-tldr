---
id: linux.pasuspender
title: Pasuspender
desc: ''
updated: 1615655543107
created: 1615655543107
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# pasuspender

> Temporarily suspends `pulseaudio` while another command is running to allow access to alsa.

- Suspend pulseaudio while running `jackd`:

`pasuspender -- {{jackd -d alsa --device hw:0}}`

