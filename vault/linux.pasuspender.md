---
id: linux.pasuspender
title: Pasuspender
desc: ''
updated: 1615663978752
created: 1615663978752
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pasuspender

> Temporarily suspends `pulseaudio` while another command is running to allow access to alsa.

- Suspend pulseaudio while running `jackd`:

`pasuspender -- {{jackd -d alsa --device hw:0}}`

