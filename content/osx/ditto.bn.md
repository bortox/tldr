---
author: ['Appledora']
date: 1634631935
title: "ditto, TLDR Pages"
description: "ditto, ফাইল এবং ডিরেক্টরি কপি করুন।"
categories: "osx"
---
> আরও তথ্য পাবেন: <https://ss64.com/osx/ditto.html>.

- সোর্স ডিরেক্টরির বিষয়বস্তু দিয়ে  গন্তব্য ডিরেক্টরির বিষয়বস্তু ওভাররাইট করুন:

```bash
ditto সোর্স/এর/পথ গন্তব্য/এর/পথ
```

- কপি করা প্রতিটি ফাইলের জন্য টার্মিনাল উইন্ডোতে একটি লাইন প্রিন্ট করুন:

```bash
ditto -V সোর্স/এর/পথ গন্তব্য/এর/পথ
```

- মূল ফাইল এর পারমিশন বজায় রেখে একটি প্রদত্ত ফাইল বা ডিরেক্টরি কপি করুন:

```bash
ditto -rsrc সোর্স/এর/পথ গন্তব্য/এর/পথ
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Appledora](mailto:nazia89@student.sust.edu) | apt, cd, cmd, ditto, git-cherry-pick, snoop: add Bengali translation (#6989) | 2021-10-19T10:25:35 | [529589f9f074](https://github.com/tldr-pages/tldr/commit/529589f9f074031156a66e752ed5dcb86701592a)

