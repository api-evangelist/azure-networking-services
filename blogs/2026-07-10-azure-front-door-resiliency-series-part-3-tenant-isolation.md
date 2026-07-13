---
title: "Azure Front Door: Resiliency Series – Part 3: Tenant isolation"
url: "https://techcommunity.microsoft.com/t5/azure-networking-blog/azure-front-door-resiliency-series-part-3-tenant-isolation/ba-p/4535866"
date: "2026-07-10"
author: "AbhishekTiwari"
feed_url: "https://techcommunity.microsoft.com/t5/s/gxcuf89792/rss/board?board.id=AzureNetworkingBlog"
---
Abhishek Tiwari, Vice President of Engineering, Azure Networking Amit Srivastava, Partner Director of PM, Azure Networking Varun Chawla, Partner Director of Engineering, Azure Networking Azure Front Door serves hundreds of thousands of tenants from hundreds of edge locations, densely sharing the globally distributed edge fleet. That density is exactly what allows us to deliver global scale, performance, and cost efficiency. It also means that, without strong isolation, a single tenant’s incompatible configuration or anomalous traffic can, in the worst case, affect many other tenants.
