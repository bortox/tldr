---
author: ['Schneider', 'Lucas Gabriel Schneider', 'mashehu', 'pixel', 'Balázs Úr', 'Marco Bonelli', 'siavash', 'Seth Falco']
date: 1632941775
title: "bedtools"
description: "bedtools, A swiss-army knife of tools for genomic-analysis tasks."
categories: "common"
---
> Used to intersect, group, convert and count data in BAM, BED, GFF/GTF, VCF format.

> More information: <https://bedtools.readthedocs.io>.

- Intersect two files regarding the sequences' strand and save the result to the specified file:

```bash
bedtools intersect -a path/to/file_1 -b path/to/file_2 -s > path/to/output_file
```

- Intersect two files with a left outer join, i.e. report each feature from {{file_1}} and NULL if no overlap with {{file_2}}:

```bash
bedtools intersect -a path/to/file_1 -b path/to/file_2 -lof > path/to/output_file
```

- Using more efficient algorithm to intersect two pre-sorted files:

```bash
bedtools intersect -a path/to/file_1 -b path/to/file_2 -sorted > path/to/output_file
```

- Group file {{`path/to/file`}} based on the first three and the fifth column and summarize the sixth column by summing it up:

```bash
bedtools groupby -i path/to/file -c 1-3,5 -g 6 -o sum
```

- Convert bam-formatted file to a bed-formatted one:

```bash
bedtools bamtobed -i path/to/file.bam > path/to/file.bed
```

- Find for all features in {{file_1}}.bed the closest one in {{file_2}}.bed and write their distance in an extra column (input files must be sorted):

```bash
bedtools closest -a path/to/file_1.bed -b path/to/file_2.bed -d
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[pixel](mailto:chrissx@chrissx.de) | *: normalize readthedocs.io more information links (#6593) | 2021-09-29T20:56:15 | [d22ca9676f6c](https://github.com/tldr-pages/tldr/commit/d22ca9676f6c02b19e6e1728f5ea777e7985c9d0)
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[siavash](mailto:siavash.solimanii@yahoo.com) | bedtools, oc, sensible-editor, azcopy: fix typos and add oc project example (#4822) | 2020-10-24T14:58:11 | [71f4635d88d0](https://github.com/tldr-pages/tldr/commit/71f4635d88d0071425a5ee00ad1de49cefa763ac)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Schneider](mailto:lucas.schneider@sap.com) | bedtools.md: add homepage | 2019-04-12T14:41:22 | [58b01f27d0ee](https://github.com/tldr-pages/tldr/commit/58b01f27d0ee35fdaa0e1dcbbd2261a506c69554)
[Balázs Úr](mailto:balazs@urbalazs.hu) | multiple pages: remove superfluous white spaces (#2801) | 2019-02-24T16:47:41 | [ad3772d8cbd5](https://github.com/tldr-pages/tldr/commit/ad3772d8cbd5a61fecfb38ab13bdc7b104b4ecdf)
[mashehu](mailto:mashehu@users.noreply.github.com) | bedtools: add page (#1169) | 2016-12-22T00:07:22 | [a6983d4063c2](https://github.com/tldr-pages/tldr/commit/a6983d4063c2c234c464adef76d4946e1cac71e2)

