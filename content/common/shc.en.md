---
author: ['Darryl Abbate', 'Guido Lena Cota', 'Sarah Haïm-Lubczanski']
date: 1636001954
title: "shc, TLDR Pages"
description: "shc, Generic shell script compiler."
categories: "common"
---
> More information: <https://manned.org/shc>.

- Compile a shell script:

```bash
shc -f script
```

- Compile a shell script and specify an output binary file:

```bash
shc -f script -o binary
```

- Compile a shell script and set an expiration date for the executable:

```bash
shc -f script -e dd/mm/yyyy
```

- Compile a shell script and set a message to display upon expiration:

```bash
shc -f script -e dd/mm/yyyy -m "Please contact your provider"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Sarah Haïm-Lubczanski](mailto:205895+mere-teresa@users.noreply.github.com) | shc: add more information link (#7372) | 2021-11-04T05:59:14 | [e4631681dbc5](https://github.com/tldr-pages/tldr/commit/e4631681dbc57e539f9311cc02ac279bd1ddb874)
[Guido Lena Cota](mailto:guido.lenacota@kreuzwerker.de) | Bulk change: move double quotes outside tokens (#4431) | 2020-10-04T19:33:38 | [354d4b8748ee](https://github.com/tldr-pages/tldr/commit/354d4b8748ee58813dd6830ced7c3b11067255d7)
[Darryl Abbate](mailto:rootbeersoup@gmail.com) | shc: add page (#2138) | 2018-06-13T18:12:54 | [28f8320a0b62](https://github.com/tldr-pages/tldr/commit/28f8320a0b620b970714aea3b27578e70865b282)

