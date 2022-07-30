---
author: ['Abraham Raji', 'Patrice Denis', 'Reinhart Previano Koentjoro']
date: 1641608133
title: "apt"
description: "apt, ഡെബിയൻ അടിസ്ഥാനമാക്കിയുള്ള വിതരണങ്ങൾക്കായുള്ള പാക്കേജ് മാനേജുമെന്റ് യൂട്ടിലിറ്റി."
categories: "linux"
---
> ഉബുണ്ടു പതിപ്പുകളിൽ 16.04ലും അതിനുശേഷമുള്ളതിലും സംവേദനാത്മകമായി ഉപയോഗിക്കുമ്പോൾ `apt-get` പകരം വയ്ക്കാൻ ശുപാർശ ചെയ്യുന്നതു.

> കൂടുതൽ വിവരങ്ങൾ: <https://manpages.debian.org/latest/apt/apt.8.html>.

- ലഭ്യമായ പാക്കേജുകളുടെയും പതിപ്പുകളുടെയും പട്ടിക അപ്‌ഡേറ്റുചെയ്യുക (മറ്റ് `apt` കമാൻഡുകൾക്ക് മുമ്പ് ഇത് പ്രവർത്തിപ്പിക്കാൻ ശുപാർശ ചെയ്യുന്നു):

```bash
sudo apt update
```

- പാക്കേജിനായി തിരയുക:

```bash
apt search പാക്കേജ്
```

- ഒരു പാക്കേജിന്റെ വിവരങ്ങൾ കാണിക്കുക:

```bash
apt show പാക്കേജ്
```

- ഒരു പാക്കേജ് ഇൻസ്റ്റാൾ ചെയ്യുക, അല്ലെങ്കിൽ ലഭ്യമായ ഏറ്റവും പുതിയ പതിപ്പിലേക്ക് അപ്‌ഡേറ്റ് ചെയ്യുക:

```bash
sudo apt install പാക്കേജ്
```

- ഒരു പാക്കേജ് നീക്കംചെയ്യുക (പകരം `purge` ഉപയോഗിക്കുന്നത് അതിന്റെ കോൺഫിഗറേഷൻ ഫയലുകളും നീക്കംചെയ്യുന്നു):

```bash
sudo apt remove പാക്കേജ്
```

- ഇൻസ്റ്റാളുചെയ്‌ത എല്ലാ പാക്കേജുകളും ലഭ്യമായ ഏറ്റവും പുതിയ പതിപ്പുകളിലേക്ക് അപ്‌ഗ്രേഡുചെയ്യുക:

```bash
sudo apt upgrade
```

- എല്ലാ പാക്കേജുകളും കാണിക്കുക:

```bash
apt list
```

- ഇൻസ്റ്റാൾ ചെയ്ത പാക്കേജുകൾ കാണിക്കുക:

```bash
apt list --installed
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Reinhart Previano Koentjoro](mailto:reinhart_previano@yahoo.com) | apt: add backticks to apt-get (#7620) | 2022-01-08T03:15:33 | [e97d77689ab9](https://github.com/tldr-pages/tldr/commit/e97d77689ab99cfb2860768a9a50a0a65a4e03bd)
[Patrice Denis](mailto:patrice.denis@gmail.com) | apt-*: add more info links; apt-file: add regex search example (#5710) | 2021-04-17T15:26:03 | [ca8394dc52de](https://github.com/tldr-pages/tldr/commit/ca8394dc52def4e55971ce4049b20fa8839f464d)
[Abraham Raji](mailto:32333507+avronr@users.noreply.github.com) | apt: add Malayalam translation (#4562) | 2020-10-09T00:24:59 | [9093863c2a56](https://github.com/tldr-pages/tldr/commit/9093863c2a5665da39dd7bfcd20f0cb4782c9b9f)

