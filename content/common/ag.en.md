---
author: ['Guilherme Leobas', 'Waldir Pimenta', 'Marco Bonelli', 'Ruben Vereecken', 'pxgamer', 'Robert Speicher', 'Lin Dong', 'AnimiVulpis', 'Lucas Gabriel Schneider']
date: 1581443623
title: "ag, TLDR Pages"
description: "ag, The Silver Searcher. Like ack, but aims to be faster."
categories: "common"
---
> More information: <https://github.com/ggreer/the_silver_searcher>.

- Find files containing "foo", and print the line matches in context:

```bash
ag foo
```

- Find files containing "foo" in a specific directory:

```bash
ag foo path/to/directory
```

- Find files containing "foo", but only list the filenames:

```bash
ag -l foo
```

- Find files containing "FOO" case-insensitively, and print only the match, rather than the whole line:

```bash
ag -i -o FOO
```

- Find "foo" in files with a name matching "bar":

```bash
ag foo -G bar
```

- Find files whose contents match a regular expression:

```bash
ag '^ba(r|z)$'
```

- Find files with a name matching "foo":

```bash
ag -g foo
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: rephrase without adjectives (#3846) Co-authored-by: Starbeamrainbowlabs <sbrl@starbeamrainbowlabs.com> Co-authored-by: [...] | 2020-02-11T18:53:43 | [8211b80c1722](https://github.com/tldr-pages/tldr/commit/8211b80c17221eed9f3f8530eafed3cc3fbd03f1)
[pxgamer](mailto:owzie123@gmail.com) | ag: add link to homepage | 2019-06-09T18:53:49 | [c90ba9c0c21c](https://github.com/tldr-pages/tldr/commit/c90ba9c0c21c2fdf9c0a2ce2e8f5b1e606066f67)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | Refactor: improve consistency of the term "directory". This commit changes the term "folder" to "directory" in every instance where [...] | 2019-02-08T20:43:24 | [ac4094e0ad70](https://github.com/tldr-pages/tldr/commit/ac4094e0ad70a6be2163b06d24b53992b93aee4f)
[Guilherme Leobas](mailto:guilhermeleobas@gmail.com) | ag: move text to make it the 2nd example (#2498) | 2018-10-26T21:29:29 | [3caafe6ef741](https://github.com/tldr-pages/tldr/commit/3caafe6ef741983122855346290ad082bde1949e)
[Guilherme Leobas](mailto:guilhermeleobas@gmail.com) | ag: add example (#2491) | 2018-10-24T22:33:11 | [8ad9792a96e6](https://github.com/tldr-pages/tldr/commit/8ad9792a96e686eddcc25a139533be47c740cb78)
[AnimiVulpis](mailto:animi.vulpis@gmail.com) | Fix tokenization | 2017-10-31T22:41:52 | [86aee1cfae30](https://github.com/tldr-pages/tldr/commit/86aee1cfae30ab634ee00f003a8bac2f3382e8a7)
[AnimiVulpis](mailto:animi.vulpis@gmail.com) | ag: tokenize values | 2017-10-30T23:48:56 | [2d3be200464d](https://github.com/tldr-pages/tldr/commit/2d3be200464d40e91d8b2b7596775a925929c9c0)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | ag: add -l and -o options | 2016-05-02T15:33:59 | [4517f2e411c4](https://github.com/tldr-pages/tldr/commit/4517f2e411c49af3457f1556ca0935d96f46704f)
[Lin Dong](mailto:ldong@users.noreply.github.com) | Update ag 1. Add case-insensitive search example | 2016-02-18T18:58:34 | [6249958bc642](https://github.com/tldr-pages/tldr/commit/6249958bc642a966dae1cc5b584509442268cff5)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Robert Speicher](mailto:rspeicher@gmail.com) | Add ag (the_silver_searcher) page | 2014-05-02T03:25:35 | [44acd7291410](https://github.com/tldr-pages/tldr/commit/44acd7291410c3445fb0b898363787d4ffb21bce)

