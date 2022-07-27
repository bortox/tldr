---
author: ['lasersharks', 'Guido Lena Cota', 'Francesco Yoshi Gobbo']
date: 1601832818
title: "snapper, TLDR Pages"
description: "snapper, Filesystem snapshot management tool."
categories: "linux"
---
> More information: <http://snapper.io/manpages/snapper.html>.

- List snapshot configs:

```bash
snapper list-configs
```

- Create snapper config:

```bash
snapper -c config create-config path/to/directory
```

- Create a snapshot with a description:

```bash
snapper -c config create -d "snapshot_description"
```

- List snapshots for a config:

```bash
snapper -c config list
```

- Delete a snapshot:

```bash
snapper -c config delete snapshot_number
```

- Delete a range of snapshots:

```bash
snapper -c config delete snapshot_X-snapshot_Y
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Guido Lena Cota](mailto:guido.lenacota@kreuzwerker.de) | Bulk change: move double quotes outside tokens (#4431) | 2020-10-04T19:33:38 | [354d4b8748ee](https://github.com/tldr-pages/tldr/commit/354d4b8748ee58813dd6830ced7c3b11067255d7)
[Francesco Yoshi Gobbo](mailto:yoshi@fgobbo.com) | snapper: snapshot creation (#3200) | 2019-07-23T05:39:39 | [1899a9fd22c5](https://github.com/tldr-pages/tldr/commit/1899a9fd22c5fc07993051551b8bf4de6ba9b0ab)
[lasersharks](mailto:jackbeckett92@gmail.com) | snapper: update snapper delete with path/to/directory | 2018-07-08T18:49:18 | [fac3666845b6](https://github.com/tldr-pages/tldr/commit/fac3666845b66b8a619f4ea109d008cd87996b1c)
[lasersharks](mailto:jackbeckett92@gmail.com) | snapper: update snapper delete | 2018-07-08T18:49:18 | [89253ea4e57a](https://github.com/tldr-pages/tldr/commit/89253ea4e57a439337e909e9635c3083a99812fa)
[lasersharks](mailto:jackbeckett92@gmail.com) | snapper: add fullstop to description | 2018-07-08T18:49:18 | [804dcf69b005](https://github.com/tldr-pages/tldr/commit/804dcf69b0053389d7fb39a8c8d038b8744a42aa)
[lasersharks](mailto:jackbeckett92@gmail.com) | snapper: add page | 2018-07-08T18:49:18 | [e64e66f82019](https://github.com/tldr-pages/tldr/commit/e64e66f8201994666b1be1e560fadcd70b78b702)

