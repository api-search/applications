---
app: Wealthfolio
app_slug: wealthfolio
app_url: https://github.com/wealthfolio/wealthfolio
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
  id: AE-230.20
  key: AE-230.20
  layer: domain
  name: Market & Financial Data
  providers:
  - Metal Price API
  - OpenFIGI
  - US Treasury (treasury.gov / TreasuryDirect)
  url: /capabilities/market-financial-data/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-230.20.20
  key: AE-230.20.20
  layer: domain
  name: Securities Market Data
  providers:
  - Alpha Vantage
  - Boerse Frankfurt (Deutsche Boerse)
  - Finnhub
  - Market Data (marketdata.app)
  - Yahoo Finance
  url: /capabilities/market-financial-data/
  via_parent: Market & Financial Data
- attribution: API Evangelist extension
  id: AE-110.10.10
  key: AE-110.10.10
  layer: common
  name: Hosted LLM Inference
  providers:
  - Anthropic
  - Google AI (Gemini)
  - Groq
  - Ollama
  - OpenAI
  url: /capabilities/model-inference/
  via_parent: Model Inference
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
  id: BC-600.50.20
  key: BC-600.50.20
  layer: common
  name: Storage Management
  providers:
  - Cloudflare R2
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
category:
  id: investing-trading
  name: Investing & Trading
  url: /applications/investing-trading/
counts:
  declared: 0
  observed: 16
credits: []
evidence:
- route: source code
  url: https://github.com/wealthfolio/wealthfolio/tree/main/crates/market-data/src/provider
- route: source code
  url: https://raw.githubusercontent.com/wealthfolio/wealthfolio/main/config/connect.defaults.json
- route: source code
  url: https://raw.githubusercontent.com/wealthfolio/wealthfolio/main/crates/ai/src/ai_providers.json
- route: source code
  url: https://raw.githubusercontent.com/wealthfolio/wealthfolio/main/crates/connect/src/broker/models.rs
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
  source: https://github.com/wealthfolio/wealthfolio/tree/main/crates/market-data/src/provider
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 46.6
    band: exemplar
    in_catalog: true
    kin_score: 86.4
    mcp: &id003
      source: https://docs.anthropic.com/en/docs/agents-and-tools/mcp-connector
      status: verified
    slug: anthropic
    status: profiled
    tags: &id004
    - Anthropic
    - Artificial Intelligence
    - Claude
    - LLM
    url: /providers/anthropic/
  layer: common
  name: Anthropic
  provider: anthropic
  says: ships the Anthropic SDK or integration code
  source: https://raw.githubusercontent.com/wealthfolio/wealthfolio/main/crates/ai/src/ai_providers.json
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
    agent_readiness: 27.2
    band: developing
    in_catalog: true
    kin_score: 52.9
    mcp: &id005
      status: none
    slug: deutsche-boerse
    status: profiled
    tags: &id006
    - Derivatives
    - Finance
    - Market Data
    - Stocks
    url: /providers/deutsche-boerse/
  layer: domain
  name: Boerse Frankfurt (Deutsche Boerse)
  provider: deutsche-boerse
  says: ships the Boerse Frankfurt (Deutsche Boerse) SDK or integration code
  source: https://raw.githubusercontent.com/wealthfolio/wealthfolio/main/crates/market-data/src/provider/boerse_frankfurt/mod.rs
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-600.50.20
    key: BC-600.50.20
    name: Storage Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 28.7
    band: thin
    in_catalog: true
    kin_score: 35.8
    mcp: &id007
      source: https://raw.githubusercontent.com/cloudflare/mcp/main/README.md
      status: verified
    slug: cloudflare-r2
    status: profiled
    tags: &id008
    - Cloud Storage
    - Egress-Free
    - Object Storage
    - S3 Compatible
    url: /providers/cloudflare-r2/
  layer: common
  name: Cloudflare R2
  provider: cloudflare-r2
  says: ships the Cloudflare R2 SDK or integration code
  source: https://raw.githubusercontent.com/wealthfolio/wealthfolio/main/config/connect.defaults.json
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
    agent_readiness: 23.1
    band: developing
    in_catalog: true
    kin_score: 42.5
    mcp: &id009
      source: https://finnhub.io/docs/api
      status: documented
    slug: finnhub
    status: profiled
    tags: &id010
    - Finance
    - Foreign Exchange
    - Market Data
    - Stocks
    url: /providers/finnhub/
  layer: domain
  name: Finnhub
  provider: finnhub
  says: ships the Finnhub SDK or integration code
  source: https://github.com/wealthfolio/wealthfolio/tree/main/crates/market-data/src/provider
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 35.0
    band: strong
    in_catalog: true
    kin_score: 61.7
    mcp: &id011
      status: none
    slug: google-gemini
    status: profiled
    tags: &id012
    - AI Agents
    - Artificial Intelligence
    - Code Generation
    - Embeddings
    url: /providers/google-gemini/
  layer: common
  name: Google AI (Gemini)
  provider: google-gemini
  says: ships the Google AI (Gemini) SDK or integration code
  source: https://raw.githubusercontent.com/wealthfolio/wealthfolio/main/crates/ai/src/ai_providers.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 21.2
    band: thin
    in_catalog: true
    kin_score: 32.3
    mcp: &id013
      source: https://github.com/groq/groq-mcp-server
      status: verified
    slug: groq
    status: profiled
    tags: &id014
    - Artificial Intelligence
    - Inference
    - LLM
    - LPU
    url: /providers/groq/
  layer: common
  name: Groq
  provider: groq
  says: ships the Groq SDK or integration code
  source: https://raw.githubusercontent.com/wealthfolio/wealthfolio/main/crates/ai/src/ai_providers.json
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
    agent_readiness: 32.2
    band: strong
    in_catalog: true
    kin_score: 59.3
    mcp: &id015
      status: none
    slug: marketdata-app
    status: profiled
    tags: &id016
    - Financial Data
    - Market Data
    - Options
    - Stocks
    url: /providers/marketdata-app/
  layer: domain
  name: Market Data (marketdata.app)
  provider: marketdata-app
  says: ships the Market Data (marketdata.app) SDK or integration code
  source: https://github.com/wealthfolio/wealthfolio/tree/main/crates/market-data/src/provider
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
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 22.4
    mcp: &id017
      status: none
    slug: metalpriceapi
    status: profiled
    tags: &id018
    - Company
    - Data
    - Finance
    - Metals
    url: /providers/metalpriceapi/
  layer: domain
  name: Metal Price API
  provider: metalpriceapi
  says: ships the Metal Price API SDK or integration code
  source: https://raw.githubusercontent.com/wealthfolio/wealthfolio/main/crates/market-data/src/provider/metal_price_api/mod.rs
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.4
    band: thin
    in_catalog: true
    kin_score: 37.7
    mcp: &id019
      status: none
    slug: ollama
    status: profiled
    tags: &id020
    - Artificial Intelligence
    - LLM
    - Models
    - Ollama
    url: /providers/ollama/
  layer: common
  name: Ollama
  provider: ollama
  says: ships the Ollama SDK or integration code
  source: https://raw.githubusercontent.com/wealthfolio/wealthfolio/main/crates/ai/src/ai_providers.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 57.5
    band: exemplar
    in_catalog: true
    kin_score: 82.5
    mcp: &id021
      source: https://platform.openai.com/docs/mcp
      status: verified
    slug: openai
    status: profiled
    tags: &id022
    - Artificial Intelligence
    - Generative AI
    - LLM
    - OpenAI
    url: /providers/openai/
  layer: common
  name: OpenAI
  provider: openai
  says: ships the OpenAI SDK or integration code
  source: https://raw.githubusercontent.com/wealthfolio/wealthfolio/main/crates/ai/src/ai_providers.json
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
    mcp: &id023
      status: none
    slug: openfigi
    status: profiled
    tags: &id024
    - Finance
    - Instruments
    url: /providers/openfigi/
  layer: domain
  name: OpenFIGI
  provider: openfigi
  says: ships the OpenFIGI SDK or integration code
  source: https://github.com/wealthfolio/wealthfolio/tree/main/crates/market-data/src/provider
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
    mcp: &id025
      source: https://openrouter.ai/docs/guides/overview/mcp-server
      status: verified
    slug: openrouter
    status: profiled
    tags: &id026
    - Artificial Intelligence
    - Gateways
    - LLM
    - Router
    url: /providers/openrouter/
  layer: common
  name: OpenRouter
  provider: openrouter
  says: ships the OpenRouter SDK or integration code
  source: https://raw.githubusercontent.com/wealthfolio/wealthfolio/main/crates/ai/src/ai_providers.json
  tier: observed
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
    agent_readiness: 46.1
    band: strong
    in_catalog: true
    kin_score: 59.0
    mcp: &id027
      source: https://docs.snaptrade.com/docs/mcp-server
      status: verified
    slug: snaptrade
    status: profiled
    tags: &id028
    - Brokerage
    - Company
    - Fintech
    - Trading
    url: /providers/snaptrade/
  layer: domain
  name: SnapTrade
  provider: snaptrade
  says: ships the SnapTrade SDK or integration code
  source: https://raw.githubusercontent.com/wealthfolio/wealthfolio/main/crates/connect/src/broker/models.rs
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
    agent_readiness: 19.6
    band: thin
    in_catalog: true
    kin_score: 29.1
    mcp: &id029
      status: none
    slug: department-of-the-treasury
    status: profiled
    tags: &id030
    - Debt
    - Federal Government
    - Finance
    - Sanctions
    url: /providers/department-of-the-treasury/
  layer: domain
  name: US Treasury (treasury.gov / TreasuryDirect)
  provider: department-of-the-treasury
  says: ships the US Treasury (treasury.gov / TreasuryDirect) SDK or integration code
  source: https://raw.githubusercontent.com/wealthfolio/wealthfolio/main/crates/market-data/src/provider/us_treasury_calc/mod.rs
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
    mcp: &id031
      status: none
    slug: yahoo
    status: profiled
    tags: &id032
    - Advertising
    - DSP
    - Fantasy Sports
    - Programmatic Advertising
    url: /providers/yahoo/
  layer: domain
  name: Yahoo Finance
  provider: yahoo
  says: ships the Yahoo Finance SDK or integration code
  source: https://github.com/wealthfolio/wealthfolio/tree/main/crates/market-data/src/provider
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/investing-trading/wealthfolio/
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
  agent_readiness: 46.6
  band: exemplar
  in_catalog: true
  kin_score: 86.4
  mcp: *id003
  name: Anthropic
  slug: anthropic
  status: profiled
  tags: *id004
  url: /providers/anthropic/
- agent_band: agent-aware
  agent_readiness: 27.2
  band: developing
  in_catalog: true
  kin_score: 52.9
  mcp: *id005
  name: Boerse Frankfurt (Deutsche Boerse)
  slug: deutsche-boerse
  status: profiled
  tags: *id006
  url: /providers/deutsche-boerse/
- agent_band: agent-ready
  agent_readiness: 28.7
  band: thin
  in_catalog: true
  kin_score: 35.8
  mcp: *id007
  name: Cloudflare R2
  slug: cloudflare-r2
  status: profiled
  tags: *id008
  url: /providers/cloudflare-r2/
- agent_band: agent-aware
  agent_readiness: 23.1
  band: developing
  in_catalog: true
  kin_score: 42.5
  mcp: *id009
  name: Finnhub
  slug: finnhub
  status: profiled
  tags: *id010
  url: /providers/finnhub/
- agent_band: agent-ready
  agent_readiness: 35.0
  band: strong
  in_catalog: true
  kin_score: 61.7
  mcp: *id011
  name: Google AI (Gemini)
  slug: google-gemini
  status: profiled
  tags: *id012
  url: /providers/google-gemini/
- agent_band: agent-aware
  agent_readiness: 21.2
  band: thin
  in_catalog: true
  kin_score: 32.3
  mcp: *id013
  name: Groq
  slug: groq
  status: profiled
  tags: *id014
  url: /providers/groq/
- agent_band: agent-ready
  agent_readiness: 32.2
  band: strong
  in_catalog: true
  kin_score: 59.3
  mcp: *id015
  name: Market Data (marketdata.app)
  slug: marketdata-app
  status: profiled
  tags: *id016
  url: /providers/marketdata-app/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 22.4
  mcp: *id017
  name: Metal Price API
  slug: metalpriceapi
  status: profiled
  tags: *id018
  url: /providers/metalpriceapi/
- agent_band: agent-aware
  agent_readiness: 24.4
  band: thin
  in_catalog: true
  kin_score: 37.7
  mcp: *id019
  name: Ollama
  slug: ollama
  status: profiled
  tags: *id020
  url: /providers/ollama/
- agent_band: agent-native
  agent_readiness: 57.5
  band: exemplar
  in_catalog: true
  kin_score: 82.5
  mcp: *id021
  name: OpenAI
  slug: openai
  status: profiled
  tags: *id022
  url: /providers/openai/
- agent_band: agent-aware
  agent_readiness: 25.9
  band: thin
  in_catalog: true
  kin_score: 32.2
  mcp: *id023
  name: OpenFIGI
  slug: openfigi
  status: profiled
  tags: *id024
  url: /providers/openfigi/
- agent_band: agent-ready
  agent_readiness: 46.4
  band: strong
  in_catalog: true
  kin_score: 54.8
  mcp: *id025
  name: OpenRouter
  slug: openrouter
  status: profiled
  tags: *id026
  url: /providers/openrouter/
- agent_band: agent-ready
  agent_readiness: 46.1
  band: strong
  in_catalog: true
  kin_score: 59.0
  mcp: *id027
  name: SnapTrade
  slug: snaptrade
  status: profiled
  tags: *id028
  url: /providers/snaptrade/
- agent_band: agent-aware
  agent_readiness: 19.6
  band: thin
  in_catalog: true
  kin_score: 29.1
  mcp: *id029
  name: US Treasury (treasury.gov / TreasuryDirect)
  slug: department-of-the-treasury
  status: profiled
  tags: *id030
  url: /providers/department-of-the-treasury/
- agent_band: agent-aware
  agent_readiness: 15.8
  band: developing
  in_catalog: true
  kin_score: 42.6
  mcp: *id031
  name: Yahoo Finance
  slug: yahoo
  status: profiled
  tags: *id032
  url: /providers/yahoo/
siblings:
- name: Freqtrade
  rows: 21
  url: /applications/investing-trading/freqtrade/
- name: Ghostfolio
  rows: 13
  url: /applications/investing-trading/ghostfolio/
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
sitemap: true
title: 'Wealthfolio: Investing & Trading reference app'
---
