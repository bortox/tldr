---
author: ['Waldir Pimenta', 'Lucas Gabriel Schneider', 'Balázs Úr', 'pxgamer', 'Ivan Aracki']
date: 1612112718
title: "gnomon"
description: "gnomon, Utility to annotate console logging statements with timestamps and find slow processes."
categories: "common"
---
> More information: <https://github.com/paypal/gnomon>.

- Use UNIX (or DOS) pipes to pipe the stdout of any command through gnomon:

```bash
npm test | gnomon
```

- Show number of seconds since the start of the process:

```bash
npm test | gnomon --type=elapsed-total
```

- Show an absolute timestamp in UTC:

```bash
npm test | gnomon --type=absolute
```

- Set a high threshold of 0.5 seconds for the elapsed time; exceeding which the timestamp will be colored bright red:

```bash
npm test | gnomon --high 0.5
```

- Set a medium threshold of 0.2 seconds (Timestamp will be colored bright yellow):

```bash
npm test | gnomon --medium 0.2
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | Harmonize formatting and capitalization of stdin/stdout/stderr | 2019-06-17T18:39:58 | [cf25745db1d8](https://github.com/tldr-pages/tldr/commit/cf25745db1d86744c762e15e6a2ba04ef9f9acc1)
[pxgamer](mailto:owzie123@gmail.com) | gnomon: add link to homepage | 2019-06-07T23:58:59 | [7a7ec840ceb7](https://github.com/tldr-pages/tldr/commit/7a7ec840ceb71f58346af015e79b2df5faad59f2)
[Balázs Úr](mailto:balazs@urbalazs.hu) | multiple pages: remove superfluous white spaces (#2801) | 2019-02-24T16:47:41 | [ad3772d8cbd5](https://github.com/tldr-pages/tldr/commit/ad3772d8cbd5a61fecfb38ab13bdc7b104b4ecdf)
[Ivan Aracki](mailto:aracki.ivan@gmail.com) | gnomon: add page (#2472) | 2018-10-29T11:46:55 | [927c82e055c6](https://github.com/tldr-pages/tldr/commit/927c82e055c6f159e58a6b0652d36b30ebd703cc)

