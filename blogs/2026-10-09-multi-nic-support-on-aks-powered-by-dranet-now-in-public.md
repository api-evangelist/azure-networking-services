---
title: "Multi-NIC Support on AKS powered by DRANET – Now in Public Preview"
url: "https://techcommunity.microsoft.com/t5/azure-networking-blog/multi-nic-support-on-aks-powered-by-dranet-now-in-public-preview/ba-p/4563257"
date: "2026-10-09"
author: "chandanAggarwal"
feed_url: "https://techcommunity.microsoft.com/t5/s/gxcuf89792/rss/board?board.id=AzureNetworkingBlog"
---
Kubernetes was designed around a simple networking model, every pod gets one network interface, and every pod on a node shares the same flat network. For most stateless microservices, this works well as it keeps the model simple and the platform portable. But a large class of workloads don't fit that shape.
