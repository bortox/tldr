---
author: ['Waldir Pimenta', 'bl-ue', 'Ruben Vereecken', 'Agniva De Sarker', 'pxgamer', 'Balázs Úr', 'Peter Tripp']
date: 1618623753
title: "autossh, TLDR Pages"
description: "autossh, Run, monitor and restart SSH connections."
categories: "common"
---
> Auto-reconnects to keep port forwarding tunnels up. Accepts all `ssh` flags.

> More information: <https://www.harding.motd.ca/autossh>.

- Start an SSH session, restarting when a monitoring port fails to return data:

```bash
autossh -M monitor_port "ssh_command"
```

- Forward a local port to a remote one, restarting when necessary:

```bash
autossh -M monitor_port -L local_port:localhost:remote_port user@host
```

- Fork `autossh` into the background before executing `ssh` and don't open a remote shell:

```bash
autossh -f -M monitor_port -N "ssh_command"
```

- Run in the background, with no monitoring port, and instead send SSH keep-alive packets every 10 seconds to detect failure:

```bash
autossh -f -M 0 -N -o "ServerAliveInterval 10" -o "ServerAliveCountMax 3" "ssh_command"
```

- Run in the background, with no monitoring port and no remote shell, exiting if the port forward fails:

```bash
autossh -f -M 0 -N -o "ServerAliveInterval 10" -o "ServerAliveCountMax 3" -o ExitOnForwardFailure=yes -L local_port:localhost:remote_port user@host
```

- Run in the background, logging `autossh` debug output and `ssh` verbose output to files:

```bash
AUTOSSH_DEBUG=1 AUTOSSH_LOGFILE=path/to/autossh_log_file.log autossh -f -M monitor_port -v -E path/to/ssh_log_file.log ssh_command
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | autossh: refresh (#5718) | 2021-04-17T03:42:33 | [cda6f2d63e91](https://github.com/tldr-pages/tldr/commit/cda6f2d63e91466d4e66d18f945b1db73ac36657)
[pxgamer](mailto:owzie123@gmail.com) | autossh: add link to homepage | 2019-06-09T18:53:49 | [c647da36d259](https://github.com/tldr-pages/tldr/commit/c647da36d2590adaecf7ee3b025a72f5057addbc)
[Balázs Úr](mailto:balazs@urbalazs.hu) | multiple pages: remove superfluous white spaces (#2801) | 2019-02-24T16:47:41 | [ad3772d8cbd5](https://github.com/tldr-pages/tldr/commit/ad3772d8cbd5a61fecfb38ab13bdc7b104b4ecdf)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | Applying the snake_case convention throughout the repo (#967) * Applying the snake_case convention throughout the repo - Also removing [...] | 2016-07-22T22:24:06 | [3da76e4150b8](https://github.com/tldr-pages/tldr/commit/3da76e4150b8631fd74aabfcc953cc23731b6bb8)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | minor phrasing tweaks | 2016-01-13T15:26:38 | [3194fb07fe73](https://github.com/tldr-pages/tldr/commit/3194fb07fe734dbe785f8badfbbd58b87cb0b884)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Reformatted pages once more | 2016-01-13T12:04:46 | [967633411984](https://github.com/tldr-pages/tldr/commit/9676334119847078e5e05fec393a3fe36991dbc2)
[Peter Tripp](mailto:petertripp@gmail.com) | Perhaps human readable autossh examples. | 2016-01-12T03:07:36 | [f3a144b830dc](https://github.com/tldr-pages/tldr/commit/f3a144b830dc4eb2d2bbf343fa3dc0da2bbb26a5)

