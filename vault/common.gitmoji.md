---
id: common.gitmoji
title: Gitmoji
desc: ''
updated: 1623965306189
created: 1623965306189
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# gitmoji

> An interactive command-line tool for using emojis on commits.
> More information: <https://github.com/carloscuesta/gitmoji-cli>.

- Start the commit wizard:

`gitmoji --commit`

- Initialize the git hook (so `gitmoji` will be run every time `git commit` is run):

`gitmoji --init`

- Remove the git hook:

`gitmoji --remove`

- List all available emojis and their descriptions:

`gitmoji --list`

- Search emoji list for a list of keywords:

`gitmoji --search {{keyword1}} {{keyword2}}`

- Update cached list of emojis from main repository:

`gitmoji --update`

- Configure global preferences:

`gitmoji --config`

