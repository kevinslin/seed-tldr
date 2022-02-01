---
id: common.pio-run
title: Pio Run
desc: ''
updated: 1642441815059
created: 1642441815059
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pio run

> Run PlatformIO project targets.
> More information: <https://docs.platformio.org/en/latest/core/userguide/cmd_run.html>.

- List all available project targets:

`pio run --list-targets`

- List all available project targets of a specific environment:

`pio run --list-targets --environment {{environment}}`

- Run all targets:

`pio run`

- Run all targets of specified environments:

`pio run --environment {{environment1}} --environment {{environment2}}`

- Run specified targets:

`pio run --target {{target1}} --target {{target2}}`

- Run the targets of a specified configuration file:

`pio run --project-conf {{path/to/platformio.ini}}`

