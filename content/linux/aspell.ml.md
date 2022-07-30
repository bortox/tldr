---
author: ['San Baby Francis']
date: 1634418184
title: "aspell"
description: "aspell, ഒരു ഇന്ററാക്ടിവ് സ്പെൽ ചെക്കർ."
categories: "linux"
---
> കൂടുതൽ വിവരങ്ങൾ: <http://aspell.net/>.

- ഒരു ഫയലിലെ തെറ്റായ പദങ്ങൾ കണ്ടെത്തുവാൻ:

```bash
aspell check ഫയലിന്റെ/പാത്/
```

- സ്റ്റാൻഡേഡ് ഇൻപുറ്റിൽ നിന്ന് തെറ്റായ പദങ്ങൾ കണ്ടെത്തുവാൻ:

```bash
cat ഫയൽ | aspell list
```

- പദശുദ്ധി കണ്ടെത്താൻ ഉപയോഗിക്കാവുന്ന ഭാഷാ-നിഘണ്ടുകൾ കാണുവാൻ:

```bash
aspell dicts
```

- മറ്റൊരു ഭാഷയുടെ പദശുദ്ധി കാണുവാൻ (ISO 639 ഭാഷാ-കോഡ് അനുസൃതം):

```bash
aspell --lang=cs
```

- പേഴ്സണൽ ലിസ്റ്റിൽ ഇല്ലാത്തതും സ്റ്റാൻഡേഡ് ഇൻപുറ്റിൽ ഉള്ളതുമായ തെറ്റുകൾ കാണുവാൻ:

```bash
cat ഫയൽ | aspell --personal=പേഴ്സണൽ-വേർഡ്-ലിസ്റ്റ്.pws ലിസ്റ്റ്
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[San Baby Francis](mailto:san.baby.francis123@gmail.com) | aspell, kwrite: add Malayalam translation (#6957) | 2021-10-16T23:03:04 | [c6c382cf676c](https://github.com/tldr-pages/tldr/commit/c6c382cf676c1673af432a67dccccf3a2b1d0c3c)

