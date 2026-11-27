---
app: BTCPay Server
app_slug: btcpay-server
app_url: https://github.com/btcpayserver/btcpayserver
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-230.20.10
  key: AE-230.20.10
  layer: domain
  name: Exchange Rates
  providers:
  - Bare Bitcoin
  - Binance
  - Bitbank
  - Bitcoin Kenya
  - Bitfinex
  - bitFlyer
  - Bitmynt
  - Bitnob
  - BitPay
  - BtcTurk
  - Buda
  - Bylls
  - Coinbase
  - CoinDCX
  - Coinmate
  - Free Currency Rates API (fawazahmed0/exchange-api)
  - HitBTC
  - Kraken
  - Luno
  - NDAX
  - Notbank
  - OKX
  - Poloniex
  - Ripio
  - Yadio
  url: /capabilities/market-financial-data/
  via_parent: Market & Financial Data
category:
  id: crypto-wallet-exchange
  name: Crypto Wallets & Exchanges
  url: /applications/crypto-wallet-exchange/
counts:
  declared: 0
  observed: 25
credits: []
evidence:
- route: source code
  url: https://github.com/btcpayserver/btcpayserver/blob/master/BTCPayServer/Hosting/BTCPayServerServices.cs
- route: source code
  url: https://github.com/btcpayserver/btcpayserver/tree/master/BTCPayServer.Rating/Providers
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
    agent_band: agent-ready
    agent_readiness: 29.9
    band: thin
    in_catalog: true
    kin_score: 37.6
    mcp: &id001
      status: unchecked
    slug: bare-bitcoin
    status: profiled
    tags: &id002
    - Company
    - Cryptocurrency
    - Finance
    - Payments
    url: /providers/bare-bitcoin/
  layer: domain
  name: Bare Bitcoin
  provider: bare-bitcoin
  says: ships the Bare Bitcoin SDK or integration code
  source: https://github.com/btcpayserver/btcpayserver/blob/master/BTCPayServer/Hosting/BTCPayServerServices.cs
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
    agent_readiness: 29.9
    band: thin
    in_catalog: true
    kin_score: 38.9
    mcp: &id003
      status: none
    slug: binance
    status: profiled
    tags: &id004
    - Blockchain
    - Cryptocurrency
    - Exchange
    - Trading
    url: /providers/binance/
  layer: domain
  name: Binance
  provider: binance
  says: ships the Binance SDK or integration code
  source: https://github.com/btcpayserver/btcpayserver/blob/master/BTCPayServer/Hosting/BTCPayServerServices.cs
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
    mcp: &id005
      source: https://github.com/bitbankinc/bitbank-mcp-server
      status: verified
    slug: bitbank
    status: profiled
    tags: &id006
    - Cryptocurrency
    - Exchange
    - Finance
    - Japan
    url: /providers/bitbank/
  layer: domain
  name: Bitbank
  provider: bitbank
  says: ships the Bitbank SDK or integration code
  source: https://github.com/btcpayserver/btcpayserver/blob/master/BTCPayServer/Hosting/BTCPayServerServices.cs
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
    agent_readiness: 3.0
    band: minimal
    in_catalog: true
    kin_score: 3.2
    mcp: &id007
      status: unchecked
    slug: bitcoin-kenya
    status: profiled
    tags: &id008
    - Bitcoin
    - Company
    - Cryptocurrency
    - Kenya
    url: /providers/bitcoin-kenya/
  layer: domain
  name: Bitcoin Kenya
  provider: bitcoin-kenya
  says: ships the Bitcoin Kenya SDK or integration code
  source: https://github.com/btcpayserver/btcpayserver/blob/master/BTCPayServer/Hosting/BTCPayServerServices.cs
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
    mcp: &id009
      status: none
    slug: bitfinex
    status: profiled
    tags: &id010
    - Cryptocurrency
    - Public APIs
    - Real-Time
    url: /providers/bitfinex/
  layer: domain
  name: Bitfinex
  provider: bitfinex
  says: ships the Bitfinex SDK or integration code
  source: https://github.com/btcpayserver/btcpayserver/blob/master/BTCPayServer/Hosting/BTCPayServerServices.cs
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
    mcp: &id011
      status: unknown
    slug: bitflyer
    status: profiled
    tags: &id012
    - Company
    - Cryptocurrency
    - Exchange
    - Trading
    url: /providers/bitflyer/
  layer: domain
  name: bitFlyer
  provider: bitflyer
  says: ships the bitFlyer SDK or integration code
  source: https://github.com/btcpayserver/btcpayserver/blob/master/BTCPayServer/Hosting/BTCPayServerServices.cs
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
    kin_score: 1.4
    mcp: &id013
      status: unchecked
    slug: bitmynt
    status: profiled
    tags: &id014
    - Bitcoin
    - Company
    - Exchange
    - Norway
    url: /providers/bitmynt/
  layer: domain
  name: Bitmynt
  provider: bitmynt
  says: ships the Bitmynt SDK or integration code
  source: https://github.com/btcpayserver/btcpayserver/blob/master/BTCPayServer/Hosting/BTCPayServerServices.cs
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
    agent_readiness: 49.8
    band: developing
    in_catalog: true
    kin_score: 49.9
    mcp: &id015
      status: unchecked
    slug: bitnob
    status: profiled
    tags: &id016
    - Bitcoin
    - Company
    - Fintech
    - Payments
    url: /providers/bitnob/
  layer: domain
  name: Bitnob
  provider: bitnob
  says: ships the Bitnob SDK or integration code
  source: https://github.com/btcpayserver/btcpayserver/blob/master/BTCPayServer/Hosting/BTCPayServerServices.cs
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
    mcp: &id017
      status: none
    slug: bitpay
    status: profiled
    tags: &id018
    - Bitcoin
    - Blockchain
    - Cryptocurrency
    - Payments
    url: /providers/bitpay/
  layer: domain
  name: BitPay
  provider: bitpay
  says: ships the BitPay SDK or integration code
  source: https://github.com/btcpayserver/btcpayserver/blob/master/BTCPayServer/Hosting/BTCPayServerServices.cs
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
    kin_score: 7.3
    mcp: &id019
      status: unknown
    slug: btcturk
    status: profiled
    tags: &id020
    - Cryptocurrency
    - Public APIs
    url: /providers/btcturk/
  layer: domain
  name: BtcTurk
  provider: btcturk
  says: ships the BtcTurk SDK or integration code
  source: https://github.com/btcpayserver/btcpayserver/blob/master/BTCPayServer/Hosting/BTCPayServerServices.cs
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
    agent_readiness: 18.2
    band: thin
    in_catalog: true
    kin_score: 34.0
    mcp: &id021
      status: unchecked
    slug: buda
    status: profiled
    tags: &id022
    - Stablecoins
    url: /providers/buda/
  layer: domain
  name: Buda
  provider: buda
  says: ships the Buda SDK or integration code
  source: https://github.com/btcpayserver/btcpayserver/blob/master/BTCPayServer/Hosting/BTCPayServerServices.cs
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
    agent_readiness: 2.8
    band: emerging
    in_catalog: true
    kin_score: 11.9
    mcp: &id023
      status: unchecked
    slug: bylls
    status: profiled
    tags: &id024
    - Bitcoin
    - Company
    - Cryptocurrency
    - Payments
    url: /providers/bylls/
  layer: domain
  name: Bylls
  provider: bylls
  says: ships the Bylls SDK or integration code
  source: https://github.com/btcpayserver/btcpayserver/blob/master/BTCPayServer/Hosting/BTCPayServerServices.cs
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
    mcp: &id025
      source: https://github.com/coinbase/payments-mcp
      status: verified
    slug: coinbase
    status: profiled
    tags: &id026
    - Blockchain
    - Cryptocurrency
    - Custody
    - Exchange
    url: /providers/coinbase/
  layer: domain
  name: Coinbase
  provider: coinbase
  says: ships the Coinbase SDK or integration code
  source: https://github.com/btcpayserver/btcpayserver/blob/master/BTCPayServer/Hosting/BTCPayServerServices.cs
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
    kin_score: 16.9
    mcp: &id027
      status: unknown
    slug: coindcx
    status: profiled
    tags: &id028
    - Cryptocurrency
    - Public APIs
    - Real-Time
    url: /providers/coindcx/
  layer: domain
  name: CoinDCX
  provider: coindcx
  says: ships the CoinDCX SDK or integration code
  source: https://github.com/btcpayserver/btcpayserver/blob/master/BTCPayServer/Hosting/BTCPayServerServices.cs
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
    agent_readiness: 27.4
    band: thin
    in_catalog: true
    kin_score: 32.4
    mcp: &id029
      status: unchecked
    slug: coinmate
    status: profiled
    tags: &id030
    - Cryptocurrency Exchange
    - Premium Trading
    - Recurring Buy
    - Trading Platform
    url: /providers/coinmate/
  layer: domain
  name: Coinmate
  provider: coinmate
  says: ships the Coinmate SDK or integration code
  source: https://github.com/btcpayserver/btcpayserver/blob/master/BTCPayServer/Hosting/BTCPayServerServices.cs
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
    kin_score: 4.6
    mcp: &id031
      status: unchecked
    slug: freecurrencyrates
    status: profiled
    tags: &id032
    - Currency
    - Finance
    - Free
    - Open Source
    url: /providers/freecurrencyrates/
  layer: domain
  name: Free Currency Rates API (fawazahmed0/exchange-api)
  provider: freecurrencyrates
  says: ships the Free Currency Rates API (fawazahmed0/exchange-api) SDK or integration code
  source: https://github.com/btcpayserver/btcpayserver/blob/master/BTCPayServer/Hosting/BTCPayServerServices.cs
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
    agent_readiness: 31.0
    band: developing
    in_catalog: true
    kin_score: 40.5
    mcp: &id033
      status: none
    slug: hitbtc
    status: profiled
    tags: &id034
    - Company
    - Cryptocurrency
    - Cryptocurrency Exchange
    - Trading
    url: /providers/hitbtc/
  layer: domain
  name: HitBTC
  provider: hitbtc
  says: ships the HitBTC SDK or integration code
  source: https://github.com/btcpayserver/btcpayserver/blob/master/BTCPayServer/Hosting/BTCPayServerServices.cs
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
    mcp: &id035
      source: https://github.com/krakenfx/kraken-cli
      status: verified
    slug: kraken
    status: profiled
    tags: &id036
    - Cryptocurrency
    - Exchange
    - Kraken
    - Trading
    url: /providers/kraken/
  layer: domain
  name: Kraken
  provider: kraken
  says: ships the Kraken SDK or integration code
  source: https://github.com/btcpayserver/btcpayserver/blob/master/BTCPayServer/Hosting/BTCPayServerServices.cs
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
  source: https://github.com/btcpayserver/btcpayserver/blob/master/BTCPayServer/Hosting/BTCPayServerServices.cs
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
    agent_readiness: 26.6
    band: emerging
    in_catalog: true
    kin_score: 24.8
    mcp: &id039
      status: unknown
    slug: ndax
    status: profiled
    tags: &id040
    - Company
    - Cryptocurrency
    - Exchange
    - Trading
    url: /providers/ndax/
  layer: domain
  name: NDAX
  provider: ndax
  says: ships the NDAX SDK or integration code
  source: https://github.com/btcpayserver/btcpayserver/blob/master/BTCPayServer/Hosting/BTCPayServerServices.cs
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
    agent_readiness: 30.9
    band: thin
    in_catalog: true
    kin_score: 34.2
    mcp: &id041
      status: unchecked
    slug: notbank
    status: profiled
    tags: &id042
    - Company
    - Cryptocurrency
    - Fintech
    - Payments
    url: /providers/notbank/
  layer: domain
  name: Notbank
  provider: notbank
  says: ships the Notbank SDK or integration code
  source: https://github.com/btcpayserver/btcpayserver/blob/master/BTCPayServer/Hosting/BTCPayServerServices.cs
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
    agent_readiness: 15.8
    band: thin
    in_catalog: true
    kin_score: 28.9
    mcp: &id043
      source: https://github.com/okx/agent-trade-kit
      status: verified
    slug: okx
    status: profiled
    tags: &id044
    - Cryptocurrency
    - Derivatives
    - Exchange
    - Trading
    url: /providers/okx/
  layer: domain
  name: OKX
  provider: okx
  says: ships the OKX SDK or integration code
  source: https://github.com/btcpayserver/btcpayserver/blob/master/BTCPayServer/Hosting/BTCPayServerServices.cs
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
    kin_score: 15.4
    mcp: &id045
      status: none
    slug: poloniex
    status: profiled
    tags: &id046
    - Cryptocurrency
    - Public APIs
    - Real-Time
    url: /providers/poloniex/
  layer: domain
  name: Poloniex
  provider: poloniex
  says: ships the Poloniex SDK or integration code
  source: https://github.com/btcpayserver/btcpayserver/blob/master/BTCPayServer/Hosting/BTCPayServerServices.cs
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
    agent_readiness: 33.8
    band: strong
    in_catalog: true
    kin_score: 59.8
    mcp: &id047
      status: none
    slug: ripio
    status: profiled
    tags: &id048
    - Company
    - Cryptocurrency
    - Exchange
    - Trading
    url: /providers/ripio/
  layer: domain
  name: Ripio
  provider: ripio
  says: ships the Ripio SDK or integration code
  source: https://github.com/btcpayserver/btcpayserver/blob/master/BTCPayServer/Hosting/BTCPayServerServices.cs
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
    mcp: &id049
      status: unchecked
    slug: yadio
    status: profiled
    tags: &id050
    - Company
    url: /providers/yadio/
  layer: domain
  name: Yadio
  provider: yadio
  says: ships the Yadio SDK or integration code
  source: https://github.com/btcpayserver/btcpayserver/blob/master/BTCPayServer/Hosting/BTCPayServerServices.cs
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/crypto-wallet-exchange/btcpay-server/
providers:
- agent_band: agent-ready
  agent_readiness: 29.9
  band: thin
  in_catalog: true
  kin_score: 37.6
  mcp: *id001
  name: Bare Bitcoin
  slug: bare-bitcoin
  status: profiled
  tags: *id002
  url: /providers/bare-bitcoin/
- agent_band: agent-ready
  agent_readiness: 29.9
  band: thin
  in_catalog: true
  kin_score: 38.9
  mcp: *id003
  name: Binance
  slug: binance
  status: profiled
  tags: *id004
  url: /providers/binance/
- agent_band: agent-aware
  agent_readiness: 14.8
  band: emerging
  in_catalog: true
  kin_score: 25.4
  mcp: *id005
  name: Bitbank
  slug: bitbank
  status: profiled
  tags: *id006
  url: /providers/bitbank/
- agent_band: human-only
  agent_readiness: 3.0
  band: minimal
  in_catalog: true
  kin_score: 3.2
  mcp: *id007
  name: Bitcoin Kenya
  slug: bitcoin-kenya
  status: profiled
  tags: *id008
  url: /providers/bitcoin-kenya/
- agent_band: agent-aware
  agent_readiness: 13.7
  band: emerging
  in_catalog: true
  kin_score: 17.3
  mcp: *id009
  name: Bitfinex
  slug: bitfinex
  status: profiled
  tags: *id010
  url: /providers/bitfinex/
- agent_band: agent-aware
  agent_readiness: 21.7
  band: emerging
  in_catalog: true
  kin_score: 18.1
  mcp: *id011
  name: bitFlyer
  slug: bitflyer
  status: profiled
  tags: *id012
  url: /providers/bitflyer/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 1.4
  mcp: *id013
  name: Bitmynt
  slug: bitmynt
  status: profiled
  tags: *id014
  url: /providers/bitmynt/
- agent_band: agent-native
  agent_readiness: 49.8
  band: developing
  in_catalog: true
  kin_score: 49.9
  mcp: *id015
  name: Bitnob
  slug: bitnob
  status: profiled
  tags: *id016
  url: /providers/bitnob/
- agent_band: agent-ready
  agent_readiness: 35.9
  band: thin
  in_catalog: true
  kin_score: 33.9
  mcp: *id017
  name: BitPay
  slug: bitpay
  status: profiled
  tags: *id018
  url: /providers/bitpay/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 7.3
  mcp: *id019
  name: BtcTurk
  slug: btcturk
  status: profiled
  tags: *id020
  url: /providers/btcturk/
- agent_band: agent-aware
  agent_readiness: 18.2
  band: thin
  in_catalog: true
  kin_score: 34.0
  mcp: *id021
  name: Buda
  slug: buda
  status: profiled
  tags: *id022
  url: /providers/buda/
- agent_band: human-only
  agent_readiness: 2.8
  band: emerging
  in_catalog: true
  kin_score: 11.9
  mcp: *id023
  name: Bylls
  slug: bylls
  status: profiled
  tags: *id024
  url: /providers/bylls/
- agent_band: agent-native
  agent_readiness: 50.8
  band: strong
  in_catalog: true
  kin_score: 57.2
  mcp: *id025
  name: Coinbase
  slug: coinbase
  status: profiled
  tags: *id026
  url: /providers/coinbase/
- agent_band: agent-aware
  agent_readiness: 13.7
  band: emerging
  in_catalog: true
  kin_score: 16.9
  mcp: *id027
  name: CoinDCX
  slug: coindcx
  status: profiled
  tags: *id028
  url: /providers/coindcx/
- agent_band: agent-aware
  agent_readiness: 27.4
  band: thin
  in_catalog: true
  kin_score: 32.4
  mcp: *id029
  name: Coinmate
  slug: coinmate
  status: profiled
  tags: *id030
  url: /providers/coinmate/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 4.6
  mcp: *id031
  name: Free Currency Rates API (fawazahmed0/exchange-api)
  slug: freecurrencyrates
  status: profiled
  tags: *id032
  url: /providers/freecurrencyrates/
- agent_band: agent-ready
  agent_readiness: 31.0
  band: developing
  in_catalog: true
  kin_score: 40.5
  mcp: *id033
  name: HitBTC
  slug: hitbtc
  status: profiled
  tags: *id034
  url: /providers/hitbtc/
- agent_band: agent-ready
  agent_readiness: 37.5
  band: strong
  in_catalog: true
  kin_score: 63.1
  mcp: *id035
  name: Kraken
  slug: kraken
  status: profiled
  tags: *id036
  url: /providers/kraken/
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
  agent_readiness: 26.6
  band: emerging
  in_catalog: true
  kin_score: 24.8
  mcp: *id039
  name: NDAX
  slug: ndax
  status: profiled
  tags: *id040
  url: /providers/ndax/
- agent_band: agent-ready
  agent_readiness: 30.9
  band: thin
  in_catalog: true
  kin_score: 34.2
  mcp: *id041
  name: Notbank
  slug: notbank
  status: profiled
  tags: *id042
  url: /providers/notbank/
- agent_band: agent-aware
  agent_readiness: 15.8
  band: thin
  in_catalog: true
  kin_score: 28.9
  mcp: *id043
  name: OKX
  slug: okx
  status: profiled
  tags: *id044
  url: /providers/okx/
- agent_band: agent-aware
  agent_readiness: 13.7
  band: emerging
  in_catalog: true
  kin_score: 15.4
  mcp: *id045
  name: Poloniex
  slug: poloniex
  status: profiled
  tags: *id046
  url: /providers/poloniex/
- agent_band: agent-ready
  agent_readiness: 33.8
  band: strong
  in_catalog: true
  kin_score: 59.8
  mcp: *id047
  name: Ripio
  slug: ripio
  status: profiled
  tags: *id048
  url: /providers/ripio/
- agent_band: agent-aware
  agent_readiness: 25.7
  band: thin
  in_catalog: true
  kin_score: 30.6
  mcp: *id049
  name: Yadio
  slug: yadio
  status: profiled
  tags: *id050
  url: /providers/yadio/
siblings:
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
- name: Unstoppable Wallet
  rows: 14
  url: /applications/crypto-wallet-exchange/unstoppable-wallet/
sitemap: true
title: 'BTCPay Server: Crypto Wallets & Exchanges reference app'
---
