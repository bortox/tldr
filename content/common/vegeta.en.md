---
author: ['Waldir Pimenta', 'Antoine Amara', 'Owen Voke', 'bl-ue', 'Marco Bonelli', 'Seth Falco']
date: 1629050349
title: "vegeta, TLDR Pages"
description: "vegeta, A command-line utility and a library for HTTP load testing."
categories: "common"
---
> See also `ab`.

> More information: <https://github.com/tsenart/vegeta>.

- Launch an attack lasting 30 seconds:

```bash
echo "GET https://example.com" | vegeta attack -duration=30s
```

- Launch an attack on a server with a self-signed HTTPS certificate:

```bash
echo "GET https://example.com" | vegeta attack -insecure -duration=30s
```

- Launch an attack with a rate of 10 requests per second:

```bash
echo "GET https://example.com" | vegeta attack -duration=30s -rate=10
```

- Launch an attack and display a report:

```bash
echo "GET https://example.com" | vegeta attack -duration=30s | vegeta report
```

- Launch an attack and plot the results on a graph (latency over time):

```bash
echo "GET https://example.com" | vegeta attack -duration=30s | vegeta plot > path/to/results.html
```

- Launch an attack against multiple URLs from a file:

```bash
vegeta attack -duration=30s -targets=requests.txt | vegeta report
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Owen Voke](mailto:owzie123@gmail.com) | multiple pages: add homepages (#3026) * zstd: add link to homepage * zsh: add link to homepage * zopflipng: add link to homepage * [...] | 2019-05-14T18:09:07 | [c4e95b92c42f](https://github.com/tldr-pages/tldr/commit/c4e95b92c42fe9fe8428c8d7c8cd5ad8d0bd1b0b)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | vegeta: various improvements (#3014) Some of these changes come from suggestions in review of PR #2519; others were minor improvements [...] | 2019-05-12T13:38:37 | [2df12038b244](https://github.com/tldr-pages/tldr/commit/2df12038b244fc28c1bc1309f4fa4848e92b885d)
[Antoine Amara](mailto:amara.antoine@gmail.com) | vegeta: add vegeta http load testing document. (#2519) Describe one example for each vegeta load testing case. One simple attack, one [...] | 2018-11-16T15:22:42 | [1627b936f0e7](https://github.com/tldr-pages/tldr/commit/1627b936f0e743108fce2acb7a5c7fff285e7352)

