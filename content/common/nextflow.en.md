---
author: ['Phil Ewels', 'Lucas Gabriel Schneider', 'sebastientinel']
date: 1603905583
title: "nextflow, TLDR Pages"
description: "nextflow, Tool for running computational pipelines. Mostly used for bioinformatics workflows."
categories: "common"
---
> More information: <https://www.nextflow.io>.

- Run a pipeline, use cached results from previous runs:

```bash
nextflow run main.nf -resume
```

- Run a specific release of a remote workflow from GitHub:

```bash
nextflow run user/repo -revision release_tag
```

- Run with a given work directory for intermediate files, save execution report:

```bash
nextflow run workflow -work-dir path/to/directory -with-report report.html
```

- Show details of previous runs in current directory:

```bash
nextflow log
```

- Remove cache and intermediate files for a specific run:

```bash
nextflow clean -force run_name
```

- List all downloaded projects:

```bash
nextflow list
```

- Pull the latest version of a remote workflow from Bitbucket:

```bash
nextflow pull user/repo -hub bitbucket
```

- Update Nextflow:

```bash
nextflow self-update
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[sebastientinel](mailto:sebastien.tinel@gmail.com) | multiple pages: Unify file path syntax to indicate a 'path to' (#4816) | 2020-10-28T18:19:43 | [1d32985f2f24](https://github.com/tldr-pages/tldr/commit/1d32985f2f24e5469dddc993dd7f354f79bfa128)
[Lucas Gabriel Schneider](mailto:lucas.schneider@sap.com) | multiple pages (pt_BR): fix homepage tokens (#3340) | 2019-10-07T15:31:50 | [83b623d988f7](https://github.com/tldr-pages/tldr/commit/83b623d988f7940581b5e9fbd43ec0fdc7496a68)
[Phil Ewels](mailto:phil.ewels@scilifelab.se) | nextflow: Move to common (#3270) | 2019-09-17T21:46:07 | [c84b65456111](https://github.com/tldr-pages/tldr/commit/c84b65456111ba476ae24af99ef8f3f1c2bd9ec5)

