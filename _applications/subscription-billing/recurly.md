---
app: Recurly
app_slug: recurly
app_url: https://recurly.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-1340.40
  key: cross-border-payment-management
  layer: domain
  name: Cross-Border Payment Management
  providers:
  - Reach (withreach.com)
  url: /capabilities/cross-border-payment-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-420
  key: customer-relationship-management
  layer: domain
  name: Customer Relationship Management
  providers:
  - HubSpot
  url: /capabilities/customer-relationship-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-200.10
  key: general-ledger-management
  layer: domain
  name: General Ledger Management
  providers:
  - Intuit QuickBooks
  - Oracle NetSuite
  url: /capabilities/general-ledger-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-220.20
  key: indirect-tax-management
  layer: domain
  name: Indirect Tax Management
  providers:
  - Avalara
  url: /capabilities/indirect-tax-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4250.40
  key: payment-collection-dunning
  layer: domain
  name: Payment Collection & Dunning
  providers:
  - ProsperStack
  - Vindicia
  url: /capabilities/payment-collection-dunning/
  via_parent: null
- attribution: Turbo EA
  id: BC-4270.70
  key: software-marketplace-listing-management
  layer: domain
  name: Software Marketplace Listing Management
  providers:
  - Google Cloud
  url: /capabilities/software-marketplace-listing-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-400.60
  key: digital-marketing-management
  layer: common
  name: Digital Marketing Management
  providers:
  - Mailchimp
  url: /capabilities/digital-marketing-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-1400.30
  key: fraud-detection-investigation-management
  layer: common
  name: Fraud Detection & Investigation Management
  providers:
  - Equifax
  - Justt
  - Kount
  url: /capabilities/fraud-detection-investigation-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: common
  name: Payment Processing Management
  providers:
  - Adyen
  - Authorize.net
  - CardConnect
  - Chase
  - Checkout.com
  - Cybersource
  - Ebanx
  - Fiserv
  - GoCardless
  - JPMorgan Chase
  - MerchantE
  - Nuvei
  - PayPal
  - Revolv3
  - Stripe
  - Worldpay
  url: /capabilities/payment-processing-management/
  via_parent: null
category:
  id: subscription-billing
  name: Subscription Billing & Payments Ops
  url: /applications/subscription-billing/
counts:
  declared: 28
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://recurly.com/integrations/
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
    agent_band: agent-native
    agent_readiness: 43.7
    band: exemplar
    in_catalog: true
    kin_score: 68.8
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
  layer: common
  name: Adyen
  provider: adyen
  says: lists Adyen as an integration
  source: https://recurly.com/integrations/
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
    agent_readiness: 25.9
    band: thin
    in_catalog: true
    kin_score: 36.4
    mcp: &id003
      source: https://github.com/AuthorizeNet/authorize-net-mcp
      status: verified
    slug: authorizenet
    status: profiled
    tags: &id004
    - Company
    - Credit Cards
    - Payment Gateway
    - Payments
    url: /providers/authorizenet/
  layer: common
  name: Authorize.net
  provider: authorizenet
  says: lists Authorize.net as an integration
  source: https://recurly.com/integrations/
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
  name: Avalara
  provider: avalara
  says: lists Avalara as an integration
  source: https://recurly.com/integrations/
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
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 8.0
    mcp: &id007
      status: none
    slug: cardconnect
    status: profiled
    tags: &id008
    - Company
    url: /providers/cardconnect/
  layer: common
  name: CardConnect
  provider: cardconnect
  says: lists CardConnect as an integration
  source: https://recurly.com/integrations/
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
  name: Chase
  provider: chase
  says: lists Chase as an integration
  source: https://recurly.com/integrations/
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
    agent_readiness: 47.5
    band: thin
    in_catalog: true
    kin_score: 33.6
    mcp: &id011
      source: https://github.com/checkout/checkout-mcp
      status: verified
    slug: checkout-com
    status: profiled
    tags: &id012
    - Acquiring
    - Cards
    - Fintech
    - Payments
    url: /providers/checkout-com/
  layer: common
  name: Checkout.com
  provider: checkout-com
  says: lists Checkout.com as an integration
  source: https://recurly.com/integrations/
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
    mcp: &id013
      source: https://github.com/CyberSource/cybersource-developer-mcp
      status: verified
    slug: cybersource
    status: profiled
    tags: &id014
    - Fraud Prevention
    - Payment Processing
    - Payments
    - Tokenization
    url: /providers/cybersource/
  layer: common
  name: Cybersource
  provider: cybersource
  says: lists Cybersource as an integration
  source: https://recurly.com/integrations/
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
    agent_readiness: 32.1
    band: thin
    in_catalog: true
    kin_score: 34.7
    mcp: &id015
      status: none
    slug: ebanx
    status: profiled
    tags: &id016
    - Foreign Exchange
    - Pay-In
    - Payments
    - Payouts
    url: /providers/ebanx/
  layer: common
  name: Ebanx
  provider: ebanx
  says: lists Ebanx as an integration
  source: https://recurly.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-1400.30
    key: fraud-detection-investigation-management
    name: Fraud Detection & Investigation Management
    url: /capabilities/fraud-detection-investigation-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 7.9
    band: developing
    in_catalog: true
    kin_score: 45.8
    mcp: &id017
      status: none
    slug: equifax
    status: profiled
    tags: &id018
    - Credit
    - Credit History
    - Credit Reporting
    - Identity
    url: /providers/equifax/
  layer: common
  name: Equifax
  provider: equifax
  says: lists Equifax as an integration
  source: https://recurly.com/integrations/
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
    agent_readiness: 25.0
    band: thin
    in_catalog: true
    kin_score: 36.6
    mcp: &id019
      status: none
    slug: fiserv
    status: profiled
    tags: &id020
    - Banking
    - Finance
    - Payments
    - Wealth Management
    url: /providers/fiserv/
  layer: common
  name: Fiserv
  provider: fiserv
  says: lists Fiserv as an integration
  source: https://recurly.com/integrations/
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
    mcp: &id021
      source: https://developer.gocardless.com/mcp
      status: verified
    slug: gocardless
    status: profiled
    tags: &id022
    - Bank Debit
    - Direct Debit
    - Payments
    - Recurring Payments
    url: /providers/gocardless/
  layer: common
  name: GoCardless
  provider: gocardless
  says: lists GoCardless as an integration
  source: https://recurly.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4270.70
    key: software-marketplace-listing-management
    name: Software Marketplace Listing Management
    url: /capabilities/software-marketplace-listing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 50.7
    band: strong
    in_catalog: true
    kin_score: 64.8
    mcp: &id023
      source: https://github.com/googleapis/mcp-toolbox
      status: verified
    slug: google-cloud-platform
    status: profiled
    tags: &id024
    - API Management
    - Cloud Computing
    - Infrastructure
    - Platform-as-a-Service
    url: /providers/google-cloud-platform/
  layer: domain
  name: Google Cloud
  provider: google-cloud-platform
  says: lists Google Cloud as an integration
  source: https://recurly.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-420
    key: customer-relationship-management
    name: Customer Relationship Management
    url: /capabilities/customer-relationship-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 52.7
    band: exemplar
    in_catalog: true
    kin_score: 94.6
    mcp: &id025
      source: https://developers.hubspot.com/mcp
      status: verified
    slug: hubspot
    status: profiled
    tags: &id026
    - Analytics
    - CRM
    - Commerce
    - Content
    url: /providers/hubspot/
  layer: domain
  name: HubSpot
  provider: hubspot
  says: lists HubSpot as an integration
  source: https://recurly.com/integrations/
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
    mcp: &id027
      source: https://github.com/intuit/quickbooks-online-mcp-server
      status: verified
    slug: quickbooks
    status: profiled
    tags: &id028
    - Accounting
    - Bookkeeping
    - Finance
    - Small Business
    url: /providers/quickbooks/
  layer: domain
  name: Intuit QuickBooks
  provider: quickbooks
  says: lists Intuit QuickBooks as an integration
  source: https://recurly.com/integrations/
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
    agent_readiness: 42.4
    band: developing
    in_catalog: true
    kin_score: 52.3
    mcp: &id029
      status: none
    slug: jp-morgan-chase
    status: profiled
    tags: &id030
    - Banking
    - Financial Services
    - Payments
    - Treasury
    url: /providers/jp-morgan-chase/
  layer: common
  name: JPMorgan Chase
  provider: jp-morgan-chase
  says: lists JPMorgan Chase as an integration
  source: https://recurly.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-1400.30
    key: fraud-detection-investigation-management
    name: Fraud Detection & Investigation Management
    url: /capabilities/fraud-detection-investigation-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 52.9
    band: strong
    in_catalog: true
    kin_score: 57.7
    mcp: &id031
      status: none
    slug: justt
    status: profiled
    tags: &id032
    - Chargebacks
    - Company
    - Disputes
    - Payments
    url: /providers/justt/
  layer: common
  name: Justt
  provider: justt
  says: lists Justt as an integration
  source: https://recurly.com/integrations/
  tier: declared
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
    agent_readiness: 2.5
    band: emerging
    in_catalog: true
    kin_score: 20.0
    mcp: &id033
      status: none
    slug: kount
    status: profiled
    tags: &id034
    - Chargebacks
    - Fraud Prevention
    - Identity
    - Payments
    url: /providers/kount/
  layer: common
  name: Kount
  provider: kount
  says: lists Kount as an integration
  source: https://recurly.com/integrations/
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
    agent_band: agent-ready
    agent_readiness: 42.3
    band: exemplar
    in_catalog: true
    kin_score: 78.3
    mcp: &id035
      status: none
    slug: mailchimp
    status: profiled
    tags: &id036
    - Campaigns
    - Email Marketing
    - Marketing Automation
    - Newsletters
    url: /providers/mailchimp/
  layer: common
  name: Mailchimp
  provider: mailchimp
  says: lists Mailchimp as an integration
  source: https://recurly.com/integrations/
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
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 11.6
    mcp: &id037
      status: unknown
    slug: merchante
    status: profiled
    tags: &id038
    - Acquiring
    - Company
    - Fintech
    - Payments
    url: /providers/merchante/
  layer: common
  name: MerchantE
  provider: merchante
  says: lists MerchantE as an integration
  source: https://recurly.com/integrations/
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
    agent_readiness: 19.9
    band: thin
    in_catalog: true
    kin_score: 26.5
    mcp: &id039
      status: none
    slug: nuvei
    status: profiled
    tags: &id040
    - Acquiring
    - Payment Gateway
    - Payment Processing
    - Payments
    url: /providers/nuvei/
  layer: common
  name: Nuvei
  provider: nuvei
  says: lists Nuvei as an integration
  source: https://recurly.com/integrations/
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
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 12.5
    mcp: &id041
      status: none
    slug: netsuite
    status: profiled
    tags: &id042
    - Accounting
    - CRM
    - ERP
    - Finance
    url: /providers/netsuite/
  layer: domain
  name: Oracle NetSuite
  provider: netsuite
  says: lists Oracle NetSuite as an integration
  source: https://recurly.com/integrations/
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
    mcp: &id043
      source: https://developer.paypal.com/tools/mcp-server/
      status: verified
    slug: paypal
    status: profiled
    tags: &id044
    - Billing
    - Commerce
    - Disputes
    - PayPal
    url: /providers/paypal/
  layer: common
  name: PayPal
  provider: paypal
  says: lists PayPal as an integration
  source: https://recurly.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4250.40
    key: payment-collection-dunning
    name: Payment Collection & Dunning
    url: /capabilities/payment-collection-dunning/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 30.1
    band: developing
    in_catalog: true
    kin_score: 43.0
    mcp: &id045
      source: https://docs.prosperstack.com/integrations/mcp-server
      status: verified
    slug: prosperstack
    status: profiled
    tags: &id046
    - Analytics
    - Company
    - Retention
    - Subscription
    url: /providers/prosperstack/
  layer: domain
  name: ProsperStack
  provider: prosperstack
  says: lists ProsperStack as an integration
  source: https://recurly.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-1340.40
    key: cross-border-payment-management
    name: Cross-Border Payment Management
    url: /capabilities/cross-border-payment-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 47.9
    band: developing
    in_catalog: true
    kin_score: 44.0
    mcp: &id047
      status: none
    slug: withreach
    status: profiled
    tags: &id048
    - Company
    - Compliance
    - Payments
    - Tax
    url: /providers/withreach/
  layer: domain
  name: Reach (withreach.com)
  provider: withreach
  says: lists Reach (withreach.com) as an integration
  source: https://recurly.com/integrations/
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
    agent_readiness: 23.4
    band: developing
    in_catalog: true
    kin_score: 41.0
    mcp: &id049
      status: unknown
    slug: revolv3
    status: profiled
    tags: &id050
    - Company
    - Enterprise
    - Payments
    - Software-as-a-Service
    url: /providers/revolv3/
  layer: common
  name: Revolv3
  provider: revolv3
  says: lists Revolv3 as an integration
  source: https://recurly.com/integrations/
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
    mcp: &id051
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id052
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
  layer: common
  name: Stripe
  provider: stripe
  says: lists Stripe as an integration
  source: https://recurly.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4250.40
    key: payment-collection-dunning
    name: Payment Collection & Dunning
    url: /capabilities/payment-collection-dunning/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 22.7
    band: thin
    in_catalog: true
    kin_score: 33.7
    mcp: &id053
      status: none
    slug: vindicia
    status: profiled
    tags: &id054
    - Company
    - Fintech
    - Recurring Payments
    - Subscription Billing
    url: /providers/vindicia/
  layer: domain
  name: Vindicia
  provider: vindicia
  says: lists Vindicia as an integration
  source: https://recurly.com/integrations/
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
    agent_readiness: 45.6
    band: developing
    in_catalog: true
    kin_score: 50.7
    mcp: &id055
      status: none
    slug: worldpay
    status: profiled
    tags: &id056
    - Payment Gateway
    - Payment Processing
    - Payments
    - Tokenization
    url: /providers/worldpay/
  layer: common
  name: Worldpay
  provider: worldpay
  says: lists Worldpay as an integration
  source: https://recurly.com/integrations/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/subscription-billing/recurly/
providers:
- agent_band: agent-native
  agent_readiness: 43.7
  band: exemplar
  in_catalog: true
  kin_score: 68.8
  mcp: *id001
  name: Adyen
  slug: adyen
  status: profiled
  tags: *id002
  url: /providers/adyen/
- agent_band: agent-aware
  agent_readiness: 25.9
  band: thin
  in_catalog: true
  kin_score: 36.4
  mcp: *id003
  name: Authorize.net
  slug: authorizenet
  status: profiled
  tags: *id004
  url: /providers/authorizenet/
- agent_band: agent-ready
  agent_readiness: 44.6
  band: exemplar
  in_catalog: true
  kin_score: 70.5
  mcp: *id005
  name: Avalara
  slug: avalara
  status: profiled
  tags: *id006
  url: /providers/avalara/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 8.0
  mcp: *id007
  name: CardConnect
  slug: cardconnect
  status: profiled
  tags: *id008
  url: /providers/cardconnect/
- agent_band: agent-aware
  agent_readiness: 26.3
  band: thin
  in_catalog: true
  kin_score: 33.4
  mcp: *id009
  name: Chase
  slug: chase
  status: profiled
  tags: *id010
  url: /providers/chase/
- agent_band: agent-native
  agent_readiness: 47.5
  band: thin
  in_catalog: true
  kin_score: 33.6
  mcp: *id011
  name: Checkout.com
  slug: checkout-com
  status: profiled
  tags: *id012
  url: /providers/checkout-com/
- agent_band: agent-ready
  agent_readiness: 33.3
  band: thin
  in_catalog: true
  kin_score: 33.8
  mcp: *id013
  name: Cybersource
  slug: cybersource
  status: profiled
  tags: *id014
  url: /providers/cybersource/
- agent_band: agent-ready
  agent_readiness: 32.1
  band: thin
  in_catalog: true
  kin_score: 34.7
  mcp: *id015
  name: Ebanx
  slug: ebanx
  status: profiled
  tags: *id016
  url: /providers/ebanx/
- agent_band: agent-aware
  agent_readiness: 7.9
  band: developing
  in_catalog: true
  kin_score: 45.8
  mcp: *id017
  name: Equifax
  slug: equifax
  status: profiled
  tags: *id018
  url: /providers/equifax/
- agent_band: agent-aware
  agent_readiness: 25.0
  band: thin
  in_catalog: true
  kin_score: 36.6
  mcp: *id019
  name: Fiserv
  slug: fiserv
  status: profiled
  tags: *id020
  url: /providers/fiserv/
- agent_band: agent-ready
  agent_readiness: 51.3
  band: developing
  in_catalog: true
  kin_score: 52.1
  mcp: *id021
  name: GoCardless
  slug: gocardless
  status: profiled
  tags: *id022
  url: /providers/gocardless/
- agent_band: agent-ready
  agent_readiness: 50.7
  band: strong
  in_catalog: true
  kin_score: 64.8
  mcp: *id023
  name: Google Cloud
  slug: google-cloud-platform
  status: profiled
  tags: *id024
  url: /providers/google-cloud-platform/
- agent_band: agent-ready
  agent_readiness: 52.7
  band: exemplar
  in_catalog: true
  kin_score: 94.6
  mcp: *id025
  name: HubSpot
  slug: hubspot
  status: profiled
  tags: *id026
  url: /providers/hubspot/
- agent_band: agent-native
  agent_readiness: 41.2
  band: strong
  in_catalog: true
  kin_score: 61.1
  mcp: *id027
  name: Intuit QuickBooks
  slug: quickbooks
  status: profiled
  tags: *id028
  url: /providers/quickbooks/
- agent_band: agent-native
  agent_readiness: 42.4
  band: developing
  in_catalog: true
  kin_score: 52.3
  mcp: *id029
  name: JPMorgan Chase
  slug: jp-morgan-chase
  status: profiled
  tags: *id030
  url: /providers/jp-morgan-chase/
- agent_band: agent-ready
  agent_readiness: 52.9
  band: strong
  in_catalog: true
  kin_score: 57.7
  mcp: *id031
  name: Justt
  slug: justt
  status: profiled
  tags: *id032
  url: /providers/justt/
- agent_band: human-only
  agent_readiness: 2.5
  band: emerging
  in_catalog: true
  kin_score: 20.0
  mcp: *id033
  name: Kount
  slug: kount
  status: profiled
  tags: *id034
  url: /providers/kount/
- agent_band: agent-ready
  agent_readiness: 42.3
  band: exemplar
  in_catalog: true
  kin_score: 78.3
  mcp: *id035
  name: Mailchimp
  slug: mailchimp
  status: profiled
  tags: *id036
  url: /providers/mailchimp/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 11.6
  mcp: *id037
  name: MerchantE
  slug: merchante
  status: profiled
  tags: *id038
  url: /providers/merchante/
- agent_band: agent-aware
  agent_readiness: 19.9
  band: thin
  in_catalog: true
  kin_score: 26.5
  mcp: *id039
  name: Nuvei
  slug: nuvei
  status: profiled
  tags: *id040
  url: /providers/nuvei/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 12.5
  mcp: *id041
  name: Oracle NetSuite
  slug: netsuite
  status: profiled
  tags: *id042
  url: /providers/netsuite/
- agent_band: agent-ready
  agent_readiness: 37.1
  band: strong
  in_catalog: true
  kin_score: 54.7
  mcp: *id043
  name: PayPal
  slug: paypal
  status: profiled
  tags: *id044
  url: /providers/paypal/
- agent_band: agent-ready
  agent_readiness: 30.1
  band: developing
  in_catalog: true
  kin_score: 43.0
  mcp: *id045
  name: ProsperStack
  slug: prosperstack
  status: profiled
  tags: *id046
  url: /providers/prosperstack/
- agent_band: agent-ready
  agent_readiness: 47.9
  band: developing
  in_catalog: true
  kin_score: 44.0
  mcp: *id047
  name: Reach (withreach.com)
  slug: withreach
  status: profiled
  tags: *id048
  url: /providers/withreach/
- agent_band: agent-aware
  agent_readiness: 23.4
  band: developing
  in_catalog: true
  kin_score: 41.0
  mcp: *id049
  name: Revolv3
  slug: revolv3
  status: profiled
  tags: *id050
  url: /providers/revolv3/
- agent_band: agent-native
  agent_readiness: 58.5
  band: exemplar
  in_catalog: true
  kin_score: 81.5
  mcp: *id051
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id052
  url: /providers/stripe/
- agent_band: agent-aware
  agent_readiness: 22.7
  band: thin
  in_catalog: true
  kin_score: 33.7
  mcp: *id053
  name: Vindicia
  slug: vindicia
  status: profiled
  tags: *id054
  url: /providers/vindicia/
- agent_band: agent-native
  agent_readiness: 45.6
  band: developing
  in_catalog: true
  kin_score: 50.7
  mcp: *id055
  name: Worldpay
  slug: worldpay
  status: profiled
  tags: *id056
  url: /providers/worldpay/
siblings:
- name: Chargebee
  rows: 44
  url: /applications/subscription-billing/chargebee/
- name: Invoice Ninja
  rows: 34
  url: /applications/subscription-billing/invoice-ninja/
- name: Kill Bill
  rows: 15
  url: /applications/subscription-billing/kill-bill/
- name: Lago
  rows: 31
  url: /applications/subscription-billing/lago/
- name: Paddle
  rows: 12
  url: /applications/subscription-billing/paddle/
- name: Polar
  rows: 14
  url: /applications/subscription-billing/polar/
sitemap: true
title: 'Recurly: Subscription Billing & Payments Ops reference app'
---
