---
title: "IonStack Part I: Unsound IonBanana Peel in Ion Compiler, Slipping Through Firefox's SpiderMonkey JIT"
url: "https://nebusec.ai/research/ionstack-part-1-cve-2026-10702/"
date: "2026-07-10"
feed_url: "https://nebusec.ai/rss.xml"
---
Despite Anthropic Mythos's extensive auditing of Firefox, our agent VEGA still managed to uncover IonBanana, a subtle SpiderMonkey IonMonkey just-in-time miscompilation that can be exploited to achieve arbitrary code execution in the Firefox content process. To our knowledge, this is the first SpiderMonkey JIT CVE after Firefox's last-minute pre-Pwn2Own update, which fixed a large batch of vulnerabilities. We also used it to pwn Tor Browser, showing that even after heavy auditing, JIT compilers still have plenty of places for a banana peel to hide.
