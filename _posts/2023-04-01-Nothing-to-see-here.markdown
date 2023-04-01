---
layout: post
title: "Nothing to see here"
date: 2023-04-01 12:00:00 -0500
categories: update
---

# Welcome

At this point there is not much to see but that will change.

There will be changes but, initially, they are likely very boring to you: tests of what is possible using Github Pages.

For starters: good security headers.

A good set up for security headers will protect users from multiple security attacks: Cross-Site Scripting, Clickjacking, Information disclosure and more.

For this site I intend to use the security headers. There will be another post explaining the choices.

```html
Content-Type: text/html; charset=utf-8 Cache-Control: public, max-age=15768000
Strict-Transport-Security: max-age=15768000; includeSubDomains; preload
X-Frame-Options: SAMEORIGIN X-Content-Type-Options: nosniff Referrer-Policy:
strict-origin-when-cross-origin Permissions-Policy: accelerometer=(),
ambient-light-sensor=(), autoplay=(), battery=(), camera=(), display-capture=(),
document-domain=(), encrypted-media=(), execution-while-not-rendered=(),
execution-while-out-of-viewport=(), gamepad=(), geolocation=(), gyroscope=(),
identity-credentials-get=(), idle-detection=(), magnetometer=(), microphone=(),
midi=(), payment=(), picture-in-picture=(), publickey-credentials-get=(),
screen-wake-lock=(), serial=(), speaker-selection=(), usb=(), web-share=(),
xr-spatial-tracking=() Content-Security-Policy: default-src 'self'; form-action
'self'; frame-ancestors 'self' X-XSS-Protection: 1; mode=block Expect-CT:
enforce, max-age=15768000 Alt-Svc: clear
```
