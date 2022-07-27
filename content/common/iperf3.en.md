---
author: ['m-p-3', 'pxgamer', 'chub16']
date: 1559788968
title: "iperf3, TLDR Pages"
description: "iperf3, Traffic generator for testing network bandwidth."
categories: "common"
---
> More information: <https://iperf.fr>.

- Run iperf3 as a server:

```bash
iperf3 -s
```

- Run an iperf3 server on a specific port:

```bash
iperf3 -s -p port
```

- Start bandwidth test:

```bash
iperf3 -c server
```

- Run iperf3 in multiple parallel streams:

```bash
iperf3 -c server -P streams
```

- Reverse direction of the test. Server sends data to the client:

```bash
iperf3 -c server -R
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[pxgamer](mailto:owzie123@gmail.com) | iperf3: add link to homepage | 2019-06-06T04:42:48 | [c5172dfe6716](https://github.com/tldr-pages/tldr/commit/c5172dfe6716225a1803dda7c3e41d30edab8730)
[m-p-3](mailto:m-p-3@users.noreply.github.com) | iperf3.md with proper spacing (#2504) | 2018-10-28T18:04:04 | [19f79580760c](https://github.com/tldr-pages/tldr/commit/19f79580760c91de219086088936d342ecac6c49)
[chub16](mailto:34138504+chub16@users.noreply.github.com) | iperf3: add page (#1952) | 2018-02-19T21:44:58 | [58af0a38c7e3](https://github.com/tldr-pages/tldr/commit/58af0a38c7e397a25f8df202a0719ac5c9dbc418)

