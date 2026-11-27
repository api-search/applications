---
app: Socotra
app_slug: socotra
app_url: https://www.socotra.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-610.50
  key: analytics-bi-management
  layer: domain
  name: Analytics & BI Management
  providers:
  - Cloverleaf Analytics
  url: /capabilities/analytics-bi-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-430.30
  key: contact-centre-operations-management
  layer: domain
  name: Contact Centre Operations Management
  providers:
  - Floatbot
  - Splice Software
  url: /capabilities/contact-centre-operations-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-150.10.30
  key: BC-150.10.30
  layer: domain
  name: Contract Execution Management
  providers:
  - DocuSign
  url: /capabilities/contract-management/
  via_parent: Contract Management
- attribution: Turbo EA
  id: BC-4270
  key: developer-platform-api-ecosystem-management
  layer: domain
  name: Developer Platform & API Ecosystem Management
  providers:
  - Unqork
  url: /capabilities/developer-platform-api-ecosystem-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-2160
  key: insurance-claims-management
  layer: domain
  name: Insurance Claims Management
  providers:
  - Five Sigma
  - Reserv
  - Snapsheet
  url: /capabilities/insurance-claims-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: domain
  name: Payment Processing Management
  providers:
  - Worldpay
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-2100.20
  key: product-rating-pricing-configuration
  layer: domain
  name: Product Rating & Pricing Configuration
  providers:
  - Coherent
  - Quantee
  url: /capabilities/product-rating-pricing-configuration/
  via_parent: null
- attribution: Turbo EA
  id: BC-600.50
  key: it-infrastructure-management
  layer: common
  name: IT Infrastructure Management
  providers:
  - Amazon Web Services
  url: /capabilities/it-infrastructure-management/
  via_parent: null
category:
  id: insurance-policy-claims
  name: Insurance Policy & Claims
  url: /applications/insurance-policy-claims/
counts:
  declared: 12
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.socotra.com/partners
integrations:
- capability:
    attribution: Turbo EA
    id: BC-600.50
    key: it-infrastructure-management
    name: IT Infrastructure Management
    url: /capabilities/it-infrastructure-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 37.9
    band: exemplar
    in_catalog: true
    kin_score: 68.5
    mcp: &id001
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-web-services
    status: profiled
    tags: &id002
    - Amazon
    - Amazon Web Services
    - Cloud
    - Networks
    url: /providers/amazon-web-services/
  layer: common
  name: Amazon Web Services
  provider: amazon-web-services
  says: lists Amazon Web Services as an integration
  source: https://www.socotra.com/partners
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-610.50
    key: analytics-bi-management
    name: Analytics & BI Management
    url: /capabilities/analytics-bi-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.7
    band: emerging
    in_catalog: true
    kin_score: 11.4
    mcp: &id003
      status: unchecked
    slug: cloverleaf-analytics
    status: profiled
    tags: &id004
    - Analytics
    - Artificial Intelligence
    - Company
    - Insurance
    url: /providers/cloverleaf-analytics/
  layer: domain
  name: Cloverleaf Analytics
  provider: cloverleaf-analytics
  says: lists Cloverleaf Analytics as an integration
  source: https://www.socotra.com/partners
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2100.20
    key: product-rating-pricing-configuration
    name: Product Rating & Pricing Configuration
    url: /capabilities/product-rating-pricing-configuration/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.1
    band: thin
    in_catalog: true
    kin_score: 32.3
    mcp: &id005
      status: unchecked
    slug: coherent-global
    status: profiled
    tags: &id006
    - Automation
    - Company
    - Excel
    - Insurance
    url: /providers/coherent-global/
  layer: domain
  name: Coherent
  provider: coherent-global
  says: lists Coherent as an integration
  source: https://www.socotra.com/partners
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-150.10.30
    key: BC-150.10.30
    name: Contract Execution Management
    url: /capabilities/contract-management/
    via_parent: Contract Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 34.7
    band: exemplar
    in_catalog: true
    kin_score: 71.5
    mcp: &id007
      source: https://www.docusign.com/products/mcp
      status: documented
    slug: docusign
    status: profiled
    tags: &id008
    - Agreements
    - Contracts
    - DocuSign
    - E-Signature
    url: /providers/docusign/
  layer: domain
  name: DocuSign
  provider: docusign
  says: lists DocuSign as an integration
  source: https://www.socotra.com/partners
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2160
    key: insurance-claims-management
    name: Insurance Claims Management
    url: /capabilities/insurance-claims-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 18.3
    band: minimal
    in_catalog: true
    kin_score: 8.8
    mcp: &id009
      status: unchecked
    slug: five-sigma
    status: profiled
    tags: &id010
    - Artificial Intelligence
    - Claims Management
    - Insurance
    - Software-as-a-Service
    url: /providers/five-sigma/
  layer: domain
  name: Five Sigma
  provider: five-sigma
  says: lists Five Sigma as an integration
  source: https://www.socotra.com/partners
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-430.30
    key: contact-centre-operations-management
    name: Contact Centre Operations Management
    url: /capabilities/contact-centre-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 17.8
    band: thin
    in_catalog: true
    kin_score: 29.3
    mcp: &id011
      status: unchecked
    slug: floatbot
    status: profiled
    tags: &id012
    - AI Platform
    - Conversational AI
    - Insurance
    - Voice AI
    url: /providers/floatbot/
  layer: domain
  name: Floatbot
  provider: floatbot
  says: lists Floatbot as an integration
  source: https://www.socotra.com/partners
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2100.20
    key: product-rating-pricing-configuration
    name: Product Rating & Pricing Configuration
    url: /capabilities/product-rating-pricing-configuration/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 7.2
    mcp: &id013
      status: unchecked
    slug: quantee
    status: profiled
    tags: &id014
    - Artificial Intelligence
    - Company
    - Data Analytics
    - Enterprise
    url: /providers/quantee/
  layer: domain
  name: Quantee
  provider: quantee
  says: lists Quantee as an integration
  source: https://www.socotra.com/partners
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2160
    key: insurance-claims-management
    name: Insurance Claims Management
    url: /capabilities/insurance-claims-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 9.7
    mcp: &id015
      status: unknown
    slug: reserv
    status: profiled
    tags: &id016
    - Claims Management
    - Company
    - Insurance
    - Insurtech
    url: /providers/reserv/
  layer: domain
  name: Reserv
  provider: reserv
  says: lists Reserv as an integration
  source: https://www.socotra.com/partners
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2160
    key: insurance-claims-management
    name: Insurance Claims Management
    url: /capabilities/insurance-claims-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 9.0
    mcp: &id017
      status: none
    slug: snapsheet
    status: profiled
    tags: &id018
    - Claims
    - Claims Management
    - Company
    - Insurance
    url: /providers/snapsheet/
  layer: domain
  name: Snapsheet
  provider: snapsheet
  says: lists Snapsheet as an integration
  source: https://www.socotra.com/partners
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-430.30
    key: contact-centre-operations-management
    name: Contact Centre Operations Management
    url: /capabilities/contact-centre-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: minimal
    in_catalog: true
    kin_score: 8.7
    mcp: &id019
      status: unchecked
    slug: splice-software
    status: profiled
    tags: &id020
    - Communication Platform
    - Company
    - Customer Engagement
    - Omnichannel
    url: /providers/splice-software/
  layer: domain
  name: Splice Software
  provider: splice-software
  says: lists Splice Software as an integration
  source: https://www.socotra.com/partners
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4270
    key: developer-platform-api-ecosystem-management
    name: Developer Platform & API Ecosystem Management
    url: /capabilities/developer-platform-api-ecosystem-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 41.4
    band: strong
    in_catalog: true
    kin_score: 64.8
    mcp: &id021
      status: unknown
    slug: unqork
    status: profiled
    tags: &id022
    - Application Development
    - Company
    - Low-Code
    - No-Code
    url: /providers/unqork/
  layer: domain
  name: Unqork
  provider: unqork
  says: lists Unqork as an integration
  source: https://www.socotra.com/partners
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
    agent_readiness: 45.1
    band: developing
    in_catalog: true
    kin_score: 48.9
    mcp: &id023
      status: none
    slug: worldpay
    status: profiled
    tags: &id024
    - Payment Gateway
    - Payment Processing
    - Payments
    - Tokenization
    url: /providers/worldpay/
  layer: domain
  name: Worldpay
  provider: worldpay
  says: lists Worldpay as an integration
  source: https://www.socotra.com/partners
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/insurance-policy-claims/socotra/
providers:
- agent_band: agent-ready
  agent_readiness: 37.9
  band: exemplar
  in_catalog: true
  kin_score: 68.5
  mcp: *id001
  name: Amazon Web Services
  slug: amazon-web-services
  status: profiled
  tags: *id002
  url: /providers/amazon-web-services/
- agent_band: human-only
  agent_readiness: 0.7
  band: emerging
  in_catalog: true
  kin_score: 11.4
  mcp: *id003
  name: Cloverleaf Analytics
  slug: cloverleaf-analytics
  status: profiled
  tags: *id004
  url: /providers/cloverleaf-analytics/
- agent_band: agent-aware
  agent_readiness: 24.1
  band: thin
  in_catalog: true
  kin_score: 32.3
  mcp: *id005
  name: Coherent
  slug: coherent-global
  status: profiled
  tags: *id006
  url: /providers/coherent-global/
- agent_band: agent-ready
  agent_readiness: 34.7
  band: exemplar
  in_catalog: true
  kin_score: 71.5
  mcp: *id007
  name: DocuSign
  slug: docusign
  status: profiled
  tags: *id008
  url: /providers/docusign/
- agent_band: agent-aware
  agent_readiness: 18.3
  band: minimal
  in_catalog: true
  kin_score: 8.8
  mcp: *id009
  name: Five Sigma
  slug: five-sigma
  status: profiled
  tags: *id010
  url: /providers/five-sigma/
- agent_band: agent-aware
  agent_readiness: 17.8
  band: thin
  in_catalog: true
  kin_score: 29.3
  mcp: *id011
  name: Floatbot
  slug: floatbot
  status: profiled
  tags: *id012
  url: /providers/floatbot/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 7.2
  mcp: *id013
  name: Quantee
  slug: quantee
  status: profiled
  tags: *id014
  url: /providers/quantee/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 9.7
  mcp: *id015
  name: Reserv
  slug: reserv
  status: profiled
  tags: *id016
  url: /providers/reserv/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 9.0
  mcp: *id017
  name: Snapsheet
  slug: snapsheet
  status: profiled
  tags: *id018
  url: /providers/snapsheet/
- agent_band: human-only
  agent_readiness: 3.0
  band: minimal
  in_catalog: true
  kin_score: 8.7
  mcp: *id019
  name: Splice Software
  slug: splice-software
  status: profiled
  tags: *id020
  url: /providers/splice-software/
- agent_band: agent-ready
  agent_readiness: 41.4
  band: strong
  in_catalog: true
  kin_score: 64.8
  mcp: *id021
  name: Unqork
  slug: unqork
  status: profiled
  tags: *id022
  url: /providers/unqork/
- agent_band: agent-native
  agent_readiness: 45.1
  band: developing
  in_catalog: true
  kin_score: 48.9
  mcp: *id023
  name: Worldpay
  slug: worldpay
  status: profiled
  tags: *id024
  url: /providers/worldpay/
siblings:
- name: Duck Creek
  rows: 11
  url: /applications/insurance-policy-claims/duck-creek/
- name: EZLynx
  rows: 13
  url: /applications/insurance-policy-claims/ezlynx/
- name: HawkSoft
  rows: 12
  url: /applications/insurance-policy-claims/hawksoft/
- name: Lemonade
  rows: 0
  url: /applications/insurance-policy-claims/lemonade/
- name: openIMIS
  rows: 6
  url: /applications/insurance-policy-claims/openimis/
sitemap: true
title: 'Socotra: Insurance Policy & Claims reference app'
---
