---
app: rotki
app_slug: rotki
app_url: https://github.com/rotki/rotki
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-240.30.20
  key: AE-240.30.20
  layer: domain
  name: Blockchain Analytics
  providers:
  - DefiLlama
  url: /capabilities/on-chain-data-indexing/
  via_parent: On-Chain Data & Indexing
- attribution: API Evangelist extension
  id: AE-240.30.10
  key: AE-240.30.10
  layer: domain
  name: Blockchain Indexing
  providers:
  - Alchemy
  - beaconcha.in
  - Blockscout
  - Etherscan
  - Helius
  - Moralis
  - Routescan
  - SoChain
  - The Graph
  url: /capabilities/on-chain-data-indexing/
  via_parent: On-Chain Data & Indexing
- attribution: API Evangelist extension
  id: AE-190.30.20
  key: AE-190.30.20
  layer: domain
  name: Crypto Exchanges & Wallets
  providers:
  - Binance
  - Bit2Me
  - Bitcoin.de
  - Bitfinex
  - Bitpanda
  - Bitstamp
  - Bybit
  - Coinbase
  - CoinEx
  - Crypto.com
  - Gate.io
  - Gemini
  - HTX
  - ICONOMI
  - Independent Reserve
  - Kraken
  - KuCoin
  - OKX
  - Poloniex
  - WOO X
  url: /capabilities/retail-investing/
  via_parent: Retail Investing
- attribution: API Evangelist extension
  id: AE-240.60.10
  key: AE-240.60.10
  layer: domain
  name: Decentralized Exchanges
  providers:
  - CoW Swap
  - Jupiter
  url: /capabilities/defi-protocols/
  via_parent: DeFi Protocols
- attribution: API Evangelist extension
  id: AE-230.20.10
  key: AE-230.20.10
  layer: domain
  name: Exchange Rates
  providers:
  - X-Rates
  url: /capabilities/market-financial-data/
  via_parent: Market & Financial Data
- attribution: API Evangelist extension
  id: AE-150.80
  key: AE-150.80
  layer: domain
  name: Mailbox & Calendar Sync
  providers:
  - Google Calendar
  url: /capabilities/mailbox-calendar-sync/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-240.50.20
  key: AE-240.50.20
  layer: domain
  name: NFTs & Digital Collectibles
  providers:
  - OpenSea
  url: /capabilities/token-issuance-smart-contracts/
  via_parent: Token Issuance & Smart Contracts
- attribution: API Evangelist extension
  id: AE-230.20.20
  key: AE-230.20.20
  layer: domain
  name: Securities Market Data
  providers:
  - Birdeye (Solana data)
  - CoinGecko
  - CryptoCompare
  url: /capabilities/market-financial-data/
  via_parent: Market & Financial Data
- attribution: API Evangelist extension
  id: AE-240.70.10
  key: AE-240.70.10
  layer: domain
  name: Stablecoin Issuance
  providers:
  - Monerium
  url: /capabilities/stablecoin-payments/
  via_parent: Stablecoin Payments
- attribution: API Evangelist extension
  id: AE-240.70
  key: AE-240.70
  layer: domain
  name: Stablecoin Payments
  providers:
  - Gnosis Pay
  url: /capabilities/stablecoin-payments/
  via_parent: null
category:
  id: investing-trading
  name: Investing & Trading
  url: /applications/investing-trading/
counts:
  declared: 0
  observed: 40
credits: []
evidence:
- route: source code
  url: https://github.com/rotki/rotki/tree/develop/rotkehlchen/exchanges
- route: source code
  url: https://github.com/rotki/rotki/tree/develop/rotkehlchen/externalapis
integrations:
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
  source: https://github.com/rotki/rotki/tree/develop/rotkehlchen/externalapis
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
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 0.4
    mcp: &id003
      status: none
    slug: beaconcha-in
    status: profiled
    tags: &id004
    - Company
    url: /providers/beaconcha-in/
  layer: domain
  name: beaconcha.in
  provider: beaconcha-in
  says: ships the beaconcha.in SDK or integration code
  source: https://github.com/rotki/rotki/tree/develop/rotkehlchen/externalapis
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
    agent_readiness: 29.9
    band: thin
    in_catalog: true
    kin_score: 38.9
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
  source: https://github.com/rotki/rotki/tree/develop/rotkehlchen/exchanges
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
    agent_readiness: 26.7
    band: thin
    in_catalog: true
    kin_score: 33.8
    mcp: &id007
      status: none
    slug: birdeye-so
    status: profiled
    tags: &id008
    - Analytics
    - Blockchain
    - Company
    - Data
    url: /providers/birdeye-so/
  layer: domain
  name: Birdeye (Solana data)
  provider: birdeye-so
  says: ships the Birdeye (Solana data) SDK or integration code
  source: https://github.com/rotki/rotki/tree/develop/rotkehlchen/externalapis
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
    agent_readiness: 52.6
    band: strong
    in_catalog: true
    kin_score: 61.9
    mcp: &id009
      source: https://api.bit2me.com/docs
      status: documented
    slug: bit2me
    status: profiled
    tags: &id010
    - Company
    - Cryptocurrency
    - Exchange
    - Fintech
    url: /providers/bit2me/
  layer: domain
  name: Bit2Me
  provider: bit2me
  says: ships the Bit2Me SDK or integration code
  source: https://github.com/rotki/rotki/tree/develop/rotkehlchen/exchanges
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
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 19.7
    mcp: &id011
      status: unknown
    slug: bitcoin-de
    status: profiled
    tags: &id012
    - Company
    url: /providers/bitcoin-de/
  layer: domain
  name: Bitcoin.de
  provider: bitcoin-de
  says: ships the Bitcoin.de SDK or integration code
  source: https://github.com/rotki/rotki/tree/develop/rotkehlchen/exchanges
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
    kin_score: 17.3
    mcp: &id013
      status: none
    slug: bitfinex
    status: profiled
    tags: &id014
    - Cryptocurrency
    - Public APIs
    - Real-Time
    url: /providers/bitfinex/
  layer: domain
  name: Bitfinex
  provider: bitfinex
  says: ships the Bitfinex SDK or integration code
  source: https://github.com/rotki/rotki/tree/develop/rotkehlchen/exchanges
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
    mcp: &id015
      source: https://github.com/bitpanda-labs/bitpanda-mcp
      status: verified
    slug: bitpanda
    status: profiled
    tags: &id016
    - Company
    - Cryptocurrency
    - Fintech
    - Trading
    url: /providers/bitpanda/
  layer: domain
  name: Bitpanda
  provider: bitpanda
  says: ships the Bitpanda SDK or integration code
  source: https://github.com/rotki/rotki/tree/develop/rotkehlchen/exchanges
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
    agent_readiness: 29.4
    band: thin
    in_catalog: true
    kin_score: 33.5
    mcp: &id017
      status: none
    slug: bitstamp
    status: profiled
    tags: &id018
    - Bitcoin
    - Cryptocurrency
    - Exchange
    - Trading
    url: /providers/bitstamp/
  layer: domain
  name: Bitstamp
  provider: bitstamp
  says: ships the Bitstamp SDK or integration code
  source: https://github.com/rotki/rotki/tree/develop/rotkehlchen/exchanges
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
    mcp: &id019
      source: https://github.com/blockscout/mcp-server
      status: verified
    slug: blockscout
    status: profiled
    tags: &id020
    - Blockscout
    - Explorer
    - Open Source
    - Web3
    url: /providers/blockscout/
  layer: domain
  name: Blockscout
  provider: blockscout
  says: ships the Blockscout SDK or integration code
  source: https://github.com/rotki/rotki/tree/develop/rotkehlchen/externalapis
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
    mcp: &id021
      source: https://github.com/bybit-exchange/trading-mcp
      status: verified
    slug: bybit
    status: profiled
    tags: &id022
    - Cryptocurrency
    - Public APIs
    - Real-Time
    url: /providers/bybit/
  layer: domain
  name: Bybit
  provider: bybit
  says: ships the Bybit SDK or integration code
  source: https://github.com/rotki/rotki/tree/develop/rotkehlchen/exchanges
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
    agent_readiness: 50.8
    band: strong
    in_catalog: true
    kin_score: 57.2
    mcp: &id023
      source: https://github.com/coinbase/payments-mcp
      status: verified
    slug: coinbase
    status: profiled
    tags: &id024
    - Blockchain
    - Cryptocurrency
    - Custody
    - Exchange
    url: /providers/coinbase/
  layer: domain
  name: Coinbase
  provider: coinbase
  says: ships the Coinbase SDK or integration code
  source: https://github.com/rotki/rotki/tree/develop/rotkehlchen/exchanges
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
    mcp: &id025
      source: https://github.com/coinexcom/coinex_mcp_server
      status: verified
    slug: coinex
    status: profiled
    tags: &id026
    - Cryptocurrency
    - Exchange
    - Futures
    - Spot Trading
    url: /providers/coinex/
  layer: domain
  name: CoinEx
  provider: coinex
  says: ships the CoinEx SDK or integration code
  source: https://github.com/rotki/rotki/tree/develop/rotkehlchen/exchanges
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
    mcp: &id027
      source: https://docs.coingecko.com/reference/mcp-server
      status: verified
    slug: coingecko
    status: profiled
    tags: &id028
    - Aggregator
    - Blockchain
    - CoinGecko
    - Cryptocurrency
    url: /providers/coingecko/
  layer: domain
  name: CoinGecko
  provider: coingecko
  says: ships the CoinGecko SDK or integration code
  source: https://github.com/rotki/rotki/tree/develop/rotkehlchen/externalapis
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
    agent_readiness: 32.3
    band: thin
    in_catalog: true
    kin_score: 38.3
    mcp: &id029
      status: none
    slug: cow-protocol
    status: profiled
    tags: &id030
    - DeFi
    - Ethereum
    - Liquidity
    - Swap
    url: /providers/cow-protocol/
  layer: domain
  name: CoW Swap
  provider: cow-protocol
  says: ships the CoW Swap SDK or integration code
  source: https://github.com/rotki/rotki/tree/develop/rotkehlchen/externalapis
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
    mcp: &id031
      source: https://mcp.crypto.com/docs
      status: verified
    slug: crypto-com
    status: profiled
    tags: &id032
    - Cryptocurrency
    - Cryptocurrency Exchange
    - Derivatives
    - Trading
    url: /providers/crypto-com/
  layer: domain
  name: Crypto.com
  provider: crypto-com
  says: ships the Crypto.com SDK or integration code
  source: https://github.com/rotki/rotki/tree/develop/rotkehlchen/exchanges
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
    agent_readiness: 55.1
    band: developing
    in_catalog: true
    kin_score: 44.2
    mcp: &id033
      status: none
    slug: cryptocompare
    status: profiled
    tags: &id034
    - Cryptocurrency
    - Market Data
    - News
    - Reference Rates
    url: /providers/cryptocompare/
  layer: domain
  name: CryptoCompare
  provider: cryptocompare
  says: ships the CryptoCompare SDK or integration code
  source: https://github.com/rotki/rotki/tree/develop/rotkehlchen/externalapis
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-240.30.20
    key: AE-240.30.20
    name: Blockchain Analytics
    url: /capabilities/on-chain-data-indexing/
    via_parent: On-Chain Data & Indexing
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 47.6
    band: thin
    in_catalog: true
    kin_score: 29.1
    mcp: &id035
      status: none
    slug: defillama
    status: profiled
    tags: &id036
    - Cryptocurrency
    - DeFi
    - TVL
    - Web3
    url: /providers/defillama/
  layer: domain
  name: DefiLlama
  provider: defillama
  says: ships the DefiLlama SDK or integration code
  source: https://github.com/rotki/rotki/tree/develop/rotkehlchen/externalapis
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
    mcp: &id037
      source: https://docs.etherscan.io/mcp
      status: verified
    slug: etherscan
    status: profiled
    tags: &id038
    - Blockchain
    - Cryptocurrency
    - EVM
    - Ethereum
    url: /providers/etherscan/
  layer: domain
  name: Etherscan
  provider: etherscan
  says: ships the Etherscan SDK or integration code
  source: https://github.com/rotki/rotki/tree/develop/rotkehlchen/externalapis
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
    mcp: &id039
      source: https://github.com/gate/gate-mcp
      status: verified
    slug: gate-io
    status: profiled
    tags: &id040
    - Cryptocurrency
    - Exchange
    - Spot Trading
    - Trading
    url: /providers/gate-io/
  layer: domain
  name: Gate.io
  provider: gate-io
  says: ships the Gate.io SDK or integration code
  source: https://github.com/rotki/rotki/tree/develop/rotkehlchen/exchanges
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
    agent_readiness: 48.5
    band: exemplar
    in_catalog: true
    kin_score: 68.6
    mcp: &id041
      status: none
    slug: gemini-trust
    status: profiled
    tags: &id042
    - Company
    - Cryptocurrency
    - Exchange
    - Trading
    url: /providers/gemini-trust/
  layer: domain
  name: Gemini
  provider: gemini-trust
  says: ships the Gemini SDK or integration code
  source: https://github.com/rotki/rotki/tree/develop/rotkehlchen/exchanges
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-240.70
    key: AE-240.70
    name: Stablecoin Payments
    url: /capabilities/stablecoin-payments/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 34.8
    band: developing
    in_catalog: true
    kin_score: 43.5
    mcp: &id043
      status: none
    slug: gnosis-pay
    status: profiled
    tags: &id044
    - Company
    - Cryptocurrency
    - Payments
    - Stablecoins
    url: /providers/gnosis-pay/
  layer: domain
  name: Gnosis Pay
  provider: gnosis-pay
  says: ships the Gnosis Pay SDK or integration code
  source: https://github.com/rotki/rotki/tree/develop/rotkehlchen/externalapis
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.80
    key: AE-150.80
    name: Mailbox & Calendar Sync
    url: /capabilities/mailbox-calendar-sync/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 44.1
    band: strong
    in_catalog: true
    kin_score: 64.6
    mcp: &id045
      source: https://github.com/google/mcp
      status: verified
    slug: google-calendar
    status: profiled
    tags: &id046
    - Availability
    - Calendar
    - Event
    - Google
    url: /providers/google-calendar/
  layer: domain
  name: Google Calendar
  provider: google-calendar
  says: ships the Google Calendar SDK or integration code
  source: https://github.com/rotki/rotki/tree/develop/rotkehlchen/externalapis
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
    agent_readiness: 33.6
    band: thin
    in_catalog: true
    kin_score: 34.0
    mcp: &id047
      source: https://www.helius.dev/docs/agents/mcp
      status: verified
    slug: helius
    status: profiled
    tags: &id048
    - Blockchain
    - RPC
    - Solana
    - Web3
    url: /providers/helius/
  layer: domain
  name: Helius
  provider: helius
  says: ships the Helius SDK or integration code
  source: https://github.com/rotki/rotki/tree/develop/rotkehlchen/externalapis
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
    mcp: &id049
      status: none
    slug: htx
    status: profiled
    tags: &id050
    - Company
    - Cryptocurrency
    - Cryptocurrency Exchange
    - Technology
    url: /providers/htx/
  layer: domain
  name: HTX
  provider: htx
  says: ships the HTX SDK or integration code
  source: https://github.com/rotki/rotki/tree/develop/rotkehlchen/exchanges
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
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 22.4
    mcp: &id051
      status: unknown
    slug: iconomi
    status: profiled
    tags: &id052
    - Asset Management
    - Cryptocurrency
    - Investment
    - Platform
    url: /providers/iconomi/
  layer: domain
  name: ICONOMI
  provider: iconomi
  says: ships the ICONOMI SDK or integration code
  source: https://github.com/rotki/rotki/tree/develop/rotkehlchen/exchanges
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
    agent_readiness: 24.4
    band: developing
    in_catalog: true
    kin_score: 40.9
    mcp: &id053
      status: none
    slug: independent-reserve
    status: profiled
    tags: &id054
    - Company
    - Cryptocurrency
    - Exchange
    - Trading
    url: /providers/independent-reserve/
  layer: domain
  name: Independent Reserve
  provider: independent-reserve
  says: ships the Independent Reserve SDK or integration code
  source: https://github.com/rotki/rotki/tree/develop/rotkehlchen/exchanges
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
    mcp: &id055
      source: https://developers.jup.ag/docs/ai/trading-mcp
      status: documented
    slug: jupiter-ag
    status: profiled
    tags: &id056
    - DEX Aggregator
    - DeFi
    - Solana
    - Swap
    url: /providers/jupiter-ag/
  layer: domain
  name: Jupiter
  provider: jupiter-ag
  says: ships the Jupiter SDK or integration code
  source: https://github.com/rotki/rotki/tree/develop/rotkehlchen/externalapis
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
    mcp: &id057
      source: https://github.com/krakenfx/kraken-cli
      status: verified
    slug: kraken
    status: profiled
    tags: &id058
    - Cryptocurrency
    - Exchange
    - Kraken
    - Trading
    url: /providers/kraken/
  layer: domain
  name: Kraken
  provider: kraken
  says: ships the Kraken SDK or integration code
  source: https://github.com/rotki/rotki/tree/develop/rotkehlchen/exchanges
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
    mcp: &id059
      status: none
    slug: kucoin
    status: profiled
    tags: &id060
    - Cryptocurrency
    - Public APIs
    - Real-Time
    url: /providers/kucoin/
  layer: domain
  name: KuCoin
  provider: kucoin
  says: ships the KuCoin SDK or integration code
  source: https://github.com/rotki/rotki/tree/develop/rotkehlchen/exchanges
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-240.70.10
    key: AE-240.70.10
    name: Stablecoin Issuance
    url: /capabilities/stablecoin-payments/
    via_parent: Stablecoin Payments
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.3
    band: developing
    in_catalog: true
    kin_score: 42.7
    mcp: &id061
      status: none
    slug: monerium
    status: profiled
    tags: &id062
    - Blockchain
    - Digital Currency
    - Fintech
    - Payments
    url: /providers/monerium/
  layer: domain
  name: Monerium
  provider: monerium
  says: ships the Monerium SDK or integration code
  source: https://github.com/rotki/rotki/tree/develop/rotkehlchen/externalapis
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
    agent_readiness: 23.0
    band: thin
    in_catalog: true
    kin_score: 29.0
    mcp: &id063
      source: https://api.github.com/orgs/MoralisWeb3/repos
      status: verified
    slug: moralis
    status: profiled
    tags: &id064
    - Blockchain
    - Data API
    - Streams
    - Web3
    url: /providers/moralis/
  layer: domain
  name: Moralis
  provider: moralis
  says: ships the Moralis SDK or integration code
  source: https://github.com/rotki/rotki/tree/develop/rotkehlchen/externalapis
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
    mcp: &id065
      source: https://github.com/okx/agent-trade-kit
      status: verified
    slug: okx
    status: profiled
    tags: &id066
    - Cryptocurrency
    - Derivatives
    - Exchange
    - Trading
    url: /providers/okx/
  layer: domain
  name: OKX
  provider: okx
  says: ships the OKX SDK or integration code
  source: https://github.com/rotki/rotki/tree/develop/rotkehlchen/exchanges
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-240.50.20
    key: AE-240.50.20
    name: NFTs & Digital Collectibles
    url: /capabilities/token-issuance-smart-contracts/
    via_parent: Token Issuance & Smart Contracts
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 37.5
    band: developing
    in_catalog: true
    kin_score: 43.0
    mcp: &id067
      source: https://docs.opensea.io/docs/mcp
      status: verified
    slug: opensea
    status: profiled
    tags: &id068
    - Blockchain
    - Marketplace
    - NFT
    - Web3
    url: /providers/opensea/
  layer: domain
  name: OpenSea
  provider: opensea
  says: ships the OpenSea SDK or integration code
  source: https://github.com/rotki/rotki/tree/develop/rotkehlchen/externalapis
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
    kin_score: 15.4
    mcp: &id069
      status: none
    slug: poloniex
    status: profiled
    tags: &id070
    - Cryptocurrency
    - Public APIs
    - Real-Time
    url: /providers/poloniex/
  layer: domain
  name: Poloniex
  provider: poloniex
  says: ships the Poloniex SDK or integration code
  source: https://github.com/rotki/rotki/tree/develop/rotkehlchen/exchanges
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
    agent_band: human-only
    agent_readiness: 4.2
    band: emerging
    in_catalog: true
    kin_score: 20.4
    mcp: &id071
      status: none
    slug: routescan
    status: profiled
    tags: &id072
    - Company
    url: /providers/routescan/
  layer: domain
  name: Routescan
  provider: routescan
  says: ships the Routescan SDK or integration code
  source: https://github.com/rotki/rotki/tree/develop/rotkehlchen/externalapis
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
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id073
      status: unchecked
    slug: sochain
    status: queued for profiling
    tags: &id074 []
    url: null
  layer: domain
  name: SoChain
  provider: sochain
  says: ships the SoChain SDK or integration code
  source: https://github.com/rotki/rotki/tree/develop/rotkehlchen/externalapis
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
    agent_readiness: 19.2
    band: thin
    in_catalog: true
    kin_score: 27.8
    mcp: &id075
      source: https://github.com/graphprotocol/mcp-monorepo
      status: verified
    slug: the-graph
    status: profiled
    tags: &id076
    - GraphQL
    - Indexing
    - Subgraph
    - Web3
    url: /providers/the-graph/
  layer: domain
  name: The Graph
  provider: the-graph
  says: ships the The Graph SDK or integration code
  source: https://github.com/rotki/rotki/tree/develop/rotkehlchen/externalapis
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
    agent_readiness: 35.7
    band: developing
    in_catalog: true
    kin_score: 49.0
    mcp: &id077
      status: none
    slug: woox
    status: profiled
    tags: &id078
    - Company
    - Cryptocurrency
    - Exchange
    - Trading
    url: /providers/woox/
  layer: domain
  name: WOO X
  provider: woox
  says: ships the WOO X SDK or integration code
  source: https://github.com/rotki/rotki/tree/develop/rotkehlchen/exchanges
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
    kin_score: 8.9
    mcp: &id079
      status: unknown
    slug: xrates
    status: profiled
    tags: &id080
    - Company
    - Currency
    - Exchange Rates
    - Finance
    url: /providers/xrates/
  layer: domain
  name: X-Rates
  provider: xrates
  says: ships the X-Rates SDK or integration code
  source: https://github.com/rotki/rotki/tree/develop/rotkehlchen/externalapis
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/investing-trading/rotki/
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
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 0.4
  mcp: *id003
  name: beaconcha.in
  slug: beaconcha-in
  status: profiled
  tags: *id004
  url: /providers/beaconcha-in/
- agent_band: agent-ready
  agent_readiness: 29.9
  band: thin
  in_catalog: true
  kin_score: 38.9
  mcp: *id005
  name: Binance
  slug: binance
  status: profiled
  tags: *id006
  url: /providers/binance/
- agent_band: agent-aware
  agent_readiness: 26.7
  band: thin
  in_catalog: true
  kin_score: 33.8
  mcp: *id007
  name: Birdeye (Solana data)
  slug: birdeye-so
  status: profiled
  tags: *id008
  url: /providers/birdeye-so/
- agent_band: agent-ready
  agent_readiness: 52.6
  band: strong
  in_catalog: true
  kin_score: 61.9
  mcp: *id009
  name: Bit2Me
  slug: bit2me
  status: profiled
  tags: *id010
  url: /providers/bit2me/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 19.7
  mcp: *id011
  name: Bitcoin.de
  slug: bitcoin-de
  status: profiled
  tags: *id012
  url: /providers/bitcoin-de/
- agent_band: agent-aware
  agent_readiness: 13.7
  band: emerging
  in_catalog: true
  kin_score: 17.3
  mcp: *id013
  name: Bitfinex
  slug: bitfinex
  status: profiled
  tags: *id014
  url: /providers/bitfinex/
- agent_band: agent-aware
  agent_readiness: 27.7
  band: developing
  in_catalog: true
  kin_score: 46.0
  mcp: *id015
  name: Bitpanda
  slug: bitpanda
  status: profiled
  tags: *id016
  url: /providers/bitpanda/
- agent_band: agent-ready
  agent_readiness: 29.4
  band: thin
  in_catalog: true
  kin_score: 33.5
  mcp: *id017
  name: Bitstamp
  slug: bitstamp
  status: profiled
  tags: *id018
  url: /providers/bitstamp/
- agent_band: agent-ready
  agent_readiness: 33.4
  band: thin
  in_catalog: true
  kin_score: 26.2
  mcp: *id019
  name: Blockscout
  slug: blockscout
  status: profiled
  tags: *id020
  url: /providers/blockscout/
- agent_band: agent-aware
  agent_readiness: 13.7
  band: emerging
  in_catalog: true
  kin_score: 15.0
  mcp: *id021
  name: Bybit
  slug: bybit
  status: profiled
  tags: *id022
  url: /providers/bybit/
- agent_band: agent-native
  agent_readiness: 50.8
  band: strong
  in_catalog: true
  kin_score: 57.2
  mcp: *id023
  name: Coinbase
  slug: coinbase
  status: profiled
  tags: *id024
  url: /providers/coinbase/
- agent_band: human-only
  agent_readiness: 4.9
  band: emerging
  in_catalog: true
  kin_score: 24.2
  mcp: *id025
  name: CoinEx
  slug: coinex
  status: profiled
  tags: *id026
  url: /providers/coinex/
- agent_band: agent-ready
  agent_readiness: 47.4
  band: developing
  in_catalog: true
  kin_score: 52.4
  mcp: *id027
  name: CoinGecko
  slug: coingecko
  status: profiled
  tags: *id028
  url: /providers/coingecko/
- agent_band: agent-ready
  agent_readiness: 32.3
  band: thin
  in_catalog: true
  kin_score: 38.3
  mcp: *id029
  name: CoW Swap
  slug: cow-protocol
  status: profiled
  tags: *id030
  url: /providers/cow-protocol/
- agent_band: agent-native
  agent_readiness: 45.3
  band: strong
  in_catalog: true
  kin_score: 66.0
  mcp: *id031
  name: Crypto.com
  slug: crypto-com
  status: profiled
  tags: *id032
  url: /providers/crypto-com/
- agent_band: agent-ready
  agent_readiness: 55.1
  band: developing
  in_catalog: true
  kin_score: 44.2
  mcp: *id033
  name: CryptoCompare
  slug: cryptocompare
  status: profiled
  tags: *id034
  url: /providers/cryptocompare/
- agent_band: agent-ready
  agent_readiness: 47.6
  band: thin
  in_catalog: true
  kin_score: 29.1
  mcp: *id035
  name: DefiLlama
  slug: defillama
  status: profiled
  tags: *id036
  url: /providers/defillama/
- agent_band: agent-ready
  agent_readiness: 30.0
  band: thin
  in_catalog: true
  kin_score: 36.5
  mcp: *id037
  name: Etherscan
  slug: etherscan
  status: profiled
  tags: *id038
  url: /providers/etherscan/
- agent_band: agent-aware
  agent_readiness: 13.3
  band: emerging
  in_catalog: true
  kin_score: 25.1
  mcp: *id039
  name: Gate.io
  slug: gate-io
  status: profiled
  tags: *id040
  url: /providers/gate-io/
- agent_band: agent-ready
  agent_readiness: 48.5
  band: exemplar
  in_catalog: true
  kin_score: 68.6
  mcp: *id041
  name: Gemini
  slug: gemini-trust
  status: profiled
  tags: *id042
  url: /providers/gemini-trust/
- agent_band: agent-ready
  agent_readiness: 34.8
  band: developing
  in_catalog: true
  kin_score: 43.5
  mcp: *id043
  name: Gnosis Pay
  slug: gnosis-pay
  status: profiled
  tags: *id044
  url: /providers/gnosis-pay/
- agent_band: agent-ready
  agent_readiness: 44.1
  band: strong
  in_catalog: true
  kin_score: 64.6
  mcp: *id045
  name: Google Calendar
  slug: google-calendar
  status: profiled
  tags: *id046
  url: /providers/google-calendar/
- agent_band: agent-ready
  agent_readiness: 33.6
  band: thin
  in_catalog: true
  kin_score: 34.0
  mcp: *id047
  name: Helius
  slug: helius
  status: profiled
  tags: *id048
  url: /providers/helius/
- agent_band: agent-aware
  agent_readiness: 21.5
  band: developing
  in_catalog: true
  kin_score: 44.5
  mcp: *id049
  name: HTX
  slug: htx
  status: profiled
  tags: *id050
  url: /providers/htx/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 22.4
  mcp: *id051
  name: ICONOMI
  slug: iconomi
  status: profiled
  tags: *id052
  url: /providers/iconomi/
- agent_band: agent-aware
  agent_readiness: 24.4
  band: developing
  in_catalog: true
  kin_score: 40.9
  mcp: *id053
  name: Independent Reserve
  slug: independent-reserve
  status: profiled
  tags: *id054
  url: /providers/independent-reserve/
- agent_band: agent-aware
  agent_readiness: 24.4
  band: thin
  in_catalog: true
  kin_score: 27.1
  mcp: *id055
  name: Jupiter
  slug: jupiter-ag
  status: profiled
  tags: *id056
  url: /providers/jupiter-ag/
- agent_band: agent-ready
  agent_readiness: 37.5
  band: strong
  in_catalog: true
  kin_score: 63.1
  mcp: *id057
  name: Kraken
  slug: kraken
  status: profiled
  tags: *id058
  url: /providers/kraken/
- agent_band: agent-aware
  agent_readiness: 13.7
  band: emerging
  in_catalog: true
  kin_score: 14.6
  mcp: *id059
  name: KuCoin
  slug: kucoin
  status: profiled
  tags: *id060
  url: /providers/kucoin/
- agent_band: agent-aware
  agent_readiness: 24.3
  band: developing
  in_catalog: true
  kin_score: 42.7
  mcp: *id061
  name: Monerium
  slug: monerium
  status: profiled
  tags: *id062
  url: /providers/monerium/
- agent_band: agent-aware
  agent_readiness: 23.0
  band: thin
  in_catalog: true
  kin_score: 29.0
  mcp: *id063
  name: Moralis
  slug: moralis
  status: profiled
  tags: *id064
  url: /providers/moralis/
- agent_band: agent-aware
  agent_readiness: 15.8
  band: thin
  in_catalog: true
  kin_score: 28.9
  mcp: *id065
  name: OKX
  slug: okx
  status: profiled
  tags: *id066
  url: /providers/okx/
- agent_band: agent-ready
  agent_readiness: 37.5
  band: developing
  in_catalog: true
  kin_score: 43.0
  mcp: *id067
  name: OpenSea
  slug: opensea
  status: profiled
  tags: *id068
  url: /providers/opensea/
- agent_band: agent-aware
  agent_readiness: 13.7
  band: emerging
  in_catalog: true
  kin_score: 15.4
  mcp: *id069
  name: Poloniex
  slug: poloniex
  status: profiled
  tags: *id070
  url: /providers/poloniex/
- agent_band: human-only
  agent_readiness: 4.2
  band: emerging
  in_catalog: true
  kin_score: 20.4
  mcp: *id071
  name: Routescan
  slug: routescan
  status: profiled
  tags: *id072
  url: /providers/routescan/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id073
  name: SoChain
  slug: sochain
  status: queued for profiling
  tags: *id074
  url: null
- agent_band: agent-aware
  agent_readiness: 19.2
  band: thin
  in_catalog: true
  kin_score: 27.8
  mcp: *id075
  name: The Graph
  slug: the-graph
  status: profiled
  tags: *id076
  url: /providers/the-graph/
- agent_band: agent-ready
  agent_readiness: 35.7
  band: developing
  in_catalog: true
  kin_score: 49.0
  mcp: *id077
  name: WOO X
  slug: woox
  status: profiled
  tags: *id078
  url: /providers/woox/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 8.9
  mcp: *id079
  name: X-Rates
  slug: xrates
  status: profiled
  tags: *id080
  url: /providers/xrates/
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
- name: Wealthfolio
  rows: 16
  url: /applications/investing-trading/wealthfolio/
sitemap: true
title: 'rotki: Investing & Trading reference app'
---
