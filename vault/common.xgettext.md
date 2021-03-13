---
id: common.xgettext
title: Xgettext
desc: ''
updated: 1615655543093
created: 1615655543093
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
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

