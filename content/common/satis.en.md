---
author: ['pxgamer', 'Seth Falco']
date: 1656325392
title: "satis"
description: "satis, The command-line utility for the Satis static Composer repository."
categories: "common"
---
> More information: <https://github.com/composer/satis>.

- Initialize a Satis configuration:

```bash
satis init satis.json
```

- Add a VCS repository to the Satis configuration:

```bash
satis add repository_url
```

- Build the static output from the configuration:

```bash
satis build satis.json path/to/output_directory
```

- Build the static output by updating only the specified repository:

```bash
satis build --repository-url repository_url satis.json path/to/output_directory
```

- Remove useless archive files:

```bash
satis purge satis.json path/to/output_directory
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: convert en-GB to en-US (#8155) | 2022-06-27T12:23:12 | [34fde6d16fbc](https://github.com/tldr-pages/tldr/commit/34fde6d16fbc0a3c45fff5903f0fc2597547b1bb)
[pxgamer](mailto:owzie123@gmail.com) | multiple pages: update the web link descriptions | 2019-05-29T14:41:10 | [f2b1446e6247](https://github.com/tldr-pages/tldr/commit/f2b1446e6247d3e794ee6577dee0c867dfc9af26)
[pxgamer](mailto:owzie123@gmail.com) | satis: add link to homepage | 2019-05-29T14:41:10 | [26e1aff0ea16](https://github.com/tldr-pages/tldr/commit/26e1aff0ea1661a2a431b2a87c544c7bf8b03510)
[pxgamer](mailto:owzie123@gmail.com) | satis: add page | 2019-02-18T22:51:25 | [409355108a96](https://github.com/tldr-pages/tldr/commit/409355108a9655b3a17510385a8ed69a69635337)

