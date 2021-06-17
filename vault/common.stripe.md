---
id: common.stripe
title: Stripe
desc: ''
updated: 1623965306212
created: 1623965306212
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# stripe

> Interact with a Stripe account.
> More information: <https://github.com/stripe/stripe-cli>.

- Follow the logs of activity on the account:

`stripe logs tail`

- Listen for events, filtering on events with the name `charge.succeeded` and forwarding them to localhost:3000/events:

`stripe listen --events="{{charge.succeeded}}" --forward-to="{{localhost:3000/events}}"`

- Send a test webhook event:

`stripe trigger {{charge.succeeded}}`

- Create a customer:

`stripe customers create --email="{{test@example.com}}" --name="{{Jenny Rosen}}"`

- Print to JSON:

`stripe listen --print-json`

