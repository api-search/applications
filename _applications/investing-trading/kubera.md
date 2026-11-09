---
app: Kubera
app_slug: kubera
app_url: https://www.kubera.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-190.30.10
  key: AE-190.30.10
  layer: domain
  name: Brokerage APIs
  providers:
  - SnapTrade
  url: /capabilities/retail-investing/
  via_parent: Retail Investing
- attribution: API Evangelist extension
  id: AE-190.50
  key: AE-190.50
  layer: domain
  name: Consumer Data Access
  providers:
  - Akahu
  - Akoya
  - Lean Technologies
  - Mastercard (Finicity open banking)
  - MX
  - Plaid
  - Salt Edge
  - Yodlee
  url: /capabilities/consumer-data-access/
  via_parent: null
- attribution: Turbo EA
  id: BC-430.50
  key: customer-feedback-management
  layer: common
  name: Customer Feedback Management
  providers:
  - REVIEWS.io
  url: /capabilities/customer-feedback-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-600.50
  key: it-infrastructure-management
  layer: common
  name: IT Infrastructure Management
  providers:
  - AWS
  url: /capabilities/it-infrastructure-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-160.10.30
  key: AE-160.10.30
  layer: common
  name: Social & Federated Login
  providers:
  - Google sign-in
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
category:
  id: investing-trading
  name: Investing & Trading
  url: /applications/investing-trading/
counts:
  declared: 12
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.kubera.com/security
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-190.50
    key: AE-190.50
    name: Consumer Data Access
    url: /capabilities/consumer-data-access/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.8
    band: developing
    in_catalog: true
    kin_score: 47.6
    mcp: &id001
      status: none
    slug: akahu
    status: profiled
    tags: &id002
    - Company
    - Finance
    - New Zealand
    - Open Banking
    url: /providers/akahu/
  layer: domain
  name: Akahu
  provider: akahu
  says: lists Akahu as an integration
  source: https://www.kubera.com/security
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-190.50
    key: AE-190.50
    name: Consumer Data Access
    url: /capabilities/consumer-data-access/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 21.1
    band: developing
    in_catalog: true
    kin_score: 53.6
    mcp: &id003
      status: none
    slug: akoya
    status: profiled
    tags: &id004
    - Aggregator
    - Fintech
    - Open Banking
    - Open Finance
    url: /providers/akoya/
  layer: domain
  name: Akoya
  provider: akoya
  says: lists Akoya as an integration
  source: https://www.kubera.com/security
  tier: declared
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
    agent_readiness: 40.8
    band: strong
    in_catalog: true
    kin_score: 60.5
    mcp: &id005
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-web-services
    status: profiled
    tags: &id006
    - Amazon
    - Amazon Web Services
    - Cloud
    - Networks
    url: /providers/amazon-web-services/
  layer: common
  name: AWS
  provider: amazon-web-services
  says: lists AWS as an integration
  source: https://www.kubera.com/security
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 19.6
    band: thin
    in_catalog: true
    kin_score: 36.8
    mcp: &id007
      status: none
    slug: google-identity-platform
    status: profiled
    tags: &id008
    - Authentication
    - Google Cloud
    - Identity
    - Multi-Tenancy
    url: /providers/google-identity-platform/
  layer: common
  name: Google sign-in
  provider: google-identity-platform
  says: lists Google sign-in as an integration
  source: https://www.kubera.com/security
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-190.50
    key: AE-190.50
    name: Consumer Data Access
    url: /capabilities/consumer-data-access/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 53.0
    band: developing
    in_catalog: true
    kin_score: 52.5
    mcp: &id009
      status: none
    slug: lean-technologies
    status: profiled
    tags: &id010
    - Financial Data
    - Open Banking
    - Open Finance
    - Payments
    url: /providers/lean-technologies/
  layer: domain
  name: Lean Technologies
  provider: lean-technologies
  says: lists Lean Technologies as an integration
  source: https://www.kubera.com/security
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-190.50
    key: AE-190.50
    name: Consumer Data Access
    url: /capabilities/consumer-data-access/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 44.2
    band: strong
    in_catalog: true
    kin_score: 57.3
    mcp: &id011
      source: https://github.com/Mastercard/developers-agent-toolkit
      status: verified
    slug: mastercard
    status: profiled
    tags: &id012
    - Credit Cards
    - Digital Identity
    - Financial Services
    - Mastercard
    url: /providers/mastercard/
  layer: domain
  name: Mastercard (Finicity open banking)
  provider: mastercard
  says: lists Mastercard (Finicity open banking) as an integration
  source: https://www.kubera.com/security
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-190.50
    key: AE-190.50
    name: Consumer Data Access
    url: /capabilities/consumer-data-access/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 26.7
    band: strong
    in_catalog: true
    kin_score: 65.0
    mcp: &id013
      status: none
    slug: mx-technologies
    status: profiled
    tags: &id014
    - Account Aggregation
    - Data Connectivity
    - Financial Data
    - Open Banking
    url: /providers/mx-technologies/
  layer: domain
  name: MX
  provider: mx-technologies
  says: lists MX as an integration
  source: https://www.kubera.com/security
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-190.50
    key: AE-190.50
    name: Consumer Data Access
    url: /capabilities/consumer-data-access/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 52.1
    band: exemplar
    in_catalog: true
    kin_score: 83.4
    mcp: &id015
      source: https://plaid.com/docs/resources/mcp/
      status: verified
    slug: plaid
    status: profiled
    tags: &id016
    - Bank Accounts
    - Finance
    - Fintech
    - Open Banking
    url: /providers/plaid/
  layer: domain
  name: Plaid
  provider: plaid
  says: lists Plaid as an integration
  source: https://www.kubera.com/security
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-430.50
    key: customer-feedback-management
    name: Customer Feedback Management
    url: /capabilities/customer-feedback-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 19.0
    band: thin
    in_catalog: true
    kin_score: 28.1
    mcp: &id017
      status: none
    slug: reviews-io
    status: profiled
    tags: &id018
    - Ratings
    - Reputation
    - Reviews
    - UGC
    url: /providers/reviews-io/
  layer: common
  name: REVIEWS.io
  provider: reviews-io
  says: lists REVIEWS.io as an integration
  source: https://www.kubera.com/security
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-190.50
    key: AE-190.50
    name: Consumer Data Access
    url: /capabilities/consumer-data-access/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 22.4
    band: thin
    in_catalog: true
    kin_score: 26.9
    mcp: &id019
      status: none
    slug: salt-edge
    status: profiled
    tags: &id020
    - Aggregator
    - Fintech
    - Open Banking
    - PSD2
    url: /providers/salt-edge/
  layer: domain
  name: Salt Edge
  provider: salt-edge
  says: lists Salt Edge as an integration
  source: https://www.kubera.com/security
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-190.30.10
    key: AE-190.30.10
    name: Brokerage APIs
    url: /capabilities/retail-investing/
    via_parent: Retail Investing
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 53.2
    band: developing
    in_catalog: true
    kin_score: 50.5
    mcp: &id021
      source: https://docs.snaptrade.com/docs/mcp-server
      status: verified
    slug: snaptrade
    status: profiled
    tags: &id022
    - Brokerage
    - Company
    - Fintech
    - Trading
    url: /providers/snaptrade/
  layer: domain
  name: SnapTrade
  provider: snaptrade
  says: lists SnapTrade as an integration
  source: https://www.kubera.com/security
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-190.50
    key: AE-190.50
    name: Consumer Data Access
    url: /capabilities/consumer-data-access/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 21.0
    band: thin
    in_catalog: true
    kin_score: 31.1
    mcp: &id023
      status: none
    slug: yodlee
    status: profiled
    tags: &id024
    - Banking
    - Data Aggregation
    - Financial Data
    - Fintech
    url: /providers/yodlee/
  layer: domain
  name: Yodlee
  provider: yodlee
  says: lists Yodlee as an integration
  source: https://www.kubera.com/security
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/investing-trading/kubera/
providers:
- agent_band: agent-ready
  agent_readiness: 33.8
  band: developing
  in_catalog: true
  kin_score: 47.6
  mcp: *id001
  name: Akahu
  slug: akahu
  status: profiled
  tags: *id002
  url: /providers/akahu/
- agent_band: agent-aware
  agent_readiness: 21.1
  band: developing
  in_catalog: true
  kin_score: 53.6
  mcp: *id003
  name: Akoya
  slug: akoya
  status: profiled
  tags: *id004
  url: /providers/akoya/
- agent_band: agent-ready
  agent_readiness: 40.8
  band: strong
  in_catalog: true
  kin_score: 60.5
  mcp: *id005
  name: AWS
  slug: amazon-web-services
  status: profiled
  tags: *id006
  url: /providers/amazon-web-services/
- agent_band: agent-aware
  agent_readiness: 19.6
  band: thin
  in_catalog: true
  kin_score: 36.8
  mcp: *id007
  name: Google sign-in
  slug: google-identity-platform
  status: profiled
  tags: *id008
  url: /providers/google-identity-platform/
- agent_band: agent-native
  agent_readiness: 53.0
  band: developing
  in_catalog: true
  kin_score: 52.5
  mcp: *id009
  name: Lean Technologies
  slug: lean-technologies
  status: profiled
  tags: *id010
  url: /providers/lean-technologies/
- agent_band: agent-native
  agent_readiness: 44.2
  band: strong
  in_catalog: true
  kin_score: 57.3
  mcp: *id011
  name: Mastercard (Finicity open banking)
  slug: mastercard
  status: profiled
  tags: *id012
  url: /providers/mastercard/
- agent_band: agent-aware
  agent_readiness: 26.7
  band: strong
  in_catalog: true
  kin_score: 65.0
  mcp: *id013
  name: MX
  slug: mx-technologies
  status: profiled
  tags: *id014
  url: /providers/mx-technologies/
- agent_band: agent-native
  agent_readiness: 52.1
  band: exemplar
  in_catalog: true
  kin_score: 83.4
  mcp: *id015
  name: Plaid
  slug: plaid
  status: profiled
  tags: *id016
  url: /providers/plaid/
- agent_band: agent-aware
  agent_readiness: 19.0
  band: thin
  in_catalog: true
  kin_score: 28.1
  mcp: *id017
  name: REVIEWS.io
  slug: reviews-io
  status: profiled
  tags: *id018
  url: /providers/reviews-io/
- agent_band: agent-aware
  agent_readiness: 22.4
  band: thin
  in_catalog: true
  kin_score: 26.9
  mcp: *id019
  name: Salt Edge
  slug: salt-edge
  status: profiled
  tags: *id020
  url: /providers/salt-edge/
- agent_band: agent-ready
  agent_readiness: 53.2
  band: developing
  in_catalog: true
  kin_score: 50.5
  mcp: *id021
  name: SnapTrade
  slug: snaptrade
  status: profiled
  tags: *id022
  url: /providers/snaptrade/
- agent_band: agent-aware
  agent_readiness: 21.0
  band: thin
  in_catalog: true
  kin_score: 31.1
  mcp: *id023
  name: Yodlee
  slug: yodlee
  status: profiled
  tags: *id024
  url: /providers/yodlee/
siblings:
- name: Freqtrade
  rows: 21
  url: /applications/investing-trading/freqtrade/
- name: Ghostfolio
  rows: 13
  url: /applications/investing-trading/ghostfolio/
- name: Portfolio Performance
  rows: 16
  url: /applications/investing-trading/portfolio-performance/
- name: Robinhood
  rows: 10
  url: /applications/investing-trading/robinhood/
- name: rotki
  rows: 40
  url: /applications/investing-trading/rotki/
- name: Wealthfolio
  rows: 16
  url: /applications/investing-trading/wealthfolio/
sitemap: true
title: 'Kubera: Investing & Trading reference app'
---
