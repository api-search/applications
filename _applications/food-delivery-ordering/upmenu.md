---
app: UpMenu
app_slug: upmenu
app_url: https://www.upmenu.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-2420.40
  key: last-mile-delivery-operations-management
  layer: domain
  name: Last-Mile Delivery Operations Management
  providers:
  - DoorDash Drive
  - Glovo on Demand
  - Relay
  - ShipDay
  - Stuart
  - Uber Direct
  - Wolt Drive
  url: /capabilities/last-mile-delivery-operations-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-2320
  key: point-of-sale-operations-management
  layer: domain
  name: Point of Sale Operations Management
  providers:
  - Clover
  - Lightspeed
  - NCR Aloha
  - Oracle Simphony
  - Square
  - Toast
  url: /capabilities/point-of-sale-operations-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-140.30.10
  key: AE-140.30.10
  layer: common
  name: Buy Now, Pay Later
  providers:
  - Affirm
  - Afterpay
  - Klarna
  url: /capabilities/consumer-payment-options/
  via_parent: Consumer Payment Options
- attribution: Turbo EA
  id: BC-400.70
  key: content-marketing-management
  layer: common
  name: Content Marketing Management
  providers:
  - Duda
  - Squarespace
  - Wix
  - WordPress
  url: /capabilities/content-marketing-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-2120.40
  key: customer-information-consent-management
  layer: common
  name: Customer Information & Consent Management
  providers:
  - CookieYes
  url: /capabilities/customer-information-consent-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-140.30.20
  key: AE-140.30.20
  layer: common
  name: Digital & Mobile Wallets
  providers:
  - Apple Pay
  - Google Pay
  url: /capabilities/consumer-payment-options/
  via_parent: Consumer Payment Options
- attribution: Turbo EA
  id: BC-400.60
  key: digital-marketing-management
  layer: common
  name: Digital Marketing Management
  providers:
  - Meta
  url: /capabilities/digital-marketing-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: common
  name: Payment Processing Management
  providers:
  - Adyen
  - Bancontact
  - PayPal
  - PayU
  - Przelewy24
  - Stripe
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Google Analytics
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-911
  key: AE-911
  layer: common
  name: Tag Management
  providers:
  - Google Tag Manager
  url: /capabilities/product-telemetry-instrumentation/
  via_parent: Product Telemetry Instrumentation
category:
  id: food-delivery-ordering
  name: Food Delivery & Restaurant Ordering
  url: /applications/food-delivery-ordering/
counts:
  declared: 32
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.upmenu.com/integrations/
integrations:
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 42.8
    band: exemplar
    in_catalog: true
    kin_score: 73.6
    mcp: &id001
      source: https://github.com/Adyen/adyen-mcp
      status: verified
    slug: adyen
    status: profiled
    tags: &id002
    - Agentic Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/adyen/
  layer: common
  name: Adyen
  provider: adyen
  says: lists Adyen as an integration
  source: https://www.upmenu.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.30.10
    key: AE-140.30.10
    name: Buy Now, Pay Later
    url: /capabilities/consumer-payment-options/
    via_parent: Consumer Payment Options
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 34.5
    band: thin
    in_catalog: true
    kin_score: 33.8
    mcp: &id003
      status: none
    slug: affirm
    status: profiled
    tags: &id004
    - Buy Now Pay Later
    - Fintech
    - Lending
    - Payments
    url: /providers/affirm/
  layer: common
  name: Affirm
  provider: affirm
  says: lists Affirm as an integration
  source: https://www.upmenu.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.30.10
    key: AE-140.30.10
    name: Buy Now, Pay Later
    url: /capabilities/consumer-payment-options/
    via_parent: Consumer Payment Options
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 12.8
    band: minimal
    in_catalog: true
    kin_score: 9.2
    mcp: &id005
      status: none
    slug: afterpay
    status: profiled
    tags: &id006
    - Buy Now Pay Later
    - Consumer
    - Fintech
    - Payments
    url: /providers/afterpay/
  layer: common
  name: Afterpay
  provider: afterpay
  says: lists Afterpay as an integration
  source: https://www.upmenu.com/integrations/
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
    agent_readiness: 30.4
    band: developing
    in_catalog: true
    kin_score: 43.0
    mcp: &id007
      status: none
    slug: apple-pay
    status: profiled
    tags: &id008
    - Apple
    - Contactless Payments
    - Digital Wallet
    - E-Commerce
    url: /providers/apple-pay/
  layer: common
  name: Apple Pay
  provider: apple-pay
  says: lists Apple Pay as an integration
  source: https://www.upmenu.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 49.8
    band: strong
    in_catalog: true
    kin_score: 62.1
    mcp: &id009
      status: none
    slug: bancontact
    status: profiled
    tags: &id010
    - Banking
    - Belgium
    - Debit Cards
    - E-Commerce
    url: /providers/bancontact/
  layer: common
  name: Bancontact
  provider: bancontact
  says: lists Bancontact as an integration
  source: https://www.upmenu.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2320
    key: point-of-sale-operations-management
    name: Point of Sale Operations Management
    url: /capabilities/point-of-sale-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.1
    band: developing
    in_catalog: true
    kin_score: 41.3
    mcp: &id011
      status: none
    slug: clover
    status: profiled
    tags: &id012
    - Payments
    - Point-of-Sale
    - Restaurant
    - Retail
    url: /providers/clover/
  layer: domain
  name: Clover
  provider: clover
  says: lists Clover as an integration
  source: https://www.upmenu.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2120.40
    key: customer-information-consent-management
    name: Customer Information & Consent Management
    url: /capabilities/customer-information-consent-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 29.3
    band: thin
    in_catalog: true
    kin_score: 31.9
    mcp: &id013
      status: none
    slug: cookieyes
    status: profiled
    tags: &id014
    - Company
    - Consent Management
    - GDPR
    - Privacy
    url: /providers/cookieyes/
  layer: common
  name: CookieYes
  provider: cookieyes
  says: lists CookieYes as an integration
  source: https://www.upmenu.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2420.40
    key: last-mile-delivery-operations-management
    name: Last-Mile Delivery Operations Management
    url: /capabilities/last-mile-delivery-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id015
      status: unchecked
    slug: doordash-drive
    status: queued for profiling
    tags: &id016 []
    url: null
  layer: domain
  name: DoorDash Drive
  provider: doordash-drive
  says: lists DoorDash Drive as an integration
  source: https://www.upmenu.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-400.70
    key: content-marketing-management
    name: Content Marketing Management
    url: /capabilities/content-marketing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 29.7
    band: thin
    in_catalog: true
    kin_score: 35.5
    mcp: &id017
      source: https://developer.duda.co/docs/duda-mcp-server
      status: documented
    slug: duda
    status: profiled
    tags: &id018
    - Agencies
    - Software-as-a-Service
    - Website Builder
    - White Label
    url: /providers/duda/
  layer: common
  name: Duda
  provider: duda
  says: lists Duda as an integration
  source: https://www.upmenu.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2420.40
    key: last-mile-delivery-operations-management
    name: Last-Mile Delivery Operations Management
    url: /capabilities/last-mile-delivery-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id019
      status: unchecked
    slug: glovo
    status: queued for profiling
    tags: &id020 []
    url: null
  layer: domain
  name: Glovo on Demand
  provider: glovo
  says: lists Glovo on Demand as an integration
  source: https://www.upmenu.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 42.9
    band: exemplar
    in_catalog: true
    kin_score: 79.7
    mcp: &id021
      source: https://developers.google.com/analytics/devguides/MCP
      status: verified
    slug: google-analytics
    status: profiled
    tags: &id022
    - Analytics
    - Data
    - Google
    - Metrics
    url: /providers/google-analytics/
  layer: common
  name: Google Analytics
  provider: google-analytics
  says: lists Google Analytics as an integration
  source: https://www.upmenu.com/integrations/
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
    agent_readiness: 39.7
    band: strong
    in_catalog: true
    kin_score: 65.2
    mcp: &id023
      status: none
    slug: google-pay
    status: profiled
    tags: &id024
    - Agentic Commerce
    - Checkout
    - Contactless Payments
    - Digital Wallet
    url: /providers/google-pay/
  layer: common
  name: Google Pay
  provider: google-pay
  says: lists Google Pay as an integration
  source: https://www.upmenu.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-911
    key: AE-911
    name: Tag Management
    url: /capabilities/product-telemetry-instrumentation/
    via_parent: Product Telemetry Instrumentation
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 35.8
    band: strong
    in_catalog: true
    kin_score: 65.8
    mcp: &id025
      status: none
    slug: google-tag-manager
    status: profiled
    tags: &id026
    - Analytics
    - Conversion Tracking
    - Marketing
    - Tag Management
    url: /providers/google-tag-manager/
  layer: common
  name: Google Tag Manager
  provider: google-tag-manager
  says: lists Google Tag Manager as an integration
  source: https://www.upmenu.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.30.10
    key: AE-140.30.10
    name: Buy Now, Pay Later
    url: /capabilities/consumer-payment-options/
    via_parent: Consumer Payment Options
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 45.1
    band: exemplar
    in_catalog: true
    kin_score: 73.1
    mcp: &id027
      status: none
    slug: klarna
    status: profiled
    tags: &id028
    - Buy Now Pay Later
    - Cards
    - Fintech
    - Payments
    url: /providers/klarna/
  layer: common
  name: Klarna
  provider: klarna
  says: lists Klarna as an integration
  source: https://www.upmenu.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2320
    key: point-of-sale-operations-management
    name: Point of Sale Operations Management
    url: /capabilities/point-of-sale-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 42.1
    band: exemplar
    in_catalog: true
    kin_score: 84.5
    mcp: &id029
      status: none
    slug: lightspeed
    status: profiled
    tags: &id030
    - Commerce
    - Point-of-Sale
    - Restaurant
    - Retail
    url: /providers/lightspeed/
  layer: domain
  name: Lightspeed
  provider: lightspeed
  says: lists Lightspeed as an integration
  source: https://www.upmenu.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 28.1
    band: developing
    in_catalog: true
    kin_score: 43.7
    mcp: &id031
      status: none
    slug: facebook
    status: profiled
    tags: &id032
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
  layer: common
  name: Meta
  provider: facebook
  says: lists Meta as an integration
  source: https://www.upmenu.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2320
    key: point-of-sale-operations-management
    name: Point of Sale Operations Management
    url: /capabilities/point-of-sale-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 23.9
    band: thin
    in_catalog: true
    kin_score: 26.8
    mcp: &id033
      status: none
    slug: ncr
    status: profiled
    tags: &id034
    - Banking
    - Point-of-Sale
    - Restaurant
    - Retail
    url: /providers/ncr/
  layer: domain
  name: NCR Aloha
  provider: ncr
  says: lists NCR Aloha as an integration
  source: https://www.upmenu.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2320
    key: point-of-sale-operations-management
    name: Point of Sale Operations Management
    url: /capabilities/point-of-sale-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 59.8
    band: exemplar
    in_catalog: true
    kin_score: 70.4
    mcp: &id035
      source: https://github.com/oracle/mcp
      status: verified
    slug: oracle
    status: profiled
    tags: &id036
    - Cloud
    - Database
    - Enterprise
    - Oracle
    url: /providers/oracle/
  layer: domain
  name: Oracle Simphony
  provider: oracle
  says: lists Oracle Simphony as an integration
  source: https://www.upmenu.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 36.3
    band: strong
    in_catalog: true
    kin_score: 54.9
    mcp: &id037
      source: https://developer.paypal.com/tools/mcp-server/
      status: verified
    slug: paypal
    status: profiled
    tags: &id038
    - Billing
    - Commerce
    - Disputes
    - PayPal
    url: /providers/paypal/
  layer: common
  name: PayPal
  provider: paypal
  says: lists PayPal as an integration
  source: https://www.upmenu.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 30.2
    band: thin
    in_catalog: true
    kin_score: 38.9
    mcp: &id039
      source: https://github.com/payu-intrepos/payu-developer-mcp
      status: verified
    slug: payu
    status: profiled
    tags: &id040
    - Financial Services
    - Fintech
    - Payment Processing
    - Payments
    url: /providers/payu/
  layer: common
  name: PayU
  provider: payu
  says: lists PayU as an integration
  source: https://www.upmenu.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 26.3
    band: thin
    in_catalog: true
    kin_score: 36.9
    mcp: &id041
      status: none
    slug: przelewy24
    status: profiled
    tags: &id042
    - BLIK
    - Bank Transfers
    - Payment Gateway
    - Payments
    url: /providers/przelewy24/
  layer: common
  name: Przelewy24
  provider: przelewy24
  says: lists Przelewy24 as an integration
  source: https://www.upmenu.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2420.40
    key: last-mile-delivery-operations-management
    name: Last-Mile Delivery Operations Management
    url: /capabilities/last-mile-delivery-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id043
      status: unchecked
    slug: relay-delivery
    status: queued for profiling
    tags: &id044 []
    url: null
  layer: domain
  name: Relay
  provider: relay-delivery
  says: lists Relay as an integration
  source: https://www.upmenu.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2420.40
    key: last-mile-delivery-operations-management
    name: Last-Mile Delivery Operations Management
    url: /capabilities/last-mile-delivery-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 18.6
    band: thin
    in_catalog: true
    kin_score: 27.9
    mcp: &id045
      source: https://registry.modelcontextprotocol.io/v0/servers?search=com.shipday&limit=3
      status: verified
    slug: shipday
    status: profiled
    tags: &id046
    - Delivery
    - Last Mile Delivery
    - Local Delivery
    - Logistics
    url: /providers/shipday/
  layer: domain
  name: ShipDay
  provider: shipday
  says: lists ShipDay as an integration
  source: https://www.upmenu.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2320
    key: point-of-sale-operations-management
    name: Point of Sale Operations Management
    url: /capabilities/point-of-sale-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 61.5
    band: exemplar
    in_catalog: true
    kin_score: 78.2
    mcp: &id047
      source: https://developer.squareup.com/docs/mcp
      status: verified
    slug: square
    status: profiled
    tags: &id048
    - Booking
    - Location
    - Restaurant
    - Square
    url: /providers/square/
  layer: domain
  name: Square
  provider: square
  says: lists Square as an integration
  source: https://www.upmenu.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-400.70
    key: content-marketing-management
    name: Content Marketing Management
    url: /capabilities/content-marketing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 48.5
    band: exemplar
    in_catalog: true
    kin_score: 68.7
    mcp: &id049
      status: none
    slug: squarespace
    status: profiled
    tags: &id050
    - Commerce
    - E-Commerce
    - Marketing
    - Payments
    url: /providers/squarespace/
  layer: common
  name: Squarespace
  provider: squarespace
  says: lists Squarespace as an integration
  source: https://www.upmenu.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 57.6
    band: exemplar
    in_catalog: true
    kin_score: 82.0
    mcp: &id051
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id052
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
  layer: common
  name: Stripe
  provider: stripe
  says: lists Stripe as an integration
  source: https://www.upmenu.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2420.40
    key: last-mile-delivery-operations-management
    name: Last-Mile Delivery Operations Management
    url: /capabilities/last-mile-delivery-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id053
      status: unchecked
    slug: stuart
    status: queued for profiling
    tags: &id054 []
    url: null
  layer: domain
  name: Stuart
  provider: stuart
  says: lists Stuart as an integration
  source: https://www.upmenu.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2320
    key: point-of-sale-operations-management
    name: Point of Sale Operations Management
    url: /capabilities/point-of-sale-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.8
    band: exemplar
    in_catalog: true
    kin_score: 68.3
    mcp: &id055
      status: none
    slug: toast
    status: profiled
    tags: &id056
    - Food Service
    - Hospitality
    - Point-of-Sale
    - Restaurant
    url: /providers/toast/
  layer: domain
  name: Toast
  provider: toast
  says: lists Toast as an integration
  source: https://www.upmenu.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2420.40
    key: last-mile-delivery-operations-management
    name: Last-Mile Delivery Operations Management
    url: /capabilities/last-mile-delivery-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.6
    band: emerging
    in_catalog: true
    kin_score: 24.4
    mcp: &id057
      status: none
    slug: uber-direct
    status: profiled
    tags: &id058
    - Couriers
    - Fulfillment
    - Last Mile Delivery
    - Logistics
    url: /providers/uber-direct/
  layer: domain
  name: Uber Direct
  provider: uber-direct
  says: lists Uber Direct as an integration
  source: https://www.upmenu.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-400.70
    key: content-marketing-management
    name: Content Marketing Management
    url: /capabilities/content-marketing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 47.2
    band: thin
    in_catalog: true
    kin_score: 35.5
    mcp: &id059
      source: https://dev.wix.com/docs/sdk/articles/use-the-wix-mcp/about-the-wix-mcp
      status: verified
    slug: wix
    status: profiled
    tags: &id060
    - CMS
    - E-Commerce
    - Headless
    - Website Builder
    url: /providers/wix/
  layer: common
  name: Wix
  provider: wix
  says: lists Wix as an integration
  source: https://www.upmenu.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2420.40
    key: last-mile-delivery-operations-management
    name: Last-Mile Delivery Operations Management
    url: /capabilities/last-mile-delivery-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 26.2
    band: thin
    in_catalog: true
    kin_score: 38.0
    mcp: &id061
      status: none
    slug: wolt
    status: profiled
    tags: &id062
    - Company
    - Food Delivery
    - Last Mile Delivery
    - Marketplace
    url: /providers/wolt/
  layer: domain
  name: Wolt Drive
  provider: wolt
  says: lists Wolt Drive as an integration
  source: https://www.upmenu.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-400.70
    key: content-marketing-management
    name: Content Marketing Management
    url: /capabilities/content-marketing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.9
    band: developing
    in_catalog: true
    kin_score: 46.6
    mcp: &id063
      source: https://github.com/WordPress/mcp-adapter
      status: verified
    slug: wordpress
    status: profiled
    tags: &id064
    - CMS
    - Content Management
    - Open Source
    - WordPress
    url: /providers/wordpress/
  layer: common
  name: WordPress
  provider: wordpress
  says: lists WordPress as an integration
  source: https://www.upmenu.com/integrations/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/food-delivery-ordering/upmenu/
providers:
- agent_band: agent-native
  agent_readiness: 42.8
  band: exemplar
  in_catalog: true
  kin_score: 73.6
  mcp: *id001
  name: Adyen
  slug: adyen
  status: profiled
  tags: *id002
  url: /providers/adyen/
- agent_band: agent-ready
  agent_readiness: 34.5
  band: thin
  in_catalog: true
  kin_score: 33.8
  mcp: *id003
  name: Affirm
  slug: affirm
  status: profiled
  tags: *id004
  url: /providers/affirm/
- agent_band: agent-aware
  agent_readiness: 12.8
  band: minimal
  in_catalog: true
  kin_score: 9.2
  mcp: *id005
  name: Afterpay
  slug: afterpay
  status: profiled
  tags: *id006
  url: /providers/afterpay/
- agent_band: agent-ready
  agent_readiness: 30.4
  band: developing
  in_catalog: true
  kin_score: 43.0
  mcp: *id007
  name: Apple Pay
  slug: apple-pay
  status: profiled
  tags: *id008
  url: /providers/apple-pay/
- agent_band: agent-native
  agent_readiness: 49.8
  band: strong
  in_catalog: true
  kin_score: 62.1
  mcp: *id009
  name: Bancontact
  slug: bancontact
  status: profiled
  tags: *id010
  url: /providers/bancontact/
- agent_band: agent-ready
  agent_readiness: 33.1
  band: developing
  in_catalog: true
  kin_score: 41.3
  mcp: *id011
  name: Clover
  slug: clover
  status: profiled
  tags: *id012
  url: /providers/clover/
- agent_band: agent-ready
  agent_readiness: 29.3
  band: thin
  in_catalog: true
  kin_score: 31.9
  mcp: *id013
  name: CookieYes
  slug: cookieyes
  status: profiled
  tags: *id014
  url: /providers/cookieyes/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id015
  name: DoorDash Drive
  slug: doordash-drive
  status: queued for profiling
  tags: *id016
  url: null
- agent_band: agent-ready
  agent_readiness: 29.7
  band: thin
  in_catalog: true
  kin_score: 35.5
  mcp: *id017
  name: Duda
  slug: duda
  status: profiled
  tags: *id018
  url: /providers/duda/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id019
  name: Glovo on Demand
  slug: glovo
  status: queued for profiling
  tags: *id020
  url: null
- agent_band: agent-ready
  agent_readiness: 42.9
  band: exemplar
  in_catalog: true
  kin_score: 79.7
  mcp: *id021
  name: Google Analytics
  slug: google-analytics
  status: profiled
  tags: *id022
  url: /providers/google-analytics/
- agent_band: agent-ready
  agent_readiness: 39.7
  band: strong
  in_catalog: true
  kin_score: 65.2
  mcp: *id023
  name: Google Pay
  slug: google-pay
  status: profiled
  tags: *id024
  url: /providers/google-pay/
- agent_band: agent-ready
  agent_readiness: 35.8
  band: strong
  in_catalog: true
  kin_score: 65.8
  mcp: *id025
  name: Google Tag Manager
  slug: google-tag-manager
  status: profiled
  tags: *id026
  url: /providers/google-tag-manager/
- agent_band: agent-native
  agent_readiness: 45.1
  band: exemplar
  in_catalog: true
  kin_score: 73.1
  mcp: *id027
  name: Klarna
  slug: klarna
  status: profiled
  tags: *id028
  url: /providers/klarna/
- agent_band: agent-ready
  agent_readiness: 42.1
  band: exemplar
  in_catalog: true
  kin_score: 84.5
  mcp: *id029
  name: Lightspeed
  slug: lightspeed
  status: profiled
  tags: *id030
  url: /providers/lightspeed/
- agent_band: agent-aware
  agent_readiness: 28.1
  band: developing
  in_catalog: true
  kin_score: 43.7
  mcp: *id031
  name: Meta
  slug: facebook
  status: profiled
  tags: *id032
  url: /providers/facebook/
- agent_band: agent-aware
  agent_readiness: 23.9
  band: thin
  in_catalog: true
  kin_score: 26.8
  mcp: *id033
  name: NCR Aloha
  slug: ncr
  status: profiled
  tags: *id034
  url: /providers/ncr/
- agent_band: agent-ready
  agent_readiness: 59.8
  band: exemplar
  in_catalog: true
  kin_score: 70.4
  mcp: *id035
  name: Oracle Simphony
  slug: oracle
  status: profiled
  tags: *id036
  url: /providers/oracle/
- agent_band: agent-ready
  agent_readiness: 36.3
  band: strong
  in_catalog: true
  kin_score: 54.9
  mcp: *id037
  name: PayPal
  slug: paypal
  status: profiled
  tags: *id038
  url: /providers/paypal/
- agent_band: agent-ready
  agent_readiness: 30.2
  band: thin
  in_catalog: true
  kin_score: 38.9
  mcp: *id039
  name: PayU
  slug: payu
  status: profiled
  tags: *id040
  url: /providers/payu/
- agent_band: agent-aware
  agent_readiness: 26.3
  band: thin
  in_catalog: true
  kin_score: 36.9
  mcp: *id041
  name: Przelewy24
  slug: przelewy24
  status: profiled
  tags: *id042
  url: /providers/przelewy24/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id043
  name: Relay
  slug: relay-delivery
  status: queued for profiling
  tags: *id044
  url: null
- agent_band: agent-aware
  agent_readiness: 18.6
  band: thin
  in_catalog: true
  kin_score: 27.9
  mcp: *id045
  name: ShipDay
  slug: shipday
  status: profiled
  tags: *id046
  url: /providers/shipday/
- agent_band: agent-native
  agent_readiness: 61.5
  band: exemplar
  in_catalog: true
  kin_score: 78.2
  mcp: *id047
  name: Square
  slug: square
  status: profiled
  tags: *id048
  url: /providers/square/
- agent_band: agent-native
  agent_readiness: 48.5
  band: exemplar
  in_catalog: true
  kin_score: 68.7
  mcp: *id049
  name: Squarespace
  slug: squarespace
  status: profiled
  tags: *id050
  url: /providers/squarespace/
- agent_band: agent-native
  agent_readiness: 57.6
  band: exemplar
  in_catalog: true
  kin_score: 82.0
  mcp: *id051
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id052
  url: /providers/stripe/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id053
  name: Stuart
  slug: stuart
  status: queued for profiling
  tags: *id054
  url: null
- agent_band: agent-ready
  agent_readiness: 38.8
  band: exemplar
  in_catalog: true
  kin_score: 68.3
  mcp: *id055
  name: Toast
  slug: toast
  status: profiled
  tags: *id056
  url: /providers/toast/
- agent_band: agent-aware
  agent_readiness: 24.6
  band: emerging
  in_catalog: true
  kin_score: 24.4
  mcp: *id057
  name: Uber Direct
  slug: uber-direct
  status: profiled
  tags: *id058
  url: /providers/uber-direct/
- agent_band: agent-ready
  agent_readiness: 47.2
  band: thin
  in_catalog: true
  kin_score: 35.5
  mcp: *id059
  name: Wix
  slug: wix
  status: profiled
  tags: *id060
  url: /providers/wix/
- agent_band: agent-aware
  agent_readiness: 26.2
  band: thin
  in_catalog: true
  kin_score: 38.0
  mcp: *id061
  name: Wolt Drive
  slug: wolt
  status: profiled
  tags: *id062
  url: /providers/wolt/
- agent_band: agent-ready
  agent_readiness: 31.9
  band: developing
  in_catalog: true
  kin_score: 46.6
  mcp: *id063
  name: WordPress
  slug: wordpress
  status: profiled
  tags: *id064
  url: /providers/wordpress/
siblings:
- name: ChowNow
  rows: 12
  url: /applications/food-delivery-ordering/chownow/
- name: Enatega Multivendor
  rows: 11
  url: /applications/food-delivery-ordering/enatega-multivendor/
- name: Otter
  rows: 37
  url: /applications/food-delivery-ordering/otter/
- name: Shipday
  rows: 23
  url: /applications/food-delivery-ordering/shipday/
- name: TastyIgniter
  rows: 13
  url: /applications/food-delivery-ordering/tastyigniter/
sitemap: true
title: 'UpMenu: Food Delivery & Restaurant Ordering reference app'
---
