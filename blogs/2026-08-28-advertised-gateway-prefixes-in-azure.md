---
title: "Advertised gateway prefixes in Azure"
url: "https://techcommunity.microsoft.com/t5/azure-networking-blog/advertised-gateway-prefixes-in-azure/ba-p/4550940"
date: "2026-08-28"
author: "erikbailey"
feed_url: "https://techcommunity.microsoft.com/t5/s/gxcuf89792/rss/board?board.id=AzureNetworkingBlog"
---
Introduction Large Azure hub-and-spoke environments can advertise a significant number of routes toward on-premises networks. By default, Azure VPN Gateway and ExpressRoute Gateway advertise the address spaces of the hub virtual network and the address spaces of peered spoke virtual networks that use gateway transit. As the number of spokes and address spaces grows, the border gateway protocol (BGP) route table grows as well.
