---
author: ['Marco Bonelli', 'Seth Falco', 'lincc', 'bl-ue']
date: 1648358715
title: "ab, TLDR Pages"
description: "ab, அப்பாச்சி தரப்படுத்தல் கருவி. சுமை சோதனை செய்ய எளிய கருவி."
categories: "common"
---
> மேலும் விவரத்திற்கு: <https://httpd.apache.org/docs/current/programs/ab.html>.

- கொடுக்கப்பட்ட முகவரி க்கு 100 HTTP GET கோரிக்கைகளை இயக்கவும்:

```bash
ab -n 100 முகவரி
```

- கொடுக்கப்பட்ட முகவரி க்கு 100 HTTP GET கோரிக்கைகளை ஒரே நேரத்தில் 10 கோரிக்கைகள் வீதம் செயல்படுத்தவும்:

```bash
ab -n 100 -c 10 முகவரி
```

- இணைப்பை தொடரச்செய்:

```bash
ab -k முகவரி
```

- தரப்படுத்தல் குறிக்க செலவழிக்க அதிகபட்ச விநாடிகளை அமைக்கவும்:

```bash
ab -t 60 முகவரி
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: normalize colons (#7913) | 2022-03-27T07:25:15 | [27ff55fc2eea](https://github.com/tldr-pages/tldr/commit/27ff55fc2eea445eb5216c3b1d934960539fc024)
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: trim multiple spaces, fix line endings | 2021-04-04T01:44:24 | [04dd546e2de7](https://github.com/tldr-pages/tldr/commit/04dd546e2de7f59f40a867acca6f46b0dc8ea9b4)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | ab: update grammar; update link (#5433) | 2021-03-13T22:44:59 | [8f2ed246f761](https://github.com/tldr-pages/tldr/commit/8f2ed246f7614df6e815b9eefae053a0f64df920)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize "more information" labels (#5140) | 2021-01-15T18:24:49 | [c59f12aa9f55](https://github.com/tldr-pages/tldr/commit/c59f12aa9f55d85612ba22e4da86db293ff76977)
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | ab, ack: add Tamil translation (revived) (#3761) Co-authored-by: MohamedSabthar <43032716+MohamedSabthar@users.noreply.github.com> | 2020-01-16T01:22:16 | [4ce320538293](https://github.com/tldr-pages/tldr/commit/4ce320538293541c474ed5e053c00e164d72a53f)

