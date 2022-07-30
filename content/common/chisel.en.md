---
author: ['Waldir Pimenta', 'Ohad Eytan']
date: 1574435164
title: "chisel"
description: "chisel, Create TCP tunnels. Includes both client and server."
categories: "common"
---
> More information: <https://github.com/jpillora/chisel>.

- Run a Chisel server:

```bash
chisel server
```

- Run a Chisel server listening to a specific port:

```bash
chisel server -p server_port
```

- Run a chisel server that accepts authenticated connections using username and password:

```bash
chisel server --auth username:password
```

- Connect to a Chisel server and tunnel a specific port to a remote server and port:

```bash
chisel client server_ip:server_port local_port:remote_server:remote_port
```

- Connect to a Chisel server and tunnel a specific host and port to a remote server and port:

```bash
chisel client server_ip:server_port local_host:local_port:remote_server:remote_port
```

- Connect to a Chisel server using username and password authentication:

```bash
chisel client --auth username:password server_ip:server_port local_port:remote_server:remote_port
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Waldir Pimenta](mailto:waldyrious@gmail.com) | chisel: rephrase descriptions for clarity (#3601) | 2019-11-22T16:06:04 | [6463f50a1803](https://github.com/tldr-pages/tldr/commit/6463f50a18034af2e191c629a9d262f0cc6a5b84)
[Ohad Eytan](mailto:ohadey@gmail.com) | chisel: fix typo (#3410) | 2019-10-13T13:52:11 | [adb9519c96f7](https://github.com/tldr-pages/tldr/commit/adb9519c96f789a580d08fe5c30c95adc8587459)
[Ohad Eytan](mailto:ohadey@gmail.com) | chisel: add page (#3343) | 2019-10-08T08:16:02 | [28d4a486f4d2](https://github.com/tldr-pages/tldr/commit/28d4a486f4d2bd22ced2b33c6fd917e31d6bab5a)

