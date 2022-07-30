---
author: ['Tomasz Durda']
date: 1646741703
title: "fio"
description: "fio, Flexible I/O tester."
categories: "common"
---
> Tool that will spawn a number of threads or processes doing a particular type of I/O action.

> More information: <https://fio.readthedocs.io/en/latest/fio_doc.html>.

- Test random reads:

```bash
sudo fio --filename=path/to/file --direct=1 --rw=randread --bs=4k --ioengine=libaio --iodepth=256 --runtime=120 --numjobs=4 --time_based --group_reporting --name=job_name --eta-newline=1 --readonly
```

- Test sequential reads:

```bash
sudo fio --filename=path/to/file --direct=1 --rw=read --bs=4k --ioengine=libaio --iodepth=256 --runtime=120 --numjobs=4 --time_based --group_reporting --name=job_name --eta-newline=1 --readonly
```

- Test random read/write:

```bash
sudo fio --filename=path/to/file --size=500GB --direct=1 --rw=randrw --bs=4k --ioengine=libaio --iodepth=256 --runtime=120 --numjobs=4 --time_based --group_reporting --name=job_name --eta-newline=1
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Tomasz Durda](mailto:tomekdur@wp.pl) | fio: add page (#7829) | 2022-03-08T13:15:03 | [609b7d1a5229](https://github.com/tldr-pages/tldr/commit/609b7d1a52292f44ac3c4b5a7d0178618d8e6b97)

