---
author: ['Felix Brilej', 'bl-ue', 'marchersimon']
date: 1619262596
title: "aws kinesis, TLDR Pages"
description: "aws kinesis, Offizielles AWS CLI für die Amazon Kinesis-Streaming-Datenplattform."
categories: "common"
---
> Weitere Informationen: <https://docs.aws.amazon.com/cli/latest/reference/kinesis/index.html#cli-aws-kinesis>.

- Liste alle Streams auf:

```bash
aws kinesis list-streams
```

- Schreibe einen Datensatz in einen Kinesis Stream:

```bash
aws kinesis put-record --stream-name name --partition-key schlüssel --data base64_codierte_nachricht
```

- Schreibe einen Datensatze in einen Kinesis Stream mit base64 inline Encodierung:

```bash
aws kinesis put-record --stream-name name --partition-key schlüssel --data "$( echo "meine nachricht" | base64 )"
```

- Liste alle verfügbaren Shards in einem Stream auf:

```bash
aws kinesis list-shards --stream-name name
```

- Rufe einen Shard Iterators auf, um diesen beginnend mit der ältesten Nachricht auszulesen:

```bash
aws kinesis get-shard-iterator --shard-iterator-type TRIM_HORIZON --stream-name name --shard-id id
```

- Lies einen Datensatz aus einem Shard über einen Shard Iterator:

```bash
aws kinesis get-records --shard-iterator iterator
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: clean up and normalize (#5437) | 2021-03-25T17:42:04 | [de311e174960](https://github.com/tldr-pages/tldr/commit/de311e17496083a7f805793ef228995ecc7e8c97)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize "more information" labels (#5140) | 2021-01-15T18:24:49 | [c59f12aa9f55](https://github.com/tldr-pages/tldr/commit/c59f12aa9f55d85612ba22e4da86db293ff76977)
[Felix Brilej](mailto:11775168+flyck@users.noreply.github.com) | aws*: add German translation (#4827) | 2020-10-24T15:27:02 | [455f988c81a2](https://github.com/tldr-pages/tldr/commit/455f988c81a21f9d47983d5b1607d3d03b216db4)

