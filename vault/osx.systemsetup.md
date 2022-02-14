---
id: osx.systemsetup
title: Systemsetup
desc: ''
updated: 1644840636313
created: 1644840636313
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# systemsetup

> Configure System Preferences machine settings.
> More information: <https://ss64.com/osx/systemsetup.html>.

- Enable remote login (SSH):

`systemsetup -setremotelogin on`

- Specify timezone, NTP Server and enable network time:

`systemsetup -settimezone "{{US/Pacific}}" -setnetworktimeserver {{us.pool.ntp.org}} -setusingnetworktime on`

- Make the machine never sleep and automatically restart on power failure or kernel panic:

`systemsetup -setsleep off -setrestartpowerfailure on -setrestartfreeze on`

- List valid startup disks:

`systemsetup -liststartupdisks`

- Specify a new startup disk:

`systemsetup -setstartupdisk {{path}}`

