---
author: ['Schneider', 'b3nj5m1n', 'Ruben Vereecken', 'Miguel Palhas', 'Agniva De Sarker', 'pxgamer', 'CleanMachine1', 'lucas schneider', 'Lucas Gabriel Schneider']
date: 1635744666
title: "pass, TLDR Pages"
description: "pass, Tool for storing and reading passwords or other sensitive data."
categories: "common"
---
> All data is GPG-encrypted, and managed with a Git repository.

> More information: <https://www.passwordstore.org>.

- Initialize (or re-encrypt) the storage using one or more GPG IDs:

```bash
pass init gpg_id_1 gpg_id_2
```

- Save a new password and additional information (press Ctrl + D on a new line to complete):

```bash
pass insert --multiline path/to/data
```

- Edit an entry:

```bash
pass edit path/to/data
```

- Copy a password (first line of the data file) to the clipboard:

```bash
pass -c path/to/data
```

- List the whole store tree:

```bash
pass
```

- Generate a new random password with a given length, and copy it to the clipboard:

```bash
pass generate -c path/to/data num
```

- Initialize a new Git repository (any changes done by pass will be committed automatically):

```bash
pass git init
```

- Run a Git command on behalf of the password storage:

```bash
pass git command
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[CleanMachine1](mailto:78213164+CleanMachine1@users.noreply.github.com) | pass: add git command example (#7300) | 2021-11-01T06:31:06 | [39d4e183b663](https://github.com/tldr-pages/tldr/commit/39d4e183b663644b7847fed9a49d09f8ad00a0f9)
[lucas schneider](mailto:casdpa@gmail.com) | rename git to Git | 2021-01-08T14:09:54 | [eef3712fc3a6](https://github.com/tldr-pages/tldr/commit/eef3712fc3a6a3774384b2e4ed934583c8349d75)
[b3nj5m1n](mailto:47924309+b3nj5m1n@users.noreply.github.com) | pass: add edit example, add more info to init/insert, simplify git example (#4139) Co-authored-by: Zlatan Vasović [...] | 2020-07-02T14:20:43 | [6fadfd16a996](https://github.com/tldr-pages/tldr/commit/6fadfd16a996309efd192bb4b1a75b1b97152ddd)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | pass: rephrase example Co-Authored-By: Starbeamrainbowlabs <sbrl@starbeamrainbowlabs.com> | 2020-02-20T18:00:28 | [5012c02228d8](https://github.com/tldr-pages/tldr/commit/5012c02228d8bc49ce993d5e3bc53c95532c277f)
[Schneider](mailto:lucas.schneider@sap.com) | pass: remove adjectives | 2020-02-20T18:00:28 | [5cd2e190369f](https://github.com/tldr-pages/tldr/commit/5cd2e190369fc5ee190b937e15806ee681569ce0)
[pxgamer](mailto:owzie123@gmail.com) | pass: add link to homepage | 2019-05-31T20:47:40 | [5dc717b80781](https://github.com/tldr-pages/tldr/commit/5dc717b80781d801d64e3dceb45d36daa3f471c6)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | Applying the snake_case convention throughout the repo (#967) * Applying the snake_case convention throughout the repo - Also removing [...] | 2016-07-22T22:24:06 | [3da76e4150b8](https://github.com/tldr-pages/tldr/commit/3da76e4150b8631fd74aabfcc953cc23731b6bb8)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Miguel Palhas](mailto:mpalhas@gmail.com) | Add pass command http://www.passwordstore.org/ | 2016-01-06T20:24:23 | [6a9e8533dca3](https://github.com/tldr-pages/tldr/commit/6a9e8533dca3c33e4ebcd40fee9ebd6a199a9b2b)

