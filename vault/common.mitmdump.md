---
id: common.mitmdump
title: Mitmdump
desc: ''
updated: 1615663978723
created: 1615663978723
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# mitmdump

> View, record, and programmatically transform HTTP traffic.
> The command-line counterpart to mitmproxy.
> More information: <https://docs.mitmproxy.org/stable/overview-tools/#mitmdump>.

- Start a proxy and save all output to a file:

`mitmdump -w {{filename}}`

- Filter a saved traffic file to just POST requests:

`mitmdump -nr {{input_filename}} -w {{output_filename}} "{{~m post}}"`

- Replay a saved traffic file:

`mitmdump -nc {{filename}}`

