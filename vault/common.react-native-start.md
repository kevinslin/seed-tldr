---
id: common.react-native-start
title: React Native Start
desc: ''
updated: 1642441815065
created: 1642441815065
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# react-native start

> Command-line tools to start the React Native server.
> More information: <https://github.com/react-native-community/cli/blob/master/docs/commands.md#start>.

- Start the server that communicates with connected devices:

`react-native start`

- Start the metro bundler with a clean cache:

`react-native start --reset-cache`

- Start the server in a custom port (defaults to 8081):

`react-native start --port {{3000}}`

- Start the server in verbose mode:

`react-native start --verbose`

- Specify the maximum number of workers for transforming files (default is the number of CPU cores):

`react-native start --max-workers {{count}}`

- Disable interactive mode:

`react-native start --no-interactive`

