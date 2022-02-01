---
id: linux.xwinwrap
title: Xwinwrap
desc: ''
updated: 1642441815119
created: 1642441815119
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# xwinwrap

> Run a player or a program as desktop background.
> More information: <https://github.com/ujjwal96/xwinwrap>.

- Run a video using mpv:

`xwinwrap -b -nf -ov -- {{mpv}} -wid {{wid}} --loop --no-audio --no-resume-playback --panscan={{1.0}} {{path/to/video.mp4}}`

- Run a video in fullscreen using mpv:

`xwinwrap -b -nf -fs -ov -- {{mpv}} -wid {{wid}} --loop --no-audio --no-resume-playback --panscan={{1.0}} {{path/to/video.mp4}}`

- Run a video using mpv with 80% opacity:

`xwinwrap -b -nf -ov -o 0.8 --- {{mpv}} -wid {{wid}} --loop --no-audio --no-resume-playback --panscan={{1.0}} {{path/to/video.mp4}}`

- Run a video using mpv in a second monitor 1600x900 with 1920 offset on X-axis:

`xwinwrap -g 1600x900+1920 -b -nf -ov -- {{mpv}} -wid {{wid}} --loop --no-audio --no-resume-playback --panscan={{1.0}} {{path/to/video.mkv}}`

