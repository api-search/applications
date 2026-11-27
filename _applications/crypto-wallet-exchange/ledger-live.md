---
app: Ledger Live
app_slug: ledger-live
app_url: https://github.com/LedgerHQ/ledger-live
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-190.30.20
  key: AE-190.30.20
  layer: domain
  name: Crypto Exchanges & Wallets
  providers:
  - MoonPay
  url: /capabilities/retail-investing/
  via_parent: Retail Investing
- attribution: API Evangelist extension
  id: AE-240.60.10
  key: AE-240.60.10
  layer: domain
  name: Decentralized Exchanges
  providers:
  - 1inch
  - LI.FI
  - NEAR Intents
  - OKX
  - ParaSwap / Velora
  - Swaps.xyz
  - THORSwap
  url: /capabilities/defi-protocols/
  via_parent: DeFi Protocols
- attribution: API Evangelist extension
  id: AE-240.60.30
  key: AE-240.60.30
  layer: domain
  name: Instant Exchange & Swap Services
  providers:
  - Changelly
  - Exodus
  url: /capabilities/defi-protocols/
  via_parent: DeFi Protocols
- attribution: Turbo EA
  id: BC-4260.40
  key: customer-lifecycle-engagement
  layer: common
  name: Customer Lifecycle Engagement
  providers:
  - Braze
  url: /capabilities/customer-lifecycle-engagement/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-903
  key: AE-903
  layer: common
  name: In-App Ad Monetisation
  providers:
  - Google AdMob
  url: /capabilities/in-app-ad-monetisation/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Datadog
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Firebase
  - Segment
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.30
  key: AE-150.30
  layer: common
  name: Push Notifications
  providers:
  - Firebase
  url: /capabilities/push-notifications/
  via_parent: null
category:
  id: crypto-wallet-exchange
  name: Crypto Wallets & Exchanges
  url: /applications/crypto-wallet-exchange/
counts:
  declared: 0
  observed: 16
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.ledger.live/latest/
- route: dependency manifest
  url: https://github.com/LedgerHQ/ledger-live/blob/develop/apps/ledger-live-desktop/package.json
- route: dependency manifest
  url: https://github.com/LedgerHQ/ledger-live/blob/develop/apps/ledger-live-mobile/package.json
- route: source code
  url: https://github.com/LedgerHQ/ledger-live/blob/develop/libs/ledger-live-common/src/exchange/providers/swap.ts
integrations:
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
    agent_readiness: 18.9
    band: emerging
    in_catalog: true
    kin_score: 20.3
    mcp: &id002
      source: https://business.1inch.com/1inch-mcp
      status: verified
    slug: 1inch
    status: profiled
    tags: &id003
    - DEX Aggregator
    - DeFi
    - Limit Orders
    - Swap
    url: /providers/1inch/
  layer: domain
  name: 1inch
  provider: 1inch
  says: ships the 1inch SDK or integration code
  source: https://github.com/LedgerHQ/ledger-live/blob/develop/libs/ledger-live-common/src/exchange/providers/swap.ts
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4260.40
    key: customer-lifecycle-engagement
    name: Customer Lifecycle Engagement
    url: /capabilities/customer-lifecycle-engagement/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 58.4
    band: exemplar
    in_catalog: true
    kin_score: 74.4
    mcp: &id004
      source: https://www.braze.com/docs/user_guide/brazeai/mcp_server
      status: verified
    slug: braze
    status: profiled
    tags: &id005
    - Customer Engagement
    - Marketing Automation
    - Messaging
    - Push Notifications
    url: /providers/braze/
  layer: common
  name: Braze
  provider: braze
  says: ships the Braze SDK or integration code
  source: https://github.com/LedgerHQ/ledger-live/blob/develop/apps/ledger-live-desktop/package.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-240.60.30
    key: AE-240.60.30
    name: Instant Exchange & Swap Services
    url: /capabilities/defi-protocols/
    via_parent: DeFi Protocols
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 20.1
    band: thin
    in_catalog: true
    kin_score: 28.9
    mcp: &id006
      status: unchecked
    slug: changelly
    status: profiled
    tags: &id007
    - Company
    - Cryptocurrency
    - Exchange
    - Fintech
    url: /providers/changelly/
  layer: domain
  name: Changelly
  provider: changelly
  says: ships the Changelly SDK or integration code
  source: https://github.com/LedgerHQ/ledger-live/blob/develop/libs/ledger-live-common/src/exchange/providers/swap.ts
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
    agent_readiness: 48.6
    band: exemplar
    in_catalog: true
    kin_score: 80.0
    mcp: &id008
      source: https://github.com/datadog-labs/mcp-server
      status: verified
    slug: datadog
    status: profiled
    tags: &id009
    - Analytics
    - Dashboards
    - Datadog
    - Visualization
    url: /providers/datadog/
  layer: common
  name: Datadog
  provider: datadog
  says: ships the Datadog SDK or integration code
  source: https://github.com/LedgerHQ/ledger-live/blob/develop/apps/ledger-live-desktop/package.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-240.60.30
    key: AE-240.60.30
    name: Instant Exchange & Swap Services
    url: /capabilities/defi-protocols/
    via_parent: DeFi Protocols
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id010
      status: unchecked
    slug: exodus
    status: queued for profiling
    tags: &id011 []
    url: null
  layer: domain
  name: Exodus
  provider: exodus
  says: ships the Exodus SDK or integration code
  source: https://github.com/LedgerHQ/ledger-live/blob/develop/libs/ledger-live-common/src/exchange/providers/swap.ts
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.30
    key: AE-150.30
    name: Push Notifications
    url: /capabilities/push-notifications/
    via_parent: null
  credit: null
  facts: &id001
    agent_band: agent-ready
    agent_readiness: 39.9
    band: strong
    in_catalog: true
    kin_score: 62.0
    mcp: &id012
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: google-firebase
    status: profiled
    tags: &id013
    - Analytics
    - Authentication
    - Backend-as-a-Service
    - Cloud Messaging
    url: /providers/google-firebase/
  layer: common
  name: Firebase
  provider: firebase
  says: ships the Firebase SDK or integration code
  source: https://github.com/LedgerHQ/ledger-live/blob/develop/apps/ledger-live-mobile/package.json
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts: *id001
  layer: common
  name: Firebase
  provider: firebase
  says: ships the Firebase SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.ledger.live/latest/
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-903
    key: AE-903
    name: In-App Ad Monetisation
    url: /capabilities/in-app-ad-monetisation/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-ready
    agent_readiness: 35.3
    band: strong
    in_catalog: true
    kin_score: 65.2
    mcp: &id014
      status: none
    slug: google-admob
    status: profiled
    tags: &id015
    - Ad Mediation
    - AdMob
    - Advertising
    - App Monetization
    url: /providers/google-admob/
  layer: common
  name: Google AdMob
  provider: google-admob
  says: ships the Google AdMob SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.ledger.live/latest/
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
    agent_readiness: 40.9
    band: strong
    in_catalog: true
    kin_score: 59.9
    mcp: &id016
      source: https://docs.li.fi/lifi-intents/mcp-server/overview
      status: verified
    slug: lifi
    status: profiled
    tags: &id017
    - Blockchain
    - Company
    - Cross-Chain
    - Web3
    url: /providers/lifi/
  layer: domain
  name: LI.FI
  provider: lifi
  says: ships the LI.FI SDK or integration code
  source: https://github.com/LedgerHQ/ledger-live/blob/develop/libs/ledger-live-common/src/exchange/providers/swap.ts
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
    agent_readiness: 29.6
    band: strong
    in_catalog: true
    kin_score: 55.8
    mcp: &id018
      source: https://support.moonpay.com/llms.txt
      status: documented
    slug: moonpay
    status: profiled
    tags: &id019
    - Company
    - Crypto Infrastructure
    - Cryptocurrency
    - Payments
    url: /providers/moonpay/
  layer: domain
  name: MoonPay
  provider: moonpay
  says: ships the MoonPay SDK or integration code
  source: https://github.com/LedgerHQ/ledger-live/blob/develop/libs/ledger-live-common/src/exchange/providers/swap.ts
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
    agent_readiness: 22.4
    band: emerging
    in_catalog: true
    kin_score: 23.7
    mcp: &id020
      status: none
    slug: near
    status: profiled
    tags: &id021
    - Blockchain
    - NEAR
    - NFT
    - Web3
    url: /providers/near/
  layer: domain
  name: NEAR Intents
  provider: near
  says: ships the NEAR Intents SDK or integration code
  source: https://github.com/LedgerHQ/ledger-live/blob/develop/libs/ledger-live-common/src/exchange/providers/swap.ts
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
    agent_readiness: 15.8
    band: thin
    in_catalog: true
    kin_score: 28.9
    mcp: &id022
      source: https://github.com/okx/agent-trade-kit
      status: verified
    slug: okx
    status: profiled
    tags: &id023
    - Cryptocurrency
    - Derivatives
    - Exchange
    - Trading
    url: /providers/okx/
  layer: domain
  name: OKX
  provider: okx
  says: ships the OKX SDK or integration code
  source: https://github.com/LedgerHQ/ledger-live/blob/develop/libs/ledger-live-common/src/exchange/providers/swap.ts
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
    agent_readiness: 31.5
    band: emerging
    in_catalog: true
    kin_score: 25.2
    mcp: &id024
      source: https://www.velora.xyz/docs/for-agents/mcp-server/overview
      status: verified
    slug: paraswap
    status: profiled
    tags: &id025
    - Blockchain
    - DEX Aggregator
    - DeFi
    - Token Swaps
    url: /providers/paraswap/
  layer: domain
  name: ParaSwap / Velora
  provider: paraswap
  says: ships the ParaSwap / Velora SDK or integration code
  source: https://github.com/LedgerHQ/ledger-live/blob/develop/libs/ledger-live-common/src/exchange/providers/swap.ts
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
    mcp: &id026
      status: none
    slug: segment
    status: profiled
    tags: &id027
    - CDP
    - Company
    - Customer Data Platform
    - Identity Resolution
    url: /providers/segment/
  layer: common
  name: Segment
  provider: segment
  says: ships the Segment SDK or integration code
  source: https://github.com/LedgerHQ/ledger-live/blob/develop/apps/ledger-live-desktop/package.json
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
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id028
      status: unchecked
    slug: swaps-xyz
    status: queued for profiling
    tags: &id029 []
    url: null
  layer: domain
  name: Swaps.xyz
  provider: swaps-xyz
  says: ships the Swaps.xyz SDK or integration code
  source: https://github.com/LedgerHQ/ledger-live/blob/develop/libs/ledger-live-common/src/exchange/providers/swap.ts
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
    agent_band: human-only
    agent_readiness: 2.8
    band: emerging
    in_catalog: true
    kin_score: 11.4
    mcp: &id030
      status: unchecked
    slug: thorswap
    status: profiled
    tags: &id031
    - DeFi
    - Decentralized Exchange
    - Multi-Chain
    - SwapKit
    url: /providers/thorswap/
  layer: domain
  name: THORSwap
  provider: thorswap
  says: ships the THORSwap SDK or integration code
  source: https://github.com/LedgerHQ/ledger-live/blob/develop/libs/ledger-live-common/src/exchange/providers/swap.ts
  tier: observed
kind: open-source-saas
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/crypto-wallet-exchange/ledger-live/
providers:
- agent_band: agent-aware
  agent_readiness: 18.9
  band: emerging
  in_catalog: true
  kin_score: 20.3
  mcp: *id002
  name: 1inch
  slug: 1inch
  status: profiled
  tags: *id003
  url: /providers/1inch/
- agent_band: agent-ready
  agent_readiness: 58.4
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id004
  name: Braze
  slug: braze
  status: profiled
  tags: *id005
  url: /providers/braze/
- agent_band: agent-aware
  agent_readiness: 20.1
  band: thin
  in_catalog: true
  kin_score: 28.9
  mcp: *id006
  name: Changelly
  slug: changelly
  status: profiled
  tags: *id007
  url: /providers/changelly/
- agent_band: agent-ready
  agent_readiness: 48.6
  band: exemplar
  in_catalog: true
  kin_score: 80.0
  mcp: *id008
  name: Datadog
  slug: datadog
  status: profiled
  tags: *id009
  url: /providers/datadog/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id010
  name: Exodus
  slug: exodus
  status: queued for profiling
  tags: *id011
  url: null
- agent_band: agent-ready
  agent_readiness: 39.9
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id012
  name: Firebase
  slug: google-firebase
  status: profiled
  tags: *id013
  url: /providers/google-firebase/
- agent_band: agent-ready
  agent_readiness: 35.3
  band: strong
  in_catalog: true
  kin_score: 65.2
  mcp: *id014
  name: Google AdMob
  slug: google-admob
  status: profiled
  tags: *id015
  url: /providers/google-admob/
- agent_band: agent-ready
  agent_readiness: 40.9
  band: strong
  in_catalog: true
  kin_score: 59.9
  mcp: *id016
  name: LI.FI
  slug: lifi
  status: profiled
  tags: *id017
  url: /providers/lifi/
- agent_band: agent-ready
  agent_readiness: 29.6
  band: strong
  in_catalog: true
  kin_score: 55.8
  mcp: *id018
  name: MoonPay
  slug: moonpay
  status: profiled
  tags: *id019
  url: /providers/moonpay/
- agent_band: agent-aware
  agent_readiness: 22.4
  band: emerging
  in_catalog: true
  kin_score: 23.7
  mcp: *id020
  name: NEAR Intents
  slug: near
  status: profiled
  tags: *id021
  url: /providers/near/
- agent_band: agent-aware
  agent_readiness: 15.8
  band: thin
  in_catalog: true
  kin_score: 28.9
  mcp: *id022
  name: OKX
  slug: okx
  status: profiled
  tags: *id023
  url: /providers/okx/
- agent_band: agent-ready
  agent_readiness: 31.5
  band: emerging
  in_catalog: true
  kin_score: 25.2
  mcp: *id024
  name: ParaSwap / Velora
  slug: paraswap
  status: profiled
  tags: *id025
  url: /providers/paraswap/
- agent_band: agent-aware
  agent_readiness: 27.7
  band: developing
  in_catalog: true
  kin_score: 42.9
  mcp: *id026
  name: Segment
  slug: segment
  status: profiled
  tags: *id027
  url: /providers/segment/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id028
  name: Swaps.xyz
  slug: swaps-xyz
  status: queued for profiling
  tags: *id029
  url: null
- agent_band: human-only
  agent_readiness: 2.8
  band: emerging
  in_catalog: true
  kin_score: 11.4
  mcp: *id030
  name: THORSwap
  slug: thorswap
  status: profiled
  tags: *id031
  url: /providers/thorswap/
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
title: 'Ledger Live: Crypto Wallets & Exchanges reference app'
---
