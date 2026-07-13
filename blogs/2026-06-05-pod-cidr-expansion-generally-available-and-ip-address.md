---
title: "Pod CIDR Expansion Generally Available and IP Address Planning on Azure CNI Overlay"
url: "https://techcommunity.microsoft.com/t5/azure-networking-blog/pod-cidr-expansion-generally-available-and-ip-address-planning/ba-p/4521700"
date: "2026-06-05"
author: "Sam_Foo"
feed_url: "https://techcommunity.microsoft.com/t5/s/gxcuf89792/rss/board?board.id=AzureNetworkingBlog"
---
In networking with Azure CNI Overlay, the cluster-wide pod CIDR is logically partitioned into smaller “node” blocks where each node is assigned a fixed CIDR slice (/24) by Azure. This decouples pod networking from the VNet address space entirely because pods receive addresses from a private CIDR that is separate from the VNet. By default, Azure CNI Overlay uses a pod CIDR of 10.244.0.0/16 which provides 65,536 addresses.
