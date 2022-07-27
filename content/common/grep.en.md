---
author: ['André König', 'Rahul Kavale', 'Abreto Fu', 'Waldir Pimenta', 'lord63', 'thalesmello', 'Mgs. M. Rizqi Fadhlurrahman', 'Agniva De Sarker', 'Ruben Vereecken', 'Rónán Ó\xa0Cuinn', 'Ahmet Kun', 'Szczepan Zalega', 'Ayakashi', 'Antonio', 'rprieto', 'Henrikh Kantuni', 'bl-ue', 'marchersimon']
date: 1652466360
title: "grep, TLDR Pages"
description: "grep, Find patterns in files using regular expressions."
categories: "common"
---
> More information: <https://www.gnu.org/software/grep/manual/grep.html>.

- Search for a pattern within a file:

```bash
grep "search_pattern" path/to/file
```

- Search for an exact string (disables regular expressions):

```bash
grep --fixed-strings "exact_string" path/to/file
```

- Search for a pattern in all files recursively in a directory, showing line numbers of matches, ignoring binary files:

```bash
grep --recursive --line-number --binary-files=without-match "search_pattern" path/to/directory
```

- Use extended regular expressions (supports `?`, `+`, `{}`, `()` and `|`), in case-insensitive mode:

```bash
grep --extended-regexp --ignore-case "search_pattern" path/to/file
```

- Print 3 lines of context around, before, or after each match:

```bash
grep --context|before-context|after-context=3 "search_pattern" path/to/file
```

- Print file name and line number for each match with color output:

```bash
grep --with-filename --line-number --color=always "search_pattern" path/to/file
```

- Search for lines matching a pattern, printing only the matched text:

```bash
grep --only-matching "search_pattern" path/to/file
```

- Search stdin for lines that do not match a pattern:

```bash
cat path/to/file | grep --invert-match "search_pattern"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Abreto Fu](mailto:m@abreto.net) | Add an example for grep with color output (#8087) | 2022-05-13T20:26:00 | [69434ed5e8e4](https://github.com/tldr-pages/tldr/commit/69434ed5e8e4a7895c28eb656f83e9a1368989b0)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | grep: edit link (#5782) | 2021-04-18T00:08:17 | [d934ae39644f](https://github.com/tldr-pages/tldr/commit/d934ae39644f2ce38f61505d40642a742e9f4c10)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | grep: refresh (#5218) | 2021-03-28T16:22:29 | [e871d01c6f35](https://github.com/tldr-pages/tldr/commit/e871d01c6f35104c3b3ee5b1f2abaccacf6c090b)
[Henrikh Kantuni](mailto:henrikh.kantuni@gmail.com) | grep: -v for in[v]ert (#5216) | 2021-02-02T13:44:00 | [4132aea569f1](https://github.com/tldr-pages/tldr/commit/4132aea569f124fcf5e2856b277aa4d3b14ed4b1)
[Mgs. M. Rizqi Fadhlurrahman](mailto:rizqirizqi23@gmail.com) | grep: add line numbers on search (#4599) | 2020-10-10T21:46:14 | [08216c539780](https://github.com/tldr-pages/tldr/commit/08216c539780673bf281b2ca713b5531d7d31a71)
[Szczepan Zalega](mailto:szszszsz@users.noreply.github.com) | grep: clarify that regexp is used by default grep searches for regexp by default on Linux, and the '-F' switch is required for the [...] | 2020-08-16T17:41:58 | [8d8f4c61c6d1](https://github.com/tldr-pages/tldr/commit/8d8f4c61c6d1e41ecf451ff68e27e3f00d7a85f5)
[Rónán Ó Cuinn](mailto:rocuinn@gmail.com) | grep: include searching recursively through symlinks (#2118) | 2018-05-22T19:10:21 | [c1ee7e5851bb](https://github.com/tldr-pages/tldr/commit/c1ee7e5851bbfd11bbb43f2bd45ba85ed1238358)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | grep: remove 2 examples (#1750) * grep: remove 2 examples Make the page conform to our maximum limit of 8 examples Fixes #1695 * [...] | 2017-12-07T04:23:40 | [3b0383d075d8](https://github.com/tldr-pages/tldr/commit/3b0383d075d815d617e893521dd4987070544e96)
[Rahul Kavale](mailto:kavale.rahul@gmail.com) | grep: add flags for lines before and after the match (#1020) | 2016-08-29T01:43:14 | [bf955d43e6f4](https://github.com/tldr-pages/tldr/commit/bf955d43e6f4c4076090a4f43c666b9b8fc5e31d)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | Apply the 'path/to/item' convention uniformly (#947) | 2016-07-13T10:53:22 | [fa8b2d8f92ab](https://github.com/tldr-pages/tldr/commit/fa8b2d8f92abfcbea46036b8a30c129ac53abdcb)
[thalesmello](mailto:thalesmello@gmail.com) | Fix extended regular expressions By default, grep already uses regular expressions when searching. The example `grep -e {{^regex$}} [...] | 2016-07-04T22:40:04 | [0579b0993cdb](https://github.com/tldr-pages/tldr/commit/0579b0993cdb95c069d95c48d5983aadeb21a1a0)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | grep: simplify -l example to match the others | 2016-06-24T11:39:17 | [385a89558e6b](https://github.com/tldr-pages/tldr/commit/385a89558e6b9d2969144dbe79497899541aa0df)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | grep.md: "something" → "search_string"; -r → -rI | 2016-06-23T19:50:38 | [a2b596861d3d](https://github.com/tldr-pages/tldr/commit/a2b596861d3db7763245d21f5c768c802108b28d)
[Ayakashi](mailto:gwanmax@gmail.com) | grep.md: add -l example (#913) | 2016-06-21T09:11:27 | [777305c630b4](https://github.com/tldr-pages/tldr/commit/777305c630b47205cf496ca691b368770b26abc1)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | make extended regex character list more readable | 2016-04-22T15:23:06 | [4fb0b58900aa](https://github.com/tldr-pages/tldr/commit/4fb0b58900aaeddb899160df2bdc2d0d9c048fdd)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | various tweaks to grep - use "case-insensitive" in the description of the -i option to make the initialism clear - use path/to/file [...] | 2016-04-22T13:24:24 | [7782d9282057](https://github.com/tldr-pages/tldr/commit/7782d9282057b9990679d4a2475ed56f50bb2061)
[Ahmet Kun](mailto:ahmetkun@gmail.com) | grep: add -i option | 2016-01-27T23:12:10 | [798ea018a09a](https://github.com/tldr-pages/tldr/commit/798ea018a09a1847cb84d540d381641873f87ac1)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Antonio](mailto:antoniom13) | grep: add line number | 2016-01-05T06:30:21 | [b0adce01cbd1](https://github.com/tldr-pages/tldr/commit/b0adce01cbd1813b23fb4bee63b86a146df93ca0)
[lord63](mailto:lord63.j@gmail.com) | Fix lint for common | 2015-10-23T02:02:34 | [56a7cba6568f](https://github.com/tldr-pages/tldr/commit/56a7cba6568fcdaaeca2ddf0b80341cfc7de6285)
[André König](mailto:andre.koenig@posteo.de) | Fixed token syntax. | 2014-07-27T14:10:52 | [457e6483110f](https://github.com/tldr-pages/tldr/commit/457e6483110fd651c787797b8a084931743cf8f4)
[André König](mailto:andre.koenig@posteo.de) | Added invert match parameter. | 2014-07-27T10:23:56 | [6875834b7900](https://github.com/tldr-pages/tldr/commit/6875834b79007b926d950cc90813f40b416c83e3)
[rprieto](mailto:choicesmade@gmail.com) | Move pages back into a "pages" folder | 2014-03-04T13:28:29 | [f00bf64426a7](https://github.com/tldr-pages/tldr/commit/f00bf64426a792ee3aac792f9c0aec3f8b1eaa7d)

