---
author: ['Igor Shubovych', 'Eric Nielsen', 'Nicolas Kosinski', 'Max Beier', 'James Carlos', 'Bob Strecansky', 'Ruben Vereecken', 'Waldir Pimenta', 'jcherqui', 'Maks Makrovets', 'Zhou Fangyi', 'rprieto', 'pxgamer', 'Seth Falco', 'lord63', 'Jacob Clark', 'Al Berez', 'Tomasz Janiszewski', 'morrme', 'Florent Guilleux', 'bl-ue']
date: 1636068940
title: "curl"
description: "curl, Transfers data from or to a server."
categories: "common"
---
> Supports most protocols, including HTTP, FTP, and POP3.

> More information: <https://curl.se>.

- Download the contents of a URL to a file:

```bash
curl http://example.com --output filename
```

- Download a file, saving the output under the filename indicated by the URL:

```bash
curl --remote-name http://example.com/filename
```

- Download a file, following location redirects, and automatically continuing (resuming) a previous file transfer and return an error on server error:

```bash
curl --fail --remote-name --location --continue-at - http://example.com/filename
```

- Send form-encoded data (POST request of type `application/x-www-form-urlencoded`). Use `--data @file_name` or `--data @'-'` to read from STDIN:

```bash
curl --data 'name=bob' http://example.com/form
```

- Send a request with an extra header, using a custom HTTP method:

```bash
curl --header 'X-My-Header: 123' --request PUT http://example.com
```

- Send data in JSON format, specifying the appropriate content-type header:

```bash
curl --data '{"name":"bob"}' --header 'Content-Type: application/json' http://example.com/users/1234
```

- Pass a username and password for server authentication:

```bash
curl --user myusername:mypassword http://example.com
```

- Pass client certificate and key for a resource, skipping certificate validation:

```bash
curl --cert client.pem --key key.pem --insecure https://example.com
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Tomasz Janiszewski](mailto:janiszt@gmail.com) | curl: add --fail in example (#6630) | 2021-11-05T00:35:40 | [a51f7f6ce16b](https://github.com/tldr-pages/tldr/commit/a51f7f6ce16ba0b108c15d803cab46d1253067af)
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Nicolas Kosinski](mailto:nicokosi@yahoo.com) | curl: use long arguments (#5872) | 2021-05-04T11:37:07 | [69f02b651045](https://github.com/tldr-pages/tldr/commit/69f02b65104530e9f5d1d32a9528f2d3803050e0)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | curl: update to new 'more information' link (#5254) | 2021-02-07T21:27:41 | [ca9ba675cea1](https://github.com/tldr-pages/tldr/commit/ca9ba675cea1e8accb6121c8c52c4bb273df5163)
[Al Berez](mailto:a-b@users.noreply.github.com) | curl: explain -d example (#4183) | 2020-07-21T22:27:14 | [2e9c71731b3b](https://github.com/tldr-pages/tldr/commit/2e9c71731b3b6b35eccabbcef155edb64c83637c)
[pxgamer](mailto:owzie123@gmail.com) | curl: add link to homepage | 2019-06-09T18:53:49 | [4a8e8d036367](https://github.com/tldr-pages/tldr/commit/4a8e8d036367fc0027e5ec4c97bd9f03a5e29b76)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | curl: remove -I from auth example (fixes #1406) (#1417) (also, minor tweaks to some of the descriptions) | 2017-06-26T12:13:01 | [04fad240fe31](https://github.com/tldr-pages/tldr/commit/04fad240fe3109fb63674337dfe71f036c2b8dad)
[Zhou Fangyi](mailto:thomas.zhoufangyi@icloud.com) | curl: add separate entry for header & HTTP method; clarify entry for JSON (#1396) | 2017-06-06T09:23:00 | [5a17e687298b](https://github.com/tldr-pages/tldr/commit/5a17e687298b3098b18adfaaea8575d4b188fa15)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | curl: tweak desc of last example, per code review | 2017-04-19T20:30:33 | [01a9717bc9e2](https://github.com/tldr-pages/tldr/commit/01a9717bc9e2f030f1af90a2663db08b6108e3a9)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | curl: remove secure/insecure ambiguity | 2017-04-19T20:30:33 | [e6a54d891a1c](https://github.com/tldr-pages/tldr/commit/e6a54d891a1cf631a9f603b9f934cc0e73f284c9)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | curl: spell out the --insecure option | 2017-04-19T20:30:33 | [b051c298d02d](https://github.com/tldr-pages/tldr/commit/b051c298d02d633fc8944680a0119d1cce9ca123)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | curl: simplify last example (#1246) | 2017-04-19T20:30:33 | [3acc0d64b892](https://github.com/tldr-pages/tldr/commit/3acc0d64b892e625af347fcdb5efed073d64dd9d)
[morrme](mailto:morrme@users.noreply.github.com) | curl: improve last example per issue #1246 (#1326) | 2017-04-15T10:49:12 | [b69c14b4049b](https://github.com/tldr-pages/tldr/commit/b69c14b4049be784c5e4c6e540d9eed51b80aabd)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | curl: minor punctuation fix | 2017-02-02T12:35:43 | [b8dd048a93b4](https://github.com/tldr-pages/tldr/commit/b8dd048a93b431ea1671b0e6797c1c926b231ada)
[jcherqui](mailto:jcherqui@users.noreply.github.com) | curl: add -I option to the -u example (#1240) | 2017-01-15T16:47:30 | [672878abd0ba](https://github.com/tldr-pages/tldr/commit/672878abd0babc310318c103cf1faccc7e6cc9a1)
[Eric Nielsen](mailto:eric@amalgamar.com.br) | curl: Add more download and rewrite data examples (#1023) - Download: first example introduces `-o`, second one introduces `-O`, third [...] | 2016-08-31T20:33:33 | [e0d884efeba0](https://github.com/tldr-pages/tldr/commit/e0d884efeba0c041eec21ac40c1869f9e343f716)
[Max Beier](mailto:beierm@htw-berlin.de) | curl: hyphen instead of en dash (#857) | 2016-04-26T19:28:44 | [49c7b1b3423e](https://github.com/tldr-pages/tldr/commit/49c7b1b3423e216d8a5b123213c657c533782def)
[Jacob Clark](mailto:jacob.jh.clark@googlemail.com) | Client certificate in cUrl example | 2016-01-28T13:12:55 | [fae986d625ee](https://github.com/tldr-pages/tldr/commit/fae986d625ee1ad29e9daf8536c6bc72afd447fe)
[Bob Strecansky](mailto:bob.strecansky@gmail.com) | Update curl.md Only including the HEAD change | 2016-01-23T00:33:32 | [a5c853137ac8](https://github.com/tldr-pages/tldr/commit/a5c853137ac8eff1144d1520cdc44936ffe5ca6c)
[Bob Strecansky](mailto:bob.strecansky@gmail.com) | Update curl.md | 2016-01-19T19:17:03 | [1770008a2e44](https://github.com/tldr-pages/tldr/commit/1770008a2e44f2bc8347450e35a9cd04fcbd6dc3)
[Bob Strecansky](mailto:bob.strecansky@gmail.com) | Update curl.md Fixing Syntax to pass CI | 2016-01-19T19:16:54 | [e3f51a7aa571](https://github.com/tldr-pages/tldr/commit/e3f51a7aa571c6628ef8230f2cc4b397965dfdf8)
[Bob Strecansky](mailto:bob.strecansky@gmail.com) | Update curl.md | 2016-01-19T19:14:49 | [96fcae692bed](https://github.com/tldr-pages/tldr/commit/96fcae692bed39b23315a26503780f49783549e4)
[Bob Strecansky](mailto:bob.strecansky@gmail.com) | Update curl.md | 2016-01-19T19:13:41 | [a129e7c02e78](https://github.com/tldr-pages/tldr/commit/a129e7c02e7804510df68d2a9f780bb2c1d42028)
[Bob Strecansky](mailto:bstrecansky@rsglab.com) | -H instead of --head for cURL, adding verbose output | 2016-01-19T19:09:42 | [982fcfce4a8c](https://github.com/tldr-pages/tldr/commit/982fcfce4a8c272b34ec925a9eacd9eaf46a56c1)
[Igor Shubovych](mailto:igor.shubovych@gmail.com) | Merge branch 'curl-header' of git://github.com/jamescarlos/tldr into jamescarlos-curl-header | 2016-01-12T20:33:40 | [4b9e574df8a5](https://github.com/tldr-pages/tldr/commit/4b9e574df8a5a4b786f09178b9e62674a30a4b96)
[James Carlos](mailto:james@jamescarlos.com) | curl: add --header example | 2016-01-12T20:24:22 | [b38813ca3f83](https://github.com/tldr-pages/tldr/commit/b38813ca3f8345bb28f3bd85b5c5885c746764d9)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Maks Makrovets](mailto:maks.markovets@gmail.com) | curl: fix example according to style guide. | 2016-01-06T12:08:39 | [16d9553b6c5d](https://github.com/tldr-pages/tldr/commit/16d9553b6c5d91ad0a707a34e81a384775c7cef2)
[lord63](mailto:lord63.j@gmail.com) | Fix lint for common | 2015-10-23T02:02:34 | [56a7cba6568f](https://github.com/tldr-pages/tldr/commit/56a7cba6568fcdaaeca2ddf0b80341cfc7de6285)
[Florent Guilleux](mailto:florent2@gmail.com) | Add user password -u option to Curl | 2014-03-11T16:01:45 | [01965fd3cfea](https://github.com/tldr-pages/tldr/commit/01965fd3cfea66c71c728696793a42d1204feaa2)
[rprieto](mailto:choicesmade@gmail.com) | Move pages back into a "pages" folder | 2014-03-04T13:28:29 | [f00bf64426a7](https://github.com/tldr-pages/tldr/commit/f00bf64426a792ee3aac792f9c0aec3f8b1eaa7d)

