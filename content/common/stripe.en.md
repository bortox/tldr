---
author: ['paulasjes-stripe', 'Starbeamrainbowlabs']
date: 1587007185
title: "stripe, TLDR Pages"
description: "stripe, Interact with a Stripe account."
categories: "common"
---
> More information: <https://github.com/stripe/stripe-cli>.

- Follow the logs of activity on the account:

```bash
stripe logs tail
```

- Listen for events, filtering on events with the name `charge.succeeded` and forwarding them to localhost:3000/events:

```bash
stripe listen --events="charge.succeeded" --forward-to="localhost:3000/events"
```

- Send a test webhook event:

```bash
stripe trigger charge.succeeded
```

- Create a customer:

```bash
stripe customers create --email="test@example.com" --name="Jenny Rosen"
```

- Print to JSON:

```bash
stripe listen --print-json
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | stripe: apply suggestions (#3989) | 2020-04-16T05:19:45 | [ead6c88196da](https://github.com/tldr-pages/tldr/commit/ead6c88196da629c54bd38baafd774f5b118669f)
[paulasjes-stripe](mailto:46610432+paulasjes-stripe@users.noreply.github.com) | stripe: add page (#3962) | 2020-04-06T20:59:20 | [ccd220a1b208](https://github.com/tldr-pages/tldr/commit/ccd220a1b208910978b530ea6b91809a2dcc4a0f)

