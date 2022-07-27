---
author: ['Leandro Ostera', 'Sadeed', 'Hayden Schiff', 'Guido Lena Cota', 'Lucas Gabriel Schneider']
date: 1633438245
title: "mmv, TLDR Pages"
description: "mmv, Move and rename files in bulk."
categories: "common"
---
> More information: <https://manned.org/mmv.1>.

- Rename all files with a certain extension to a different extension:

```bash
mmv "*.old_extension" "#1.new_extension"
```

- Copy `report6part4.txt` to `./french/rapport6partie4.txt` along with all similarly named files:

```bash
mmv -c "report*part*.txt" "./french/rapport#1partie#2.txt"
```

- Append all `.txt` files into one file:

```bash
mmv -a "*.txt" "all.txt"
```

- Convert dates in filenames from "M-D-Y" format to "D-M-Y" format:

```bash
mmv "[0-1][0-9]-[0-3][0-9]-[0-9][0-9][0-9][0-9].txt" "#3#4-#1#2-#5#6#7#8.txt"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Sadeed](mailto:sadeeedw@gmail.com) | mail, mailx, mesg, mmv, monop, most, mscore: add link (#6795) | 2021-10-05T14:50:45 | [696b11611fa5](https://github.com/tldr-pages/tldr/commit/696b11611fa5c0ebd61d71d470fc2cd34b700f08)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Guido Lena Cota](mailto:guido.lenacota@kreuzwerker.de) | Bulk change: move double quotes outside tokens (#4431) | 2020-10-04T19:33:38 | [354d4b8748ee](https://github.com/tldr-pages/tldr/commit/354d4b8748ee58813dd6830ced7c3b11067255d7)
[Leandro Ostera](mailto:leandro@ostera.io) | Embrace the arguments! | 2016-02-13T00:11:51 | [5f21c67ead37](https://github.com/tldr-pages/tldr/commit/5f21c67ead37289ef8e868ea43a3a7225efcad30)
[Hayden Schiff](mailto:oxguy3@gmail.com) | mmv: add page | 2016-01-22T00:42:37 | [b1bf59918d92](https://github.com/tldr-pages/tldr/commit/b1bf59918d926296ee7dcc3c2f43b6b33e0405b0)

