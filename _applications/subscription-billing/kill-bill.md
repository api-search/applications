---
app: Kill Bill
app_slug: kill-bill
app_url: https://github.com/killbill/killbill
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-220.20
  key: indirect-tax-management
  layer: domain
  name: Indirect Tax Management
  providers:
  - Avalara (AvaTax)
  - Kintsugi
  - Vertex (tax)
  url: /capabilities/indirect-tax-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-1400.30
  key: fraud-detection-investigation-management
  layer: common
  name: Fraud Detection & Investigation Management
  providers:
  - Accertify
  url: /capabilities/fraud-detection-investigation-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: common
  name: Payment Processing Management
  providers:
  - Adyen
  - Braintree
  - Chase (Orbital / Paymentech)
  - CyberSource
  - Dwolla
  - Forte
  - GoCardless
  - PayPal
  - Qualpay
  - SecureNet
  - Stripe
  url: /capabilities/payment-processing-management/
  via_parent: null
category:
  id: subscription-billing
  name: Subscription Billing & Payments Ops
  url: /applications/subscription-billing/
counts:
  declared: 15
  observed: 0
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/killbill/killbill/master/pom.xml
- route: documentation
  url: https://killbill.io/plugins/
- route: source code
  url: https://raw.githubusercontent.com/killbill/killbill-cloud/master/kpm/lib/kpm/plugins_directory.yml
integrations:
- capability:
    attribution: Turbo EA
    id: BC-1400.30
    key: fraud-detection-investigation-management
    name: Fraud Detection & Investigation Management
    url: /capabilities/fraud-detection-investigation-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 6.0
    mcp: &id001
      status: unknown
    slug: accertify
    status: profiled
    tags: &id002
    - Company
    - Fraud Prevention
    - Payments
    - Risk Management
    url: /providers/accertify/
  layer: common
  name: Accertify
  provider: accertify
  says: lists Accertify as an integration
  source: https://raw.githubusercontent.com/killbill/killbill-cloud/master/kpm/lib/kpm/plugins_directory.yml
  tier: declared
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
    agent_readiness: 43.7
    band: exemplar
    in_catalog: true
    kin_score: 68.8
    mcp: &id003
      source: https://github.com/Adyen/adyen-mcp
      status: verified
    slug: adyen
    status: profiled
    tags: &id004
    - Agentic Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/adyen/
  layer: common
  name: Adyen
  provider: adyen
  says: lists Adyen as an integration
  source: https://raw.githubusercontent.com/killbill/killbill-cloud/master/kpm/lib/kpm/plugins_directory.yml
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-220.20
    key: indirect-tax-management
    name: Indirect Tax Management
    url: /capabilities/indirect-tax-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 44.6
    band: exemplar
    in_catalog: true
    kin_score: 70.5
    mcp: &id005
      source: https://github.com/avadev/mcp
      status: verified
    slug: avalara
    status: profiled
    tags: &id006
    - Accounting
    - Avalara
    - Tax
    url: /providers/avalara/
  layer: domain
  name: Avalara (AvaTax)
  provider: avalara
  says: lists Avalara (AvaTax) as an integration
  source: https://raw.githubusercontent.com/killbill/killbill-cloud/master/kpm/lib/kpm/plugins_directory.yml
  tier: declared
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
    mcp: &id007
      status: none
    slug: braintree
    status: profiled
    tags: &id008
    - Mobile
    - Payments
    - Subscription
    - Transaction
    url: /providers/braintree/
  layer: common
  name: Braintree
  provider: braintree
  says: lists Braintree as an integration
  source: https://raw.githubusercontent.com/killbill/killbill-cloud/master/kpm/lib/kpm/plugins_directory.yml
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 26.3
    band: thin
    in_catalog: true
    kin_score: 33.4
    mcp: &id009
      status: none
    slug: chase
    status: profiled
    tags: &id010
    - Account Aggregation
    - Banking
    - Consent
    - Credit Cards
    url: /providers/chase/
  layer: common
  name: Chase (Orbital / Paymentech)
  provider: chase
  says: lists Chase (Orbital / Paymentech) as an integration
  source: https://raw.githubusercontent.com/killbill/killbill-cloud/master/kpm/lib/kpm/plugins_directory.yml
  tier: declared
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
    agent_readiness: 33.3
    band: thin
    in_catalog: true
    kin_score: 33.8
    mcp: &id011
      source: https://github.com/CyberSource/cybersource-developer-mcp
      status: verified
    slug: cybersource
    status: profiled
    tags: &id012
    - Fraud Prevention
    - Payment Processing
    - Payments
    - Tokenization
    url: /providers/cybersource/
  layer: common
  name: CyberSource
  provider: cybersource
  says: lists CyberSource as an integration
  source: https://raw.githubusercontent.com/killbill/killbill-cloud/master/kpm/lib/kpm/plugins_directory.yml
  tier: declared
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
    agent_readiness: 53.9
    band: exemplar
    in_catalog: true
    kin_score: 74.8
    mcp: &id013
      source: https://github.com/Dwolla/dwolla-mcp
      status: verified
    slug: dwolla
    status: profiled
    tags: &id014
    - ACH
    - Bank Transfers
    - Fintech
    - Payments
    url: /providers/dwolla/
  layer: common
  name: Dwolla
  provider: dwolla
  says: lists Dwolla as an integration
  source: https://raw.githubusercontent.com/killbill/killbill-cloud/master/kpm/lib/kpm/plugins_directory.yml
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 22.3
    band: developing
    in_catalog: true
    kin_score: 46.0
    mcp: &id015
      status: none
    slug: csg
    status: profiled
    tags: &id016
    - Billing
    - Customer Engagement
    - Payments
    - Revenue Management
    url: /providers/csg/
  layer: common
  name: Forte
  provider: csg
  says: lists Forte as an integration
  source: https://raw.githubusercontent.com/killbill/killbill-cloud/master/kpm/lib/kpm/plugins_directory.yml
  tier: declared
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
    agent_readiness: 51.3
    band: developing
    in_catalog: true
    kin_score: 52.1
    mcp: &id017
      source: https://developer.gocardless.com/mcp
      status: verified
    slug: gocardless
    status: profiled
    tags: &id018
    - Bank Debit
    - Direct Debit
    - Payments
    - Recurring Payments
    url: /providers/gocardless/
  layer: common
  name: GoCardless
  provider: gocardless
  says: lists GoCardless as an integration
  source: https://raw.githubusercontent.com/killbill/killbill-cloud/master/kpm/lib/kpm/plugins_directory.yml
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-220.20
    key: indirect-tax-management
    name: Indirect Tax Management
    url: /capabilities/indirect-tax-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 44.2
    band: thin
    in_catalog: true
    kin_score: 38.7
    mcp: &id019
      status: none
    slug: kintsugi
    status: profiled
    tags: &id020
    - Sales Tax
    - Tax Automation
    - Tax Compliance
    - VAT
    url: /providers/kintsugi/
  layer: domain
  name: Kintsugi
  provider: kintsugi
  says: lists Kintsugi as an integration
  source: https://raw.githubusercontent.com/killbill/killbill-cloud/master/kpm/lib/kpm/plugins_directory.yml
  tier: declared
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
    agent_readiness: 37.1
    band: strong
    in_catalog: true
    kin_score: 54.7
    mcp: &id021
      source: https://developer.paypal.com/tools/mcp-server/
      status: verified
    slug: paypal
    status: profiled
    tags: &id022
    - Billing
    - Commerce
    - Disputes
    - PayPal
    url: /providers/paypal/
  layer: common
  name: PayPal
  provider: paypal
  says: lists PayPal as an integration
  source: https://raw.githubusercontent.com/killbill/killbill-cloud/master/kpm/lib/kpm/plugins_directory.yml
  tier: declared
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
    agent_readiness: 34.4
    band: developing
    in_catalog: true
    kin_score: 42.4
    mcp: &id023
      status: none
    slug: qualpay
    status: profiled
    tags: &id024
    - B2B Payments
    - Merchant Services
    - Payment Processing
    - Payments
    url: /providers/qualpay/
  layer: common
  name: Qualpay
  provider: qualpay
  says: lists Qualpay as an integration
  source: https://raw.githubusercontent.com/killbill/killbill-cloud/master/kpm/lib/kpm/plugins_directory.yml
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
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
    slug: securenet
    status: queued for profiling
    tags: &id026 []
    url: null
  layer: common
  name: SecureNet
  provider: securenet
  says: lists SecureNet as an integration
  source: https://raw.githubusercontent.com/killbill/killbill-cloud/master/kpm/lib/kpm/plugins_directory.yml
  tier: declared
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
  layer: common
  name: Stripe
  provider: stripe
  says: lists Stripe as an integration
  source: https://raw.githubusercontent.com/killbill/killbill-cloud/master/kpm/lib/kpm/plugins_directory.yml
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-220.20
    key: indirect-tax-management
    name: Indirect Tax Management
    url: /capabilities/indirect-tax-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 21.1
    band: emerging
    in_catalog: true
    kin_score: 23.1
    mcp: &id029
      status: none
    slug: vertex
    status: profiled
    tags: &id030
    - Automation
    - Company
    - Compliance
    - Tax
    url: /providers/vertex/
  layer: domain
  name: Vertex (tax)
  provider: vertex
  says: lists Vertex (tax) as an integration
  source: https://raw.githubusercontent.com/killbill/killbill-cloud/master/kpm/lib/kpm/plugins_directory.yml
  tier: declared
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/subscription-billing/kill-bill/
providers:
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 6.0
  mcp: *id001
  name: Accertify
  slug: accertify
  status: profiled
  tags: *id002
  url: /providers/accertify/
- agent_band: agent-native
  agent_readiness: 43.7
  band: exemplar
  in_catalog: true
  kin_score: 68.8
  mcp: *id003
  name: Adyen
  slug: adyen
  status: profiled
  tags: *id004
  url: /providers/adyen/
- agent_band: agent-ready
  agent_readiness: 44.6
  band: exemplar
  in_catalog: true
  kin_score: 70.5
  mcp: *id005
  name: Avalara (AvaTax)
  slug: avalara
  status: profiled
  tags: *id006
  url: /providers/avalara/
- agent_band: agent-ready
  agent_readiness: 52.0
  band: developing
  in_catalog: true
  kin_score: 46.2
  mcp: *id007
  name: Braintree
  slug: braintree
  status: profiled
  tags: *id008
  url: /providers/braintree/
- agent_band: agent-aware
  agent_readiness: 26.3
  band: thin
  in_catalog: true
  kin_score: 33.4
  mcp: *id009
  name: Chase (Orbital / Paymentech)
  slug: chase
  status: profiled
  tags: *id010
  url: /providers/chase/
- agent_band: agent-ready
  agent_readiness: 33.3
  band: thin
  in_catalog: true
  kin_score: 33.8
  mcp: *id011
  name: CyberSource
  slug: cybersource
  status: profiled
  tags: *id012
  url: /providers/cybersource/
- agent_band: agent-native
  agent_readiness: 53.9
  band: exemplar
  in_catalog: true
  kin_score: 74.8
  mcp: *id013
  name: Dwolla
  slug: dwolla
  status: profiled
  tags: *id014
  url: /providers/dwolla/
- agent_band: agent-aware
  agent_readiness: 22.3
  band: developing
  in_catalog: true
  kin_score: 46.0
  mcp: *id015
  name: Forte
  slug: csg
  status: profiled
  tags: *id016
  url: /providers/csg/
- agent_band: agent-ready
  agent_readiness: 51.3
  band: developing
  in_catalog: true
  kin_score: 52.1
  mcp: *id017
  name: GoCardless
  slug: gocardless
  status: profiled
  tags: *id018
  url: /providers/gocardless/
- agent_band: agent-ready
  agent_readiness: 44.2
  band: thin
  in_catalog: true
  kin_score: 38.7
  mcp: *id019
  name: Kintsugi
  slug: kintsugi
  status: profiled
  tags: *id020
  url: /providers/kintsugi/
- agent_band: agent-ready
  agent_readiness: 37.1
  band: strong
  in_catalog: true
  kin_score: 54.7
  mcp: *id021
  name: PayPal
  slug: paypal
  status: profiled
  tags: *id022
  url: /providers/paypal/
- agent_band: agent-ready
  agent_readiness: 34.4
  band: developing
  in_catalog: true
  kin_score: 42.4
  mcp: *id023
  name: Qualpay
  slug: qualpay
  status: profiled
  tags: *id024
  url: /providers/qualpay/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id025
  name: SecureNet
  slug: securenet
  status: queued for profiling
  tags: *id026
  url: null
- agent_band: agent-native
  agent_readiness: 58.5
  band: exemplar
  in_catalog: true
  kin_score: 81.5
  mcp: *id027
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id028
  url: /providers/stripe/
- agent_band: agent-aware
  agent_readiness: 21.1
  band: emerging
  in_catalog: true
  kin_score: 23.1
  mcp: *id029
  name: Vertex (tax)
  slug: vertex
  status: profiled
  tags: *id030
  url: /providers/vertex/
siblings:
- name: Chargebee
  rows: 44
  url: /applications/subscription-billing/chargebee/
- name: Invoice Ninja
  rows: 34
  url: /applications/subscription-billing/invoice-ninja/
- name: Lago
  rows: 31
  url: /applications/subscription-billing/lago/
- name: Paddle
  rows: 12
  url: /applications/subscription-billing/paddle/
- name: Polar
  rows: 14
  url: /applications/subscription-billing/polar/
- name: Recurly
  rows: 28
  url: /applications/subscription-billing/recurly/
sitemap: true
title: 'Kill Bill: Subscription Billing & Payments Ops reference app'
---
