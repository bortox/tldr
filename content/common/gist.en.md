---
author: ['Waldir Pimenta', 'jasonxia23', 'Thales Mello', 'Nicolas Kosinski', 'Lucas Gabriel Schneider', 'pxgamer', 'Guido Lena Cota', 'Seth Falco', 'marchersimon']
date: 1629050349
title: "gist"
description: "gist, Upload code to https://gist.github.com."
categories: "common"
---
> More information: <https://github.com/defunkt/gist>.

- Log in in gist on this computer:

```bash
gist --login
```

- Create a gist from any number of text files:

```bash
gist file.txt file2.txt
```

- Create a private gist with a description:

```bash
gist --private --description "A meaningful description" file.txt 
```

- Read contents from stdin and create a gist from it:

```bash
echo "hello world" | gist
```

- List your public and private gists:

```bash
gist --list
```

- List all public gists for any user:

```bash
gist --list username
```

- Update a gist using the ID from URL:

```bash
gist --update GIST_ID file.txt
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | change login/logout to `log in`/`log out` (#5920) | 2021-05-14T02:42:15 | [be88cdda9201](https://github.com/tldr-pages/tldr/commit/be88cdda9201a6262af27d8788e222b5df98cc9c)
[Nicolas Kosinski](mailto:nicolas.kosinski@vidal.fr) | gist: enhance list/update description (#5666) | 2021-04-02T18:59:30 | [80c2d46b46de](https://github.com/tldr-pages/tldr/commit/80c2d46b46deb6735b262f13109001f0a3ebfcaa)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Guido Lena Cota](mailto:guido.lenacota@kreuzwerker.de) | Bulk change: move double quotes outside tokens (#4431) | 2020-10-04T19:33:38 | [354d4b8748ee](https://github.com/tldr-pages/tldr/commit/354d4b8748ee58813dd6830ced7c3b11067255d7)
[Lucas Gabriel Schneider](mailto:lucas.schneider@sap.com) | multiple pages: change user_name to username (#3841) | 2020-02-08T19:56:05 | [26e019b295f1](https://github.com/tldr-pages/tldr/commit/26e019b295f1782e6dd695b03108f061946327e8)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | Harmonize formatting and capitalization of stdin/stdout/stderr | 2019-06-17T18:39:58 | [cf25745db1d8](https://github.com/tldr-pages/tldr/commit/cf25745db1d86744c762e15e6a2ba04ef9f9acc1)
[pxgamer](mailto:owzie123@gmail.com) | gist: add link to homepage | 2019-06-07T23:58:59 | [8af2ae09a308](https://github.com/tldr-pages/tldr/commit/8af2ae09a308550515eb9f501c658710dfea90d7)
[jasonxia23](mailto:xia_da_yu@126.com) | gist: add two examples (#1453) | 2017-08-25T13:53:33 | [563ccc9b2ae3](https://github.com/tldr-pages/tldr/commit/563ccc9b2ae3df3ec53724a5333b75cd66aa6a47)
[Thales Mello](mailto:thalesmello@gmail.com) | gist: add page (#1389) * Include gist page * Fix linting errors * Quote "hello world" in the echo commnad * Change wording to make [...] | 2017-05-29T17:02:09 | [efedbb283593](https://github.com/tldr-pages/tldr/commit/efedbb28359321804b2f9be094328e72ecb5a8ef)

