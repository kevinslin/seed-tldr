---
id: osx.textutil
title: Textutil
desc: ''
updated: 1615655543116
created: 1615655543116
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# textutil

> Used to manipulate text files of various formats.

- Display information about `foo.rtf`:

`textutil -info {{foo.rtf}}`

- Convert `foo.rtf` into `foo.html`:

`textutil -convert {{html}} {{foo.rtf}}`

- Convert rich text to normal text:

`textutil {{foo.rtf}} -convert {{txt}}`

- Convert `foo.txt` into `foo.rtf`, using Times 10 for the font:

`textutil -convert {{rtf}} -font {{Times}} -fontsize {{10}} {{foo.txt}}`

- Load all RTF files in the current directory, concatenates their contents, and writes the result out as `index.html` with the HTML title set to "Several Files":

`textutil -cat {{html}} -title "Several Files" -output {{index.html}} *.rtf`

