---
id: common.ansiweather
title: Ansiweather
desc: ''
updated: 1615655543043
created: 1615655543043
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# ansiweather

> A shell script for displaying the current weather conditions in your terminal.
> More information: <https://github.com/fcambus/ansiweather>.

- Display a forecast using metric units for the next five days for Rzeszow, Poland:

`ansiweather -u {{metric}} -f {{5}} -l {{Rzeszow,PL}}`

- Display a forecast showing symbols and daylight data for your current location:

`ansiweather -s {{true}} -d {{true}}`

- Display a forecast showing wind and humidity data for your current location:

`ansiweather -w {{true}} -h {{true}}`

