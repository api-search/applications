---
app: ERPNext
app_slug: erpnext
app_url: https://github.com/frappe/erpnext
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-210.60
  key: bank-relationship-management
  layer: domain
  name: Bank Relationship Management
  providers:
  - Plaid
  url: /capabilities/bank-relationship-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-410.60
  key: channel-sales-management
  layer: domain
  name: Channel Sales Management
  providers:
  - Amazon Seller Central
  - Zenoti
  url: /capabilities/channel-sales-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-140.10.10
  key: AE-140.10.10
  layer: domain
  name: Hosted Storefronts
  providers:
  - Shopify
  url: /capabilities/storefront-platforms/
  via_parent: Storefront Platforms
- attribution: Turbo EA
  id: BC-520.40
  key: order-fulfilment-management
  layer: domain
  name: Order Fulfilment Management
  providers:
  - Unicommerce
  url: /capabilities/order-fulfilment-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: domain
  name: Payment Processing Management
  providers:
  - Braintree
  - GoCardless
  - M-Pesa
  - Paymob
  - PayPal
  - Paytm
  - Razorpay
  - Stripe
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-120.10.10
  key: AE-120.10.10
  layer: common
  name: Forward Geocoding
  providers:
  - Geoapify
  - HERE
  - Nominatim
  url: /capabilities/geocoding/
  via_parent: Geocoding
- attribution: API Evangelist extension
  id: AE-150.80
  key: AE-150.80
  layer: common
  name: Mailbox & Calendar Sync
  providers:
  - Google Calendar
  - Google Contacts
  url: /capabilities/mailbox-calendar-sync/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-160.10.30
  key: AE-160.10.30
  layer: common
  name: Social & Federated Login
  providers:
  - Facebook
  - GitHub
  - Google sign-in
  - Office 365 sign-in
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
- attribution: Turbo EA
  id: BC-4230.50
  key: tenant-identity-federation
  layer: common
  name: Tenant Identity Federation
  providers:
  - Keycloak
  - Salesforce sign-in
  url: /capabilities/tenant-identity-federation/
  via_parent: null
category:
  id: erp-operations
  name: ERP & Business Operations
  url: /applications/erp-operations/
counts:
  declared: 0
  observed: 24
credits: []
evidence:
- route: source code
  url: https://github.com/frappe/ecommerce_integrations/tree/main/ecommerce_integrations
- route: source code
  url: https://github.com/frappe/erpnext/tree/develop/erpnext/erpnext_integrations/doctype
- route: source code
  url: https://github.com/frappe/frappe/tree/develop/frappe/integrations/doctype
- route: source code
  url: https://github.com/frappe/payments/tree/develop/payments/payment_gateways/doctype
integrations:
- capability:
    attribution: Turbo EA
    id: BC-410.60
    key: channel-sales-management
    name: Channel Sales Management
    url: /capabilities/channel-sales-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 46.8
    band: developing
    in_catalog: true
    kin_score: 46.7
    mcp: &id001
      source: https://github.com/amzn/selling-partner-agentic-toolkit
      status: verified
    slug: amazon
    status: profiled
    tags: &id002
    - Advertising
    - Alexa
    - Amazon
    - E-Commerce
    url: /providers/amazon/
  layer: domain
  name: Amazon Seller Central
  provider: amazon
  says: ships the Amazon Seller Central SDK or integration code
  source: https://github.com/frappe/ecommerce_integrations/tree/main/ecommerce_integrations/amazon
  tier: observed
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
    agent_readiness: 52.0
    band: developing
    in_catalog: true
    kin_score: 46.2
    mcp: &id003
      status: none
    slug: braintree
    status: profiled
    tags: &id004
    - Mobile
    - Payments
    - Subscription
    - Transaction
    url: /providers/braintree/
  layer: domain
  name: Braintree
  provider: braintree
  says: ships the Braintree SDK or integration code
  source: https://github.com/frappe/payments/tree/develop/payments/payment_gateways/doctype/braintree_settings
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 28.2
    band: developing
    in_catalog: true
    kin_score: 42.7
    mcp: &id005
      status: none
    slug: facebook
    status: profiled
    tags: &id006
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
  layer: common
  name: Facebook
  provider: facebook
  says: ships the Facebook SDK or integration code
  source: https://github.com/frappe/frappe/tree/develop/frappe/integrations/doctype/social_login_key
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-120.10.10
    key: AE-120.10.10
    name: Forward Geocoding
    url: /capabilities/geocoding/
    via_parent: Geocoding
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 44.3
    band: strong
    in_catalog: true
    kin_score: 60.3
    mcp: &id007
      status: none
    slug: geoapify
    status: profiled
    tags: &id008
    - Geocoding
    - Geospatial
    - Location
    - Maps
    url: /providers/geoapify/
  layer: common
  name: Geoapify
  provider: geoapify
  says: ships the Geoapify SDK or integration code
  source: https://github.com/frappe/frappe/tree/develop/frappe/integrations/doctype/geolocation_settings
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 63.4
    band: exemplar
    in_catalog: true
    kin_score: 85.4
    mcp: &id009
      source: https://github.com/github/github-mcp-server
      status: verified
    slug: github
    status: profiled
    tags: &id010
    - Code
    - Developer Tools
    - Pipelines
    - Platform
    url: /providers/github/
  layer: common
  name: GitHub
  provider: github
  says: ships the GitHub SDK or integration code
  source: https://github.com/frappe/frappe/tree/develop/frappe/integrations/doctype/social_login_key
  tier: observed
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
    agent_readiness: 51.3
    band: developing
    in_catalog: true
    kin_score: 52.1
    mcp: &id011
      source: https://developer.gocardless.com/mcp
      status: verified
    slug: gocardless
    status: profiled
    tags: &id012
    - Bank Debit
    - Direct Debit
    - Payments
    - Recurring Payments
    url: /providers/gocardless/
  layer: domain
  name: GoCardless
  provider: gocardless
  says: ships the GoCardless SDK or integration code
  source: https://github.com/frappe/payments/tree/develop/payments/payment_gateways/doctype/gocardless_settings
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
    agent_band: agent-aware
    agent_readiness: 20.7
    band: developing
    in_catalog: true
    kin_score: 48.8
    mcp: &id013
      source: https://github.com/google/mcp
      status: verified
    slug: google-calendar
    status: profiled
    tags: &id014
    - Availability
    - Calendar
    - Event
    - Google
    url: /providers/google-calendar/
  layer: common
  name: Google Calendar
  provider: google-calendar
  says: ships the Google Calendar SDK or integration code
  source: https://github.com/frappe/frappe/tree/develop/frappe/integrations/doctype/google_calendar
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
    agent_band: agent-aware
    agent_readiness: 24.6
    band: developing
    in_catalog: true
    kin_score: 45.6
    mcp: &id015
      source: https://docs.cloud.google.com/mcp/supported-products
      status: verified
    slug: google-people
    status: profiled
    tags: &id016
    - Address Book
    - Contacts
    - Google
    - People
    url: /providers/google-people/
  layer: common
  name: Google Contacts
  provider: google-people
  says: ships the Google Contacts SDK or integration code
  source: https://github.com/frappe/frappe/tree/develop/frappe/integrations/doctype/google_contacts
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 19.6
    band: thin
    in_catalog: true
    kin_score: 36.8
    mcp: &id017
      status: none
    slug: google-identity-platform
    status: profiled
    tags: &id018
    - Authentication
    - Google Cloud
    - Identity
    - Multi-Tenancy
    url: /providers/google-identity-platform/
  layer: common
  name: Google sign-in
  provider: google-identity-platform
  says: ships the Google sign-in SDK or integration code
  source: https://github.com/frappe/frappe/tree/develop/frappe/integrations/doctype/social_login_key
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-120.10.10
    key: AE-120.10.10
    name: Forward Geocoding
    url: /capabilities/geocoding/
    via_parent: Geocoding
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 55.5
    band: exemplar
    in_catalog: true
    kin_score: 77.6
    mcp: &id019
      status: none
    slug: here
    status: profiled
    tags: &id020
    - Location
    - Mapping
    - Maps
    - Spatial
    url: /providers/here/
  layer: common
  name: HERE
  provider: here
  says: ships the HERE SDK or integration code
  source: https://github.com/frappe/frappe/tree/develop/frappe/integrations/doctype/geolocation_settings
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4230.50
    key: tenant-identity-federation
    name: Tenant Identity Federation
    url: /capabilities/tenant-identity-federation/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 17.6
    band: thin
    in_catalog: true
    kin_score: 35.3
    mcp: &id021
      status: none
    slug: keycloak
    status: profiled
    tags: &id022
    - Authentication
    - Authorization
    - Identity and Access Management
    - OAuth
    url: /providers/keycloak/
  layer: common
  name: Keycloak
  provider: keycloak
  says: ships the Keycloak SDK or integration code
  source: https://github.com/frappe/frappe/tree/develop/frappe/integrations/doctype/social_login_key
  tier: observed
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
    agent_readiness: 29.2
    band: developing
    in_catalog: true
    kin_score: 49.0
    mcp: &id023
      status: none
    slug: mpesa
    status: profiled
    tags: &id024
    - Fintech
    - Kenya
    - Mobile Money
    - Payments
    url: /providers/mpesa/
  layer: domain
  name: M-Pesa
  provider: mpesa
  says: ships the M-Pesa SDK or integration code
  source: https://github.com/frappe/payments/tree/develop/payments/payment_gateways/doctype/mpesa_settings
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-120.10.10
    key: AE-120.10.10
    name: Forward Geocoding
    url: /capabilities/geocoding/
    via_parent: Geocoding
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 19.9
    band: developing
    in_catalog: true
    kin_score: 42.4
    mcp: &id025
      status: none
    slug: nominatim
    status: profiled
    tags: &id026
    - Geocoding
    - Location Services
    - Maps
    - OpenStreetMap
    url: /providers/nominatim/
  layer: common
  name: Nominatim
  provider: nominatim
  says: ships the Nominatim SDK or integration code
  source: https://github.com/frappe/frappe/tree/develop/frappe/integrations/doctype/geolocation_settings
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.5
    band: exemplar
    in_catalog: true
    kin_score: 73.9
    mcp: &id027
      status: none
    slug: microsoft-entra
    status: profiled
    tags: &id028
    - Authentication
    - Azure AD
    - Entra
    - Identity and Access Management
    url: /providers/microsoft-entra/
  layer: common
  name: Office 365 sign-in
  provider: microsoft-entra
  says: ships the Office 365 sign-in SDK or integration code
  source: https://github.com/frappe/frappe/tree/develop/frappe/integrations/doctype/social_login_key
  tier: observed
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
    agent_readiness: 46.8
    band: developing
    in_catalog: true
    kin_score: 53.8
    mcp: &id029
      source: https://github.com/PaymobAccept/Paymob-AI-Integration-Skill
      status: documented
    slug: paymob
    status: profiled
    tags: &id030
    - Fintech
    - MENA
    - Payment Gateway
    - Payments
    url: /providers/paymob/
  layer: domain
  name: Paymob
  provider: paymob
  says: ships the Paymob SDK or integration code
  source: https://github.com/frappe/payments/tree/develop/payments/payment_gateways/doctype/paymob_settings
  tier: observed
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
    agent_readiness: 37.1
    band: strong
    in_catalog: true
    kin_score: 54.7
    mcp: &id031
      source: https://developer.paypal.com/tools/mcp-server/
      status: verified
    slug: paypal
    status: profiled
    tags: &id032
    - Billing
    - Commerce
    - Disputes
    - PayPal
    url: /providers/paypal/
  layer: domain
  name: PayPal
  provider: paypal
  says: ships the PayPal SDK or integration code
  source: https://github.com/frappe/payments/tree/develop/payments/payment_gateways/doctype/paypal_settings
  tier: observed
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
    agent_readiness: 23.8
    band: emerging
    in_catalog: true
    kin_score: 25.5
    mcp: &id033
      source: https://registry.modelcontextprotocol.io/v0/servers?search=paytm
      status: verified
    slug: paytm
    status: profiled
    tags: &id034
    - Payment Gateway
    - Payments
    - Payouts
    - UPI
    url: /providers/paytm/
  layer: domain
  name: Paytm
  provider: paytm
  says: ships the Paytm SDK or integration code
  source: https://github.com/frappe/payments/tree/develop/payments/payment_gateways/doctype/paytm_settings
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-210.60
    key: bank-relationship-management
    name: Bank Relationship Management
    url: /capabilities/bank-relationship-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 52.1
    band: exemplar
    in_catalog: true
    kin_score: 83.4
    mcp: &id035
      source: https://plaid.com/docs/resources/mcp/
      status: verified
    slug: plaid
    status: profiled
    tags: &id036
    - Bank Accounts
    - Finance
    - Fintech
    - Open Banking
    url: /providers/plaid/
  layer: domain
  name: Plaid
  provider: plaid
  says: ships the Plaid SDK or integration code
  source: https://github.com/frappe/erpnext/tree/develop/erpnext/erpnext_integrations/doctype/plaid_settings
  tier: observed
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
    agent_readiness: 26.8
    band: developing
    in_catalog: true
    kin_score: 52.4
    mcp: &id037
      source: https://github.com/razorpay/razorpay-mcp-server
      status: verified
    slug: razorpay
    status: profiled
    tags: &id038
    - Fintech
    - India
    - Payment Gateway
    - Payments
    url: /providers/razorpay/
  layer: domain
  name: Razorpay
  provider: razorpay
  says: ships the Razorpay SDK or integration code
  source: https://github.com/frappe/payments/tree/develop/payments/payment_gateways/doctype/razorpay_settings
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4230.50
    key: tenant-identity-federation
    name: Tenant Identity Federation
    url: /capabilities/tenant-identity-federation/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 54.7
    band: exemplar
    in_catalog: true
    kin_score: 90.6
    mcp: &id039
      source: https://github.com/salesforcecli/mcp
      status: verified
    slug: salesforce
    status: profiled
    tags: &id040
    - Analytics
    - Artificial Intelligence
    - Cloud
    - Fortune 500
    url: /providers/salesforce/
  layer: common
  name: Salesforce sign-in
  provider: salesforce
  says: ships the Salesforce sign-in SDK or integration code
  source: https://github.com/frappe/frappe/tree/develop/frappe/integrations/doctype/social_login_key
  tier: observed
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
    agent_readiness: 52.5
    band: exemplar
    in_catalog: true
    kin_score: 84.6
    mcp: &id041
      source: https://shopify.dev/docs/apps/build/devmcp
      status: verified
    slug: shopify
    status: profiled
    tags: &id042
    - Commerce
    - E-Commerce
    - Payments
    - Retail
    url: /providers/shopify/
  layer: domain
  name: Shopify
  provider: shopify
  says: ships the Shopify SDK or integration code
  source: https://github.com/frappe/ecommerce_integrations/tree/main/ecommerce_integrations/shopify
  tier: observed
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
    agent_readiness: 58.5
    band: exemplar
    in_catalog: true
    kin_score: 81.5
    mcp: &id043
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id044
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
  layer: domain
  name: Stripe
  provider: stripe
  says: ships the Stripe SDK or integration code
  source: https://github.com/frappe/payments/tree/develop/payments/payment_gateways/doctype/stripe_settings
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-520.40
    key: order-fulfilment-management
    name: Order Fulfilment Management
    url: /capabilities/order-fulfilment-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 14.4
    band: emerging
    in_catalog: true
    kin_score: 14.8
    mcp: &id045
      status: unknown
    slug: unicommerce
    status: profiled
    tags: &id046
    - Company
    - E-Commerce
    - Order Management
    - Software-as-a-Service
    url: /providers/unicommerce/
  layer: domain
  name: Unicommerce
  provider: unicommerce
  says: ships the Unicommerce SDK or integration code
  source: https://github.com/frappe/ecommerce_integrations/tree/main/ecommerce_integrations/unicommerce
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-410.60
    key: channel-sales-management
    name: Channel Sales Management
    url: /capabilities/channel-sales-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 22.7
    band: developing
    in_catalog: true
    kin_score: 48.5
    mcp: &id047
      status: none
    slug: zenoti
    status: profiled
    tags: &id048
    - Beauty
    - Company
    - Services
    - Wellness
    url: /providers/zenoti/
  layer: domain
  name: Zenoti
  provider: zenoti
  says: ships the Zenoti SDK or integration code
  source: https://github.com/frappe/ecommerce_integrations/tree/main/ecommerce_integrations/zenoti
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/erp-operations/erpnext/
providers:
- agent_band: agent-ready
  agent_readiness: 46.8
  band: developing
  in_catalog: true
  kin_score: 46.7
  mcp: *id001
  name: Amazon Seller Central
  slug: amazon
  status: profiled
  tags: *id002
  url: /providers/amazon/
- agent_band: agent-ready
  agent_readiness: 52.0
  band: developing
  in_catalog: true
  kin_score: 46.2
  mcp: *id003
  name: Braintree
  slug: braintree
  status: profiled
  tags: *id004
  url: /providers/braintree/
- agent_band: agent-aware
  agent_readiness: 28.2
  band: developing
  in_catalog: true
  kin_score: 42.7
  mcp: *id005
  name: Facebook
  slug: facebook
  status: profiled
  tags: *id006
  url: /providers/facebook/
- agent_band: agent-ready
  agent_readiness: 44.3
  band: strong
  in_catalog: true
  kin_score: 60.3
  mcp: *id007
  name: Geoapify
  slug: geoapify
  status: profiled
  tags: *id008
  url: /providers/geoapify/
- agent_band: agent-ready
  agent_readiness: 63.4
  band: exemplar
  in_catalog: true
  kin_score: 85.4
  mcp: *id009
  name: GitHub
  slug: github
  status: profiled
  tags: *id010
  url: /providers/github/
- agent_band: agent-ready
  agent_readiness: 51.3
  band: developing
  in_catalog: true
  kin_score: 52.1
  mcp: *id011
  name: GoCardless
  slug: gocardless
  status: profiled
  tags: *id012
  url: /providers/gocardless/
- agent_band: agent-aware
  agent_readiness: 20.7
  band: developing
  in_catalog: true
  kin_score: 48.8
  mcp: *id013
  name: Google Calendar
  slug: google-calendar
  status: profiled
  tags: *id014
  url: /providers/google-calendar/
- agent_band: agent-aware
  agent_readiness: 24.6
  band: developing
  in_catalog: true
  kin_score: 45.6
  mcp: *id015
  name: Google Contacts
  slug: google-people
  status: profiled
  tags: *id016
  url: /providers/google-people/
- agent_band: agent-aware
  agent_readiness: 19.6
  band: thin
  in_catalog: true
  kin_score: 36.8
  mcp: *id017
  name: Google sign-in
  slug: google-identity-platform
  status: profiled
  tags: *id018
  url: /providers/google-identity-platform/
- agent_band: agent-native
  agent_readiness: 55.5
  band: exemplar
  in_catalog: true
  kin_score: 77.6
  mcp: *id019
  name: HERE
  slug: here
  status: profiled
  tags: *id020
  url: /providers/here/
- agent_band: agent-aware
  agent_readiness: 17.6
  band: thin
  in_catalog: true
  kin_score: 35.3
  mcp: *id021
  name: Keycloak
  slug: keycloak
  status: profiled
  tags: *id022
  url: /providers/keycloak/
- agent_band: agent-ready
  agent_readiness: 29.2
  band: developing
  in_catalog: true
  kin_score: 49.0
  mcp: *id023
  name: M-Pesa
  slug: mpesa
  status: profiled
  tags: *id024
  url: /providers/mpesa/
- agent_band: agent-aware
  agent_readiness: 19.9
  band: developing
  in_catalog: true
  kin_score: 42.4
  mcp: *id025
  name: Nominatim
  slug: nominatim
  status: profiled
  tags: *id026
  url: /providers/nominatim/
- agent_band: agent-ready
  agent_readiness: 33.5
  band: exemplar
  in_catalog: true
  kin_score: 73.9
  mcp: *id027
  name: Office 365 sign-in
  slug: microsoft-entra
  status: profiled
  tags: *id028
  url: /providers/microsoft-entra/
- agent_band: agent-ready
  agent_readiness: 46.8
  band: developing
  in_catalog: true
  kin_score: 53.8
  mcp: *id029
  name: Paymob
  slug: paymob
  status: profiled
  tags: *id030
  url: /providers/paymob/
- agent_band: agent-ready
  agent_readiness: 37.1
  band: strong
  in_catalog: true
  kin_score: 54.7
  mcp: *id031
  name: PayPal
  slug: paypal
  status: profiled
  tags: *id032
  url: /providers/paypal/
- agent_band: agent-aware
  agent_readiness: 23.8
  band: emerging
  in_catalog: true
  kin_score: 25.5
  mcp: *id033
  name: Paytm
  slug: paytm
  status: profiled
  tags: *id034
  url: /providers/paytm/
- agent_band: agent-native
  agent_readiness: 52.1
  band: exemplar
  in_catalog: true
  kin_score: 83.4
  mcp: *id035
  name: Plaid
  slug: plaid
  status: profiled
  tags: *id036
  url: /providers/plaid/
- agent_band: agent-aware
  agent_readiness: 26.8
  band: developing
  in_catalog: true
  kin_score: 52.4
  mcp: *id037
  name: Razorpay
  slug: razorpay
  status: profiled
  tags: *id038
  url: /providers/razorpay/
- agent_band: agent-ready
  agent_readiness: 54.7
  band: exemplar
  in_catalog: true
  kin_score: 90.6
  mcp: *id039
  name: Salesforce sign-in
  slug: salesforce
  status: profiled
  tags: *id040
  url: /providers/salesforce/
- agent_band: agent-ready
  agent_readiness: 52.5
  band: exemplar
  in_catalog: true
  kin_score: 84.6
  mcp: *id041
  name: Shopify
  slug: shopify
  status: profiled
  tags: *id042
  url: /providers/shopify/
- agent_band: agent-native
  agent_readiness: 58.5
  band: exemplar
  in_catalog: true
  kin_score: 81.5
  mcp: *id043
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id044
  url: /providers/stripe/
- agent_band: agent-aware
  agent_readiness: 14.4
  band: emerging
  in_catalog: true
  kin_score: 14.8
  mcp: *id045
  name: Unicommerce
  slug: unicommerce
  status: profiled
  tags: *id046
  url: /providers/unicommerce/
- agent_band: agent-aware
  agent_readiness: 22.7
  band: developing
  in_catalog: true
  kin_score: 48.5
  mcp: *id047
  name: Zenoti
  slug: zenoti
  status: profiled
  tags: *id048
  url: /providers/zenoti/
siblings:
- name: Dolibarr
  rows: 13
  url: /applications/erp-operations/dolibarr/
- name: Fishbowl
  rows: 42
  url: /applications/erp-operations/fishbowl/
- name: Katana
  rows: 19
  url: /applications/erp-operations/katana/
- name: Odoo
  rows: 45
  url: /applications/erp-operations/odoo/
- name: Tryton
  rows: 13
  url: /applications/erp-operations/tryton/
sitemap: true
title: 'ERPNext: ERP & Business Operations reference app'
---
