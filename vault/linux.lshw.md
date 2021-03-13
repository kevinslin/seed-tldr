---
id: linux.lshw
title: Lshw
desc: ''
updated: 1615655543104
created: 1615655543104
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# lshw

> List detailed information about hardware configurations as root user.

- Launch the GUI:

`sudo lshw -X`

- List all hardwares in tabular format:

`sudo lshw -short`

- List all disks and storage controllers in tabular format:

`sudo lshw -class disk -class storage -short`

- Save all network interfaces to an HTML file:

`sudo lshw -class network -html > {{interfaces.html}}`

