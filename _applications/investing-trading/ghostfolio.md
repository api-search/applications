---
app: Ghostfolio
app_slug: ghostfolio
app_url: https://github.com/ghostfolio/ghostfolio
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-230.20
  key: AE-230.20
  layer: domain
  name: Market & Financial Data
  providers:
  - OpenFIGI
  - RapidAPI (Fear & Greed Index)
  url: /capabilities/market-financial-data/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-230.20.20
  key: AE-230.20.20
  layer: domain
  name: Securities Market Data
  providers:
  - Alpha Vantage
  - CoinGecko
  - EODHD (EOD Historical Data)
  - Financial Modeling Prep
  - Google Sheets
  - Trackinsight
  - Yahoo Finance
  url: /capabilities/market-financial-data/
  via_parent: Market & Financial Data
- attribution: API Evangelist extension
  id: AE-110.10.30
  key: AE-110.10.30
  layer: common
  name: Model Routing & Gateways
  providers:
  - OpenRouter
  url: /capabilities/model-inference/
  via_parent: Model Inference
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: common
  name: Payment Processing Management
  providers:
  - Stripe
  url: /capabilities/payment-processing-management/
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
- attribution: API Evangelist extension
  id: AE-170.50
  key: AE-170.50
  layer: common
  name: Social Networks & Community
  providers:
  - X (Twitter)
  url: /capabilities/social-networks-community/
  via_parent: null
category:
  id: investing-trading
  name: Investing & Trading
  url: /applications/investing-trading/
counts:
  declared: 0
  observed: 13
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/ghostfolio/ghostfolio/main/package.json
- route: source code
  url: https://github.com/ghostfolio/ghostfolio/tree/main/apps/api/src/services/data-provider
- route: source code
  url: https://github.com/ghostfolio/ghostfolio/tree/main/apps/api/src/services/data-provider/data-enhancer
- route: source code
  url: https://raw.githubusercontent.com/ghostfolio/ghostfolio/main/apps/api/src/services/data-provider/rapid-api/rapid-api.service.ts
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-230.20.20
    key: AE-230.20.20
    name: Securities Market Data
    url: /capabilities/market-financial-data/
    via_parent: Market & Financial Data
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 50.5
    band: developing
    in_catalog: true
    kin_score: 50.6
    mcp: &id001
      source: https://github.com/alphavantage/alpha_vantage_mcp
      status: verified
    slug: alpha-vantage
    status: profiled
    tags: &id002
    - Fintech
    - Foreign Exchange
    - Market Data
    - Stocks
    url: /providers/alpha-vantage/
  layer: domain
  name: Alpha Vantage
  provider: alpha-vantage
  says: ships the Alpha Vantage SDK or integration code
  source: https://github.com/ghostfolio/ghostfolio/tree/main/apps/api/src/services/data-provider
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-230.20.20
    key: AE-230.20.20
    name: Securities Market Data
    url: /capabilities/market-financial-data/
    via_parent: Market & Financial Data
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 47.4
    band: developing
    in_catalog: true
    kin_score: 52.4
    mcp: &id003
      source: https://docs.coingecko.com/reference/mcp-server
      status: verified
    slug: coingecko
    status: profiled
    tags: &id004
    - Aggregator
    - Blockchain
    - CoinGecko
    - Cryptocurrency
    url: /providers/coingecko/
  layer: domain
  name: CoinGecko
  provider: coingecko
  says: ships the CoinGecko SDK or integration code
  source: https://github.com/ghostfolio/ghostfolio/tree/main/apps/api/src/services/data-provider
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-230.20.20
    key: AE-230.20.20
    name: Securities Market Data
    url: /capabilities/market-financial-data/
    via_parent: Market & Financial Data
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 53.1
    band: strong
    in_catalog: true
    kin_score: 60.7
    mcp: &id005
      source: https://github.com/EodHistoricalData/EODHD-MCP-Server
      status: verified
    slug: eodhd
    status: profiled
    tags: &id006
    - Finance
    - Market Data
    - Stock Options
    - Stocks
    url: /providers/eodhd/
  layer: domain
  name: EODHD (EOD Historical Data)
  provider: eodhd
  says: ships the EODHD (EOD Historical Data) SDK or integration code
  source: https://github.com/ghostfolio/ghostfolio/tree/main/apps/api/src/services/data-provider
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-230.20.20
    key: AE-230.20.20
    name: Securities Market Data
    url: /capabilities/market-financial-data/
    via_parent: Market & Financial Data
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 49.6
    band: exemplar
    in_catalog: true
    kin_score: 69.0
    mcp: &id007
      status: none
    slug: financial-modeling-prep
    status: profiled
    tags: &id008
    - Financial Data
    - Market Data
    - Quotes
    - Stocks
    url: /providers/financial-modeling-prep/
  layer: domain
  name: Financial Modeling Prep
  provider: financial-modeling-prep
  says: ships the Financial Modeling Prep SDK or integration code
  source: https://github.com/ghostfolio/ghostfolio/tree/main/apps/api/src/services/data-provider
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-230.20.20
    key: AE-230.20.20
    name: Securities Market Data
    url: /capabilities/market-financial-data/
    via_parent: Market & Financial Data
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 30.1
    band: strong
    in_catalog: true
    kin_score: 63.8
    mcp: &id009
      status: none
    slug: google-sheets
    status: profiled
    tags: &id010
    - Google Workspace
    - Productivity
    - Spreadsheets
    url: /providers/google-sheets/
  layer: domain
  name: Google Sheets
  provider: google-sheets
  says: ships the Google Sheets SDK or integration code
  source: https://github.com/ghostfolio/ghostfolio/tree/main/apps/api/src/services/data-provider
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.7
    band: strong
    in_catalog: true
    kin_score: 58.8
    mcp: &id011
      status: none
    slug: google-identity-platform
    status: profiled
    tags: &id012
    - Authentication
    - Google Cloud
    - Identity
    - Multi-Tenancy
    url: /providers/google-identity-platform/
  layer: common
  name: Google sign-in
  provider: google-identity-platform
  says: ships the Google sign-in SDK or integration code
  source: https://raw.githubusercontent.com/ghostfolio/ghostfolio/main/package.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-230.20
    key: AE-230.20
    name: Market & Financial Data
    url: /capabilities/market-financial-data/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.9
    band: thin
    in_catalog: true
    kin_score: 32.2
    mcp: &id013
      status: none
    slug: openfigi
    status: profiled
    tags: &id014
    - Finance
    - Instruments
    url: /providers/openfigi/
  layer: domain
  name: OpenFIGI
  provider: openfigi
  says: ships the OpenFIGI SDK or integration code
  source: https://github.com/ghostfolio/ghostfolio/tree/main/apps/api/src/services/data-provider/data-enhancer
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.30
    key: AE-110.10.30
    name: Model Routing & Gateways
    url: /capabilities/model-inference/
    via_parent: Model Inference
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 46.4
    band: strong
    in_catalog: true
    kin_score: 54.8
    mcp: &id015
      source: https://openrouter.ai/docs/guides/overview/mcp-server
      status: verified
    slug: openrouter
    status: profiled
    tags: &id016
    - Artificial Intelligence
    - Gateways
    - LLM
    - Router
    url: /providers/openrouter/
  layer: common
  name: OpenRouter
  provider: openrouter
  says: ships the OpenRouter SDK or integration code
  source: https://raw.githubusercontent.com/ghostfolio/ghostfolio/main/package.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-230.20
    key: AE-230.20
    name: Market & Financial Data
    url: /capabilities/market-financial-data/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 32.6
    band: developing
    in_catalog: true
    kin_score: 39.5
    mcp: &id017
      status: none
    slug: rapidapi
    status: profiled
    tags: &id018
    - API Gateway
    - API Management
    - API Marketplace
    - API Testing
    url: /providers/rapidapi/
  layer: domain
  name: RapidAPI (Fear & Greed Index)
  provider: rapidapi
  says: ships the RapidAPI (Fear & Greed Index) SDK or integration code
  source: https://raw.githubusercontent.com/ghostfolio/ghostfolio/main/apps/api/src/services/data-provider/rapid-api/rapid-api.service.ts
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
    agent_readiness: 57.6
    band: exemplar
    in_catalog: true
    kin_score: 82.0
    mcp: &id019
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id020
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
  layer: common
  name: Stripe
  provider: stripe
  says: ships the Stripe SDK or integration code
  source: https://raw.githubusercontent.com/ghostfolio/ghostfolio/main/package.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-230.20.20
    key: AE-230.20.20
    name: Securities Market Data
    url: /capabilities/market-financial-data/
    via_parent: Market & Financial Data
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 1.1
    mcp: &id021
      status: none
    slug: trackinsight
    status: profiled
    tags: &id022
    - Company
    url: /providers/trackinsight/
  layer: domain
  name: Trackinsight
  provider: trackinsight
  says: ships the Trackinsight SDK or integration code
  source: https://github.com/ghostfolio/ghostfolio/tree/main/apps/api/src/services/data-provider/data-enhancer
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.50
    key: AE-170.50
    name: Social Networks & Community
    url: /capabilities/social-networks-community/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 59.9
    band: exemplar
    in_catalog: true
    kin_score: 75.0
    mcp: &id023
      source: https://github.com/xdevplatform/xmcp
      status: verified
    slug: x
    status: profiled
    tags: &id024
    - Conversations
    - Social
    - Spaces
    - X
    url: /providers/x/
  layer: common
  name: X (Twitter)
  provider: x
  says: ships the X (Twitter) SDK or integration code
  source: https://raw.githubusercontent.com/ghostfolio/ghostfolio/main/package.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-230.20.20
    key: AE-230.20.20
    name: Securities Market Data
    url: /capabilities/market-financial-data/
    via_parent: Market & Financial Data
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 15.8
    band: developing
    in_catalog: true
    kin_score: 42.6
    mcp: &id025
      status: none
    slug: yahoo
    status: profiled
    tags: &id026
    - Advertising
    - DSP
    - Fantasy Sports
    - Programmatic Advertising
    url: /providers/yahoo/
  layer: domain
  name: Yahoo Finance
  provider: yahoo
  says: ships the Yahoo Finance SDK or integration code
  source: https://raw.githubusercontent.com/ghostfolio/ghostfolio/main/package.json
  tier: observed
kind: open-source-saas
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/investing-trading/ghostfolio/
providers:
- agent_band: agent-ready
  agent_readiness: 50.5
  band: developing
  in_catalog: true
  kin_score: 50.6
  mcp: *id001
  name: Alpha Vantage
  slug: alpha-vantage
  status: profiled
  tags: *id002
  url: /providers/alpha-vantage/
- agent_band: agent-ready
  agent_readiness: 47.4
  band: developing
  in_catalog: true
  kin_score: 52.4
  mcp: *id003
  name: CoinGecko
  slug: coingecko
  status: profiled
  tags: *id004
  url: /providers/coingecko/
- agent_band: agent-ready
  agent_readiness: 53.1
  band: strong
  in_catalog: true
  kin_score: 60.7
  mcp: *id005
  name: EODHD (EOD Historical Data)
  slug: eodhd
  status: profiled
  tags: *id006
  url: /providers/eodhd/
- agent_band: agent-native
  agent_readiness: 49.6
  band: exemplar
  in_catalog: true
  kin_score: 69.0
  mcp: *id007
  name: Financial Modeling Prep
  slug: financial-modeling-prep
  status: profiled
  tags: *id008
  url: /providers/financial-modeling-prep/
- agent_band: agent-ready
  agent_readiness: 30.1
  band: strong
  in_catalog: true
  kin_score: 63.8
  mcp: *id009
  name: Google Sheets
  slug: google-sheets
  status: profiled
  tags: *id010
  url: /providers/google-sheets/
- agent_band: agent-ready
  agent_readiness: 33.7
  band: strong
  in_catalog: true
  kin_score: 58.8
  mcp: *id011
  name: Google sign-in
  slug: google-identity-platform
  status: profiled
  tags: *id012
  url: /providers/google-identity-platform/
- agent_band: agent-aware
  agent_readiness: 25.9
  band: thin
  in_catalog: true
  kin_score: 32.2
  mcp: *id013
  name: OpenFIGI
  slug: openfigi
  status: profiled
  tags: *id014
  url: /providers/openfigi/
- agent_band: agent-ready
  agent_readiness: 46.4
  band: strong
  in_catalog: true
  kin_score: 54.8
  mcp: *id015
  name: OpenRouter
  slug: openrouter
  status: profiled
  tags: *id016
  url: /providers/openrouter/
- agent_band: agent-ready
  agent_readiness: 32.6
  band: developing
  in_catalog: true
  kin_score: 39.5
  mcp: *id017
  name: RapidAPI (Fear & Greed Index)
  slug: rapidapi
  status: profiled
  tags: *id018
  url: /providers/rapidapi/
- agent_band: agent-native
  agent_readiness: 57.6
  band: exemplar
  in_catalog: true
  kin_score: 82.0
  mcp: *id019
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id020
  url: /providers/stripe/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 1.1
  mcp: *id021
  name: Trackinsight
  slug: trackinsight
  status: profiled
  tags: *id022
  url: /providers/trackinsight/
- agent_band: agent-native
  agent_readiness: 59.9
  band: exemplar
  in_catalog: true
  kin_score: 75.0
  mcp: *id023
  name: X (Twitter)
  slug: x
  status: profiled
  tags: *id024
  url: /providers/x/
- agent_band: agent-aware
  agent_readiness: 15.8
  band: developing
  in_catalog: true
  kin_score: 42.6
  mcp: *id025
  name: Yahoo Finance
  slug: yahoo
  status: profiled
  tags: *id026
  url: /providers/yahoo/
siblings:
- name: Freqtrade
  rows: 21
  url: /applications/investing-trading/freqtrade/
- name: Kubera
  rows: 12
  url: /applications/investing-trading/kubera/
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
title: 'Ghostfolio: Investing & Trading reference app'
---
