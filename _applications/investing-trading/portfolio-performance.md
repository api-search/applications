---
app: Portfolio Performance
app_slug: portfolio-performance
app_url: https://github.com/portfolio-performance/portfolio
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-190.30.20
  key: AE-190.30.20
  layer: domain
  name: Crypto Exchanges & Wallets
  providers:
  - Binance
  - Bitfinex
  - Kraken
  - MEXC
  url: /capabilities/retail-investing/
  via_parent: Retail Investing
- attribution: API Evangelist extension
  id: AE-230.20.10
  key: AE-230.20.10
  layer: domain
  name: Exchange Rates
  providers:
  - ECB Data Portal
  url: /capabilities/market-financial-data/
  via_parent: Market & Financial Data
- attribution: API Evangelist extension
  id: AE-230.20
  key: AE-230.20
  layer: domain
  name: Market & Financial Data
  providers:
  - Eurostat (HICP)
  url: /capabilities/market-financial-data/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-230.20.20
  key: AE-230.20.20
  layer: domain
  name: Securities Market Data
  providers:
  - Alpha Vantage
  - AMFI India
  - CoinGecko
  - DivvyDiary
  - EODHD
  - Finnhub
  - Leeway
  - Nasdaq Data Link (Quandl)
  - Twelve Data
  - Yahoo Finance
  url: /capabilities/market-financial-data/
  via_parent: Market & Financial Data
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
  url: https://github.com/portfolio-performance/portfolio/tree/master/name.abuchen.portfolio/src/name/abuchen/portfolio/online/impl
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
    agent_readiness: 51.4
    band: strong
    in_catalog: true
    kin_score: 54.4
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
  source: https://github.com/portfolio-performance/portfolio/tree/master/name.abuchen.portfolio/src/name/abuchen/portfolio/online/impl
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
    kin_score: 6.7
    mcp: &id003
      status: unknown
    slug: amfi-india
    status: profiled
    tags: &id004
    - Company
    - Finance
    - India
    - Mutual Funds
    url: /providers/amfi-india/
  layer: domain
  name: AMFI India
  provider: amfi-india
  says: ships the AMFI India SDK or integration code
  source: https://github.com/portfolio-performance/portfolio/tree/master/name.abuchen.portfolio/src/name/abuchen/portfolio/online/impl
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-190.30.20
    key: AE-190.30.20
    name: Crypto Exchanges & Wallets
    url: /capabilities/retail-investing/
    via_parent: Retail Investing
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 30.5
    band: thin
    in_catalog: true
    kin_score: 39.1
    mcp: &id005
      status: none
    slug: binance
    status: profiled
    tags: &id006
    - Blockchain
    - Cryptocurrency
    - Exchange
    - Trading
    url: /providers/binance/
  layer: domain
  name: Binance
  provider: binance
  says: ships the Binance SDK or integration code
  source: https://github.com/portfolio-performance/portfolio/tree/master/name.abuchen.portfolio/src/name/abuchen/portfolio/online/impl
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-190.30.20
    key: AE-190.30.20
    name: Crypto Exchanges & Wallets
    url: /capabilities/retail-investing/
    via_parent: Retail Investing
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 14.0
    band: emerging
    in_catalog: true
    kin_score: 17.4
    mcp: &id007
      status: none
    slug: bitfinex
    status: profiled
    tags: &id008
    - Cryptocurrency
    - Public APIs
    - Real-Time
    url: /providers/bitfinex/
  layer: domain
  name: Bitfinex
  provider: bitfinex
  says: ships the Bitfinex SDK or integration code
  source: https://github.com/portfolio-performance/portfolio/tree/master/name.abuchen.portfolio/src/name/abuchen/portfolio/online/impl
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
    agent_readiness: 46.2
    band: developing
    in_catalog: true
    kin_score: 52.0
    mcp: &id009
      source: https://docs.coingecko.com/reference/mcp-server
      status: verified
    slug: coingecko
    status: profiled
    tags: &id010
    - Aggregator
    - Blockchain
    - CoinGecko
    - Cryptocurrency
    url: /providers/coingecko/
  layer: domain
  name: CoinGecko
  provider: coingecko
  says: ships the CoinGecko SDK or integration code
  source: https://github.com/portfolio-performance/portfolio/tree/master/name.abuchen.portfolio/src/name/abuchen/portfolio/online/impl
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
    band: emerging
    in_catalog: true
    kin_score: 15.8
    mcp: &id011
      status: none
    slug: divvydiary
    status: profiled
    tags: &id012
    - Company
    - Dividend
    - Finance
    - Investment
    url: /providers/divvydiary/
  layer: domain
  name: DivvyDiary
  provider: divvydiary
  says: ships the DivvyDiary SDK or integration code
  source: https://github.com/portfolio-performance/portfolio/tree/master/name.abuchen.portfolio/src/name/abuchen/portfolio/online/impl
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-230.20.10
    key: AE-230.20.10
    name: Exchange Rates
    url: /capabilities/market-financial-data/
    via_parent: Market & Financial Data
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 7.8
    mcp: &id013
      status: none
    slug: european-central-bank
    status: profiled
    tags: &id014
    - Banking
    - Economic Data
    - European Union
    - Finance
    url: /providers/european-central-bank/
  layer: domain
  name: ECB Data Portal
  provider: european-central-bank
  says: ships the ECB Data Portal SDK or integration code
  source: https://github.com/portfolio-performance/portfolio/tree/master/name.abuchen.portfolio/src/name/abuchen/portfolio/online/impl
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
    agent_readiness: 58.3
    band: strong
    in_catalog: true
    kin_score: 62.2
    mcp: &id015
      source: https://github.com/EodHistoricalData/EODHD-MCP-Server
      status: verified
    slug: eodhd
    status: profiled
    tags: &id016
    - Finance
    - Market Data
    - Stock Options
    - Stocks
    url: /providers/eodhd/
  layer: domain
  name: EODHD
  provider: eodhd
  says: ships the EODHD SDK or integration code
  source: https://github.com/portfolio-performance/portfolio/tree/master/name.abuchen.portfolio/src/name/abuchen/portfolio/online/impl
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
    agent_readiness: 20.2
    band: thin
    in_catalog: true
    kin_score: 30.4
    mcp: &id017
      status: none
    slug: eurostat
    status: profiled
    tags: &id018
    - Demographics
    - European Union
    - Open Data
    - Statistics
    url: /providers/eurostat/
  layer: domain
  name: Eurostat (HICP)
  provider: eurostat
  says: ships the Eurostat (HICP) SDK or integration code
  source: https://github.com/portfolio-performance/portfolio/tree/master/name.abuchen.portfolio/src/name/abuchen/portfolio/online/impl
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
    agent_readiness: 23.6
    band: developing
    in_catalog: true
    kin_score: 43.9
    mcp: &id019
      source: https://finnhub.io/docs/api
      status: documented
    slug: finnhub
    status: profiled
    tags: &id020
    - Finance
    - Foreign Exchange
    - Market Data
    - Stocks
    url: /providers/finnhub/
  layer: domain
  name: Finnhub
  provider: finnhub
  says: ships the Finnhub SDK or integration code
  source: https://github.com/portfolio-performance/portfolio/tree/master/name.abuchen.portfolio/src/name/abuchen/portfolio/online/impl
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-190.30.20
    key: AE-190.30.20
    name: Crypto Exchanges & Wallets
    url: /capabilities/retail-investing/
    via_parent: Retail Investing
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 37.9
    band: strong
    in_catalog: true
    kin_score: 64.3
    mcp: &id021
      source: https://github.com/krakenfx/kraken-cli
      status: verified
    slug: kraken
    status: profiled
    tags: &id022
    - Cryptocurrency
    - Exchange
    - Kraken
    - Trading
    url: /providers/kraken/
  layer: domain
  name: Kraken
  provider: kraken
  says: ships the Kraken SDK or integration code
  source: https://github.com/portfolio-performance/portfolio/tree/master/name.abuchen.portfolio/src/name/abuchen/portfolio/online/impl
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
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id023
      status: unchecked
    slug: leeway
    status: queued for profiling
    tags: &id024 []
    url: null
  layer: domain
  name: Leeway
  provider: leeway
  says: ships the Leeway SDK or integration code
  source: https://github.com/portfolio-performance/portfolio/tree/master/name.abuchen.portfolio/src/name/abuchen/portfolio/online/impl
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-190.30.20
    key: AE-190.30.20
    name: Crypto Exchanges & Wallets
    url: /capabilities/retail-investing/
    via_parent: Retail Investing
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 21.3
    band: thin
    in_catalog: true
    kin_score: 33.0
    mcp: &id025
      status: none
    slug: mexc
    status: profiled
    tags: &id026
    - Cryptocurrency
    - Exchange
    - Futures
    - Trading
    url: /providers/mexc/
  layer: domain
  name: MEXC
  provider: mexc
  says: ships the MEXC SDK or integration code
  source: https://github.com/portfolio-performance/portfolio/tree/master/name.abuchen.portfolio/src/name/abuchen/portfolio/online/impl
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
    agent_readiness: 27.6
    band: thin
    in_catalog: true
    kin_score: 34.4
    mcp: &id027
      status: none
    slug: nasdaq-data-link
    status: profiled
    tags: &id028
    - Economic Data
    - Financial Data
    - Market Data
    - Stock Market
    url: /providers/nasdaq-data-link/
  layer: domain
  name: Nasdaq Data Link (Quandl)
  provider: nasdaq-data-link
  says: ships the Nasdaq Data Link (Quandl) SDK or integration code
  source: https://github.com/portfolio-performance/portfolio/tree/master/name.abuchen.portfolio/src/name/abuchen/portfolio/online/impl
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
    agent_readiness: 58.9
    band: exemplar
    in_catalog: true
    kin_score: 68.2
    mcp: &id029
      source: https://github.com/twelvedata/mcp
      status: verified
    slug: twelvedata
    status: profiled
    tags: &id030
    - Financial Data
    - Foreign Exchange
    - Market Data
    - Stocks
    url: /providers/twelvedata/
  layer: domain
  name: Twelve Data
  provider: twelvedata
  says: ships the Twelve Data SDK or integration code
  source: https://github.com/portfolio-performance/portfolio/tree/master/name.abuchen.portfolio/src/name/abuchen/portfolio/online/impl
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
    agent_readiness: 16.2
    band: developing
    in_catalog: true
    kin_score: 41.4
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
  source: https://github.com/portfolio-performance/portfolio/tree/master/name.abuchen.portfolio/src/name/abuchen/portfolio/online/impl
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/investing-trading/portfolio-performance/
providers:
- agent_band: agent-ready
  agent_readiness: 51.4
  band: strong
  in_catalog: true
  kin_score: 54.4
  mcp: *id001
  name: Alpha Vantage
  slug: alpha-vantage
  status: profiled
  tags: *id002
  url: /providers/alpha-vantage/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 6.7
  mcp: *id003
  name: AMFI India
  slug: amfi-india
  status: profiled
  tags: *id004
  url: /providers/amfi-india/
- agent_band: agent-ready
  agent_readiness: 30.5
  band: thin
  in_catalog: true
  kin_score: 39.1
  mcp: *id005
  name: Binance
  slug: binance
  status: profiled
  tags: *id006
  url: /providers/binance/
- agent_band: agent-aware
  agent_readiness: 14.0
  band: emerging
  in_catalog: true
  kin_score: 17.4
  mcp: *id007
  name: Bitfinex
  slug: bitfinex
  status: profiled
  tags: *id008
  url: /providers/bitfinex/
- agent_band: agent-ready
  agent_readiness: 46.2
  band: developing
  in_catalog: true
  kin_score: 52.0
  mcp: *id009
  name: CoinGecko
  slug: coingecko
  status: profiled
  tags: *id010
  url: /providers/coingecko/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 15.8
  mcp: *id011
  name: DivvyDiary
  slug: divvydiary
  status: profiled
  tags: *id012
  url: /providers/divvydiary/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 7.8
  mcp: *id013
  name: ECB Data Portal
  slug: european-central-bank
  status: profiled
  tags: *id014
  url: /providers/european-central-bank/
- agent_band: agent-ready
  agent_readiness: 58.3
  band: strong
  in_catalog: true
  kin_score: 62.2
  mcp: *id015
  name: EODHD
  slug: eodhd
  status: profiled
  tags: *id016
  url: /providers/eodhd/
- agent_band: agent-aware
  agent_readiness: 20.2
  band: thin
  in_catalog: true
  kin_score: 30.4
  mcp: *id017
  name: Eurostat (HICP)
  slug: eurostat
  status: profiled
  tags: *id018
  url: /providers/eurostat/
- agent_band: agent-aware
  agent_readiness: 23.6
  band: developing
  in_catalog: true
  kin_score: 43.9
  mcp: *id019
  name: Finnhub
  slug: finnhub
  status: profiled
  tags: *id020
  url: /providers/finnhub/
- agent_band: agent-ready
  agent_readiness: 37.9
  band: strong
  in_catalog: true
  kin_score: 64.3
  mcp: *id021
  name: Kraken
  slug: kraken
  status: profiled
  tags: *id022
  url: /providers/kraken/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id023
  name: Leeway
  slug: leeway
  status: queued for profiling
  tags: *id024
  url: null
- agent_band: agent-aware
  agent_readiness: 21.3
  band: thin
  in_catalog: true
  kin_score: 33.0
  mcp: *id025
  name: MEXC
  slug: mexc
  status: profiled
  tags: *id026
  url: /providers/mexc/
- agent_band: agent-aware
  agent_readiness: 27.6
  band: thin
  in_catalog: true
  kin_score: 34.4
  mcp: *id027
  name: Nasdaq Data Link (Quandl)
  slug: nasdaq-data-link
  status: profiled
  tags: *id028
  url: /providers/nasdaq-data-link/
- agent_band: agent-ready
  agent_readiness: 58.9
  band: exemplar
  in_catalog: true
  kin_score: 68.2
  mcp: *id029
  name: Twelve Data
  slug: twelvedata
  status: profiled
  tags: *id030
  url: /providers/twelvedata/
- agent_band: agent-aware
  agent_readiness: 16.2
  band: developing
  in_catalog: true
  kin_score: 41.4
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
title: 'Portfolio Performance: Investing & Trading reference app'
---
