---
author: ['Sailesh Shrestha', 'lincc', 'Seth Falco', 'marchersimon']
date: 1659075216
title: "at"
description: "at, पछि एक पटक आदेशहरू कार्यान्वयन गर्छ।"
categories: "common"
---
> वास्तविक कार्यान्वयनको लागि service atd(अथवा atrun) चलिरहेको हुनुपर्छ ।

> थप जानकारी: <https://manned.org/at>.

- standard input बाट आदेशहरू ५ मिनटमा कार्यान्वयन गर्नुहोस् (सकिएपछि `Ctrl +D` थिच्नुहोस्):

```bash
at now + 5 minutes
```

- standard input बाट आदेश आजको बिहानको १० बजे कार्यान्वयन गर्नुहोस्:

```bash
echo "./make_db_backup.sh" | at 1000
```

- एउटा दिइएको फाइलबाट अर्को मङ्गलबार आदेशहरु कार्यान्वयन गर्नुहोस्:

```bash
at -f path/to/file 9:30 PM Tue
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Sync more information links with all translations (#8256) | 2022-07-29T08:13:36 | [1f610a952ea0](https://github.com/tldr-pages/tldr/commit/1f610a952ea0d53e0a1bdbd1246ef81f24db2f3f)
[Seth Falco](mailto:seth@falco.fun) | *: normalize colons (#7913) | 2022-03-27T07:25:15 | [27ff55fc2eea](https://github.com/tldr-pages/tldr/commit/27ff55fc2eea445eb5216c3b1d934960539fc024)
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Sailesh Shrestha](mailto:34860977+werewolf-65@users.noreply.github.com) | alias, at: add Nepali translation (#7221) | 2021-10-29T15:57:49 | [1c0222ee731a](https://github.com/tldr-pages/tldr/commit/1c0222ee731a4ac7fcdd3b139c6c234324609e2e)

