---
author: ['pxgamer', 'Hayden Schiff']
date: 1560099229
title: "csvstat, TLDR Pages"
description: "csvstat, Print descriptive statistics for all columns in a CSV file."
categories: "common"
---
> Included in csvkit.

> More information: <https://csvkit.readthedocs.io/en/latest/scripts/csvstat.html>.

- Show all stats for all columns:

```bash
csvstat data.csv
```

- Show all stats for columns 2 and 4:

```bash
csvstat -c 2,4 data.csv
```

- Show sums for all columns:

```bash
csvstat --sum data.csv
```

- Show the max value length for column 3:

```bash
csvstat -c 3 --len data.csv
```

- Show the number of unique values in the "name" column:

```bash
csvstat -c name --unique data.csv
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[pxgamer](mailto:owzie123@gmail.com) | csvstat: add link to homepage | 2019-06-09T18:53:49 | [13bc0a39a732](https://github.com/tldr-pages/tldr/commit/13bc0a39a7328d4f36b1c4edfc7309808f7679d9)
[Hayden Schiff](mailto:oxguy3@gmail.com) | fixed typo, removed an example for brevity | 2016-01-22T00:18:05 | [6937b082d69f](https://github.com/tldr-pages/tldr/commit/6937b082d69f41f527217f8c714bc81e60a29625)
[Hayden Schiff](mailto:oxguy3@gmail.com) | added csvstat | 2016-01-22T00:04:35 | [ff695a1601c3](https://github.com/tldr-pages/tldr/commit/ff695a1601c3dfc31242525f91b82e1d38d7b153)

