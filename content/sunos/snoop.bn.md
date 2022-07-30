---
author: ['Appledora', 'Seth Falco']
date: 1648358715
title: "snoop"
description: "snoop, নেটওয়ার্ক প্যাকেট স্নিফার।"
categories: "sunos"
---
> SunOS এর জন্য tcpdump এর সমতুল্য।

> আরও তথ্য পাবেন: <https://www.unix.com/man-page/sunos/1m/snoop>.

- একটি নির্দিষ্ট নেটওয়ার্ক ইন্টারফেসে প্যাকেটগুলি ক্যাপচার করুন:

```bash
snoop -d e1000g0
```

- ক্যাপচার করা প্যাকেটগুলিকে প্রদর্শন করার পরিবর্তে একটি ফাইলে সংরক্ষণ করুন:

```bash
snoop -o ফাইলের_নাম
```

- একটি ফাইল থেকে প্যাকেটের ভার্বোজ প্রোটোকল লেয়ারের সারাংশ প্রদর্শন করুন:

```bash
snoop -V -i ফাইলের_নাম
```

- একটি হোস্টনাম থেকে আসা নেটওয়ার্ক প্যাকেটগুলি ক্যাপচার করুন এবং একটি প্রদত্ত পোর্টে যান:

```bash
snoop to port পোর্ট from host হোস্টনাম
```

- দুটি আইপি ঠিকানার মধ্যে বিনিময় করা নেটওয়ার্ক প্যাকেটের একটি হেক্স-ডাম্প ক্যাপচার করুন এবং প্রদর্শন করুন:

```bash
snoop -x0 -p4 আইপি_ঠিকানা_১ আইপি_ঠিকানা_২
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: normalize colons (#7913) | 2022-03-27T07:25:15 | [27ff55fc2eea](https://github.com/tldr-pages/tldr/commit/27ff55fc2eea445eb5216c3b1d934960539fc024)
[Appledora](mailto:nazia89@student.sust.edu) | apt, cd, cmd, ditto, git-cherry-pick, snoop: add Bengali translation (#6989) | 2021-10-19T10:25:35 | [529589f9f074](https://github.com/tldr-pages/tldr/commit/529589f9f074031156a66e752ed5dcb86701592a)

