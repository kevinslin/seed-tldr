---
id: common.redshift
title: Redshift
desc: ''
updated: 1615655543081
created: 1615655543081
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# redshift

> Adjust the color temperature of your screen according to your surroundings.
> More information: <https://jonls.dk/redshift>.

- Turn on Redshift with 5700K temperature during day and 3600K at night:

`redshift -t {{5700}}:{{3600}}`

- Turn on Redshift with a manually-specified custom location:

`redshift -l {{latitude}}:{{longitude}}`

- Turn on Redshift with 70% screen brightness during day and 40% brightness at night:

`redshift -b {{0.7}}:{{0.4}}`

- Turn on Redshift with custom gamma levels (between 0 and 1):

`redshift -g {{red}}:{{green}}:{{blue}}`

- Turn on Redshift with a constant unchanging color temperature:

`redshift -O {{temperature}}`

