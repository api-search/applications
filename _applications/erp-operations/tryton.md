---
app: Tryton
app_slug: tryton
app_url: https://github.com/tryton/tryton
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-220.20.30
  key: BC-220.20.30
  layer: domain
  name: E-Invoicing and Real-Time Reporting
  providers:
  - Chorus Pro
  - Peppyrus
  url: /capabilities/indirect-tax-management/
  via_parent: Indirect Tax Management
- attribution: Turbo EA
  id: BC-200.10
  key: general-ledger-management
  layer: domain
  name: General Ledger Management
  providers:
  - WinBooks
  url: /capabilities/general-ledger-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-140.10.10
  key: AE-140.10.10
  layer: domain
  name: Hosted Storefronts
  providers:
  - Shopify
  - Vue Storefront (Alokai)
  url: /capabilities/storefront-platforms/
  via_parent: Storefront Platforms
- attribution: API Evangelist extension
  id: AE-110.40.20
  key: AE-110.40.20
  layer: domain
  name: OCR & Document AI
  providers:
  - Eagle Doc
  - Typless
  url: /capabilities/language-document-understanding/
  via_parent: Language & Document Understanding
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: domain
  name: Payment Processing Management
  providers:
  - Braintree
  - Stripe
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-2510.20
  key: shipment-tracking-management
  layer: domain
  name: Shipment Tracking Management
  providers:
  - DPD
  - GLS (MyGLS)
  - Sendcloud
  - UPS
  url: /capabilities/shipment-tracking-management/
  via_parent: null
category:
  id: erp-operations
  name: ERP & Business Operations
  url: /applications/erp-operations/
counts:
  declared: 0
  observed: 13
credits: []
evidence:
- route: source code
  url: https://github.com/tryton/tryton/tree/default/modules
integrations:
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 52.0
    band: developing
    in_catalog: true
    kin_score: 46.2
    mcp: &id001
      status: none
    slug: braintree
    status: profiled
    tags: &id002
    - Mobile
    - Payments
    - Subscription
    - Transaction
    url: /providers/braintree/
  layer: domain
  name: Braintree
  provider: braintree
  says: ships the Braintree SDK or integration code
  source: https://github.com/tryton/tryton/tree/default/modules/account_payment_braintree
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-220.20.30
    key: BC-220.20.30
    name: E-Invoicing and Real-Time Reporting
    url: /capabilities/indirect-tax-management/
    via_parent: Indirect Tax Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 23.2
    band: emerging
    in_catalog: true
    kin_score: 14.7
    mcp: &id003
      status: unknown
    slug: chorus-pro
    status: profiled
    tags: &id004
    - Company
    - France
    - Payments
    - Public Sector
    url: /providers/chorus-pro/
  layer: domain
  name: Chorus Pro
  provider: chorus-pro
  says: ships the Chorus Pro SDK or integration code
  source: https://github.com/tryton/tryton/tree/default/modules/account_fr_chorus
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-2510.20
    key: shipment-tracking-management
    name: Shipment Tracking Management
    url: /capabilities/shipment-tracking-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 4.9
    mcp: &id005
      status: none
    slug: dpd
    status: profiled
    tags: &id006
    - Company
    - International Shipping
    - Logistics
    - Parcel Delivery
    url: /providers/dpd/
  layer: domain
  name: DPD
  provider: dpd
  says: ships the DPD SDK or integration code
  source: https://github.com/tryton/tryton/tree/default/modules/stock_package_shipping_dpd
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.40.20
    key: AE-110.40.20
    name: OCR & Document AI
    url: /capabilities/language-document-understanding/
    via_parent: Language & Document Understanding
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 22.5
    band: thin
    in_catalog: true
    kin_score: 28.1
    mcp: &id007
      status: none
    slug: eagle-doc
    status: profiled
    tags: &id008
    - Artificial Intelligence
    - Bookkeeping
    - Company
    - OCR
    url: /providers/eagle-doc/
  layer: domain
  name: Eagle Doc
  provider: eagle-doc
  says: ships the Eagle Doc SDK or integration code
  source: https://github.com/tryton/tryton/tree/default/modules/document_incoming_ocr_eagle_doc
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-2510.20
    key: shipment-tracking-management
    name: Shipment Tracking Management
    url: /capabilities/shipment-tracking-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 29.2
    band: emerging
    in_catalog: true
    kin_score: 23.5
    mcp: &id009
      status: none
    slug: gls-group
    status: profiled
    tags: &id010
    - Logistics
    - Netherlands
    - Parcel
    - Supply Chain
    url: /providers/gls-group/
  layer: domain
  name: GLS (MyGLS)
  provider: gls-group
  says: ships the GLS (MyGLS) SDK or integration code
  source: https://github.com/tryton/tryton/tree/default/modules/stock_package_shipping_mygls
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-220.20.30
    key: BC-220.20.30
    name: E-Invoicing and Real-Time Reporting
    url: /capabilities/indirect-tax-management/
    via_parent: Indirect Tax Management
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 4.3
    band: emerging
    in_catalog: true
    kin_score: 16.9
    mcp: &id011
      status: unknown
    slug: peppyrus
    status: profiled
    tags: &id012
    - Company
    - E-Invoicing
    - Free
    - PEPPOL
    url: /providers/peppyrus/
  layer: domain
  name: Peppyrus
  provider: peppyrus
  says: ships the Peppyrus SDK or integration code
  source: https://github.com/tryton/tryton/tree/default/modules/edocument_peppol_peppyrus
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-2510.20
    key: shipment-tracking-management
    name: Shipment Tracking Management
    url: /capabilities/shipment-tracking-management/
    via_parent: null
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
  says: ships the Sendcloud SDK or integration code
  source: https://github.com/tryton/tryton/tree/default/modules/stock_package_shipping_sendcloud
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-140.10.10
    key: AE-140.10.10
    name: Hosted Storefronts
    url: /capabilities/storefront-platforms/
    via_parent: Storefront Platforms
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 52.5
    band: exemplar
    in_catalog: true
    kin_score: 84.6
    mcp: &id015
      source: https://shopify.dev/docs/apps/build/devmcp
      status: verified
    slug: shopify
    status: profiled
    tags: &id016
    - Commerce
    - E-Commerce
    - Payments
    - Retail
    url: /providers/shopify/
  layer: domain
  name: Shopify
  provider: shopify
  says: ships the Shopify SDK or integration code
  source: https://github.com/tryton/tryton/tree/default/modules/web_shop_shopify
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 58.5
    band: exemplar
    in_catalog: true
    kin_score: 81.5
    mcp: &id017
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id018
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
  layer: domain
  name: Stripe
  provider: stripe
  says: ships the Stripe SDK or integration code
  source: https://github.com/tryton/tryton/tree/default/modules/account_payment_stripe
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.40.20
    key: AE-110.40.20
    name: OCR & Document AI
    url: /capabilities/language-document-understanding/
    via_parent: Language & Document Understanding
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.9
    band: emerging
    in_catalog: true
    kin_score: 12.8
    mcp: &id019
      status: none
    slug: typless
    status: profiled
    tags: &id020
    - Artificial Intelligence
    - Automation
    - Company
    - Document Processing
    url: /providers/typless/
  layer: domain
  name: Typless
  provider: typless
  says: ships the Typless SDK or integration code
  source: https://github.com/tryton/tryton/tree/default/modules/document_incoming_ocr_typless
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-2510.20
    key: shipment-tracking-management
    name: Shipment Tracking Management
    url: /capabilities/shipment-tracking-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.1
    band: thin
    in_catalog: true
    kin_score: 29.0
    mcp: &id021
      source: https://github.com/UPS-API/ups-mcp
      status: verified
    slug: ups
    status: profiled
    tags: &id022
    - Fortune 500
    - Logistics
    - Shipping
    - Supply Chain
    url: /providers/ups/
  layer: domain
  name: UPS
  provider: ups
  says: ships the UPS SDK or integration code
  source: https://github.com/tryton/tryton/tree/default/modules/stock_package_shipping_ups
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-140.10.10
    key: AE-140.10.10
    name: Hosted Storefronts
    url: /capabilities/storefront-platforms/
    via_parent: Storefront Platforms
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id023
      status: unchecked
    slug: vue-storefront
    status: queued for profiling
    tags: &id024 []
    url: null
  layer: domain
  name: Vue Storefront (Alokai)
  provider: vue-storefront
  says: ships the Vue Storefront (Alokai) SDK or integration code
  source: https://github.com/tryton/tryton/tree/default/modules/web_shop_vue_storefront
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-200.10
    key: general-ledger-management
    name: General Ledger Management
    url: /capabilities/general-ledger-management/
    via_parent: null
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id025
      status: unchecked
    slug: winbooks
    status: queued for profiling
    tags: &id026 []
    url: null
  layer: domain
  name: WinBooks
  provider: winbooks
  says: ships the WinBooks SDK or integration code
  source: https://github.com/tryton/tryton/tree/default/modules/account_export_winbooks
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/erp-operations/tryton/
providers:
- agent_band: agent-ready
  agent_readiness: 52.0
  band: developing
  in_catalog: true
  kin_score: 46.2
  mcp: *id001
  name: Braintree
  slug: braintree
  status: profiled
  tags: *id002
  url: /providers/braintree/
- agent_band: agent-aware
  agent_readiness: 23.2
  band: emerging
  in_catalog: true
  kin_score: 14.7
  mcp: *id003
  name: Chorus Pro
  slug: chorus-pro
  status: profiled
  tags: *id004
  url: /providers/chorus-pro/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 4.9
  mcp: *id005
  name: DPD
  slug: dpd
  status: profiled
  tags: *id006
  url: /providers/dpd/
- agent_band: agent-aware
  agent_readiness: 22.5
  band: thin
  in_catalog: true
  kin_score: 28.1
  mcp: *id007
  name: Eagle Doc
  slug: eagle-doc
  status: profiled
  tags: *id008
  url: /providers/eagle-doc/
- agent_band: agent-ready
  agent_readiness: 29.2
  band: emerging
  in_catalog: true
  kin_score: 23.5
  mcp: *id009
  name: GLS (MyGLS)
  slug: gls-group
  status: profiled
  tags: *id010
  url: /providers/gls-group/
- agent_band: human-only
  agent_readiness: 4.3
  band: emerging
  in_catalog: true
  kin_score: 16.9
  mcp: *id011
  name: Peppyrus
  slug: peppyrus
  status: profiled
  tags: *id012
  url: /providers/peppyrus/
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
  agent_readiness: 52.5
  band: exemplar
  in_catalog: true
  kin_score: 84.6
  mcp: *id015
  name: Shopify
  slug: shopify
  status: profiled
  tags: *id016
  url: /providers/shopify/
- agent_band: agent-native
  agent_readiness: 58.5
  band: exemplar
  in_catalog: true
  kin_score: 81.5
  mcp: *id017
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id018
  url: /providers/stripe/
- agent_band: human-only
  agent_readiness: 2.9
  band: emerging
  in_catalog: true
  kin_score: 12.8
  mcp: *id019
  name: Typless
  slug: typless
  status: profiled
  tags: *id020
  url: /providers/typless/
- agent_band: agent-aware
  agent_readiness: 24.1
  band: thin
  in_catalog: true
  kin_score: 29.0
  mcp: *id021
  name: UPS
  slug: ups
  status: profiled
  tags: *id022
  url: /providers/ups/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id023
  name: Vue Storefront (Alokai)
  slug: vue-storefront
  status: queued for profiling
  tags: *id024
  url: null
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id025
  name: WinBooks
  slug: winbooks
  status: queued for profiling
  tags: *id026
  url: null
siblings:
- name: Dolibarr
  rows: 13
  url: /applications/erp-operations/dolibarr/
- name: ERPNext
  rows: 24
  url: /applications/erp-operations/erpnext/
- name: Fishbowl
  rows: 42
  url: /applications/erp-operations/fishbowl/
- name: Katana
  rows: 19
  url: /applications/erp-operations/katana/
- name: Odoo
  rows: 45
  url: /applications/erp-operations/odoo/
sitemap: true
title: 'Tryton: ERP & Business Operations reference app'
---
