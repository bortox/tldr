---
author: ['Max Isom', 'pxgamer', 'Ein Verne']
date: 1586254579
title: "iperf, TLDR Pages"
description: "iperf, Measure network bandwidth between computers."
categories: "common"
---
> More information: <https://iperf.fr>.

- Run on server:

```bash
iperf -s
```

- Run on server using UDP mode and set server port to listen on 5001:

```bash
iperf -u -s -p 5001
```

- Run on client:

```bash
iperf -c server_address
```

- Run on client every 2 seconds:

```bash
iperf -c server_address -i 2
```

- Run on client with 5 parallel threads:

```bash
iperf -c server_address -P 5
```

- Run on client using UDP mode:

```bash
iperf -u -c server_address -p 5001
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Ein Verne](mailto:einverne@gmail.com) | iperf: update page (#3960) | 2020-04-07T12:16:19 | [5409614fb9b5](https://github.com/tldr-pages/tldr/commit/5409614fb9b53207611cd3f6824ce0d26ca695ea)
[pxgamer](mailto:owzie123@gmail.com) | iperf: add link to homepage | 2019-06-06T04:42:48 | [d50cd1f2aa02](https://github.com/tldr-pages/tldr/commit/d50cd1f2aa02c5135092ede803b1b3a8ba0f682c)
[Max Isom](mailto:codetheweb@users.noreply.github.com) | iperf: add page (#2059) | 2018-04-10T11:49:40 | [0437cee5f68e](https://github.com/tldr-pages/tldr/commit/0437cee5f68e4b13bcdb228d894a014c9a7f9832)

