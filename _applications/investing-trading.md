---
access: understanding
agent_layer:
- app: Ghostfolio
  finding: README documents ENABLE_FEATURE_MCP, an MCP endpoint exposing the portfolio to agents
  source: https://raw.githubusercontent.com/ghostfolio/ghostfolio/main/README.md
  tier: declared
- app: Wealthfolio
  finding: BYO-LLM assistant (Ollama, Groq, Gemini, Anthropic, OpenAI, OpenRouter) plus an agent-tools crate
  source: https://raw.githubusercontent.com/wealthfolio/wealthfolio/main/crates/ai/src/ai_providers.json
  tier: observed
- app: Kubera
  finding: connect ChatGPT, Claude, Grok or Perplexity to the account; they get the same portfolio view as the user
  source: https://www.kubera.com/security
  tier: declared
- app: Robinhood
  finding: privacy policy names login via a third-party AI agent
  source: https://robinhood.com/us/en/support/articles/privacy-policy/
  tier: declared
apps:
- anchor: ghostfolio
  counts:
    declared: 0
    observed: 13
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/ghostfolio/ghostfolio/main/package.json
  - route: source code
    url: https://github.com/ghostfolio/ghostfolio/tree/main/apps/api/src/services/data-provider
  - route: source code
    url: https://github.com/ghostfolio/ghostfolio/tree/main/apps/api/src/services/data-provider/data-enhancer
  - route: source code
    url: https://raw.githubusercontent.com/ghostfolio/ghostfolio/main/apps/api/src/services/data-provider/rapid-api/rapid-api.service.ts
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-230.20.20
      key: AE-230.20.20
      name: Securities Market Data
      url: /capabilities/market-financial-data/
      via_parent: Market & Financial Data
    credit: null
    layer: domain
    name: Alpha Vantage
    provider: alpha-vantage
    says: ships the Alpha Vantage SDK or integration code
    source: https://github.com/ghostfolio/ghostfolio/tree/main/apps/api/src/services/data-provider
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-230.20.20
      key: AE-230.20.20
      name: Securities Market Data
      url: /capabilities/market-financial-data/
      via_parent: Market & Financial Data
    credit: null
    layer: domain
    name: CoinGecko
    provider: coingecko
    says: ships the CoinGecko SDK or integration code
    source: https://github.com/ghostfolio/ghostfolio/tree/main/apps/api/src/services/data-provider
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-230.20.20
      key: AE-230.20.20
      name: Securities Market Data
      url: /capabilities/market-financial-data/
      via_parent: Market & Financial Data
    credit: null
    layer: domain
    name: EODHD (EOD Historical Data)
    provider: eodhd
    says: ships the EODHD (EOD Historical Data) SDK or integration code
    source: https://github.com/ghostfolio/ghostfolio/tree/main/apps/api/src/services/data-provider
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-230.20.20
      key: AE-230.20.20
      name: Securities Market Data
      url: /capabilities/market-financial-data/
      via_parent: Market & Financial Data
    credit: null
    layer: domain
    name: Financial Modeling Prep
    provider: financial-modeling-prep
    says: ships the Financial Modeling Prep SDK or integration code
    source: https://github.com/ghostfolio/ghostfolio/tree/main/apps/api/src/services/data-provider
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-230.20.20
      key: AE-230.20.20
      name: Securities Market Data
      url: /capabilities/market-financial-data/
      via_parent: Market & Financial Data
    credit: null
    layer: domain
    name: Google Sheets
    provider: google-sheets
    says: ships the Google Sheets SDK or integration code
    source: https://github.com/ghostfolio/ghostfolio/tree/main/apps/api/src/services/data-provider
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: common
    name: Google sign-in
    provider: google-identity-platform
    says: ships the Google sign-in SDK or integration code
    source: https://raw.githubusercontent.com/ghostfolio/ghostfolio/main/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-230.20
      key: AE-230.20
      name: Market & Financial Data
      url: /capabilities/market-financial-data/
      via_parent: null
    credit: null
    layer: domain
    name: OpenFIGI
    provider: openfigi
    says: ships the OpenFIGI SDK or integration code
    source: https://github.com/ghostfolio/ghostfolio/tree/main/apps/api/src/services/data-provider/data-enhancer
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.30
      key: AE-110.10.30
      name: Model Routing & Gateways
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: common
    name: OpenRouter
    provider: openrouter
    says: ships the OpenRouter SDK or integration code
    source: https://raw.githubusercontent.com/ghostfolio/ghostfolio/main/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-230.20
      key: AE-230.20
      name: Market & Financial Data
      url: /capabilities/market-financial-data/
      via_parent: null
    credit: null
    layer: domain
    name: RapidAPI (Fear & Greed Index)
    provider: rapidapi
    says: ships the RapidAPI (Fear & Greed Index) SDK or integration code
    source: https://raw.githubusercontent.com/ghostfolio/ghostfolio/main/apps/api/src/services/data-provider/rapid-api/rapid-api.service.ts
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: Stripe
    provider: stripe
    says: ships the Stripe SDK or integration code
    source: https://raw.githubusercontent.com/ghostfolio/ghostfolio/main/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-230.20.20
      key: AE-230.20.20
      name: Securities Market Data
      url: /capabilities/market-financial-data/
      via_parent: Market & Financial Data
    credit: null
    layer: domain
    name: Trackinsight
    provider: trackinsight
    says: ships the Trackinsight SDK or integration code
    source: https://github.com/ghostfolio/ghostfolio/tree/main/apps/api/src/services/data-provider/data-enhancer
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: common
    name: X (Twitter)
    provider: x
    says: ships the X (Twitter) SDK or integration code
    source: https://raw.githubusercontent.com/ghostfolio/ghostfolio/main/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-230.20.20
      key: AE-230.20.20
      name: Securities Market Data
      url: /capabilities/market-financial-data/
      via_parent: Market & Financial Data
    credit: null
    layer: domain
    name: Yahoo Finance
    provider: yahoo
    says: ships the Yahoo Finance SDK or integration code
    source: https://raw.githubusercontent.com/ghostfolio/ghostfolio/main/package.json
    tier: observed
  kind: open-source-saas
  name: Ghostfolio
  page: /applications/investing-trading/ghostfolio/
  slug: ghostfolio
  url: https://github.com/ghostfolio/ghostfolio
- anchor: wealthfolio
  counts:
    declared: 0
    observed: 16
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
    layer: domain
    name: Yahoo Finance
    provider: yahoo
    says: ships the Yahoo Finance SDK or integration code
    source: https://github.com/wealthfolio/wealthfolio/tree/main/crates/market-data/src/provider
    tier: observed
  kind: self-hosted
  name: Wealthfolio
  page: /applications/investing-trading/wealthfolio/
  slug: wealthfolio
  url: https://github.com/wealthfolio/wealthfolio
- anchor: portfolio-performance
  counts:
    declared: 0
    observed: 16
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
    layer: domain
    name: Yahoo Finance
    provider: yahoo
    says: ships the Yahoo Finance SDK or integration code
    source: https://github.com/portfolio-performance/portfolio/tree/master/name.abuchen.portfolio/src/name/abuchen/portfolio/online/impl
    tier: observed
  kind: self-hosted
  name: Portfolio Performance
  page: /applications/investing-trading/portfolio-performance/
  slug: portfolio-performance
  url: https://github.com/portfolio-performance/portfolio
- anchor: freqtrade
  counts:
    declared: 0
    observed: 21
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
    layer: common
    name: Telegram
    provider: telegram
    says: ships the Telegram SDK or integration code
    source: https://raw.githubusercontent.com/freqtrade/freqtrade/develop/requirements.txt
    tier: observed
  kind: self-hosted
  name: Freqtrade
  page: /applications/investing-trading/freqtrade/
  slug: freqtrade
  url: https://github.com/freqtrade/freqtrade
- anchor: rotki
  counts:
    declared: 0
    observed: 40
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
    layer: domain
    name: X-Rates
    provider: xrates
    says: ships the X-Rates SDK or integration code
    source: https://github.com/rotki/rotki/tree/develop/rotkehlchen/externalapis
    tier: observed
  kind: self-hosted
  name: rotki
  page: /applications/investing-trading/rotki/
  slug: rotki
  url: https://github.com/rotki/rotki
- anchor: kubera
  counts:
    declared: 12
    observed: 0
  evidence:
  - route: integrations page
    url: https://www.kubera.com/security
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-190.50
      key: AE-190.50
      name: Consumer Data Access
      url: /capabilities/consumer-data-access/
      via_parent: null
    credit: null
    layer: domain
    name: Akahu
    provider: akahu
    says: lists Akahu as an integration
    source: https://www.kubera.com/security
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-190.50
      key: AE-190.50
      name: Consumer Data Access
      url: /capabilities/consumer-data-access/
      via_parent: null
    credit: null
    layer: domain
    name: Akoya
    provider: akoya
    says: lists Akoya as an integration
    source: https://www.kubera.com/security
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-600.50
      key: it-infrastructure-management
      name: IT Infrastructure Management
      url: /capabilities/it-infrastructure-management/
      via_parent: null
    credit: null
    layer: common
    name: AWS
    provider: amazon-web-services
    says: lists AWS as an integration
    source: https://www.kubera.com/security
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: common
    name: Google sign-in
    provider: google-identity-platform
    says: lists Google sign-in as an integration
    source: https://www.kubera.com/security
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-190.50
      key: AE-190.50
      name: Consumer Data Access
      url: /capabilities/consumer-data-access/
      via_parent: null
    credit: null
    layer: domain
    name: Lean Technologies
    provider: lean-technologies
    says: lists Lean Technologies as an integration
    source: https://www.kubera.com/security
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-190.50
      key: AE-190.50
      name: Consumer Data Access
      url: /capabilities/consumer-data-access/
      via_parent: null
    credit: null
    layer: domain
    name: Mastercard (Finicity open banking)
    provider: mastercard
    says: lists Mastercard (Finicity open banking) as an integration
    source: https://www.kubera.com/security
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-190.50
      key: AE-190.50
      name: Consumer Data Access
      url: /capabilities/consumer-data-access/
      via_parent: null
    credit: null
    layer: domain
    name: MX
    provider: mx-technologies
    says: lists MX as an integration
    source: https://www.kubera.com/security
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-190.50
      key: AE-190.50
      name: Consumer Data Access
      url: /capabilities/consumer-data-access/
      via_parent: null
    credit: null
    layer: domain
    name: Plaid
    provider: plaid
    says: lists Plaid as an integration
    source: https://www.kubera.com/security
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-430.50
      key: customer-feedback-management
      name: Customer Feedback Management
      url: /capabilities/customer-feedback-management/
      via_parent: null
    credit: null
    layer: common
    name: REVIEWS.io
    provider: reviews-io
    says: lists REVIEWS.io as an integration
    source: https://www.kubera.com/security
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-190.50
      key: AE-190.50
      name: Consumer Data Access
      url: /capabilities/consumer-data-access/
      via_parent: null
    credit: null
    layer: domain
    name: Salt Edge
    provider: salt-edge
    says: lists Salt Edge as an integration
    source: https://www.kubera.com/security
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-190.30.10
      key: AE-190.30.10
      name: Brokerage APIs
      url: /capabilities/retail-investing/
      via_parent: Retail Investing
    credit: null
    layer: domain
    name: SnapTrade
    provider: snaptrade
    says: lists SnapTrade as an integration
    source: https://www.kubera.com/security
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-190.50
      key: AE-190.50
      name: Consumer Data Access
      url: /capabilities/consumer-data-access/
      via_parent: null
    credit: null
    layer: domain
    name: Yodlee
    provider: yodlee
    says: lists Yodlee as an integration
    source: https://www.kubera.com/security
    tier: declared
  kind: commercial
  name: Kubera
  page: /applications/investing-trading/kubera/
  slug: kubera
  url: https://www.kubera.com/
- anchor: robinhood
  counts:
    declared: 5
    observed: 5
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.robinhood.android/latest/
  - route: documentation
    url: https://robinhood.com/us/en/support/articles/privacy-policy/
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-902
      key: AE-902
      name: Mobile Attribution & Deep Linking
      url: /capabilities/mobile-attribution-deep-linking/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Adjust
    provider: adjust
    says: ships the Adjust SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.robinhood.android/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-902
      key: AE-902
      name: Mobile Attribution & Deep Linking
      url: /capabilities/mobile-attribution-deep-linking/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Branch
    provider: branch-io
    says: ships the Branch SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.robinhood.android/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Google Firebase Analytics / Crashlytics
    provider: firebase
    says: ships the Google Firebase Analytics / Crashlytics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.robinhood.android/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Sentry
    provider: sentry-system
    says: ships the Sentry SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.robinhood.android/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-902
      key: AE-902
      name: Mobile Attribution & Deep Linking
      url: /capabilities/mobile-attribution-deep-linking/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Singular
    provider: singular
    says: ships the Singular SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.robinhood.android/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: null
    layer: common
    name: Google Ads
    provider: google-ads
    says: lists Google Ads as an integration
    source: https://robinhood.com/us/en/support/articles/privacy-policy/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: common
    name: Google sign-in
    provider: google-identity-platform
    says: lists Google sign-in as an integration
    source: https://robinhood.com/us/en/support/articles/privacy-policy/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-160.30
      key: AE-160.30
      name: Identity Verification
      url: /capabilities/identity-verification/
      via_parent: null
    credit: null
    layer: common
    name: Persona
    provider: persona
    says: lists Persona as an integration
    source: https://robinhood.com/us/en/support/articles/privacy-policy/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-190.50
      key: AE-190.50
      name: Consumer Data Access
      url: /capabilities/consumer-data-access/
      via_parent: null
    credit: null
    layer: domain
    name: Plaid
    provider: plaid
    says: lists Plaid as an integration
    source: https://robinhood.com/us/en/support/articles/privacy-policy/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: common
    name: Sign in with Apple
    provider: apple
    says: lists Sign in with Apple as an integration
    source: https://robinhood.com/us/en/support/articles/privacy-policy/
    tier: declared
  kind: commercial
  name: Robinhood
  page: /applications/investing-trading/robinhood/
  slug: robinhood
  url: https://robinhood.com/
author: API Evangelist
candidates: []
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
html: public
id: investing-trading
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Finance
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Finance
  store: google-play
  url: https://play.google.com/store/apps/category/FINANCE
name: Investing & Trading
needs:
- capability:
    attribution: API Evangelist extension
    id: AE-230.20.20
    key: AE-230.20.20
    name: Securities Market Data
    url: /capabilities/market-financial-data/
    via_parent: Market & Financial Data
  fit: nearest
  layer: domain
  why: quotes, history, dividends and fundamentals are the core of every tracker
- capability:
    attribution: API Evangelist extension
    id: AE-230.20
    key: AE-230.20
    name: Market & Financial Data
    url: /capabilities/market-financial-data/
    via_parent: null
  fit: exact
  layer: domain
  why: identifiers, macro series, metals, sentiment
- capability:
    attribution: API Evangelist extension
    id: AE-230.20.10
    key: AE-230.20.10
    name: Exchange Rates
    url: /capabilities/market-financial-data/
    via_parent: Market & Financial Data
  fit: exact
  layer: domain
  why: multi-currency portfolios need fiat conversion
- capability:
    attribution: API Evangelist extension
    id: AE-190.30.20
    key: AE-190.30.20
    name: Crypto Exchanges & Wallets
    url: /capabilities/retail-investing/
    via_parent: Retail Investing
  fit: exact
  layer: domain
  why: exchange connectors for import (rotki) and execution (Freqtrade)
- capability:
    attribution: API Evangelist extension
    id: AE-190.30.10
    key: AE-190.30.10
    name: Brokerage APIs
    url: /capabilities/retail-investing/
    via_parent: Retail Investing
  fit: exact
  layer: domain
  why: read-only brokerage aggregation for holdings sync
- capability:
    attribution: API Evangelist extension
    id: AE-190.50
    key: AE-190.50
    name: Consumer Data Access
    url: /capabilities/consumer-data-access/
    via_parent: null
  fit: exact
  layer: domain
  why: bank and investment account aggregation
- capability:
    attribution: API Evangelist extension
    id: AE-240.30.10
    key: AE-240.30.10
    name: Blockchain Indexing
    url: /capabilities/on-chain-data-indexing/
    via_parent: On-Chain Data & Indexing
  fit: exact
  layer: domain
  why: onchain balances and transactions for self-custody holdings
- capability:
    attribution: API Evangelist extension
    id: AE-240.30.20
    key: AE-240.30.20
    name: Blockchain Analytics
    url: /capabilities/on-chain-data-indexing/
    via_parent: On-Chain Data & Indexing
  fit: exact
  layer: domain
  why: DeFi positions and TVL
- capability:
    attribution: API Evangelist extension
    id: AE-240.60.10
    key: AE-240.60.10
    name: Decentralized Exchanges
    url: /capabilities/defi-protocols/
    via_parent: DeFi Protocols
  fit: exact
  layer: domain
  why: DEX trade history import
- capability:
    attribution: API Evangelist extension
    id: AE-240.50.20
    key: AE-240.50.20
    name: NFTs & Digital Collectibles
    url: /capabilities/token-issuance-smart-contracts/
    via_parent: Token Issuance & Smart Contracts
  fit: exact
  layer: domain
  why: NFT holdings (nearest; no NFT node)
- capability:
    attribution: API Evangelist extension
    id: AE-240.70
    key: AE-240.70
    name: Stablecoin Payments
    url: /capabilities/stablecoin-payments/
    via_parent: null
  fit: nearest
  layer: domain
  why: onchain e-money and crypto cards (nearest)
- capability:
    attribution: API Evangelist extension
    id: AE-160.30
    key: AE-160.30
    name: Identity Verification
    url: /capabilities/identity-verification/
    via_parent: null
  fit: exact
  layer: common
  why: brokerage KYC
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  fit: exact
  layer: common
  why: premium subscriptions
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  fit: exact
  layer: common
  why: sign-in
- capability:
    attribution: API Evangelist extension
    id: AE-170.50
    key: AE-170.50
    name: Social Networks & Community
    url: /capabilities/social-networks-community/
    via_parent: null
  fit: exact
  layer: common
  why: social posting
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  fit: exact
  layer: common
  why: AI portfolio assistants
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.30
    key: AE-110.10.30
    name: Model Routing & Gateways
    url: /capabilities/model-inference/
    via_parent: Model Inference
  fit: exact
  layer: common
  why: BYO model routing
- capability:
    attribution: Turbo EA
    id: BC-600.50.20
    key: BC-600.50.20
    name: Storage Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: encrypted sync storage
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.20
    key: AE-150.20.20
    name: WhatsApp & OTT Messaging
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  fit: exact
  layer: common
  why: trade alerts and bot control
- capability:
    attribution: Turbo EA
    id: BC-850.10
    key: internal-communications-management
    name: Internal Communications Management
    url: /capabilities/internal-communications-management/
    via_parent: null
  fit: exact
  layer: common
  why: bot notifications to a channel
- capability:
    attribution: API Evangelist extension
    id: AE-150.80
    key: AE-150.80
    name: Mailbox & Calendar Sync
    url: /capabilities/mailbox-calendar-sync/
    via_parent: null
  fit: exact
  layer: common
  why: event reminders
- capability:
    attribution: Turbo EA
    id: BC-600.50
    key: it-infrastructure-management
    name: IT Infrastructure Management
    url: /capabilities/it-infrastructure-management/
    via_parent: null
  fit: exact
  layer: common
  why: hosting
- capability:
    attribution: Turbo EA
    id: BC-430.50
    key: customer-feedback-management
    name: Customer Feedback Management
    url: /capabilities/customer-feedback-management/
    via_parent: null
  fit: exact
  layer: common
  why: public reviews
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  fit: exact
  layer: common
  why: acquisition advertising
- capability:
    attribution: API Evangelist extension
    id: AE-902
    key: AE-902
    name: Mobile Attribution & Deep Linking
    url: /capabilities/mobile-attribution-deep-linking/
    via_parent: null
  fit: exact
  layer: common
  why: mobile attribution SDKs in the Android apps
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: exact
  layer: common
  why: app telemetry in the Android apps
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: common
  why: crash and error reporting in the Android apps
stack:
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-190.30.20
      key: AE-190.30.20
      name: Crypto Exchanges & Wallets
      url: /capabilities/retail-investing/
      via_parent: Retail Investing
    providers:
    - agent_band: agent-ready
      agent_readiness: 37.9
      apps:
      - Freqtrade
      - Portfolio Performance
      - rotki
      band: strong
      in_catalog: true
      kin_score: 64.3
      mcp:
        source: https://github.com/krakenfx/kraken-cli
        status: verified
      name: Kraken
      slug: kraken
      sources:
      - https://github.com/freqtrade/freqtrade/tree/develop/freqtrade/exchange
      - https://github.com/portfolio-performance/portfolio/tree/master/name.abuchen.portfolio/src/name/abuchen/portfolio/online/impl
      - https://github.com/rotki/rotki/tree/develop/rotkehlchen/exchanges
      status: profiled
      tags:
      - Cryptocurrency
      - Exchange
      - Kraken
      - Trading
      tier: observed
      url: /providers/kraken/
    - agent_band: agent-ready
      agent_readiness: 30.5
      apps:
      - Freqtrade
      - Portfolio Performance
      - rotki
      band: thin
      in_catalog: true
      kin_score: 39.1
      mcp:
        status: none
      name: Binance
      slug: binance
      sources:
      - https://github.com/freqtrade/freqtrade/tree/develop/freqtrade/exchange
      - https://github.com/portfolio-performance/portfolio/tree/master/name.abuchen.portfolio/src/name/abuchen/portfolio/online/impl
      - https://github.com/rotki/rotki/tree/develop/rotkehlchen/exchanges
      status: profiled
      tags:
      - Blockchain
      - Cryptocurrency
      - Exchange
      - Trading
      tier: observed
      url: /providers/binance/
    - agent_band: agent-native
      agent_readiness: 46.3
      apps:
      - Freqtrade
      - rotki
      band: exemplar
      in_catalog: true
      kin_score: 67.2
      mcp:
        source: https://mcp.crypto.com/docs
        status: verified
      name: Crypto.com
      slug: crypto-com
      sources:
      - https://github.com/freqtrade/freqtrade/tree/develop/freqtrade/exchange
      - https://github.com/rotki/rotki/tree/develop/rotkehlchen/exchanges
      status: profiled
      tags:
      - Cryptocurrency
      - Cryptocurrency Exchange
      - Derivatives
      - Trading
      tier: observed
      url: /providers/crypto-com/
    - agent_band: agent-aware
      agent_readiness: 26.0
      apps:
      - Freqtrade
      - rotki
      band: developing
      in_catalog: true
      kin_score: 47.5
      mcp:
        source: https://github.com/bitpanda-labs/bitpanda-mcp
        status: verified
      name: Bitpanda
      slug: bitpanda
      sources:
      - https://github.com/freqtrade/freqtrade/tree/develop/freqtrade/exchange
      - https://github.com/rotki/rotki/tree/develop/rotkehlchen/exchanges
      status: profiled
      tags:
      - Company
      - Cryptocurrency
      - Fintech
      - Trading
      tier: observed
      url: /providers/bitpanda/
    - agent_band: agent-aware
      agent_readiness: 21.9
      apps:
      - Freqtrade
      - rotki
      band: developing
      in_catalog: true
      kin_score: 44.3
      mcp:
        status: none
      name: HTX
      slug: htx
      sources:
      - https://github.com/freqtrade/freqtrade/tree/develop/freqtrade/exchange
      - https://github.com/rotki/rotki/tree/develop/rotkehlchen/exchanges
      status: profiled
      tags:
      - Company
      - Cryptocurrency
      - Cryptocurrency Exchange
      - Technology
      tier: observed
      url: /providers/htx/
    - agent_band: agent-aware
      agent_readiness: 16.1
      apps:
      - Freqtrade
      - rotki
      band: thin
      in_catalog: true
      kin_score: 30.3
      mcp:
        source: https://github.com/okx/agent-trade-kit
        status: verified
      name: OKX
      slug: okx
      sources:
      - https://github.com/freqtrade/freqtrade/tree/develop/freqtrade/exchange
      - https://github.com/rotki/rotki/tree/develop/rotkehlchen/exchanges
      status: profiled
      tags:
      - Cryptocurrency
      - Derivatives
      - Exchange
      - Trading
      tier: observed
      url: /providers/okx/
    - agent_band: agent-aware
      agent_readiness: 13.6
      apps:
      - Freqtrade
      - rotki
      band: thin
      in_catalog: true
      kin_score: 26.5
      mcp:
        source: https://github.com/gate/gate-mcp
        status: verified
      name: Gate.io
      slug: gate-io
      sources:
      - https://github.com/freqtrade/freqtrade/tree/develop/freqtrade/exchange
      - https://github.com/rotki/rotki/tree/develop/rotkehlchen/exchanges
      status: profiled
      tags:
      - Cryptocurrency
      - Exchange
      - Spot Trading
      - Trading
      tier: observed
      url: /providers/gate-io/
    - agent_band: human-only
      agent_readiness: 5.0
      apps:
      - Freqtrade
      - rotki
      band: emerging
      in_catalog: true
      kin_score: 22.3
      mcp:
        source: https://github.com/coinexcom/coinex_mcp_server
        status: verified
      name: CoinEx
      slug: coinex
      sources:
      - https://github.com/freqtrade/freqtrade/tree/develop/freqtrade/exchange
      - https://github.com/rotki/rotki/tree/develop/rotkehlchen/exchanges
      status: profiled
      tags:
      - Cryptocurrency
      - Exchange
      - Futures
      - Spot Trading
      tier: observed
      url: /providers/coinex/
    - agent_band: agent-aware
      agent_readiness: 14.0
      apps:
      - Portfolio Performance
      - rotki
      band: emerging
      in_catalog: true
      kin_score: 17.4
      mcp:
        status: none
      name: Bitfinex
      slug: bitfinex
      sources:
      - https://github.com/portfolio-performance/portfolio/tree/master/name.abuchen.portfolio/src/name/abuchen/portfolio/online/impl
      - https://github.com/rotki/rotki/tree/develop/rotkehlchen/exchanges
      status: profiled
      tags:
      - Cryptocurrency
      - Public APIs
      - Real-Time
      tier: observed
      url: /providers/bitfinex/
    - agent_band: agent-aware
      agent_readiness: 14.0
      apps:
      - Freqtrade
      - rotki
      band: emerging
      in_catalog: true
      kin_score: 15.5
      mcp:
        status: none
      name: KuCoin
      slug: kucoin
      sources:
      - https://github.com/freqtrade/freqtrade/tree/develop/freqtrade/exchange
      - https://github.com/rotki/rotki/tree/develop/rotkehlchen/exchanges
      status: profiled
      tags:
      - Cryptocurrency
      - Public APIs
      - Real-Time
      tier: observed
      url: /providers/kucoin/
    - agent_band: agent-aware
      agent_readiness: 14.0
      apps:
      - Freqtrade
      - rotki
      band: emerging
      in_catalog: true
      kin_score: 15.0
      mcp:
        source: https://github.com/bybit-exchange/trading-mcp
        status: verified
      name: Bybit
      slug: bybit
      sources:
      - https://github.com/freqtrade/freqtrade/tree/develop/freqtrade/exchange
      - https://github.com/rotki/rotki/tree/develop/rotkehlchen/exchanges
      status: profiled
      tags:
      - Cryptocurrency
      - Public APIs
      - Real-Time
      tier: observed
      url: /providers/bybit/
    - agent_band: agent-ready
      agent_readiness: 49.5
      apps:
      - rotki
      band: exemplar
      in_catalog: true
      kin_score: 69.2
      mcp:
        status: none
      name: Gemini
      slug: gemini-trust
      sources:
      - https://github.com/rotki/rotki/tree/develop/rotkehlchen/exchanges
      status: profiled
      tags:
      - Company
      - Cryptocurrency
      - Exchange
      - Trading
      tier: observed
      url: /providers/gemini-trust/
    - agent_band: agent-native
      agent_readiness: 51.5
      apps:
      - rotki
      band: strong
      in_catalog: true
      kin_score: 56.6
      mcp:
        source: https://github.com/coinbase/payments-mcp
        status: verified
      name: Coinbase
      slug: coinbase
      sources:
      - https://github.com/rotki/rotki/tree/develop/rotkehlchen/exchanges
      status: profiled
      tags:
      - Blockchain
      - Cryptocurrency
      - Custody
      - Exchange
      tier: observed
      url: /providers/coinbase/
    - agent_band: agent-aware
      agent_readiness: 26.3
      apps:
      - Freqtrade
      band: developing
      in_catalog: true
      kin_score: 49.9
      mcp:
        source: https://github.com/luno/luno-mcp
        status: verified
      name: Luno
      slug: luno
      sources:
      - https://github.com/freqtrade/freqtrade/tree/develop/freqtrade/exchange
      status: profiled
      tags:
      - Bitcoin
      - Company
      - Cryptocurrency
      - Exchange
      tier: observed
      url: /providers/luno/
    - agent_band: agent-ready
      agent_readiness: 55.4
      apps:
      - rotki
      band: developing
      in_catalog: true
      kin_score: 48.0
      mcp:
        source: https://api.bit2me.com/docs
        status: documented
      name: Bit2Me
      slug: bit2me
      sources:
      - https://github.com/rotki/rotki/tree/develop/rotkehlchen/exchanges
      status: profiled
      tags:
      - Company
      - Cryptocurrency
      - Exchange
      - Fintech
      tier: observed
      url: /providers/bit2me/
    - agent_band: agent-ready
      agent_readiness: 31.6
      apps:
      - Freqtrade
      band: developing
      in_catalog: true
      kin_score: 39.5
      mcp:
        status: none
      name: HitBTC
      slug: hitbtc
      sources:
      - https://github.com/freqtrade/freqtrade/tree/develop/freqtrade/exchange
      status: profiled
      tags:
      - Company
      - Cryptocurrency
      - Cryptocurrency Exchange
      - Trading
      tier: observed
      url: /providers/hitbtc/
    - agent_band: agent-ready
      agent_readiness: 35.9
      apps:
      - rotki
      band: developing
      in_catalog: true
      kin_score: 39.3
      mcp:
        status: none
      name: WOO X
      slug: woox
      sources:
      - https://github.com/rotki/rotki/tree/develop/rotkehlchen/exchanges
      status: profiled
      tags:
      - Company
      - Cryptocurrency
      - Exchange
      - Trading
      tier: observed
      url: /providers/woox/
    - agent_band: agent-aware
      agent_readiness: 21.3
      apps:
      - Portfolio Performance
      band: thin
      in_catalog: true
      kin_score: 33.0
      mcp:
        status: none
      name: MEXC
      slug: mexc
      sources:
      - https://github.com/portfolio-performance/portfolio/tree/master/name.abuchen.portfolio/src/name/abuchen/portfolio/online/impl
      status: profiled
      tags:
      - Cryptocurrency
      - Exchange
      - Futures
      - Trading
      tier: observed
      url: /providers/mexc/
    - agent_band: agent-aware
      agent_readiness: 23.0
      apps:
      - Freqtrade
      band: thin
      in_catalog: true
      kin_score: 32.8
      mcp:
        status: none
      name: LBank
      slug: lbank
      sources:
      - https://github.com/freqtrade/freqtrade/tree/develop/freqtrade/exchange
      status: profiled
      tags:
      - Cryptocurrency
      - Exchange
      - Market Data
      - Trading
      tier: observed
      url: /providers/lbank/
    - agent_band: agent-aware
      agent_readiness: 16.5
      apps:
      - Freqtrade
      band: thin
      in_catalog: true
      kin_score: 31.3
      mcp:
        status: none
      name: Hyperliquid
      slug: hyperliquid
      sources:
      - https://github.com/freqtrade/freqtrade/tree/develop/freqtrade/exchange
      status: profiled
      tags:
      - DeFi
      - Decentralized Exchange
      - Layer 1
      - Perpetuals
      tier: observed
      url: /providers/hyperliquid/
    - agent_band: agent-ready
      agent_readiness: 34.3
      apps:
      - Freqtrade
      band: thin
      in_catalog: true
      kin_score: 30.7
      mcp:
        status: none
      name: Bitvavo
      slug: bitvavo
      sources:
      - https://github.com/freqtrade/freqtrade/tree/develop/freqtrade/exchange
      status: profiled
      tags:
      - Company
      - Cryptocurrency
      - Exchange
      - Trading
      tier: observed
      url: /providers/bitvavo/
    - agent_band: agent-ready
      agent_readiness: 30.1
      apps:
      - rotki
      band: thin
      in_catalog: true
      kin_score: 30.3
      mcp:
        status: none
      name: Bitstamp
      slug: bitstamp
      sources:
      - https://github.com/rotki/rotki/tree/develop/rotkehlchen/exchanges
      status: profiled
      tags:
      - Bitcoin
      - Cryptocurrency
      - Exchange
      - Trading
      tier: observed
      url: /providers/bitstamp/
    - agent_band: agent-aware
      agent_readiness: 24.9
      apps:
      - rotki
      band: thin
      in_catalog: true
      kin_score: 27.2
      mcp:
        status: none
      name: Independent Reserve
      slug: independent-reserve
      sources:
      - https://github.com/rotki/rotki/tree/develop/rotkehlchen/exchanges
      status: profiled
      tags:
      - Company
      - Cryptocurrency
      - Exchange
      - Trading
      tier: observed
      url: /providers/independent-reserve/
    - agent_band: agent-aware
      agent_readiness: 15.5
      apps:
      - Freqtrade
      band: emerging
      in_catalog: true
      kin_score: 24.3
      mcp:
        source: https://github.com/Bitget-AI/agent-mcp
        status: verified
      name: Bitget
      slug: bitget
      sources:
      - https://github.com/freqtrade/freqtrade/tree/develop/freqtrade/exchange
      status: profiled
      tags:
      - Cryptocurrency
      - Exchange
      - Futures
      - Spot Trading
      tier: observed
      url: /providers/bitget/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - rotki
      band: emerging
      in_catalog: true
      kin_score: 18.6
      mcp:
        status: unknown
      name: ICONOMI
      slug: iconomi
      sources:
      - https://github.com/rotki/rotki/tree/develop/rotkehlchen/exchanges
      status: profiled
      tags:
      - Asset Management
      - Cryptocurrency
      - Investment
      - Platform
      tier: observed
      url: /providers/iconomi/
    - agent_band: agent-aware
      agent_readiness: 14.0
      apps:
      - rotki
      band: emerging
      in_catalog: true
      kin_score: 16.3
      mcp:
        status: none
      name: Poloniex
      slug: poloniex
      sources:
      - https://github.com/rotki/rotki/tree/develop/rotkehlchen/exchanges
      status: profiled
      tags:
      - Cryptocurrency
      - Public APIs
      - Real-Time
      tier: observed
      url: /providers/poloniex/
    - agent_band: agent-aware
      agent_readiness: 20.7
      apps:
      - Freqtrade
      band: emerging
      in_catalog: true
      kin_score: 15.9
      mcp:
        status: none
      name: BingX
      slug: bingx
      sources:
      - https://github.com/freqtrade/freqtrade/tree/develop/freqtrade/exchange
      status: profiled
      tags:
      - Company
      - Cryptocurrency
      - Exchange
      - Trading
      tier: observed
      url: /providers/bingx/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - rotki
      band: emerging
      in_catalog: true
      kin_score: 12.0
      mcp:
        status: unknown
      name: Bitcoin.de
      slug: bitcoin-de
      sources:
      - https://github.com/rotki/rotki/tree/develop/rotkehlchen/exchanges
      status: profiled
      tags:
      - Company
      tier: observed
      url: /providers/bitcoin-de/
    - agent_band: null
      agent_readiness: null
      apps:
      - Freqtrade
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: IDEX (exchange)
      slug: idex-io
      sources:
      - https://github.com/freqtrade/freqtrade/tree/develop/freqtrade/exchange
      status: queued for profiling
      tags: []
      tier: observed
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-230.20.20
      key: AE-230.20.20
      name: Securities Market Data
      url: /capabilities/market-financial-data/
      via_parent: Market & Financial Data
    providers:
    - agent_band: agent-ready
      agent_readiness: 51.4
      apps:
      - Ghostfolio
      - Portfolio Performance
      - Wealthfolio
      band: strong
      in_catalog: true
      kin_score: 54.4
      mcp:
        source: https://github.com/alphavantage/alpha_vantage_mcp
        status: verified
      name: Alpha Vantage
      slug: alpha-vantage
      sources:
      - https://github.com/ghostfolio/ghostfolio/tree/main/apps/api/src/services/data-provider
      - https://github.com/portfolio-performance/portfolio/tree/master/name.abuchen.portfolio/src/name/abuchen/portfolio/online/impl
      - https://github.com/wealthfolio/wealthfolio/tree/main/crates/market-data/src/provider
      status: profiled
      tags:
      - Fintech
      - Foreign Exchange
      - Market Data
      - Stocks
      tier: observed
      url: /providers/alpha-vantage/
    - agent_band: agent-ready
      agent_readiness: 46.2
      apps:
      - Ghostfolio
      - Portfolio Performance
      - rotki
      band: developing
      in_catalog: true
      kin_score: 52.0
      mcp: &id001
        source: https://docs.coingecko.com/reference/mcp-server
        status: verified
      name: CoinGecko
      slug: coingecko
      sources:
      - https://github.com/ghostfolio/ghostfolio/tree/main/apps/api/src/services/data-provider
      - https://github.com/portfolio-performance/portfolio/tree/master/name.abuchen.portfolio/src/name/abuchen/portfolio/online/impl
      - https://github.com/rotki/rotki/tree/develop/rotkehlchen/externalapis
      status: profiled
      tags: &id002
      - Aggregator
      - Blockchain
      - CoinGecko
      - Cryptocurrency
      tier: observed
      url: /providers/coingecko/
    - agent_band: agent-aware
      agent_readiness: 16.2
      apps:
      - Ghostfolio
      - Portfolio Performance
      - Wealthfolio
      band: developing
      in_catalog: true
      kin_score: 41.4
      mcp:
        status: none
      name: Yahoo Finance
      slug: yahoo
      sources:
      - https://github.com/portfolio-performance/portfolio/tree/master/name.abuchen.portfolio/src/name/abuchen/portfolio/online/impl
      - https://github.com/wealthfolio/wealthfolio/tree/main/crates/market-data/src/provider
      - https://raw.githubusercontent.com/ghostfolio/ghostfolio/main/package.json
      status: profiled
      tags:
      - Advertising
      - DSP
      - Fantasy Sports
      - Programmatic Advertising
      tier: observed
      url: /providers/yahoo/
    - agent_band: agent-ready
      agent_readiness: 58.3
      apps:
      - Ghostfolio
      - Portfolio Performance
      band: strong
      in_catalog: true
      kin_score: 62.2
      mcp:
        source: https://github.com/EodHistoricalData/EODHD-MCP-Server
        status: verified
      name: EODHD (EOD Historical Data)
      slug: eodhd
      sources:
      - https://github.com/ghostfolio/ghostfolio/tree/main/apps/api/src/services/data-provider
      - https://github.com/portfolio-performance/portfolio/tree/master/name.abuchen.portfolio/src/name/abuchen/portfolio/online/impl
      status: profiled
      tags:
      - Finance
      - Market Data
      - Stock Options
      - Stocks
      tier: observed
      url: /providers/eodhd/
    - agent_band: agent-aware
      agent_readiness: 23.6
      apps:
      - Portfolio Performance
      - Wealthfolio
      band: developing
      in_catalog: true
      kin_score: 43.9
      mcp:
        source: https://finnhub.io/docs/api
        status: documented
      name: Finnhub
      slug: finnhub
      sources:
      - https://github.com/portfolio-performance/portfolio/tree/master/name.abuchen.portfolio/src/name/abuchen/portfolio/online/impl
      - https://github.com/wealthfolio/wealthfolio/tree/main/crates/market-data/src/provider
      status: profiled
      tags:
      - Finance
      - Foreign Exchange
      - Market Data
      - Stocks
      tier: observed
      url: /providers/finnhub/
    - agent_band: agent-native
      agent_readiness: 41.2
      apps:
      - Ghostfolio
      band: exemplar
      in_catalog: true
      kin_score: 69.5
      mcp:
        status: none
      name: Financial Modeling Prep
      slug: financial-modeling-prep
      sources:
      - https://github.com/ghostfolio/ghostfolio/tree/main/apps/api/src/services/data-provider
      status: profiled
      tags:
      - Financial Data
      - Market Data
      - Quotes
      - Stocks
      tier: observed
      url: /providers/financial-modeling-prep/
    - agent_band: agent-ready
      agent_readiness: 58.9
      apps:
      - Portfolio Performance
      band: exemplar
      in_catalog: true
      kin_score: 68.2
      mcp:
        source: https://github.com/twelvedata/mcp
        status: verified
      name: Twelve Data
      slug: twelvedata
      sources:
      - https://github.com/portfolio-performance/portfolio/tree/master/name.abuchen.portfolio/src/name/abuchen/portfolio/online/impl
      status: profiled
      tags:
      - Financial Data
      - Foreign Exchange
      - Market Data
      - Stocks
      tier: observed
      url: /providers/twelvedata/
    - agent_band: agent-ready
      agent_readiness: 33.8
      apps:
      - Ghostfolio
      band: strong
      in_catalog: true
      kin_score: 64.5
      mcp:
        status: none
      name: Google Sheets
      slug: google-sheets
      sources:
      - https://github.com/ghostfolio/ghostfolio/tree/main/apps/api/src/services/data-provider
      status: profiled
      tags:
      - Google Workspace
      - Productivity
      - Spreadsheets
      tier: observed
      url: /providers/google-sheets/
    - agent_band: agent-ready
      agent_readiness: 29.8
      apps:
      - Wealthfolio
      band: strong
      in_catalog: true
      kin_score: 60.7
      mcp:
        status: none
      name: Market Data (marketdata.app)
      slug: marketdata-app
      sources:
      - https://github.com/wealthfolio/wealthfolio/tree/main/crates/market-data/src/provider
      status: profiled
      tags:
      - Financial Data
      - Market Data
      - Options
      - Stocks
      tier: observed
      url: /providers/marketdata-app/
    - agent_band: agent-aware
      agent_readiness: 23.0
      apps:
      - Wealthfolio
      band: developing
      in_catalog: true
      kin_score: 51.1
      mcp:
        status: none
      name: Boerse Frankfurt (Deutsche Boerse)
      slug: deutsche-boerse
      sources:
      - https://raw.githubusercontent.com/wealthfolio/wealthfolio/main/crates/market-data/src/provider/boerse_frankfurt/mod.rs
      status: profiled
      tags:
      - Derivatives
      - Finance
      - Market Data
      - Stocks
      tier: observed
      url: /providers/deutsche-boerse/
    - agent_band: agent-ready
      agent_readiness: 56.3
      apps:
      - rotki
      band: developing
      in_catalog: true
      kin_score: 46.2
      mcp:
        status: none
      name: CryptoCompare
      slug: cryptocompare
      sources:
      - https://github.com/rotki/rotki/tree/develop/rotkehlchen/externalapis
      status: profiled
      tags:
      - Cryptocurrency
      - Market Data
      - News
      - Reference Rates
      tier: observed
      url: /providers/cryptocompare/
    - agent_band: agent-aware
      agent_readiness: 27.6
      apps:
      - Portfolio Performance
      band: thin
      in_catalog: true
      kin_score: 34.4
      mcp:
        status: none
      name: Nasdaq Data Link (Quandl)
      slug: nasdaq-data-link
      sources:
      - https://github.com/portfolio-performance/portfolio/tree/master/name.abuchen.portfolio/src/name/abuchen/portfolio/online/impl
      status: profiled
      tags:
      - Economic Data
      - Financial Data
      - Market Data
      - Stock Market
      tier: observed
      url: /providers/nasdaq-data-link/
    - agent_band: agent-ready
      agent_readiness: 29.6
      apps:
      - rotki
      band: emerging
      in_catalog: true
      kin_score: 25.3
      mcp:
        status: none
      name: Birdeye (Solana data)
      slug: birdeye-so
      sources:
      - https://github.com/rotki/rotki/tree/develop/rotkehlchen/externalapis
      status: profiled
      tags:
      - Analytics
      - Blockchain
      - Company
      - Data
      tier: observed
      url: /providers/birdeye-so/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Portfolio Performance
      band: emerging
      in_catalog: true
      kin_score: 15.8
      mcp:
        status: none
      name: DivvyDiary
      slug: divvydiary
      sources:
      - https://github.com/portfolio-performance/portfolio/tree/master/name.abuchen.portfolio/src/name/abuchen/portfolio/online/impl
      status: profiled
      tags:
      - Company
      - Dividend
      - Finance
      - Investment
      tier: observed
      url: /providers/divvydiary/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Portfolio Performance
      band: minimal
      in_catalog: true
      kin_score: 6.7
      mcp:
        status: unknown
      name: AMFI India
      slug: amfi-india
      sources:
      - https://github.com/portfolio-performance/portfolio/tree/master/name.abuchen.portfolio/src/name/abuchen/portfolio/online/impl
      status: profiled
      tags:
      - Company
      - Finance
      - India
      - Mutual Funds
      tier: observed
      url: /providers/amfi-india/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Ghostfolio
      band: minimal
      in_catalog: true
      kin_score: 2.0
      mcp:
        status: none
      name: Trackinsight
      slug: trackinsight
      sources:
      - https://github.com/ghostfolio/ghostfolio/tree/main/apps/api/src/services/data-provider/data-enhancer
      status: profiled
      tags:
      - Company
      tier: observed
      url: /providers/trackinsight/
    - agent_band: null
      agent_readiness: null
      apps:
      - Portfolio Performance
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Leeway
      slug: leeway
      sources:
      - https://github.com/portfolio-performance/portfolio/tree/master/name.abuchen.portfolio/src/name/abuchen/portfolio/online/impl
      status: queued for profiling
      tags: []
      tier: observed
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-240.30.10
      key: AE-240.30.10
      name: Blockchain Indexing
      url: /capabilities/on-chain-data-indexing/
      via_parent: On-Chain Data & Indexing
    providers:
    - agent_band: agent-ready
      agent_readiness: 30.7
      apps:
      - rotki
      band: thin
      in_catalog: true
      kin_score: 38.1
      mcp:
        source: https://docs.etherscan.io/mcp
        status: verified
      name: Etherscan
      slug: etherscan
      sources:
      - https://github.com/rotki/rotki/tree/develop/rotkehlchen/externalapis
      status: profiled
      tags:
      - Blockchain
      - Cryptocurrency
      - EVM
      - Ethereum
      tier: observed
      url: /providers/etherscan/
    - agent_band: agent-ready
      agent_readiness: 32.8
      apps:
      - rotki
      band: thin
      in_catalog: true
      kin_score: 33.5
      mcp:
        source: https://www.helius.dev/docs/agents/mcp
        status: verified
      name: Helius
      slug: helius
      sources:
      - https://github.com/rotki/rotki/tree/develop/rotkehlchen/externalapis
      status: profiled
      tags:
      - Blockchain
      - RPC
      - Solana
      - Web3
      tier: observed
      url: /providers/helius/
    - agent_band: agent-ready
      agent_readiness: 43.2
      apps:
      - rotki
      band: thin
      in_catalog: true
      kin_score: 32.4
      mcp:
        source: https://github.com/alchemyplatform/alchemy-mcp-server
        status: verified
      name: Alchemy
      slug: alchemy
      sources:
      - https://github.com/rotki/rotki/tree/develop/rotkehlchen/externalapis
      status: profiled
      tags:
      - Blockchain
      - NFT
      - RPC
      - Web3
      tier: observed
      url: /providers/alchemy/
    - agent_band: agent-aware
      agent_readiness: 23.0
      apps:
      - rotki
      band: thin
      in_catalog: true
      kin_score: 29.4
      mcp:
        source: https://api.github.com/orgs/MoralisWeb3/repos
        status: verified
      name: Moralis
      slug: moralis
      sources:
      - https://github.com/rotki/rotki/tree/develop/rotkehlchen/externalapis
      status: profiled
      tags:
      - Blockchain
      - Data API
      - Streams
      - Web3
      tier: observed
      url: /providers/moralis/
    - agent_band: agent-aware
      agent_readiness: 19.6
      apps:
      - rotki
      band: thin
      in_catalog: true
      kin_score: 28.3
      mcp:
        source: https://github.com/graphprotocol/mcp-monorepo
        status: verified
      name: The Graph
      slug: the-graph
      sources:
      - https://github.com/rotki/rotki/tree/develop/rotkehlchen/externalapis
      status: profiled
      tags:
      - GraphQL
      - Indexing
      - Subgraph
      - Web3
      tier: observed
      url: /providers/the-graph/
    - agent_band: agent-ready
      agent_readiness: 33.6
      apps:
      - rotki
      band: thin
      in_catalog: true
      kin_score: 27.5
      mcp:
        source: https://github.com/blockscout/mcp-server
        status: verified
      name: Blockscout
      slug: blockscout
      sources:
      - https://github.com/rotki/rotki/tree/develop/rotkehlchen/externalapis
      status: profiled
      tags:
      - Blockscout
      - Explorer
      - Open Source
      - Web3
      tier: observed
      url: /providers/blockscout/
    - agent_band: agent-aware
      agent_readiness: 7.2
      apps:
      - rotki
      band: emerging
      in_catalog: true
      kin_score: 15.5
      mcp:
        status: none
      name: Routescan
      slug: routescan
      sources:
      - https://github.com/rotki/rotki/tree/develop/rotkehlchen/externalapis
      status: profiled
      tags:
      - Company
      tier: observed
      url: /providers/routescan/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - rotki
      band: minimal
      in_catalog: true
      kin_score: 1.3
      mcp:
        status: none
      name: beaconcha.in
      slug: beaconcha-in
      sources:
      - https://github.com/rotki/rotki/tree/develop/rotkehlchen/externalapis
      status: profiled
      tags:
      - Company
      tier: observed
      url: /providers/beaconcha-in/
    - agent_band: null
      agent_readiness: null
      apps:
      - rotki
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: SoChain
      slug: sochain
      sources:
      - https://github.com/rotki/rotki/tree/develop/rotkehlchen/externalapis
      status: queued for profiling
      tags: []
      tier: observed
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-190.50
      key: AE-190.50
      name: Consumer Data Access
      url: /capabilities/consumer-data-access/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 52.1
      apps:
      - Kubera
      - Robinhood
      band: exemplar
      in_catalog: true
      kin_score: 83.4
      mcp:
        source: https://plaid.com/docs/resources/mcp/
        status: verified
      name: Plaid
      slug: plaid
      sources:
      - https://robinhood.com/us/en/support/articles/privacy-policy/
      - https://www.kubera.com/security
      status: profiled
      tags:
      - Bank Accounts
      - Finance
      - Fintech
      - Open Banking
      tier: declared
      url: /providers/plaid/
    - agent_band: agent-aware
      agent_readiness: 26.7
      apps:
      - Kubera
      band: strong
      in_catalog: true
      kin_score: 65.0
      mcp:
        status: none
      name: MX
      slug: mx-technologies
      sources:
      - https://www.kubera.com/security
      status: profiled
      tags:
      - Account Aggregation
      - Data Connectivity
      - Financial Data
      - Open Banking
      tier: declared
      url: /providers/mx-technologies/
    - agent_band: agent-native
      agent_readiness: 44.2
      apps:
      - Kubera
      band: strong
      in_catalog: true
      kin_score: 57.3
      mcp:
        source: https://github.com/Mastercard/developers-agent-toolkit
        status: verified
      name: Mastercard (Finicity open banking)
      slug: mastercard
      sources:
      - https://www.kubera.com/security
      status: profiled
      tags:
      - Credit Cards
      - Digital Identity
      - Financial Services
      - Mastercard
      tier: declared
      url: /providers/mastercard/
    - agent_band: agent-aware
      agent_readiness: 21.1
      apps:
      - Kubera
      band: developing
      in_catalog: true
      kin_score: 53.6
      mcp:
        status: none
      name: Akoya
      slug: akoya
      sources:
      - https://www.kubera.com/security
      status: profiled
      tags:
      - Aggregator
      - Fintech
      - Open Banking
      - Open Finance
      tier: declared
      url: /providers/akoya/
    - agent_band: agent-native
      agent_readiness: 53.0
      apps:
      - Kubera
      band: developing
      in_catalog: true
      kin_score: 52.5
      mcp:
        status: none
      name: Lean Technologies
      slug: lean-technologies
      sources:
      - https://www.kubera.com/security
      status: profiled
      tags:
      - Financial Data
      - Open Banking
      - Open Finance
      - Payments
      tier: declared
      url: /providers/lean-technologies/
    - agent_band: agent-ready
      agent_readiness: 33.8
      apps:
      - Kubera
      band: developing
      in_catalog: true
      kin_score: 47.6
      mcp:
        status: none
      name: Akahu
      slug: akahu
      sources:
      - https://www.kubera.com/security
      status: profiled
      tags:
      - Company
      - Finance
      - New Zealand
      - Open Banking
      tier: declared
      url: /providers/akahu/
    - agent_band: agent-aware
      agent_readiness: 21.0
      apps:
      - Kubera
      band: thin
      in_catalog: true
      kin_score: 31.1
      mcp:
        status: none
      name: Yodlee
      slug: yodlee
      sources:
      - https://www.kubera.com/security
      status: profiled
      tags:
      - Banking
      - Data Aggregation
      - Financial Data
      - Fintech
      tier: declared
      url: /providers/yodlee/
    - agent_band: agent-aware
      agent_readiness: 22.4
      apps:
      - Kubera
      band: thin
      in_catalog: true
      kin_score: 26.9
      mcp:
        status: none
      name: Salt Edge
      slug: salt-edge
      sources:
      - https://www.kubera.com/security
      status: profiled
      tags:
      - Aggregator
      - Fintech
      - Open Banking
      - PSD2
      tier: declared
      url: /providers/salt-edge/
  - capability:
      attribution: API Evangelist extension
      id: AE-230.20
      key: AE-230.20
      name: Market & Financial Data
      url: /capabilities/market-financial-data/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 26.4
      apps:
      - Ghostfolio
      - Wealthfolio
      band: thin
      in_catalog: true
      kin_score: 33.7
      mcp:
        status: none
      name: OpenFIGI
      slug: openfigi
      sources:
      - https://github.com/ghostfolio/ghostfolio/tree/main/apps/api/src/services/data-provider/data-enhancer
      - https://github.com/wealthfolio/wealthfolio/tree/main/crates/market-data/src/provider
      status: profiled
      tags:
      - Finance
      - Instruments
      tier: observed
      url: /providers/openfigi/
    - agent_band: agent-ready
      agent_readiness: 33.2
      apps:
      - Ghostfolio
      band: developing
      in_catalog: true
      kin_score: 41.3
      mcp:
        status: none
      name: RapidAPI (Fear & Greed Index)
      slug: rapidapi
      sources:
      - https://raw.githubusercontent.com/ghostfolio/ghostfolio/main/apps/api/src/services/data-provider/rapid-api/rapid-api.service.ts
      status: profiled
      tags:
      - API Gateway
      - API Management
      - API Marketplace
      - API Testing
      tier: observed
      url: /providers/rapidapi/
    - agent_band: agent-aware
      agent_readiness: 20.2
      apps:
      - Portfolio Performance
      band: thin
      in_catalog: true
      kin_score: 30.4
      mcp:
        status: none
      name: Eurostat (HICP)
      slug: eurostat
      sources:
      - https://github.com/portfolio-performance/portfolio/tree/master/name.abuchen.portfolio/src/name/abuchen/portfolio/online/impl
      status: profiled
      tags:
      - Demographics
      - European Union
      - Open Data
      - Statistics
      tier: observed
      url: /providers/eurostat/
    - agent_band: agent-aware
      agent_readiness: 17.4
      apps:
      - Wealthfolio
      band: thin
      in_catalog: true
      kin_score: 29.7
      mcp:
        status: none
      name: US Treasury (treasury.gov / TreasuryDirect)
      slug: department-of-the-treasury
      sources:
      - https://raw.githubusercontent.com/wealthfolio/wealthfolio/main/crates/market-data/src/provider/us_treasury_calc/mod.rs
      status: profiled
      tags:
      - Debt
      - Federal Government
      - Finance
      - Sanctions
      tier: observed
      url: /providers/department-of-the-treasury/
    - agent_band: human-only
      agent_readiness: 2.9
      apps:
      - Wealthfolio
      band: emerging
      in_catalog: true
      kin_score: 17.4
      mcp:
        status: none
      name: Metal Price API
      slug: metalpriceapi
      sources:
      - https://raw.githubusercontent.com/wealthfolio/wealthfolio/main/crates/market-data/src/provider/metal_price_api/mod.rs
      status: profiled
      tags:
      - Company
      - Data
      - Finance
      - Metals
      tier: observed
      url: /providers/metalpriceapi/
  - capability:
      attribution: API Evangelist extension
      id: AE-230.20.10
      key: AE-230.20.10
      name: Exchange Rates
      url: /capabilities/market-financial-data/
      via_parent: Market & Financial Data
    providers:
    - agent_band: agent-ready
      agent_readiness: 46.2
      apps:
      - Freqtrade
      band: developing
      in_catalog: true
      kin_score: 52.0
      mcp: *id001
      name: CoinGecko
      slug: coingecko
      sources:
      - https://raw.githubusercontent.com/freqtrade/freqtrade/develop/requirements.txt
      status: profiled
      tags: *id002
      tier: observed
      url: /providers/coingecko/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Portfolio Performance
      band: minimal
      in_catalog: true
      kin_score: 7.8
      mcp:
        status: none
      name: ECB Data Portal
      slug: european-central-bank
      sources:
      - https://github.com/portfolio-performance/portfolio/tree/master/name.abuchen.portfolio/src/name/abuchen/portfolio/online/impl
      status: profiled
      tags:
      - Banking
      - Economic Data
      - European Union
      - Finance
      tier: observed
      url: /providers/european-central-bank/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - rotki
      band: minimal
      in_catalog: true
      kin_score: 4.9
      mcp:
        status: unknown
      name: X-Rates
      slug: xrates
      sources:
      - https://github.com/rotki/rotki/tree/develop/rotkehlchen/externalapis
      status: profiled
      tags:
      - Company
      - Currency
      - Exchange Rates
      - Finance
      tier: observed
      url: /providers/xrates/
  - capability:
      attribution: API Evangelist extension
      id: AE-190.30.10
      key: AE-190.30.10
      name: Brokerage APIs
      url: /capabilities/retail-investing/
      via_parent: Retail Investing
    providers:
    - agent_band: agent-ready
      agent_readiness: 53.2
      apps:
      - Kubera
      - Wealthfolio
      band: developing
      in_catalog: true
      kin_score: 50.5
      mcp:
        source: https://docs.snaptrade.com/docs/mcp-server
        status: verified
      name: SnapTrade
      slug: snaptrade
      sources:
      - https://raw.githubusercontent.com/wealthfolio/wealthfolio/main/crates/connect/src/broker/models.rs
      - https://www.kubera.com/security
      status: profiled
      tags:
      - Brokerage
      - Company
      - Fintech
      - Trading
      tier: observed
      url: /providers/snaptrade/
  - capability:
      attribution: API Evangelist extension
      id: AE-240.60.10
      key: AE-240.60.10
      name: Decentralized Exchanges
      url: /capabilities/defi-protocols/
      via_parent: DeFi Protocols
    providers:
    - agent_band: agent-ready
      agent_readiness: 32.9
      apps:
      - rotki
      band: thin
      in_catalog: true
      kin_score: 35.1
      mcp:
        status: none
      name: CoW Swap
      slug: cow-protocol
      sources:
      - https://github.com/rotki/rotki/tree/develop/rotkehlchen/externalapis
      status: profiled
      tags:
      - DeFi
      - Ethereum
      - Liquidity
      - Swap
      tier: observed
      url: /providers/cow-protocol/
    - agent_band: agent-aware
      agent_readiness: 24.4
      apps:
      - rotki
      band: thin
      in_catalog: true
      kin_score: 27.6
      mcp:
        source: https://developers.jup.ag/docs/ai/trading-mcp
        status: documented
      name: Jupiter
      slug: jupiter-ag
      sources:
      - https://github.com/rotki/rotki/tree/develop/rotkehlchen/externalapis
      status: profiled
      tags:
      - DEX Aggregator
      - DeFi
      - Solana
      - Swap
      tier: observed
      url: /providers/jupiter-ag/
  - capability:
      attribution: API Evangelist extension
      id: AE-240.30.20
      key: AE-240.30.20
      name: Blockchain Analytics
      url: /capabilities/on-chain-data-indexing/
      via_parent: On-Chain Data & Indexing
    providers:
    - agent_band: agent-ready
      agent_readiness: 48.7
      apps:
      - rotki
      band: thin
      in_catalog: true
      kin_score: 30.7
      mcp:
        status: none
      name: DefiLlama
      slug: defillama
      sources:
      - https://github.com/rotki/rotki/tree/develop/rotkehlchen/externalapis
      status: profiled
      tags:
      - Cryptocurrency
      - DeFi
      - TVL
      - Web3
      tier: observed
      url: /providers/defillama/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.80
      key: AE-150.80
      name: Mailbox & Calendar Sync
      url: /capabilities/mailbox-calendar-sync/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 20.7
      apps:
      - rotki
      band: developing
      in_catalog: true
      kin_score: 48.8
      mcp:
        source: https://github.com/google/mcp
        status: verified
      name: Google Calendar
      slug: google-calendar
      sources:
      - https://github.com/rotki/rotki/tree/develop/rotkehlchen/externalapis
      status: profiled
      tags:
      - Availability
      - Calendar
      - Event
      - Google
      tier: observed
      url: /providers/google-calendar/
  - capability:
      attribution: API Evangelist extension
      id: AE-240.50.20
      key: AE-240.50.20
      name: NFTs & Digital Collectibles
      url: /capabilities/token-issuance-smart-contracts/
      via_parent: Token Issuance & Smart Contracts
    providers:
    - agent_band: agent-ready
      agent_readiness: 37.5
      apps:
      - rotki
      band: developing
      in_catalog: true
      kin_score: 41.4
      mcp:
        source: https://docs.opensea.io/docs/mcp
        status: verified
      name: OpenSea
      slug: opensea
      sources:
      - https://github.com/rotki/rotki/tree/develop/rotkehlchen/externalapis
      status: profiled
      tags:
      - Blockchain
      - Marketplace
      - NFT
      - Web3
      tier: observed
      url: /providers/opensea/
  - capability:
      attribution: API Evangelist extension
      id: AE-240.70.10
      key: AE-240.70.10
      name: Stablecoin Issuance
      url: /capabilities/stablecoin-payments/
      via_parent: Stablecoin Payments
    providers:
    - agent_band: agent-aware
      agent_readiness: 24.8
      apps:
      - rotki
      band: thin
      in_catalog: true
      kin_score: 38.2
      mcp:
        status: none
      name: Monerium
      slug: monerium
      sources:
      - https://github.com/rotki/rotki/tree/develop/rotkehlchen/externalapis
      status: profiled
      tags:
      - Blockchain
      - Digital Currency
      - Fintech
      - Payments
      tier: observed
      url: /providers/monerium/
  - capability:
      attribution: API Evangelist extension
      id: AE-240.70
      key: AE-240.70
      name: Stablecoin Payments
      url: /capabilities/stablecoin-payments/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 32.8
      apps:
      - rotki
      band: developing
      in_catalog: true
      kin_score: 39.3
      mcp:
        status: none
      name: Gnosis Pay
      slug: gnosis-pay
      sources:
      - https://github.com/rotki/rotki/tree/develop/rotkehlchen/externalapis
      status: profiled
      tags:
      - Company
      - Cryptocurrency
      - Payments
      - Stablecoins
      tier: observed
      url: /providers/gnosis-pay/
  layer: domain
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    providers:
    - agent_band: agent-ready
      agent_readiness: 47.6
      apps:
      - Wealthfolio
      band: exemplar
      in_catalog: true
      kin_score: 87.5
      mcp:
        source: https://docs.anthropic.com/en/docs/agents-and-tools/mcp-connector
        status: verified
      name: Anthropic
      slug: anthropic
      sources:
      - https://raw.githubusercontent.com/wealthfolio/wealthfolio/main/crates/ai/src/ai_providers.json
      status: profiled
      tags:
      - Anthropic
      - Artificial Intelligence
      - Claude
      - LLM
      tier: observed
      url: /providers/anthropic/
    - agent_band: agent-native
      agent_readiness: 58.4
      apps:
      - Wealthfolio
      band: exemplar
      in_catalog: true
      kin_score: 81.8
      mcp:
        source: https://platform.openai.com/docs/mcp
        status: verified
      name: OpenAI
      slug: openai
      sources:
      - https://raw.githubusercontent.com/wealthfolio/wealthfolio/main/crates/ai/src/ai_providers.json
      status: profiled
      tags:
      - Artificial Intelligence
      - Generative AI
      - LLM
      - OpenAI
      tier: observed
      url: /providers/openai/
    - agent_band: agent-ready
      agent_readiness: 31.3
      apps:
      - Wealthfolio
      band: strong
      in_catalog: true
      kin_score: 55.1
      mcp:
        status: none
      name: Google AI (Gemini)
      slug: google-gemini
      sources:
      - https://raw.githubusercontent.com/wealthfolio/wealthfolio/main/crates/ai/src/ai_providers.json
      status: profiled
      tags:
      - AI Agents
      - Artificial Intelligence
      - Code Generation
      - Embeddings
      tier: observed
      url: /providers/google-gemini/
    - agent_band: agent-aware
      agent_readiness: 24.4
      apps:
      - Wealthfolio
      band: thin
      in_catalog: true
      kin_score: 38.0
      mcp:
        status: none
      name: Ollama
      slug: ollama
      sources:
      - https://raw.githubusercontent.com/wealthfolio/wealthfolio/main/crates/ai/src/ai_providers.json
      status: profiled
      tags:
      - Artificial Intelligence
      - LLM
      - Models
      - Ollama
      tier: observed
      url: /providers/ollama/
    - agent_band: agent-aware
      agent_readiness: 21.6
      apps:
      - Wealthfolio
      band: thin
      in_catalog: true
      kin_score: 32.9
      mcp:
        source: https://github.com/groq/groq-mcp-server
        status: verified
      name: Groq
      slug: groq
      sources:
      - https://raw.githubusercontent.com/wealthfolio/wealthfolio/main/crates/ai/src/ai_providers.json
      status: profiled
      tags:
      - Artificial Intelligence
      - Inference
      - LLM
      - LPU
      tier: observed
      url: /providers/groq/
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    providers:
    - agent_band: agent-aware
      agent_readiness: 19.6
      apps:
      - Ghostfolio
      - Kubera
      - Robinhood
      band: thin
      in_catalog: true
      kin_score: 36.8
      mcp:
        status: none
      name: Google sign-in
      slug: google-identity-platform
      sources:
      - https://raw.githubusercontent.com/ghostfolio/ghostfolio/main/package.json
      - https://robinhood.com/us/en/support/articles/privacy-policy/
      - https://www.kubera.com/security
      status: profiled
      tags:
      - Authentication
      - Google Cloud
      - Identity
      - Multi-Tenancy
      tier: observed
      url: /providers/google-identity-platform/
    - agent_band: agent-ready
      agent_readiness: 31.9
      apps:
      - Robinhood
      band: strong
      in_catalog: true
      kin_score: 55.2
      mcp:
        status: none
      name: Sign in with Apple
      slug: apple
      sources:
      - https://robinhood.com/us/en/support/articles/privacy-policy/
      status: profiled
      tags:
      - Apple
      - Developers
      - iOS
      - macOS
      tier: declared
      url: /providers/apple/
  - capability:
      attribution: API Evangelist extension
      id: AE-902
      key: AE-902
      name: Mobile Attribution & Deep Linking
      url: /capabilities/mobile-attribution-deep-linking/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 50.0
      apps:
      - Robinhood
      band: exemplar
      in_catalog: true
      kin_score: 67.4
      mcp:
        status: none
      name: Singular
      slug: singular
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.robinhood.android/latest/
      status: profiled
      tags:
      - Attribution
      - Company
      - Marketing Analytics
      - Mobile Attribution
      tier: observed
      url: /providers/singular/
    - agent_band: agent-aware
      agent_readiness: 23.8
      apps:
      - Robinhood
      band: emerging
      in_catalog: true
      kin_score: 24.9
      mcp:
        status: none
      name: Adjust
      slug: adjust
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.robinhood.android/latest/
      status: profiled
      tags:
      - Analytics
      - Attribution
      - Deep Linking
      - Measurements
      tier: observed
      url: /providers/adjust/
    - agent_band: agent-aware
      agent_readiness: 24.7
      apps:
      - Robinhood
      band: emerging
      in_catalog: true
      kin_score: 23.0
      mcp:
        status: none
      name: Branch
      slug: branch-io
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.robinhood.android/latest/
      status: profiled
      tags:
      - Company
      tier: observed
      url: /providers/branch-io/
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.30
      key: AE-110.10.30
      name: Model Routing & Gateways
      url: /capabilities/model-inference/
      via_parent: Model Inference
    providers:
    - agent_band: agent-ready
      agent_readiness: 46.9
      apps:
      - Ghostfolio
      - Wealthfolio
      band: strong
      in_catalog: true
      kin_score: 55.4
      mcp:
        source: https://openrouter.ai/docs/guides/overview/mcp-server
        status: verified
      name: OpenRouter
      slug: openrouter
      sources:
      - https://raw.githubusercontent.com/ghostfolio/ghostfolio/main/package.json
      - https://raw.githubusercontent.com/wealthfolio/wealthfolio/main/crates/ai/src/ai_providers.json
      status: profiled
      tags:
      - Artificial Intelligence
      - Gateways
      - LLM
      - Router
      tier: observed
      url: /providers/openrouter/
  - capability:
      attribution: Turbo EA
      id: BC-430.50
      key: customer-feedback-management
      name: Customer Feedback Management
      url: /capabilities/customer-feedback-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 19.0
      apps:
      - Kubera
      band: thin
      in_catalog: true
      kin_score: 28.1
      mcp:
        status: none
      name: REVIEWS.io
      slug: reviews-io
      sources:
      - https://www.kubera.com/security
      status: profiled
      tags:
      - Ratings
      - Reputation
      - Reviews
      - UGC
      tier: declared
      url: /providers/reviews-io/
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 47.7
      apps:
      - Robinhood
      band: exemplar
      in_catalog: true
      kin_score: 73.1
      mcp:
        source: https://developers.google.com/google-ads/api/docs/developer-toolkit/mcp-server
        status: verified
      name: Google Ads
      slug: google-ads
      sources:
      - https://robinhood.com/us/en/support/articles/privacy-policy/
      status: profiled
      tags:
      - Advertising
      - Campaign Management
      - Digital Advertising
      - Google
      tier: declared
      url: /providers/google-ads/
  - capability:
      attribution: Turbo EA
      id: BC-600.50
      key: it-infrastructure-management
      name: IT Infrastructure Management
      url: /capabilities/it-infrastructure-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 40.8
      apps:
      - Kubera
      band: strong
      in_catalog: true
      kin_score: 60.5
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: AWS
      slug: amazon-web-services
      sources:
      - https://www.kubera.com/security
      status: profiled
      tags:
      - Amazon
      - Amazon Web Services
      - Cloud
      - Networks
      tier: declared
      url: /providers/amazon-web-services/
  - capability:
      attribution: API Evangelist extension
      id: AE-160.30
      key: AE-160.30
      name: Identity Verification
      url: /capabilities/identity-verification/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 33.8
      apps:
      - Robinhood
      band: developing
      in_catalog: true
      kin_score: 51.9
      mcp:
        status: none
      name: Persona
      slug: persona
      sources:
      - https://robinhood.com/us/en/support/articles/privacy-policy/
      status: profiled
      tags:
      - Fraud Prevention
      - Identity Verification
      - KYC
      tier: declared
      url: /providers/persona/
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 30.6
      apps:
      - Freqtrade
      band: developing
      in_catalog: true
      kin_score: 46.9
      mcp:
        status: none
      name: Discord
      slug: discord
      sources:
      - https://github.com/freqtrade/freqtrade/tree/develop/freqtrade/rpc
      status: profiled
      tags:
      - Chat
      - Communications
      - Discord
      - Gaming
      tier: observed
      url: /providers/discord/
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 50.2
      apps:
      - Robinhood
      band: exemplar
      in_catalog: true
      kin_score: 80.6
      mcp:
        source: https://docs.sentry.io/product/sentry-mcp/
        status: verified
      name: Sentry
      slug: sentry-system
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.robinhood.android/latest/
      status: profiled
      tags:
      - APM
      - Application Monitoring
      - Bug Tracking
      - Developer Tools
      tier: observed
      url: /providers/sentry-system/
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 58.5
      apps:
      - Ghostfolio
      band: exemplar
      in_catalog: true
      kin_score: 81.5
      mcp:
        source: https://docs.stripe.com/mcp
        status: verified
      name: Stripe
      slug: stripe
      sources:
      - https://raw.githubusercontent.com/ghostfolio/ghostfolio/main/package.json
      status: profiled
      tags:
      - Commerce
      - Financial Services
      - Fintech
      - Payments
      tier: observed
      url: /providers/stripe/
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 14.2
      apps:
      - Robinhood
      band: developing
      in_catalog: true
      kin_score: 50.3
      mcp:
        source: https://firebase.google.com/docs/ai-assistance/mcp-server
        status: verified
      name: Google Firebase Analytics / Crashlytics
      slug: firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.robinhood.android/latest/
      status: profiled
      tags:
      - Application Development
      - Backend-as-a-Service
      - Company
      - Mobile
      tier: observed
      url: /providers/firebase/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 61.2
      apps:
      - Ghostfolio
      band: exemplar
      in_catalog: true
      kin_score: 74.7
      mcp:
        source: https://github.com/xdevplatform/xmcp
        status: verified
      name: X (Twitter)
      slug: x
      sources:
      - https://raw.githubusercontent.com/ghostfolio/ghostfolio/main/package.json
      status: profiled
      tags:
      - Conversations
      - Social
      - Spaces
      - X
      tier: observed
      url: /providers/x/
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-aware
      agent_readiness: 27.7
      apps:
      - Wealthfolio
      band: thin
      in_catalog: true
      kin_score: 36.3
      mcp:
        source: https://raw.githubusercontent.com/cloudflare/mcp/main/README.md
        status: verified
      name: Cloudflare R2
      slug: cloudflare-r2
      sources:
      - https://raw.githubusercontent.com/wealthfolio/wealthfolio/main/config/connect.defaults.json
      status: profiled
      tags:
      - Cloud Storage
      - Egress-Free
      - Object Storage
      - S3 Compatible
      tier: observed
      url: /providers/cloudflare-r2/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.20
      key: AE-150.20.20
      name: WhatsApp & OTT Messaging
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    providers:
    - agent_band: agent-aware
      agent_readiness: 25.4
      apps:
      - Freqtrade
      band: strong
      in_catalog: true
      kin_score: 58.4
      mcp:
        status: none
      name: Telegram
      slug: telegram
      sources:
      - https://raw.githubusercontent.com/freqtrade/freqtrade/develop/requirements.txt
      status: profiled
      tags:
      - Bots
      - Chat
      - Messaging
      - Notification
      tier: observed
      url: /providers/telegram/
  layer: common
summary:
  coverage_pct: 97.0
  declared_only: 13
  distinct_providers: 100
  in_catalog: 97
  mcp:
    documented: 3
    none: 54
    unchecked: 3
    verified: 36
  mcp_verified: 36
  mean_kin_score: 40.9
  observed: 87
  queued: 3
  reference_apps: 7
title: 'Investing & Trading: application blueprint'
---
