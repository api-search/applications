---
access: understanding
agent_layer:
- app: Ghostfolio
  finding: ships its own MCP server at /mcp behind ENABLE_FEATURE_MCP (experimental), scoped by MCP access tokens
  source: https://raw.githubusercontent.com/ghostfolio/ghostfolio/main/README.md
  tier: declared
- app: YNAB
  finding: no first-party MCP; the YNAB API works-with list carries community MCP servers (e.g. avenir-mcp) and ChatGPT GPTs
  source: https://api.ynab.com/
  tier: declared
- app: Maybe
  finding: BYO OpenAI key drives an in-app AI assistant (llm provider concept); no MCP server
  source: https://github.com/maybe-finance/maybe/blob/main/app/models/provider/registry.rb
  tier: observed
- app: Ghostfolio
  finding: BYO-LLM via OpenRouter
  source: https://raw.githubusercontent.com/ghostfolio/ghostfolio/main/package.json
  tier: observed
apps:
- anchor: actual-budget
  counts:
    declared: 0
    observed: 5
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/actualbudget/actual/master/packages/sync-server/package.json
  - route: documentation
    url: https://actualbudget.org/docs/advanced/bank-sync/
  - route: source code
    url: https://github.com/actualbudget/actual/tree/master/packages/sync-server/src
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
    says: ships the Akahu SDK or integration code
    source: https://github.com/actualbudget/actual/tree/master/packages/sync-server/src
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-190.50
      key: AE-190.50
      name: Consumer Data Access
      url: /capabilities/consumer-data-access/
      via_parent: null
    credit: null
    layer: domain
    name: Enable Banking
    provider: enable-banking
    says: ships the Enable Banking SDK or integration code
    source: https://github.com/actualbudget/actual/tree/master/packages/sync-server/src
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-190.50
      key: AE-190.50
      name: Consumer Data Access
      url: /capabilities/consumer-data-access/
      via_parent: null
    credit: null
    layer: domain
    name: GoCardless Bank Account Data
    provider: nordigen
    says: ships the GoCardless Bank Account Data SDK or integration code
    source: https://github.com/actualbudget/actual/tree/master/packages/sync-server/src
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-190.50
      key: AE-190.50
      name: Consumer Data Access
      url: /capabilities/consumer-data-access/
      via_parent: null
    credit: null
    layer: domain
    name: Pluggy
    provider: pluggy
    says: ships the Pluggy SDK or integration code
    source: https://raw.githubusercontent.com/actualbudget/actual/master/packages/sync-server/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-190.50
      key: AE-190.50
      name: Consumer Data Access
      url: /capabilities/consumer-data-access/
      via_parent: null
    credit: null
    layer: domain
    name: SimpleFIN Bridge
    provider: simplefin
    says: ships the SimpleFIN Bridge SDK or integration code
    source: https://github.com/actualbudget/actual/tree/master/packages/sync-server/src
    tier: observed
  kind: self-hosted
  name: Actual Budget
  page: /applications/personal-finance-budgeting/actual-budget/
  slug: actual-budget
  url: https://github.com/actualbudget/actual
- anchor: firefly-iii
  counts:
    declared: 0
    observed: 9
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/firefly-iii/firefly-iii/main/composer.json
  - route: source code
    url: https://github.com/firefly-iii/data-importer/tree/main/app/Services
  - route: source code
    url: https://github.com/firefly-iii/firefly-iii/blob/main/app/Notifications/ReturnsAvailableChannels.php
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
    says: ships the Akahu SDK or integration code
    source: https://github.com/firefly-iii/data-importer/tree/main/app/Services
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-190.50
      key: AE-190.50
      name: Consumer Data Access
      url: /capabilities/consumer-data-access/
      via_parent: null
    credit: null
    layer: domain
    name: Enable Banking
    provider: enable-banking
    says: ships the Enable Banking SDK or integration code
    source: https://github.com/firefly-iii/data-importer/tree/main/app/Services
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-190.50
      key: AE-190.50
      name: Consumer Data Access
      url: /capabilities/consumer-data-access/
      via_parent: null
    credit: null
    layer: domain
    name: GoCardless Bank Account Data
    provider: nordigen
    says: ships the GoCardless Bank Account Data SDK or integration code
    source: https://github.com/firefly-iii/data-importer/tree/main/app/Services
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-190.50
      key: AE-190.50
      name: Consumer Data Access
      url: /capabilities/consumer-data-access/
      via_parent: null
    credit: null
    layer: domain
    name: Lunch Flow
    provider: lunch-flow
    says: ships the Lunch Flow SDK or integration code
    source: https://github.com/firefly-iii/data-importer/tree/main/app/Services
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.10
      key: AE-150.10.10
      name: Transactional Email
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: common
    name: MailerSend
    provider: mailersend
    says: ships the MailerSend SDK or integration code
    source: https://raw.githubusercontent.com/firefly-iii/firefly-iii/main/composer.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.30
      key: AE-150.30
      name: Push Notifications
      url: /capabilities/push-notifications/
      via_parent: null
    credit: null
    layer: common
    name: Pushover
    provider: pushover
    says: ships the Pushover SDK or integration code
    source: https://raw.githubusercontent.com/firefly-iii/firefly-iii/main/composer.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-190.50
      key: AE-190.50
      name: Consumer Data Access
      url: /capabilities/consumer-data-access/
      via_parent: null
    credit: null
    layer: domain
    name: SimpleFIN Bridge
    provider: simplefin
    says: ships the SimpleFIN Bridge SDK or integration code
    source: https://github.com/firefly-iii/data-importer/tree/main/app/Services
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150
      key: AE-150
      name: Application Communications
      url: /capabilities/application-communications/
      via_parent: null
    credit: null
    layer: common
    name: Slack
    provider: slack
    says: ships the Slack SDK or integration code
    source: https://github.com/firefly-iii/firefly-iii/blob/main/app/Notifications/ReturnsAvailableChannels.php
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-190.50
      key: AE-190.50
      name: Consumer Data Access
      url: /capabilities/consumer-data-access/
      via_parent: null
    credit: null
    layer: domain
    name: Sophtron
    provider: sophtron
    says: ships the Sophtron SDK or integration code
    source: https://github.com/firefly-iii/data-importer/tree/main/app/Services
    tier: observed
  kind: self-hosted
  name: Firefly III
  page: /applications/personal-finance-budgeting/firefly-iii/
  slug: firefly-iii
  url: https://github.com/firefly-iii/firefly-iii
- anchor: maybe
  counts:
    declared: 0
    observed: 10
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/maybe-finance/maybe/main/Gemfile
  - route: source code
    url: https://github.com/maybe-finance/maybe/blob/main/app/models/provider/registry.rb
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-3710.30
      key: asset-storage-tiering
      name: Asset Storage & Tiering
      url: /capabilities/asset-storage-tiering/
      via_parent: null
    credit: null
    layer: common
    name: Amazon S3
    provider: amazon-s3
    says: ships the Amazon S3 SDK or integration code
    source: https://raw.githubusercontent.com/maybe-finance/maybe/main/Gemfile
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: common
    name: Better Stack
    provider: betterstack
    says: ships the Better Stack SDK or integration code
    source: https://raw.githubusercontent.com/maybe-finance/maybe/main/Gemfile
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4210
      key: software-release-deployment-management
      name: Software Release & Deployment Management
      url: /capabilities/software-release-deployment-management/
      via_parent: null
    credit: null
    layer: common
    name: GitHub
    provider: github
    says: ships the GitHub SDK or integration code
    source: https://github.com/maybe-finance/maybe/blob/main/app/models/provider/registry.rb
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: common
    name: Intercom
    provider: intercom
    says: ships the Intercom SDK or integration code
    source: https://raw.githubusercontent.com/maybe-finance/maybe/main/Gemfile
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
    source: https://github.com/maybe-finance/maybe/blob/main/app/models/provider/registry.rb
    tier: observed
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
    says: ships the Plaid SDK or integration code
    source: https://github.com/maybe-finance/maybe/blob/main/app/models/provider/registry.rb
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: common
    name: Sentry
    provider: sentry-system
    says: ships the Sentry SDK or integration code
    source: https://raw.githubusercontent.com/maybe-finance/maybe/main/Gemfile
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: common
    name: Skylight
    provider: skylight
    says: ships the Skylight SDK or integration code
    source: https://raw.githubusercontent.com/maybe-finance/maybe/main/Gemfile
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
    source: https://github.com/maybe-finance/maybe/blob/main/app/models/provider/registry.rb
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
    name: Synth Finance
    provider: synth
    says: ships the Synth Finance SDK or integration code
    source: https://github.com/maybe-finance/maybe/blob/main/app/models/provider/registry.rb
    tier: observed
  kind: open-source-saas
  name: Maybe
  page: /applications/personal-finance-budgeting/maybe/
  slug: maybe
  url: https://github.com/maybe-finance/maybe
- anchor: ghostfolio
  counts:
    declared: 0
    observed: 13
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/ghostfolio/ghostfolio/main/package.json
  - route: documentation
    url: https://raw.githubusercontent.com/ghostfolio/ghostfolio/main/README.md
  - route: source code
    url: https://github.com/ghostfolio/ghostfolio/tree/main/apps/api/src/services/data-provider
  - route: source code
    url: https://github.com/ghostfolio/ghostfolio/tree/main/apps/api/src/services/data-provider/data-enhancer
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
    name: EODHD
    provider: eodhd
    says: ships the EODHD SDK or integration code
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
      id: AE-230.20.20
      key: AE-230.20.20
      name: Securities Market Data
      url: /capabilities/market-financial-data/
      via_parent: Market & Financial Data
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
      id: AE-230.20.20
      key: AE-230.20.20
      name: Securities Market Data
      url: /capabilities/market-financial-data/
      via_parent: Market & Financial Data
    credit: null
    layer: domain
    name: RapidAPI
    provider: rapidapi
    says: ships the RapidAPI SDK or integration code
    source: https://github.com/ghostfolio/ghostfolio/tree/main/apps/api/src/services/data-provider
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
      attribution: Turbo EA
      id: BC-400.60.40
      key: BC-400.60.40
      name: Social Media Management
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
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
  page: /applications/personal-finance-budgeting/ghostfolio/
  slug: ghostfolio
  url: https://github.com/ghostfolio/ghostfolio
- anchor: monarch-money
  counts:
    declared: 0
    observed: 7
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.monarchmoney.mobile/latest/
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Amplitude
    provider: amplitude
    says: ships the Amplitude SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.monarchmoney.mobile/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Facebook
    provider: facebook
    says: ships the Facebook SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.monarchmoney.mobile/latest/
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
    name: Firebase
    provider: firebase
    says: ships the Firebase SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.monarchmoney.mobile/latest/
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
    name: FullStory
    provider: fullstory
    says: ships the FullStory SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.monarchmoney.mobile/latest/
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
    name: Segment
    provider: segment
    says: ships the Segment SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.monarchmoney.mobile/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.monarchmoney.mobile/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Singular
    provider: singular
    says: ships the Singular SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.monarchmoney.mobile/latest/
    tier: observed
  kind: commercial
  name: Monarch Money
  page: /applications/personal-finance-budgeting/monarch-money/
  slug: monarch-money
  url: https://www.monarchmoney.com/
- anchor: ynab
  counts:
    declared: 4
    observed: 3
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.youneedabudget.evergreen.app/latest/
  - route: documentation
    url: https://support.ynab.com/en_us/how-direct-import-works-H1IGYLgnxl.md
  - route: integrations page
    url: https://api.ynab.com/
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Amplitude
    provider: amplitude
    says: ships the Amplitude SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.youneedabudget.evergreen.app/latest/
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
    name: Bugsnag
    provider: bugsnag
    says: ships the Bugsnag SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.youneedabudget.evergreen.app/latest/
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
    name: Firebase
    provider: firebase
    says: ships the Firebase SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.youneedabudget.evergreen.app/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-190.50
      key: AE-190.50
      name: Consumer Data Access
      url: /capabilities/consumer-data-access/
      via_parent: null
    credit: null
    layer: domain
    name: Apple (Apple Wallet)
    provider: apple
    says: lists Apple (Apple Wallet) as an integration
    source: https://support.ynab.com/en_us/how-direct-import-works-H1IGYLgnxl.md
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
    source: https://support.ynab.com/en_us/how-direct-import-works-H1IGYLgnxl.md
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
    source: https://support.ynab.com/en_us/how-direct-import-works-H1IGYLgnxl.md
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-910
      key: AE-910
      name: Workflow Automation & iPaaS
      url: /capabilities/process-automation-governance/
      via_parent: Process Automation Governance
    credit: null
    layer: common
    name: Zapier
    provider: zapier
    says: lists Zapier as an integration
    source: https://api.ynab.com/
    tier: declared
  kind: commercial
  name: YNAB
  page: /applications/personal-finance-budgeting/ynab/
  slug: ynab
  url: https://www.ynab.com/
- anchor: wallet-by-budgetbakers
  counts:
    declared: 1
    observed: 4
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.droid4you.application.wallet/latest/
  - route: documentation
    url: https://budgetbakers.com/en/legal/saltedge-privacy/
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Facebook
    provider: facebook
    says: ships the Facebook SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.droid4you.application.wallet/latest/
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
    name: Firebase
    provider: firebase
    says: ships the Firebase SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.droid4you.application.wallet/latest/
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
    name: Mixpanel
    provider: mixpanel
    says: ships the Mixpanel SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.droid4you.application.wallet/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4260.40
      key: customer-lifecycle-engagement
      name: Customer Lifecycle Engagement
      url: /capabilities/customer-lifecycle-engagement/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: MoEngage
    provider: moengage
    says: ships the MoEngage SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.droid4you.application.wallet/latest/
    tier: observed
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
    source: https://budgetbakers.com/en/legal/saltedge-privacy/
    tier: declared
  kind: commercial
  name: Wallet by BudgetBakers
  page: /applications/personal-finance-budgeting/wallet-by-budgetbakers/
  slug: wallet-by-budgetbakers
  url: https://budgetbakers.com/en/products/wallet/
author: API Evangelist
candidates: []
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
html: public
id: personal-finance-budgeting
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Finance
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Finance
  store: google-play
  url: https://play.google.com/store/apps/category/FINANCE
- category: Money, Budgeting & Management
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#money-budgeting--management
- category: Accounting
  store: zapier
  url: https://zapier.com/apps
name: Personal Finance & Budgeting
needs:
- capability:
    attribution: API Evangelist extension
    id: AE-190
    key: AE-190
    name: Personal Finance & Consumer Money
    url: /capabilities/personal-finance-consumer-money/
    via_parent: null
  fit: gap
  layer: domain
  why: 'AE-190.50 Consumer Data Access: bank and card transaction aggregation -- the core of every budgeting app (dotted AE ids rejected by validator)'
- capability:
    attribution: API Evangelist extension
    id: AE-150
    key: AE-150
    name: Application Communications
    url: /capabilities/application-communications/
    via_parent: null
  fit: gap
  layer: common
  why: 'AE-150.10.10 Transactional Email: transactional email; AE-150.30 Push Notifications: push alerts for bills/budgets (dotted AE ids rejected by validator)'
- capability:
    attribution: API Evangelist extension
    id: AE-230
    key: AE-230
    name: Data & Reference Information Services
    url: /capabilities/data-reference-information-services/
    via_parent: null
  fit: gap
  layer: domain
  why: 'AE-230.20.10 Exchange Rates: multi-currency conversion; AE-230.20.20 Securities Market Data: security and crypto prices for net-worth and portfolio tracking (dotted AE ids rejected by validator)'
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  fit: exact
  layer: common
  why: charging for the hosted/premium tier
- capability:
    attribution: API Evangelist extension
    id: AE-110
    key: AE-110
    name: AI Model Services
    url: /capabilities/ai-model-services/
    via_parent: null
  fit: gap
  layer: common
  why: 'AE-110.10.10 Hosted LLM Inference: AI assistant over the user''s finances; AE-110.10.30 Model Routing & Gateways: routing LLM calls across models (dotted AE ids rejected by validator)'
- capability:
    attribution: Turbo EA
    id: BC-4210
    key: software-release-deployment-management
    name: Software Release & Deployment Management
    url: /capabilities/software-release-deployment-management/
    via_parent: null
  fit: nearest
  layer: common
  why: self-update checks against releases
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: common
  why: error and performance monitoring
- capability:
    attribution: Turbo EA
    id: BC-430
    key: customer-service-management
    name: Customer Service Management
    url: /capabilities/customer-service-management/
    via_parent: null
  fit: exact
  layer: common
  why: in-app support chat
- capability:
    attribution: Turbo EA
    id: BC-3710.30
    key: asset-storage-tiering
    name: Asset Storage & Tiering
    url: /capabilities/asset-storage-tiering/
    via_parent: null
  fit: exact
  layer: common
  why: attachments/receipts storage
- capability:
    attribution: API Evangelist extension
    id: AE-160
    key: AE-160
    name: Application Identity & Verification
    url: /capabilities/application-identity-verification/
    via_parent: null
  fit: gap
  layer: common
  why: 'AE-160.10.30 Social & Federated Login: social login (dotted AE ids rejected by validator)'
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  fit: nearest
  layer: common
  why: attribution and social posting
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: exact
  layer: common
  why: mobile app analytics
- capability:
    attribution: API Evangelist extension
    id: AE-910
    key: AE-910
    name: Workflow Automation & iPaaS
    url: /capabilities/process-automation-governance/
    via_parent: Process Automation Governance
  fit: exact
  layer: common
  why: no-code automation into other tools
- capability:
    attribution: Turbo EA
    id: BC-4260.40
    key: customer-lifecycle-engagement
    name: Customer Lifecycle Engagement
    url: /capabilities/customer-lifecycle-engagement/
    via_parent: null
  fit: exact
  layer: common
  why: lifecycle messaging
stack:
- capabilities:
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
      - Maybe
      - YNAB
      band: exemplar
      in_catalog: true
      kin_score: 83.4
      mcp:
        source: https://plaid.com/docs/resources/mcp/
        status: verified
      name: Plaid
      slug: plaid
      sources:
      - https://github.com/maybe-finance/maybe/blob/main/app/models/provider/registry.rb
      - https://support.ynab.com/en_us/how-direct-import-works-H1IGYLgnxl.md
      status: profiled
      tags:
      - Bank Accounts
      - Finance
      - Fintech
      - Open Banking
      tier: observed
      url: /providers/plaid/
    - agent_band: agent-ready
      agent_readiness: 33.8
      apps:
      - Actual Budget
      - Firefly III
      band: developing
      in_catalog: true
      kin_score: 47.6
      mcp:
        status: none
      name: Akahu
      slug: akahu
      sources:
      - https://github.com/actualbudget/actual/tree/master/packages/sync-server/src
      - https://github.com/firefly-iii/data-importer/tree/main/app/Services
      status: profiled
      tags:
      - Company
      - Finance
      - New Zealand
      - Open Banking
      tier: observed
      url: /providers/akahu/
    - agent_band: agent-aware
      agent_readiness: 26.5
      apps:
      - Actual Budget
      - Firefly III
      band: developing
      in_catalog: true
      kin_score: 39.9
      mcp:
        status: none
      name: Enable Banking
      slug: enable-banking
      sources:
      - https://github.com/actualbudget/actual/tree/master/packages/sync-server/src
      - https://github.com/firefly-iii/data-importer/tree/main/app/Services
      status: profiled
      tags:
      - AISP
      - Open Banking
      - PISP
      - PSD2
      tier: observed
      url: /providers/enable-banking/
    - agent_band: human-only
      agent_readiness: 2.9
      apps:
      - Actual Budget
      - Firefly III
      band: minimal
      in_catalog: true
      kin_score: 9.9
      mcp:
        status: none
      name: SimpleFIN Bridge
      slug: simplefin
      sources:
      - https://github.com/actualbudget/actual/tree/master/packages/sync-server/src
      - https://github.com/firefly-iii/data-importer/tree/main/app/Services
      status: profiled
      tags:
      - Company
      - Data
      - Finance
      - Open Source
      tier: observed
      url: /providers/simplefin/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Actual Budget
      - Firefly III
      band: minimal
      in_catalog: true
      kin_score: 5.1
      mcp:
        source: https://github.com/gocardless/gc-mcp
        status: verified
      name: GoCardless Bank Account Data
      slug: nordigen
      sources:
      - https://github.com/actualbudget/actual/tree/master/packages/sync-server/src
      - https://github.com/firefly-iii/data-importer/tree/main/app/Services
      status: profiled
      tags:
      - Finance
      - Public APIs
      tier: observed
      url: /providers/nordigen/
    - agent_band: agent-ready
      agent_readiness: 59.4
      apps:
      - Actual Budget
      band: strong
      in_catalog: true
      kin_score: 61.7
      mcp:
        source: https://github.com/pluggyai/pluggy-mcp
        status: verified
      name: Pluggy
      slug: pluggy
      sources:
      - https://raw.githubusercontent.com/actualbudget/actual/master/packages/sync-server/package.json
      status: profiled
      tags:
      - Banking
      - Company
      - Financial Data
      - Open Finance
      tier: observed
      url: /providers/pluggy/
    - agent_band: agent-ready
      agent_readiness: 38.4
      apps:
      - Firefly III
      band: thin
      in_catalog: true
      kin_score: 33.1
      mcp:
        source: https://www.lunchflow.app/docs/guides/destinations/mcp
        status: verified
      name: Lunch Flow
      slug: lunch-flow
      sources:
      - https://github.com/firefly-iii/data-importer/tree/main/app/Services
      status: profiled
      tags:
      - Banking
      - Fintech
      - Integration
      - OpenAPI
      tier: observed
      url: /providers/lunch-flow/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Firefly III
      band: emerging
      in_catalog: true
      kin_score: 15.3
      mcp:
        source: https://sophtron.com/mcp-server/
        status: verified
      name: Sophtron
      slug: sophtron
      sources:
      - https://github.com/firefly-iii/data-importer/tree/main/app/Services
      status: profiled
      tags:
      - Banking
      - Data Aggregation
      - Financial Services
      - Fintech
      tier: observed
      url: /providers/sophtron/
    - agent_band: agent-aware
      agent_readiness: 26.7
      apps:
      - YNAB
      band: strong
      in_catalog: true
      kin_score: 65.0
      mcp:
        status: none
      name: MX
      slug: mx-technologies
      sources:
      - https://support.ynab.com/en_us/how-direct-import-works-H1IGYLgnxl.md
      status: profiled
      tags:
      - Account Aggregation
      - Data Connectivity
      - Financial Data
      - Open Banking
      tier: declared
      url: /providers/mx-technologies/
    - agent_band: agent-ready
      agent_readiness: 31.9
      apps:
      - YNAB
      band: strong
      in_catalog: true
      kin_score: 55.2
      mcp:
        status: none
      name: Apple (Apple Wallet)
      slug: apple
      sources:
      - https://support.ynab.com/en_us/how-direct-import-works-H1IGYLgnxl.md
      status: profiled
      tags:
      - Apple
      - Developers
      - iOS
      - macOS
      tier: declared
      url: /providers/apple/
    - agent_band: agent-aware
      agent_readiness: 22.4
      apps:
      - Wallet by BudgetBakers
      band: thin
      in_catalog: true
      kin_score: 26.9
      mcp:
        status: none
      name: Salt Edge
      slug: salt-edge
      sources:
      - https://budgetbakers.com/en/legal/saltedge-privacy/
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
      id: AE-230.20.20
      key: AE-230.20.20
      name: Securities Market Data
      url: /capabilities/market-financial-data/
      via_parent: Market & Financial Data
    providers:
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
      agent_readiness: 58.3
      apps:
      - Ghostfolio
      band: strong
      in_catalog: true
      kin_score: 62.2
      mcp:
        source: https://github.com/EodHistoricalData/EODHD-MCP-Server
        status: verified
      name: EODHD
      slug: eodhd
      sources:
      - https://github.com/ghostfolio/ghostfolio/tree/main/apps/api/src/services/data-provider
      status: profiled
      tags:
      - Finance
      - Market Data
      - Stock Options
      - Stocks
      tier: observed
      url: /providers/eodhd/
    - agent_band: agent-ready
      agent_readiness: 51.4
      apps:
      - Ghostfolio
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
      band: developing
      in_catalog: true
      kin_score: 52.0
      mcp:
        source: https://docs.coingecko.com/reference/mcp-server
        status: verified
      name: CoinGecko
      slug: coingecko
      sources:
      - https://github.com/ghostfolio/ghostfolio/tree/main/apps/api/src/services/data-provider
      status: profiled
      tags:
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
      band: developing
      in_catalog: true
      kin_score: 41.4
      mcp:
        status: none
      name: Yahoo Finance
      slug: yahoo
      sources:
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
      agent_readiness: 33.2
      apps:
      - Ghostfolio
      band: developing
      in_catalog: true
      kin_score: 41.3
      mcp:
        status: none
      name: RapidAPI
      slug: rapidapi
      sources:
      - https://github.com/ghostfolio/ghostfolio/tree/main/apps/api/src/services/data-provider
      status: profiled
      tags:
      - API Gateway
      - API Management
      - API Marketplace
      - API Testing
      tier: observed
      url: /providers/rapidapi/
    - agent_band: agent-aware
      agent_readiness: 26.4
      apps:
      - Ghostfolio
      band: thin
      in_catalog: true
      kin_score: 33.7
      mcp:
        status: none
      name: OpenFIGI
      slug: openfigi
      sources:
      - https://github.com/ghostfolio/ghostfolio/tree/main/apps/api/src/services/data-provider/data-enhancer
      status: profiled
      tags:
      - Finance
      - Instruments
      tier: observed
      url: /providers/openfigi/
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
  - capability:
      attribution: API Evangelist extension
      id: AE-230.20.10
      key: AE-230.20.10
      name: Exchange Rates
      url: /capabilities/market-financial-data/
      via_parent: Market & Financial Data
    providers:
    - agent_band: null
      agent_readiness: null
      apps:
      - Maybe
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Synth Finance
      slug: synth
      sources:
      - https://github.com/maybe-finance/maybe/blob/main/app/models/provider/registry.rb
      status: queued for profiling
      tags: []
      tier: observed
      url: null
  layer: domain
- capabilities:
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
      - Monarch Money
      - Wallet by BudgetBakers
      - YNAB
      band: developing
      in_catalog: true
      kin_score: 50.3
      mcp:
        source: https://firebase.google.com/docs/ai-assistance/mcp-server
        status: verified
      name: Firebase
      slug: firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.droid4you.application.wallet/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.monarchmoney.mobile/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.youneedabudget.evergreen.app/latest/
      status: profiled
      tags:
      - Application Development
      - Backend-as-a-Service
      - Company
      - Mobile
      tier: observed
      url: /providers/firebase/
    - agent_band: agent-ready
      agent_readiness: 56.7
      apps:
      - Monarch Money
      - YNAB
      band: strong
      in_catalog: true
      kin_score: 63.5
      mcp:
        source: https://amplitude.com/docs/amplitude-ai/amplitude-mcp
        status: verified
      name: Amplitude
      slug: amplitude
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.monarchmoney.mobile/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.youneedabudget.evergreen.app/latest/
      status: profiled
      tags:
      - A/B Testing
      - Analytics
      - Experimentation
      - Feature Flags
      tier: observed
      url: /providers/amplitude/
    - agent_band: agent-ready
      agent_readiness: 48.3
      apps:
      - Wallet by BudgetBakers
      band: strong
      in_catalog: true
      kin_score: 60.3
      mcp:
        source: https://docs.mixpanel.com/docs/features/mcp
        status: verified
      name: Mixpanel
      slug: mixpanel
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.droid4you.application.wallet/latest/
      status: profiled
      tags:
      - Analytics
      - Data Analysis
      - Event Tracking
      - Product Analytics
      tier: observed
      url: /providers/mixpanel/
    - agent_band: agent-aware
      agent_readiness: 26.8
      apps:
      - Monarch Money
      band: developing
      in_catalog: true
      kin_score: 43.8
      mcp:
        status: none
      name: Segment
      slug: segment
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.monarchmoney.mobile/latest/
      status: profiled
      tags:
      - CDP
      - Company
      - Customer Data Platform
      - Identity Resolution
      tier: observed
      url: /providers/segment/
    - agent_band: agent-ready
      agent_readiness: 30.6
      apps:
      - Monarch Money
      band: thin
      in_catalog: true
      kin_score: 37.1
      mcp:
        source: https://developer.fullstory.com/mcp/introduction/
        status: documented
      name: FullStory
      slug: fullstory
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.monarchmoney.mobile/latest/
      status: profiled
      tags:
      - Behavioral Analytics
      - Digital Experience
      - Product Analytics
      - Session Replay
      tier: observed
      url: /providers/fullstory/
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
      - Maybe
      - Monarch Money
      band: exemplar
      in_catalog: true
      kin_score: 80.6
      mcp:
        source: https://docs.sentry.io/product/sentry-mcp/
        status: verified
      name: Sentry
      slug: sentry-system
      sources:
      - https://raw.githubusercontent.com/maybe-finance/maybe/main/Gemfile
      - https://reports.exodus-privacy.eu.org/en/reports/com.monarchmoney.mobile/latest/
      status: profiled
      tags:
      - APM
      - Application Monitoring
      - Bug Tracking
      - Developer Tools
      tier: observed
      url: /providers/sentry-system/
    - agent_band: agent-ready
      agent_readiness: 53.1
      apps:
      - YNAB
      band: exemplar
      in_catalog: true
      kin_score: 78.5
      mcp:
        source: https://github.com/SmartBear/smartbear-mcp
        status: verified
      name: Bugsnag
      slug: bugsnag
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.youneedabudget.evergreen.app/latest/
      status: profiled
      tags:
      - Application Performance Monitoring
      - Error Monitoring
      - Monitoring
      - Observability
      tier: observed
      url: /providers/bugsnag/
    - agent_band: agent-ready
      agent_readiness: 58.0
      apps:
      - Maybe
      band: exemplar
      in_catalog: true
      kin_score: 70.2
      mcp:
        source: https://betterstack.com/docs/getting-started/integrations/mcp/
        status: documented
      name: Better Stack
      slug: betterstack
      sources:
      - https://raw.githubusercontent.com/maybe-finance/maybe/main/Gemfile
      status: profiled
      tags:
      - Incidents
      - Logs
      - Observability
      - Uptime Monitoring
      tier: observed
      url: /providers/betterstack/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Maybe
      band: emerging
      in_catalog: true
      kin_score: 17.8
      mcp:
        status: unknown
      name: Skylight
      slug: skylight
      sources:
      - https://raw.githubusercontent.com/maybe-finance/maybe/main/Gemfile
      status: profiled
      tags:
      - Monitoring
      - Performance
      - Ruby
      - Ruby on Rails
      tier: observed
      url: /providers/skylight/
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    providers:
    - agent_band: agent-aware
      agent_readiness: 28.2
      apps:
      - Monarch Money
      - Wallet by BudgetBakers
      band: developing
      in_catalog: true
      kin_score: 42.7
      mcp:
        status: none
      name: Facebook
      slug: facebook
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.droid4you.application.wallet/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.monarchmoney.mobile/latest/
      status: profiled
      tags:
      - Advertising
      - Content Publishing
      - Facebook
      - Fortune 500
      tier: observed
      url: /providers/facebook/
    - agent_band: agent-aware
      agent_readiness: 19.6
      apps:
      - Ghostfolio
      band: thin
      in_catalog: true
      kin_score: 36.8
      mcp:
        status: none
      name: Google sign-in
      slug: google-identity-platform
      sources:
      - https://raw.githubusercontent.com/ghostfolio/ghostfolio/main/package.json
      status: profiled
      tags:
      - Authentication
      - Google Cloud
      - Identity
      - Multi-Tenancy
      tier: observed
      url: /providers/google-identity-platform/
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
      - Maybe
      band: exemplar
      in_catalog: true
      kin_score: 81.5
      mcp:
        source: https://docs.stripe.com/mcp
        status: verified
      name: Stripe
      slug: stripe
      sources:
      - https://github.com/maybe-finance/maybe/blob/main/app/models/provider/registry.rb
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
      attribution: API Evangelist extension
      id: AE-150
      key: AE-150
      name: Application Communications
      url: /capabilities/application-communications/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 38.7
      apps:
      - Firefly III
      band: exemplar
      in_catalog: true
      kin_score: 74.7
      mcp:
        source: https://docs.slack.dev/ai/mcp-server/
        status: verified
      name: Slack
      slug: slack
      sources:
      - https://github.com/firefly-iii/firefly-iii/blob/main/app/Notifications/ReturnsAvailableChannels.php
      status: profiled
      tags:
      - Bots
      - Chat
      - Collaboration
      - Messaging
      tier: observed
      url: /providers/slack/
  - capability:
      attribution: Turbo EA
      id: BC-3710.30
      key: asset-storage-tiering
      name: Asset Storage & Tiering
      url: /capabilities/asset-storage-tiering/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 23.3
      apps:
      - Maybe
      band: exemplar
      in_catalog: true
      kin_score: 71.2
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon S3
      slug: amazon-s3
      sources:
      - https://raw.githubusercontent.com/maybe-finance/maybe/main/Gemfile
      status: profiled
      tags:
      - Amazon Web Services
      - Archives
      - Backup
      - Cloud Storage
      tier: observed
      url: /providers/amazon-s3/
  - capability:
      attribution: Turbo EA
      id: BC-4260.40
      key: customer-lifecycle-engagement
      name: Customer Lifecycle Engagement
      url: /capabilities/customer-lifecycle-engagement/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 66.2
      apps:
      - Wallet by BudgetBakers
      band: exemplar
      in_catalog: true
      kin_score: 68.5
      mcp:
        status: none
      name: MoEngage
      slug: moengage
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.droid4you.application.wallet/latest/
      status: profiled
      tags:
      - Customer Data Platform
      - Customer Engagement
      - Marketing Automation
      - Push Notifications
      tier: observed
      url: /providers/moengage/
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 31.7
      apps:
      - Maybe
      band: developing
      in_catalog: true
      kin_score: 52.5
      mcp:
        source: https://developers.intercom.com/docs/guides/mcp
        status: verified
      name: Intercom
      slug: intercom
      sources:
      - https://raw.githubusercontent.com/maybe-finance/maybe/main/Gemfile
      status: profiled
      tags:
      - Artificial Intelligence
      - Conversational AI
      - Customer Service
      - Messaging
      tier: observed
      url: /providers/intercom/
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 50.0
      apps:
      - Monarch Money
      band: exemplar
      in_catalog: true
      kin_score: 67.4
      mcp:
        status: none
      name: Singular
      slug: singular
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.monarchmoney.mobile/latest/
      status: profiled
      tags:
      - Attribution
      - Company
      - Marketing Analytics
      - Mobile Attribution
      tier: observed
      url: /providers/singular/
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    providers:
    - agent_band: agent-native
      agent_readiness: 58.4
      apps:
      - Maybe
      band: exemplar
      in_catalog: true
      kin_score: 81.8
      mcp:
        source: https://platform.openai.com/docs/mcp
        status: verified
      name: OpenAI
      slug: openai
      sources:
      - https://github.com/maybe-finance/maybe/blob/main/app/models/provider/registry.rb
      status: profiled
      tags:
      - Artificial Intelligence
      - Generative AI
      - LLM
      - OpenAI
      tier: observed
      url: /providers/openai/
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
      status: profiled
      tags:
      - Artificial Intelligence
      - Gateways
      - LLM
      - Router
      tier: observed
      url: /providers/openrouter/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.30
      key: AE-150.30
      name: Push Notifications
      url: /capabilities/push-notifications/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 22.0
      apps:
      - Firefly III
      band: thin
      in_catalog: true
      kin_score: 29.2
      mcp:
        status: none
      name: Pushover
      slug: pushover
      sources:
      - https://raw.githubusercontent.com/firefly-iii/firefly-iii/main/composer.json
      status: profiled
      tags:
      - Alerts
      - Messaging
      - Notification
      - Push Notifications
      tier: observed
      url: /providers/pushover/
  - capability:
      attribution: Turbo EA
      id: BC-400.60.40
      key: BC-400.60.40
      name: Social Media Management
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
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
      id: BC-4210
      key: software-release-deployment-management
      name: Software Release & Deployment Management
      url: /capabilities/software-release-deployment-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 63.4
      apps:
      - Maybe
      band: exemplar
      in_catalog: true
      kin_score: 85.4
      mcp:
        source: https://github.com/github/github-mcp-server
        status: verified
      name: GitHub
      slug: github
      sources:
      - https://github.com/maybe-finance/maybe/blob/main/app/models/provider/registry.rb
      status: profiled
      tags:
      - Code
      - Developer Tools
      - Pipelines
      - Platform
      tier: observed
      url: /providers/github/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.10
      key: AE-150.10.10
      name: Transactional Email
      url: /capabilities/email/
      via_parent: Email
    providers:
    - agent_band: agent-ready
      agent_readiness: 56.3
      apps:
      - Firefly III
      band: strong
      in_catalog: true
      kin_score: 59.5
      mcp:
        source: https://developers.mailersend.com/mcp-server.html
        status: verified
      name: MailerSend
      slug: mailersend
      sources:
      - https://raw.githubusercontent.com/firefly-iii/firefly-iii/main/composer.json
      status: profiled
      tags:
      - Email
      - Marketing
      - SMTP
      - Transactional Email
      tier: observed
      url: /providers/mailersend/
  - capability:
      attribution: API Evangelist extension
      id: AE-910
      key: AE-910
      name: Workflow Automation & iPaaS
      url: /capabilities/process-automation-governance/
      via_parent: Process Automation Governance
    providers:
    - agent_band: agent-ready
      agent_readiness: 66.2
      apps:
      - YNAB
      band: exemplar
      in_catalog: true
      kin_score: 72.0
      mcp:
        source: https://zapier.com/mcp
        status: verified
      name: Zapier
      slug: zapier
      sources:
      - https://api.ynab.com/
      status: profiled
      tags:
      - Integration
      - Workflow Automation
      - Zapier
      - iPaaS
      tier: declared
      url: /providers/zapier/
  layer: common
summary:
  coverage_pct: 97.8
  declared_only: 4
  distinct_providers: 45
  in_catalog: 44
  mcp:
    documented: 2
    none: 18
    unchecked: 1
    verified: 23
  mcp_verified: 23
  mean_kin_score: 52.7
  observed: 41
  queued: 1
  reference_apps: 7
title: 'Personal Finance & Budgeting: application blueprint'
---
