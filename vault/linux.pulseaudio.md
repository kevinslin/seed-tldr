---
id: linux.pulseaudio
title: Pulseaudio
desc: ''
updated: 1623965306228
created: 1623965306228
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pulseaudio

> The pulseaudio sound system daemon and manager.
> More information: <https://www.freedesktop.org/wiki/Software/PulseAudio/>.

- Check if pulseaudio is running (a non-zero exit code means it is not running):

`pulseaudio --check`

- Start the pulseaudio daemon in the background:

`pulseaudio --start`

- Kill the running pulseaudio daemon:

`pulseaudio --kill`

- List available modules:

`pulseaudio --dump-modules`

- Load a module into the currently running daemon with the specified arguments:

`pulseaudio --load="{{module_name}} {{arguments}}"`

