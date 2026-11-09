---
app: Lightspeed Restaurant
app_slug: lightspeed-restaurant
app_url: https://www.lightspeedhq.com/pos/restaurant/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-140.100.20
  key: AE-140.100.20
  layer: domain
  name: Food Delivery
  providers:
  - Deliveroo
  - DoorDash
  - Uber Eats
  url: /capabilities/quick-local-commerce/
  via_parent: Quick & Local Commerce
- attribution: Turbo EA
  id: BC-420.40
  key: loyalty-retention-management
  layer: domain
  name: Loyalty & Retention Management
  providers:
  - Marsello
  url: /capabilities/loyalty-retention-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-140.20.20
  key: AE-140.20.20
  layer: domain
  name: Online Ordering
  providers:
  - me&u
  - Mr Yum
  url: /capabilities/cart-checkout/
  via_parent: Cart & Checkout
- attribution: Turbo EA
  id: BC-2320.50.40
  key: BC-2320.50.40
  layer: domain
  name: POS Peripheral Configuration
  providers:
  - Epson (receipt/kitchen printers)
  url: /capabilities/pos-configuration-management/
  via_parent: POS Configuration Management
- attribution: API Evangelist extension
  id: AE-140.30.30
  key: AE-140.30.30
  layer: domain
  name: QR & Contactless Payments
  providers:
  - Alipay (Ant Group)
  - WeChat Pay
  url: /capabilities/consumer-payment-options/
  via_parent: Consumer Payment Options
- attribution: Turbo EA
  id: BC-2320.20
  key: tender-and-payment-acceptance-management
  layer: domain
  name: Tender and Payment Acceptance Management
  providers:
  - Westpac Presto Smart
  url: /capabilities/tender-and-payment-acceptance-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-200.10
  key: general-ledger-management
  layer: common
  name: General Ledger Management
  providers:
  - MYOB
  - QuickBooks
  - Sage
  - Xero
  url: /capabilities/general-ledger-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-2310.30.20
  key: BC-2310.30.20
  layer: common
  name: Store Shift Scheduling
  providers:
  - Deputy
  - Tanda
  url: /capabilities/store-workforce-management/
  via_parent: Store Workforce Management
category:
  id: point-of-sale
  name: Point of Sale & In-Person Payments
  url: /applications/point-of-sale/
counts:
  declared: 16
  observed: 0
credits: []
evidence:
- route: documentation
  url: https://www.lightspeedhq.com/au/blog/must-have-pos-integrations-for-hospitality/
- route: integrations page
  url: https://www.lightspeedhq.com/pos/restaurant/accounting/
- route: integrations page
  url: https://www.lightspeedhq.com/pos/retail/integrations/
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-140.30.30
    key: AE-140.30.30
    name: QR & Contactless Payments
    url: /capabilities/consumer-payment-options/
    via_parent: Consumer Payment Options
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 18.0
    band: emerging
    in_catalog: true
    kin_score: 25.6
    mcp: &id001
      source: https://github.com/alipay/global-alipayplus-mcp
      status: verified
    slug: ant-group
    status: profiled
    tags: &id002
    - Company
    - Fintech
    - Payments
    - Technology
    url: /providers/ant-group/
  layer: domain
  name: Alipay (Ant Group)
  provider: ant-group
  says: lists Alipay (Ant Group) as an integration
  source: https://www.lightspeedhq.com/au/blog/must-have-pos-integrations-for-hospitality/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.100.20
    key: AE-140.100.20
    name: Food Delivery
    url: /capabilities/quick-local-commerce/
    via_parent: Quick & Local Commerce
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.7
    band: thin
    in_catalog: true
    kin_score: 33.3
    mcp: &id003
      status: none
    slug: deliveroo
    status: profiled
    tags: &id004
    - Food Delivery
    - Grocery
    - Logistics
    - Marketplace
    url: /providers/deliveroo/
  layer: domain
  name: Deliveroo
  provider: deliveroo
  says: lists Deliveroo as an integration
  source: https://www.lightspeedhq.com/au/blog/must-have-pos-integrations-for-hospitality/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2310.30.20
    key: BC-2310.30.20
    name: Store Shift Scheduling
    url: /capabilities/store-workforce-management/
    via_parent: Store Workforce Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 34.4
    band: strong
    in_catalog: true
    kin_score: 66.2
    mcp: &id005
      status: none
    slug: deputy
    status: profiled
    tags: &id006
    - Employee Scheduling
    - Time and Attendance
    - Timesheets
    - Workforce Management
    url: /providers/deputy/
  layer: common
  name: Deputy
  provider: deputy
  says: lists Deputy as an integration
  source: https://www.lightspeedhq.com/au/blog/must-have-pos-integrations-for-hospitality/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.100.20
    key: AE-140.100.20
    name: Food Delivery
    url: /capabilities/quick-local-commerce/
    via_parent: Quick & Local Commerce
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 35.5
    band: exemplar
    in_catalog: true
    kin_score: 77.8
    mcp: &id007
      status: none
    slug: doordash
    status: profiled
    tags: &id008
    - Delivery
    - Last Mile Delivery
    - Logistics
    - On-Demand
    url: /providers/doordash/
  layer: domain
  name: DoorDash
  provider: doordash
  says: lists DoorDash as an integration
  source: https://www.lightspeedhq.com/au/blog/must-have-pos-integrations-for-hospitality/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2320.50.40
    key: BC-2320.50.40
    name: POS Peripheral Configuration
    url: /capabilities/pos-configuration-management/
    via_parent: POS Configuration Management
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 7.0
    mcp: &id009
      status: unknown
    slug: epson
    status: profiled
    tags: &id010
    - Automation
    - Company
    - Imaging
    - Printing
    url: /providers/epson/
  layer: domain
  name: Epson (receipt/kitchen printers)
  provider: epson
  says: lists Epson (receipt/kitchen printers) as an integration
  source: https://www.lightspeedhq.com/au/blog/must-have-pos-integrations-for-hospitality/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-420.40
    key: loyalty-retention-management
    name: Loyalty & Retention Management
    url: /capabilities/loyalty-retention-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 9.3
    band: thin
    in_catalog: true
    kin_score: 38.7
    mcp: &id011
      status: unknown
    slug: marsello
    status: profiled
    tags: &id012
    - Company
    - Loyalty
    - Marketing
    - Retail
    url: /providers/marsello/
  layer: domain
  name: Marsello
  provider: marsello
  says: lists Marsello as an integration
  source: https://www.lightspeedhq.com/au/blog/must-have-pos-integrations-for-hospitality/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.20.20
    key: AE-140.20.20
    name: Online Ordering
    url: /capabilities/cart-checkout/
    via_parent: Cart & Checkout
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 15.9
    mcp: &id013
      status: unknown
    slug: meandu
    status: profiled
    tags: &id014
    - Company
    - Hospitality
    - Payments
    - Software-as-a-Service
    url: /providers/meandu/
  layer: domain
  name: me&u
  provider: meandu
  says: lists me&u as an integration
  source: https://www.lightspeedhq.com/au/blog/must-have-pos-integrations-for-hospitality/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.20.20
    key: AE-140.20.20
    name: Online Ordering
    url: /capabilities/cart-checkout/
    via_parent: Cart & Checkout
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 5.6
    mcp: &id015
      status: none
    slug: mr-yum
    status: profiled
    tags: &id016
    - Hospitality
    - Ordering
    - RestaurantTech
    - Software-as-a-Service
    url: /providers/mr-yum/
  layer: domain
  name: Mr Yum
  provider: mr-yum
  says: lists Mr Yum as an integration
  source: https://www.lightspeedhq.com/au/blog/must-have-pos-integrations-for-hospitality/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-200.10
    key: general-ledger-management
    name: General Ledger Management
    url: /capabilities/general-ledger-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 15.4
    band: emerging
    in_catalog: true
    kin_score: 23.3
    mcp: &id017
      status: none
    slug: myob
    status: profiled
    tags: &id018
    - Accounting
    - Bills
    - Business Management
    - Invoices
    url: /providers/myob/
  layer: common
  name: MYOB
  provider: myob
  says: lists MYOB as an integration
  source: https://www.lightspeedhq.com/au/blog/must-have-pos-integrations-for-hospitality/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-200.10
    key: general-ledger-management
    name: General Ledger Management
    url: /capabilities/general-ledger-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 41.2
    band: strong
    in_catalog: true
    kin_score: 61.1
    mcp: &id019
      source: https://github.com/intuit/quickbooks-online-mcp-server
      status: verified
    slug: quickbooks
    status: profiled
    tags: &id020
    - Accounting
    - Bookkeeping
    - Finance
    - Small Business
    url: /providers/quickbooks/
  layer: common
  name: QuickBooks
  provider: quickbooks
  says: lists QuickBooks as an integration
  source: https://www.lightspeedhq.com/pos/restaurant/accounting/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-200.10
    key: general-ledger-management
    name: General Ledger Management
    url: /capabilities/general-ledger-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.3
    band: developing
    in_catalog: true
    kin_score: 41.8
    mcp: &id021
      status: none
    slug: sage
    status: profiled
    tags: &id022
    - Accounting
    - Business Management
    - Cloud Software
    - ERP
    url: /providers/sage/
  layer: common
  name: Sage
  provider: sage
  says: lists Sage as an integration
  source: https://www.lightspeedhq.com/pos/restaurant/accounting/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2310.30.20
    key: BC-2310.30.20
    name: Store Shift Scheduling
    url: /capabilities/store-workforce-management/
    via_parent: Store Workforce Management
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 12.9
    mcp: &id023
      status: none
    slug: tanda
    status: profiled
    tags: &id024
    - Company
    - Human Resources
    - Payroll
    - Workforce Management
    url: /providers/tanda/
  layer: common
  name: Tanda
  provider: tanda
  says: lists Tanda as an integration
  source: https://www.lightspeedhq.com/au/blog/must-have-pos-integrations-for-hospitality/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.100.20
    key: AE-140.100.20
    name: Food Delivery
    url: /capabilities/quick-local-commerce/
    via_parent: Quick & Local Commerce
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.8
    band: developing
    in_catalog: true
    kin_score: 46.9
    mcp: &id025
      status: none
    slug: uber-eats
    status: profiled
    tags: &id026
    - Food Delivery
    - Last Mile Delivery
    - Uber Direct
    - Uber Eats
    url: /providers/uber-eats/
  layer: domain
  name: Uber Eats
  provider: uber-eats
  says: lists Uber Eats as an integration
  source: https://www.lightspeedhq.com/au/blog/must-have-pos-integrations-for-hospitality/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.30.30
    key: AE-140.30.30
    name: QR & Contactless Payments
    url: /capabilities/consumer-payment-options/
    via_parent: Consumer Payment Options
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.2
    band: developing
    in_catalog: true
    kin_score: 50.5
    mcp: &id027
      status: none
    slug: wechat
    status: profiled
    tags: &id028
    - Messaging
    - Mini Programs
    - Payments
    - Social
    url: /providers/wechat/
  layer: domain
  name: WeChat Pay
  provider: wechat
  says: lists WeChat Pay as an integration
  source: https://www.lightspeedhq.com/au/blog/must-have-pos-integrations-for-hospitality/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2320.20
    key: tender-and-payment-acceptance-management
    name: Tender and Payment Acceptance Management
    url: /capabilities/tender-and-payment-acceptance-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.2
    band: strong
    in_catalog: true
    kin_score: 59.6
    mcp: &id029
      status: none
    slug: westpac
    status: profiled
    tags: &id030
    - Banks
    - CDR
    - Finance
    - Open Banking
    url: /providers/westpac/
  layer: domain
  name: Westpac Presto Smart
  provider: westpac
  says: lists Westpac Presto Smart as an integration
  source: https://www.lightspeedhq.com/au/blog/must-have-pos-integrations-for-hospitality/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-200.10
    key: general-ledger-management
    name: General Ledger Management
    url: /capabilities/general-ledger-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 61.3
    band: exemplar
    in_catalog: true
    kin_score: 82.4
    mcp: &id031
      source: https://github.com/XeroAPI/xero-mcp-server
      status: verified
    slug: xero
    status: profiled
    tags: &id032
    - Accounting
    - Bank Feeds
    - Finance
    - Financial Services
    url: /providers/xero/
  layer: common
  name: Xero
  provider: xero
  says: lists Xero as an integration
  source: https://www.lightspeedhq.com/pos/restaurant/accounting/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/point-of-sale/lightspeed-restaurant/
providers:
- agent_band: agent-aware
  agent_readiness: 18.0
  band: emerging
  in_catalog: true
  kin_score: 25.6
  mcp: *id001
  name: Alipay (Ant Group)
  slug: ant-group
  status: profiled
  tags: *id002
  url: /providers/ant-group/
- agent_band: agent-aware
  agent_readiness: 24.7
  band: thin
  in_catalog: true
  kin_score: 33.3
  mcp: *id003
  name: Deliveroo
  slug: deliveroo
  status: profiled
  tags: *id004
  url: /providers/deliveroo/
- agent_band: agent-ready
  agent_readiness: 34.4
  band: strong
  in_catalog: true
  kin_score: 66.2
  mcp: *id005
  name: Deputy
  slug: deputy
  status: profiled
  tags: *id006
  url: /providers/deputy/
- agent_band: agent-ready
  agent_readiness: 35.5
  band: exemplar
  in_catalog: true
  kin_score: 77.8
  mcp: *id007
  name: DoorDash
  slug: doordash
  status: profiled
  tags: *id008
  url: /providers/doordash/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 7.0
  mcp: *id009
  name: Epson (receipt/kitchen printers)
  slug: epson
  status: profiled
  tags: *id010
  url: /providers/epson/
- agent_band: agent-aware
  agent_readiness: 9.3
  band: thin
  in_catalog: true
  kin_score: 38.7
  mcp: *id011
  name: Marsello
  slug: marsello
  status: profiled
  tags: *id012
  url: /providers/marsello/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 15.9
  mcp: *id013
  name: me&u
  slug: meandu
  status: profiled
  tags: *id014
  url: /providers/meandu/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 5.6
  mcp: *id015
  name: Mr Yum
  slug: mr-yum
  status: profiled
  tags: *id016
  url: /providers/mr-yum/
- agent_band: agent-aware
  agent_readiness: 15.4
  band: emerging
  in_catalog: true
  kin_score: 23.3
  mcp: *id017
  name: MYOB
  slug: myob
  status: profiled
  tags: *id018
  url: /providers/myob/
- agent_band: agent-native
  agent_readiness: 41.2
  band: strong
  in_catalog: true
  kin_score: 61.1
  mcp: *id019
  name: QuickBooks
  slug: quickbooks
  status: profiled
  tags: *id020
  url: /providers/quickbooks/
- agent_band: agent-ready
  agent_readiness: 31.3
  band: developing
  in_catalog: true
  kin_score: 41.8
  mcp: *id021
  name: Sage
  slug: sage
  status: profiled
  tags: *id022
  url: /providers/sage/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 12.9
  mcp: *id023
  name: Tanda
  slug: tanda
  status: profiled
  tags: *id024
  url: /providers/tanda/
- agent_band: agent-ready
  agent_readiness: 31.8
  band: developing
  in_catalog: true
  kin_score: 46.9
  mcp: *id025
  name: Uber Eats
  slug: uber-eats
  status: profiled
  tags: *id026
  url: /providers/uber-eats/
- agent_band: agent-aware
  agent_readiness: 24.2
  band: developing
  in_catalog: true
  kin_score: 50.5
  mcp: *id027
  name: WeChat Pay
  slug: wechat
  status: profiled
  tags: *id028
  url: /providers/wechat/
- agent_band: agent-ready
  agent_readiness: 31.2
  band: strong
  in_catalog: true
  kin_score: 59.6
  mcp: *id029
  name: Westpac Presto Smart
  slug: westpac
  status: profiled
  tags: *id030
  url: /providers/westpac/
- agent_band: agent-native
  agent_readiness: 61.3
  band: exemplar
  in_catalog: true
  kin_score: 82.4
  mcp: *id031
  name: Xero
  slug: xero
  status: profiled
  tags: *id032
  url: /providers/xero/
siblings:
- name: Loyverse POS
  rows: 33
  url: /applications/point-of-sale/loyverse-pos/
- name: NexoPOS
  rows: 2
  url: /applications/point-of-sale/nexopos/
- name: Odoo Point of Sale
  rows: 16
  url: /applications/point-of-sale/odoo-point-of-sale/
- name: Open Source Point of Sale
  rows: 3
  url: /applications/point-of-sale/open-source-point-of-sale/
- name: Square Point of Sale
  rows: 28
  url: /applications/point-of-sale/square-point-of-sale/
sitemap: true
title: 'Lightspeed Restaurant: Point of Sale & In-Person Payments reference app'
---
