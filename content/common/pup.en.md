---
author: ['bl-ue', 'pxgamer', 'deekim']
date: 1621541621
title: "pup"
description: "pup, Command-line HTML parsing tool."
categories: "common"
---
> More information: <https://github.com/ericchiang/pup>.

- Transform a raw HTML file into a cleaned, indented, and colored format:

```bash
cat index.html | pup --color
```

- Filter HTML by element tag name:

```bash
cat index.html | pup 'tag'
```

- Filter HTML by id:

```bash
cat index.html | pup 'div#id'
```

- Filter HTML by attribute value:

```bash
cat index.html | pup 'input[type="text"]'
```

- Print all text from the filtered HTML elements and their children:

```bash
cat index.html | pup 'div text{}'
```

- Print HTML as JSON:

```bash
cat index.html | pup 'div json{}'
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[pxgamer](mailto:owzie123@gmail.com) | pup: add link to homepage | 2019-05-31T20:47:40 | [397e69f1c23f](https://github.com/tldr-pages/tldr/commit/397e69f1c23ff0970182933e54632d4a156028d2)
[deekim](mailto:todankim@gmail.com) | fixup! pup: add page | 2017-10-11T14:17:46 | [fbf4590e7a46](https://github.com/tldr-pages/tldr/commit/fbf4590e7a46618da1997da5b64e62f8cb1288a9)
[deekim](mailto:todankim@gmail.com) | fixup! pup: add page | 2017-10-11T01:05:27 | [2f4233a52da7](https://github.com/tldr-pages/tldr/commit/2f4233a52da71536f67ccbd51d1649cb322d65e6)
[deekim](mailto:todankim@gmail.com) | fixup! pup: add page | 2017-10-11T01:03:33 | [e5bcbfd08173](https://github.com/tldr-pages/tldr/commit/e5bcbfd08173d95dd93248829a6018792efc1952)
[deekim](mailto:todankim@gmail.com) | fixup! pup: add page | 2017-10-11T01:00:49 | [e2f2779c3c1e](https://github.com/tldr-pages/tldr/commit/e2f2779c3c1e3bc1f32477fb6f85337d14cf725e)
[deekim](mailto:todankim@gmail.com) | fixup! pup: add page | 2017-10-08T18:13:22 | [3dd8f82127ac](https://github.com/tldr-pages/tldr/commit/3dd8f82127ac228d84b511b4013b4e5ee46e8109)
[deekim](mailto:todankim@gmail.com) | fixup! pup: add page | 2017-10-08T18:03:16 | [7ebeed5ca757](https://github.com/tldr-pages/tldr/commit/7ebeed5ca757a72084d9d4ae86ef47bd2a335612)
[deekim](mailto:todankim@gmail.com) | pup: add page | 2017-10-08T18:00:15 | [f76926abdbd4](https://github.com/tldr-pages/tldr/commit/f76926abdbd43662814fee95f2e3e28ec37132ad)

