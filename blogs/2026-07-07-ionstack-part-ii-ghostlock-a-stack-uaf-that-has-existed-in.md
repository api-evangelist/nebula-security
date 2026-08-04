---
title: "IonStack part II: GhostLock, a stack-UAF that has existed in ALL Linux distributions for 15 years"
url: "https://nebusec.ai/research/ionstack-part-2/"
date: "2026-07-07"
feed_url: "https://nebusec.ai/rss.xml"
---
GhostLock (CVE-2026-43499) is a Linux kernel vulnerability found by VEGA that exists in every major distribution since 2011. Triggering the bug does not require any special kernel config or privilege. By turning it into a 97% stable privilege escalation and container escape, Google has rewarded us $92,337 in kernelCTF.
