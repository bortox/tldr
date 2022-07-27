---
author: ['Waldir Pimenta', 'Schneider', 'HairyFotr', 'Marco Bonelli', 'Joel Huang']
date: 1559564381
title: "convmv, TLDR Pages"
description: "convmv, Convert filenames (NOT file content) from one encoding to another."
categories: "common"
---
> More information: <https://www.j3e.de/linux/convmv/man/>.

- Test filename encoding conversion (don't actually change the filename):

```bash
convmv -f from_encoding -t to_encoding input_file
```

- Convert filename encoding and rename the file to the new encoding:

```bash
convmv -f from_encoding -t to_encoding --notest input_file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Schneider](mailto:lucas.schneider@sap.com) | convmv.md: add homepage | 2019-04-15T01:35:17 | [d585a57cacee](https://github.com/tldr-pages/tldr/commit/d585a57cacee04eb8c8bd6a36e8118618a12778c)
[HairyFotr](mailto:hairyfotr@gmail.com) | Fix a few typos | 2017-07-23T16:22:44 | [e0ccb7147a25](https://github.com/tldr-pages/tldr/commit/e0ccb7147a25b5d738e3991f399f87e45f3a4140)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | convmv: less awkward wording, fix lint | 2016-01-22T02:15:34 | [953c9eb54c1f](https://github.com/tldr-pages/tldr/commit/953c9eb54c1f5c021487172d5c731ae2e903a5aa)
[Joel Huang](mailto:joelhy@gmail.com) | clearify command purpose in the main description | 2016-01-04T16:45:46 | [f15d078b2fce](https://github.com/tldr-pages/tldr/commit/f15d078b2fce78b86150c0a0292561ae0389c9b5)
[Joel Huang](mailto:joelhy@gmail.com) | wording twist | 2016-01-04T14:50:38 | [819ef66c6bc1](https://github.com/tldr-pages/tldr/commit/819ef66c6bc10649f968530269147ea2e0b91262)
[Joel Huang](mailto:joelhy@gmail.com) | Add a space between "convert encoding" and (dry run)/(not dry run) | 2016-01-04T14:27:37 | [0c044862181d](https://github.com/tldr-pages/tldr/commit/0c044862181dedf0840c92289c62106ebf1b92d0)
[Joel Huang](mailto:joelhy@gmail.com) | clarify command's behavior by adding dry run example | 2016-01-04T03:00:33 | [e7b76dae7d83](https://github.com/tldr-pages/tldr/commit/e7b76dae7d83a12eec077a15365ff0d2713bfc6c)
[Joel Huang](mailto:joelhy@gmail.com) | fix store path | 2016-01-04T02:55:36 | [bdd001e3312f](https://github.com/tldr-pages/tldr/commit/bdd001e3312fa1f923707dd3a891a3e47292dbb6)

