---
id: common.git-notes
title: Git Notes
desc: ''
updated: 1623965016128
created: 1623965016128
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# git notes

> Add or inspect object notes.
> More information: <https://git-scm.com/docs/git-notes>.

- List all notes and the objects they are attached to:

`git notes list`

- List all notes attached to a given object (defaults to HEAD):

`git notes list [{{object}}]`

- Show the notes attached to a given object (defaults to HEAD):

`git notes show [{{object}}]`

- Append a note to a specified object (opens the default text editor):

`git notes append {{object}}`

- Append a note to a specified object, specifying the message:

`git notes append --message="{{message_text}}"`

- Edit an existing note (defaults to HEAD):

`git notes edit [{{object}}]`

- Copy a note from one object to another:

`git notes copy {{source_object}} {{target_object}}`

- Remove all the notes added to a specified object:

`git notes remove {{object}}`

