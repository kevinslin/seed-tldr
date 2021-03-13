---
id: linux.notify-send
title: Notify Send
desc: ''
updated: 1615655543106
created: 1615655543106
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
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

