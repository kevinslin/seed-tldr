---
id: linux.notify-send
title: Notify Send
desc: ''
updated: 1623965306226
created: 1623965306226
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# notify-send

> Uses the current desktop environment's notification system to create a notification.

- Show a notification with the title "Test" and the content "This is a test":

`notify-send "{{Test}}" "{{This is a test}}"`

- Show a notification with a custom icon:

`notify-send -i {{icon.png}} "{{Test}}" "{{This is a test}}"`

- Show a notification for 5 seconds:

`notify-send -t 5000 "{{Test}}" "{{This is a test}}"`

- Show a notification with an app's icon:

`notify-send "{{Test}}" --icon={{google-chrome}}`

