---
author: ['Mpho Mphego', 'pxgamer', 'Lucas Gabriel Schneider', 'Guido Lena Cota']
date: 1612112718
title: "mosquitto_pub"
description: "mosquitto_pub, A simple MQTT version 3.1.1 client that will publish a single message on a topic and exit."
categories: "common"
---
> More information: <https://mosquitto.org/man/mosquitto_pub-1.html>.

- Publish a temperature value of 32 on the topic `sensors/temperature` to 192.168.1.1 (defaults to `localhost`) with Quality of Service (`QoS`) set to 1:

```bash
mosquitto_pub -h 192.168.1.1 -t sensors/temperature -m 32 -q 1
```

- Publish timestamp and temperature data on the topic `sensors/temperature` to a remote host on a non-standard port:

```bash
mosquitto_pub -h 192.168.1.1 -p 1885 -t sensors/temperature -m "1266193804 32"
```

- Publish light switch status and retain the message on the topic `switches/kitchen_lights/status` to a remote host because there may be a long period of time between light switch events:

```bash
mosquitto_pub -r -h "iot.eclipse.org" -t switches/kitchen_lights/status -m "on"
```

- Send the contents of a file (`data.txt`) as a message and publish it to `sensors/temperature` topic:

```bash
mosquitto_pub -t sensors/temperature -f data.txt
```

- Send the contents of a file (`data.txt`), by reading from stdin and send the entire input as a message and publish it to `sensors/temperature` topic:

```bash
mosquitto_pub -t sensors/temperature -s < data.txt
```

- Read newline delimited data from stdin as a message and publish it to `sensors/temperature` topic:

```bash
echo data.txt | mosquitto_pub -t sensors/temperature -l
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Guido Lena Cota](mailto:guido.lenacota@kreuzwerker.de) | Bulk change: move double quotes outside tokens (#4431) | 2020-10-04T19:33:38 | [354d4b8748ee](https://github.com/tldr-pages/tldr/commit/354d4b8748ee58813dd6830ced7c3b11067255d7)
[pxgamer](mailto:owzie123@gmail.com) | mosquitto_pub: add link to homepage | 2019-06-04T21:29:40 | [661c93b34ff6](https://github.com/tldr-pages/tldr/commit/661c93b34ff6a58992c8381b3e4a124abae492a3)
[Mpho Mphego](mailto:mmphego@ska.ac.za) | mosquitto_pub: add page (#2719) | 2019-02-14T22:39:17 | [bd66fa3eceab](https://github.com/tldr-pages/tldr/commit/bd66fa3eceab0e22c087b86d154c97a912c8634a)

