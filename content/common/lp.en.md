---
author: ['Jonathan C. Dietrich', 'Ruben Vereecken', 'Igor Shubovych', 'lincc']
date: 1632422063
title: "lp, TLDR Pages"
description: "lp, Print files."
categories: "common"
---
> More information: <https://manned.org/lp>.

- Print the output of a command to the default printer (see `lpstat` command):

```bash
echo "test" | lp
```

- Print a file to the default printer:

```bash
lp path/to/filename
```

- Print a file to a named printer (see `lpstat` command):

```bash
lp -d printer_name path/to/filename
```

- Print N copies of file to default printer (replace N with desired number of copies):

```bash
lp -n N path/to/filename
```

- Print only certain pages to the default printer (print pages 1, 3-5, and 16):

```bash
lp -P 1,3-5,16 path/to/filename
```

- Resume printing a job:

```bash
lp -i job_id -H resume
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | common/l*: add more information link (#6577) | 2021-09-23T20:34:23 | [35d3601e388a](https://github.com/tldr-pages/tldr/commit/35d3601e388ad4b54affea092d6dd4f0a8be37d2)
[Jonathan C. Dietrich](mailto:jcdietrich@gmail.com) | lp: add resume a job example (#3176) | 2019-07-07T15:12:37 | [435b31ba36ce](https://github.com/tldr-pages/tldr/commit/435b31ba36ce0cd65296653420bbfa03f33e501c)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Igor Shubovych](mailto:igor.shubovych@gmail.com) | #321: add lp and lpstat commands (kudos to @Qtrain) | 2015-12-01T03:44:01 | [08b7e1c0cdda](https://github.com/tldr-pages/tldr/commit/08b7e1c0cdda3e3af4adee0d1735ba2fdf9def0a)

