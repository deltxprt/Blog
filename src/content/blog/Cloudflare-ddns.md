---
title: I Made a DDNS Integration For Cloudflare
description: ''
pubDate: 'January 10, 2025'
heroImage: '/Cloudflare-banner.jpg'
---

Github Project: https://github.com/deltxprt/cloudflare-ddns
# Yet an another DDNS app, why!???

I don't really know i just wanted to build something easy and straight forward.
It has a few options and the rest is taken care by cloudflare default values.

# How does it work?

It's really simple, all it does is call a cloudflare endpoint that tells you your public IP address and check if the record in cloudflare is still the same or not.

## Settings
There is only only 2 required settings and 2 optional settings.

### Required Settings
All you really need is the cloudflare token (CF_TOKEN) and the name of the record you want to associate with your external ip address (RECORD_NAME).

### Optional Settings
Then there is the optional ones.

One is to set at which interval you want to check/update the record in cloudflare (INTERVAL). 
By default I set it to 5 minutes ("5m").

The other is to have cloudflare proxy your external ip (PROXIED) instead of being directly accessible on the internet. 
By default it doesn't activate the proxy, because i know i can add a layer of complexity for some and also not every use case will need to be proxied.

# Why This Over Other Options?
Honestly i don't really know, i just wanted to do a small and simple project for myself and just wanted to share it with others self-hoster/homelabber like myself.
It also helps me learning more about GO and programming in general, since I recently changed from a 4+ years Windows Server Sys Admin role to a Fullstack dev role.

# Is There Other Projects You'd Like To Work On?
I do have a bigger project that i'm working on, to put it in simple words, it will be a central platform to manage every aspect of a server. But it will take some times before i have something to show.

Until then i might do more of these small projects this year.

See ya!
