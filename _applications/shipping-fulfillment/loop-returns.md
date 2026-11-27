---
app: Loop Returns
app_slug: loop-returns
app_url: https://www.loopreturns.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-4260.40
  key: customer-lifecycle-engagement
  layer: domain
  name: Customer Lifecycle Engagement
  providers:
  - Rise.ai
  url: /capabilities/customer-lifecycle-engagement/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-929
  key: AE-929
  layer: domain
  name: Multi-Carrier Shipping Platforms
  providers:
  - EasyPost
  url: /capabilities/logistics-operations-management/
  via_parent: Logistics Operations Management
- attribution: API Evangelist extension
  id: AE-928
  key: AE-928
  layer: domain
  name: Parcel Rating & Label Purchase
  providers:
  - UPS
  - USPS
  url: /capabilities/logistics-operations-management/
  via_parent: Logistics Operations Management
- attribution: Turbo EA
  id: BC-2460.60
  key: warehouse-resource-management
  layer: domain
  name: Warehouse Resource Management
  providers:
  - Ryder
  - ShipHero
  url: /capabilities/warehouse-resource-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-430
  key: customer-service-management
  layer: common
  name: Customer Service Management
  providers:
  - Gorgias
  url: /capabilities/customer-service-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-400.60
  key: digital-marketing-management
  layer: common
  name: Digital Marketing Management
  providers:
  - Attentive
  - Klaviyo
  url: /capabilities/digital-marketing-management/
  via_parent: null
category:
  id: shipping-fulfillment
  name: Shipping, Fulfillment & Returns
  url: /applications/shipping-fulfillment/
counts:
  declared: 9
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.loopreturns.com/integrations/
integrations:
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 35.8
    band: exemplar
    in_catalog: true
    kin_score: 75.7
    mcp: &id001
      status: none
    slug: attentive
    status: profiled
    tags: &id002
    - Company
    - Email Marketing
    - MarTech
    - SMS Marketing
    url: /providers/attentive/
  layer: common
  name: Attentive
  provider: attentive
  says: lists Attentive as an integration
  source: https://www.loopreturns.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-929
    key: AE-929
    name: Multi-Carrier Shipping Platforms
    url: /capabilities/logistics-operations-management/
    via_parent: Logistics Operations Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 21.9
    band: thin
    in_catalog: true
    kin_score: 32.0
    mcp: &id003
      status: none
    slug: easypost
    status: profiled
    tags: &id004
    - Logistics
    - Multi-Carrier
    - Shipping
    - Tracking
    url: /providers/easypost/
  layer: domain
  name: EasyPost
  provider: easypost
  says: lists EasyPost as an integration
  source: https://www.loopreturns.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-430
    key: customer-service-management
    name: Customer Service Management
    url: /capabilities/customer-service-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.3
    band: developing
    in_catalog: true
    kin_score: 42.5
    mcp: &id005
      source: https://github.com/gorgias/mcp-cookbook
      status: verified
    slug: gorgias
    status: profiled
    tags: &id006
    - Customer Service
    - E-Commerce
    - Help Desk
    - Shopify
    url: /providers/gorgias/
  layer: common
  name: Gorgias
  provider: gorgias
  says: lists Gorgias as an integration
  source: https://www.loopreturns.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 58.7
    band: exemplar
    in_catalog: true
    kin_score: 78.1
    mcp: &id007
      source: https://developers.klaviyo.com/en/docs/klaviyo_mcp_server
      status: verified
    slug: klaviyo
    status: profiled
    tags: &id008
    - Customer Data
    - Email
    - Marketing
    - SMS
    url: /providers/klaviyo/
  layer: common
  name: Klaviyo
  provider: klaviyo
  says: lists Klaviyo as an integration
  source: https://www.loopreturns.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4260.40
    key: customer-lifecycle-engagement
    name: Customer Lifecycle Engagement
    url: /capabilities/customer-lifecycle-engagement/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.0
    band: emerging
    in_catalog: true
    kin_score: 17.4
    mcp: &id009
      status: unknown
    slug: rise-ai
    status: profiled
    tags: &id010
    - Company
    url: /providers/rise-ai/
  layer: domain
  name: Rise.ai
  provider: rise-ai
  says: lists Rise.ai as an integration
  source: https://www.loopreturns.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2460.60
    key: warehouse-resource-management
    name: Warehouse Resource Management
    url: /capabilities/warehouse-resource-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 18.6
    band: thin
    in_catalog: true
    kin_score: 34.3
    mcp: &id011
      status: none
    slug: ryder-system
    status: profiled
    tags: &id012
    - Fleet Management
    - Logistics
    - Supply Chain
    - Transportation
    url: /providers/ryder-system/
  layer: domain
  name: Ryder
  provider: ryder-system
  says: lists Ryder as an integration
  source: https://www.loopreturns.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2460.60
    key: warehouse-resource-management
    name: Warehouse Resource Management
    url: /capabilities/warehouse-resource-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 29.1
    band: thin
    in_catalog: true
    kin_score: 30.6
    mcp: &id013
      status: none
    slug: shiphero
    status: profiled
    tags: &id014
    - E-Commerce
    - Fulfillment
    - GraphQL
    - Warehouse Management
    url: /providers/shiphero/
  layer: domain
  name: ShipHero
  provider: shiphero
  says: lists ShipHero as an integration
  source: https://www.loopreturns.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-928
    key: AE-928
    name: Parcel Rating & Label Purchase
    url: /capabilities/logistics-operations-management/
    via_parent: Logistics Operations Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 29.2
    band: thin
    in_catalog: true
    kin_score: 27.9
    mcp: &id015
      source: https://github.com/UPS-API/ups-mcp
      status: verified
    slug: ups
    status: profiled
    tags: &id016
    - Fortune 500
    - Logistics
    - Shipping
    - Supply Chain
    url: /providers/ups/
  layer: domain
  name: UPS
  provider: ups
  says: lists UPS as an integration
  source: https://www.loopreturns.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-928
    key: AE-928
    name: Parcel Rating & Label Purchase
    url: /capabilities/logistics-operations-management/
    via_parent: Logistics Operations Management
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 51.8
    band: developing
    in_catalog: true
    kin_score: 52.0
    mcp: &id017
      status: none
    slug: usps
    status: profiled
    tags: &id018
    - Government
    - Logistics
    - Postal Service
    - Shipping
    url: /providers/usps/
  layer: domain
  name: USPS
  provider: usps
  says: lists USPS as an integration
  source: https://www.loopreturns.com/integrations/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/shipping-fulfillment/loop-returns/
providers:
- agent_band: agent-ready
  agent_readiness: 35.8
  band: exemplar
  in_catalog: true
  kin_score: 75.7
  mcp: *id001
  name: Attentive
  slug: attentive
  status: profiled
  tags: *id002
  url: /providers/attentive/
- agent_band: agent-aware
  agent_readiness: 21.9
  band: thin
  in_catalog: true
  kin_score: 32.0
  mcp: *id003
  name: EasyPost
  slug: easypost
  status: profiled
  tags: *id004
  url: /providers/easypost/
- agent_band: agent-aware
  agent_readiness: 25.3
  band: developing
  in_catalog: true
  kin_score: 42.5
  mcp: *id005
  name: Gorgias
  slug: gorgias
  status: profiled
  tags: *id006
  url: /providers/gorgias/
- agent_band: agent-native
  agent_readiness: 58.7
  band: exemplar
  in_catalog: true
  kin_score: 78.1
  mcp: *id007
  name: Klaviyo
  slug: klaviyo
  status: profiled
  tags: *id008
  url: /providers/klaviyo/
- agent_band: agent-ready
  agent_readiness: 31.0
  band: emerging
  in_catalog: true
  kin_score: 17.4
  mcp: *id009
  name: Rise.ai
  slug: rise-ai
  status: profiled
  tags: *id010
  url: /providers/rise-ai/
- agent_band: agent-aware
  agent_readiness: 18.6
  band: thin
  in_catalog: true
  kin_score: 34.3
  mcp: *id011
  name: Ryder
  slug: ryder-system
  status: profiled
  tags: *id012
  url: /providers/ryder-system/
- agent_band: agent-ready
  agent_readiness: 29.1
  band: thin
  in_catalog: true
  kin_score: 30.6
  mcp: *id013
  name: ShipHero
  slug: shiphero
  status: profiled
  tags: *id014
  url: /providers/shiphero/
- agent_band: agent-ready
  agent_readiness: 29.2
  band: thin
  in_catalog: true
  kin_score: 27.9
  mcp: *id015
  name: UPS
  slug: ups
  status: profiled
  tags: *id016
  url: /providers/ups/
- agent_band: agent-native
  agent_readiness: 51.8
  band: developing
  in_catalog: true
  kin_score: 52.0
  mcp: *id017
  name: USPS
  slug: usps
  status: profiled
  tags: *id018
  url: /providers/usps/
siblings:
- name: ERPNext Shipping
  rows: 2
  url: /applications/shipping-fulfillment/erpnext-shipping/
- name: Karrio
  rows: 24
  url: /applications/shipping-fulfillment/karrio/
- name: Odoo Inventory (delivery connectors)
  rows: 11
  url: /applications/shipping-fulfillment/odoo-inventory-delivery-connectors/
- name: Sendcloud
  rows: 53
  url: /applications/shipping-fulfillment/sendcloud/
- name: Shippo
  rows: 33
  url: /applications/shipping-fulfillment/shippo/
sitemap: true
title: 'Loop Returns: Shipping, Fulfillment & Returns reference app'
---
