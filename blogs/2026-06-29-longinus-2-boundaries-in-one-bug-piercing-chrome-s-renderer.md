---
title: "Longinus: 2 Boundaries in One Bug, Piercing Chrome’s Renderer and V8 Sandbox with a Single Vulnerability, CVE-2026-6307"
url: "https://nebusec.ai/research/v8-cve-2026-6307-writeup/"
date: "2026-06-29"
feed_url: "https://nebusec.ai/rss.xml"
---
Chrome V8 JavaScript engine features a heap sandbox to prevent an attacker from writing outside of the sandbox region with only a vulnerability in their JavaScript engine. However, VEGA discovered a special bug in the JIT compiler that allows an attacker to gain arbitrary read/write primitives in sandbox and even escape the sandbox to write outside of it solely on its own. This writeup will cover the technical details of the vulnerability.
