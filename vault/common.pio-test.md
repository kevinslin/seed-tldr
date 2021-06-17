---
id: common.pio-test
title: Pio Test
desc: ''
updated: 1623965306205
created: 1623965306205
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pio test

> Run local tests on a PlatformIO project.
> More information: <https://docs.platformio.org/en/latest/core/userguide/cmd_test.html>.

- Run all tests in all environments of the current PlatformIO project:

`pio test`

- Test only specific environments:

`pio test --environment {{environment1}} --environment {{environment2}}`

- Run only tests whose name matches a specific glob pattern:

`pio test --filter "{{pattern}}"`

- Ignore tests whose name matches a specific glob pattern:

`pio test --ignore "{{pattern}}"`

- Specify a port for firmware uploading:

`pio test --upload-port {{upload_port}}`

- Specify a custom configuration file for running the tests:

`pio test --project-conf {{path/to/platformio.ini}}`

