---
author: ['bl-ue', 'Shane', 'Starbeamrainbowlabs']
date: 1621541621
title: "awslogs"
description: "awslogs, Queries groups, streams and events from Amazon CloudWatch logs."
categories: "common"
---
> More information: <https://github.com/jorgebastida/awslogs>.

- List log groups:

```bash
awslogs groups
```

- List existing streams for the specified group:

```bash
awslogs streams /var/log/syslog
```

- Get logs for any streams in the specified group between 1 and 2 hours ago:

```bash
awslogs get /var/log/syslog --start='2h ago' --end='1h ago'
```

- Get logs that match a specific CloudWatch Logs Filter pattern:

```bash
awslogs get /aws/lambda/my_lambda_group --filter-pattern='ERROR'
```

- Watch logs for any streams in the specified group:

```bash
awslogs get /var/log/syslog ALL --watch
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | awslogs: add missing article | 2020-08-10T01:33:41 | [769555f8a70b](https://github.com/tldr-pages/tldr/commit/769555f8a70b8aeaeff05610ff9576862e98154b)
[Shane](mailto:shane@shanedowling.com) | awslogs: add page | 2020-08-10T01:33:41 | [1fdd0754d43a](https://github.com/tldr-pages/tldr/commit/1fdd0754d43aa551d288c90325583c3ce5b4b8b7)

