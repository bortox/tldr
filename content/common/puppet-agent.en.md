---
author: ['valentin lauber', 'Daniel']
date: 1645104205
title: "puppet agent, TLDR Pages"
description: "puppet agent, Retrieves the client configuration from a Puppet server and applies it to the local host."
categories: "common"
---
> More information: <https://puppet.com/docs/puppet/7/man/agent.html>.

- Register a node at a Puppet server and apply the received catalog:

```bash
puppet agent --test --server puppetserver_fqdn --serverport port --waitforcert poll_time
```

- Run the agent in the background (uses settings from `puppet.conf`):

```bash
puppet agent
```

- Run the agent once in the foreground, then exit:

```bash
puppet agent --test
```

- Run the agent in dry-mode:

```bash
puppet agent --test --noop
```

- Log every resource being evaluated (even if nothing is being changed):

```bash
puppet agent --test --evaltrace
```

- Disable the agent:

```bash
puppet agent --disable "message"
```

- Enable the agent:

```bash
puppet agent --enable
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[valentin lauber](mailto:valentin@gwservice.ch) | puppet-agent: add --disable and --enable examples (#7787) | 2022-02-17T14:23:25 | [3ed8d563bc37](https://github.com/tldr-pages/tldr/commit/3ed8d563bc37bcd3ce9681d1f9cc182b8363b38c)
[Daniel](mailto:33197631+dadav@users.noreply.github.com) | puppet, puppet-agent, puppet-apply: add page (#6794) | 2021-10-12T05:05:25 | [376a838eabd1](https://github.com/tldr-pages/tldr/commit/376a838eabd1db7407af56860f0f9d26ef02cb9c)

