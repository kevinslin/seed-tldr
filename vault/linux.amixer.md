---
id: linux.amixer
title: Amixer
desc: ''
updated: 1642441815087
created: 1642441815087
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# amixer

> Mixer for ALSA soundcard driver.
> More information: <https://manned.org/amixer>.

- Turn up the master volume by 10%:

`amixer -D pulse sset Master {{10%+}}`

- Turn down the master volume by 10%:

`amixer -D pulse sset Master {{10%-}}`

