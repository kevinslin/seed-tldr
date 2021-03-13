---
id: linux.aplay
title: Aplay
desc: ''
updated: 1615663978741
created: 1615663978741
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# aplay

> Command-line sound player for ALSA soundcard driver.
> More information: <https://linux.die.net/man/1/aplay>.

- Play a specific file (sampling rate, bit depth, etc. will be automatically determined for the file format):

`aplay {{path/to/file}}`

- Play the first 10 seconds of a specific file at 2500Hz:

`aplay --duration={{10}} --rate={{2500}} {{path/to/file}}`

- Play the raw file as a 22050Hz, mono, 8-bit, Mu-Law `.au` file:

`aplay --channels={{1}} --file-type {{raw}} --rate={{22050}} --format={{mu_law}} {{path/to/file}}`

