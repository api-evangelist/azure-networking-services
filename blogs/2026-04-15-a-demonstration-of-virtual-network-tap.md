---
title: "A demonstration of Virtual Network TAP"
url: "https://techcommunity.microsoft.com/t5/azure-networking-blog/a-demonstration-of-virtual-network-tap/ba-p/4479136"
date: "2026-04-15"
author: "Marc de Droog"
feed_url: "https://techcommunity.microsoft.com/t5/s/gxcuf89792/rss/board?board.id=AzureNetworkingBlog"
---
Azure Virtual Network Terminal Access Point (VTAP) , at the time of writing in April 2026 in public preview in select regions, copies network traffic from source Virtual Machines to a collector or traffic analytics tool, running as a Network Virtual Appliance (NVA). VTAP creates a full copy of all traffic sent and received by Virtual Machine Network Interface Card(s) (NICs) designated as VTAP source(s). This includes packet payload content - in contrast to VNET Flow Logs, which only collect traffic meta data.
