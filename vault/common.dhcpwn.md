---
id: common.dhcpwn
title: Dhcpwn
desc: ''
updated: 1615655543050
created: 1615655543050
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# dhcpwn

> Test DHCP IP exhaustion attacks and sniff local DHCP traffic.
> More information: <https://github.com/mschwager/dhcpwn>.

- Flood the network with IP requests:

`dhcpwn --interface {{network_interface}} flood --count {{number_of_requests}}`

- Sniff local DHCP traffic:

`dhcpwn --interface {{network_interface}} sniff`

