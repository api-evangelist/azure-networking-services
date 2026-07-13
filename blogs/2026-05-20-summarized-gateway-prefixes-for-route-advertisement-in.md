---
title: "Summarized Gateway Prefixes for Route Advertisement in Azure Virtual Networks"
url: "https://techcommunity.microsoft.com/t5/azure-networking-blog/summarized-gateway-prefixes-for-route-advertisement-in-azure/ba-p/4521652"
date: "2026-05-20"
author: "Jay-Li"
feed_url: "https://techcommunity.microsoft.com/t5/s/gxcuf89792/rss/board?board.id=AzureNetworkingBlog"
---
Background Many Azure deployments follow a hub-and-spoke topology : one VNet is designated as the hub and holds the connection to on-premises (via ExpressRoute Gateway, VPN Gateway, or both), and workload VNets — the spokes — peer to the hub to reach on-premises and shared services. This centralizes gateway connectivity so many workloads can share a single ExpressRoute or VPN Gateway. However, in large hub-and-spoke topologies, ExpressRoute and VPN Gateway limits on advertised prefixes (for example, 1,000 IPv4 and 100 IPv6 prefixes) can be reached.
