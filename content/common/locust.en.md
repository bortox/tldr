---
author: ['pxgamer', 'Zac']
date: 1559788968
title: "locust, TLDR Pages"
description: "locust, Load-testing tool to determine number of concurrent users a system can handle."
categories: "common"
---
> More information: <https://locust.io>.

- Load-test "example.com" with web interface using locustfile.py:

```bash
locust --host=http://example.com
```

- Use a different test file:

```bash
locust --locustfile=test_file.py --host=http://example.com
```

- Run test without web interface, spawning 1 user a second until there are 100 users:

```bash
locust --no-web --clients=100 --hatch-rate=1 --host=http://example.com
```

- Start locust in master mode:

```bash
locust --master --host=http://example.com
```

- Connect locust slave to master:

```bash
locust --slave --host=http://example.com
```

- Connect locust slave to master on a different machine:

```bash
locust --slave --master-host=master_hostname --host=http://example.com
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[pxgamer](mailto:owzie123@gmail.com) | locust: add link to homepage | 2019-06-06T04:42:48 | [5bb07e02afbc](https://github.com/tldr-pages/tldr/commit/5bb07e02afbcdf66c3d4f6d85124801913dd852b)
[Zac](mailto:zpitones+github@gmail.com) | locust: add page (#1534) | 2017-10-11T12:29:29 | [ae695bdbb74c](https://github.com/tldr-pages/tldr/commit/ae695bdbb74cb9365b43d02f3dd1816eeedbc3f0)

