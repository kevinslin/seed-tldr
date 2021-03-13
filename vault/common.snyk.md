---
id: common.snyk
title: Snyk
desc: ''
updated: 1615655543086
created: 1615655543086
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# snyk

> Find vulnerabilities in your code and remediate risks.
> More information: <https://snyk.io>.

- Login to your Snyk account:

`snyk auth`

- Test your code for any known vulnerabilities:

`snyk test`

- Test a local Docker image for any known vulnerabilities:

`snyk test --docker {{docker_image}}`

- Record the state of dependencies and any vulnerabilities on snyk.io:

`snyk monitor`

- Auto patch and ignore vulnerabilities:

`snyk wizard`

