---
author: ['Joshua Shanks', 'Agniva De Sarker', 'Jacek Wielemborek']
date: 1633557112
title: "pv, TLDR Pages"
description: "pv, Monitor the progress of data through a pipe."
categories: "common"
---
> More information: <https://manned.org/pv>.

- Print the contents of the file and display a progress bar:

```bash
pv file
```

- Measure the speed and amount of data flow between pipes (`-s` is optional):

```bash
command1 | pv -s expected_amount_of_data_for_eta | command2
```

- Filter a file, see both progress and amount of output data:

```bash
pv -cN in big_text_file | grep pattern | pv -cN out > filtered_file
```

- Attach to an already running process and see its file reading progress:

```bash
pv -d PID
```

- Read an erroneous file, skip errors as `dd conv=sync,noerror` would:

```bash
pv -EE path/to/faulty_media > image.img
```

- Stop reading after reading specified amount of data, rate limit to 1K/s:

```bash
pv -L 1K -S maximum_file_size_to_be_read
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Joshua Shanks](mailto:jjshanks@gmail.com) | ps, pv, pygmentize, quota, rabin2: add link (#6830) | 2021-10-06T23:51:52 | [52b9aaf74c57](https://github.com/tldr-pages/tldr/commit/52b9aaf74c571d0ee04b6f2986e09fff22ba7256)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | Apply the 'path/to/item' convention uniformly (#947) | 2016-07-13T10:53:22 | [fa8b2d8f92ab](https://github.com/tldr-pages/tldr/commit/fa8b2d8f92abfcbea46036b8a30c129ac53abdcb)
[Jacek Wielemborek](mailto:d33tah@gmail.com) | Add pv.md. | 2016-01-28T18:44:01 | [1bc96c237d24](https://github.com/tldr-pages/tldr/commit/1bc96c237d24d8388a2697eb447ce6413b871c1e)

