---
author: ['Wolfgang Lutz', 'Waldir Pimenta', 'Dario Vladović', 'Angsuman Chakraborty', 'Daniel Senff', 'Ruben Vereecken', 'marchersimon']
date: 1617292466
title: "tr"
description: "tr, Translate characters: run replacements based on single characters and character sets."
categories: "common"
---
> More information: <https://www.gnu.org/software/coreutils/tr>.

- Replace all occurrences of a character in a file, and print the result:

```bash
tr find_character replace_character < filename
```

- Replace all occurrences of a character from another command's output:

```bash
echo text | tr find_character replace_character
```

- Map each character of the first set to the corresponding character of the second set:

```bash
tr 'abcd' 'jkmn' < filename
```

- Delete all occurrences of the specified set of characters from the input:

```bash
tr -d 'input_characters' < filename
```

- Compress a series of identical characters to a single character:

```bash
tr -s 'input_characters' < filename
```

- Translate the contents of a file to upper-case:

```bash
tr "[:lower:]" "[:upper:]" < filename
```

- Strip out non-printable characters from a file:

```bash
tr -cd "[:print:]" < filename
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | tr: add more information link (#5596) | 2021-03-30T15:46:31 | [2df3339d1d9a](https://github.com/tldr-pages/tldr/commit/2df3339d1d9ad017f9237710483a46190ae5c225)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | tr: improve page - Add source data to all examples - Add an example for piping from another command - Improve punctuation in main [...] | 2019-01-15T15:44:34 | [2ac288139075](https://github.com/tldr-pages/tldr/commit/2ac2881390758dc0463f3e4e3de78c5967bfb094)
[Angsuman Chakraborty](mailto:angsuman@taragana.com) | Corrected the example: Compress a series of identical characters to a single character The example wrongly used \n instead of [...] | 2017-11-26T11:39:41 | [fc6b0e4661ff](https://github.com/tldr-pages/tldr/commit/fc6b0e4661ffba84632525f1d9ddbd94b4101289)
[Wolfgang Lutz](mailto:WLBORg@gmx.de) | fix typos using misspell (#1374) | 2017-05-12T11:29:18 | [550ede5cfb90](https://github.com/tldr-pages/tldr/commit/550ede5cfb90cb772d1ecf27241b22e5086b024b)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Daniel Senff](mailto:mail@danielsenff.de) | common verb conjugation for all tr command descriptions | 2015-03-14T16:34:38 | [7f48d18e12cd](https://github.com/tldr-pages/tldr/commit/7f48d18e12cdc336cac7d8f398697a180016b23e)
[Daniel Senff](mailto:mail@danielsenff.de) | add more examples to tr These examples were suggested to add and are based from the tr-wikipedia article at [...] | 2015-03-14T12:05:19 | [70017a62004c](https://github.com/tldr-pages/tldr/commit/70017a62004c2c2440bda4f209e43e6ac23d6628)
[Daniel Senff](mailto:mail@danielsenff.de) | Create tr.md tr is a small utility for translating characters in text documents | 2015-03-12T09:41:54 | [c86216e2612b](https://github.com/tldr-pages/tldr/commit/c86216e2612ba236816a5210e50aaa27ef0cad0a)

