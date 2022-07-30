---
author: ['jspickard', 'Agno94']
date: 1603970505
title: "ddrescue"
description: "ddrescue, Data recovery tool that reads data from damaged block devices."
categories: "linux"
---
> More information: <https://www.gnu.org/software/ddrescue/>.

- Take an image of a device, creating a log file:

```bash
sudo ddrescue /dev/sdb path/to/image.dd path/to/log.txt
```

- Clone Disk A to Disk B, creating a log file:

```bash
sudo ddrescue --force --no-scrape /dev/sdX /dev/sdY path/to/log.txt
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Agno94](mailto:agnophi@gmail.com) | badblocks, ddrescue, fdisk, fsck, ioping, smartctl, wipefs: change /dev/sda into /dev/sdX (#4861) | 2020-10-29T12:21:45 | [c312c50b9906](https://github.com/tldr-pages/tldr/commit/c312c50b99062c4dca949685ddc31385b179b7d5)
[jspickard](mailto:jsp.and.dmm@gmail.com) | photorec, ddrescue: add page (#3625) | 2019-12-06T14:56:04 | [59185a7ec97d](https://github.com/tldr-pages/tldr/commit/59185a7ec97d6fc1e5698202ae8faa2390f0e21b)

