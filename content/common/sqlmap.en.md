---
author: ['Hakan', 'pxgamer', 'Guido Lena Cota', 'Marco Bonelli']
date: 1601832818
title: "sqlmap"
description: "sqlmap, Detect and exploit SQL injection flaws."
categories: "common"
---
> More information: <https://sqlmap.org>.

- Run sqlmap against a single target URL:

```bash
python sqlmap.py -u "http://www.target.com/vuln.php?id=1"
```

- Send data in a POST request (`--data` implies POST request):

```bash
python sqlmap.py -u "http://www.target.com/vuln.php" --data="id=1"
```

- Change the parameter delimiter (& is the default):

```bash
python sqlmap.py -u "http://www.target.com/vuln.php" --data="query=foobar;id=1" --param-del=";"
```

- Select a random `User-Agent` from `./txt/user-agents.txt` and use it:

```bash
python sqlmap.py -u "http://www.target.com/vuln.php" --random-agent
```

- Provide user credentials for HTTP protocol authentication:

```bash
python sqlmap.py -u "http://www.target.com/vuln.php" --auth-type Basic --auth-cred "testuser:testpass"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Guido Lena Cota](mailto:guido.lenacota@kreuzwerker.de) | Bulk change: move double quotes outside tokens (#4431) | 2020-10-04T19:33:38 | [354d4b8748ee](https://github.com/tldr-pages/tldr/commit/354d4b8748ee58813dd6830ced7c3b11067255d7)
[Marco Bonelli](mailto:marco@mebeim.net) | sqlmap: fix user token typo | 2019-06-09T06:12:25 | [da1330ea04ef](https://github.com/tldr-pages/tldr/commit/da1330ea04ef1985a4c2372513b00bf1975a3582)
[pxgamer](mailto:owzie123@gmail.com) | multiple pages: update the web link descriptions | 2019-05-29T14:41:10 | [f2b1446e6247](https://github.com/tldr-pages/tldr/commit/f2b1446e6247d3e794ee6577dee0c867dfc9af26)
[pxgamer](mailto:owzie123@gmail.com) | sqlmap: add link to homepage | 2019-05-29T14:41:10 | [0ac0ddac08b0](https://github.com/tldr-pages/tldr/commit/0ac0ddac08b0166fcb9bfb16050c41536f9398af)
[Hakan](mailto:hbostann@users.noreply.github.com) | sqlmap: add page (#2412) | 2018-10-24T07:18:16 | [72038e7744b5](https://github.com/tldr-pages/tldr/commit/72038e7744b546736cf68ff65da9229920d29360)

