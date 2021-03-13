---
id: common.jar
title: Jar
desc: ''
updated: 1615655543065
created: 1615655543065
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# jar

> Java Applications/Libraries Packager.
> More information: <https://docs.oracle.com/javase/tutorial/deployment/jar/basicsindex.html>.

- Recursively archive all files in the current directory into a .jar file:

`jar cf {{file.jar}} *`

- Unzip .jar/.war file to the current directory:

`jar -xvf {{file.jar}}`

- List a .jar/.war file content:

`jar tf {{path/to/file.jar}}`

- List a .jar/.war file content with verbose output:

`jar tvf {{path/to/file.jar}}`

