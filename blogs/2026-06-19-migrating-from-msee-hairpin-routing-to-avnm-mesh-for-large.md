---
title: "Migrating from MSEE Hairpin Routing to AVNM Mesh for Large-Scale VNet-to-VNet Connectivity"
url: "https://techcommunity.microsoft.com/t5/azure-networking-blog/migrating-from-msee-hairpin-routing-to-avnm-mesh-for-large-scale/ba-p/4529320"
date: "2026-06-19"
author: "Jay-Li"
feed_url: "https://techcommunity.microsoft.com/t5/s/gxcuf89792/rss/board?board.id=AzureNetworkingBlog"
---
Introduction A common pattern in large Azure deployments is to route VNet-to-VNet traffic through Microsoft Enterprise Edge (MSEE) routers. This happens when spoke VNets in a hub-and-spoke topology communicate with each other by hairpinning through the ExpressRoute circuit: traffic exits the Azure data center, traverses MSEE, and re-enters the data center to reach the destination VNet. This pattern works, but it was not designed as the long-term connectivity model for east-west traffic.
