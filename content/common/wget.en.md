---
author: ['Waldir Pimenta', 'Eric Nielsen', 'Owen Voke', 'a-raccoon', 'Nicolas Kosinski', 'rprieto', 'lord63', 'Kishan B', 'Thomas BARUSSEAU', 'Marco Bonelli', 'Larry850806', 'saeed', 'Seth Falco', 'Ruben Vereecken']
date: 1629050349
title: "wget"
description: "wget, Download files from the Web."
categories: "common"
---
> Supports HTTP, HTTPS, and FTP.

> More information: <https://www.gnu.org/software/wget>.

- Download the contents of a URL to a file (named "foo" in this case):

```bash
wget https://example.com/foo
```

- Download the contents of a URL to a file (named "bar" in this case):

```bash
wget --output-document bar https://example.com/foo
```

- Download a single web page and all its resources with 3-second intervals between requests (scripts, stylesheets, images, etc.):

```bash
wget --page-requisites --convert-links --wait=3 https://example.com/somepage.html
```

- Download all listed files within a directory and its sub-directories (does not download embedded page elements):

```bash
wget --mirror --no-parent https://example.com/somepath/
```

- Limit the download speed and the number of connection retries:

```bash
wget --limit-rate=300k --tries=100 https://example.com/somepath/
```

- Download a file from an HTTP server using Basic Auth (also works for FTP):

```bash
wget --user=username --password=password https://example.com
```

- Continue an incomplete download:

```bash
wget --continue https://example.com
```

- Download all URLs stored in a text file to a specific directory:

```bash
wget --directory-prefix path/to/directory --input-file URLs.txt
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Nicolas Kosinski](mailto:nicokosi@yahoo.com) | wget: use long arguments (#5879) | 2021-05-04T09:25:49 | [5d01dae43fae](https://github.com/tldr-pages/tldr/commit/5d01dae43fae9f8dcf5d5f1d7df2d7104ece7907)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Owen Voke](mailto:owzie123@gmail.com) | multiple pages: add homepages (#3026) * zstd: add link to homepage * zsh: add link to homepage * zopflipng: add link to homepage * [...] | 2019-05-14T18:09:07 | [c4e95b92c42f](https://github.com/tldr-pages/tldr/commit/c4e95b92c42fe9fe8428c8d7c8cd5ad8d0bd1b0b)
[saeed](mailto:39596095+smzm@users.noreply.github.com) | wget : add some options (#2798) | 2019-02-26T23:15:47 | [558edac53e36](https://github.com/tldr-pages/tldr/commit/558edac53e36792c2146e9134ebd43673df3c762)
[Kishan B](mailto:kishancs46@gmail.com) | wget.md: add quiet mode (#2026) | 2018-03-16T14:57:22 | [1dc079ce24e3](https://github.com/tldr-pages/tldr/commit/1dc079ce24e3f5fe9e0cce14a4562bbc16887b72)
[a-raccoon](mailto:a-raccoon.gethub@vulp.us) | wget: Add subdirectory example (#1693) | 2018-01-09T09:29:24 | [33e9cb17b3e3](https://github.com/tldr-pages/tldr/commit/33e9cb17b3e3c72a36afa8ac62a6b5f872d32220)
[Thomas BARUSSEAU](mailto:Thomas.BARUSSEAU@ingenico.com) | wget: update page | 2017-12-07T04:24:52 | [3a0d13a8d2ea](https://github.com/tldr-pages/tldr/commit/3a0d13a8d2eab14f0cb8dcc08140aee49105e8fc)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | wget: reorder examples and add additional details (#1501) | 2017-09-27T16:27:59 | [968aa0bff4d8](https://github.com/tldr-pages/tldr/commit/968aa0bff4d8ab71cdf6111b0298f240b6fa4675)
[Eric Nielsen](mailto:eric@amalgamar.com.br) | wget: Use same example description as for curl (#1026) - Use same description for the "Download a URL to a file" example as for curl [...] | 2016-08-31T01:27:02 | [1c0471fc235b](https://github.com/tldr-pages/tldr/commit/1c0471fc235beff146d84c8a4914ae87b7e8294d)
[Larry850806](mailto:pudding850806@gmail.com) | Update wget.md | 2016-05-17T07:28:13 | [df82496c6cd3](https://github.com/tldr-pages/tldr/commit/df82496c6cd32524acd65ca8bff56ebd50667f7b)
[Larry850806](mailto:pudding850806@gmail.com) | Update wget.md | 2016-05-16T03:54:31 | [397e0587f31f](https://github.com/tldr-pages/tldr/commit/397e0587f31fa0a47ae856348680cc281e00d51f)
[Larry850806](mailto:pudding850806@gmail.com) | Update wget.md | 2016-05-15T15:52:14 | [73f945753dac](https://github.com/tldr-pages/tldr/commit/73f945753dacf07ccc8a92851ce2b4a50e4b760a)
[Larry850806](mailto:pudding850806@gmail.com) | Update wget.md | 2016-05-15T15:49:44 | [c170b92b3329](https://github.com/tldr-pages/tldr/commit/c170b92b33295c4e610b7ac3281d2e41fabdce92)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[lord63](mailto:lord63.j@gmail.com) | Fix lint for common | 2015-10-23T02:02:34 | [56a7cba6568f](https://github.com/tldr-pages/tldr/commit/56a7cba6568fcdaaeca2ddf0b80341cfc7de6285)
[rprieto](mailto:choicesmade@gmail.com) | Move pages back into a "pages" folder | 2014-03-04T13:28:29 | [f00bf64426a7](https://github.com/tldr-pages/tldr/commit/f00bf64426a792ee3aac792f9c0aec3f8b1eaa7d)

