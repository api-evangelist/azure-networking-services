---
title: "Private subnets by default in Azure Virtual Networks: What changed and how to use NAT Gateway"
url: "https://techcommunity.microsoft.com/t5/azure-networking-blog/private-subnets-by-default-in-azure-virtual-networks-what/ba-p/4513778"
date: "2026-04-22"
author: "aimeelittleton"
feed_url: "https://techcommunity.microsoft.com/t5/s/gxcuf89792/rss/board?board.id=AzureNetworkingBlog"
---
Azure is evolving to better support secure ‑ by ‑ default cloud architectures. Starting with API version 2025 ‑ 07 ‑ 01 (released after March 31, 2026) , newly created virtual networks now default to using private subnets . This change removes the long ‑ standing platform behavior of automatically enabling outbound internet access through implicit public IPs, also known as default outbound access (DOA) .
