---
title: "Enabling fallback to internet for Azure Private DNS Zones in hybrid architectures"
url: "https://techcommunity.microsoft.com/t5/azure-networking-blog/enabling-fallback-to-internet-for-azure-private-dns-zones-in/ba-p/4511131"
date: "2026-04-15"
author: "kirankumar_manchiwar04"
feed_url: "https://techcommunity.microsoft.com/t5/s/gxcuf89792/rss/board?board.id=AzureNetworkingBlog"
---
Introduction Azure Private Endpoint enables secure connectivity to Azure PaaS services such as: Azure SQL Managed Instance Azure Container Registry Azure Key Vault Azure Storage Account through private IP addresses within a virtual network. When Private Endpoint is enabled for a service, Azure DNS automatically changes the name resolution path using CNAME Redirection Example: myserver.database.windows.net ↓ myserver.privatelink.database.windows.net ↓ Private IP Azure Private DNS Zones are then used to resolve this Private Endpoint FQDN within the VNet. However, this introduces a critical DNS limitation in: Hybrid cloud architectures (AWS → Azure SQL MI) Multiregion deployments (DR region access) Crosstenant / Crosssubscription access MultiVNet isolated networks If the Private DNS zone does not contain a corresponding record, Azure DNS returns: NXDOMAIN (NonExistent Domain) When a DNS resolver receives a negative response (NXDOMAIN), it sends no DNS response to the DNS client and the query fails.
