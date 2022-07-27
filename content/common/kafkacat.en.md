---
author: ['Waldir Pimenta', 'pxgamer', 'Fabien Meurillon', 'Chris', 'Lucas Gabriel Schneider']
date: 1612112718
title: "kafkacat, TLDR Pages"
description: "kafkacat, Apache Kafka producer and consumer tool."
categories: "common"
---
> More information: <https://github.com/edenhill/kafkacat>.

- Consume messages starting with the newest offset:

```bash
kafkacat -C -t topic -b brokers
```

- Consume messages starting with the oldest offset and exit after the last message is received:

```bash
kafkacat -C -t topic -b brokers -o beginning -e
```

- Consume messages as a Kafka consumer group:

```bash
kafkacat -G group_id topic -b brokers
```

- Publish message by reading from stdin:

```bash
 echo message | kafkacat -P -t topic -b brokers
```

- Publish messages by reading from a file:

```bash
kafkacat -P -t topic -b brokers path/to/file
```

- List metadata for all topics and brokers:

```bash
kafkacat -L -b brokers
```

- List metadata for a specific topic:

```bash
kafkacat -L -t topic -b brokers
```

- Get offset for a topic/partition for a specific point in time:

```bash
kafkacat -Q -t topic:partition:unix_timestamp -b brokers
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Fabien Meurillon](mailto:FabienM@users.noreply.github.com) | kafkacat: fix parameter bracket (#3362) | 2019-10-09T23:37:32 | [738b583d5a9d](https://github.com/tldr-pages/tldr/commit/738b583d5a9d916bb6e2c4014f617c50dbecc57b)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | Harmonize formatting and capitalization of stdin/stdout/stderr | 2019-06-17T18:39:58 | [cf25745db1d8](https://github.com/tldr-pages/tldr/commit/cf25745db1d86744c762e15e6a2ba04ef9f9acc1)
[pxgamer](mailto:owzie123@gmail.com) | kafkacat: add link to homepage | 2019-06-06T04:42:48 | [f537b58d83b3](https://github.com/tldr-pages/tldr/commit/f537b58d83b3bfb0356c02cad9e4b4dd6a67b519)
[Chris](mailto:12035877+ckauf@users.noreply.github.com) | kafkacat: add page (#2430) | 2018-10-26T20:50:16 | [9113ebb028d8](https://github.com/tldr-pages/tldr/commit/9113ebb028d8b99ccd0403e486e543d8ba72055f)

