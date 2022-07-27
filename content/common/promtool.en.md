---
author: ['Kargins']
date: 1611252217
title: "promtool, TLDR Pages"
description: "promtool, Tooling for the Prometheus monitoring system."
categories: "common"
---
> More information: <https://prometheus.io/docs/prometheus/latest/getting_started/>.

- Check if the config files are valid or not (if present report errors):

```bash
promtool check config config_file.yml
```

- Check if the rule files are valid or not (if present report errors):

```bash
promtool check rules rules_file.yml
```

- Pass Prometheus metrics over stdin to check them for consistency and correctness:

```bash
curl --silent http://example.com:9090/metrics/ | promtool check metrics
```

- Unit tests for rules config:

```bash
promtool test rules test_file.yml
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Kargins](mailto:GETandSELECT@users.noreply.github.com) | promtool: add page (#5166) | 2021-01-21T19:03:37 | [ca2b6850a8de](https://github.com/tldr-pages/tldr/commit/ca2b6850a8decf42928329d7c292a341c65a9c04)

