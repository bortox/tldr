---
author: ['Waldir Pimenta', 'bl-ue', 'pxgamer', 'Abhijit Paul', 'Seth Falco']
date: 1629050349
title: "logstash, TLDR Pages"
description: "logstash, An Elasticsearch ETL (extract, transform and load) tool."
categories: "common"
---
> Commonly used to load data from various sources (such as databases and log files) into Elasticsearch.

> More information: <https://www.elastic.co/products/logstash>.

- Check validity of a Logstash configuration:

```bash
logstash --configtest --config logstash_config.conf
```

- Run Logstash using configuration:

```bash
sudo logstash --config logstash_config.conf
```

- Run Logstash with the most basic inline configuration string:

```bash
sudo logstash -e 'input {} filter {} output {}'
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[pxgamer](mailto:owzie123@gmail.com) | logstash: add link to homepage | 2019-06-06T04:42:48 | [76a0354539c2](https://github.com/tldr-pages/tldr/commit/76a0354539c29de7c983adaddd11eeb7eb48f539)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | logstash: minor tweaks to the main description | 2017-02-03T20:55:05 | [5b977738d12c](https://github.com/tldr-pages/tldr/commit/5b977738d12c7de9b0bcf4ab2cc31d76ff0512b6)
[Abhijit Paul](mailto:abhijitunderground@gmail.com) | logstash: add page (#1245) | 2017-02-03T20:52:44 | [a969d6ebd817](https://github.com/tldr-pages/tldr/commit/a969d6ebd8179c1763ca700976f0c8c3164eabc4)

