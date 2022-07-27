---
author: ['bagginslin', 'Wolfgang Lutz', 'pxgamer', 'jduan', 'Lucas Gabriel Schneider', 'Starbeamrainbowlabs']
date: 1612112718
title: "cloc, TLDR Pages"
description: "cloc, Count, and compute differences of, lines of source code and comments."
categories: "common"
---
> More information: <https://github.com/AlDanial/cloc>.

- Count all the lines of code in a directory:

```bash
cloc path/to/directory
```

- Count all the lines of code in a directory, displaying a progress bar during the counting process:

```bash
cloc --progress=1 path/to/directory
```

- Compare 2 directory structures and count the differences between them:

```bash
cloc --diff path/to/directory/one path/to/directory/two
```

- Ignore files that are ignored by VCS, such as files specified in `.gitignore`:

```bash
cloc --vcs git path/to/directory
```

- Count all the lines of code in a directory, displaying the results for each file instead of each language:

```bash
cloc --by-file path/to/directory
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[bagginslin](mailto:51952061+bagginslin@users.noreply.github.com) | cloc: add --by-file example (#4129) | 2020-06-27T14:25:57 | [7eddc00f20eb](https://github.com/tldr-pages/tldr/commit/7eddc00f20eb50459ad31b3ad28203974f0b3f28)
[jduan](mailto:duanjingjing@gmail.com) | cloc: add --vcs example (#3707) | 2019-12-30T15:46:08 | [0205dc21ffae](https://github.com/tldr-pages/tldr/commit/0205dc21ffaea93214575c8e50783711e076c7e9)
[pxgamer](mailto:owzie123@gmail.com) | cloc: add link to homepage | 2019-06-09T18:53:49 | [544fa427dcf1](https://github.com/tldr-pages/tldr/commit/544fa427dcf181f5d25fd94970aa3573ad5b5770)
[Wolfgang Lutz](mailto:WLBORg@gmx.de) | fix typos using misspell (#1374) | 2017-05-12T11:29:18 | [550ede5cfb90](https://github.com/tldr-pages/tldr/commit/550ede5cfb90cb772d1ecf27241b22e5086b024b)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | Make directory paths even more clearerererer | 2016-05-06T11:41:00 | [fb3cf26a7d7c](https://github.com/tldr-pages/tldr/commit/fb3cf26a7d7c35e8a454bf853252edeacb9ac1b4)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | Fixed directory tokens. | 2016-05-06T11:12:39 | [154d0db2a3c4](https://github.com/tldr-pages/tldr/commit/154d0db2a3c4e26447bafd53697e5c4f8b9389d7)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | Correct progress example. | 2016-05-06T10:57:18 | [28b087e980ff](https://github.com/tldr-pages/tldr/commit/28b087e980ff771f260c48681ce18f584dd68759)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | SImplify directory tokens. | 2016-05-06T07:44:10 | [88efafaf974a](https://github.com/tldr-pages/tldr/commit/88efafaf974a1d0a2e0f71ac459be9973ada01d9)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | Add cloc Find out more about cloc here: https://github.com/AlDanial/cloc | 2016-05-05T21:01:56 | [80a67a17aa40](https://github.com/tldr-pages/tldr/commit/80a67a17aa40e2bfc809cce8d82b505e8053d751)

