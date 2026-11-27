---
app: Loyverse POS
app_slug: loyverse-pos
app_url: https://loyverse.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-140.30.20
  key: AE-140.30.20
  layer: domain
  name: Digital & Mobile Wallets
  providers:
  - Google Wallet
  url: /capabilities/consumer-payment-options/
  via_parent: Consumer Payment Options
- attribution: API Evangelist extension
  id: AE-140.100.20
  key: AE-140.100.20
  layer: domain
  name: Food Delivery
  providers:
  - Grab (GrabFood)
  - Otter (TryOtter)
  url: /capabilities/quick-local-commerce/
  via_parent: Quick & Local Commerce
- attribution: API Evangelist extension
  id: AE-140.10.10
  key: AE-140.10.10
  layer: domain
  name: Hosted Storefronts
  providers:
  - BigCommerce
  - Magento
  - Shopify
  - SKUPLUGS
  - Squarespace
  - Wix
  - WooCommerce
  url: /capabilities/storefront-platforms/
  via_parent: Storefront Platforms
- attribution: API Evangelist extension
  id: AE-140.80
  key: AE-140.80
  layer: domain
  name: Marketplaces
  providers:
  - Amazon
  - eBay
  - Lazada
  url: /capabilities/marketplaces/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-928
  key: AE-928
  layer: domain
  name: Parcel Rating & Label Purchase
  providers:
  - FedEx
  - UPS
  url: /capabilities/logistics-operations-management/
  via_parent: Logistics Operations Management
- attribution: Turbo EA
  id: BC-610.50
  key: analytics-bi-management
  layer: common
  name: Analytics & BI Management
  providers:
  - Dataddo
  url: /capabilities/analytics-bi-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-400.60
  key: digital-marketing-management
  layer: common
  name: Digital Marketing Management
  providers:
  - Facebook Analytics
  url: /capabilities/digital-marketing-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.10.20
  key: AE-150.10.20
  layer: common
  name: Email Marketing Sends
  providers:
  - Constant Contact
  - Mailchimp
  url: /capabilities/email/
  via_parent: Email
- attribution: Turbo EA
  id: BC-200.10
  key: general-ledger-management
  layer: common
  name: General Ledger Management
  providers:
  - Amaka
  - QuickBooks Online
  - Xero
  - Zoho Books
  url: /capabilities/general-ledger-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Google CrashLytics
  - Sentry
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - FullStory
  - Google Firebase Analytics
  - Mixpanel
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.20.20
  key: AE-150.20.20
  layer: common
  name: WhatsApp & OTT Messaging
  providers:
  - WhatsApp
  url: /capabilities/sms-messaging-apps/
  via_parent: SMS & Messaging Apps
- attribution: API Evangelist extension
  id: AE-910
  key: AE-910
  layer: common
  name: Workflow Automation & iPaaS
  providers:
  - Make
  - Workato
  - Zapier
  - Zoho Flow
  url: /capabilities/process-automation-governance/
  via_parent: Process Automation Governance
category:
  id: point-of-sale
  name: Point of Sale & In-Person Payments
  url: /applications/point-of-sale/
counts:
  declared: 27
  observed: 6
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.loyverse.sale/latest/
- route: integrations page
  url: https://loyverse.com/marketplace
integrations:
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-aware
    agent_readiness: 28.1
    band: developing
    in_catalog: true
    kin_score: 43.7
    mcp: &id014
      status: none
    slug: facebook
    status: profiled
    tags: &id015
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
  layer: common
  name: Facebook Analytics
  provider: facebook
  says: ships the Facebook Analytics SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.loyverse.sale/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-ready
    agent_readiness: 30.0
    band: thin
    in_catalog: true
    kin_score: 37.4
    mcp: &id018
      source: https://developer.fullstory.com/mcp/introduction/
      status: documented
    slug: fullstory
    status: profiled
    tags: &id019
    - Behavioral Analytics
    - Digital Experience
    - Product Analytics
    - Session Replay
    url: /providers/fullstory/
  layer: common
  name: FullStory
  provider: fullstory
  says: ships the FullStory SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.loyverse.sale/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts: &id001
    agent_band: agent-ready
    agent_readiness: 39.9
    band: strong
    in_catalog: true
    kin_score: 62.0
    mcp: &id020
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: google-firebase
    status: profiled
    tags: &id021
    - Analytics
    - Authentication
    - Backend-as-a-Service
    - Cloud Messaging
    url: /providers/google-firebase/
  layer: common
  name: Google CrashLytics
  provider: firebase
  says: ships the Google CrashLytics SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.loyverse.sale/latest/
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
  name: Google Firebase Analytics
  provider: firebase
  says: ships the Google Firebase Analytics SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.loyverse.sale/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-ready
    agent_readiness: 47.7
    band: strong
    in_catalog: true
    kin_score: 60.8
    mcp: &id034
      source: https://docs.mixpanel.com/docs/features/mcp
      status: verified
    slug: mixpanel
    status: profiled
    tags: &id035
    - Analytics
    - Data Analysis
    - Event Tracking
    - Product Analytics
    url: /providers/mixpanel/
  layer: common
  name: Mixpanel
  provider: mixpanel
  says: ships the Mixpanel SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.loyverse.sale/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-ready
    agent_readiness: 50.2
    band: exemplar
    in_catalog: true
    kin_score: 80.7
    mcp: &id040
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id041
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: common
  name: Sentry
  provider: sentry-system
  says: ships the Sentry SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.loyverse.sale/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-200.10
    key: general-ledger-management
    name: General Ledger Management
    url: /capabilities/general-ledger-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 25.5
    mcp: &id002
      status: unknown
    slug: amaka
    status: profiled
    tags: &id003
    - Accounting
    - Artificial Intelligence
    - Automation
    - Company
    url: /providers/amaka/
  layer: common
  name: Amaka
  provider: amaka
  says: lists Amaka as an integration
  source: https://loyverse.com/marketplace
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.80
    key: AE-140.80
    name: Marketplaces
    url: /capabilities/marketplaces/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 53.6
    band: strong
    in_catalog: true
    kin_score: 58.4
    mcp: &id004
      source: https://github.com/amzn/selling-partner-agentic-toolkit
      status: verified
    slug: amazon
    status: profiled
    tags: &id005
    - Advertising
    - Alexa
    - Amazon
    - E-Commerce
    url: /providers/amazon/
  layer: domain
  name: Amazon
  provider: amazon
  says: lists Amazon as an integration
  source: https://loyverse.com/marketplace
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.10.10
    key: AE-140.10.10
    name: Hosted Storefronts
    url: /capabilities/storefront-platforms/
    via_parent: Storefront Platforms
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 56.3
    band: exemplar
    in_catalog: true
    kin_score: 84.3
    mcp: &id006
      source: https://developer.bigcommerce.com/developer/docs/beta/store-management-mcp
      status: verified
    slug: bigcommerce
    status: profiled
    tags: &id007
    - Catalog
    - E-Commerce
    - Order
    - Retail
    url: /providers/bigcommerce/
  layer: domain
  name: BigCommerce
  provider: bigcommerce
  says: lists BigCommerce as an integration
  source: https://loyverse.com/marketplace
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.20
    key: AE-150.10.20
    name: Email Marketing Sends
    url: /capabilities/email/
    via_parent: Email
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.4
    band: exemplar
    in_catalog: true
    kin_score: 67.7
    mcp: &id008
      status: none
    slug: constant-contact
    status: profiled
    tags: &id009
    - Campaigns
    - Contacts
    - Email Marketing
    - Event
    url: /providers/constant-contact/
  layer: common
  name: Constant Contact
  provider: constant-contact
  says: lists Constant Contact as an integration
  source: https://loyverse.com/marketplace
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-610.50
    key: analytics-bi-management
    name: Analytics & BI Management
    url: /capabilities/analytics-bi-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 27.2
    band: developing
    in_catalog: true
    kin_score: 50.2
    mcp: &id010
      source: https://registry.modelcontextprotocol.io/v0/servers?search=dataddo
      status: verified
    slug: dataddo
    status: profiled
    tags: &id011
    - API Platform
    - Artificial Intelligence
    - Data Integration
    - Real-Time
    url: /providers/dataddo/
  layer: common
  name: Dataddo
  provider: dataddo
  says: lists Dataddo as an integration
  source: https://loyverse.com/marketplace
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.80
    key: AE-140.80
    name: Marketplaces
    url: /capabilities/marketplaces/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.3
    band: developing
    in_catalog: true
    kin_score: 48.7
    mcp: &id012
      source: https://github.com/eBay/npm-public-api-mcp
      status: verified
    slug: ebay
    status: profiled
    tags: &id013
    - Auctions
    - Commerce
    - Marketplace
    - Product
    url: /providers/ebay/
  layer: domain
  name: eBay
  provider: ebay
  says: lists eBay as an integration
  source: https://loyverse.com/marketplace
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-928
    key: AE-928
    name: Parcel Rating & Label Purchase
    url: /capabilities/logistics-operations-management/
    via_parent: Logistics Operations Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 35.2
    band: exemplar
    in_catalog: true
    kin_score: 70.7
    mcp: &id016
      status: none
    slug: fedex
    status: profiled
    tags: &id017
    - Address Validation
    - Freight
    - Logistics
    - Pickup
    url: /providers/fedex/
  layer: domain
  name: FedEx
  provider: fedex
  says: lists FedEx as an integration
  source: https://loyverse.com/marketplace
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.30.20
    key: AE-140.30.20
    name: Digital & Mobile Wallets
    url: /capabilities/consumer-payment-options/
    via_parent: Consumer Payment Options
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 40.5
    band: strong
    in_catalog: true
    kin_score: 61.3
    mcp: &id022
      source: https://developers.google.com/pay-wallet/ai-tools/mcp-server/mcp-server
      status: verified
    slug: google-wallet
    status: profiled
    tags: &id023
    - Digital Wallet
    - Google Wallet
    - Loyalty Cards
    - Mobile Payments
    url: /providers/google-wallet/
  layer: domain
  name: Google Wallet
  provider: google-wallet
  says: lists Google Wallet as an integration
  source: https://loyverse.com/marketplace
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.100.20
    key: AE-140.100.20
    name: Food Delivery
    url: /capabilities/quick-local-commerce/
    via_parent: Quick & Local Commerce
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 20.9
    band: thin
    in_catalog: true
    kin_score: 26.5
    mcp: &id024
      status: none
    slug: grab
    status: profiled
    tags: &id025
    - Digital Payments
    - Food Delivery
    - Last Mile Delivery
    - Ride Hailing
    url: /providers/grab/
  layer: domain
  name: Grab (GrabFood)
  provider: grab
  says: lists Grab (GrabFood) as an integration
  source: https://loyverse.com/marketplace
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.80
    key: AE-140.80
    name: Marketplaces
    url: /capabilities/marketplaces/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.6
    band: emerging
    in_catalog: true
    kin_score: 13.3
    mcp: &id026
      status: none
    slug: lazada
    status: profiled
    tags: &id027
    - Alibaba
    - E-Commerce
    - Marketplace
    - Southeast Asia
    url: /providers/lazada/
  layer: domain
  name: Lazada
  provider: lazada
  says: lists Lazada as an integration
  source: https://loyverse.com/marketplace
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.10.10
    key: AE-140.10.10
    name: Hosted Storefronts
    url: /capabilities/storefront-platforms/
    via_parent: Storefront Platforms
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 28.9
    band: thin
    in_catalog: true
    kin_score: 30.3
    mcp: &id028
      status: none
    slug: magento
    status: profiled
    tags: &id029
    - Catalog
    - E-Commerce
    - Headless Commerce
    - Magento
    url: /providers/magento/
  layer: domain
  name: Magento
  provider: magento
  says: lists Magento as an integration
  source: https://loyverse.com/marketplace
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.20
    key: AE-150.10.20
    name: Email Marketing Sends
    url: /capabilities/email/
    via_parent: Email
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 41.9
    band: exemplar
    in_catalog: true
    kin_score: 77.7
    mcp: &id030
      status: none
    slug: mailchimp
    status: profiled
    tags: &id031
    - Campaigns
    - Email Marketing
    - Marketing Automation
    - Newsletters
    url: /providers/mailchimp/
  layer: common
  name: Mailchimp
  provider: mailchimp
  says: lists Mailchimp as an integration
  source: https://loyverse.com/marketplace
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-910
    key: AE-910
    name: Workflow Automation & iPaaS
    url: /capabilities/process-automation-governance/
    via_parent: Process Automation Governance
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 43.0
    band: developing
    in_catalog: true
    kin_score: 43.4
    mcp: &id032
      source: https://github.com/integromat/make-mcp-server
      status: verified
    slug: make
    status: profiled
    tags: &id033
    - Automation
    - Integration
    - No-Code
    - iPaaS
    url: /providers/make/
  layer: common
  name: Make
  provider: make
  says: lists Make as an integration
  source: https://loyverse.com/marketplace
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.100.20
    key: AE-140.100.20
    name: Food Delivery
    url: /capabilities/quick-local-commerce/
    via_parent: Quick & Local Commerce
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 37.1
    band: thin
    in_catalog: true
    kin_score: 32.6
    mcp: &id036
      source: https://help.otter.ai/api/v2/help_center/en-us/articles/35287607569687.json
      status: verified
    slug: otter
    status: profiled
    tags: &id037
    - Delivery
    - Online Ordering
    - Order Management
    - Restaurant
    url: /providers/otter/
  layer: domain
  name: Otter (TryOtter)
  provider: otter
  says: lists Otter (TryOtter) as an integration
  source: https://loyverse.com/marketplace
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-200.10
    key: general-ledger-management
    name: General Ledger Management
    url: /capabilities/general-ledger-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.3
    band: strong
    in_catalog: true
    kin_score: 59.8
    mcp: &id038
      source: https://github.com/intuit/quickbooks-online-mcp-server
      status: verified
    slug: quickbooks
    status: profiled
    tags: &id039
    - Accounting
    - Bookkeeping
    - Finance
    - Small Business
    url: /providers/quickbooks/
  layer: common
  name: QuickBooks Online
  provider: quickbooks
  says: lists QuickBooks Online as an integration
  source: https://loyverse.com/marketplace
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.10.10
    key: AE-140.10.10
    name: Hosted Storefronts
    url: /capabilities/storefront-platforms/
    via_parent: Storefront Platforms
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 51.8
    band: exemplar
    in_catalog: true
    kin_score: 83.8
    mcp: &id042
      source: https://shopify.dev/docs/apps/build/devmcp
      status: verified
    slug: shopify
    status: profiled
    tags: &id043
    - Commerce
    - E-Commerce
    - Payments
    - Retail
    url: /providers/shopify/
  layer: domain
  name: Shopify
  provider: shopify
  says: lists Shopify as an integration
  source: https://loyverse.com/marketplace
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.10.10
    key: AE-140.10.10
    name: Hosted Storefronts
    url: /capabilities/storefront-platforms/
    via_parent: Storefront Platforms
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 18.3
    band: emerging
    in_catalog: true
    kin_score: 18.8
    mcp: &id044
      status: unknown
    slug: skuplugs
    status: profiled
    tags: &id045
    - E-Commerce
    - InventorySync
    - No-Code
    - POS Integration
    url: /providers/skuplugs/
  layer: domain
  name: SKUPLUGS
  provider: skuplugs
  says: lists SKUPLUGS as an integration
  source: https://loyverse.com/marketplace
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.10.10
    key: AE-140.10.10
    name: Hosted Storefronts
    url: /capabilities/storefront-platforms/
    via_parent: Storefront Platforms
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 48.5
    band: exemplar
    in_catalog: true
    kin_score: 68.7
    mcp: &id046
      status: none
    slug: squarespace
    status: profiled
    tags: &id047
    - Commerce
    - E-Commerce
    - Marketing
    - Payments
    url: /providers/squarespace/
  layer: domain
  name: Squarespace
  provider: squarespace
  says: lists Squarespace as an integration
  source: https://loyverse.com/marketplace
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-928
    key: AE-928
    name: Parcel Rating & Label Purchase
    url: /capabilities/logistics-operations-management/
    via_parent: Logistics Operations Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 29.2
    band: thin
    in_catalog: true
    kin_score: 27.9
    mcp: &id048
      source: https://github.com/UPS-API/ups-mcp
      status: verified
    slug: ups
    status: profiled
    tags: &id049
    - Fortune 500
    - Logistics
    - Shipping
    - Supply Chain
    url: /providers/ups/
  layer: domain
  name: UPS
  provider: ups
  says: lists UPS as an integration
  source: https://loyverse.com/marketplace
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.20
    key: AE-150.20.20
    name: WhatsApp & OTT Messaging
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 44.4
    band: exemplar
    in_catalog: true
    kin_score: 72.3
    mcp: &id050
      status: none
    slug: whatsapp
    status: profiled
    tags: &id051
    - Analytics
    - Business Messaging
    - Messaging
    - WhatsApp
    url: /providers/whatsapp/
  layer: common
  name: WhatsApp
  provider: whatsapp
  says: lists WhatsApp as an integration
  source: https://loyverse.com/marketplace
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.10.10
    key: AE-140.10.10
    name: Hosted Storefronts
    url: /capabilities/storefront-platforms/
    via_parent: Storefront Platforms
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 47.2
    band: thin
    in_catalog: true
    kin_score: 35.5
    mcp: &id052
      source: https://dev.wix.com/docs/sdk/articles/use-the-wix-mcp/about-the-wix-mcp
      status: verified
    slug: wix
    status: profiled
    tags: &id053
    - CMS
    - E-Commerce
    - Headless
    - Website Builder
    url: /providers/wix/
  layer: domain
  name: Wix
  provider: wix
  says: lists Wix as an integration
  source: https://loyverse.com/marketplace
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.10.10
    key: AE-140.10.10
    name: Hosted Storefronts
    url: /capabilities/storefront-platforms/
    via_parent: Storefront Platforms
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 34.7
    band: strong
    in_catalog: true
    kin_score: 54.6
    mcp: &id054
      source: https://developer.woocommerce.com/docs/features/mcp/
      status: verified
    slug: woocommerce
    status: profiled
    tags: &id055
    - E-Commerce
    - Open Source
    - Order
    - WooCommerce
    url: /providers/woocommerce/
  layer: domain
  name: WooCommerce
  provider: woocommerce
  says: lists WooCommerce as an integration
  source: https://loyverse.com/marketplace
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-910
    key: AE-910
    name: Workflow Automation & iPaaS
    url: /capabilities/process-automation-governance/
    via_parent: Process Automation Governance
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 53.8
    band: exemplar
    in_catalog: true
    kin_score: 70.5
    mcp: &id056
      source: https://docs.workato.com/mcp.html
      status: verified
    slug: workato
    status: profiled
    tags: &id057
    - AI Agents
    - API Management
    - Automation
    - B2B
    url: /providers/workato/
  layer: common
  name: Workato
  provider: workato
  says: lists Workato as an integration
  source: https://loyverse.com/marketplace
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-200.10
    key: general-ledger-management
    name: General Ledger Management
    url: /capabilities/general-ledger-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 60.0
    band: exemplar
    in_catalog: true
    kin_score: 87.1
    mcp: &id058
      source: https://github.com/XeroAPI/xero-mcp-server
      status: verified
    slug: xero
    status: profiled
    tags: &id059
    - Accounting
    - Bank Feeds
    - Finance
    - Financial Services
    url: /providers/xero/
  layer: common
  name: Xero
  provider: xero
  says: lists Xero as an integration
  source: https://loyverse.com/marketplace
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-910
    key: AE-910
    name: Workflow Automation & iPaaS
    url: /capabilities/process-automation-governance/
    via_parent: Process Automation Governance
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 66.1
    band: exemplar
    in_catalog: true
    kin_score: 72.9
    mcp: &id060
      source: https://zapier.com/mcp
      status: verified
    slug: zapier
    status: profiled
    tags: &id061
    - Integration
    - Workflow Automation
    - Zapier
    - iPaaS
    url: /providers/zapier/
  layer: common
  name: Zapier
  provider: zapier
  says: lists Zapier as an integration
  source: https://loyverse.com/marketplace
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-200.10
    key: general-ledger-management
    name: General Ledger Management
    url: /capabilities/general-ledger-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 18.6
    band: developing
    in_catalog: true
    kin_score: 47.5
    mcp: &id062
      source: https://www.zoho.com/mcp/
      status: documented
    slug: zoho-books
    status: profiled
    tags: &id063
    - Accounting
    - Bookkeeping
    - Expenses
    - Invoicing
    url: /providers/zoho-books/
  layer: common
  name: Zoho Books
  provider: zoho-books
  says: lists Zoho Books as an integration
  source: https://loyverse.com/marketplace
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-910
    key: AE-910
    name: Workflow Automation & iPaaS
    url: /capabilities/process-automation-governance/
    via_parent: Process Automation Governance
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id064
      status: unchecked
    slug: zoho-flow
    status: queued for profiling
    tags: &id065 []
    url: null
  layer: common
  name: Zoho Flow
  provider: zoho-flow
  says: lists Zoho Flow as an integration
  source: https://loyverse.com/marketplace
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/point-of-sale/loyverse-pos/
providers:
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 25.5
  mcp: *id002
  name: Amaka
  slug: amaka
  status: profiled
  tags: *id003
  url: /providers/amaka/
- agent_band: agent-native
  agent_readiness: 53.6
  band: strong
  in_catalog: true
  kin_score: 58.4
  mcp: *id004
  name: Amazon
  slug: amazon
  status: profiled
  tags: *id005
  url: /providers/amazon/
- agent_band: agent-ready
  agent_readiness: 56.3
  band: exemplar
  in_catalog: true
  kin_score: 84.3
  mcp: *id006
  name: BigCommerce
  slug: bigcommerce
  status: profiled
  tags: *id007
  url: /providers/bigcommerce/
- agent_band: agent-ready
  agent_readiness: 31.4
  band: exemplar
  in_catalog: true
  kin_score: 67.7
  mcp: *id008
  name: Constant Contact
  slug: constant-contact
  status: profiled
  tags: *id009
  url: /providers/constant-contact/
- agent_band: agent-aware
  agent_readiness: 27.2
  band: developing
  in_catalog: true
  kin_score: 50.2
  mcp: *id010
  name: Dataddo
  slug: dataddo
  status: profiled
  tags: *id011
  url: /providers/dataddo/
- agent_band: agent-ready
  agent_readiness: 31.3
  band: developing
  in_catalog: true
  kin_score: 48.7
  mcp: *id012
  name: eBay
  slug: ebay
  status: profiled
  tags: *id013
  url: /providers/ebay/
- agent_band: agent-aware
  agent_readiness: 28.1
  band: developing
  in_catalog: true
  kin_score: 43.7
  mcp: *id014
  name: Facebook Analytics
  slug: facebook
  status: profiled
  tags: *id015
  url: /providers/facebook/
- agent_band: agent-ready
  agent_readiness: 35.2
  band: exemplar
  in_catalog: true
  kin_score: 70.7
  mcp: *id016
  name: FedEx
  slug: fedex
  status: profiled
  tags: *id017
  url: /providers/fedex/
- agent_band: agent-ready
  agent_readiness: 30.0
  band: thin
  in_catalog: true
  kin_score: 37.4
  mcp: *id018
  name: FullStory
  slug: fullstory
  status: profiled
  tags: *id019
  url: /providers/fullstory/
- agent_band: agent-ready
  agent_readiness: 39.9
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id020
  name: Google CrashLytics
  slug: google-firebase
  status: profiled
  tags: *id021
  url: /providers/google-firebase/
- agent_band: agent-ready
  agent_readiness: 40.5
  band: strong
  in_catalog: true
  kin_score: 61.3
  mcp: *id022
  name: Google Wallet
  slug: google-wallet
  status: profiled
  tags: *id023
  url: /providers/google-wallet/
- agent_band: agent-aware
  agent_readiness: 20.9
  band: thin
  in_catalog: true
  kin_score: 26.5
  mcp: *id024
  name: Grab (GrabFood)
  slug: grab
  status: profiled
  tags: *id025
  url: /providers/grab/
- agent_band: human-only
  agent_readiness: 0.6
  band: emerging
  in_catalog: true
  kin_score: 13.3
  mcp: *id026
  name: Lazada
  slug: lazada
  status: profiled
  tags: *id027
  url: /providers/lazada/
- agent_band: agent-ready
  agent_readiness: 28.9
  band: thin
  in_catalog: true
  kin_score: 30.3
  mcp: *id028
  name: Magento
  slug: magento
  status: profiled
  tags: *id029
  url: /providers/magento/
- agent_band: agent-ready
  agent_readiness: 41.9
  band: exemplar
  in_catalog: true
  kin_score: 77.7
  mcp: *id030
  name: Mailchimp
  slug: mailchimp
  status: profiled
  tags: *id031
  url: /providers/mailchimp/
- agent_band: agent-ready
  agent_readiness: 43.0
  band: developing
  in_catalog: true
  kin_score: 43.4
  mcp: *id032
  name: Make
  slug: make
  status: profiled
  tags: *id033
  url: /providers/make/
- agent_band: agent-ready
  agent_readiness: 47.7
  band: strong
  in_catalog: true
  kin_score: 60.8
  mcp: *id034
  name: Mixpanel
  slug: mixpanel
  status: profiled
  tags: *id035
  url: /providers/mixpanel/
- agent_band: agent-ready
  agent_readiness: 37.1
  band: thin
  in_catalog: true
  kin_score: 32.6
  mcp: *id036
  name: Otter (TryOtter)
  slug: otter
  status: profiled
  tags: *id037
  url: /providers/otter/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: strong
  in_catalog: true
  kin_score: 59.8
  mcp: *id038
  name: QuickBooks Online
  slug: quickbooks
  status: profiled
  tags: *id039
  url: /providers/quickbooks/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.7
  mcp: *id040
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id041
  url: /providers/sentry-system/
- agent_band: agent-ready
  agent_readiness: 51.8
  band: exemplar
  in_catalog: true
  kin_score: 83.8
  mcp: *id042
  name: Shopify
  slug: shopify
  status: profiled
  tags: *id043
  url: /providers/shopify/
- agent_band: agent-aware
  agent_readiness: 18.3
  band: emerging
  in_catalog: true
  kin_score: 18.8
  mcp: *id044
  name: SKUPLUGS
  slug: skuplugs
  status: profiled
  tags: *id045
  url: /providers/skuplugs/
- agent_band: agent-native
  agent_readiness: 48.5
  band: exemplar
  in_catalog: true
  kin_score: 68.7
  mcp: *id046
  name: Squarespace
  slug: squarespace
  status: profiled
  tags: *id047
  url: /providers/squarespace/
- agent_band: agent-ready
  agent_readiness: 29.2
  band: thin
  in_catalog: true
  kin_score: 27.9
  mcp: *id048
  name: UPS
  slug: ups
  status: profiled
  tags: *id049
  url: /providers/ups/
- agent_band: agent-ready
  agent_readiness: 44.4
  band: exemplar
  in_catalog: true
  kin_score: 72.3
  mcp: *id050
  name: WhatsApp
  slug: whatsapp
  status: profiled
  tags: *id051
  url: /providers/whatsapp/
- agent_band: agent-ready
  agent_readiness: 47.2
  band: thin
  in_catalog: true
  kin_score: 35.5
  mcp: *id052
  name: Wix
  slug: wix
  status: profiled
  tags: *id053
  url: /providers/wix/
- agent_band: agent-ready
  agent_readiness: 34.7
  band: strong
  in_catalog: true
  kin_score: 54.6
  mcp: *id054
  name: WooCommerce
  slug: woocommerce
  status: profiled
  tags: *id055
  url: /providers/woocommerce/
- agent_band: agent-ready
  agent_readiness: 53.8
  band: exemplar
  in_catalog: true
  kin_score: 70.5
  mcp: *id056
  name: Workato
  slug: workato
  status: profiled
  tags: *id057
  url: /providers/workato/
- agent_band: agent-native
  agent_readiness: 60.0
  band: exemplar
  in_catalog: true
  kin_score: 87.1
  mcp: *id058
  name: Xero
  slug: xero
  status: profiled
  tags: *id059
  url: /providers/xero/
- agent_band: agent-ready
  agent_readiness: 66.1
  band: exemplar
  in_catalog: true
  kin_score: 72.9
  mcp: *id060
  name: Zapier
  slug: zapier
  status: profiled
  tags: *id061
  url: /providers/zapier/
- agent_band: agent-aware
  agent_readiness: 18.6
  band: developing
  in_catalog: true
  kin_score: 47.5
  mcp: *id062
  name: Zoho Books
  slug: zoho-books
  status: profiled
  tags: *id063
  url: /providers/zoho-books/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id064
  name: Zoho Flow
  slug: zoho-flow
  status: queued for profiling
  tags: *id065
  url: null
siblings:
- name: Lightspeed Restaurant
  rows: 16
  url: /applications/point-of-sale/lightspeed-restaurant/
- name: NexoPOS
  rows: 2
  url: /applications/point-of-sale/nexopos/
- name: Odoo Point of Sale
  rows: 16
  url: /applications/point-of-sale/odoo-point-of-sale/
- name: Open Source Point of Sale
  rows: 3
  url: /applications/point-of-sale/open-source-point-of-sale/
- name: Square Point of Sale
  rows: 28
  url: /applications/point-of-sale/square-point-of-sale/
sitemap: true
title: 'Loyverse POS: Point of Sale & In-Person Payments reference app'
---
