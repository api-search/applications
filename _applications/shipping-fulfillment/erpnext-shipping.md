---
app: ERPNext Shipping
app_slug: erpnext-shipping
app_url: https://github.com/frappe/erpnext-shipping
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-929
  key: AE-929
  layer: domain
  name: Multi-Carrier Shipping Platforms
  providers:
  - LetMeShip
  - Sendcloud
  url: /capabilities/logistics-operations-management/
  via_parent: Logistics Operations Management
category:
  id: shipping-fulfillment
  name: Shipping, Fulfillment & Returns
  url: /applications/shipping-fulfillment/
counts:
  declared: 0
  observed: 2
credits: []
evidence:
- route: documentation
  url: https://github.com/frappe/erpnext-shipping/blob/develop/README.md
- route: source code
  url: https://github.com/frappe/erpnext-shipping/tree/develop/erpnext_shipping/erpnext_shipping/doctype
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-929
    key: AE-929
    name: Multi-Carrier Shipping Platforms
    url: /capabilities/logistics-operations-management/
    via_parent: Logistics Operations Management
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 20.6
    mcp: &id001
      status: none
    slug: letmeship
    status: profiled
    tags: &id002
    - B2B
    - Europe
    - Logistics
    - Shipping
    url: /providers/letmeship/
  layer: domain
  name: LetMeShip
  provider: letmeship
  says: ships the LetMeShip SDK or integration code
  source: https://github.com/frappe/erpnext-shipping/tree/develop/erpnext_shipping/erpnext_shipping/doctype
  tier: observed
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
    agent_readiness: 48.2
    band: strong
    in_catalog: true
    kin_score: 65.6
    mcp: &id003
      status: none
    slug: sendcloud
    status: profiled
    tags: &id004
    - Carrier
    - E-Commerce
    - Logistics
    - Shipping
    url: /providers/sendcloud/
  layer: domain
  name: Sendcloud
  provider: sendcloud
  says: ships the Sendcloud SDK or integration code
  source: https://github.com/frappe/erpnext-shipping/tree/develop/erpnext_shipping/erpnext_shipping/doctype
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/shipping-fulfillment/erpnext-shipping/
providers:
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 20.6
  mcp: *id001
  name: LetMeShip
  slug: letmeship
  status: profiled
  tags: *id002
  url: /providers/letmeship/
- agent_band: agent-ready
  agent_readiness: 48.2
  band: strong
  in_catalog: true
  kin_score: 65.6
  mcp: *id003
  name: Sendcloud
  slug: sendcloud
  status: profiled
  tags: *id004
  url: /providers/sendcloud/
siblings:
- name: Karrio
  rows: 24
  url: /applications/shipping-fulfillment/karrio/
- name: Loop Returns
  rows: 9
  url: /applications/shipping-fulfillment/loop-returns/
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
title: 'ERPNext Shipping: Shipping, Fulfillment & Returns reference app'
---
