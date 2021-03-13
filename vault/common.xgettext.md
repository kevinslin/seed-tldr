---
id: common.xgettext
title: Xgettext
desc: ''
updated: 1615663978740
created: 1615663978740
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# xgettext

> Extract gettext strings from code files.
> More information: <https://www.gnu.org/software/gettext/manual/html_node/xgettext-Invocation.html>.

- Scan file and output strings to `messages.po`:

`xgettext {{path/to/input_file}}`

- Use a different output filename:

`xgettext --output {{path/to/output_file}} {{path/to/input_file}}`

- Append new strings to an existing file:

`xgettext --join-existing --output {{path/to/output_file}} {{path/to/input_file}}`

- Don't add a header containing metadata to the output file:

`xgettext --omit-header {{path/to/input_file}}`

