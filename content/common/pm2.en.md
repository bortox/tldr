---
author: ['Waldir Pimenta', 'pxgamer', 'Phil Rukin', 'Nir Elbaz', 'Vincent Yang']
date: 1622740034
title: "pm2"
description: "pm2, Process manager for Node.js."
categories: "common"
---
> Used for log management, monitoring and configuring processes.

> More information: <https://pm2.keymetrics.io>.

- Start a process with a name that can be used for later operations:

```bash
pm2 start app.js --name myapp
```

- List processes:

```bash
pm2 list
```

- Monitor all processes:

```bash
pm2 monit
```

- Stop a process:

```bash
pm2 stop myapp
```

- Restart a process:

```bash
pm2 restart myapp
```

- Dump all processes for resurrecting them later:

```bash
pm2 save
```

- Resurrect previously dumped processes:

```bash
pm2 resurrect
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Phil Rukin](mailto:philipp@rukin.me) | pm2: remove duplicate monit example (#6090) | 2021-06-03T19:07:14 | [c9d70c3f1828](https://github.com/tldr-pages/tldr/commit/c9d70c3f1828f647b10345a9067db8c64934250d)
[Nir Elbaz](mailto:nire0510@gmail.com) | Update pm2.md (#3569) | 2019-11-18T11:18:32 | [e9967dfdecb2](https://github.com/tldr-pages/tldr/commit/e9967dfdecb29b15b00098c7a06b65c0d0329de2)
[pxgamer](mailto:owzie123@gmail.com) | pm2: add link to homepage | 2019-05-31T20:47:40 | [21e164970a47](https://github.com/tldr-pages/tldr/commit/21e164970a477e652fc5816d6db284d8c0f3d69a)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | pm2: add article in last two examples | 2017-05-01T12:16:05 | [3b0cf23bacea](https://github.com/tldr-pages/tldr/commit/3b0cf23bacea13fc4e7be80335e8f43ab196131e)
[Vincent Yang](mailto:VincentYang2014@gmail.com) | pm2: add page (#1306) * pm2: add page * Make Travis happy * Added pm2 restart * Simplifying examples * Fixed typo | 2017-04-06T13:40:06 | [7fd90b1d58cc](https://github.com/tldr-pages/tldr/commit/7fd90b1d58cc4a543ac8845d3b31839d68bbb47a)

