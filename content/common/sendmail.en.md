---
author: ['kalebo', 'Agniva De Sarker', 'Lucas Gabriel Schneider', 'bl-ue', 'Dylan Rees', 'Marco Bonelli', 'Juri']
date: 1634444636
title: "sendmail"
description: "sendmail, Send email from the command-line."
categories: "common"
---
> More information: <https://manned.org/sendmail>.

- Send a message with the content of `message.txt` to the mail directory of local user `username`:

```bash
sendmail username < message.txt
```

- Send an email from you@yourdomain.com (assuming the mail server is configured for this) to test@gmail.com containing the message in `message.txt`:

```bash
sendmail -f you@yourdomain.com test@gmail.com < message.txt
```

- Send an email from you@yourdomain.com (assuming the mail server is configured for this) to test@gmail.com containing the file `file.zip`:

```bash
sendmail -f you@yourdomain.com test@gmail.com < file.zip
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Juri](mailto:juri.dispan@posteo.net) | meshlabserver, nkf, obs, pax, pdfimages, pinky, pssh, s, sd, sendmail, sftp: add link (#6971) | 2021-10-17T06:23:56 | [977d4212d52c](https://github.com/tldr-pages/tldr/commit/977d4212d52c031de053f549d819b8b0e18ce184)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Lucas Gabriel Schneider](mailto:lucas.schneider@sap.com) | multiple pages: change user_name to username (#3841) | 2020-02-08T19:56:05 | [26e019b295f1](https://github.com/tldr-pages/tldr/commit/26e019b295f1782e6dd695b03108f061946327e8)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | Refactor: change "folder" to "directory" where needed. This commit fixes every instance in which the word "folder" is incorrectly used [...] | 2019-02-13T16:21:04 | [2599a6de483a](https://github.com/tldr-pages/tldr/commit/2599a6de483a70601ab17b29e0f18a5a8bdcaa12)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | Adding tokens to variables | 2017-10-17T06:04:58 | [3ff22d2260f1](https://github.com/tldr-pages/tldr/commit/3ff22d2260f184e4fb6410daa295b05fc290c967)
[kalebo](mailto:kaleb.olson@gmail.com) | Corrected inaccuracy | 2017-10-17T06:04:58 | [fcdd190c3afe](https://github.com/tldr-pages/tldr/commit/fcdd190c3afe611595d1be965fa08a18ce7bf4e6)
[Dylan Rees](mailto:dylanrees@protonmail.ch) | Create sendmail.md (#906) | 2016-06-21T00:56:54 | [40223d8eef03](https://github.com/tldr-pages/tldr/commit/40223d8eef034508bf2a96bdccd7c3afb0a1a703)

