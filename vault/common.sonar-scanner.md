---
id: common.sonar-scanner
title: Sonar Scanner
desc: ''
updated: 1642441815069
created: 1642441815069
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# sonar-scanner

> SonarScanner is a generic scanner for SonarQube projects that do not use build tools such as Maven, Gradle, or Ant.
> More information: <https://docs.sonarqube.org/latest/analysis/scan/sonarscanner/>.

- Scan a project with configuration file in your project's root directory named `sonar-project.properties`:

`sonar-scanner`

- Scan a project using configuration file other than `sonar-project.properties`:

`sonar-scanner -D{{project.settings=myproject.properties}}`

- Print help information:

`sonar-scanner -h`

- Print debugging information:

`sonar-scanner -X`

