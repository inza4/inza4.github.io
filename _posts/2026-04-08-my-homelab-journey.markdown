---
layout: post
title:  "My homelab journey"
date:   2026-04-08 11:16:56 +0200
categories: homelab
---

I was watching YouTube in my ~~smart~~ TV and after the n<sup>th</sup> ad, I decided it was enough. There has to be a better way. I started researching and found a solution: a Raspberry Pi running Kodi with a [youtube plugin](https://github.com/anxdpanic/plugin.video.youtube/releases).

It worked like a charm. Life was good now. Then I realized that I can get more from that little computer, so I installed docker on it. Stack after stack, I ended up with jellyfin as a music service, vaultwarden for password management and wireguard as VPN. Then I started playing with Ansible to maintain my homelab and restore it in case of failure.

| [![Image](/assets/images/blursed_server.jpg){: width="300" }](/assets/images/blursed_server.jpg) |
|:--:|
| *My first server in 2008, a VIA EPIA LT running Linux* |

This is of course not how my journey really started. In my late teens my passion for Linux and servers was already there, after trying different distributions, I successfully made a SUSE Linux connect to the internet dialing my 256 Kbps ADSL modem. In 2008 I got my hands on a [VIA EPIA LT](https://cdn.viaembedded.com/eol_products/docs/epia-lt/datasheet/VIA+EPIA+LT_datasheet_v120508.pdf) where I setup a Linux server, I don't remember which one but probably Debian.

| [![Image](/assets/images/server_rack.jpg){: width="300" }](/assets/images/server_rack.jpg) |
|:--:|
| *My current homelab: Dell Optiplex 5070 micro and a Raspberry Pi 5 (not in the picture)* |

Fast forward to September 2025, I found a second hand Dell Optiplex 5070 micro and decided to level up my setup. I installed Proxmox, instantiated a VM with OPNSense as router, learned about VLANs and with the help of some managed switches I started a new chapter in my homelab hobby. With the help of some friends, I 3d printed a nice [10 inches rack](https://www.printables.com/model/1210194-mini-rack-10-server-rack-for-navepoint-or-gator-ra) to organize it.

In future posts I will give more technical details of my infrastructure, for those who are interested in the details.

