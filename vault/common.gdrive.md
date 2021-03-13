---
id: common.gdrive
title: Gdrive
desc: ''
updated: 1615663978711
created: 1615663978711
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# gdrive

> Command line tool to interact with Google Drive.
> Folder/file id can be obtained from the Google Drive folder or id url.
> More information: <https://github.com/gdrive-org/gdrive>.

- Upload a local path to the parent folder with the specified id:

`gdrive upload -p {{id}} {{path/to/file_or_folder}}`

- Download file or directory by id to current directory:

`gdrive download {{id}}`

- Download to a given local path by its id:

`gdrive download --path {{path/to/folder}} {{id}}`

- Create a new revision of an id using a given file or folder:

`gdrive update {{id}} {{path/to/file_or_folder}}`

