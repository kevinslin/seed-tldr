---
id: linux.amixer
title: Amixer
desc: ''
updated: 1615663978741
created: 1615663978741
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# amixer

> Mixer for ALSA soundcard driver.

- Turn up the master volume by 10%:

`amixer -D pulse sset Master {{10%+}}`

- Turn down the master volume by 10%:

`amixer -D pulse sset Master {{10%-}}`

