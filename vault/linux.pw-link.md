---
id: linux.pw-link
title: Pw Link
desc: ''
updated: 1643509837368
created: 1643509837368
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pw-link

> Manage links between ports in PipeWire.
> More information: <https://gitlab.freedesktop.org/pipewire/pipewire/-/wikis/Virtual-Devices>.

- List all audio output and input ports:

`pw-link --output --input'`

- Create a link between an output and an input port:

`pw-link {{output_port_name}} {{input_port_name}}`

- Disconnect two ports:

`pw-link --disconnect {{output_port_name}} {{input_port_name}}`

- Display help:

`pw-link -h`

