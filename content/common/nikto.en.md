---
author: ['pxgamer', 'jordi', 'Agniva De Sarker', 'Schneider']
date: 1570937284
title: "nikto, TLDR Pages"
description: "nikto, Web server scanner which performs tests against web servers for multiple items."
categories: "common"
---
> More information: <https://cirt.net/Nikto2>.

- Perform a basic Nikto scan against a target host:

```bash
perl nikto.pl -h 192.168.0.1
```

- Specify the port number when performing a basic scan:

```bash
perl nikto.pl -h 192.168.0.1 -p 443
```

- Scan ports and protocols with full URL syntax:

```bash
perl nikto.pl -h https://192.168.0.1:443/
```

- Scan multiple ports in the same scanning session:

```bash
perl nikto.pl -h 192.168.0.1 -p 80,88,443
```

- Update to the latest plugins and databases:

```bash
perl nikto.pl -update
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Schneider](mailto:lucas.schneider@sap.com) | multiple pages: rephrase without adjectives | 2019-10-13T05:28:04 | [42152ed45923](https://github.com/tldr-pages/tldr/commit/42152ed459230c2b244529f0c5990335e0057c6c)
[pxgamer](mailto:owzie123@gmail.com) | nikto: add link to homepage | 2019-06-04T21:29:40 | [a459fecd8756](https://github.com/tldr-pages/tldr/commit/a459fecd875646f9e6dab2a076d3b53958a0a044)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | Fixed a typo | 2017-12-13T09:24:36 | [b887a6506cdf](https://github.com/tldr-pages/tldr/commit/b887a6506cdfc233b9d4329f024c1ab88167a23b)
[jordi](mailto:pascual.dalmau@gmail.com) | nikto: add page | 2017-12-13T09:11:08 | [6d2d5d718327](https://github.com/tldr-pages/tldr/commit/6d2d5d718327a38d6b72ee6dfa4a20e4853e946a)
[jordi](mailto:pascual.dalmau@gmail.com) | Nikto - Web server scanner | 2017-12-12T21:38:03 | [c34dd895cdf1](https://github.com/tldr-pages/tldr/commit/c34dd895cdf1f6adda23a7360c19af5f00ce1a17)
[jordi](mailto:pascual.dalmau@gmail.com) | Nikto - Web server scanner | 2017-12-12T19:00:03 | [5d1472b4ecef](https://github.com/tldr-pages/tldr/commit/5d1472b4ecef51d86c9fb724d73e5668709258a4)
[jordi](mailto:pascual.dalmau@gmail.com) | Nikto - Web server scanner | 2017-12-12T18:51:28 | [57486e9fd308](https://github.com/tldr-pages/tldr/commit/57486e9fd308af386fae5aee063e95094c399fea)
[jordi](mailto:pascual.dalmau@gmail.com) | Nikto - Web server scanner | 2017-12-12T18:39:26 | [e2393a32f0b0](https://github.com/tldr-pages/tldr/commit/e2393a32f0b0a4bc1c0e7661b7e11ebbf544e731)

