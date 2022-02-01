---
id: linux.pasuspender
title: Pasuspender
desc: ''
updated: 1642441815107
created: 1642441815107
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pasuspender

> Temporarily suspends `pulseaudio` while another command is running to allow access to alsa.

- Suspend PulseAudio while running `jackd`:

`pasuspender -- {{jackd -d alsa --device hw:0}}`

