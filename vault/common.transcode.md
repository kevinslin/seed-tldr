---
id: common.transcode
title: Transcode
desc: ''
updated: 1615655543089
created: 1615655543090
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# transcode

> Transcode video and audio codecs, and convert between media formats.

- Create stabilisation file to be able to remove camera shakes:

`transcode -J stabilize -i {{input_file}}`

- Remove camera shakes after creating stabilisation file, transform video using xvid:

`transcode -J transform -i {{input_file}} -y xvid -o {{output_file}}`

- Resize the video to 640x480 pixels and convert to MPEG4 codec using xvid:

`transcode -Z 640x480 -i {{input_file}} -y xvid -o {{output_file}}`

