---
author: ['Waldir Pimenta', 'Ruben Vereecken', 'Sadeed', 'marklee', 'Starbeamrainbowlabs']
date: 1633438245
title: "mailx, TLDR Pages"
description: "mailx, Send and receive mail."
categories: "common"
---
> More information: <https://manned.org/mailx>.

- Send mail (the content should be typed after the command, and ended with `Ctrl+D`):

```bash
mailx -s "subject" to_addr
```

- Send mail with content passed from another command:

```bash
echo "content" | mailx -s "subject" to_addr
```

- Send mail with content read from a file:

```bash
mailx -s "subject" to_addr < content.txt
```

- Send mail to a recipient and CC to another address:

```bash
mailx -s "subject" -c cc_addr to_addr
```

- Send mail specifying the sender address:

```bash
mailx -s "subject" -r from_addr to_addr
```

- Send mail with an attachment:

```bash
mailx -a file -s "subject" to_addr
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Sadeed](mailto:sadeeedw@gmail.com) | mail, mailx, mesg, mmv, monop, most, mscore: add link (#6795) | 2021-10-05T14:50:45 | [696b11611fa5](https://github.com/tldr-pages/tldr/commit/696b11611fa5c0ebd61d71d470fc2cd34b700f08)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | mailx: fix keyboard shortcut format, per #1354 | 2017-09-08T11:01:07 | [7b3bb72fbaf3](https://github.com/tldr-pages/tldr/commit/7b3bb72fbaf39e203e1b3215f74ad7a7750e9f72)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | mailx: various tweaks - restore "content" as opposed to "body", per PR discussion - various improvements to command descriptions | 2017-04-17T07:24:29 | [1fcc48e01adf](https://github.com/tldr-pages/tldr/commit/1fcc48e01adf03948a5b35b18446ce811c8615ec)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | mailx: Improve the readability of the descriptions | 2017-04-17T07:24:29 | [092294370d10](https://github.com/tldr-pages/tldr/commit/092294370d10931bad2277781457c5d985f529dc)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[marklee](mailto:marklee@localhost.localdomain) | mailx: add page | 2016-01-04T11:27:47 | [bcf3b6b99748](https://github.com/tldr-pages/tldr/commit/bcf3b6b99748b5ce8aee61eb2f443db8d7d32367)

