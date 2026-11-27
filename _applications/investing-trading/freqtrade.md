---
app: Freqtrade
app_slug: freqtrade
app_url: https://github.com/freqtrade/freqtrade
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-190.30.20
  key: AE-190.30.20
  layer: domain
  name: Crypto Exchanges & Wallets
  providers:
  - Binance
  - BingX
  - Bitget
  - Bitpanda
  - Bitvavo
  - Bybit
  - CoinEx
  - Crypto.com
  - Gate.io
  - HitBTC
  - HTX
  - Hyperliquid
  - IDEX (exchange)
  - Kraken
  - KuCoin
  - LBank
  - Luno
  - OKX
  url: /capabilities/retail-investing/
  via_parent: Retail Investing
- attribution: API Evangelist extension
  id: AE-230.20.10
  key: AE-230.20.10
  layer: domain
  name: Exchange Rates
  providers:
  - CoinGecko
  url: /capabilities/market-financial-data/
  via_parent: Market & Financial Data
- attribution: Turbo EA
  id: BC-850.10
  key: internal-communications-management
  layer: common
  name: Internal Communications Management
  providers:
  - Discord
  url: /capabilities/internal-communications-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.20.20
  key: AE-150.20.20
  layer: common
  name: WhatsApp & OTT Messaging
  providers:
  - Telegram
  url: /capabilities/sms-messaging-apps/
  via_parent: SMS & Messaging Apps
category:
  id: investing-trading
  name: Investing & Trading
  url: /applications/investing-trading/
counts:
  declared: 0
  observed: 21
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/freqtrade/freqtrade/develop/requirements.txt
- route: source code
  url: https://github.com/freqtrade/freqtrade/tree/develop/freqtrade/exchange
- route: source code
  url: https://github.com/freqtrade/freqtrade/tree/develop/freqtrade/rpc
integrations:
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
    agent_readiness: 29.9
    band: thin
    in_catalog: true
    kin_score: 38.9
    mcp: &id001
      status: none
    slug: binance
    status: profiled
    tags: &id002
    - Blockchain
    - Cryptocurrency
    - Exchange
    - Trading
    url: /providers/binance/
  layer: domain
  name: Binance
  provider: binance
  says: ships the Binance SDK or integration code
  source: https://github.com/freqtrade/freqtrade/tree/develop/freqtrade/exchange
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
    agent_readiness: 17.5
    band: emerging
    in_catalog: true
    kin_score: 20.8
    mcp: &id003
      status: none
    slug: bingx
    status: profiled
    tags: &id004
    - Company
    - Cryptocurrency
    - Exchange
    - Trading
    url: /providers/bingx/
  layer: domain
  name: BingX
  provider: bingx
  says: ships the BingX SDK or integration code
  source: https://github.com/freqtrade/freqtrade/tree/develop/freqtrade/exchange
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
    agent_readiness: 15.1
    band: emerging
    in_catalog: true
    kin_score: 24.3
    mcp: &id005
      source: https://github.com/Bitget-AI/agent-mcp
      status: verified
    slug: bitget
    status: profiled
    tags: &id006
    - Cryptocurrency
    - Exchange
    - Futures
    - Spot Trading
    url: /providers/bitget/
  layer: domain
  name: Bitget
  provider: bitget
  says: ships the Bitget SDK or integration code
  source: https://github.com/freqtrade/freqtrade/tree/develop/freqtrade/exchange
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
    agent_readiness: 27.7
    band: developing
    in_catalog: true
    kin_score: 46.0
    mcp: &id007
      source: https://github.com/bitpanda-labs/bitpanda-mcp
      status: verified
    slug: bitpanda
    status: profiled
    tags: &id008
    - Company
    - Cryptocurrency
    - Fintech
    - Trading
    url: /providers/bitpanda/
  layer: domain
  name: Bitpanda
  provider: bitpanda
  says: ships the Bitpanda SDK or integration code
  source: https://github.com/freqtrade/freqtrade/tree/develop/freqtrade/exchange
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
    agent_readiness: 33.6
    band: thin
    in_catalog: true
    kin_score: 33.6
    mcp: &id009
      status: none
    slug: bitvavo
    status: profiled
    tags: &id010
    - Company
    - Cryptocurrency
    - Exchange
    - Trading
    url: /providers/bitvavo/
  layer: domain
  name: Bitvavo
  provider: bitvavo
  says: ships the Bitvavo SDK or integration code
  source: https://github.com/freqtrade/freqtrade/tree/develop/freqtrade/exchange
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
    agent_readiness: 13.7
    band: emerging
    in_catalog: true
    kin_score: 15.0
    mcp: &id011
      source: https://github.com/bybit-exchange/trading-mcp
      status: verified
    slug: bybit
    status: profiled
    tags: &id012
    - Cryptocurrency
    - Public APIs
    - Real-Time
    url: /providers/bybit/
  layer: domain
  name: Bybit
  provider: bybit
  says: ships the Bybit SDK or integration code
  source: https://github.com/freqtrade/freqtrade/tree/develop/freqtrade/exchange
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
    agent_band: human-only
    agent_readiness: 4.9
    band: emerging
    in_catalog: true
    kin_score: 24.2
    mcp: &id013
      source: https://github.com/coinexcom/coinex_mcp_server
      status: verified
    slug: coinex
    status: profiled
    tags: &id014
    - Cryptocurrency
    - Exchange
    - Futures
    - Spot Trading
    url: /providers/coinex/
  layer: domain
  name: CoinEx
  provider: coinex
  says: ships the CoinEx SDK or integration code
  source: https://github.com/freqtrade/freqtrade/tree/develop/freqtrade/exchange
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
    mcp: &id015
      source: https://docs.coingecko.com/reference/mcp-server
      status: verified
    slug: coingecko
    status: profiled
    tags: &id016
    - Aggregator
    - Blockchain
    - CoinGecko
    - Cryptocurrency
    url: /providers/coingecko/
  layer: domain
  name: CoinGecko
  provider: coingecko
  says: ships the CoinGecko SDK or integration code
  source: https://raw.githubusercontent.com/freqtrade/freqtrade/develop/requirements.txt
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
    agent_band: agent-native
    agent_readiness: 45.3
    band: strong
    in_catalog: true
    kin_score: 66.0
    mcp: &id017
      source: https://mcp.crypto.com/docs
      status: verified
    slug: crypto-com
    status: profiled
    tags: &id018
    - Cryptocurrency
    - Cryptocurrency Exchange
    - Derivatives
    - Trading
    url: /providers/crypto-com/
  layer: domain
  name: Crypto.com
  provider: crypto-com
  says: ships the Crypto.com SDK or integration code
  source: https://github.com/freqtrade/freqtrade/tree/develop/freqtrade/exchange
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-850.10
    key: internal-communications-management
    name: Internal Communications Management
    url: /capabilities/internal-communications-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.1
    band: developing
    in_catalog: true
    kin_score: 48.0
    mcp: &id019
      status: none
    slug: discord
    status: profiled
    tags: &id020
    - Chat
    - Communications
    - Discord
    - Gaming
    url: /providers/discord/
  layer: common
  name: Discord
  provider: discord
  says: ships the Discord SDK or integration code
  source: https://github.com/freqtrade/freqtrade/tree/develop/freqtrade/rpc
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
    agent_readiness: 13.3
    band: emerging
    in_catalog: true
    kin_score: 25.1
    mcp: &id021
      source: https://github.com/gate/gate-mcp
      status: verified
    slug: gate-io
    status: profiled
    tags: &id022
    - Cryptocurrency
    - Exchange
    - Spot Trading
    - Trading
    url: /providers/gate-io/
  layer: domain
  name: Gate.io
  provider: gate-io
  says: ships the Gate.io SDK or integration code
  source: https://github.com/freqtrade/freqtrade/tree/develop/freqtrade/exchange
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
    agent_readiness: 31.0
    band: developing
    in_catalog: true
    kin_score: 40.5
    mcp: &id023
      status: none
    slug: hitbtc
    status: profiled
    tags: &id024
    - Company
    - Cryptocurrency
    - Cryptocurrency Exchange
    - Trading
    url: /providers/hitbtc/
  layer: domain
  name: HitBTC
  provider: hitbtc
  says: ships the HitBTC SDK or integration code
  source: https://github.com/freqtrade/freqtrade/tree/develop/freqtrade/exchange
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
    agent_readiness: 21.5
    band: developing
    in_catalog: true
    kin_score: 44.5
    mcp: &id025
      status: none
    slug: htx
    status: profiled
    tags: &id026
    - Company
    - Cryptocurrency
    - Cryptocurrency Exchange
    - Technology
    url: /providers/htx/
  layer: domain
  name: HTX
  provider: htx
  says: ships the HTX SDK or integration code
  source: https://github.com/freqtrade/freqtrade/tree/develop/freqtrade/exchange
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
    agent_readiness: 16.1
    band: thin
    in_catalog: true
    kin_score: 30.8
    mcp: &id027
      status: none
    slug: hyperliquid
    status: profiled
    tags: &id028
    - DeFi
    - Decentralized Exchange
    - Layer 1
    - Perpetuals
    url: /providers/hyperliquid/
  layer: domain
  name: Hyperliquid
  provider: hyperliquid
  says: ships the Hyperliquid SDK or integration code
  source: https://github.com/freqtrade/freqtrade/tree/develop/freqtrade/exchange
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
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id029
      status: unchecked
    slug: idex-io
    status: queued for profiling
    tags: &id030 []
    url: null
  layer: domain
  name: IDEX (exchange)
  provider: idex-io
  says: ships the IDEX (exchange) SDK or integration code
  source: https://github.com/freqtrade/freqtrade/tree/develop/freqtrade/exchange
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
    agent_readiness: 37.5
    band: strong
    in_catalog: true
    kin_score: 63.1
    mcp: &id031
      source: https://github.com/krakenfx/kraken-cli
      status: verified
    slug: kraken
    status: profiled
    tags: &id032
    - Cryptocurrency
    - Exchange
    - Kraken
    - Trading
    url: /providers/kraken/
  layer: domain
  name: Kraken
  provider: kraken
  says: ships the Kraken SDK or integration code
  source: https://github.com/freqtrade/freqtrade/tree/develop/freqtrade/exchange
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
    agent_readiness: 13.7
    band: emerging
    in_catalog: true
    kin_score: 14.6
    mcp: &id033
      status: none
    slug: kucoin
    status: profiled
    tags: &id034
    - Cryptocurrency
    - Public APIs
    - Real-Time
    url: /providers/kucoin/
  layer: domain
  name: KuCoin
  provider: kucoin
  says: ships the KuCoin SDK or integration code
  source: https://github.com/freqtrade/freqtrade/tree/develop/freqtrade/exchange
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
    agent_readiness: 22.5
    band: thin
    in_catalog: true
    kin_score: 32.5
    mcp: &id035
      status: none
    slug: lbank
    status: profiled
    tags: &id036
    - Cryptocurrency
    - Exchange
    - Market Data
    - Trading
    url: /providers/lbank/
  layer: domain
  name: LBank
  provider: lbank
  says: ships the LBank SDK or integration code
  source: https://github.com/freqtrade/freqtrade/tree/develop/freqtrade/exchange
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
    agent_readiness: 26.3
    band: developing
    in_catalog: true
    kin_score: 49.7
    mcp: &id037
      source: https://github.com/luno/luno-mcp
      status: verified
    slug: luno
    status: profiled
    tags: &id038
    - Bitcoin
    - Company
    - Cryptocurrency
    - Exchange
    url: /providers/luno/
  layer: domain
  name: Luno
  provider: luno
  says: ships the Luno SDK or integration code
  source: https://github.com/freqtrade/freqtrade/tree/develop/freqtrade/exchange
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
    agent_readiness: 15.8
    band: thin
    in_catalog: true
    kin_score: 28.9
    mcp: &id039
      source: https://github.com/okx/agent-trade-kit
      status: verified
    slug: okx
    status: profiled
    tags: &id040
    - Cryptocurrency
    - Derivatives
    - Exchange
    - Trading
    url: /providers/okx/
  layer: domain
  name: OKX
  provider: okx
  says: ships the OKX SDK or integration code
  source: https://github.com/freqtrade/freqtrade/tree/develop/freqtrade/exchange
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.20
    key: AE-150.20.20
    name: WhatsApp & OTT Messaging
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.3
    band: strong
    in_catalog: true
    kin_score: 56.8
    mcp: &id041
      status: none
    slug: telegram
    status: profiled
    tags: &id042
    - Bots
    - Chat
    - Messaging
    - Notification
    url: /providers/telegram/
  layer: common
  name: Telegram
  provider: telegram
  says: ships the Telegram SDK or integration code
  source: https://raw.githubusercontent.com/freqtrade/freqtrade/develop/requirements.txt
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/investing-trading/freqtrade/
providers:
- agent_band: agent-ready
  agent_readiness: 29.9
  band: thin
  in_catalog: true
  kin_score: 38.9
  mcp: *id001
  name: Binance
  slug: binance
  status: profiled
  tags: *id002
  url: /providers/binance/
- agent_band: agent-aware
  agent_readiness: 17.5
  band: emerging
  in_catalog: true
  kin_score: 20.8
  mcp: *id003
  name: BingX
  slug: bingx
  status: profiled
  tags: *id004
  url: /providers/bingx/
- agent_band: agent-aware
  agent_readiness: 15.1
  band: emerging
  in_catalog: true
  kin_score: 24.3
  mcp: *id005
  name: Bitget
  slug: bitget
  status: profiled
  tags: *id006
  url: /providers/bitget/
- agent_band: agent-aware
  agent_readiness: 27.7
  band: developing
  in_catalog: true
  kin_score: 46.0
  mcp: *id007
  name: Bitpanda
  slug: bitpanda
  status: profiled
  tags: *id008
  url: /providers/bitpanda/
- agent_band: agent-ready
  agent_readiness: 33.6
  band: thin
  in_catalog: true
  kin_score: 33.6
  mcp: *id009
  name: Bitvavo
  slug: bitvavo
  status: profiled
  tags: *id010
  url: /providers/bitvavo/
- agent_band: agent-aware
  agent_readiness: 13.7
  band: emerging
  in_catalog: true
  kin_score: 15.0
  mcp: *id011
  name: Bybit
  slug: bybit
  status: profiled
  tags: *id012
  url: /providers/bybit/
- agent_band: human-only
  agent_readiness: 4.9
  band: emerging
  in_catalog: true
  kin_score: 24.2
  mcp: *id013
  name: CoinEx
  slug: coinex
  status: profiled
  tags: *id014
  url: /providers/coinex/
- agent_band: agent-ready
  agent_readiness: 47.4
  band: developing
  in_catalog: true
  kin_score: 52.4
  mcp: *id015
  name: CoinGecko
  slug: coingecko
  status: profiled
  tags: *id016
  url: /providers/coingecko/
- agent_band: agent-native
  agent_readiness: 45.3
  band: strong
  in_catalog: true
  kin_score: 66.0
  mcp: *id017
  name: Crypto.com
  slug: crypto-com
  status: profiled
  tags: *id018
  url: /providers/crypto-com/
- agent_band: agent-ready
  agent_readiness: 33.1
  band: developing
  in_catalog: true
  kin_score: 48.0
  mcp: *id019
  name: Discord
  slug: discord
  status: profiled
  tags: *id020
  url: /providers/discord/
- agent_band: agent-aware
  agent_readiness: 13.3
  band: emerging
  in_catalog: true
  kin_score: 25.1
  mcp: *id021
  name: Gate.io
  slug: gate-io
  status: profiled
  tags: *id022
  url: /providers/gate-io/
- agent_band: agent-ready
  agent_readiness: 31.0
  band: developing
  in_catalog: true
  kin_score: 40.5
  mcp: *id023
  name: HitBTC
  slug: hitbtc
  status: profiled
  tags: *id024
  url: /providers/hitbtc/
- agent_band: agent-aware
  agent_readiness: 21.5
  band: developing
  in_catalog: true
  kin_score: 44.5
  mcp: *id025
  name: HTX
  slug: htx
  status: profiled
  tags: *id026
  url: /providers/htx/
- agent_band: agent-aware
  agent_readiness: 16.1
  band: thin
  in_catalog: true
  kin_score: 30.8
  mcp: *id027
  name: Hyperliquid
  slug: hyperliquid
  status: profiled
  tags: *id028
  url: /providers/hyperliquid/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id029
  name: IDEX (exchange)
  slug: idex-io
  status: queued for profiling
  tags: *id030
  url: null
- agent_band: agent-ready
  agent_readiness: 37.5
  band: strong
  in_catalog: true
  kin_score: 63.1
  mcp: *id031
  name: Kraken
  slug: kraken
  status: profiled
  tags: *id032
  url: /providers/kraken/
- agent_band: agent-aware
  agent_readiness: 13.7
  band: emerging
  in_catalog: true
  kin_score: 14.6
  mcp: *id033
  name: KuCoin
  slug: kucoin
  status: profiled
  tags: *id034
  url: /providers/kucoin/
- agent_band: agent-aware
  agent_readiness: 22.5
  band: thin
  in_catalog: true
  kin_score: 32.5
  mcp: *id035
  name: LBank
  slug: lbank
  status: profiled
  tags: *id036
  url: /providers/lbank/
- agent_band: agent-aware
  agent_readiness: 26.3
  band: developing
  in_catalog: true
  kin_score: 49.7
  mcp: *id037
  name: Luno
  slug: luno
  status: profiled
  tags: *id038
  url: /providers/luno/
- agent_band: agent-aware
  agent_readiness: 15.8
  band: thin
  in_catalog: true
  kin_score: 28.9
  mcp: *id039
  name: OKX
  slug: okx
  status: profiled
  tags: *id040
  url: /providers/okx/
- agent_band: agent-aware
  agent_readiness: 25.3
  band: strong
  in_catalog: true
  kin_score: 56.8
  mcp: *id041
  name: Telegram
  slug: telegram
  status: profiled
  tags: *id042
  url: /providers/telegram/
siblings:
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
- name: Wealthfolio
  rows: 16
  url: /applications/investing-trading/wealthfolio/
sitemap: true
title: 'Freqtrade: Investing & Trading reference app'
---
