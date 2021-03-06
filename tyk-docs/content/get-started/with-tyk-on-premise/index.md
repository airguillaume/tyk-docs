---
date: 2017-03-15T15:01:42Z
title: With Tyk On-Premises
menu: 
  main:
    parent: "Get started"
weight: 5
url: "/get-started/with-tyk-on-premise"
---

## <a name="what-is-tyk-on-premises"></a>What is Tyk On-Premises?

Tyk On-Premises is the way to install an entire Tyk solution in your own infrastructure, it enables you to have full control over every element of the Tyk stack as well as no external dependency on our cloud solution or infrastructure.

The full Tyk On-Premises system consists of:

*   Tyk API Gateway: The API Gateway that proxies and manages your traffic.
*   Tyk Dashboard: The management Dashboard and integration API for managing a cluster of Tyk Gateways, also shows analytics and features the Developer portal.
*   Tyk Pump: Handles moving analytics data between your gateways and your Dashboard (amongst other data sinks).
*   Tyk Identity Broker (Optional): Handles integrations with third-party IDP's.
*   Tyk Multi-Data-Center Bridge (Optional, Enterprise-only): Allows for the configuration of a Tyk ecosystem that spans many data centers and clouds.

### Getting Started

To get started with Tyk On-Premises, visit our [licensing page][1].

## <a name="dependencies"></a>Dependencies

A full Tyk On-Premises installation has the following requirements:

*   Redis: The primary key store for the Tyk Gateway, also synchronises data across gateways in a horizontally scaling installation.
*   MongoDB: The primary configuration store and analytics data store, required by the dashboard and portal, not required by the gateway.

 [1]: /api-manager-licenses/
