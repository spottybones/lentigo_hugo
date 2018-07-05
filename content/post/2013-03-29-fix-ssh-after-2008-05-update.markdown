---
author: Scott Burns
categories: null
comments: true
date: 2013-03-29T13:15:19Z
title: Fix ssh-agent after installing Apple's 2008-005 security update
url: /node/25
---

After installing Apple's 2008-005 security update on my Leopard machines I found that ssh-agent was no longer being started on system boot.  I use <code>ssh</code> with key-based authentication for lots of things and not having it automatically loaded and communicating with my keychain was a real pain.  After monkeying around with lots of ways to get it going again I found the following command, entered in a terminal and followed by a reboot, did the trick:

```
sudo launchctl load -w /System/Library/LaunchAgents/org.openbsd.ssh-agent.plist
```

On OS X all roads lead to launchd.
