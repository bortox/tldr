---
author: ['Dario Vladović', 'Igor Shubovych', 'Guido Lena Cota', 'Agam Agarwal', 'Ruben Vereecken', 'Ivan Aracki', 'Romain Prieto', 'marchersimon']
date: 1617292466
title: "echo"
description: "echo, Print given arguments."
categories: "common"
---
> More information: <https://www.gnu.org/software/coreutils/echo>.

- Print a text message. Note: quotes are optional:

```bash
echo "Hello World"
```

- Print a message with environment variables:

```bash
echo "My path is $PATH"
```

- Print a message without the trailing newline:

```bash
echo -n "Hello World"
```

- Append a message to the file:

```bash
echo "Hello World" >> file.txt
```

- Enable interpretation of backslash escapes (special characters):

```bash
echo -e "Column 1\tColumn 2"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | echo: add link (#5606) | 2021-03-30T15:54:21 | [206703144d57](https://github.com/tldr-pages/tldr/commit/206703144d576491dbcf66be20770c47ebe329d3)
[Guido Lena Cota](mailto:guido.lenacota@kreuzwerker.de) | Bulk change: move double quotes outside tokens (#4431) | 2020-10-04T19:33:38 | [354d4b8748ee](https://github.com/tldr-pages/tldr/commit/354d4b8748ee58813dd6830ced7c3b11067255d7)
[Ivan Aracki](mailto:aracki.ivan@gmail.com) | echo: add one more example (#3122) | 2019-06-22T17:40:44 | [a6adec927f07](https://github.com/tldr-pages/tldr/commit/a6adec927f07aa3d9ce7a94918a65b87e1c5ebad)
[Agam Agarwal](mailto:agammaster@gmail.com) | echo: added -n, -e examples (#963) | 2016-07-21T15:52:49 | [87540fec499d](https://github.com/tldr-pages/tldr/commit/87540fec499d07d1a71d4b496e1e8dae01124bd0)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Romain Prieto](mailto:choicesmade@gmail.com) | echo: fix token syntax + 1 example per description | 2014-05-11T13:11:46 | [0bdf0da31885](https://github.com/tldr-pages/tldr/commit/0bdf0da31885a209bd0ed282294db793dc24b222)
[Igor Shubovych](mailto:igor.shubovych@gmail.com) | Pages: echo | 2014-05-11T12:20:51 | [1b0766942d01](https://github.com/tldr-pages/tldr/commit/1b0766942d014789b353392750ea311c4f83942a)

