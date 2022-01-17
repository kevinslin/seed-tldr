---
id: common.mosquitto_passwd
title: Mosquitto_passwd
desc: ''
updated: 1642441815048
created: 1642441815048
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# mosquitto_passwd

> Manage password files for mosquitto.
> See also `mosquitto`, the MQTT server that this manages.
> More information: <https://mosquitto.org/man/mosquitto_passwd-1.html>.

- Add a new user to a password file (will prompt to enter the password):

`mosquitto_passwd {{path/to/password_file}} {{username}}`

- Create the password file if it doesn't already exist:

`mosquitto_passwd -c {{path/to/password_file}} {{username}}`

- Delete the specified username instead:

`mosquitto_passwd -D {{path/to/password_file}} {{username}}`

- Upgrade an old plain-text password file to a hashed password file:

`mosquitto_passwd -U {{path/to/password_file}}`

