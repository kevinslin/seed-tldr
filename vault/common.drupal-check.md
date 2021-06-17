---
id: common.drupal-check
title: Drupal Check
desc: ''
updated: 1623965016122
created: 1623965016122
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# drupal-check

> Check Drupal PHP code for deprecations.
> More information: <https://github.com/mglaman/drupal-check>.

- Check the code in a specific directory for deprecations:

`drupal-check {{path/to/directory}}`

- Check the code excluding a comma-separated list of directories:

`drupal-check --exclude-dir {{path/to/excluded_directory}},{{path/to/excluded_files/*.php}} {{path/to/directory}}`

- Don't show a progress bar:

`drupal-check --no-progress {{path/to/directory}}`

- Perform static analysis to detect bad coding practices:

`drupal-check --analysis {{path/to/directory}}`

