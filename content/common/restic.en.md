---
author: ['Marco Bonelli', 'Halvor Haukvik', 'pxgamer', 'Peter Babič', 'Bruno Bigras', 'Lucas Gabriel Schneider']
date: 1626527438
title: "restic, TLDR Pages"
description: "restic, A backup program that aims to be fast, secure and efficient."
categories: "common"
---
> More information: <https://restic.net>.

- Initialize a backup repository in the specified local directory:

```bash
restic init --repo path/to/repository
```

- Backup a directory to the repository:

```bash
restic --repo path/to/repository backup path/to/directory
```

- Show backup snapshots currently stored in the repository:

```bash
restic --repo path/to/repository snapshots
```

- Restore a specific backup snapshot to a target directory:

```bash
restic --repo path/to/repository restore latest|snapshot_id --target path/to/target
```

- Restore a specific path from a specific backup to a target directory:

```bash
restic --repo path/to/repository restore snapshot_id --target path/to/target --include path/to/restore
```

- Clean up the repository and keep only the most recent snapshot of each unique backup:

```bash
restic forget --keep-last 1 --prune
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Peter Babič](mailto:peter@babic.dev) | restic: fix restore example (#6240) | 2021-07-17T15:10:38 | [3f4d0a37fdf1](https://github.com/tldr-pages/tldr/commit/3f4d0a37fdf156d2d1d3dfdbdd34b8bdd58aefa4)
[Peter Babič](mailto:peter@babic.dev) | restic: replace -r by long argument --repo (#6212) | 2021-07-10T20:36:37 | [5c70d6589650](https://github.com/tldr-pages/tldr/commit/5c70d6589650774010a9249cc54986426dfacb69)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: rephrase without adjectives (#3846) Co-authored-by: Starbeamrainbowlabs <sbrl@starbeamrainbowlabs.com> Co-authored-by: [...] | 2020-02-11T18:53:43 | [8211b80c1722](https://github.com/tldr-pages/tldr/commit/8211b80c17221eed9f3f8530eafed3cc3fbd03f1)
[pxgamer](mailto:owzie123@gmail.com) | multiple pages: update the web link descriptions | 2019-05-29T14:41:10 | [f2b1446e6247](https://github.com/tldr-pages/tldr/commit/f2b1446e6247d3e794ee6577dee0c867dfc9af26)
[pxgamer](mailto:owzie123@gmail.com) | restic: add link to homepage | 2019-05-29T14:41:10 | [221c4c051a19](https://github.com/tldr-pages/tldr/commit/221c4c051a193f628612d929f9edf4f03cd28af6)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | Refactor: change "folder" to "directory" where needed. This commit fixes every instance in which the word "folder" is incorrectly used [...] | 2019-02-13T16:21:04 | [2599a6de483a](https://github.com/tldr-pages/tldr/commit/2599a6de483a70601ab17b29e0f18a5a8bdcaa12)
[Bruno Bigras](mailto:bigras.bruno@gmail.com) | restic: add how to restore a specific file (#2605) | 2018-11-24T11:10:08 | [88bccae363db](https://github.com/tldr-pages/tldr/commit/88bccae363dbdd8626f3fa919881020b41f85d31)
[Halvor Haukvik](mailto:hdhauk@users.noreply.github.com) | restic: add page (#1943) | 2018-02-05T10:18:52 | [6bbced900cd9](https://github.com/tldr-pages/tldr/commit/6bbced900cd900bc8c382dcc6798243649749aab)

