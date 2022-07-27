---
author: ['Urs Braem', 'fuerbringer', 'Lucas Gabriel Schneider', 'pxgamer']
date: 1581188165
title: "htpasswd, TLDR Pages"
description: "htpasswd, Create and manage htpasswd files to protect web server directories using basic authentication."
categories: "common"
---
> More information: <https://httpd.apache.org/docs/current/programs/htpasswd.html>.

- Create/overwrite htpasswd file:

```bash
htpasswd -c path/to/file username
```

- Add user to htpasswd file or update existing user:

```bash
htpasswd path/to/file username
```

- Add user to htpasswd file in batch mode without an interactive password prompt (for script usage):

```bash
htpasswd -b path/to/file username password
```

- Delete user from htpasswd file:

```bash
htpasswd -D path/to/file username
```

- Verify user password:

```bash
htpasswd -v path/to/file username
```

- Display a string with username (plain text) and password (md5):

```bash
htpasswd -nbm username password
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:lucas.schneider@sap.com) | multiple pages: change user_name to username (#3841) | 2020-02-08T19:56:05 | [26e019b295f1](https://github.com/tldr-pages/tldr/commit/26e019b295f1782e6dd695b03108f061946327e8)
[Urs Braem](mailto:info@ursbraem.ch) | htpasswd: add direct generation of username/password (#3357) Co-authored-by: Zlatan Vasović <zlatanvasovic@gmail.com> | 2019-12-24T14:57:59 | [eaef0f2d4448](https://github.com/tldr-pages/tldr/commit/eaef0f2d444800c24558073d51aa4a187d7d7c1a)
[pxgamer](mailto:owzie123@gmail.com) | htpasswd: add link to homepage | 2019-06-07T23:58:59 | [f19c900253dd](https://github.com/tldr-pages/tldr/commit/f19c900253dda94c154de8b531035ce9db7319be)
[fuerbringer](mailto:severin@protonmail.ch) | Changed batch mode description. | 2016-11-13T14:59:25 | [aa6cb04e10ea](https://github.com/tldr-pages/tldr/commit/aa6cb04e10eac72e89a95dbb818cad888bc01e7b)
[fuerbringer](mailto:severin@protonmail.ch) | Changed file path tokens and batch mode description. | 2016-11-13T14:59:25 | [4f0a7b9a489a](https://github.com/tldr-pages/tldr/commit/4f0a7b9a489acee97b1ec4c8b9f10957c8a045ae)
[fuerbringer](mailto:severin@protonmail.ch) | htpasswd: add page | 2016-11-13T14:59:25 | [fc981c211680](https://github.com/tldr-pages/tldr/commit/fc981c2116801ca864afbee8291574509d4f465a)

