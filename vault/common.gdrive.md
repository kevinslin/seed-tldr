---
id: common.gdrive
title: Gdrive
desc: ''
updated: 1642441815019
created: 1642441815019
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# gdrive

> Command-line tool to interact with Google Drive.
> Folder/file ID can be obtained from the Google Drive folder or ID URL.
> More information: <https://github.com/gdrive-org/gdrive>.

- Upload a local path to the parent folder with the specified ID:

`gdrive upload -p {{id}} {{path/to/file_or_folder}}`

- Download file or directory by ID to current directory:

`gdrive download {{id}}`

- Download to a given local path by its ID:

`gdrive download --path {{path/to/folder}} {{id}}`

- Create a new revision of an ID using a given file or folder:

`gdrive update {{id}} {{path/to/file_or_folder}}`

