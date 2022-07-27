---
author: ['Eiman']
date: 1603804101
title: "ss-local, TLDR Pages"
description: "ss-local, Run a Shadowsocks client as a SOCKS5 proxy."
categories: "common"
---
> More information: <https://github.com/shadowsocks/shadowsocks-libev/blob/master/doc/ss-local.asciidoc>.

- Run a Shadowsocks proxy by specifying the host, server port, local port, password, and encryption method:

```bash
ss-local -s host -p server_port -l local port -k password -m encrypt_method
```

- Run a Shadowsocks proxy by specifying the config file:

```bash
ss-local -c path/to/config/file.json
```

- Use a plugin to run the proxy client:

```bash
ss-local --plugin plugin_name --plugin-opts plugin_options
```

- Enable TCP fast open:

```bash
ss-local --fast-open
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Eiman](mailto:eimanip@users.noreply.github.com) | ss-local: add page (#4857) | 2020-10-27T14:08:21 | [e55878a77813](https://github.com/tldr-pages/tldr/commit/e55878a77813267aa404b31169f5586c69620ec1)

