---
author: ['Appledora']
date: 1634631935
title: "apt, TLDR Pages"
description: "apt, ডেবিয়ান ভিত্তিক ডিস্ট্রিবিউশনের জন্য প্যাকেজ ম্যানেজমেন্ট ইউটিলিটি।"
categories: "linux"
---
> ইন্টারেক্টিভভাবে ব্যবহৃত হলে উবুন্টু সংস্করণ 16.04 এবং তার পরবর্তী সংস্করনের জন্য `apt-get` এর পরিবরতে রেকোমেন্ডেড প্রতিস্থাপন।

> আরও তথ্য পাবেন: <https://manpages.debian.org/latest/apt/apt.8.html>.

- উপলভ্য প্যাকেজ এবং সংস্করণের তালিকা আপডেট করুন (অন্যান্য `apt` কমান্ডের আগে এটি চালানোর পরামর্শ দেওয়া হচ্ছে):

```bash
sudo apt update
```

- প্রদত্ত প্যাকেজ অনুসন্ধান করুন:

```bash
apt search প্যাকেজ
```

- একটি প্যাকেজের জন্য তথ্য দেখান:

```bash
apt show প্যাকেজ
```

- একটি প্যাকেজ ইনস্টল করুন, অথবা সর্বশেষ উপলব্ধ সংস্করণে আপডেট করুন:

```bash
sudo apt install প্যাকেজ
```

- একটি প্যাকেজ সরান (পরিবর্তে `purge` ব্যবহার করে এর কনফিগারেশন ফাইলও সরিয়ে দেয়):

```bash
sudo apt remove প্যাকেজ
```

- সমস্ত ইনস্টল করা প্যাকেজগুলি তাদের নতুন উপলব্ধ সংস্করণগুলিতে আপগ্রেড করুন:

```bash
sudo apt upgrade
```

- সমস্ত প্যাকেজের তালিকা করুন:

```bash
apt list
```

- ইনস্টল করা প্যাকেজ সমূহ তালিকা করুন:

```bash
apt list --installed
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Appledora](mailto:nazia89@student.sust.edu) | apt, cd, cmd, ditto, git-cherry-pick, snoop: add Bengali translation (#6989) | 2021-10-19T10:25:35 | [529589f9f074](https://github.com/tldr-pages/tldr/commit/529589f9f074031156a66e752ed5dcb86701592a)

