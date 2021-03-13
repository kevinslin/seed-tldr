---
id: linux.kreadconfig5
title: Kreadconfig5
desc: ''
updated: 1615663978748
created: 1615663978748
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# kreadconfig5

> Read KConfig entries for KDE Plasma.
> More information: <https://userbase.kde.org/KDE_System_Administration/Configuration_Files>.

- Read a key from the global configuration:

`kreadconfig5 --group {{group_name}} --key {{key_name}}`

- Read a key from a specific configuration file:

`kwriteconfig5 --file {{path/to/file}} --group {{group_name}} --key {{key_name}}`

- Check if systemd is used to start the Plasma session:

`kreadconfig5 --file {{startkderc}} --group {{General}} --key {{systemdBoot}}`

