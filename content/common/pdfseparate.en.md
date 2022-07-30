---
author: ['Sahil Dhiman', 'Starbeamrainbowlabs']
date: 1600794952
title: "pdfseparate"
description: "pdfseparate, Portable Document Format (PDF) file page extractor."
categories: "common"
---
> More information: <https://manpages.debian.org/unstable/poppler-utils/pdfseparate.1.en.html>.

- Extract pages from PDF file and make a separate PDF file for each page:

```bash
pdfseparate path/to/source_filename.pdf path/to/destination_filename-%d.pdf
```

- Specify the first/start page for extraction:

```bash
pdfseparate -f 3 path/to/source_filename.pdf path/to/destination_filename-%d.pdf
```

- Specify the last page for extraction:

```bash
pdfseparate -l 10 path/to/source_filename.pdf path/to/destination_filename-%d.pdf
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | pdfseparate: teensy grammatical improvement | 2020-09-22T19:15:52 | [9bb108ac9fa8](https://github.com/tldr-pages/tldr/commit/9bb108ac9fa8a2b1f08518fbc550d1e283fe9ad2)
[Sahil Dhiman](mailto:52946452+sahilister@users.noreply.github.com) | pdfseparate: add page | 2020-09-22T19:15:52 | [7fd14afc9d6b](https://github.com/tldr-pages/tldr/commit/7fd14afc9d6be85d0a17868ab4be80632ae133e4)

