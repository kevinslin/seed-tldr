---
id: osx.say
title: Say
desc: ''
updated: 1615655543116
created: 1615655543116
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# say

> Converts text to speech.

- Say a phrase aloud:

`say "{{I like to ride my bike.}}"`

- Read a file aloud:

`say -f {{filename.txt}}`

- Say a phrase with a custom voice and speech rate:

`say -v {{voice}} -r {{words_per_minute}} "{{I'm sorry Dave, I can't let you do that.}}"`

- List the available voices:

`say -v "?"`

- Create an audio file of the spoken text:

`say -o {{filename.aiff}} "{{Here's to the Crazy Ones.}}"`

