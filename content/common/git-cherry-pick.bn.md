---
author: ['Appledora']
date: 1634631935
title: "git cherry-pick, TLDR Pages"
description: "git cherry-pick, বিদ্যমান কমিট দ্বারা প্রবর্তিত পরিবর্তনগুলি বর্তমান ব্র্যাঞ্চে প্রয়োগ করুন।"
categories: "common"
---
> অন্য ব্র্যাঞ্চে পরিবর্তনগুলি প্রয়োগ করতে, প্রথমে পছন্দসই ব্র্যাঞ্চে স্যুইচ করতে `git checkout` ব্যবহার করুন।

> আরও তথ্য পাবেন: <https://git-scm.com/docs/git-cherry-pick>.

- বর্তমান ব্র্যাঞ্চে কমিট করুন:

```bash
git cherry-pick কমিট
```

- বর্তমান ব্র্যাঞ্চে বিভিন্ন ধরনের কমিট করুন (এছাড়াও দেখুন 'git rebase --onto`):

```bash
git cherry-pick শুরুর_কমিট~..শেষের_কমিট
```

- বর্তমান ব্র্যাঞ্চে  একাধিক (অ-ক্রমিক) কমিট  করুন:

```bash
git cherry-pick কমিট_১ কমিট_২
```

- কমিট তৈরি না করেই ওয়ার্কিং ডিরেক্টরিতে কমিটের পরিবর্তন যোগ করুন:

```bash
git cherry-pick -n কমিট
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Appledora](mailto:nazia89@student.sust.edu) | apt, cd, cmd, ditto, git-cherry-pick, snoop: add Bengali translation (#6989) | 2021-10-19T10:25:35 | [529589f9f074](https://github.com/tldr-pages/tldr/commit/529589f9f074031156a66e752ed5dcb86701592a)

