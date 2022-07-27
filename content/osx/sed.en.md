---
author: ['Miroslav Čech', 'Waldir Pimenta', 'Cristobal Forno', 'Stefan Wessels Beljaars', 'Seth Falco', 'marchersimon']
date: 1629050349
title: "sed, TLDR Pages"
description: "sed, Edit text in a scriptable manner."
categories: "osx"
---
> More information: <https://ss64.com/osx/sed.html>.

- Replace the first occurrence of a string in a file, and print the result:

```bash
sed 's/find/replace/' filename
```

- Replace all occurrences of an extended regular expression in a file:

```bash
sed -E 's/regular_expression/replace/g' filename
```

- Replace all occurrences of a string [i]n a file, overwriting the file (i.e. in-place):

```bash
sed -i '' 's/find/replace/g' filename
```

- Replace only on lines matching the line pattern:

```bash
sed '/line_pattern/s/find/replace/' filename
```

- Print only text between n-th line till the next empty line:

```bash
sed -n 'line_number,/^$/p' filename
```

- Apply multiple find-replace expressions to a file:

```bash
sed -e 's/find/replace/' -e 's/find/replace/' filename
```

- Replace separator `/` by any other character not used in the find or replace patterns, e.g. `#`:

```bash
sed 's#find#replace#' filename
```

- [d]elete the line at the specific line number [i]n a file, overwriting the file:

```bash
sed -i '' 'line_numberd' filename
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | multiple pages: normalize `regular expression` instead of `regex`, `regexp` or `pattern` (#5830) | 2021-05-10T11:03:12 | [10728f1ab485](https://github.com/tldr-pages/tldr/commit/10728f1ab485957d66af3940a030b0fb77611fc0)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | osx/sed: add link (#5535) | 2021-03-30T11:00:13 | [dc0617c0623f](https://github.com/tldr-pages/tldr/commit/dc0617c0623fc0d1a798892a02a7f20c55a28f2b)
[Stefan Wessels Beljaars](mailto:stefanwb@gmail.com) | sed: fix faulty example and add remove line from file osx (#4781) | 2020-10-24T16:10:25 | [b9e393f602a5](https://github.com/tldr-pages/tldr/commit/b9e393f602a590500e8c34a5d9169b38c878dbdf)
[Cristobal Forno](mailto:cforno1@binghamton.edu) | sed: minor syntax fix (#3908) | 2020-03-18T22:23:45 | [32997ccf6b2b](https://github.com/tldr-pages/tldr/commit/32997ccf6b2b7aea552d7b4427793c3742b6c9f1)
[Miroslav Čech](mailto:miroslav.cech@gooddata.com) | sed: introduce print command in osx | 2018-08-14T19:27:04 | [93690e072355](https://github.com/tldr-pages/tldr/commit/93690e072355909a8e1a77dbd2fc3a40f24b54c2)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | sed.md: add input to the only example missing it (#992) * sed.md: add input to the only example missing it * osx/sed.md: add input to [...] | 2016-08-08T09:09:34 | [a1ceb9d1b6e1](https://github.com/tldr-pages/tldr/commit/a1ceb9d1b6e12f7b0b774c166e3e028d4fe11c64)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | sed: swap extended regex & line pattern examples | 2016-04-21T20:13:01 | [685b6ea8bd99](https://github.com/tldr-pages/tldr/commit/685b6ea8bd99e71d1c645e5b9bc374d490022776)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | sed: reword last example and add it to the osx version too | 2016-04-21T20:11:33 | [1c76b8ea7be0](https://github.com/tldr-pages/tldr/commit/1c76b8ea7be08498f82d44b049e78ca528173493)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | Add OSX version of sed -- see #281, #293 and #332 | 2016-03-21T11:22:03 | [474e589bfa87](https://github.com/tldr-pages/tldr/commit/474e589bfa873fcf56b4212d74f65dcc1de9ffcd)

