---
id: common.espeak
title: Espeak
desc: ''
updated: 1615655543053
created: 1615655543053
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# espeak

> Uses text-to-speech to speak through the default sound device.
> More information: <http://espeak.sourceforge.net>.

- Speak a phrase aloud:

`espeak "I like to ride my bike."`

- Speak a file aloud:

`espeak -f {{filename}}`

- Save output to a WAV audio file, rather than speaking it directly:

`espeak -w {{filename.wav}} "It's GNU plus Linux"`

- Use a different voice:

`espeak -v {{voice}}`

