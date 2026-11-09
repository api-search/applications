---
app: Odoo Inventory (delivery connectors)
app_slug: odoo-inventory-delivery-connectors
app_url: https://github.com/odoo/odoo
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-929
  key: AE-929
  layer: domain
  name: Multi-Carrier Shipping Platforms
  providers:
  - EasyPost
  - Envia.com
  - Sendcloud
  - Shiprocket
  - Starshipit
  url: /capabilities/logistics-operations-management/
  via_parent: Logistics Operations Management
- attribution: API Evangelist extension
  id: AE-928
  key: AE-928
  layer: domain
  name: Parcel Rating & Label Purchase
  providers:
  - Mondial Relay
  - bpost
  - DHL
  - FedEx
  - UPS
  - USPS
  url: /capabilities/logistics-operations-management/
  via_parent: Logistics Operations Management
category:
  id: shipping-fulfillment
  name: Shipping, Fulfillment & Returns
  url: /applications/shipping-fulfillment/
counts:
  declared: 10
  observed: 1
credits: []
evidence:
- route: documentation
  url: https://www.odoo.com/documentation/18.0/applications/inventory_and_mrp/inventory/shipping_receiving/setup_configuration/third_party_shipper.html
- route: source code
  url: https://github.com/odoo/odoo/tree/18.0/addons
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-928
    key: AE-928
    name: Parcel Rating & Label Purchase
    url: /capabilities/logistics-operations-management/
    via_parent: Logistics Operations Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 12.9
    band: emerging
    in_catalog: true
    kin_score: 13.7
    mcp: &id011
      status: none
    slug: mondial-relay
    status: profiled
    tags: &id012
    - Company
    - E-Commerce
    - Logistics
    - Parcel Delivery
    url: /providers/mondial-relay/
  layer: domain
  name: Mondial Relay
  provider: mondial-relay
  says: ships the Mondial Relay SDK or integration code
  source: https://github.com/odoo/odoo/tree/18.0/addons
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-928
    key: AE-928
    name: Parcel Rating & Label Purchase
    url: /capabilities/logistics-operations-management/
    via_parent: Logistics Operations Management
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.9
    band: minimal
    in_catalog: true
    kin_score: 6.0
    mcp: &id001
      status: unknown
    slug: bpost
    status: profiled
    tags: &id002
    - Belgium
    - Company
    - Logistics
    - Postal
    url: /providers/bpost/
  layer: domain
  name: bpost
  provider: bpost
  says: lists bpost as an integration
  source: https://www.odoo.com/documentation/18.0/applications/inventory_and_mrp/inventory/shipping_receiving/setup_configuration/third_party_shipper.html
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
    agent_band: agent-aware
    agent_readiness: 24.1
    band: emerging
    in_catalog: true
    kin_score: 26.1
    mcp: &id003
      status: none
    slug: dhl
    status: profiled
    tags: &id004
    - E-Commerce
    - Freight
    - Logistics
    - Shipping
    url: /providers/dhl/
  layer: domain
  name: DHL
  provider: dhl
  says: lists DHL as an integration
  source: https://www.odoo.com/documentation/18.0/applications/inventory_and_mrp/inventory/shipping_receiving/setup_configuration/third_party_shipper.html
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
    agent_readiness: 22.4
    band: thin
    in_catalog: true
    kin_score: 32.4
    mcp: &id005
      status: none
    slug: easypost
    status: profiled
    tags: &id006
    - Logistics
    - Multi-Carrier
    - Shipping
    - Tracking
    url: /providers/easypost/
  layer: domain
  name: EasyPost
  provider: easypost
  says: lists EasyPost as an integration
  source: https://www.odoo.com/documentation/18.0/applications/inventory_and_mrp/inventory/shipping_receiving/setup_configuration/third_party_shipper.html
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
    agent_band: agent-ready
    agent_readiness: 45.0
    band: thin
    in_catalog: true
    kin_score: 39.2
    mcp: &id007
      source: https://docs.envia.com/docs/mcp-overview
      status: verified
    slug: envia
    status: profiled
    tags: &id008
    - Company
    - E-Commerce
    - Logistics
    - Shipping
    url: /providers/envia/
  layer: domain
  name: Envia.com
  provider: envia
  says: lists Envia.com as an integration
  source: https://www.odoo.com/documentation/18.0/applications/inventory_and_mrp/inventory/shipping_receiving/setup_configuration/third_party_shipper.html
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
    agent_readiness: 35.9
    band: exemplar
    in_catalog: true
    kin_score: 69.4
    mcp: &id009
      status: none
    slug: fedex
    status: profiled
    tags: &id010
    - Address Validation
    - Freight
    - Logistics
    - Pickup
    url: /providers/fedex/
  layer: domain
  name: FedEx
  provider: fedex
  says: lists FedEx as an integration
  source: https://www.odoo.com/documentation/18.0/applications/inventory_and_mrp/inventory/shipping_receiving/setup_configuration/third_party_shipper.html
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
    agent_band: agent-ready
    agent_readiness: 48.8
    band: exemplar
    in_catalog: true
    kin_score: 68.9
    mcp: &id013
      status: none
    slug: sendcloud
    status: profiled
    tags: &id014
    - Carrier
    - E-Commerce
    - Logistics
    - Shipping
    url: /providers/sendcloud/
  layer: domain
  name: Sendcloud
  provider: sendcloud
  says: lists Sendcloud as an integration
  source: https://www.odoo.com/documentation/18.0/applications/inventory_and_mrp/inventory/shipping_receiving/setup_configuration/third_party_shipper.html
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
    agent_band: agent-ready
    agent_readiness: 45.5
    band: strong
    in_catalog: true
    kin_score: 57.2
    mcp: &id015
      status: none
    slug: shiprocket
    status: profiled
    tags: &id016
    - Company
    - E-Commerce
    - Logistics
    - Shipping
    url: /providers/shiprocket/
  layer: domain
  name: Shiprocket
  provider: shiprocket
  says: lists Shiprocket as an integration
  source: https://www.odoo.com/documentation/18.0/applications/inventory_and_mrp/inventory/shipping_receiving/setup_configuration/third_party_shipper.html
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
    agent_readiness: 21.4
    band: emerging
    in_catalog: true
    kin_score: 16.1
    mcp: &id017
      status: unknown
    slug: starshipit
    status: profiled
    tags: &id018
    - Automation
    - E-Commerce
    - Fulfilment
    - Shipping
    url: /providers/starshipit/
  layer: domain
  name: Starshipit
  provider: starshipit
  says: lists Starshipit as an integration
  source: https://www.odoo.com/documentation/18.0/applications/inventory_and_mrp/inventory/shipping_receiving/setup_configuration/third_party_shipper.html
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
    agent_band: agent-aware
    agent_readiness: 24.1
    band: thin
    in_catalog: true
    kin_score: 29.0
    mcp: &id019
      source: https://github.com/UPS-API/ups-mcp
      status: verified
    slug: ups
    status: profiled
    tags: &id020
    - Fortune 500
    - Logistics
    - Shipping
    - Supply Chain
    url: /providers/ups/
  layer: domain
  name: UPS
  provider: ups
  says: lists UPS as an integration
  source: https://www.odoo.com/documentation/18.0/applications/inventory_and_mrp/inventory/shipping_receiving/setup_configuration/third_party_shipper.html
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
    agent_readiness: 31.9
    band: thin
    in_catalog: true
    kin_score: 33.2
    mcp: &id021
      status: none
    slug: usps
    status: profiled
    tags: &id022
    - Government
    - Logistics
    - Postal Service
    - Shipping
    url: /providers/usps/
  layer: domain
  name: USPS
  provider: usps
  says: lists USPS as an integration
  source: https://www.odoo.com/documentation/18.0/applications/inventory_and_mrp/inventory/shipping_receiving/setup_configuration/third_party_shipper.html
  tier: declared
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/shipping-fulfillment/odoo-inventory-delivery-connectors/
providers:
- agent_band: human-only
  agent_readiness: 2.9
  band: minimal
  in_catalog: true
  kin_score: 6.0
  mcp: *id001
  name: bpost
  slug: bpost
  status: profiled
  tags: *id002
  url: /providers/bpost/
- agent_band: agent-aware
  agent_readiness: 24.1
  band: emerging
  in_catalog: true
  kin_score: 26.1
  mcp: *id003
  name: DHL
  slug: dhl
  status: profiled
  tags: *id004
  url: /providers/dhl/
- agent_band: agent-aware
  agent_readiness: 22.4
  band: thin
  in_catalog: true
  kin_score: 32.4
  mcp: *id005
  name: EasyPost
  slug: easypost
  status: profiled
  tags: *id006
  url: /providers/easypost/
- agent_band: agent-ready
  agent_readiness: 45.0
  band: thin
  in_catalog: true
  kin_score: 39.2
  mcp: *id007
  name: Envia.com
  slug: envia
  status: profiled
  tags: *id008
  url: /providers/envia/
- agent_band: agent-ready
  agent_readiness: 35.9
  band: exemplar
  in_catalog: true
  kin_score: 69.4
  mcp: *id009
  name: FedEx
  slug: fedex
  status: profiled
  tags: *id010
  url: /providers/fedex/
- agent_band: agent-aware
  agent_readiness: 12.9
  band: emerging
  in_catalog: true
  kin_score: 13.7
  mcp: *id011
  name: Mondial Relay
  slug: mondial-relay
  status: profiled
  tags: *id012
  url: /providers/mondial-relay/
- agent_band: agent-ready
  agent_readiness: 48.8
  band: exemplar
  in_catalog: true
  kin_score: 68.9
  mcp: *id013
  name: Sendcloud
  slug: sendcloud
  status: profiled
  tags: *id014
  url: /providers/sendcloud/
- agent_band: agent-ready
  agent_readiness: 45.5
  band: strong
  in_catalog: true
  kin_score: 57.2
  mcp: *id015
  name: Shiprocket
  slug: shiprocket
  status: profiled
  tags: *id016
  url: /providers/shiprocket/
- agent_band: agent-aware
  agent_readiness: 21.4
  band: emerging
  in_catalog: true
  kin_score: 16.1
  mcp: *id017
  name: Starshipit
  slug: starshipit
  status: profiled
  tags: *id018
  url: /providers/starshipit/
- agent_band: agent-aware
  agent_readiness: 24.1
  band: thin
  in_catalog: true
  kin_score: 29.0
  mcp: *id019
  name: UPS
  slug: ups
  status: profiled
  tags: *id020
  url: /providers/ups/
- agent_band: agent-ready
  agent_readiness: 31.9
  band: thin
  in_catalog: true
  kin_score: 33.2
  mcp: *id021
  name: USPS
  slug: usps
  status: profiled
  tags: *id022
  url: /providers/usps/
siblings:
- name: ERPNext Shipping
  rows: 2
  url: /applications/shipping-fulfillment/erpnext-shipping/
- name: Karrio
  rows: 24
  url: /applications/shipping-fulfillment/karrio/
- name: Loop Returns
  rows: 9
  url: /applications/shipping-fulfillment/loop-returns/
- name: Sendcloud
  rows: 53
  url: /applications/shipping-fulfillment/sendcloud/
- name: Shippo
  rows: 33
  url: /applications/shipping-fulfillment/shippo/
sitemap: true
title: 'Odoo Inventory (delivery connectors): Shipping, Fulfillment & Returns reference app'
---
