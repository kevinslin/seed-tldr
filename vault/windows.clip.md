---
id: windows.clip
title: Clip
desc: ''
updated: 1642441815126
created: 1642441815126
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# clip

> Copy input content to the Windows clipboard.
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/clip>.

- Pipe command-line output to the Windows clipboard:

`{{dir}} | clip`

- Copy the contents of a file to the Windows clipboard:

`clip < {{path/to/file.ext}}`

- Copy text with a trailing newline to the Windows clipboard:

`echo {{some text}} | clip`

- Copy text without a trailing newline to the Windows clipboard:

`echo | set /p="some text" | clip`

