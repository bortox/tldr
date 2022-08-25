---
author: ['André Santos']
date: 1661355708
title: "jmeter"
description: "jmeter, Open source java application designed for load testing functional behavior and measure performance."
categories: "common"
---
> More information: <https://jmeter.apache.org>.

- Run a specific test plan in nongui mode:

```bash
jmeter --nongui --testfile path/to/file.jmx
```

- Run a test plan in nongui mode using a specific log file:

```bash
jmeter --nogui --testfile path/to/file.jmx --logfile path/to/logfile.jtl
```

- Run a test plan in nongui mode using a specific proxy:

```bash
jmeter --nongui --testfile path/to/file.jmx --proxyHost 127.0.0.1 --proxyPort 8888
```

- Run a test plan in nongui mode using a specific JMeter property:

```bash
jmeter --jmeterproperty key='value' --nongui --testfile path/to/file.jmx
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[André Santos](mailto:103038983+andre-santos-fd@users.noreply.github.com) | jmeter: add page (#8391) * jmeter: add page * Rename jmeter.md to pages/common/jmeter.md * Replaced hyphens with "greater than" signs [...] | 2022-08-24T17:41:48 | [c84a1a7eccf1](https://github.com/tldr-pages/tldr/commit/c84a1a7eccf13d487655df245d8997b086c07539)

