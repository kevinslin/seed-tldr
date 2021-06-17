---
id: common.adguardhome
title: Adguardhome
desc: ''
updated: 1623965306172
created: 1623965306172
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# AdGuardHome

> A network-wide software for blocking ads & tracking.
> More information: <https://github.com/AdguardTeam/AdGuardHome>.

- Run AdGuard Home:

`AdGuardHome`

- Run AdGuard Home with a specific config:

`AdGuardHome --config {{path/to/AdGuardHome.yaml}}`

- Set the work directory for data to be stored in:

`AdGuardHome --work-dir {{path/to/directory}}`

- Install or uninstall AdGuard Home as a service:

`AdGuardHome --service {{install|uninstall}}`

- Start the AdGuard Home service:

`AdGuardHome --service start`

- Reload the configuration for the AdGuard Home service:

`AdGuardHome --service reload`

- Stop or restart the AdGuard Home service:

`AdGuardHome --service {{stop|restart}}`

