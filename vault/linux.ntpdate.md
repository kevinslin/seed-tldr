---
id: linux.ntpdate
title: Ntpdate
desc: ''
updated: 1642441815106
created: 1642441815106
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ntpdate

> Synchronize and set the date and time via NTP.
> More information: <http://support.ntp.org/documentation>.

- Synchronize and set date and time:

`sudo ntpdate {{host}}`

- Query the host without setting the time:

`ntpdate -q {{host}}`

- Use an unprivileged port in case a firewall is blocking privileged ports:

`sudo ntpdate -u {{host}}`

- Force time to be stepped using `settimeofday` instead of `slewed`:

`sudo ntpdate -b {{host}}`

