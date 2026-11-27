---
app: Odoo Point of Sale
app_slug: odoo-point-of-sale
app_url: https://github.com/odoo/odoo
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-2320.40.10
  key: BC-2320.40.10
  layer: domain
  name: Cash Drawer Management
  providers:
  - CashDro
  - Cashmatic
  - Glory (cash recyclers)
  url: /capabilities/pos-cash-and-tender-handling/
  via_parent: POS Cash and Tender Handling
- attribution: Turbo EA
  id: BC-2320.50.40
  key: BC-2320.50.40
  layer: domain
  name: POS Peripheral Configuration
  providers:
  - iMin
  url: /capabilities/pos-configuration-management/
  via_parent: POS Configuration Management
- attribution: API Evangelist extension
  id: AE-140.30.30
  key: AE-140.30.30
  layer: domain
  name: QR & Contactless Payments
  providers:
  - Bancontact Payconiq
  url: /capabilities/consumer-payment-options/
  via_parent: Consumer Payment Options
- attribution: Turbo EA
  id: BC-2320.20
  key: tender-and-payment-acceptance-management
  layer: domain
  name: Tender and Payment Acceptance Management
  providers:
  - Adyen
  - DPO Pay
  - M-Pesa (Safaricom)
  - Mercado Pago
  - Mollie
  - Pine Labs
  - QFPay
  - Razorpay
  - Stripe
  - SumUp
  - Viva.com (Viva Wallet)
  url: /capabilities/tender-and-payment-acceptance-management/
  via_parent: null
category:
  id: point-of-sale
  name: Point of Sale & In-Person Payments
  url: /applications/point-of-sale/
counts:
  declared: 0
  observed: 16
credits: []
evidence:
- route: source code
  url: https://github.com/odoo/odoo/tree/master/addons
integrations:
- capability:
    attribution: Turbo EA
    id: BC-2320.20
    key: tender-and-payment-acceptance-management
    name: Tender and Payment Acceptance Management
    url: /capabilities/tender-and-payment-acceptance-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 42.8
    band: exemplar
    in_catalog: true
    kin_score: 73.6
    mcp: &id001
      source: https://github.com/Adyen/adyen-mcp
      status: verified
    slug: adyen
    status: profiled
    tags: &id002
    - Agentic Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/adyen/
  layer: domain
  name: Adyen
  provider: adyen
  says: ships the Adyen SDK or integration code
  source: https://github.com/odoo/odoo/tree/master/addons
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-140.30.30
    key: AE-140.30.30
    name: QR & Contactless Payments
    url: /capabilities/consumer-payment-options/
    via_parent: Consumer Payment Options
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 49.8
    band: strong
    in_catalog: true
    kin_score: 62.1
    mcp: &id003
      status: none
    slug: bancontact
    status: profiled
    tags: &id004
    - Banking
    - Belgium
    - Debit Cards
    - E-Commerce
    url: /providers/bancontact/
  layer: domain
  name: Bancontact Payconiq
  provider: bancontact
  says: ships the Bancontact Payconiq SDK or integration code
  source: https://github.com/odoo/odoo/tree/master/addons
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-2320.40.10
    key: BC-2320.40.10
    name: Cash Drawer Management
    url: /capabilities/pos-cash-and-tender-handling/
    via_parent: POS Cash and Tender Handling
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 8.7
    mcp: &id005
      status: unknown
    slug: cashdro
    status: profiled
    tags: &id006
    - Cash Management
    - Company
    - Fintech
    - Retail
    url: /providers/cashdro/
  layer: domain
  name: CashDro
  provider: cashdro
  says: ships the CashDro SDK or integration code
  source: https://github.com/odoo/odoo/tree/master/addons
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-2320.40.10
    key: BC-2320.40.10
    name: Cash Drawer Management
    url: /capabilities/pos-cash-and-tender-handling/
    via_parent: POS Cash and Tender Handling
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 18.3
    band: minimal
    in_catalog: true
    kin_score: 3.4
    mcp: &id007
      status: unknown
    slug: cashmatic
    status: profiled
    tags: &id008
    - Automation
    - Company
    - Payments
    - Retail
    url: /providers/cashmatic/
  layer: domain
  name: Cashmatic
  provider: cashmatic
  says: ships the Cashmatic SDK or integration code
  source: https://github.com/odoo/odoo/tree/master/addons
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-2320.20
    key: tender-and-payment-acceptance-management
    name: Tender and Payment Acceptance Management
    url: /capabilities/tender-and-payment-acceptance-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 5.6
    band: emerging
    in_catalog: true
    kin_score: 22.6
    mcp: &id009
      status: none
    slug: dpo-pay
    status: profiled
    tags: &id010
    - Africa
    - Company
    - Fintech
    - Payments
    url: /providers/dpo-pay/
  layer: domain
  name: DPO Pay
  provider: dpo-pay
  says: ships the DPO Pay SDK or integration code
  source: https://github.com/odoo/odoo/tree/master/addons
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-2320.40.10
    key: BC-2320.40.10
    name: Cash Drawer Management
    url: /capabilities/pos-cash-and-tender-handling/
    via_parent: POS Cash and Tender Handling
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 12.7
    mcp: &id011
      status: unknown
    slug: glory-global-solutions
    status: profiled
    tags: &id012
    - CashAutomation
    - Company
    - Financial Services
    - Retail Tech
    url: /providers/glory-global-solutions/
  layer: domain
  name: Glory (cash recyclers)
  provider: glory-global-solutions
  says: ships the Glory (cash recyclers) SDK or integration code
  source: https://github.com/odoo/odoo/tree/master/addons
  tier: observed
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
    kin_score: 1.3
    mcp: &id013
      status: unknown
    slug: imin
    status: profiled
    tags: &id014
    - Company
    url: /providers/imin/
  layer: domain
  name: iMin
  provider: imin
  says: ships the iMin SDK or integration code
  source: https://github.com/odoo/odoo/tree/master/addons
  tier: observed
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
    agent_readiness: 28.6
    band: developing
    in_catalog: true
    kin_score: 48.0
    mcp: &id015
      status: none
    slug: mpesa
    status: profiled
    tags: &id016
    - Fintech
    - Kenya
    - Mobile Money
    - Payments
    url: /providers/mpesa/
  layer: domain
  name: M-Pesa (Safaricom)
  provider: mpesa
  says: ships the M-Pesa (Safaricom) SDK or integration code
  source: https://github.com/odoo/odoo/tree/master/addons
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-2320.20
    key: tender-and-payment-acceptance-management
    name: Tender and Payment Acceptance Management
    url: /capabilities/tender-and-payment-acceptance-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.9
    band: developing
    in_catalog: true
    kin_score: 40.4
    mcp: &id017
      source: https://www.mercadopago.com.br/developers/en/docs/mcp-server/overview
      status: verified
    slug: mercado-pago
    status: profiled
    tags: &id018
    - Checkout
    - Payments
    - Point-of-Sale
    - Subscription
    url: /providers/mercado-pago/
  layer: domain
  name: Mercado Pago
  provider: mercado-pago
  says: ships the Mercado Pago SDK or integration code
  source: https://github.com/odoo/odoo/tree/master/addons
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-2320.20
    key: tender-and-payment-acceptance-management
    name: Tender and Payment Acceptance Management
    url: /capabilities/tender-and-payment-acceptance-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 71.7
    band: exemplar
    in_catalog: true
    kin_score: 68.1
    mcp: &id019
      source: https://docs.mollie.com/docs/mcp-server
      status: verified
    slug: mollie
    status: profiled
    tags: &id020
    - Company
    - Financial Services
    - Fintech
    - Payments
    url: /providers/mollie/
  layer: domain
  name: Mollie
  provider: mollie
  says: ships the Mollie SDK or integration code
  source: https://github.com/odoo/odoo/tree/master/addons
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-2320.20
    key: tender-and-payment-acceptance-management
    name: Tender and Payment Acceptance Management
    url: /capabilities/tender-and-payment-acceptance-management/
    via_parent: null
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id021
      status: unchecked
    slug: pine-labs
    status: queued for profiling
    tags: &id022 []
    url: null
  layer: domain
  name: Pine Labs
  provider: pine-labs
  says: ships the Pine Labs SDK or integration code
  source: https://github.com/odoo/odoo/tree/master/addons
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-2320.20
    key: tender-and-payment-acceptance-management
    name: Tender and Payment Acceptance Management
    url: /capabilities/tender-and-payment-acceptance-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.4
    band: minimal
    in_catalog: true
    kin_score: 9.9
    mcp: &id023
      status: none
    slug: qfpay
    status: profiled
    tags: &id024
    - Company
    - Fintech
    - Payments
    url: /providers/qfpay/
  layer: domain
  name: QFPay
  provider: qfpay
  says: ships the QFPay SDK or integration code
  source: https://github.com/odoo/odoo/tree/master/addons
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-2320.20
    key: tender-and-payment-acceptance-management
    name: Tender and Payment Acceptance Management
    url: /capabilities/tender-and-payment-acceptance-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 27.7
    band: developing
    in_catalog: true
    kin_score: 50.6
    mcp: &id025
      source: https://github.com/razorpay/razorpay-mcp-server
      status: verified
    slug: razorpay
    status: profiled
    tags: &id026
    - Fintech
    - India
    - Payment Gateway
    - Payments
    url: /providers/razorpay/
  layer: domain
  name: Razorpay
  provider: razorpay
  says: ships the Razorpay SDK or integration code
  source: https://github.com/odoo/odoo/tree/master/addons
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-2320.20
    key: tender-and-payment-acceptance-management
    name: Tender and Payment Acceptance Management
    url: /capabilities/tender-and-payment-acceptance-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 57.6
    band: exemplar
    in_catalog: true
    kin_score: 82.0
    mcp: &id027
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id028
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
  layer: domain
  name: Stripe
  provider: stripe
  says: ships the Stripe SDK or integration code
  source: https://github.com/odoo/odoo/tree/master/addons
  tier: observed
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
    agent_readiness: 53.2
    band: developing
    in_catalog: true
    kin_score: 44.0
    mcp: &id029
      source: https://github.com/sumup/sumup-mcp
      status: verified
    slug: sumup
    status: profiled
    tags: &id030
    - Card Reader
    - Checkout
    - Payments
    - Point-of-Sale
    url: /providers/sumup/
  layer: domain
  name: SumUp
  provider: sumup
  says: ships the SumUp SDK or integration code
  source: https://github.com/odoo/odoo/tree/master/addons
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-2320.20
    key: tender-and-payment-acceptance-management
    name: Tender and Payment Acceptance Management
    url: /capabilities/tender-and-payment-acceptance-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 11.8
    mcp: &id031
      status: none
    slug: viva-com
    status: profiled
    tags: &id032
    - Banking
    - Europe
    - Fintech
    - Payments
    url: /providers/viva-com/
  layer: domain
  name: Viva.com (Viva Wallet)
  provider: viva-com
  says: ships the Viva.com (Viva Wallet) SDK or integration code
  source: https://github.com/odoo/odoo/tree/master/addons
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/point-of-sale/odoo-point-of-sale/
providers:
- agent_band: agent-native
  agent_readiness: 42.8
  band: exemplar
  in_catalog: true
  kin_score: 73.6
  mcp: *id001
  name: Adyen
  slug: adyen
  status: profiled
  tags: *id002
  url: /providers/adyen/
- agent_band: agent-native
  agent_readiness: 49.8
  band: strong
  in_catalog: true
  kin_score: 62.1
  mcp: *id003
  name: Bancontact Payconiq
  slug: bancontact
  status: profiled
  tags: *id004
  url: /providers/bancontact/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 8.7
  mcp: *id005
  name: CashDro
  slug: cashdro
  status: profiled
  tags: *id006
  url: /providers/cashdro/
- agent_band: agent-aware
  agent_readiness: 18.3
  band: minimal
  in_catalog: true
  kin_score: 3.4
  mcp: *id007
  name: Cashmatic
  slug: cashmatic
  status: profiled
  tags: *id008
  url: /providers/cashmatic/
- agent_band: agent-aware
  agent_readiness: 5.6
  band: emerging
  in_catalog: true
  kin_score: 22.6
  mcp: *id009
  name: DPO Pay
  slug: dpo-pay
  status: profiled
  tags: *id010
  url: /providers/dpo-pay/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 12.7
  mcp: *id011
  name: Glory (cash recyclers)
  slug: glory-global-solutions
  status: profiled
  tags: *id012
  url: /providers/glory-global-solutions/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 1.3
  mcp: *id013
  name: iMin
  slug: imin
  status: profiled
  tags: *id014
  url: /providers/imin/
- agent_band: agent-ready
  agent_readiness: 28.6
  band: developing
  in_catalog: true
  kin_score: 48.0
  mcp: *id015
  name: M-Pesa (Safaricom)
  slug: mpesa
  status: profiled
  tags: *id016
  url: /providers/mpesa/
- agent_band: agent-aware
  agent_readiness: 24.9
  band: developing
  in_catalog: true
  kin_score: 40.4
  mcp: *id017
  name: Mercado Pago
  slug: mercado-pago
  status: profiled
  tags: *id018
  url: /providers/mercado-pago/
- agent_band: agent-native
  agent_readiness: 71.7
  band: exemplar
  in_catalog: true
  kin_score: 68.1
  mcp: *id019
  name: Mollie
  slug: mollie
  status: profiled
  tags: *id020
  url: /providers/mollie/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id021
  name: Pine Labs
  slug: pine-labs
  status: queued for profiling
  tags: *id022
  url: null
- agent_band: human-only
  agent_readiness: 3.4
  band: minimal
  in_catalog: true
  kin_score: 9.9
  mcp: *id023
  name: QFPay
  slug: qfpay
  status: profiled
  tags: *id024
  url: /providers/qfpay/
- agent_band: agent-aware
  agent_readiness: 27.7
  band: developing
  in_catalog: true
  kin_score: 50.6
  mcp: *id025
  name: Razorpay
  slug: razorpay
  status: profiled
  tags: *id026
  url: /providers/razorpay/
- agent_band: agent-native
  agent_readiness: 57.6
  band: exemplar
  in_catalog: true
  kin_score: 82.0
  mcp: *id027
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id028
  url: /providers/stripe/
- agent_band: agent-ready
  agent_readiness: 53.2
  band: developing
  in_catalog: true
  kin_score: 44.0
  mcp: *id029
  name: SumUp
  slug: sumup
  status: profiled
  tags: *id030
  url: /providers/sumup/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 11.8
  mcp: *id031
  name: Viva.com (Viva Wallet)
  slug: viva-com
  status: profiled
  tags: *id032
  url: /providers/viva-com/
siblings:
- name: Lightspeed Restaurant
  rows: 16
  url: /applications/point-of-sale/lightspeed-restaurant/
- name: Loyverse POS
  rows: 33
  url: /applications/point-of-sale/loyverse-pos/
- name: NexoPOS
  rows: 2
  url: /applications/point-of-sale/nexopos/
- name: Open Source Point of Sale
  rows: 3
  url: /applications/point-of-sale/open-source-point-of-sale/
- name: Square Point of Sale
  rows: 28
  url: /applications/point-of-sale/square-point-of-sale/
sitemap: true
title: 'Odoo Point of Sale: Point of Sale & In-Person Payments reference app'
---
