---
author: ['Mpho Mphego', 'pxgamer', 'Lucas Gabriel Schneider']
date: 1612112718
title: "mosquitto_sub"
description: "mosquitto_sub, A simple MQTT version 3.1.1 client that will subscribe to topics and print the messages that it receives."
categories: "common"
---
> More information: <https://mosquitto.org/man/mosquitto_sub-1.html>.

- Subscribe to the topic `sensors/temperature` information with Quality of Service (`QoS`) set to 1. (The default hostname is `localhost` and port 1883):

```bash
mosquitto_sub -t sensors/temperature -q 1
```

- Subscribe to all broker status messages publishing on `iot.eclipse.org` port 1885 and print published messages verbosely:

```bash
mosquitto_sub -v -h "iot.eclipse.org" -p 1885 -t \$SYS/#
```

- Subscribe to multiple topics matching a given pattern. (+ takes any metric name):

```bash
mosquitto_sub -t sensors/machines/+/temperature/+
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[pxgamer](mailto:owzie123@gmail.com) | mosquitto_sub: add link to homepage | 2019-06-04T21:29:40 | [2e1d0abf33fa](https://github.com/tldr-pages/tldr/commit/2e1d0abf33fa4d36f1809165a22b70c66c1aa0a9)
[Mpho Mphego](mailto:mmphego@ska.ac.za) | mosquitto_sub: add page (#2718) | 2019-02-14T22:37:17 | [fb9970921156](https://github.com/tldr-pages/tldr/commit/fb997092115642bc3ac796da3f60ca5ea450a2a8)

