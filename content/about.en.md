---
date: 2021-11-17
title: "About TLDR Pages"
description: "What is TLDR Pages? How to contribute? What is this website?"
---
![TLDR Pages Logo](/tldr-logo.png)

|Gitter|PRs|Contributors|Build Status|LICENSE|
|---|---|---|---|---|
[![Gitter chat][gitter-image]][gitter-url]|[![Merged PRs][prs-merged-image]][prs-merged-url]|[![GitHub contributors][contributors-image]][contributors-url]|[![Build status][github-actions-image]][github-actions-url]|[![license][license-image]][license-url]

[github-actions-url]: https://github.com/tldr-pages/tldr/actions
[github-actions-image]: https://img.shields.io/github/workflow/status/tldr-pages/tldr/CI.svg
[gitter-url]: https://gitter.im/tldr-pages/tldr
[gitter-image]: https://img.shields.io/badge/chat-on_gitter-deeppink
[prs-merged-url]: https://github.com/tldr-pages/tldr/pulls?q=is:pr+is:merged
[prs-merged-image]: https://img.shields.io/github/issues-pr-closed-raw/tldr-pages/tldr.svg?label=merged+PRs&color=green
[contributors-url]: https://github.com/tldr-pages/tldr/graphs/contributors
[contributors-image]: https://img.shields.io/github/contributors-anon/tldr-pages/tldr.svg
[license-url]: https://github.com/tldr-pages/tldr/blob/main/LICENSE.md
[license-image]: https://img.shields.io/badge/license-CC_BY_4.0-blue.svg
</div>

This is a mix of TLDR Pages' Documentation and of information about this website.

## What is tldr-pages?

The **tldr-pages** project is a collection of community-maintained help pages
for command-line tools, that aims to be a simpler, more approachable complement
to traditional [man pages](https://en.wikipedia.org/wiki/Man_page).

Maybe you're new to the command-line world? Perhaps you're just a little rusty or can't always recall the arguments for commands like `lsof`, or `tar`?

It certainly doesn't help that the first option explained in `man tar` is:

```
-b blocksize
   Specify the block size, in 512-byte records, for tape drive I/O.
   As a rule, this argument is only needed when reading from or writing to tape drives,
   and usually not even then as the default block size of 20 records (10240 bytes) is very common.
```

There seems to be room for simpler help pages, focused on practical examples.
How about:

![Animated SVG of the tldr client displaying the tar command.](/tldr-tar.svg)

> The tar command TLDR Page is also available in this website at [this link](https://tldr.bortox.it/common/tar)

This repository is just that: an ever-growing collection of examples
for the most common UNIX, Linux, macOS, SunOS, Android and Windows command-line tools.

## What is this website?

This website aims to spread the TLDR Pages, _a collection of community-maintained help pages
for command-line tools_ among web users with a simple query for "TLDR Pages + command_name" on their preferred search engine.



As of now, you cannot find with an easy Google search the TLDR page of a command. That's even worse if you search a command in a specific language that is not English, there are often slow and clickbait websites



This website supports indeed comments and sharing too, so TLDR Pages also become "Web friendly". 

### Analytics, tracking & ads

Obviously in terms of ads, there are **no ads**. 

Tracking is done with Matomo. Matomo is set to **not collect any personal data**[^1], so it's GDPR compliant and doesn't need any cookie banner. [If you want to opt-out, you can do it here](https://stats.bortox.it/index.php?module=CoreAdminHome&action=optOut&language=it).
The website is **hosted in Europe**, by PHP-Friends. According to website-carbon.com the datacenter uses **sustainable energy**!

If you want to **support the website** (i do pay for the servers) you can [**donate** something here](https://bortox.it/contribuisci-cs-en).

### Why this website?

1. To index TLDR Pages and make them searchable online easily in multiple languages
2. Just for the sake of scripting something

### How does this website work?

* markdown TLDR source files and related git data get read by a script (30m)
* Hugo-compatible pages get created by the script
* Hugo builds this website (~6500 pages) in only 10 seconds!

### Potential new things

- [ ] Commit-specific pages
- [ ] Automatic Translation with DeepL (up to 500.000 chars / month in the free version)


## How do I use it?

A popular and convenient way to access these pages on your computer
is to install the [Node.js client](https://github.com/tldr-pages/tldr-node-client),
which is supported by the tldr-pages project maintainers:

```sh
npm install -g tldr
```

Alternatively, you can also use the [Python client](https://github.com/tldr-pages/tldr-python-client) which can be installed via `pip3`.

```sh
pip3 install tldr
```

Then you have direct access to simplified, easy-to-read help for commands, such as `tar`,
accessible through typing `tldr tar` instead of the standard `man tar`.

---

If you want an offline version without installing any software,
check out the [PDF version](https://tldr.sh/assets/tldr-book.pdf).

For browsing without installing a client to your computer,
see the web client at <https://tldr.ostera.io> or at my website, tldr.bortox.it

There are also **various other clients** provided by the community,
both for the command-line and for other platforms.
For a comprehensive list of clients, head over to our [Wiki](https://github.com/tldr-pages/tldr/wiki/tldr-pages-clients).

I recommend [**tealdeer**](https://dbrgn.github.io/tealdeer/). Tealdeer is written in Rust and makes use of a local cache, so the results are almost instant, instead with the Node/Python client there is always to wait a couple of seconds.

## How do I contribute to tldr-pages?

All contributions are welcome!

Some ways to contribute include:

- Adding your favorite command which isn't covered.
- Adding examples or improving the content of an existing page.
- Adding requested pages from our issues with the [help wanted](https://github.com/tldr-pages/tldr/issues?q=is%3Aopen+is%3Aissue+label%3A%22help+wanted%22) label.
- Translating pages into different languages.

All `tldr` pages are written in markdown, so they can be edited quite easily and changes can be submitted in
pull requests here using Git on the command-line or
using the GitHub web interface.

We strive to maintain a [welcoming and collaborative](https://github.com/tldr-pages/tldr/blob/main/GOVERNANCE.md) community.
If it's your first time contributing, have a look at the [contributing guidelines](https://github.com/tldr-pages/tldr/blob/main/CONTRIBUTING.md), and go ahead!

If you'd like to contribute to translations, you can visit <https://lukwebsforge.github.io/tldri18n/>
to see the overall progress of all translations, and which translations are missing or outdated.

## What does "tldr" mean?

TL;DR stands for "Too Long; Didn't Read".
It originated as Internet slang, where it is used to indicate that a long text
(or parts of it) has been skipped as too lengthy.
Read more in How-To Geek's [article](https://www.howtogeek.com/435266/what-does-tldr-mean-and-how-do-you-use-it/).

[^1]: No visitor log, cookieless tracking, IP addresses anonymized (2 bytes, like 192.168.xxx.xxx ) according to [matomo official guide](https://matomo.org/faq/new-to-piwik/how-do-i-use-matomo-analytics-without-consent-or-cookie-banner/) ... 