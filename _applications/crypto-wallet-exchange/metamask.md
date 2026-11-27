---
app: MetaMask
app_slug: metamask
app_url: https://github.com/MetaMask/metamask-extension
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-240.40.10
  key: AE-240.40.10
  layer: domain
  name: RPC Endpoints
  providers:
  - Infura
  url: /capabilities/node-rpc-infrastructure/
  via_parent: Node & RPC Infrastructure
- attribution: API Evangelist extension
  id: AE-240.10.20
  key: AE-240.10.20
  layer: domain
  name: Self-Custody Wallets
  providers:
  - GridPlus
  - Keystone
  - Ledger
  - Trezor
  url: /capabilities/crypto-wallets/
  via_parent: Crypto Wallets
- attribution: API Evangelist extension
  id: AE-240.30.40
  key: AE-240.30.40
  layer: domain
  name: Transaction Security & Simulation
  providers:
  - Blockaid
  url: /capabilities/on-chain-data-indexing/
  via_parent: On-Chain Data & Indexing
- attribution: API Evangelist extension
  id: AE-902
  key: AE-902
  layer: common
  name: Mobile Attribution & Deep Linking
  providers:
  - Branch
  url: /capabilities/mobile-attribution-deep-linking/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Sentry
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Segment
  url: /capabilities/product-usage-analytics/
  via_parent: null
category:
  id: crypto-wallet-exchange
  name: Crypto Wallets & Exchanges
  url: /applications/crypto-wallet-exchange/
counts:
  declared: 0
  observed: 9
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/io.metamask/latest/
- route: dependency manifest
  url: https://github.com/MetaMask/metamask-extension/blob/main/package.json
- route: source code
  url: https://github.com/MetaMask/metamask-extension/blob/main/.metamaskrc.dist
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-240.30.40
    key: AE-240.30.40
    name: Transaction Security & Simulation
    url: /capabilities/on-chain-data-indexing/
    via_parent: On-Chain Data & Indexing
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 30.5
    band: thin
    in_catalog: true
    kin_score: 37.8
    mcp: &id001
      source: https://mcp.blockaid.io/mcp
      status: verified
    slug: blockaid
    status: profiled
    tags: &id002
    - Blockchain
    - Company
    - Fintech
    - Web3 Security
    url: /providers/blockaid/
  layer: domain
  name: Blockaid
  provider: blockaid
  says: ships the Blockaid SDK or integration code
  source: https://github.com/MetaMask/metamask-extension/blob/main/package.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-902
    key: AE-902
    name: Mobile Attribution & Deep Linking
    url: /capabilities/mobile-attribution-deep-linking/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-aware
    agent_readiness: 21.9
    band: thin
    in_catalog: true
    kin_score: 33.8
    mcp: &id003
      status: none
    slug: branch-io
    status: profiled
    tags: &id004
    - Company
    url: /providers/branch-io/
  layer: common
  name: Branch
  provider: branch-io
  says: ships the Branch SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/io.metamask/latest/
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-240.10.20
    key: AE-240.10.20
    name: Self-Custody Wallets
    url: /capabilities/crypto-wallets/
    via_parent: Crypto Wallets
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 10.3
    band: emerging
    in_catalog: true
    kin_score: 16.9
    mcp: &id005
      status: unchecked
    slug: gridplus
    status: profiled
    tags: &id006
    - Company
    - Crypto Security
    - Developer Tools
    - Hardware Wallet
    url: /providers/gridplus/
  layer: domain
  name: GridPlus
  provider: gridplus
  says: ships the GridPlus SDK or integration code
  source: https://github.com/MetaMask/metamask-extension/blob/main/package.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-240.40.10
    key: AE-240.40.10
    name: RPC Endpoints
    url: /capabilities/node-rpc-infrastructure/
    via_parent: Node & RPC Infrastructure
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 23.5
    band: thin
    in_catalog: true
    kin_score: 27.2
    mcp: &id007
      status: none
    slug: infura
    status: profiled
    tags: &id008
    - Blockchain
    - Infrastructure
    - RPC
    - Web3
    url: /providers/infura/
  layer: domain
  name: Infura
  provider: infura
  says: ships the Infura SDK or integration code
  source: https://github.com/MetaMask/metamask-extension/blob/main/.metamaskrc.dist
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-240.10.20
    key: AE-240.10.20
    name: Self-Custody Wallets
    url: /capabilities/crypto-wallets/
    via_parent: Crypto Wallets
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id009
      status: unchecked
    slug: keystone
    status: queued for profiling
    tags: &id010 []
    url: null
  layer: domain
  name: Keystone
  provider: keystone
  says: ships the Keystone SDK or integration code
  source: https://github.com/MetaMask/metamask-extension/blob/main/package.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-240.10.20
    key: AE-240.10.20
    name: Self-Custody Wallets
    url: /capabilities/crypto-wallets/
    via_parent: Crypto Wallets
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 40.3
    band: strong
    in_catalog: true
    kin_score: 63.1
    mcp: &id011
      status: none
    slug: ledger
    status: profiled
    tags: &id012
    - Cryptocurrency
    - Digital Assets
    - Hardware Wallet
    - Ledger
    url: /providers/ledger/
  layer: domain
  name: Ledger
  provider: ledger
  says: ships the Ledger SDK or integration code
  source: https://github.com/MetaMask/metamask-extension/blob/main/package.json
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 27.7
    band: developing
    in_catalog: true
    kin_score: 42.9
    mcp: &id013
      status: none
    slug: segment
    status: profiled
    tags: &id014
    - CDP
    - Company
    - Customer Data Platform
    - Identity Resolution
    url: /providers/segment/
  layer: common
  name: Segment
  provider: segment
  says: ships the Segment SDK or integration code
  source: https://github.com/MetaMask/metamask-extension/blob/main/package.json
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 50.2
    band: exemplar
    in_catalog: true
    kin_score: 80.7
    mcp: &id015
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id016
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: common
  name: Sentry
  provider: sentry-system
  says: ships the Sentry SDK or integration code
  source: https://github.com/MetaMask/metamask-extension/blob/main/package.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-240.10.20
    key: AE-240.10.20
    name: Self-Custody Wallets
    url: /capabilities/crypto-wallets/
    via_parent: Crypto Wallets
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 6.2
    band: emerging
    in_catalog: true
    kin_score: 14.7
    mcp: &id017
      status: unchecked
    slug: trezor
    status: profiled
    tags: &id018
    - Company
    - Cryptocurrency
    - Hardware Wallet
    - Security
    url: /providers/trezor/
  layer: domain
  name: Trezor
  provider: trezor
  says: ships the Trezor SDK or integration code
  source: https://github.com/MetaMask/metamask-extension/blob/main/package.json
  tier: observed
kind: open-source-saas
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/crypto-wallet-exchange/metamask/
providers:
- agent_band: agent-ready
  agent_readiness: 30.5
  band: thin
  in_catalog: true
  kin_score: 37.8
  mcp: *id001
  name: Blockaid
  slug: blockaid
  status: profiled
  tags: *id002
  url: /providers/blockaid/
- agent_band: agent-aware
  agent_readiness: 21.9
  band: thin
  in_catalog: true
  kin_score: 33.8
  mcp: *id003
  name: Branch
  slug: branch-io
  status: profiled
  tags: *id004
  url: /providers/branch-io/
- agent_band: agent-aware
  agent_readiness: 10.3
  band: emerging
  in_catalog: true
  kin_score: 16.9
  mcp: *id005
  name: GridPlus
  slug: gridplus
  status: profiled
  tags: *id006
  url: /providers/gridplus/
- agent_band: agent-aware
  agent_readiness: 23.5
  band: thin
  in_catalog: true
  kin_score: 27.2
  mcp: *id007
  name: Infura
  slug: infura
  status: profiled
  tags: *id008
  url: /providers/infura/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id009
  name: Keystone
  slug: keystone
  status: queued for profiling
  tags: *id010
  url: null
- agent_band: agent-native
  agent_readiness: 40.3
  band: strong
  in_catalog: true
  kin_score: 63.1
  mcp: *id011
  name: Ledger
  slug: ledger
  status: profiled
  tags: *id012
  url: /providers/ledger/
- agent_band: agent-aware
  agent_readiness: 27.7
  band: developing
  in_catalog: true
  kin_score: 42.9
  mcp: *id013
  name: Segment
  slug: segment
  status: profiled
  tags: *id014
  url: /providers/segment/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.7
  mcp: *id015
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id016
  url: /providers/sentry-system/
- agent_band: agent-aware
  agent_readiness: 6.2
  band: emerging
  in_catalog: true
  kin_score: 14.7
  mcp: *id017
  name: Trezor
  slug: trezor
  status: profiled
  tags: *id018
  url: /providers/trezor/
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
- name: Sparrow Wallet
  rows: 10
  url: /applications/crypto-wallet-exchange/sparrow-wallet/
- name: Unstoppable Wallet
  rows: 14
  url: /applications/crypto-wallet-exchange/unstoppable-wallet/
sitemap: true
title: 'MetaMask: Crypto Wallets & Exchanges reference app'
---
