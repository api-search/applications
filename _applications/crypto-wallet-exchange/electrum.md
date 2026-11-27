---
app: Electrum
app_slug: electrum
app_url: https://github.com/spesmilo/electrum
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-230.20.10
  key: AE-230.20.10
  layer: domain
  name: Exchange Rates
  providers:
  - Bit2C
  - Bitbank
  - BitcoinAverage
  - Bitfinex
  - bitFlyer
  - BitPay
  - Bitso
  - Bitstamp
  - Cointrader Monitor
  - Kraken
  - mempool.space
  - Yadio
  - Zaif
  url: /capabilities/market-financial-data/
  via_parent: Market & Financial Data
category:
  id: crypto-wallet-exchange
  name: Crypto Wallets & Exchanges
  url: /applications/crypto-wallet-exchange/
counts:
  declared: 0
  observed: 13
credits: []
evidence:
- route: source code
  url: https://github.com/spesmilo/electrum/blob/master/electrum/exchange_rate.py
integrations:
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
    agent_readiness: 3.9
    band: minimal
    in_catalog: true
    kin_score: 6.8
    mcp: &id001
      status: unchecked
    slug: bit2c
    status: profiled
    tags: &id002
    - OTC
    url: /providers/bit2c/
  layer: domain
  name: Bit2C
  provider: bit2c
  says: ships the Bit2C SDK or integration code
  source: https://github.com/spesmilo/electrum/blob/master/electrum/exchange_rate.py
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
    agent_band: agent-aware
    agent_readiness: 14.8
    band: emerging
    in_catalog: true
    kin_score: 25.4
    mcp: &id003
      source: https://github.com/bitbankinc/bitbank-mcp-server
      status: verified
    slug: bitbank
    status: profiled
    tags: &id004
    - Cryptocurrency
    - Exchange
    - Finance
    - Japan
    url: /providers/bitbank/
  layer: domain
  name: Bitbank
  provider: bitbank
  says: ships the Bitbank SDK or integration code
  source: https://github.com/spesmilo/electrum/blob/master/electrum/exchange_rate.py
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
    kin_score: 3.3
    mcp: &id005
      status: unknown
    slug: bitcoinaverage
    status: profiled
    tags: &id006
    - Cryptocurrency
    - Public APIs
    url: /providers/bitcoinaverage/
  layer: domain
  name: BitcoinAverage
  provider: bitcoinaverage
  says: ships the BitcoinAverage SDK or integration code
  source: https://github.com/spesmilo/electrum/blob/master/electrum/exchange_rate.py
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
    agent_band: agent-aware
    agent_readiness: 13.7
    band: emerging
    in_catalog: true
    kin_score: 17.3
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
  source: https://github.com/spesmilo/electrum/blob/master/electrum/exchange_rate.py
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
    agent_band: agent-aware
    agent_readiness: 21.7
    band: emerging
    in_catalog: true
    kin_score: 18.1
    mcp: &id009
      status: unknown
    slug: bitflyer
    status: profiled
    tags: &id010
    - Company
    - Cryptocurrency
    - Exchange
    - Trading
    url: /providers/bitflyer/
  layer: domain
  name: bitFlyer
  provider: bitflyer
  says: ships the bitFlyer SDK or integration code
  source: https://github.com/spesmilo/electrum/blob/master/electrum/exchange_rate.py
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
    agent_band: agent-ready
    agent_readiness: 35.9
    band: thin
    in_catalog: true
    kin_score: 33.9
    mcp: &id011
      status: none
    slug: bitpay
    status: profiled
    tags: &id012
    - Bitcoin
    - Blockchain
    - Cryptocurrency
    - Payments
    url: /providers/bitpay/
  layer: domain
  name: BitPay
  provider: bitpay
  says: ships the BitPay SDK or integration code
  source: https://github.com/spesmilo/electrum/blob/master/electrum/exchange_rate.py
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
    agent_band: agent-aware
    agent_readiness: 24.3
    band: thin
    in_catalog: true
    kin_score: 27.3
    mcp: &id013
      status: unknown
    slug: bitso
    status: profiled
    tags: &id014
    - Cryptocurrency
    - Exchange
    - Stablecoins
    - Trading
    url: /providers/bitso/
  layer: domain
  name: Bitso
  provider: bitso
  says: ships the Bitso SDK or integration code
  source: https://github.com/spesmilo/electrum/blob/master/electrum/exchange_rate.py
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
    agent_band: agent-ready
    agent_readiness: 29.4
    band: thin
    in_catalog: true
    kin_score: 33.5
    mcp: &id015
      status: none
    slug: bitstamp
    status: profiled
    tags: &id016
    - Bitcoin
    - Cryptocurrency
    - Exchange
    - Trading
    url: /providers/bitstamp/
  layer: domain
  name: Bitstamp
  provider: bitstamp
  says: ships the Bitstamp SDK or integration code
  source: https://github.com/spesmilo/electrum/blob/master/electrum/exchange_rate.py
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
    agent_band: agent-aware
    agent_readiness: 6.2
    band: minimal
    in_catalog: true
    kin_score: 8.3
    mcp: &id017
      status: unchecked
    slug: cointradermonitor
    status: profiled
    tags: &id018
    - Bitcoin
    - Brazil
    - Cryptocurrency
    - Market Data
    url: /providers/cointradermonitor/
  layer: domain
  name: Cointrader Monitor
  provider: cointradermonitor
  says: ships the Cointrader Monitor SDK or integration code
  source: https://github.com/spesmilo/electrum/blob/master/electrum/exchange_rate.py
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
    agent_band: agent-ready
    agent_readiness: 37.5
    band: strong
    in_catalog: true
    kin_score: 63.1
    mcp: &id019
      source: https://github.com/krakenfx/kraken-cli
      status: verified
    slug: kraken
    status: profiled
    tags: &id020
    - Cryptocurrency
    - Exchange
    - Kraken
    - Trading
    url: /providers/kraken/
  layer: domain
  name: Kraken
  provider: kraken
  says: ships the Kraken SDK or integration code
  source: https://github.com/spesmilo/electrum/blob/master/electrum/exchange_rate.py
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
    kin_score: 2.9
    mcp: &id021
      status: none
    slug: mempool
    status: profiled
    tags: &id022
    - Cryptocurrency
    - Public APIs
    url: /providers/mempool/
  layer: domain
  name: mempool.space
  provider: mempool
  says: ships the mempool.space SDK or integration code
  source: https://github.com/spesmilo/electrum/blob/master/electrum/exchange_rate.py
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
    agent_band: agent-aware
    agent_readiness: 25.7
    band: thin
    in_catalog: true
    kin_score: 30.6
    mcp: &id023
      status: unchecked
    slug: yadio
    status: profiled
    tags: &id024
    - Company
    url: /providers/yadio/
  layer: domain
  name: Yadio
  provider: yadio
  says: ships the Yadio SDK or integration code
  source: https://github.com/spesmilo/electrum/blob/master/electrum/exchange_rate.py
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
    band: emerging
    in_catalog: true
    kin_score: 15.9
    mcp: &id025
      status: unchecked
    slug: zaif
    status: profiled
    tags: &id026
    - Automatic Trading
    - Payment Card
    - Staking
    url: /providers/zaif/
  layer: domain
  name: Zaif
  provider: zaif
  says: ships the Zaif SDK or integration code
  source: https://github.com/spesmilo/electrum/blob/master/electrum/exchange_rate.py
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/crypto-wallet-exchange/electrum/
providers:
- agent_band: human-only
  agent_readiness: 3.9
  band: minimal
  in_catalog: true
  kin_score: 6.8
  mcp: *id001
  name: Bit2C
  slug: bit2c
  status: profiled
  tags: *id002
  url: /providers/bit2c/
- agent_band: agent-aware
  agent_readiness: 14.8
  band: emerging
  in_catalog: true
  kin_score: 25.4
  mcp: *id003
  name: Bitbank
  slug: bitbank
  status: profiled
  tags: *id004
  url: /providers/bitbank/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 3.3
  mcp: *id005
  name: BitcoinAverage
  slug: bitcoinaverage
  status: profiled
  tags: *id006
  url: /providers/bitcoinaverage/
- agent_band: agent-aware
  agent_readiness: 13.7
  band: emerging
  in_catalog: true
  kin_score: 17.3
  mcp: *id007
  name: Bitfinex
  slug: bitfinex
  status: profiled
  tags: *id008
  url: /providers/bitfinex/
- agent_band: agent-aware
  agent_readiness: 21.7
  band: emerging
  in_catalog: true
  kin_score: 18.1
  mcp: *id009
  name: bitFlyer
  slug: bitflyer
  status: profiled
  tags: *id010
  url: /providers/bitflyer/
- agent_band: agent-ready
  agent_readiness: 35.9
  band: thin
  in_catalog: true
  kin_score: 33.9
  mcp: *id011
  name: BitPay
  slug: bitpay
  status: profiled
  tags: *id012
  url: /providers/bitpay/
- agent_band: agent-aware
  agent_readiness: 24.3
  band: thin
  in_catalog: true
  kin_score: 27.3
  mcp: *id013
  name: Bitso
  slug: bitso
  status: profiled
  tags: *id014
  url: /providers/bitso/
- agent_band: agent-ready
  agent_readiness: 29.4
  band: thin
  in_catalog: true
  kin_score: 33.5
  mcp: *id015
  name: Bitstamp
  slug: bitstamp
  status: profiled
  tags: *id016
  url: /providers/bitstamp/
- agent_band: agent-aware
  agent_readiness: 6.2
  band: minimal
  in_catalog: true
  kin_score: 8.3
  mcp: *id017
  name: Cointrader Monitor
  slug: cointradermonitor
  status: profiled
  tags: *id018
  url: /providers/cointradermonitor/
- agent_band: agent-ready
  agent_readiness: 37.5
  band: strong
  in_catalog: true
  kin_score: 63.1
  mcp: *id019
  name: Kraken
  slug: kraken
  status: profiled
  tags: *id020
  url: /providers/kraken/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 2.9
  mcp: *id021
  name: mempool.space
  slug: mempool
  status: profiled
  tags: *id022
  url: /providers/mempool/
- agent_band: agent-aware
  agent_readiness: 25.7
  band: thin
  in_catalog: true
  kin_score: 30.6
  mcp: *id023
  name: Yadio
  slug: yadio
  status: profiled
  tags: *id024
  url: /providers/yadio/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 15.9
  mcp: *id025
  name: Zaif
  slug: zaif
  status: profiled
  tags: *id026
  url: /providers/zaif/
siblings:
- name: BTCPay Server
  rows: 25
  url: /applications/crypto-wallet-exchange/btcpay-server/
- name: Coinbase
  rows: 7
  url: /applications/crypto-wallet-exchange/coinbase/
- name: Kraken
  rows: 6
  url: /applications/crypto-wallet-exchange/kraken/
- name: Ledger Live
  rows: 16
  url: /applications/crypto-wallet-exchange/ledger-live/
- name: MetaMask
  rows: 9
  url: /applications/crypto-wallet-exchange/metamask/
- name: Sparrow Wallet
  rows: 10
  url: /applications/crypto-wallet-exchange/sparrow-wallet/
- name: Unstoppable Wallet
  rows: 14
  url: /applications/crypto-wallet-exchange/unstoppable-wallet/
sitemap: true
title: 'Electrum: Crypto Wallets & Exchanges reference app'
---
