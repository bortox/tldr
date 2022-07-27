---
author: ['johnsmith2077', 'Harrison', 'Waldir Pimenta', 'Schneider', 'Emily Grace Seville', 'Matt Watson', 'Marco Bonelli', 'Agniva De Sarker', 'pxgamer', 'chuanjin', 'Eric Nielsen', 'Yorke Rhodes', 'Erik Bartels', 'maximpertsov', 'Bruno Bigras', 'Lucas Gabriel Schneider', 'Starbeamrainbowlabs']
date: 1653793342
title: "jq, TLDR Pages"
description: "jq, A command-line JSON processor that uses a domain-specific language."
categories: "common"
---
> More information: <https://stedolan.github.io/jq/manual/>.

- Execute a specific expression (print a colored and formatted json):

```bash
cat path/to/file.json | jq '.'
```

- Execute a specific script:

```bash
cat path/to/file.json | jq --from-file path/to/script.jq
```

- Pass specific arguments:

```bash
cat path/to/file.json | jq --arg "name1" "value1" --arg "name2" "value2" ... '. + $ARGS.named'
```

- Print specific keys:

```bash
cat path/to/file.json | jq '.key1, .key2, ...'
```

- Print specific array items:

```bash
cat path/to/file.json | jq '.[index1], .[index2], ...'
```

- Print all array items/object keys:

```bash
cat path/to/file.json | jq '.[]'
```

- Add/remove specific keys:

```bash
cat path/to/file.json | jq '. +|- {"key1": "value1", "key2": "value2", ...}'
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | jq: refresh page (#7995) * Prefer `a specific` * Fix grammar errors | 2022-05-29T05:02:22 | [47479477449c](https://github.com/tldr-pages/tldr/commit/47479477449cff1a76276aabd0dd07244e8cab51)
[Erik Bartels](mailto:eb@soundcloud.com) | jq: remove filename dangling quote (#8063) | 2022-04-30T09:07:02 | [61805c1a2557](https://github.com/tldr-pages/tldr/commit/61805c1a2557b6004374e0950f7d027b2a65020e)
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | jq: update page (#7945) * Fix manual url * Replace all old examples with new ones: - executing expression/script - accessing [...] | 2022-04-13T03:45:18 | [f0dacdbd2098](https://github.com/tldr-pages/tldr/commit/f0dacdbd20986a8fef80179f94f120df3234928e)
[Yorke Rhodes](mailto:email@yorke.dev) | jq: add filter array example (#7871) * Add filter array example * Remove 8th example | 2022-03-12T05:08:08 | [fc874d901b15](https://github.com/tldr-pages/tldr/commit/fc874d901b15f45d16ae8902e2d8b53cd8bad595)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | jq: remove example to bring it under the 8 example limit (#5057) | 2021-01-01T22:30:53 | [a1b636f844b8](https://github.com/tldr-pages/tldr/commit/a1b636f844b82fd0fcc5496b2e26932684137c2a)
[johnsmith2077](mailto:66582070+johnsmith2077@users.noreply.github.com) | jq: correct description of example (#4299) | 2020-08-28T10:25:06 | [595194214314](https://github.com/tldr-pages/tldr/commit/595194214314eed8e9066d0a51c094391cae7122)
[Harrison](mailto:mccullough.harrison@gmail.com) | jq: fix jq syntax error (#4257) | 2020-08-11T17:49:43 | [677ca84ceb20](https://github.com/tldr-pages/tldr/commit/677ca84ceb201fbad54ebc1462031586691fcca1)
[Matt Watson](mailto:matthew.watson1990@googlemail.com) | jq: Add example for constructing new JSON object (#4172) Co-authored-by: Starbeamrainbowlabs <sbrl@starbeamrainbowlabs.com> | 2020-07-17T19:37:49 | [fc69d1297dee](https://github.com/tldr-pages/tldr/commit/fc69d1297dee295a9025e4a1220a405d40ee307d)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | jq: rephrase description Co-Authored-By: Starbeamrainbowlabs <sbrl@starbeamrainbowlabs.com> | 2020-02-20T18:00:28 | [36dae50265e1](https://github.com/tldr-pages/tldr/commit/36dae50265e1aa8a43b0c12e0e47954c1bce25fc)
[Schneider](mailto:lucas.schneider@sap.com) | jq: remove adjectives | 2020-02-20T18:00:28 | [2ea46b006fa1](https://github.com/tldr-pages/tldr/commit/2ea46b006fa10740bcc38e5a5c0e9886bbcedca9)
[chuanjin](mailto:chuan.jin.813@gmail.com) | Update jq page with correct command format | 2019-06-27T19:07:24 | [14cefcc7f96a](https://github.com/tldr-pages/tldr/commit/14cefcc7f96a997fc5f43f6c2abd51e457574f0b)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | Harmonize formatting and capitalization of stdin/stdout/stderr | 2019-06-17T18:39:58 | [cf25745db1d8](https://github.com/tldr-pages/tldr/commit/cf25745db1d86744c762e15e6a2ba04ef9f9acc1)
[pxgamer](mailto:owzie123@gmail.com) | jq: add link to homepage | 2019-06-06T04:42:48 | [afd88db28233](https://github.com/tldr-pages/tldr/commit/afd88db28233433aaaeb500249564e1153c2d68b)
[Bruno Bigras](mailto:bigras.bruno@gmail.com) | jq: add 'output to string' example (#2916) | 2019-04-22T22:22:29 | [c24e2d610c65](https://github.com/tldr-pages/tldr/commit/c24e2d610c65e7b8572a47ba42927669d6bbf498)
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | jq: fix typo (#2925) | 2019-04-18T07:45:39 | [e952f260dcdf](https://github.com/tldr-pages/tldr/commit/e952f260dcdf436d1582a97355bb4432335ff2bd)
[Bruno Bigras](mailto:bigras.bruno@gmail.com) | jq: add 'combines multiple filters' example (#2917) | 2019-04-17T16:55:23 | [1c66acf26847](https://github.com/tldr-pages/tldr/commit/1c66acf26847a9e7e5091cd580e2926ff89b8728)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | jq: clarify json text input from stdin | 2018-04-17T11:05:20 | [1fd030ef01a3](https://github.com/tldr-pages/tldr/commit/1fd030ef01a357789fe233e7b4195a537dc464a1)
[Eric Nielsen](mailto:eric@amalgamar.com.br) | jq: Accepts a file as last parameter Examples look simpler with file as last parameter than with using `cat`, also they explicitly [...] | 2018-04-17T11:05:20 | [a2d755a50401](https://github.com/tldr-pages/tldr/commit/a2d755a504012af2932919fbd9dd36e4b1913a27)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | jq: clarify descriptions (#1361) | 2017-05-04T10:35:38 | [7ca686634d69](https://github.com/tldr-pages/tldr/commit/7ca686634d69d983b9e3ba5ffe6463e16479aa8f)
[maximpertsov](mailto:maxim.pertsov@gmail.com) | jq: add page (#1092) | 2016-12-22T00:40:12 | [89c2015940c2](https://github.com/tldr-pages/tldr/commit/89c2015940c27891f6d57f0bd1cf6f4c8f186345)

