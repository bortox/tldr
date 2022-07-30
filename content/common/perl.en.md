---
author: ['Waldir Pimenta', 'Lucas Gabriel Schneider', 'Assem Attia', 'pxgamer', 'morrme', 'bl-ue', 'Zachary Sherwin', 'Shawn Allen']
date: 1651302593
title: "perl"
description: "perl, The Perl 5 language interpreter."
categories: "common"
---
> More information: <https://www.perl.org>.

- Parse and execute a Perl script:

```bash
perl script.pl
```

- Check syntax errors on a Perl script:

```bash
perl -c script.pl
```

- Parse and execute a Perl statement:

```bash
perl -e perl_statement
```

- Run a Perl script in debug mode, using `perldebug`:

```bash
perl -d script.pl
```

- Edit all file lines [i]n-place with a specific replacement [e]xpression and save a file with a new extension:

```bash
perl -p -i'.extension' -e 's/regular_expression/replacement/g' path/to/file
```

- Run a multi-line replacement [e]xpression on a file, and save the result in a specific file:

```bash
perl -p -e 's/foo\nbar/foobar/g' path/to/input_file > path/to/output_file
```

- Run a regular [e]xpression on stdin, printing matching [l]ines:

```bash
cat path/to/file | perl -n -l -e 'print if /regular_expression/'
```

- Run a regular [e]xpression on stdin, printing only the first capture group for each matching [l]ine:

```bash
cat path/to/file | perl -n -l -e 'print $1 if /before(regular_expression)after/'
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Shawn Allen](mailto:shawnbot@users.noreply.github.com) | perl: improve matching pattern example, arg consistency, etc. (#8043) * perl: improve matching pattern examples * perl: remove in- [...] | 2022-04-30T09:09:53 | [918891f3118b](https://github.com/tldr-pages/tldr/commit/918891f3118b43ad58873deb75f79577c727d37e)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | perl: minor tweaks to command descriptions (#3554) | 2019-11-12T09:50:23 | [caebe8505096](https://github.com/tldr-pages/tldr/commit/caebe850509654e0cb973033b91857d9be30817f)
[Zachary Sherwin](mailto:48960849+hello-woof@users.noreply.github.com) | perl: add PCRE one liner example (#3129) | 2019-09-24T15:00:09 | [ec2213a34a4e](https://github.com/tldr-pages/tldr/commit/ec2213a34a4ea27734311be403b2664fce782255)
[pxgamer](mailto:owzie123@gmail.com) | perl: add link to homepage | 2019-05-31T20:47:40 | [f2a8784ddefe](https://github.com/tldr-pages/tldr/commit/f2a8784ddefe9e15b5fb2b48005d3bdac283b965)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | perl: tweak the -0 example | 2017-05-22T16:17:03 | [efbf0cc51e00](https://github.com/tldr-pages/tldr/commit/efbf0cc51e0052a7f6674f022072f518dc6e2ff9)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | perl: swap -M example with -0, for multiline regex For completeness: the -0 option is actually used to specify the input record [...] | 2017-05-22T16:17:03 | [dc9547925fb1](https://github.com/tldr-pages/tldr/commit/dc9547925fb1221e73532e47cffe60829dddf092)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | perl: improve descriptions of -pie examples | 2017-04-26T11:32:58 | [c3146ede2a31](https://github.com/tldr-pages/tldr/commit/c3146ede2a313a80840d54910859df6c7e51043b)
[morrme](mailto:morrme@users.noreply.github.com) | perl: add pie example per issue #1239 | 2017-04-26T11:32:58 | [8b85207f357b](https://github.com/tldr-pages/tldr/commit/8b85207f357beb6c9ef0d2e14d85787b815386b0)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | perl: various minor tweaks - use generic names in the descriptions, since they can be directly matched to the corresponding tokens - [...] | 2016-11-05T20:17:40 | [1524aa95da61](https://github.com/tldr-pages/tldr/commit/1524aa95da61b5224f3602aecab5a9020ef463e5)
[Assem Attia](mailto:assem.m.ahmad@gmail.com) | perl: add page (#1142) | 2016-11-05T20:14:19 | [b9bb46e6de3c](https://github.com/tldr-pages/tldr/commit/b9bb46e6de3cb86e78087a192ca20e9a207fd084)

