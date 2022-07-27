---
author: ['David Heimann', 'Marco Bonelli', 'Seth Falco', 'Starbeamrainbowlabs']
date: 1629050349
title: "serverless, TLDR Pages"
description: "serverless, Toolkit for deploying and operating serverless architectures on AWS, Google Cloud, Azure and IBM OpenWhisk."
categories: "common"
---
> Commands can be run either using the `serverless` command or its alias, `sls`.

> More information: <https://serverless.com/>.

- Create a serverless project:

```bash
serverless create
```

- Create a serverless project from a template:

```bash
serverless create --template template_name
```

- Deploy to a cloud provider:

```bash
serverless deploy
```

- Display information about a serverless project:

```bash
serverless info
```

- Invoke a deployed function:

```bash
serverless invoke -f function_name
```

- Follow the logs for a project:

```bash
serverless logs -t
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | multiple pages: add homepages (#2660) | 2019-01-30T12:19:23 | [a19866e88add](https://github.com/tldr-pages/tldr/commit/a19866e88addb239484637579b17e7c6ea9b53aa)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | Revert "multiple pages: add homepages" This reverts commit 347e5573036e13b360b81a3f9f1bad75cf2c2b03. | 2018-12-20T00:33:18 | [45ec3033c04f](https://github.com/tldr-pages/tldr/commit/45ec3033c04fbc67b97fa4d21e2b409b1f14a667)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | multiple pages: add homepages | 2018-12-20T00:29:00 | [347e5573036e](https://github.com/tldr-pages/tldr/commit/347e5573036e13b360b81a3f9f1bad75cf2c2b03)
[David Heimann](mailto:davidheimann@gmail.com) | Move log example, remove metrics and add invoke | 2017-12-20T21:41:32 | [5496cd9478df](https://github.com/tldr-pages/tldr/commit/5496cd9478df999b67279e81c71138029b2b4ed3)
[David Heimann](mailto:davidheimann@gmail.com) | Remove rogue space from end of description line. | 2017-12-19T20:03:12 | [0ca78603e8cf](https://github.com/tldr-pages/tldr/commit/0ca78603e8cfa49909858a472fccef48b7832f0c)
[David Heimann](mailto:davidheimann@gmail.com) | Add single quotes around commands in description | 2017-12-19T19:58:43 | [7cc56dde3fde](https://github.com/tldr-pages/tldr/commit/7cc56dde3fdedfb9a94958f97a3e1c76a8d3a13d)
[David Heimann](mailto:davidheimann@gmail.com) | Use the serverless command in examples | 2017-12-19T19:56:26 | [134eb1fd83f4](https://github.com/tldr-pages/tldr/commit/134eb1fd83f43e2a20be21d7d4cb00c585501af6)
[David Heimann](mailto:davidheimann@gmail.com) | Add definite and indefinite articles | 2017-12-19T15:45:17 | [e2b10df5e274](https://github.com/tldr-pages/tldr/commit/e2b10df5e274eb0ca97a13924c215481c12075b5)
[David Heimann](mailto:davidheimann@gmail.com) | Add newline at the end of file | 2017-12-18T22:39:52 | [01fbda27752c](https://github.com/tldr-pages/tldr/commit/01fbda27752c60c93d18b0b828d8a1d5ee2e86ba)
[David Heimann](mailto:davidheimann@gmail.com) | remove trailing whitespace | 2017-12-18T22:38:38 | [a9dc8c46c2f4](https://github.com/tldr-pages/tldr/commit/a9dc8c46c2f489e3f3631e21c29c73edf8538594)
[David Heimann](mailto:davidheimann@gmail.com) | Add colon to first description | 2017-12-18T22:35:44 | [8e72df9fdbbb](https://github.com/tldr-pages/tldr/commit/8e72df9fdbbb752027591737d795f987d6075710)
[David Heimann](mailto:davidheimann@gmail.com) | Add serverless page | 2017-12-18T22:30:51 | [f5b8b4e2b53d](https://github.com/tldr-pages/tldr/commit/f5b8b4e2b53d26c930ed732feea77386552b6a15)

