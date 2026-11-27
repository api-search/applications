---
app: Unstoppable Wallet
app_slug: unstoppable-wallet
app_url: https://github.com/horizontalsystems/unstoppable-wallet-android
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-240.30.10
  key: AE-240.30.10
  layer: domain
  name: Blockchain Indexing
  providers:
  - Blockscout
  - BscScan
  - Etherscan
  url: /capabilities/on-chain-data-indexing/
  via_parent: On-Chain Data & Indexing
- attribution: API Evangelist extension
  id: AE-240.10
  key: AE-240.10
  layer: domain
  name: Crypto Wallets
  providers:
  - Reown (WalletConnect)
  url: /capabilities/crypto-wallets/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-240.60.10
  key: AE-240.60.10
  layer: domain
  name: Decentralized Exchanges
  providers:
  - Jupiter
  - THORChain
  url: /capabilities/defi-protocols/
  via_parent: DeFi Protocols
- attribution: API Evangelist extension
  id: AE-240.40.10
  key: AE-240.40.10
  layer: domain
  name: RPC Endpoints
  providers:
  - Alchemy
  - FastNEAR
  - TonAPI
  - TronGrid
  url: /capabilities/node-rpc-infrastructure/
  via_parent: Node & RPC Infrastructure
- attribution: API Evangelist extension
  id: AE-170.50
  key: AE-170.50
  layer: domain
  name: Social Networks & Community
  providers:
  - X
  url: /capabilities/social-networks-community/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-240.30.40
  key: AE-240.30.40
  layer: domain
  name: Transaction Security & Simulation
  providers:
  - Chainalysis
  - HashDit
  url: /capabilities/on-chain-data-indexing/
  via_parent: On-Chain Data & Indexing
- attribution: API Evangelist extension
  id: AE-240.100
  key: AE-240.100
  layer: domain
  name: Web3 Naming Services
  providers:
  - Unstoppable Domains
  url: /capabilities/web3-naming-services/
  via_parent: null
category:
  id: crypto-wallet-exchange
  name: Crypto Wallets & Exchanges
  url: /applications/crypto-wallet-exchange/
counts:
  declared: 0
  observed: 14
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/io.horizontalsystems.bankwallet/latest/
- route: source code
  url: https://github.com/horizontalsystems/unstoppable-wallet-android/blob/develop/app/build.gradle.kts
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-240.40.10
    key: AE-240.40.10
    name: RPC Endpoints
    url: /capabilities/node-rpc-infrastructure/
    via_parent: Node & RPC Infrastructure
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 37.9
    band: thin
    in_catalog: true
    kin_score: 31.9
    mcp: &id001
      source: https://github.com/alchemyplatform/alchemy-mcp-server
      status: verified
    slug: alchemy
    status: profiled
    tags: &id002
    - Blockchain
    - NFT
    - RPC
    - Web3
    url: /providers/alchemy/
  layer: domain
  name: Alchemy
  provider: alchemy
  says: ships the Alchemy SDK or integration code
  source: https://github.com/horizontalsystems/unstoppable-wallet-android/blob/develop/app/build.gradle.kts
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
    agent_band: agent-ready
    agent_readiness: 33.4
    band: thin
    in_catalog: true
    kin_score: 26.2
    mcp: &id003
      source: https://github.com/blockscout/mcp-server
      status: verified
    slug: blockscout
    status: profiled
    tags: &id004
    - Blockscout
    - Explorer
    - Open Source
    - Web3
    url: /providers/blockscout/
  layer: domain
  name: Blockscout
  provider: blockscout
  says: ships the Blockscout SDK or integration code
  source: https://github.com/horizontalsystems/unstoppable-wallet-android/blob/develop/app/build.gradle.kts
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
    agent_readiness: 25.9
    band: thin
    in_catalog: true
    kin_score: 35.3
    mcp: &id005
      status: unknown
    slug: bscscan
    status: profiled
    tags: &id006
    - BNB Smart Chain
    - BSC
    - Block Explorer
    - Blockchain
    url: /providers/bscscan/
  layer: domain
  name: BscScan
  provider: bscscan
  says: ships the BscScan SDK or integration code
  source: https://github.com/horizontalsystems/unstoppable-wallet-android/blob/develop/app/build.gradle.kts
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-240.30.40
    key: AE-240.30.40
    name: Transaction Security & Simulation
    url: /capabilities/on-chain-data-indexing/
    via_parent: On-Chain Data & Indexing
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 8.4
    band: developing
    in_catalog: true
    kin_score: 42.3
    mcp: &id007
      status: none
    slug: chainalysis
    status: profiled
    tags: &id008
    - AML
    - Compliance
    - Sanctions
    - Transaction Monitoring
    url: /providers/chainalysis/
  layer: domain
  name: Chainalysis
  provider: chainalysis
  says: ships the Chainalysis SDK or integration code
  source: https://github.com/horizontalsystems/unstoppable-wallet-android/blob/develop/app/build.gradle.kts
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
    agent_band: agent-ready
    agent_readiness: 30.0
    band: thin
    in_catalog: true
    kin_score: 36.5
    mcp: &id009
      source: https://docs.etherscan.io/mcp
      status: verified
    slug: etherscan
    status: profiled
    tags: &id010
    - Blockchain
    - Cryptocurrency
    - EVM
    - Ethereum
    url: /providers/etherscan/
  layer: domain
  name: Etherscan
  provider: etherscan
  says: ships the Etherscan SDK or integration code
  source: https://github.com/horizontalsystems/unstoppable-wallet-android/blob/develop/app/build.gradle.kts
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
    agent_readiness: 22.9
    band: thin
    in_catalog: true
    kin_score: 38.1
    mcp: &id011
      status: unchecked
    slug: fastnear
    status: profiled
    tags: &id012
    - Blockchain
    - FastNEAR
    - Infrastructure
    - NEAR
    url: /providers/fastnear/
  layer: domain
  name: FastNEAR
  provider: fastnear
  says: ships the FastNEAR SDK or integration code
  source: https://github.com/horizontalsystems/unstoppable-wallet-android/blob/develop/app/build.gradle.kts
  tier: observed
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
    agent_readiness: 35.3
    band: thin
    in_catalog: true
    kin_score: 37.4
    mcp: &id013
      status: unchecked
    slug: hashdit
    status: profiled
    tags: &id014
    - Crypto Security
    - Scam Protection
    - Token Scanner
    - Web3 Tools
    url: /providers/hashdit/
  layer: domain
  name: HashDit
  provider: hashdit
  says: ships the HashDit SDK or integration code
  source: https://github.com/horizontalsystems/unstoppable-wallet-android/blob/develop/app/build.gradle.kts
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-240.60.10
    key: AE-240.60.10
    name: Decentralized Exchanges
    url: /capabilities/defi-protocols/
    via_parent: DeFi Protocols
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.4
    band: thin
    in_catalog: true
    kin_score: 27.1
    mcp: &id015
      source: https://developers.jup.ag/docs/ai/trading-mcp
      status: documented
    slug: jupiter-ag
    status: profiled
    tags: &id016
    - DEX Aggregator
    - DeFi
    - Solana
    - Swap
    url: /providers/jupiter-ag/
  layer: domain
  name: Jupiter
  provider: jupiter-ag
  says: ships the Jupiter SDK or integration code
  source: https://github.com/horizontalsystems/unstoppable-wallet-android/blob/develop/app/build.gradle.kts
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-240.10
    key: AE-240.10
    name: Crypto Wallets
    url: /capabilities/crypto-wallets/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 23.3
    band: thin
    in_catalog: true
    kin_score: 30.6
    mcp: &id017
      status: none
    slug: reown
    status: profiled
    tags: &id018
    - AppKit
    - WalletConnect
    - Wallets
    - Web3
    url: /providers/reown/
  layer: domain
  name: Reown (WalletConnect)
  provider: reown
  says: ships the Reown (WalletConnect) SDK or integration code
  source: https://github.com/horizontalsystems/unstoppable-wallet-android/blob/develop/app/build.gradle.kts
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-240.60.10
    key: AE-240.60.10
    name: Decentralized Exchanges
    url: /capabilities/defi-protocols/
    via_parent: DeFi Protocols
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 36.4
    band: thin
    in_catalog: true
    kin_score: 35.1
    mcp: &id019
      source: https://mcp.thorchain.org/mcp
      status: verified
    slug: thorchain
    status: profiled
    tags: &id020
    - Blockchain
    - Company
    - DeFi
    - Web3
    url: /providers/thorchain/
  layer: domain
  name: THORChain
  provider: thorchain
  says: ships the THORChain SDK or integration code
  source: https://github.com/horizontalsystems/unstoppable-wallet-android/blob/develop/app/build.gradle.kts
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
    agent_readiness: 21.0
    band: thin
    in_catalog: true
    kin_score: 28.1
    mcp: &id021
      status: unchecked
    slug: tonapi
    status: profiled
    tags: &id022
    - Blockchain
    - Company
    - Developer Tools
    - Software-as-a-Service
    url: /providers/tonapi/
  layer: domain
  name: TonAPI
  provider: tonapi
  says: ships the TonAPI SDK or integration code
  source: https://github.com/horizontalsystems/unstoppable-wallet-android/blob/develop/app/build.gradle.kts
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
    agent_readiness: 25.7
    band: thin
    in_catalog: true
    kin_score: 34.1
    mcp: &id023
      status: unchecked
    slug: trongrid
    status: profiled
    tags: &id024
    - Blockchain
    - Decentralized Applications
    - Developer Tools
    - TRON
    url: /providers/trongrid/
  layer: domain
  name: TronGrid
  provider: trongrid
  says: ships the TronGrid SDK or integration code
  source: https://github.com/horizontalsystems/unstoppable-wallet-android/blob/develop/app/build.gradle.kts
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-240.100
    key: AE-240.100
    name: Web3 Naming Services
    url: /capabilities/web3-naming-services/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 35.9
    band: thin
    in_catalog: true
    kin_score: 35.9
    mcp: &id025
      source: https://github.com/unstoppabledomains/unstoppable-mcp-server
      status: verified
    slug: unstoppable-domains
    status: profiled
    tags: &id026
    - Blockchain
    - Domain Names
    - NFT Domains
    - Web3
    url: /providers/unstoppable-domains/
  layer: domain
  name: Unstoppable Domains
  provider: unstoppable-domains
  says: ships the Unstoppable Domains SDK or integration code
  source: https://github.com/horizontalsystems/unstoppable-wallet-android/blob/develop/app/build.gradle.kts
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
    mcp: &id027
      source: https://github.com/xdevplatform/xmcp
      status: verified
    slug: x
    status: profiled
    tags: &id028
    - Conversations
    - Social
    - Spaces
    - X
    url: /providers/x/
  layer: domain
  name: X
  provider: x
  says: ships the X SDK or integration code
  source: https://github.com/horizontalsystems/unstoppable-wallet-android/blob/develop/app/build.gradle.kts
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/crypto-wallet-exchange/unstoppable-wallet/
providers:
- agent_band: agent-ready
  agent_readiness: 37.9
  band: thin
  in_catalog: true
  kin_score: 31.9
  mcp: *id001
  name: Alchemy
  slug: alchemy
  status: profiled
  tags: *id002
  url: /providers/alchemy/
- agent_band: agent-ready
  agent_readiness: 33.4
  band: thin
  in_catalog: true
  kin_score: 26.2
  mcp: *id003
  name: Blockscout
  slug: blockscout
  status: profiled
  tags: *id004
  url: /providers/blockscout/
- agent_band: agent-aware
  agent_readiness: 25.9
  band: thin
  in_catalog: true
  kin_score: 35.3
  mcp: *id005
  name: BscScan
  slug: bscscan
  status: profiled
  tags: *id006
  url: /providers/bscscan/
- agent_band: agent-aware
  agent_readiness: 8.4
  band: developing
  in_catalog: true
  kin_score: 42.3
  mcp: *id007
  name: Chainalysis
  slug: chainalysis
  status: profiled
  tags: *id008
  url: /providers/chainalysis/
- agent_band: agent-ready
  agent_readiness: 30.0
  band: thin
  in_catalog: true
  kin_score: 36.5
  mcp: *id009
  name: Etherscan
  slug: etherscan
  status: profiled
  tags: *id010
  url: /providers/etherscan/
- agent_band: agent-aware
  agent_readiness: 22.9
  band: thin
  in_catalog: true
  kin_score: 38.1
  mcp: *id011
  name: FastNEAR
  slug: fastnear
  status: profiled
  tags: *id012
  url: /providers/fastnear/
- agent_band: agent-ready
  agent_readiness: 35.3
  band: thin
  in_catalog: true
  kin_score: 37.4
  mcp: *id013
  name: HashDit
  slug: hashdit
  status: profiled
  tags: *id014
  url: /providers/hashdit/
- agent_band: agent-aware
  agent_readiness: 24.4
  band: thin
  in_catalog: true
  kin_score: 27.1
  mcp: *id015
  name: Jupiter
  slug: jupiter-ag
  status: profiled
  tags: *id016
  url: /providers/jupiter-ag/
- agent_band: agent-aware
  agent_readiness: 23.3
  band: thin
  in_catalog: true
  kin_score: 30.6
  mcp: *id017
  name: Reown (WalletConnect)
  slug: reown
  status: profiled
  tags: *id018
  url: /providers/reown/
- agent_band: agent-ready
  agent_readiness: 36.4
  band: thin
  in_catalog: true
  kin_score: 35.1
  mcp: *id019
  name: THORChain
  slug: thorchain
  status: profiled
  tags: *id020
  url: /providers/thorchain/
- agent_band: agent-aware
  agent_readiness: 21.0
  band: thin
  in_catalog: true
  kin_score: 28.1
  mcp: *id021
  name: TonAPI
  slug: tonapi
  status: profiled
  tags: *id022
  url: /providers/tonapi/
- agent_band: agent-aware
  agent_readiness: 25.7
  band: thin
  in_catalog: true
  kin_score: 34.1
  mcp: *id023
  name: TronGrid
  slug: trongrid
  status: profiled
  tags: *id024
  url: /providers/trongrid/
- agent_band: agent-ready
  agent_readiness: 35.9
  band: thin
  in_catalog: true
  kin_score: 35.9
  mcp: *id025
  name: Unstoppable Domains
  slug: unstoppable-domains
  status: profiled
  tags: *id026
  url: /providers/unstoppable-domains/
- agent_band: agent-native
  agent_readiness: 59.9
  band: exemplar
  in_catalog: true
  kin_score: 75.0
  mcp: *id027
  name: X
  slug: x
  status: profiled
  tags: *id028
  url: /providers/x/
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
- name: Sparrow Wallet
  rows: 10
  url: /applications/crypto-wallet-exchange/sparrow-wallet/
sitemap: true
title: 'Unstoppable Wallet: Crypto Wallets & Exchanges reference app'
---
