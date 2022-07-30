---
author: ['Grzegorz Baranski', 'gbaranski']
date: 1618870065
title: "xh"
description: "xh, Friendly and fast tool for sending HTTP requests."
categories: "common"
---
> More information: <https://github.com/ducaale/xh>.

- Send a GET request:

```bash
xh httpbin.org/get
```

- Send a POST request with a JSON body (key-value pairs are added to a top-level JSON object - e.g. `{"name": "john", "age": 25}`):

```bash
xh post httpbin.org/post name=john age:=25
```

- Send a GET request with query parameters (e.g. `first_param=5&second_param=true`):

```bash
xh get httpbin.org/get first_param==5 second_param==true
```

- Send a GET request with a custom header:

```bash
xh get httpbin.org/get header-name:header-value
```

- Make a GET request and save the response body to a file:

```bash
xh --download httpbin.org/json --output path/to/file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Grzegorz Baranski](mailto:root@gbaranski.com) | xh: rename query parameter vars | 2021-04-20T00:07:45 | [d95f3adf9f52](https://github.com/tldr-pages/tldr/commit/d95f3adf9f5245e021951ddeee8aa781f759a4ac)
[Grzegorz Baranski](mailto:root@gbaranski.com) | xh: fix example with POSTing JSON Body Co-authored-by: Starbeamrainbowlabs <sbrl@starbeamrainbowlabs.com> | 2021-04-20T00:07:45 | [0579078491b7](https://github.com/tldr-pages/tldr/commit/0579078491b7b74ffaff3e7d9d621e2c73a1dfd1)
[gbaranski](mailto:root@gbaranski.com) | xh: remove irrevelant example | 2021-04-20T00:07:45 | [ef319c824078](https://github.com/tldr-pages/tldr/commit/ef319c82407836b9849b78c248f417a52437e989)
[Grzegorz Baranski](mailto:root@gbaranski.com) | fix: remove unused semicolon Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> | 2021-04-20T00:07:45 | [5898f92cee19](https://github.com/tldr-pages/tldr/commit/5898f92cee19b38f408745f1c54513ecacad6989)
[Grzegorz Baranski](mailto:root@gbaranski.com) | xh: fix sending POST Request with JSON body example Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> | 2021-04-20T00:07:45 | [13ab7eae616d](https://github.com/tldr-pages/tldr/commit/13ab7eae616db51d72b2f62750fb61c203b6ed87)
[Grzegorz Baranski](mailto:root@gbaranski.com) | xh: fix sending GET Request example Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> | 2021-04-20T00:07:45 | [8918dd4d6d42](https://github.com/tldr-pages/tldr/commit/8918dd4d6d427b0800ffa3f520dad60be10bda38)
[Grzegorz Baranski](mailto:root@gbaranski.com) | xh: fix downloading JSON example Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> | 2021-04-20T00:07:45 | [ca04bb9921cd](https://github.com/tldr-pages/tldr/commit/ca04bb9921cde8f0e69c5a56f7122a6833488746)
[Grzegorz Baranski](mailto:root@gbaranski.com) | xh: fix get with a custom header example Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> | 2021-04-20T00:07:45 | [f727e15ee7b8](https://github.com/tldr-pages/tldr/commit/f727e15ee7b89a7350d5add775561bdd02f1733e)
[Grzegorz Baranski](mailto:root@gbaranski.com) | xh: remove app name in title Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> | 2021-04-20T00:07:45 | [0d3b7d7f7e6f](https://github.com/tldr-pages/tldr/commit/0d3b7d7f7e6fc8cfd590a0d0b8fae17dfe13fc95)
[gbaranski](mailto:root@gbaranski.com) | xh: solve few linting errors | 2021-04-20T00:07:45 | [2cf485847f9a](https://github.com/tldr-pages/tldr/commit/2cf485847f9a64cd9f83cd9ee65ee56fdbdd70a1)
[Grzegorz Baranski](mailto:root@gbaranski.com) | xh: add highlighting variables | 2021-04-20T00:07:45 | [f1f15b255b97](https://github.com/tldr-pages/tldr/commit/f1f15b255b977bbc0f031c247c1209f5936d4698)
[Grzegorz Baranski](mailto:root@gbaranski.com) | create xh.md | 2021-04-20T00:07:45 | [72dabb9f7375](https://github.com/tldr-pages/tldr/commit/72dabb9f73756524049eec041d65c518118e2b0a)

