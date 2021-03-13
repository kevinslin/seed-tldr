---
id: windows.attrib
title: Attrib
desc: ''
updated: 1615663978762
created: 1615663978762
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# attrib

> Displays or changes file and directory attributes.
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/attrib>.

- Display the attributes of the files in the current directory:

`attrib`

- Display the attributes of the files in the current directory and sub-directories:

`attrib /S`

- Display the attributes of the files and directories in the current directory and sub-directories:

`attrib /S /D`

- Add the read-only attribute to a file:

`attrib +R {{document.txt}}`

- Remove the system and hidden attributes of a file:

`attrib -S -H {{document.txt}}`

- Add the hidden attribute to a directory:

`attrib +H {{path\to\directory}}`

