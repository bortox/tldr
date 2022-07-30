---
author: ['Appledora', 'marchersimon']
date: 1659075216
title: "snap, TLDR Pages"
description: "snap, 'স্ন্যাপ' স্বয়ংসম্পূর্ণ সফটওয়্যার প্যাকেজসমুহ  পরিচালনার জন্য একটি টুল।"
categories: "linux"
---
> এটি ".deb" এর জন্য `apt` এর অনুরূপ।

> আরও তথ্য পাবেন: <https://manned.org/snap>.

- একটি প্যাকেজ অনুসন্ধান করুন:

```bash
snap find প্যাকেজের_নাম
```

- একটি প্যাকেজ ইনস্টল করুন:

```bash
snap install প্যাকেজের_নাম
```

- একটি প্যাকেজ আপডেট করুন:

```bash
snap refresh প্যাকেজের_নাম
```

- অন্য চ্যানেলে একটি প্যাকেজ আপডেট করুন (ট্র্যাক, রিস্ক বা ব্র্যাঞ্চ):

```bash
snap refresh প্যাকেজের_নাম --channel=চ্যানেল
```

- সমস্ত প্যাকেজ আপডেট করুন:

```bash
snap refresh
```

- ইনস্টল করা স্ন্যাপ সফটওয়্যার সম্পর্কে প্রাথমিক তথ্য প্রদর্শন করুন:

```bash
snap list
```

- একটি প্যাকেজ আনইনস্টল করুন:

```bash
snap remove প্যাকেজের_নাম
```

- সিস্টেমে সাম্প্রতিক স্ন্যাপ পরিবর্তনের জন্য পরীক্ষা করুন:

```bash
snap changes
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Sync more information links with all translations (#8256) | 2022-07-29T08:13:36 | [1f610a952ea0](https://github.com/tldr-pages/tldr/commit/1f610a952ea0d53e0a1bdbd1246ef81f24db2f3f)
[Appledora](mailto:nazia89@student.sust.edu) | snap: add Bengali translation (#6988) | 2021-10-19T11:56:04 | [421da6253b7c](https://github.com/tldr-pages/tldr/commit/421da6253b7c3c3dc55c6e9ffa9148d093f0bd30)

