---
access: understanding
agent_layer:
- app: Thumbtack
  finding: public Thumbtack API and widgets for partners; no first-party MCP server (community thumbtack-mcp only, per mcp-registry)
  source: https://developers.thumbtack.com/
  tier: declared
apps:
- anchor: thumbtack
  counts:
    declared: 1
    observed: 5
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.thumbtack.consumer/latest/
  - route: documentation
    url: https://developers.thumbtack.com/
  - route: documentation
    url: https://www.thumbtack.com/privacy/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.thumbtack.consumer/latest/
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
    name: Facebook
    provider: facebook
    says: ships the Facebook SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.thumbtack.consumer/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: domain
    name: Facebook
    provider: facebook
    says: ships the Facebook SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.thumbtack.consumer/latest/
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
    name: Firebase
    provider: firebase
    says: ships the Firebase SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.thumbtack.consumer/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.thumbtack.consumer/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: common
    name: Google Analytics
    provider: google-analytics
    says: lists Google Analytics as an integration
    source: https://www.thumbtack.com/privacy/
    tier: declared
  kind: commercial
  name: Thumbtack
  page: /applications/home-services-marketplace/thumbtack/
  slug: thumbtack
  url: https://www.thumbtack.com/
- anchor: angi
  counts:
    declared: 0
    observed: 0
  evidence:
  - route: documentation
    url: https://www.angi.com/companylist/privacy.htm
  - route: integrations page
    url: https://www.angi.com/pro/integrations
  integrations: []
  kind: commercial
  name: Angi
  page: /applications/home-services-marketplace/angi/
  slug: angi
  url: https://www.angi.com/
- anchor: taskrabbit
  counts:
    declared: 1
    observed: 3
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.taskrabbit.droid.consumer/latest/
  - route: documentation
    url: https://support.taskrabbit.com/hc/en-us/articles/360008913792-Taskrabbit-s-Terms-of-Service
  - route: integrations page
    url: https://www.taskrabbit.com/ikea
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
    name: AppsFlyer
    provider: appsflyer
    says: ships the AppsFlyer SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.taskrabbit.droid.consumer/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.taskrabbit.droid.consumer/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.taskrabbit.droid.consumer/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-200.50.20
      key: AE-200.50.20
      name: Retail-Partner Installation & Assembly
      url: /capabilities/home-services/
      via_parent: Home Services
    credit: null
    layer: domain
    name: IKEA
    provider: ikea
    says: lists IKEA as an integration
    source: https://www.taskrabbit.com/ikea
    tier: declared
  kind: commercial
  name: Taskrabbit
  page: /applications/home-services-marketplace/taskrabbit/
  slug: taskrabbit
  url: https://www.taskrabbit.com/
- anchor: housecall-pro
  counts:
    declared: 15
    observed: 0
  evidence:
  - route: integrations page
    url: https://www.housecallpro.com/features/integrations/
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-200.50.10
      key: AE-200.50.10
      name: Home-Services Lead Marketplaces
      url: /capabilities/home-services/
      via_parent: Home Services
    credit: null
    layer: domain
    name: Angi
    provider: angi
    says: lists Angi as an integration
    source: https://www.housecallpro.com/features/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.60
      key: AE-140.60
      name: Reviews & Social Proof
      url: /capabilities/reviews-social-proof/
      via_parent: null
    credit: null
    layer: domain
    name: Broadly
    provider: broadly
    says: lists Broadly as an integration
    source: https://www.housecallpro.com/features/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.50.10
      key: AE-150.50.10
      name: Programmable Voice
      url: /capabilities/voice-telephony/
      via_parent: Voice & Telephony
    credit: null
    layer: common
    name: CallRail
    provider: callrail
    says: lists CallRail as an integration
    source: https://www.housecallpro.com/features/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30
      key: AE-170.30
      name: Photo & Image Libraries
      url: /capabilities/photo-image-libraries/
      via_parent: null
    credit: null
    layer: domain
    name: CompanyCam
    provider: companycam
    says: lists CompanyCam as an integration
    source: https://www.housecallpro.com/features/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.30.40
      key: AE-140.30.40
      name: Point-of-Service Consumer Financing
      url: /capabilities/consumer-payment-options/
      via_parent: Consumer Payment Options
    credit: null
    layer: domain
    name: Fundbox
    provider: fundbox
    says: lists Fundbox as an integration
    source: https://www.housecallpro.com/features/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-200.50.10
      key: AE-200.50.10
      name: Home-Services Lead Marketplaces
      url: /capabilities/home-services/
      via_parent: Home Services
    credit: null
    layer: domain
    name: Google Local Services
    provider: google-local-services
    says: lists Google Local Services as an integration
    source: https://www.housecallpro.com/features/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: common
    name: Gusto
    provider: gusto
    says: lists Gusto as an integration
    source: https://www.housecallpro.com/features/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    credit: null
    layer: common
    name: Intuit QuickBooks
    provider: quickbooks
    says: lists Intuit QuickBooks as an integration
    source: https://www.housecallpro.com/features/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: common
    name: Mailchimp
    provider: mailchimp
    says: lists Mailchimp as an integration
    source: https://www.housecallpro.com/features/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.60
      key: AE-140.60
      name: Reviews & Social Proof
      url: /capabilities/reviews-social-proof/
      via_parent: null
    credit: null
    layer: domain
    name: NiceJob
    provider: nicejob
    says: lists NiceJob as an integration
    source: https://www.housecallpro.com/features/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.60
      key: AE-140.60
      name: Reviews & Social Proof
      url: /capabilities/reviews-social-proof/
      via_parent: null
    credit: null
    layer: domain
    name: Podium
    provider: podium
    says: lists Podium as an integration
    source: https://www.housecallpro.com/features/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-200.50.10
      key: AE-200.50.10
      name: Home-Services Lead Marketplaces
      url: /capabilities/home-services/
      via_parent: Home Services
    credit: null
    layer: domain
    name: Thumbtack
    provider: thumbtack
    says: lists Thumbtack as an integration
    source: https://www.housecallpro.com/features/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.30.40
      key: AE-140.30.40
      name: Point-of-Service Consumer Financing
      url: /capabilities/consumer-payment-options/
      via_parent: Consumer Payment Options
    credit: null
    layer: domain
    name: Wisetack
    provider: wisetack
    says: lists Wisetack as an integration
    source: https://www.housecallpro.com/features/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-200.50.10
      key: AE-200.50.10
      name: Home-Services Lead Marketplaces
      url: /capabilities/home-services/
      via_parent: Home Services
    credit: null
    layer: domain
    name: Yelp
    provider: yelp
    says: lists Yelp as an integration
    source: https://www.housecallpro.com/features/integrations/
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
    source: https://www.housecallpro.com/features/integrations/
    tier: declared
  kind: commercial
  name: Housecall Pro
  page: /applications/home-services-marketplace/housecall-pro/
  slug: housecall-pro
  url: https://www.housecallpro.com/
- anchor: sharetribe-go
  counts:
    declared: 0
    observed: 13
  evidence:
  - route: dependency manifest
    url: https://github.com/sharetribe/sharetribe/blob/master/Gemfile
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: common
    name: Airbrake
    provider: airbrake
    says: ships the Airbrake SDK or integration code
    source: https://github.com/sharetribe/sharetribe/blob/master/Gemfile
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
    name: Amazon S3
    provider: amazon-s3
    says: ships the Amazon S3 SDK or integration code
    source: https://github.com/sharetribe/sharetribe/blob/master/Gemfile
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
    name: Amazon SES
    provider: amazon-ses
    says: ships the Amazon SES SDK or integration code
    source: https://github.com/sharetribe/sharetribe/blob/master/Gemfile
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
    name: Facebook
    provider: facebook
    says: ships the Facebook SDK or integration code
    source: https://github.com/sharetribe/sharetribe/blob/master/Gemfile
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-830.20.30
      key: BC-830.20.30
      name: Search and Discovery Management
      url: /capabilities/knowledge-curation-taxonomy-management/
      via_parent: Knowledge Curation & Taxonomy Management
    credit: null
    layer: common
    name: Flying Sphinx
    provider: flying-sphinx
    says: ships the Flying Sphinx SDK or integration code
    source: https://github.com/sharetribe/sharetribe/blob/master/Gemfile
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.70
      key: AE-160.70
      name: Bot Protection & CAPTCHA
      url: /capabilities/bot-protection-captcha/
      via_parent: null
    credit: null
    layer: common
    name: Google reCAPTCHA
    provider: google-recaptcha
    says: ships the Google reCAPTCHA SDK or integration code
    source: https://github.com/sharetribe/sharetribe/blob/master/Gemfile
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
    source: https://github.com/sharetribe/sharetribe/blob/master/Gemfile
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
    source: https://github.com/sharetribe/sharetribe/blob/master/Gemfile
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
    name: New Relic
    provider: new-relic
    says: ships the New Relic SDK or integration code
    source: https://github.com/sharetribe/sharetribe/blob/master/Gemfile
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
    name: PayPal
    provider: paypal
    says: ships the PayPal SDK or integration code
    source: https://github.com/sharetribe/sharetribe/blob/master/Gemfile
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Redis
    provider: redis
    says: ships the Redis SDK or integration code
    source: https://github.com/sharetribe/sharetribe/blob/master/Gemfile
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-830.20.30
      key: BC-830.20.30
      name: Search and Discovery Management
      url: /capabilities/knowledge-curation-taxonomy-management/
      via_parent: Knowledge Curation & Taxonomy Management
    credit: null
    layer: common
    name: Sphinx Search
    provider: sphinx-search
    says: ships the Sphinx Search SDK or integration code
    source: https://github.com/sharetribe/sharetribe/blob/master/Gemfile
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
    source: https://github.com/sharetribe/sharetribe/blob/master/Gemfile
    tier: observed
  kind: self-hosted
  name: Sharetribe Go
  page: /applications/home-services-marketplace/sharetribe-go/
  slug: sharetribe-go
  url: https://github.com/sharetribe/sharetribe
- anchor: sharetribe-web-template
  counts:
    declared: 0
    observed: 5
  evidence:
  - route: dependency manifest
    url: https://github.com/sharetribe/web-template/blob/main/package.json
  - route: source code
    url: https://github.com/sharetribe/web-template/blob/main/.env-template
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: common
    name: Facebook
    provider: facebook
    says: ships the Facebook SDK or integration code
    source: https://github.com/sharetribe/web-template/blob/main/package.json
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
    source: https://github.com/sharetribe/web-template/blob/main/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120.20.10
      key: AE-120.20.10
      name: Base Map Tiles
      url: /capabilities/maps-tiles/
      via_parent: Maps & Tiles
    credit: null
    layer: domain
    name: Mapbox
    provider: mapbox
    says: ships the Mapbox SDK or integration code
    source: https://github.com/sharetribe/web-template/blob/main/.env-template
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
    source: https://github.com/sharetribe/web-template/blob/main/package.json
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
    source: https://github.com/sharetribe/web-template/blob/main/.env-template
    tier: observed
  kind: open-source-saas
  name: Sharetribe Web Template
  page: /applications/home-services-marketplace/sharetribe-web-template/
  slug: sharetribe-web-template
  url: https://github.com/sharetribe/web-template
- anchor: cocorico
  counts:
    declared: 0
    observed: 7
  evidence:
  - route: dependency manifest
    url: https://github.com/Cocolabs-SAS/cocorico/blob/master/composer.json
  - route: source code
    url: https://github.com/Cocolabs-SAS/cocorico/blob/master/app/config/parameters.yml.dist
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: common
    name: Facebook
    provider: facebook
    says: ships the Facebook SDK or integration code
    source: https://github.com/Cocolabs-SAS/cocorico/blob/master/app/config/parameters.yml.dist
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: common
    name: Google Analytics
    provider: google-analytics
    says: ships the Google Analytics SDK or integration code
    source: https://github.com/Cocolabs-SAS/cocorico/blob/master/app/config/parameters.yml.dist
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120.40.10
      key: AE-120.40.10
      name: Place Search
      url: /capabilities/places-points-of-interest/
      via_parent: Places & Points of Interest
    credit: null
    layer: domain
    name: Google Places
    provider: google-places
    says: ships the Google Places SDK or integration code
    source: https://github.com/Cocolabs-SAS/cocorico/blob/master/app/config/parameters.yml.dist
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-911
      key: AE-911
      name: Tag Management
      url: /capabilities/product-telemetry-instrumentation/
      via_parent: Product Telemetry Instrumentation
    credit: null
    layer: common
    name: Google Tag Manager
    provider: google-tag-manager
    says: ships the Google Tag Manager SDK or integration code
    source: https://github.com/Cocolabs-SAS/cocorico/blob/master/app/config/parameters.yml.dist
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120.50.10
      key: AE-120.50.10
      name: IP Geolocation
      url: /capabilities/device-ip-location/
      via_parent: Device & IP Location
    credit: null
    layer: common
    name: IPInfoDB
    provider: ipinfodb
    says: ships the IPInfoDB SDK or integration code
    source: https://github.com/Cocolabs-SAS/cocorico/blob/master/app/config/parameters.yml.dist
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
    name: Mangopay
    provider: mangopay
    says: ships the Mangopay SDK or integration code
    source: https://github.com/Cocolabs-SAS/cocorico/blob/master/app/config/parameters.yml.dist
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.40.10
      key: AE-110.40.10
      name: Machine Translation
      url: /capabilities/language-document-understanding/
      via_parent: Language & Document Understanding
    credit: null
    layer: common
    name: Microsoft Translator
    provider: microsoft-translator
    says: ships the Microsoft Translator SDK or integration code
    source: https://github.com/Cocolabs-SAS/cocorico/blob/master/app/config/parameters.yml.dist
    tier: observed
  kind: self-hosted
  name: Cocorico
  page: /applications/home-services-marketplace/cocorico/
  slug: cocorico
  url: https://github.com/Cocolabs-SAS/cocorico
author: API Evangelist
candidates: []
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
html: public
id: home-services-marketplace
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Lifestyle
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: House & Home
  store: google-play
  url: https://play.google.com/store/apps/category/HOUSE_AND_HOME
- category: E-commerce
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#e-commerce
name: Home Services Marketplaces
needs:
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: exact
  layer: common
  why: named by Cocorico, Thumbtack
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  fit: exact
  layer: common
  why: named by Cocorico, Sharetribe Go, Sharetribe Web Template, Thumbtack
- capability:
    attribution: API Evangelist extension
    id: AE-200.50.20
    key: AE-200.50.20
    name: Retail-Partner Installation & Assembly
    url: /capabilities/home-services/
    via_parent: Home Services
  fit: exact
  layer: domain
  why: 'Retail-Partner Installation & Assembly: IKEA'
- capability:
    attribution: API Evangelist extension
    id: AE-200.50.10
    key: AE-200.50.10
    name: Home-Services Lead Marketplaces
    url: /capabilities/home-services/
    via_parent: Home Services
  fit: exact
  layer: domain
  why: pros receive marketplace leads (Thumbtack, Angi, Yelp, Google Local Services) inside their job software
- capability:
    attribution: API Evangelist extension
    id: AE-150.50.10
    key: AE-150.50.10
    name: Programmable Voice
    url: /capabilities/voice-telephony/
    via_parent: Voice & Telephony
  fit: nearest
  layer: common
  why: named by Housecall Pro
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.20
    key: AE-150.10.20
    name: Email Marketing Sends
    url: /capabilities/email/
    via_parent: Email
  fit: exact
  layer: common
  why: named by Housecall Pro
- capability:
    attribution: API Evangelist extension
    id: AE-910
    key: AE-910
    name: Workflow Automation & iPaaS
    url: /capabilities/process-automation-governance/
    via_parent: Process Automation Governance
  fit: exact
  layer: common
  why: named by Housecall Pro
- capability:
    attribution: Turbo EA
    id: BC-200.10
    key: general-ledger-management
    name: General Ledger Management
    url: /capabilities/general-ledger-management/
    via_parent: null
  fit: exact
  layer: common
  why: named by Housecall Pro
- capability:
    attribution: Turbo EA
    id: BC-300
    key: human-capital-management
    name: Human Capital Management
    url: /capabilities/human-capital-management/
    via_parent: null
  fit: exact
  layer: common
  why: named by Housecall Pro
- capability:
    attribution: API Evangelist extension
    id: AE-140.30.40
    key: AE-140.30.40
    name: Point-of-Service Consumer Financing
    url: /capabilities/consumer-payment-options/
    via_parent: Consumer Payment Options
  fit: exact
  layer: domain
  why: named by Housecall Pro
- capability:
    attribution: API Evangelist extension
    id: AE-170.30
    key: AE-170.30
    name: Photo & Image Libraries
    url: /capabilities/photo-image-libraries/
    via_parent: null
  fit: nearest
  layer: domain
  why: named by Housecall Pro
- capability:
    attribution: API Evangelist extension
    id: AE-140.60
    key: AE-140.60
    name: Reviews & Social Proof
    url: /capabilities/reviews-social-proof/
    via_parent: null
  fit: exact
  layer: domain
  why: named by Housecall Pro
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  fit: exact
  layer: common
  why: marketplace payouts and escrow (Stripe, PayPal, Mangopay)
- capability:
    attribution: Turbo EA
    id: BC-600.50.20
    key: BC-600.50.20
    name: Storage Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: named by Sharetribe Go
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.10
    key: AE-150.10.10
    name: Transactional Email
    url: /capabilities/email/
    via_parent: Email
  fit: exact
  layer: common
  why: named by Sharetribe Go
- capability:
    attribution: API Evangelist extension
    id: AE-915
    key: AE-915
    name: Managed Operational Databases
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: named by Sharetribe Go
- capability:
    attribution: Turbo EA
    id: BC-830.20.30
    key: BC-830.20.30
    name: Search and Discovery Management
    url: /capabilities/knowledge-curation-taxonomy-management/
    via_parent: Knowledge Curation & Taxonomy Management
  fit: exact
  layer: common
  why: named by Sharetribe Go
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: common
  why: named by Sharetribe Go, Sharetribe Web Template
- capability:
    attribution: API Evangelist extension
    id: AE-160.70
    key: AE-160.70
    name: Bot Protection & CAPTCHA
    url: /capabilities/bot-protection-captcha/
    via_parent: null
  fit: exact
  layer: common
  why: named by Sharetribe Go
- capability:
    attribution: Turbo EA
    id: BC-430
    key: customer-service-management
    name: Customer Service Management
    url: /capabilities/customer-service-management/
    via_parent: null
  fit: exact
  layer: common
  why: named by Sharetribe Go
- capability:
    attribution: API Evangelist extension
    id: AE-120.20.10
    key: AE-120.20.10
    name: Base Map Tiles
    url: /capabilities/maps-tiles/
    via_parent: Maps & Tiles
  fit: exact
  layer: domain
  why: named by Sharetribe Web Template
- capability:
    attribution: API Evangelist extension
    id: AE-110.40.10
    key: AE-110.40.10
    name: Machine Translation
    url: /capabilities/language-document-understanding/
    via_parent: Language & Document Understanding
  fit: exact
  layer: common
  why: named by Cocorico
- capability:
    attribution: API Evangelist extension
    id: AE-911
    key: AE-911
    name: Tag Management
    url: /capabilities/product-telemetry-instrumentation/
    via_parent: Product Telemetry Instrumentation
  fit: exact
  layer: common
  why: named by Cocorico
- capability:
    attribution: API Evangelist extension
    id: AE-120.40.10
    key: AE-120.40.10
    name: Place Search
    url: /capabilities/places-points-of-interest/
    via_parent: Places & Points of Interest
  fit: exact
  layer: domain
  why: named by Cocorico
- capability:
    attribution: API Evangelist extension
    id: AE-120.50.10
    key: AE-120.50.10
    name: IP Geolocation
    url: /capabilities/device-ip-location/
    via_parent: Device & IP Location
  fit: exact
  layer: common
  why: named by Cocorico
- capability:
    attribution: API Evangelist extension
    id: AE-170.50
    key: AE-170.50
    name: Social Networks & Community
    url: /capabilities/social-networks-community/
    via_parent: null
  fit: exact
  layer: domain
  why: 'the channels themselves: every app publishes to and reads from social networks (also hosts the social-listening gap rows)'
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
stack:
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-200.50.10
      key: AE-200.50.10
      name: Home-Services Lead Marketplaces
      url: /capabilities/home-services/
      via_parent: Home Services
    providers:
    - agent_band: agent-native
      agent_readiness: 46.7
      apps:
      - Housecall Pro
      band: exemplar
      in_catalog: true
      kin_score: 68.2
      mcp:
        source: https://github.com/Yelp/yelp-mcp
        status: verified
      name: Yelp
      slug: yelp
      sources:
      - https://www.housecallpro.com/features/integrations/
      status: profiled
      tags:
      - Business Data
      - Local Search
      - Restaurant
      - Reviews
      tier: declared
      url: /providers/yelp/
    - agent_band: agent-aware
      agent_readiness: 24.9
      apps:
      - Housecall Pro
      band: thin
      in_catalog: true
      kin_score: 29.8
      mcp:
        status: none
      name: Thumbtack
      slug: thumbtack
      sources:
      - https://www.housecallpro.com/features/integrations/
      status: profiled
      tags:
      - Home Services
      - Leads
      - Local Services
      - Marketplace
      tier: declared
      url: /providers/thumbtack/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Housecall Pro
      band: emerging
      in_catalog: true
      kin_score: 11.1
      mcp:
        status: none
      name: Angi
      slug: angi
      sources:
      - https://www.housecallpro.com/features/integrations/
      status: profiled
      tags:
      - Angie's List
      - Home Services
      - Leads
      - Marketplace
      tier: declared
      url: /providers/angi/
    - agent_band: null
      agent_readiness: null
      apps:
      - Housecall Pro
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Google Local Services
      slug: google-local-services
      sources:
      - https://www.housecallpro.com/features/integrations/
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-140.60
      key: AE-140.60
      name: Reviews & Social Proof
      url: /capabilities/reviews-social-proof/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 40.1
      apps:
      - Housecall Pro
      band: strong
      in_catalog: true
      kin_score: 59.1
      mcp:
        status: none
      name: Podium
      slug: podium
      sources:
      - https://www.housecallpro.com/features/integrations/
      status: profiled
      tags:
      - Customer Communication
      - Messaging
      - Payments
      - Reviews
      tier: declared
      url: /providers/podium/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Housecall Pro
      band: emerging
      in_catalog: true
      kin_score: 19.2
      mcp:
        status: none
      name: Broadly
      slug: broadly
      sources:
      - https://www.housecallpro.com/features/integrations/
      status: profiled
      tags:
      - AI Workforce
      - CRM
      - Local SEO
      - Reputation Management
      tier: declared
      url: /providers/broadly/
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - Housecall Pro
      band: emerging
      in_catalog: true
      kin_score: 18.4
      mcp:
        status: none
      name: NiceJob
      slug: nicejob
      sources:
      - https://www.housecallpro.com/features/integrations/
      status: profiled
      tags:
      - Artificial Intelligence
      - Reputation Marketing
      - Service Business
      - Software-as-a-Service
      tier: declared
      url: /providers/nicejob/
  - capability:
      attribution: API Evangelist extension
      id: AE-140.30.40
      key: AE-140.30.40
      name: Point-of-Service Consumer Financing
      url: /capabilities/consumer-payment-options/
      via_parent: Consumer Payment Options
    providers:
    - agent_band: agent-aware
      agent_readiness: 16.9
      apps:
      - Housecall Pro
      band: thin
      in_catalog: true
      kin_score: 34.9
      mcp:
        status: none
      name: Wisetack
      slug: wisetack
      sources:
      - https://www.housecallpro.com/features/integrations/
      status: profiled
      tags:
      - Company
      - Consumer Financing
      - Fintech
      - Lending
      tier: declared
      url: /providers/wisetack/
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - Housecall Pro
      band: minimal
      in_catalog: true
      kin_score: 10.1
      mcp:
        status: none
      name: Fundbox
      slug: fundbox
      sources:
      - https://www.housecallpro.com/features/integrations/
      status: profiled
      tags:
      - B2B Credit
      - Embedded Finance
      - Fintech
      - Net Terms
      tier: declared
      url: /providers/fundbox/
  - capability:
      attribution: API Evangelist extension
      id: AE-120.20.10
      key: AE-120.20.10
      name: Base Map Tiles
      url: /capabilities/maps-tiles/
      via_parent: Maps & Tiles
    providers:
    - agent_band: agent-ready
      agent_readiness: 45.2
      apps:
      - Sharetribe Web Template
      band: developing
      in_catalog: true
      kin_score: 50.7
      mcp:
        source: https://github.com/mapbox/mcp-server
        status: verified
      name: Mapbox
      slug: mapbox
      sources:
      - https://github.com/sharetribe/web-template/blob/main/.env-template
      status: profiled
      tags:
      - Geospatial
      - Location
      - Mapping
      - Maps
      tier: observed
      url: /providers/mapbox/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30
      key: AE-170.30
      name: Photo & Image Libraries
      url: /capabilities/photo-image-libraries/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 40.1
      apps:
      - Housecall Pro
      band: exemplar
      in_catalog: true
      kin_score: 70.3
      mcp:
        status: none
      name: CompanyCam
      slug: companycam
      sources:
      - https://www.housecallpro.com/features/integrations/
      status: profiled
      tags:
      - Company
      - Construction
      - Field Service Management
      - Photos
      tier: declared
      url: /providers/companycam/
  - capability:
      attribution: API Evangelist extension
      id: AE-120.40.10
      key: AE-120.40.10
      name: Place Search
      url: /capabilities/places-points-of-interest/
      via_parent: Places & Points of Interest
    providers:
    - agent_band: agent-ready
      agent_readiness: 40.3
      apps:
      - Cocorico
      band: strong
      in_catalog: true
      kin_score: 62.4
      mcp:
        source: https://developers.google.com/maps/ai/grounding-lite
        status: verified
      name: Google Places
      slug: google-places
      sources:
      - https://github.com/Cocolabs-SAS/cocorico/blob/master/app/config/parameters.yml.dist
      status: profiled
      tags:
      - Geolocation
      - Google
      - Location
      - Restaurant
      tier: observed
      url: /providers/google-places/
  - capability:
      attribution: API Evangelist extension
      id: AE-200.50.20
      key: AE-200.50.20
      name: Retail-Partner Installation & Assembly
      url: /capabilities/home-services/
      via_parent: Home Services
    providers:
    - agent_band: agent-aware
      agent_readiness: 26.0
      apps:
      - Taskrabbit
      band: thin
      in_catalog: true
      kin_score: 34.3
      mcp:
        status: none
      name: IKEA
      slug: ikea
      sources:
      - https://www.taskrabbit.com/ikea
      status: profiled
      tags:
      - Consumer Products
      - Home Furnishings
      - Open Source
      - Retail
      tier: declared
      url: /providers/ikea/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 28.1
      apps:
      - Thumbtack
      band: developing
      in_catalog: true
      kin_score: 43.7
      mcp: &id001
        status: none
      name: Facebook
      slug: facebook
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.thumbtack.consumer/latest/
      status: profiled
      tags: &id002
      - Advertising
      - Content Publishing
      - Facebook
      - Fortune 500
      tier: observed
      url: /providers/facebook/
  layer: domain
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    providers:
    - agent_band: agent-aware
      agent_readiness: 28.1
      apps:
      - Cocorico
      - Sharetribe Go
      - Sharetribe Web Template
      - Thumbtack
      band: developing
      in_catalog: true
      kin_score: 43.7
      mcp: *id001
      name: Facebook
      slug: facebook
      sources:
      - https://github.com/Cocolabs-SAS/cocorico/blob/master/app/config/parameters.yml.dist
      - https://github.com/sharetribe/sharetribe/blob/master/Gemfile
      - https://github.com/sharetribe/web-template/blob/main/package.json
      status: profiled
      tags: *id002
      tier: observed
      url: /providers/facebook/
    - agent_band: agent-ready
      agent_readiness: 33.7
      apps:
      - Sharetribe Go
      - Sharetribe Web Template
      band: strong
      in_catalog: true
      kin_score: 58.8
      mcp:
        status: none
      name: Google sign-in
      slug: google-identity-platform
      sources:
      - https://github.com/sharetribe/sharetribe/blob/master/Gemfile
      - https://github.com/sharetribe/web-template/blob/main/package.json
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
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 50.2
      apps:
      - Sharetribe Web Template
      band: exemplar
      in_catalog: true
      kin_score: 80.7
      mcp:
        source: https://docs.sentry.io/product/sentry-mcp/
        status: verified
      name: Sentry
      slug: sentry-system
      sources:
      - https://github.com/sharetribe/web-template/blob/main/package.json
      status: profiled
      tags:
      - APM
      - Application Monitoring
      - Bug Tracking
      - Developer Tools
      tier: observed
      url: /providers/sentry-system/
    - agent_band: agent-ready
      agent_readiness: 52.0
      apps:
      - Taskrabbit
      band: exemplar
      in_catalog: true
      kin_score: 76.3
      mcp:
        source: https://github.com/SmartBear/smartbear-mcp
        status: verified
      name: Bugsnag
      slug: bugsnag
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.taskrabbit.droid.consumer/latest/
      status: profiled
      tags:
      - Application Performance Monitoring
      - Error Monitoring
      - Monitoring
      - Observability
      tier: observed
      url: /providers/bugsnag/
    - agent_band: agent-ready
      agent_readiness: 44.8
      apps:
      - Sharetribe Go
      band: exemplar
      in_catalog: true
      kin_score: 74.4
      mcp:
        source: https://docs.newrelic.com/docs/agentic-ai/mcp/overview/
        status: verified
      name: New Relic
      slug: new-relic
      sources:
      - https://github.com/sharetribe/sharetribe/blob/master/Gemfile
      status: profiled
      tags:
      - APM
      - Analysis
      - Analytics
      - DevOps
      tier: observed
      url: /providers/new-relic/
    - agent_band: agent-ready
      agent_readiness: 39.9
      apps:
      - Thumbtack
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: &id003
        source: https://firebase.google.com/docs/ai-assistance/mcp-server
        status: verified
      name: Firebase
      slug: google-firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.thumbtack.consumer/latest/
      status: profiled
      tags: &id004
      - Analytics
      - Authentication
      - Backend-as-a-Service
      - Cloud Messaging
      tier: observed
      url: /providers/google-firebase/
    - agent_band: agent-aware
      agent_readiness: 18.6
      apps:
      - Sharetribe Go
      band: emerging
      in_catalog: true
      kin_score: 25.8
      mcp:
        status: none
      name: Airbrake
      slug: airbrake
      sources:
      - https://github.com/sharetribe/sharetribe/blob/master/Gemfile
      status: profiled
      tags:
      - Application Performance Monitoring
      - DevOps
      - Error Monitoring
      - Observability
      tier: observed
      url: /providers/airbrake/
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 42.9
      apps:
      - Cocorico
      - Thumbtack
      band: exemplar
      in_catalog: true
      kin_score: 79.7
      mcp:
        source: https://developers.google.com/analytics/devguides/MCP
        status: verified
      name: Google Analytics
      slug: google-analytics
      sources:
      - https://github.com/Cocolabs-SAS/cocorico/blob/master/app/config/parameters.yml.dist
      - https://www.thumbtack.com/privacy/
      status: profiled
      tags:
      - Analytics
      - Data
      - Google
      - Metrics
      tier: observed
      url: /providers/google-analytics/
    - agent_band: agent-ready
      agent_readiness: 39.9
      apps:
      - Taskrabbit
      - Thumbtack
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: *id003
      name: Firebase
      slug: google-firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.taskrabbit.droid.consumer/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.thumbtack.consumer/latest/
      status: profiled
      tags: *id004
      tier: observed
      url: /providers/google-firebase/
    - agent_band: agent-aware
      agent_readiness: 28.1
      apps:
      - Thumbtack
      band: developing
      in_catalog: true
      kin_score: 43.7
      mcp: *id001
      name: Facebook
      slug: facebook
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.thumbtack.consumer/latest/
      status: profiled
      tags: *id002
      tier: observed
      url: /providers/facebook/
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 57.6
      apps:
      - Sharetribe Go
      - Sharetribe Web Template
      band: exemplar
      in_catalog: true
      kin_score: 82.0
      mcp:
        source: https://docs.stripe.com/mcp
        status: verified
      name: Stripe
      slug: stripe
      sources:
      - https://github.com/sharetribe/sharetribe/blob/master/Gemfile
      - https://github.com/sharetribe/web-template/blob/main/.env-template
      status: profiled
      tags:
      - Commerce
      - Financial Services
      - Fintech
      - Payments
      tier: observed
      url: /providers/stripe/
    - agent_band: agent-ready
      agent_readiness: 36.3
      apps:
      - Sharetribe Go
      band: strong
      in_catalog: true
      kin_score: 54.9
      mcp:
        source: https://developer.paypal.com/tools/mcp-server/
        status: verified
      name: PayPal
      slug: paypal
      sources:
      - https://github.com/sharetribe/sharetribe/blob/master/Gemfile
      status: profiled
      tags:
      - Billing
      - Commerce
      - Disputes
      - PayPal
      tier: observed
      url: /providers/paypal/
    - agent_band: agent-ready
      agent_readiness: 40.3
      apps:
      - Cocorico
      band: thin
      in_catalog: true
      kin_score: 37.3
      mcp:
        status: none
      name: Mangopay
      slug: mangopay
      sources:
      - https://github.com/Cocolabs-SAS/cocorico/blob/master/app/config/parameters.yml.dist
      status: profiled
      tags:
      - Digital Wallet
      - KYC
      - Marketplace Payments
      - Payments
      tier: observed
      url: /providers/mangopay/
  - capability:
      attribution: Turbo EA
      id: BC-830.20.30
      key: BC-830.20.30
      name: Search and Discovery Management
      url: /capabilities/knowledge-curation-taxonomy-management/
      via_parent: Knowledge Curation & Taxonomy Management
    providers:
    - agent_band: agent-aware
      agent_readiness: 14.5
      apps:
      - Sharetribe Go
      band: thin
      in_catalog: true
      kin_score: 28.0
      mcp:
        status: unchecked
      name: Flying Sphinx
      slug: flying-sphinx
      sources:
      - https://github.com/sharetribe/sharetribe/blob/master/Gemfile
      status: profiled
      tags:
      - Addon
      - Heroku
      - Search
      - Sphinx
      tier: observed
      url: /providers/flying-sphinx/
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - Sharetribe Go
      band: emerging
      in_catalog: true
      kin_score: 11.7
      mcp:
        status: unchecked
      name: Sphinx Search
      slug: sphinx-search
      sources:
      - https://github.com/sharetribe/sharetribe/blob/master/Gemfile
      status: profiled
      tags:
      - Enterprise
      - Full-Text Search
      - Open Source
      - Search
      tier: observed
      url: /providers/sphinx-search/
  - capability:
      attribution: API Evangelist extension
      id: AE-160.70
      key: AE-160.70
      name: Bot Protection & CAPTCHA
      url: /capabilities/bot-protection-captcha/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.9
      apps:
      - Sharetribe Go
      band: strong
      in_catalog: true
      kin_score: 65.1
      mcp:
        status: none
      name: Google reCAPTCHA
      slug: google-recaptcha
      sources:
      - https://github.com/sharetribe/sharetribe/blob/master/Gemfile
      status: profiled
      tags:
      - Abuse Prevention
      - Bot Detection
      - CAPTCHA
      - Fraud Prevention
      tier: observed
      url: /providers/google-recaptcha/
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 32.5
      apps:
      - Sharetribe Go
      band: developing
      in_catalog: true
      kin_score: 51.0
      mcp:
        source: https://developers.intercom.com/docs/guides/mcp
        status: verified
      name: Intercom
      slug: intercom
      sources:
      - https://github.com/sharetribe/sharetribe/blob/master/Gemfile
      status: profiled
      tags:
      - Artificial Intelligence
      - Conversational AI
      - Customer Service
      - Messaging
      tier: observed
      url: /providers/intercom/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    providers:
    - agent_band: agent-ready
      agent_readiness: 41.9
      apps:
      - Housecall Pro
      band: exemplar
      in_catalog: true
      kin_score: 77.7
      mcp:
        status: none
      name: Mailchimp
      slug: mailchimp
      sources:
      - https://www.housecallpro.com/features/integrations/
      status: profiled
      tags:
      - Campaigns
      - Email Marketing
      - Marketing Automation
      - Newsletters
      tier: declared
      url: /providers/mailchimp/
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 38.3
      apps:
      - Housecall Pro
      band: strong
      in_catalog: true
      kin_score: 59.8
      mcp:
        source: https://github.com/intuit/quickbooks-online-mcp-server
        status: verified
      name: Intuit QuickBooks
      slug: quickbooks
      sources:
      - https://www.housecallpro.com/features/integrations/
      status: profiled
      tags:
      - Accounting
      - Bookkeeping
      - Finance
      - Small Business
      tier: declared
      url: /providers/quickbooks/
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 31.7
      apps:
      - Housecall Pro
      band: developing
      in_catalog: true
      kin_score: 44.9
      mcp:
        status: none
      name: Gusto
      slug: gusto
      sources:
      - https://www.housecallpro.com/features/integrations/
      status: profiled
      tags:
      - Benefits
      - Enterprise Software
      - Human Resources
      - Payroll
      tier: declared
      url: /providers/gusto/
  - capability:
      attribution: API Evangelist extension
      id: AE-120.50.10
      key: AE-120.50.10
      name: IP Geolocation
      url: /capabilities/device-ip-location/
      via_parent: Device & IP Location
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Cocorico
      band: minimal
      in_catalog: true
      kin_score: 4.3
      mcp:
        status: none
      name: IPInfoDB
      slug: ipinfodb
      sources:
      - https://github.com/Cocolabs-SAS/cocorico/blob/master/app/config/parameters.yml.dist
      status: profiled
      tags:
      - Geocoding
      - Public APIs
      tier: observed
      url: /providers/ipinfodb/
  - capability:
      attribution: API Evangelist extension
      id: AE-110.40.10
      key: AE-110.40.10
      name: Machine Translation
      url: /capabilities/language-document-understanding/
      via_parent: Language & Document Understanding
    providers:
    - agent_band: null
      agent_readiness: null
      apps:
      - Cocorico
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Microsoft Translator
      slug: microsoft-translator
      sources:
      - https://github.com/Cocolabs-SAS/cocorico/blob/master/app/config/parameters.yml.dist
      status: queued for profiling
      tags: []
      tier: observed
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 41.5
      apps:
      - Sharetribe Go
      band: developing
      in_catalog: true
      kin_score: 46.5
      mcp:
        source: https://github.com/redis/mcp-redis
        status: verified
      name: Redis
      slug: redis
      sources:
      - https://github.com/sharetribe/sharetribe/blob/master/Gemfile
      status: profiled
      tags:
      - Cache
      - Database
      - In-Memory
      - Key-Value Store
      tier: observed
      url: /providers/redis/
  - capability:
      attribution: API Evangelist extension
      id: AE-902
      key: AE-902
      name: Mobile Attribution & Deep Linking
      url: /capabilities/mobile-attribution-deep-linking/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 53.4
      apps:
      - Taskrabbit
      band: exemplar
      in_catalog: true
      kin_score: 72.1
      mcp:
        source: https://registry.modelcontextprotocol.io/v0/servers?search=appsflyer
        status: verified
      name: AppsFlyer
      slug: appsflyer
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.taskrabbit.droid.consumer/latest/
      status: profiled
      tags:
      - Company
      - Marketing Analytics
      - Mobile Attribution
      - Mobile Measurement
      tier: observed
      url: /providers/appsflyer/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.50.10
      key: AE-150.50.10
      name: Programmable Voice
      url: /capabilities/voice-telephony/
      via_parent: Voice & Telephony
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.9
      apps:
      - Housecall Pro
      band: developing
      in_catalog: true
      kin_score: 54.1
      mcp:
        status: none
      name: CallRail
      slug: callrail
      sources:
      - https://www.housecallpro.com/features/integrations/
      status: profiled
      tags:
      - Call Tracking
      - Conversation Intelligence
      - Lead Tracking
      - Marketing Attribution
      tier: declared
      url: /providers/callrail/
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.8
      apps:
      - Sharetribe Go
      band: exemplar
      in_catalog: true
      kin_score: 76.6
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon S3
      slug: amazon-s3
      sources:
      - https://github.com/sharetribe/sharetribe/blob/master/Gemfile
      status: profiled
      tags:
      - Amazon Web Services
      - Archives
      - Backup
      - Cloud Storage
      tier: observed
      url: /providers/amazon-s3/
  - capability:
      attribution: API Evangelist extension
      id: AE-911
      key: AE-911
      name: Tag Management
      url: /capabilities/product-telemetry-instrumentation/
      via_parent: Product Telemetry Instrumentation
    providers:
    - agent_band: agent-ready
      agent_readiness: 35.8
      apps:
      - Cocorico
      band: strong
      in_catalog: true
      kin_score: 65.8
      mcp:
        status: none
      name: Google Tag Manager
      slug: google-tag-manager
      sources:
      - https://github.com/Cocolabs-SAS/cocorico/blob/master/app/config/parameters.yml.dist
      status: profiled
      tags:
      - Analytics
      - Conversion Tracking
      - Marketing
      - Tag Management
      tier: observed
      url: /providers/google-tag-manager/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.10
      key: AE-150.10.10
      name: Transactional Email
      url: /capabilities/email/
      via_parent: Email
    providers:
    - agent_band: agent-ready
      agent_readiness: 38.0
      apps:
      - Sharetribe Go
      band: exemplar
      in_catalog: true
      kin_score: 83.8
      mcp:
        status: none
      name: Amazon SES
      slug: amazon-ses
      sources:
      - https://github.com/sharetribe/sharetribe/blob/master/Gemfile
      status: profiled
      tags:
      - Amazon Web Services
      - Email
      - Email Deliverability
      - Email Service
      tier: observed
      url: /providers/amazon-ses/
  - capability:
      attribution: API Evangelist extension
      id: AE-910
      key: AE-910
      name: Workflow Automation & iPaaS
      url: /capabilities/process-automation-governance/
      via_parent: Process Automation Governance
    providers:
    - agent_band: agent-ready
      agent_readiness: 66.1
      apps:
      - Housecall Pro
      band: exemplar
      in_catalog: true
      kin_score: 72.9
      mcp:
        source: https://zapier.com/mcp
        status: verified
      name: Zapier
      slug: zapier
      sources:
      - https://www.housecallpro.com/features/integrations/
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
  coverage_pct: 95.0
  declared_only: 16
  distinct_providers: 40
  in_catalog: 38
  mcp:
    documented: 0
    none: 20
    unchecked: 4
    verified: 16
  mcp_verified: 16
  mean_kin_score: 51.5
  observed: 24
  queued: 2
  reference_apps: 7
title: 'Home Services Marketplaces: application blueprint'
---
