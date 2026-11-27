---
app: Mindbody
app_slug: mindbody
app_url: https://www.mindbodyonline.com/business
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-130.10
  key: AE-130.10
  layer: domain
  name: Activity & Fitness Tracking
  providers:
  - FitOn
  url: /capabilities/activity-fitness-tracking/
  via_parent: null
- attribution: Turbo EA
  id: BC-1320.20
  key: credit-underwriting-decisioning-management
  layer: domain
  name: Credit Underwriting & Decisioning Management
  providers:
  - Equifax
  url: /capabilities/credit-underwriting-decisioning-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-420
  key: customer-relationship-management
  layer: domain
  name: Customer Relationship Management
  providers:
  - GymSales
  - HubSpot
  - Keepme
  url: /capabilities/customer-relationship-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-140.50
  key: gift-cards-gifting-cashback
  layer: domain
  name: Gift Cards, Gifting & Cashback
  providers:
  - Nift
  url: /capabilities/gift-cards-gifting-cashback/
  via_parent: null
- attribution: Turbo EA
  id: BC-220.20
  key: indirect-tax-management
  layer: domain
  name: Indirect Tax Management
  providers:
  - DAVO Sales Tax
  url: /capabilities/indirect-tax-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-140.80
  key: marketplaces
  layer: domain
  name: Marketplaces
  providers:
  - ClassPass
  url: /capabilities/marketplaces/
  via_parent: null
- attribution: Turbo EA
  id: BC-300.70.20
  key: BC-300.70.20
  layer: domain
  name: Payroll Administration
  providers:
  - Paychex
  url: /capabilities/hr-operations-management/
  via_parent: HR Operations Management
- attribution: API Evangelist extension
  id: AE-200.90
  key: AE-200.90
  layer: domain
  name: Physical Access Control & Mobile Keys
  providers:
  - Kisi
  url: /capabilities/physical-access-control-mobile-keys/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-140.60
  key: reviews-social-proof
  layer: domain
  name: Reviews & Social Proof
  providers:
  - Birdeye
  - Listen360
  - NiceJob
  - Podium
  url: /capabilities/reviews-social-proof/
  via_parent: null
- attribution: Turbo EA
  id: BC-200.10
  key: general-ledger-management
  layer: common
  name: General Ledger Management
  providers:
  - Bench
  - Bookkeep.com
  url: /capabilities/general-ledger-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: common
  name: Payment Processing Management
  providers:
  - Brijpay
  - Truemed
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-910
  key: AE-910
  layer: common
  name: Workflow Automation & iPaaS
  providers:
  - APIANT (CRMConnect, ShopifyConnect)
  - Flozic by Appy Pie
  url: /capabilities/process-automation-governance/
  via_parent: Process Automation Governance
- attribution: API Evangelist extension
  id: AE-100.70.30
  key: AE-100.70.30
  layer: agent
  name: Support & Assist Agents
  providers:
  - Healthdesk
  url: /capabilities/vertical-agents/
  via_parent: Vertical Agents
- attribution: API Evangelist extension
  id: AE-150.50.30
  key: AE-150.50.30
  layer: agent
  name: Virtual Receptionists & Answering Services
  providers:
  - REACH ai
  url: /capabilities/voice-telephony/
  via_parent: Voice & Telephony
category:
  id: salon-spa-management
  name: Salon & Spa Management
  url: /applications/salon-spa-management/
counts:
  declared: 22
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://integrations.mindbodyonline.com/t/categories/connectors
- route: integrations page
  url: https://integrations.mindbodyonline.com/t/categories/financial-services
- route: integrations page
  url: https://integrations.mindbodyonline.com/t/categories/marketing
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-910
    key: AE-910
    name: Workflow Automation & iPaaS
    url: /capabilities/process-automation-governance/
    via_parent: Process Automation Governance
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 20.8
    band: thin
    in_catalog: true
    kin_score: 29.9
    mcp: &id001
      source: https://mcp.apiant.ai/mcp
      status: verified
    slug: apiant
    status: profiled
    tags: &id002
    - Artificial Intelligence
    - Automation
    - Company
    - Integration
    url: /providers/apiant/
  layer: common
  name: APIANT (CRMConnect, ShopifyConnect)
  provider: apiant
  says: lists APIANT (CRMConnect, ShopifyConnect) as an integration
  source: https://integrations.mindbodyonline.com/t/categories/marketing
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
    band: thin
    in_catalog: true
    kin_score: 30.4
    mcp: &id003
      status: unknown
    slug: bench
    status: profiled
    tags: &id004
    - Accounting
    - Bookkeeping
    - Small Business
    - Software-as-a-Service
    url: /providers/bench/
  layer: common
  name: Bench
  provider: bench
  says: lists Bench as an integration
  source: https://integrations.mindbodyonline.com/t/categories/financial-services
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.60
    key: reviews-social-proof
    name: Reviews & Social Proof
    url: /capabilities/reviews-social-proof/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 59.9
    band: exemplar
    in_catalog: true
    kin_score: 72.5
    mcp: &id005
      source: https://docs.birdeye.com/mcp/introduction
      status: verified
    slug: birdeye
    status: profiled
    tags: &id006
    - Customer Experience
    - Reputation Management
    - Reviews
    - Surveys
    url: /providers/birdeye/
  layer: domain
  name: Birdeye
  provider: birdeye
  says: lists Birdeye as an integration
  source: https://integrations.mindbodyonline.com/t/categories/marketing
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
    agent_readiness: 34.4
    band: thin
    in_catalog: true
    kin_score: 35.4
    mcp: &id007
      status: unknown
    slug: bookkeep-com
    status: profiled
    tags: &id008
    - Accounting
    - Automation
    - Company
    - Shopify
    url: /providers/bookkeep-com/
  layer: common
  name: Bookkeep.com
  provider: bookkeep-com
  says: lists Bookkeep.com as an integration
  source: https://integrations.mindbodyonline.com/t/categories/connectors
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
    kin_score: 8.4
    mcp: &id009
      status: unchecked
    slug: brijpay
    status: profiled
    tags: &id010
    - E-Commerce
    - Middleware
    - Payments
    - Subscription Billing
    url: /providers/brijpay/
  layer: common
  name: Brijpay
  provider: brijpay
  says: lists Brijpay as an integration
  source: https://integrations.mindbodyonline.com/t/categories/connectors
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.80
    key: marketplaces
    name: Marketplaces
    url: /capabilities/marketplaces/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 11.0
    mcp: &id011
      status: none
    slug: classpass
    status: profiled
    tags: &id012
    - Class Booking
    - Fitness
    - Marketplace
    - Wellness
    url: /providers/classpass/
  layer: domain
  name: ClassPass
  provider: classpass
  says: lists ClassPass as an integration
  source: https://integrations.mindbodyonline.com/t/categories/marketing
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
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id013
      status: unchecked
    slug: davo
    status: queued for profiling
    tags: &id014 []
    url: null
  layer: domain
  name: DAVO Sales Tax
  provider: davo
  says: lists DAVO Sales Tax as an integration
  source: https://integrations.mindbodyonline.com/t/categories/financial-services
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-1320.20
    key: credit-underwriting-decisioning-management
    name: Credit Underwriting & Decisioning Management
    url: /capabilities/credit-underwriting-decisioning-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 7.7
    band: developing
    in_catalog: true
    kin_score: 47.1
    mcp: &id015
      status: none
    slug: equifax
    status: profiled
    tags: &id016
    - Credit
    - Credit History
    - Credit Reporting
    - Identity
    url: /providers/equifax/
  layer: domain
  name: Equifax
  provider: equifax
  says: lists Equifax as an integration
  source: https://integrations.mindbodyonline.com/t/categories/financial-services
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-130.10
    key: AE-130.10
    name: Activity & Fitness Tracking
    url: /capabilities/activity-fitness-tracking/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 14.2
    mcp: &id017
      status: unknown
    slug: fiton
    status: profiled
    tags: &id018
    - Company
    - Fitness
    - Healthcare
    - Wellness
    url: /providers/fiton/
  layer: domain
  name: FitOn
  provider: fiton
  says: lists FitOn as an integration
  source: https://integrations.mindbodyonline.com/t/categories/marketing
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-910
    key: AE-910
    name: Workflow Automation & iPaaS
    url: /capabilities/process-automation-governance/
    via_parent: Process Automation Governance
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.5
    band: thin
    in_catalog: true
    kin_score: 29.6
    mcp: &id019
      status: unknown
    slug: appypie
    status: profiled
    tags: &id020
    - App Builder
    - Artificial Intelligence
    - Mobile App
    - No-Code
    url: /providers/appypie/
  layer: common
  name: Flozic by Appy Pie
  provider: appypie
  says: lists Flozic by Appy Pie as an integration
  source: https://integrations.mindbodyonline.com/t/categories/connectors
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
    agent_band: human-only
    agent_readiness: 3.0
    band: emerging
    in_catalog: true
    kin_score: 11.6
    mcp: &id021
      status: unchecked
    slug: gymsales
    status: profiled
    tags: &id022
    - Club Management
    - Lead Management
    - Performance Reporting
    - Sales Platform
    url: /providers/gymsales/
  layer: domain
  name: GymSales
  provider: gymsales
  says: lists GymSales as an integration
  source: https://integrations.mindbodyonline.com/t/categories/marketing
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-100.70.30
    key: AE-100.70.30
    name: Support & Assist Agents
    url: /capabilities/vertical-agents/
    via_parent: Vertical Agents
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id023
      status: unchecked
    slug: healthdesk
    status: queued for profiling
    tags: &id024 []
    url: null
  layer: agent
  name: Healthdesk
  provider: healthdesk
  says: lists Healthdesk as an integration
  source: https://integrations.mindbodyonline.com/t/categories/marketing
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
    agent_readiness: 52.0
    band: exemplar
    in_catalog: true
    kin_score: 91.9
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
  source: https://integrations.mindbodyonline.com/t/categories/marketing
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
    agent_band: agent-aware
    agent_readiness: 6.2
    band: emerging
    in_catalog: true
    kin_score: 17.5
    mcp: &id027
      status: unchecked
    slug: keepme
    status: profiled
    tags: &id028
    - Artificial Intelligence
    - Company
    - Fitness
    - Software-as-a-Service
    url: /providers/keepme/
  layer: domain
  name: Keepme
  provider: keepme
  says: lists Keepme as an integration
  source: https://integrations.mindbodyonline.com/t/categories/marketing
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-200.90
    key: AE-200.90
    name: Physical Access Control & Mobile Keys
    url: /capabilities/physical-access-control-mobile-keys/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 34.1
    band: strong
    in_catalog: true
    kin_score: 57.6
    mcp: &id029
      status: none
    slug: kisi
    status: profiled
    tags: &id030
    - Company
    - Identity
    - Physical Access Control
    - Security
    url: /providers/kisi/
  layer: domain
  name: Kisi
  provider: kisi
  says: lists Kisi as an integration
  source: https://integrations.mindbodyonline.com/t/categories/marketing
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.60
    key: reviews-social-proof
    name: Reviews & Social Proof
    url: /capabilities/reviews-social-proof/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 17.5
    band: emerging
    in_catalog: true
    kin_score: 22.7
    mcp: &id031
      status: unchecked
    slug: listen360
    status: profiled
    tags: &id032
    - Customer Experience
    - Enterprise Software
    - Feedback Management
    - Reputation Management
    url: /providers/listen360/
  layer: domain
  name: Listen360
  provider: listen360
  says: lists Listen360 as an integration
  source: https://integrations.mindbodyonline.com/t/categories/marketing
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.60
    key: reviews-social-proof
    name: Reviews & Social Proof
    url: /capabilities/reviews-social-proof/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.5
    band: emerging
    in_catalog: true
    kin_score: 18.4
    mcp: &id033
      status: none
    slug: nicejob
    status: profiled
    tags: &id034
    - Artificial Intelligence
    - Reputation Marketing
    - Service Business
    - Software-as-a-Service
    url: /providers/nicejob/
  layer: domain
  name: NiceJob
  provider: nicejob
  says: lists NiceJob as an integration
  source: https://integrations.mindbodyonline.com/t/categories/marketing
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.50
    key: gift-cards-gifting-cashback
    name: Gift Cards, Gifting & Cashback
    url: /capabilities/gift-cards-gifting-cashback/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.1
    band: developing
    in_catalog: true
    kin_score: 42.6
    mcp: &id035
      status: unknown
    slug: nift
    status: profiled
    tags: &id036
    - Company
    - Customer Acquisition
    - Gifting
    - Marketing
    url: /providers/nift/
  layer: domain
  name: Nift
  provider: nift
  says: lists Nift as an integration
  source: https://integrations.mindbodyonline.com/t/categories/marketing
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-300.70.20
    key: BC-300.70.20
    name: Payroll Administration
    url: /capabilities/hr-operations-management/
    via_parent: HR Operations Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 29.3
    band: thin
    in_catalog: true
    kin_score: 37.8
    mcp: &id037
      status: none
    slug: paychex-developer
    status: profiled
    tags: &id038
    - Benefits
    - HCM
    - Human Resources
    - Paychex Flex
    url: /providers/paychex-developer/
  layer: domain
  name: Paychex
  provider: paychex-developer
  says: lists Paychex as an integration
  source: https://integrations.mindbodyonline.com/t/categories/financial-services
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.60
    key: reviews-social-proof
    name: Reviews & Social Proof
    url: /capabilities/reviews-social-proof/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 40.1
    band: strong
    in_catalog: true
    kin_score: 59.1
    mcp: &id039
      status: none
    slug: podium
    status: profiled
    tags: &id040
    - Customer Communication
    - Messaging
    - Payments
    - Reviews
    url: /providers/podium/
  layer: domain
  name: Podium
  provider: podium
  says: lists Podium as an integration
  source: https://integrations.mindbodyonline.com/t/categories/financial-services
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.50.30
    key: AE-150.50.30
    name: Virtual Receptionists & Answering Services
    url: /capabilities/voice-telephony/
    via_parent: Voice & Telephony
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id041
      status: unchecked
    slug: reach-ai
    status: queued for profiling
    tags: &id042 []
    url: null
  layer: agent
  name: REACH ai
  provider: reach-ai
  says: lists REACH ai as an integration
  source: https://integrations.mindbodyonline.com/t/categories/marketing
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
    agent_readiness: 55.0
    band: developing
    in_catalog: true
    kin_score: 52.3
    mcp: &id043
      status: unchecked
    slug: truemed
    status: profiled
    tags: &id044
    - Company
    - Fintech
    - HSA
    - Health
    url: /providers/truemed/
  layer: common
  name: Truemed
  provider: truemed
  says: lists Truemed as an integration
  source: https://integrations.mindbodyonline.com/t/categories/marketing
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/salon-spa-management/mindbody/
providers:
- agent_band: agent-aware
  agent_readiness: 20.8
  band: thin
  in_catalog: true
  kin_score: 29.9
  mcp: *id001
  name: APIANT (CRMConnect, ShopifyConnect)
  slug: apiant
  status: profiled
  tags: *id002
  url: /providers/apiant/
- agent_band: human-only
  agent_readiness: 0.0
  band: thin
  in_catalog: true
  kin_score: 30.4
  mcp: *id003
  name: Bench
  slug: bench
  status: profiled
  tags: *id004
  url: /providers/bench/
- agent_band: agent-ready
  agent_readiness: 59.9
  band: exemplar
  in_catalog: true
  kin_score: 72.5
  mcp: *id005
  name: Birdeye
  slug: birdeye
  status: profiled
  tags: *id006
  url: /providers/birdeye/
- agent_band: agent-ready
  agent_readiness: 34.4
  band: thin
  in_catalog: true
  kin_score: 35.4
  mcp: *id007
  name: Bookkeep.com
  slug: bookkeep-com
  status: profiled
  tags: *id008
  url: /providers/bookkeep-com/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 8.4
  mcp: *id009
  name: Brijpay
  slug: brijpay
  status: profiled
  tags: *id010
  url: /providers/brijpay/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 11.0
  mcp: *id011
  name: ClassPass
  slug: classpass
  status: profiled
  tags: *id012
  url: /providers/classpass/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id013
  name: DAVO Sales Tax
  slug: davo
  status: queued for profiling
  tags: *id014
  url: null
- agent_band: agent-aware
  agent_readiness: 7.7
  band: developing
  in_catalog: true
  kin_score: 47.1
  mcp: *id015
  name: Equifax
  slug: equifax
  status: profiled
  tags: *id016
  url: /providers/equifax/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 14.2
  mcp: *id017
  name: FitOn
  slug: fiton
  status: profiled
  tags: *id018
  url: /providers/fiton/
- agent_band: human-only
  agent_readiness: 2.5
  band: thin
  in_catalog: true
  kin_score: 29.6
  mcp: *id019
  name: Flozic by Appy Pie
  slug: appypie
  status: profiled
  tags: *id020
  url: /providers/appypie/
- agent_band: human-only
  agent_readiness: 3.0
  band: emerging
  in_catalog: true
  kin_score: 11.6
  mcp: *id021
  name: GymSales
  slug: gymsales
  status: profiled
  tags: *id022
  url: /providers/gymsales/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id023
  name: Healthdesk
  slug: healthdesk
  status: queued for profiling
  tags: *id024
  url: null
- agent_band: agent-ready
  agent_readiness: 52.0
  band: exemplar
  in_catalog: true
  kin_score: 91.9
  mcp: *id025
  name: HubSpot
  slug: hubspot
  status: profiled
  tags: *id026
  url: /providers/hubspot/
- agent_band: agent-aware
  agent_readiness: 6.2
  band: emerging
  in_catalog: true
  kin_score: 17.5
  mcp: *id027
  name: Keepme
  slug: keepme
  status: profiled
  tags: *id028
  url: /providers/keepme/
- agent_band: agent-ready
  agent_readiness: 34.1
  band: strong
  in_catalog: true
  kin_score: 57.6
  mcp: *id029
  name: Kisi
  slug: kisi
  status: profiled
  tags: *id030
  url: /providers/kisi/
- agent_band: agent-aware
  agent_readiness: 17.5
  band: emerging
  in_catalog: true
  kin_score: 22.7
  mcp: *id031
  name: Listen360
  slug: listen360
  status: profiled
  tags: *id032
  url: /providers/listen360/
- agent_band: human-only
  agent_readiness: 2.5
  band: emerging
  in_catalog: true
  kin_score: 18.4
  mcp: *id033
  name: NiceJob
  slug: nicejob
  status: profiled
  tags: *id034
  url: /providers/nicejob/
- agent_band: agent-ready
  agent_readiness: 38.1
  band: developing
  in_catalog: true
  kin_score: 42.6
  mcp: *id035
  name: Nift
  slug: nift
  status: profiled
  tags: *id036
  url: /providers/nift/
- agent_band: agent-ready
  agent_readiness: 29.3
  band: thin
  in_catalog: true
  kin_score: 37.8
  mcp: *id037
  name: Paychex
  slug: paychex-developer
  status: profiled
  tags: *id038
  url: /providers/paychex-developer/
- agent_band: agent-native
  agent_readiness: 40.1
  band: strong
  in_catalog: true
  kin_score: 59.1
  mcp: *id039
  name: Podium
  slug: podium
  status: profiled
  tags: *id040
  url: /providers/podium/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id041
  name: REACH ai
  slug: reach-ai
  status: queued for profiling
  tags: *id042
  url: null
- agent_band: agent-native
  agent_readiness: 55.0
  band: developing
  in_catalog: true
  kin_score: 52.3
  mcp: *id043
  name: Truemed
  slug: truemed
  status: profiled
  tags: *id044
  url: /providers/truemed/
siblings:
- name: Booksy Biz
  rows: 5
  url: /applications/salon-spa-management/booksy-biz/
- name: Boulevard
  rows: 16
  url: /applications/salon-spa-management/boulevard/
- name: Fresha
  rows: 6
  url: /applications/salon-spa-management/fresha/
- name: Open Salon
  rows: 2
  url: /applications/salon-spa-management/open-salon/
- name: Salon Booking System
  rows: 44
  url: /applications/salon-spa-management/salon-booking-system/
- name: Square Appointments
  rows: 32
  url: /applications/salon-spa-management/square-appointments/
- name: Vagaro
  rows: 2
  url: /applications/salon-spa-management/vagaro/
sitemap: true
title: 'Mindbody: Salon & Spa Management reference app'
---
