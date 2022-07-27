---
author: ['Waldir Pimenta', 'Kyle', 'Marco Bonelli', 'Phil Ewels', 'Lucas Gabriel Schneider']
date: 1628807637
title: "samtools, TLDR Pages"
description: "samtools, Tools for handling high-throughput sequencing (genomics) data."
categories: "common"
---
> Used for reading/writing/editing/indexing/viewing of data in SAM/BAM/CRAM format.

> More information: <https://www.htslib.org>.

- Convert a SAM input file to BAM stream and save to file:

```bash
samtools view -S -b input.sam > output.bam
```

- Take input from stdin (-) and print the SAM header and any reads overlapping a specific region to stdout:

```bash
other_command | samtools view -h - chromosome:start-end
```

- Sort file and save to BAM (the output format is automatically determined from the output file's extension):

```bash
samtools sort input -o output.bam
```

- Index a sorted BAM file (creates {{sorted_input.bam.bai}}):

```bash
samtools index sorted_input.bam
```

- Print alignment statistics about a file:

```bash
samtools flagstat sorted_input
```

- Count alignments to each index (chromosome / contig):

```bash
samtools idxstats sorted_indexed_input
```

- Merge multiple files:

```bash
samtools merge output input1 input2 …
```

- Split input file according to read groups:

```bash
samtools split merged_input
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Kyle](mailto:76597257+Gitleptune@users.noreply.github.com) | samtools: add more information link (#6336) | 2021-08-13T00:33:57 | [df4da3a557ef](https://github.com/tldr-pages/tldr/commit/df4da3a557ef4270a8ff90eed886ffdb1c342030)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | Harmonize formatting and capitalization of stdin/stdout/stderr | 2019-06-17T18:39:58 | [cf25745db1d8](https://github.com/tldr-pages/tldr/commit/cf25745db1d86744c762e15e6a2ba04ef9f9acc1)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | nmap, pdftk, samtools, tig: ellipsis consistency. | 2019-02-03T04:27:37 | [1799a53d7876](https://github.com/tldr-pages/tldr/commit/1799a53d7876f1abb9ddcd1eb33cd2ca6df745ca)
[Phil Ewels](mailto:phil.ewels@scilifelab.se) | samtools: add page (#1159) | 2016-11-26T08:47:48 | [951f690e1dc4](https://github.com/tldr-pages/tldr/commit/951f690e1dc467ee54b0e1d4218bebf536468ff1)

