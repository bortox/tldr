---
author: ['Sam James', 'bl-ue']
date: 1621541621
title: "siege"
description: "siege, HTTP loadtesting and benchmarking tool."
categories: "common"
---
> More information: <https://www.joedog.org/siege-manual/>.

- Test a URL with default settings:

```bash
siege https://example.com
```

- Test a list of URLs:

```bash
siege --file path/to/url_list.txt
```

- Test list of URLs in a random order (Simulates internet traffic):

```bash
siege --internet --file path/to/url_list.txt
```

- Benchmark a list of URLs (without waiting between requests):

```bash
siege --benchmark --file path/to/url_list.txt
```

- Set the amount of concurrent connections:

```bash
siege --concurrent=50 --file path/to/url_list.txt
```

- Set how long for the siege to run for:

```bash
siege --time=30s --file path/to/url_list.txt
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Sam James](mailto:sam@samdjames.uk) | siege: add page (#5028) * siege: add page * fix: Added token syntax & made more consistent with other pages * Apply suggestions from [...] | 2021-01-08T14:40:46 | [76db7af9d414](https://github.com/tldr-pages/tldr/commit/76db7af9d414ed9076e215369a780868067342a7)

