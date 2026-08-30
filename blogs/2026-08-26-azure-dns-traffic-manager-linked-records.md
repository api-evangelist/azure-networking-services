---
title: "Azure DNS + Traffic Manager linked records"
url: "https://techcommunity.microsoft.com/t5/azure-networking-blog/azure-dns-traffic-manager-linked-records/ba-p/4548221"
date: "2026-08-26"
author: "atiy"
feed_url: "https://techcommunity.microsoft.com/t5/s/gxcuf89792/rss/board?board.id=AzureNetworkingBlog"
---
Introduction Traffic Manager linked records creates a direct, managed link between an Azure DNS record set and a Traffic Manager profile. When a query arrives, Azure DNS evaluates the linked Traffic Manager profile internally and returns the appropriate endpoint response directly. For A and AAAA records, this means the client receives endpoint IP addresses without an intermediate CNAME response to trafficmanager.net.
