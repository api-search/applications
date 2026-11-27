---
app: Sparrow Wallet
app_slug: sparrow-wallet
app_url: https://github.com/sparrowwallet/sparrow
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-240.30.10
  key: AE-240.30.10
  layer: domain
  name: Blockchain Indexing
  providers:
  - Blockstream
  - mempool.space
  url: /capabilities/on-chain-data-indexing/
  via_parent: On-Chain Data & Indexing
- attribution: API Evangelist extension
  id: AE-230.20.10
  key: AE-230.20.10
  layer: domain
  name: Exchange Rates
  providers:
  - Coinbase
  - CoinGecko
  - mempool.space
  url: /capabilities/market-financial-data/
  via_parent: Market & Financial Data
- attribution: API Evangelist extension
  id: AE-240.30.30
  key: AE-240.30.30
  layer: domain
  name: Fee Rate Estimation
  providers:
  - bitview.space
  - Block (block.xyz fee API)
  - Earn.com (bitcoinfees.earn.com)
  - mempool.space
  - OXT
  url: /capabilities/on-chain-data-indexing/
  via_parent: On-Chain Data & Indexing
category:
  id: crypto-wallet-exchange
  name: Crypto Wallets & Exchanges
  url: /applications/crypto-wallet-exchange/
counts:
  declared: 0
  observed: 10
credits: []
evidence:
- route: source code
  url: https://github.com/sparrowwallet/sparrow/blob/master/src/main/java/com/sparrowwallet/sparrow/net/BlockExplorer.java
- route: source code
  url: https://github.com/sparrowwallet/sparrow/blob/master/src/main/java/com/sparrowwallet/sparrow/net/ExchangeSource.java
- route: source code
  url: https://github.com/sparrowwallet/sparrow/blob/master/src/main/java/com/sparrowwallet/sparrow/net/FeeRatesSource.java
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-240.30.30
    key: AE-240.30.30
    name: Fee Rate Estimation
    url: /capabilities/on-chain-data-indexing/
    via_parent: On-Chain Data & Indexing
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 23.7
    band: thin
    in_catalog: true
    kin_score: 27.9
    mcp: &id002
      status: unchecked
    slug: bitview-space
    status: profiled
    tags: &id003
    - Company
    url: /providers/bitview-space/
  layer: domain
  name: bitview.space
  provider: bitview-space
  says: ships the bitview.space SDK or integration code
  source: https://github.com/sparrowwallet/sparrow/blob/master/src/main/java/com/sparrowwallet/sparrow/net/FeeRatesSource.java
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-240.30.30
    key: AE-240.30.30
    name: Fee Rate Estimation
    url: /capabilities/on-chain-data-indexing/
    via_parent: On-Chain Data & Indexing
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 45.4
    band: developing
    in_catalog: true
    kin_score: 54.1
    mcp: &id004
      source: https://github.com/square/square-mcp-server
      status: verified
    slug: block
    status: profiled
    tags: &id005
    - Commerce
    - Cryptocurrency
    - E-Commerce
    - Fintech
    url: /providers/block/
  layer: domain
  name: Block (block.xyz fee API)
  provider: block
  says: ships the Block (block.xyz fee API) SDK or integration code
  source: https://github.com/sparrowwallet/sparrow/blob/master/src/main/java/com/sparrowwallet/sparrow/net/FeeRatesSource.java
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-240.30.10
    key: AE-240.30.10
    name: Blockchain Indexing
    url: /capabilities/on-chain-data-indexing/
    via_parent: On-Chain Data & Indexing
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 18.4
    band: emerging
    in_catalog: true
    kin_score: 21.6
    mcp: &id006
      status: none
    slug: blockstream
    status: profiled
    tags: &id007
    - Bitcoin
    - Blockchain
    - Company
    - Cryptocurrency
    url: /providers/blockstream/
  layer: domain
  name: Blockstream
  provider: blockstream
  says: ships the Blockstream SDK or integration code
  source: https://github.com/sparrowwallet/sparrow/blob/master/src/main/java/com/sparrowwallet/sparrow/net/BlockExplorer.java
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
    agent_band: agent-native
    agent_readiness: 50.8
    band: strong
    in_catalog: true
    kin_score: 57.2
    mcp: &id008
      source: https://github.com/coinbase/payments-mcp
      status: verified
    slug: coinbase
    status: profiled
    tags: &id009
    - Blockchain
    - Cryptocurrency
    - Custody
    - Exchange
    url: /providers/coinbase/
  layer: domain
  name: Coinbase
  provider: coinbase
  says: ships the Coinbase SDK or integration code
  source: https://github.com/sparrowwallet/sparrow/blob/master/src/main/java/com/sparrowwallet/sparrow/net/ExchangeSource.java
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
    agent_readiness: 47.4
    band: developing
    in_catalog: true
    kin_score: 52.4
    mcp: &id010
      source: https://docs.coingecko.com/reference/mcp-server
      status: verified
    slug: coingecko
    status: profiled
    tags: &id011
    - Aggregator
    - Blockchain
    - CoinGecko
    - Cryptocurrency
    url: /providers/coingecko/
  layer: domain
  name: CoinGecko
  provider: coingecko
  says: ships the CoinGecko SDK or integration code
  source: https://github.com/sparrowwallet/sparrow/blob/master/src/main/java/com/sparrowwallet/sparrow/net/ExchangeSource.java
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-240.30.30
    key: AE-240.30.30
    name: Fee Rate Estimation
    url: /capabilities/on-chain-data-indexing/
    via_parent: On-Chain Data & Indexing
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 1.9
    mcp: &id012
      status: unknown
    slug: earn
    status: profiled
    tags: &id013
    - Bitcoin
    - Company
    - Cryptocurrency
    - Payments
    url: /providers/earn/
  layer: domain
  name: Earn.com (bitcoinfees.earn.com)
  provider: earn
  says: ships the Earn.com (bitcoinfees.earn.com) SDK or integration code
  source: https://github.com/sparrowwallet/sparrow/blob/master/src/main/java/com/sparrowwallet/sparrow/net/FeeRatesSource.java
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-230.20.10
    key: AE-230.20.10
    name: Exchange Rates
    url: /capabilities/market-financial-data/
    via_parent: Market & Financial Data
  credit: null
  facts: &id001
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 2.9
    mcp: &id014
      status: none
    slug: mempool
    status: profiled
    tags: &id015
    - Cryptocurrency
    - Public APIs
    url: /providers/mempool/
  layer: domain
  name: mempool.space
  provider: mempool
  says: ships the mempool.space SDK or integration code
  source: https://github.com/sparrowwallet/sparrow/blob/master/src/main/java/com/sparrowwallet/sparrow/net/ExchangeSource.java
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-240.30.10
    key: AE-240.30.10
    name: Blockchain Indexing
    url: /capabilities/on-chain-data-indexing/
    via_parent: On-Chain Data & Indexing
  credit: null
  facts: *id001
  layer: domain
  name: mempool.space
  provider: mempool
  says: ships the mempool.space SDK or integration code
  source: https://github.com/sparrowwallet/sparrow/blob/master/src/main/java/com/sparrowwallet/sparrow/net/BlockExplorer.java
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-240.30.30
    key: AE-240.30.30
    name: Fee Rate Estimation
    url: /capabilities/on-chain-data-indexing/
    via_parent: On-Chain Data & Indexing
  credit: null
  facts: *id001
  layer: domain
  name: mempool.space
  provider: mempool
  says: ships the mempool.space SDK or integration code
  source: https://github.com/sparrowwallet/sparrow/blob/master/src/main/java/com/sparrowwallet/sparrow/net/FeeRatesSource.java
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-240.30.30
    key: AE-240.30.30
    name: Fee Rate Estimation
    url: /capabilities/on-chain-data-indexing/
    via_parent: On-Chain Data & Indexing
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id016
      status: unchecked
    slug: oxt-me
    status: queued for profiling
    tags: &id017 []
    url: null
  layer: domain
  name: OXT
  provider: oxt-me
  says: ships the OXT SDK or integration code
  source: https://github.com/sparrowwallet/sparrow/blob/master/src/main/java/com/sparrowwallet/sparrow/net/FeeRatesSource.java
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/crypto-wallet-exchange/sparrow-wallet/
providers:
- agent_band: agent-aware
  agent_readiness: 23.7
  band: thin
  in_catalog: true
  kin_score: 27.9
  mcp: *id002
  name: bitview.space
  slug: bitview-space
  status: profiled
  tags: *id003
  url: /providers/bitview-space/
- agent_band: agent-ready
  agent_readiness: 45.4
  band: developing
  in_catalog: true
  kin_score: 54.1
  mcp: *id004
  name: Block (block.xyz fee API)
  slug: block
  status: profiled
  tags: *id005
  url: /providers/block/
- agent_band: agent-aware
  agent_readiness: 18.4
  band: emerging
  in_catalog: true
  kin_score: 21.6
  mcp: *id006
  name: Blockstream
  slug: blockstream
  status: profiled
  tags: *id007
  url: /providers/blockstream/
- agent_band: agent-native
  agent_readiness: 50.8
  band: strong
  in_catalog: true
  kin_score: 57.2
  mcp: *id008
  name: Coinbase
  slug: coinbase
  status: profiled
  tags: *id009
  url: /providers/coinbase/
- agent_band: agent-ready
  agent_readiness: 47.4
  band: developing
  in_catalog: true
  kin_score: 52.4
  mcp: *id010
  name: CoinGecko
  slug: coingecko
  status: profiled
  tags: *id011
  url: /providers/coingecko/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 1.9
  mcp: *id012
  name: Earn.com (bitcoinfees.earn.com)
  slug: earn
  status: profiled
  tags: *id013
  url: /providers/earn/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 2.9
  mcp: *id014
  name: mempool.space
  slug: mempool
  status: profiled
  tags: *id015
  url: /providers/mempool/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id016
  name: OXT
  slug: oxt-me
  status: queued for profiling
  tags: *id017
  url: null
siblings:
- name: BTCPay Server
  rows: 25
  url: /applications/crypto-wallet-exchange/btcpay-server/
- name: Coinbase
  rows: 7
  url: /applications/crypto-wallet-exchange/coinbase/
- name: Electrum
  rows: 13
  url: /applications/crypto-wallet-exchange/electrum/
- name: Kraken
  rows: 6
  url: /applications/crypto-wallet-exchange/kraken/
- name: Ledger Live
  rows: 16
  url: /applications/crypto-wallet-exchange/ledger-live/
- name: MetaMask
  rows: 9
  url: /applications/crypto-wallet-exchange/metamask/
- name: Unstoppable Wallet
  rows: 14
  url: /applications/crypto-wallet-exchange/unstoppable-wallet/
sitemap: true
title: 'Sparrow Wallet: Crypto Wallets & Exchanges reference app'
---
