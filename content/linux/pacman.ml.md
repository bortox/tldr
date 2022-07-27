---
author: ['Axel Navarro', 'Govind V Shenoy', 'Seth Falco', 'marchersimon']
date: 1648358715
title: "pacman, TLDR Pages"
description: "pacman, ആർച്ച് ലിന്ക്സിന്റെ പാക്കേജ് മാനേജുമെന്റ് യൂട്ടിലിറ്റി."
categories: "linux"
---
> കൂടുതൽ വിവരങ്ങൾ: <https://man.archlinux.org/man/pacman.8>.

- ഇൻസ്റ്റാൾ ചെയ്‌ത എല്ലാ പാക്കേജും അപ്‌ഡേറ്റു ചെയ്യുക:

```bash
sudo pacman --sync --refresh --sysupgrade
```

- പുതിയ പാക്കേജ് ഇൻസ്റ്റാൾ ചെയ്യുക:

```bash
sudo pacman --sync പാക്കേജ്
```

- ഒരു പാക്കേജും അത് ആശ്രയിക്കുന്ന മറ്റ് പാക്കേജുകളെയും കളയുക:

```bash
sudo pacman --remove --recursive പാക്കേജ്
```

- പാക്കേജ് ഡാറ്റാബേസിൽ ഒരു സൂചകപദം അല്ലെങ്കിൽ റെഗുലർ എക്സ്പ്രെഷൻ വെച്ച് തിരയുക:

```bash
pacman --sync --search "സെർച്ച് പാറ്റേൺ"
```

- ഇൻസ്റ്റാൾ ചെയ്‌ത എല്ലാ പാക്കേജുകളും അതിന്റെ പതിപ്പും കാണിക്കുക:

```bash
pacman --query
```

- നേരെ ഇൻസ്റ്റാൾ ചെയ്ത പാക്കേജ്‌സ് മാത്റം കാണിക്കുക:

```bash
pacman --query --explicit
```

- ഏത് പാക്കേജാണ് ഒരു ഫയലിന്റെ ഉടമ എന്ന് കണ്ടുപിടിക്കാൻ:

```bash
pacman --query --owns ഫയലിന്റെ പേര്
```

- പാക്കേജ് ക്യാഷ് കാലിയാക്കി സ്റ്റോറേജ്‌ മുക്തമാക്കുക:

```bash
sudo pacman --sync --clean --clean
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: normalize colons (#7913) | 2022-03-27T07:25:15 | [27ff55fc2eea](https://github.com/tldr-pages/tldr/commit/27ff55fc2eea445eb5216c3b1d934960539fc024)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | pacman: add sudo and use long options (#7132) | 2021-10-25T04:10:33 | [c9b534415099](https://github.com/tldr-pages/tldr/commit/c9b534415099cd2931eaf120938f201240c521a8)
[Axel Navarro](mailto:navarroaxel@gmail.com) | pacman: add more information link (#5146) | 2021-01-19T15:40:16 | [dbb0e9ef9767](https://github.com/tldr-pages/tldr/commit/dbb0e9ef97671aff87d987e2e67dce8f19d6668a)
[Govind V Shenoy](mailto:govindvshenoy@gmail.com) | pacman: add Malayalam translation (#4617) | 2020-10-11T06:54:32 | [1fb08e57a5b4](https://github.com/tldr-pages/tldr/commit/1fb08e57a5b4e8bf08a8661e19712cd358dc7723)

