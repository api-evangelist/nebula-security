---
title: "Route of Root: Bring a \"DoS only\" bug to LPE and bypass the existing patch to win $10,500 in kernelCTF"
url: "https://nebusec.ai/research/cve-2026-43501-route-of-root/"
date: "2026-08-08"
feed_url: "https://nebusec.ai/rss.xml"
---
CVE-2023-2156 ("Route of Death") is a Linux kernel vulnerability that was believed to only lead to a DoS attack, and was considered patched in April 2023. However, Nebula Security discovered a bypass of the patch and found that it is actually exploitable and can lead to LPE on any Linux distribution that has IPv6 and namespaces enabled. This writeup covers the technical details of the exploit.
