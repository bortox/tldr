---
author: ['Alex']
date: 1603128658
title: "crunch"
description: "crunch, Wordlist generator."
categories: "common"
---
> More information: <https://sourceforge.net/projects/crunch-wordlist/>.

- Output a list of words of length 1 to 3 with only lowercase characters:

```bash
crunch 1 3
```

- Output a list of hexadecimal words of length 8:

```bash
crunch 8 8 0123456789abcdef
```

- Output a list of all permutations of abc (lengths are not processed):

```bash
crunch 1 1 -p abc
```

- Output a list of all permutations of the given strings (lengths are not processed):

```bash
crunch 1 1 -p abc def ghi
```

- Output a list of words generated according to the given pattern and a maximum number of duplicate letters:

```bash
crunch 5 5 abcde123 -t @@@12 -d 2@
```

- Write a list of words in chunk files of a given size, starting with the given string:

```bash
crunch 3 5 -o START -b 10kb -s abc
```

- Write a list of words stopping with the given string and inverting the wordlist:

```bash
crunch 1 5 -o START -e abcde -i
```

- Write a list of words in compressed chunk files with a specified number of words:

```bash
crunch 1 5 -o START -c 1000 -z gzip|bzip2|lzma|7z
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Alex](mailto:alexandre.dhondt@gmail.com) | crunch: add page (#4719) | 2020-10-19T19:30:58 | [71fd0643e4f0](https://github.com/tldr-pages/tldr/commit/71fd0643e4f05458b27236d9ef6c577a6067835f)

