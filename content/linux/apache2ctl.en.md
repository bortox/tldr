---
author: ['Amit Sharma', 'siavashsoleymani', 'Patrice Denis']
date: 1617209183
title: "apache2ctl"
description: "apache2ctl, The CLI tool to administrate HTTP web server Apache."
categories: "linux"
---
> This command comes with Debian based OSes, for RHEL based ones see `httpd`.

> More information: <https://manpages.debian.org/latest/apache2/apache2ctl.8.en.html>.

- Start the Apache daemon. Throw a message if it is already running:

```bash
sudo apache2ctl start
```

- Stop the Apache daemon:

```bash
sudo apache2ctl stop
```

- Restart the Apache daemon:

```bash
sudo apache2ctl restart
```

- Test syntax of the configuration file:

```bash
sudo apache2ctl -t
```

- List loaded modules:

```bash
sudo apache2ctl -M
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Patrice Denis](mailto:patrice.denis@gmail.com) | apache2ctl: add more info link | 2021-03-31T18:46:23 | [df2b0c108c82](https://github.com/tldr-pages/tldr/commit/df2b0c108c82b6ab11c8dc0e16104f3e01e6b16f)
[siavashsoleymani](mailto:siavash.solimanii@yahoo.com) | apache2ctl: fix typo | 2020-10-27T12:01:11 | [44a3a7888e8b](https://github.com/tldr-pages/tldr/commit/44a3a7888e8b303ed5c065e2a9ed6beb24fbb5d1)
[Amit Sharma](mailto:7789327+amitech@users.noreply.github.com) | apache2ctl: add page (#2073) | 2018-05-02T12:41:22 | [e10778e24c63](https://github.com/tldr-pages/tldr/commit/e10778e24c6322087b6d65602f433bad2777d500)

