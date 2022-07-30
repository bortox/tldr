---
author: ['Starbeamrainbowlabs']
date: 1574644766
title: "influx"
description: "influx, InfluxDB command-line client."
categories: "common"
---
> More information: <https://docs.influxdata.com/influxdb/v1.7/tools/shell/>.

- Connect to an InfluxDB running on localhost with no credentials:

```bash
influx
```

- Connect with a specific username (will prompt for a password):

```bash
influx -username username -password ""
```

- Connect to a specific host:

```bash
influx -host hostname
```

- Use a specific database:

```bash
influx -database database_name
```

- Execute a given command:

```bash
influx -execute "influxql_command"
```

- Return output in a specific format:

```bash
influx -execute "influxql_command" -format json|csv|column
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | influx: add page (#3605) | 2019-11-25T02:19:26 | [707db4b5b23b](https://github.com/tldr-pages/tldr/commit/707db4b5b23b35ee5bee16b87d6e0d856369c37f)

