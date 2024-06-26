+++
title = "Home"
description = "Welcome to the home of the Azure Proactive Resiliency Library (APRL)"
weight = 1
+++

{{< alert style="danger" >}}

## ARCHIVE NOTICE

The APRL repository has undergone migration to a new repository called APRLv2.
As of April 15, 2024, it has been ARCHIVED and will no longer receive support or updates.

### New Repository: [https://github.com/Azure/Azure-Proactive-Resiliency-Library-v2](https://github.com/Azure/Azure-Proactive-Resiliency-Library-v2)

### [aka.ms/aprl](https://aka.ms/aprl) will redirect to the new website starting April 15th

{{< /alert >}}

Welcome to the home of the Azure Proactive Resiliency Library (APRL).

<img src="/Azure-Proactive-Resiliency-Library/media/img/aprl-white.png" width=40%>
<br><br>

This library is built with the intention of being a staging area for guidance and recommendations that can be used by customers, partners and the field in Well-Architected Framework reliability engagements/assessments; with the intent of the guidance and recommendations being promoted, once tested and validated with customers and partners, into the official [Well-Architected Framework documentation](https://aka.ms/waf).

The library also contains supporting [Azure Resource Graph (ARG)](https://learn.microsoft.com/azure/governance/resource-graph/overview) queries that can help customers, partners and the field identify resources that may or may not be compliant with the guidance and recommendations. The intent for these queries, in the long-term, is to make them part of the [Azure Advisor](https://learn.microsoft.com/azure/advisor/advisor-overview) service.

## Get Started

To get started head over to the [Azure Services section]({{< ref "services/_index.md">}}) and then navigate via the appropriate category to find guidance, recommendations alongside supporting Azure Resource Graph queries to help you discover compliant/non-compliant resources in your environment.

{{< alert style="info" >}}

You can also use the basic search functionality provided by this site to locate the Azure service you are looking for guidance, recommendations and supporting queries and scripts for.

{{< /alert >}}

### Definitions of Terms Used in APRL

In APRL you will see a number of terms used, like Preview & Verified. The below table provides the definition for each of these terms for clarity.

{{< table style="table-striped" >}}

| Term              | Definition                                                                                                                                                                                                              |
| ----------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Preview Guidance  | Guidance that Microsoft FTEs have created based on customer engagements and is in the process of reviewing with the relevant Azure Product Group Engineering Service owners to ensure the content is valid and accurate |
| Verified Guidance | Guidance has been signed off by Azure Product Group Engineering Service owners following their review                                                                                                                   |

{{< /table >}}

## Contributing

Please see the [contribution guide here]({{< ref "contributing/_index.md">}}).

{{< alert style="info" >}}

Please note that this site is built upon [GithHub Pages](https://pages.github.com) using [Hugo](https://gohugo.io/) which is using the [Ace Documentation theme](https://docs.vantage-design.com/ace/)

{{< /alert >}}
