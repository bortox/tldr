---
author: ['Kyle', 'sebastientinel', 'Emily Grace Seville', 'Agniva De Sarker', 'Vincent Yang', 'Guido Lena Cota']
date: 1644837703
title: "codesign, TLDR Pages"
description: "codesign, Create and manipulate code signatures for macOS."
categories: "osx"
---
> More information: <https://www.unix.com/man-page/osx/1/codesign/>.

- Sign an application with a certificate:

```bash
codesign --sign "My Company Name" path/to/App.app
```

- Verify the certificate of an application:

```bash
codesign --verify path/to/App.app
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | osx/*: update page (#7665) | 2022-02-14T12:21:43 | [692469016e62](https://github.com/tldr-pages/tldr/commit/692469016e62d4410ec92a8f29272e447046a0d2)
[Kyle](mailto:76597257+Gitleptune@users.noreply.github.com) | a*, g*, i*, osx[a*-i*]: add more information links (#6342) | 2021-08-23T21:33:24 | [0590a21917dc](https://github.com/tldr-pages/tldr/commit/0590a21917dc981d3cc64b8094b1cffa9d0a3b78)
[sebastientinel](mailto:sebastien.tinel@gmail.com) | multiple pages: Unify file path syntax to indicate a 'path to' (#4816) | 2020-10-28T18:19:43 | [1d32985f2f24](https://github.com/tldr-pages/tldr/commit/1d32985f2f24e5469dddc993dd7f354f79bfa128)
[Guido Lena Cota](mailto:guido.lenacota@kreuzwerker.de) | Bulk change: move double quotes outside tokens (#4431) | 2020-10-04T19:33:38 | [354d4b8748ee](https://github.com/tldr-pages/tldr/commit/354d4b8748ee58813dd6830ced7c3b11067255d7)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | codesign: remove direct 2nd person usage | 2017-10-15T22:11:43 | [797b45b8b71b](https://github.com/tldr-pages/tldr/commit/797b45b8b71b49881da2c59833efefdb76ed2aae)
[Vincent Yang](mailto:VincentYang2014@gmail.com) | codesign grammar updates | 2017-10-15T20:57:27 | [aac8ed5e6d32](https://github.com/tldr-pages/tldr/commit/aac8ed5e6d3250705744bdf3acd20962e3cc9260)
[Vincent Yang](mailto:VincentYang2014@gmail.com) | Added params for codesign | 2017-10-15T06:01:32 | [7de5a750d385](https://github.com/tldr-pages/tldr/commit/7de5a750d3859b2d198feb0fff2c09d06e0145fd)
[Vincent Yang](mailto:VincentYang2014@gmail.com) | Updated descriptions | 2017-10-08T08:56:25 | [9e16847bc2bd](https://github.com/tldr-pages/tldr/commit/9e16847bc2bdfa50738383799b3df3e763e7e51d)
[Vincent Yang](mailto:VincentYang2014@gmail.com) | remove space | 2017-10-06T23:51:12 | [60d13d2cf52b](https://github.com/tldr-pages/tldr/commit/60d13d2cf52b7285371e49e05e8163241580adbc)
[Vincent Yang](mailto:VincentYang2014@gmail.com) | Added codesign | 2017-10-06T23:48:32 | [8e71f13521f3](https://github.com/tldr-pages/tldr/commit/8e71f13521f3bec33ad68df9588d054363ece1fc)

