---
author: ['Cornelius Roemer']
date: 1661545521
title: "nextclade"
description: "nextclade, Bioinformatics tool for virus genome alignment, clade assignment and qc checks."
categories: "common"
---
> More information: <https://docs.nextstrain.org/projects/nextclade/en/stable/user/nextclade-cli.html>.

- Create a TSV report, auto-downloading the latest [d]ataset:

```bash
nextclade run -d dataset_name path/to/fasta -t path/to/output_tsv
```

- List all available datasets:

```bash
nextclade dataset list
```

- Download the latest SARS-CoV-2 dataset:

```bash
nextclade dataset get --name sars-cov-2 --output-dir path/to/directory
```

- Use a downloaded [D]ataset, producing all [O]utputs:

```bash
nextclade run -D path/to/dataset_dir -O path/to/output_dir path/to/dataset_dir/sequences.fasta
```

- Run on multiple files:

```bash
nextclade run -d dataset_name -t path/to/output_tsv -- path/to/input_fasta_1 path/to/input_fasta_2 ...
```

- Try reverse complement if sequence does not align:

```bash
nextclade run --retry-reverse-complement -d dataset_name -t path/to/output_tsv path/to/input_fasta
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Cornelius Roemer](mailto:cornelius.roemer@gmail.com) | nextclade: add page (#8400) | 2022-08-26T22:25:21 | [be8233b8bb57](https://github.com/tldr-pages/tldr/commit/be8233b8bb57f309186bfe4dd827a858faa9ff81)

