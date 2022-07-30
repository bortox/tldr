---
author: ['Axel Navarro', 'pxgamer', 'Seth Falco', 'Sacha Bron']
date: 1645730884
title: "chromium"
description: "chromium, Open-source web browser principally developed and maintained by Google."
categories: "common"
---
> More information: <https://www.chromium.org/developers/how-tos/run-chromium-with-flags/>.

- Open a specific URL or file:

```bash
chromium https://example.com|path/to/file.html
```

- Open in incognito mode:

```bash
chromium --incognito example.com
```

- Open in a new window:

```bash
chromium --new-window example.com
```

- Open in application mode (without toolbars, URL bar, buttons, etc.):

```bash
chromium --app=https://example.com
```

- Use a proxy server:

```bash
chromium --proxy-server="socks5://hostname:66" example.com
```

- Open with a custom profile directory:

```bash
chromium --user-data-dir=path/to/directory
```

- Open without CORS validation (useful to test an API):

```bash
chromium --user-data-dir=path/to/directory --disable-web-security
```

- Open with a DevTools window for each tab opened:

```bash
chromium --auto-open-devtools-for-tabs
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | chromium: refresh (#7811) | 2022-02-24T20:28:04 | [a8bcde4a28fa](https://github.com/tldr-pages/tldr/commit/a8bcde4a28fa7a971454f4c8c3c918d7f756300f)
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[pxgamer](mailto:owzie123@gmail.com) | chromium: add link to homepage | 2019-06-09T18:53:49 | [27ed5dd0c1fb](https://github.com/tldr-pages/tldr/commit/27ed5dd0c1fb70333dcaf905304cefc1a8c36692)
[Sacha Bron](mailto:BinaryBrain@users.noreply.github.com) | chromium: add page (#2533) | 2018-11-05T20:11:01 | [bfc3e8482207](https://github.com/tldr-pages/tldr/commit/bfc3e8482207916f817c2a4dfbc745a0b1b892e0)

