---
author: ['Waldir Pimenta', 'Gear J', 'Balázs Úr']
date: 1633928905
title: "launchctl, TLDR Pages"
description: "launchctl, A command-line interface to Apple's `launchd` manager for launch daemons (system-wide services) and launch agents (per-user programs)."
categories: "osx"
---
> `launchd` loads XML-based `*.plist` files placed in the appropriate locations, and runs the corresponding commands according to their defined schedule.

> More information: <https://manned.org/launchctl>.

- Activate a user-specific agent to be loaded into `launchd` whenever the user logs in:

```bash
launchctl load ~/Library/LaunchAgents/my_script.plist
```

- Activate an agent which requires root privileges to run and/or should be loaded whenever any user logs in (note the absence of `~` in the path):

```bash
sudo launchctl load /Library/LaunchAgents/root_script.plist
```

- Activate a system-wide daemon to be loaded whenever the system boots up (even if no user logs in):

```bash
sudo launchctl load /Library/LaunchDaemons/system_daemon.plist
```

- Show all loaded agents/daemons, with the PID if the process they specify is currently running, and the exit code returned the last time they ran:

```bash
launchctl list
```

- Unload a currently loaded agent, e.g. to make changes (note: the plist file is automatically loaded into `launchd` after a reboot and/or logging in):

```bash
launchctl unload ~/Library/LaunchAgents/my_script.plist
```

- Manually run a known (loaded) agent/daemon, even if it is not the right time (note: this command uses the agent's label, rather than the filename):

```bash
launchctl start my_script
```

- Manually kill the process associated with a known agent/daemon, if it is running:

```bash
launchctl stop my_script
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Gear J](mailto:12108619+gearj@users.noreply.github.com) | launchctl, lldb, locate, look: add more information link (#6893) | 2021-10-11T07:08:25 | [fcc03f1e6ff9](https://github.com/tldr-pages/tldr/commit/fcc03f1e6ff9776ca4433447e9859a3c1a42e539)
[Balázs Úr](mailto:balazs@urbalazs.hu) | multiple pages: change Unicode characters to ASCII (#2802) Change Unicode characters to ASCII: - non-breaking spaces (\xc2\xa0) to [...] | 2019-02-25T00:56:24 | [6956cd5348e4](https://github.com/tldr-pages/tldr/commit/6956cd5348e4f87db1586a68ab299e46f7384b63)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | launchctl: add page (#1040) | 2016-09-14T18:29:12 | [c4740ca4e3ae](https://github.com/tldr-pages/tldr/commit/c4740ca4e3ae41f0c4d7aaaf774a25ffa5da9a8e)

