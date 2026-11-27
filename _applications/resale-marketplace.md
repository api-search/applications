---
access: understanding
agent_layer: []
apps:
- anchor: sharetribe-go
  counts:
    declared: 0
    observed: 11
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
    name: Facebook Login
    provider: facebook
    says: ships the Facebook Login SDK or integration code
    source: https://github.com/sharetribe/sharetribe/blob/master/Gemfile
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.70
      key: bot-protection-captcha
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
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: common
    name: LinkedIn sign-in
    provider: linkedin
    says: ships the LinkedIn sign-in SDK or integration code
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
    layer: domain
    name: PayPal
    provider: paypal
    says: ships the PayPal SDK or integration code
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
    layer: domain
    name: Stripe
    provider: stripe
    says: ships the Stripe SDK or integration code
    source: https://github.com/sharetribe/sharetribe/blob/master/Gemfile
    tier: observed
  kind: self-hosted
  name: Sharetribe Go
  page: /applications/resale-marketplace/sharetribe-go/
  slug: sharetribe-go
  url: https://github.com/sharetribe/sharetribe
- anchor: sharetribe-web-template
  counts:
    declared: 0
    observed: 6
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
    name: Facebook Login
    provider: facebook
    says: ships the Facebook Login SDK or integration code
    source: https://github.com/sharetribe/web-template/blob/main/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120
      key: location-mapping
      name: Location & Mapping
      url: /capabilities/location-mapping/
      via_parent: null
    credit: null
    layer: domain
    name: Google Maps Platform
    provider: google-maps
    says: ships the Google Maps Platform SDK or integration code
    source: https://github.com/sharetribe/web-template/blob/main/.env-template
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
      id: AE-120
      key: location-mapping
      name: Location & Mapping
      url: /capabilities/location-mapping/
      via_parent: null
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
    layer: domain
    name: Stripe
    provider: stripe
    says: ships the Stripe SDK or integration code
    source: https://github.com/sharetribe/web-template/blob/main/.env-template
    tier: observed
  kind: open-source-saas
  name: Sharetribe Web Template
  page: /applications/resale-marketplace/sharetribe-web-template/
  slug: sharetribe-web-template
  url: https://github.com/sharetribe/web-template
- anchor: sharetribe-(hosted)
  counts:
    declared: 11
    observed: 0
  evidence:
  - route: integrations page
    url: https://www.sharetribe.com/docs/concepts/integrations/integrations-introduction/
  integrations:
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
    source: https://www.sharetribe.com/docs/concepts/integrations/integrations-introduction/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.80
      key: mailbox-calendar-sync
      name: Mailbox & Calendar Sync
      url: /capabilities/mailbox-calendar-sync/
      via_parent: null
    credit: null
    layer: common
    name: Google Calendar
    provider: google-calendar
    says: lists Google Calendar as an integration
    source: https://www.sharetribe.com/docs/concepts/integrations/integrations-introduction/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: common
    name: Hotjar
    provider: hotjar
    says: lists Hotjar as an integration
    source: https://www.sharetribe.com/docs/concepts/integrations/integrations-introduction/
    tier: declared
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
    says: lists Intercom as an integration
    source: https://www.sharetribe.com/docs/concepts/integrations/integrations-introduction/
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
    source: https://www.sharetribe.com/docs/concepts/integrations/integrations-introduction/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: domain
    name: PayPal
    provider: paypal
    says: lists PayPal as an integration
    source: https://www.sharetribe.com/docs/concepts/integrations/integrations-introduction/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.40
      key: in-app-chat
      name: In-App Chat
      url: /capabilities/in-app-chat/
      via_parent: null
    credit: null
    layer: domain
    name: Sendbird
    provider: sendbird
    says: lists Sendbird as an integration
    source: https://www.sharetribe.com/docs/concepts/integrations/integrations-introduction/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Stripe
    provider: stripe
    says: lists Stripe as an integration
    source: https://www.sharetribe.com/docs/concepts/integrations/integrations-introduction/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20
      key: AE-150.20
      name: SMS & Messaging Apps
      url: /capabilities/sms-messaging-apps/
      via_parent: null
    credit: null
    layer: common
    name: Twilio
    provider: twilio
    says: lists Twilio as an integration
    source: https://www.sharetribe.com/docs/concepts/integrations/integrations-introduction/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-440.30
      key: discount-promotion-management
      name: Discount & Promotion Management
      url: /capabilities/discount-promotion-management/
      via_parent: null
    credit: null
    layer: domain
    name: Voucherify
    provider: voucherify
    says: lists Voucherify as an integration
    source: https://www.sharetribe.com/docs/concepts/integrations/integrations-introduction/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-910
      key: AE-910
      name: Workflow Automation & iPaaS
      url: /capabilities/process-automation-governance/
      via_parent: Process Automation Governance
    credit: null
    layer: domain
    name: Zapier
    provider: zapier
    says: lists Zapier as an integration
    source: https://www.sharetribe.com/docs/concepts/integrations/integrations-introduction/
    tier: declared
  kind: commercial
  name: Sharetribe (hosted)
  page: /applications/resale-marketplace/sharetribe-hosted/
  slug: sharetribe-hosted
  url: https://www.sharetribe.com/
- anchor: cocorico
  counts:
    declared: 0
    observed: 5
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
    name: Facebook Login
    provider: facebook
    says: ships the Facebook Login SDK or integration code
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
      id: AE-120
      key: location-mapping
      name: Location & Mapping
      url: /capabilities/location-mapping/
      via_parent: null
    credit: null
    layer: domain
    name: Google Maps Platform
    provider: google-maps
    says: ships the Google Maps Platform SDK or integration code
    source: https://github.com/Cocolabs-SAS/cocorico/blob/master/composer.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: domain
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
  page: /applications/resale-marketplace/cocorico/
  slug: cocorico
  url: https://github.com/Cocolabs-SAS/cocorico
- anchor: vinted
  counts:
    declared: 0
    observed: 25
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/fr.vinted/latest/
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: AdColony
    provider: adcolony
    says: ships the AdColony SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/fr.vinted/latest/
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
    name: Adjust
    provider: adjust
    says: ships the Adjust SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/fr.vinted/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Amazon
    provider: amazon
    says: ships the Amazon SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/fr.vinted/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: AppLovin
    provider: applovin
    says: ships the AppLovin SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/fr.vinted/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: BidMachine
    provider: bidmachine-io
    says: ships the BidMachine SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/fr.vinted/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Chartboost
    provider: chartboost
    says: ships the Chartboost SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/fr.vinted/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Digital Turbine (Fyber)
    provider: digital-turbine
    says: ships the Digital Turbine (Fyber) SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/fr.vinted/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Facebook
    provider: facebook
    says: ships the Facebook SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/fr.vinted/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/fr.vinted/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/fr.vinted/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/fr.vinted/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/fr.vinted/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Google AdMob
    provider: google-admob
    says: ships the Google AdMob SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/fr.vinted/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-3760.30
      key: programmatic-sales-management
      name: Programmatic Sales Management
      url: /capabilities/programmatic-sales-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: IAB Open Measurement
    provider: iab-tech-lab
    says: ships the IAB Open Measurement SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/fr.vinted/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: InMobi
    provider: inmobi
    says: ships the InMobi SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/fr.vinted/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: ironSource
    provider: ironsource
    says: ships the ironSource SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/fr.vinted/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Mintegral
    provider: mintegral
    says: ships the Mintegral SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/fr.vinted/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-420.10
      key: customer-data-management
      name: Customer Data Management
      url: /capabilities/customer-data-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: mParticle
    provider: mparticle
    says: ships the mParticle SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/fr.vinted/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: myTarget
    provider: mytarget
    says: ships the myTarget SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/fr.vinted/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Pangle
    provider: pangle
    says: ships the Pangle SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/fr.vinted/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-3760.30
      key: programmatic-sales-management
      name: Programmatic Sales Management
      url: /capabilities/programmatic-sales-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Prebid Mobile
    provider: prebid
    says: ships the Prebid Mobile SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/fr.vinted/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: PubMatic
    provider: pubmatic
    says: ships the PubMatic SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/fr.vinted/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: PubNative
    provider: pubnative
    says: ships the PubNative SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/fr.vinted/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Unity
    provider: unity
    says: ships the Unity SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/fr.vinted/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Yandex Ads
    provider: yandex-ads
    says: ships the Yandex Ads SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/fr.vinted/latest/
    tier: observed
  kind: commercial
  name: Vinted
  page: /applications/resale-marketplace/vinted/
  slug: vinted
  url: https://www.vinted.com/
- anchor: depop
  counts:
    declared: 0
    observed: 6
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.depop/latest/
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
    name: Branch
    provider: branch-io
    says: ships the Branch SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.depop/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.depop/latest/
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
    name: Facebook
    provider: facebook
    says: ships the Facebook SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.depop/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.depop/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.depop/latest/
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
    name: Google Analytics
    provider: google-analytics
    says: ships the Google Analytics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.depop/latest/
    tier: observed
  kind: commercial
  name: Depop
  page: /applications/resale-marketplace/depop/
  slug: depop
  url: https://www.depop.com/
- anchor: poshmark
  counts:
    declared: 0
    observed: 11
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.poshmark.app/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.poshmark.app/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.poshmark.app/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.poshmark.app/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.poshmark.app/latest/
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
    name: Facebook
    provider: facebook
    says: ships the Facebook SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.poshmark.app/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.poshmark.app/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.poshmark.app/latest/
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
    name: Google Analytics
    provider: google-analytics
    says: ships the Google Analytics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.poshmark.app/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-911
      key: AE-911
      name: Tag Management
      url: /capabilities/product-telemetry-instrumentation/
      via_parent: Product Telemetry Instrumentation
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Google Tag Manager
    provider: google-tag-manager
    says: ships the Google Tag Manager SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.poshmark.app/latest/
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
    name: Visual Studio App Center Analytics
    provider: microsoft-app-center
    says: ships the Visual Studio App Center Analytics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.poshmark.app/latest/
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
    name: Visual Studio App Center Crashes
    provider: microsoft-app-center
    says: ships the Visual Studio App Center Crashes SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.poshmark.app/latest/
    tier: observed
  kind: commercial
  name: Poshmark
  page: /applications/resale-marketplace/poshmark/
  slug: poshmark
  url: https://poshmark.com/
- anchor: mercari
  counts:
    declared: 0
    observed: 9
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.mercariapp.mercari/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.mercariapp.mercari/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.mercariapp.mercari/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.mercariapp.mercari/latest/
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
    name: Facebook
    provider: facebook
    says: ships the Facebook SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.mercariapp.mercari/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.mercariapp.mercari/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.mercariapp.mercari/latest/
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
    name: Google Analytics
    provider: google-analytics
    says: ships the Google Analytics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.mercariapp.mercari/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-911
      key: AE-911
      name: Tag Management
      url: /capabilities/product-telemetry-instrumentation/
      via_parent: Product Telemetry Instrumentation
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Google Tag Manager
    provider: google-tag-manager
    says: ships the Google Tag Manager SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.mercariapp.mercari/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.mercariapp.mercari/latest/
    tier: observed
  kind: commercial
  name: Mercari
  page: /applications/resale-marketplace/mercari/
  slug: mercari
  url: https://www.mercari.com/
author: API Evangelist
candidates: []
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
html: public
id: resale-marketplace
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Shopping
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Shopping
  store: google-play
  url: https://play.google.com/store/apps/category/SHOPPING
- category: E-commerce
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#e-commerce
name: Resale & Second-hand Marketplaces
needs:
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  fit: exact
  layer: domain
  why: buyer checkout, escrow-style holds and seller payouts (Stripe Connect, PayPal, Mangopay wallets)
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  fit: exact
  layer: common
  why: low-friction buyer/seller sign-up via Facebook, Google, LinkedIn
- capability:
    attribution: Turbo EA
    id: BC-3710.30
    key: asset-storage-tiering
    name: Asset Storage & Tiering
    url: /capabilities/asset-storage-tiering/
    via_parent: null
  fit: exact
  layer: common
  why: listing photos
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.10
    key: AE-150.10.10
    name: Transactional Email
    url: /capabilities/email/
    via_parent: Email
  fit: exact
  layer: common
  why: order and offer notifications
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: common
  why: error monitoring and APM
- capability:
    attribution: Turbo EA
    id: BC-430
    key: customer-service-management
    name: Customer Service Management
    url: /capabilities/customer-service-management/
    via_parent: null
  fit: exact
  layer: common
  why: support and dispute messaging
- capability:
    attribution: API Evangelist extension
    id: AE-160.70
    key: bot-protection-captcha
    name: Bot Protection & CAPTCHA
    url: /capabilities/bot-protection-captcha/
    via_parent: null
  fit: exact
  layer: common
  why: spam/fake-listing protection at sign-up
- capability:
    attribution: API Evangelist extension
    id: AE-120
    key: location-mapping
    name: Location & Mapping
    url: /capabilities/location-mapping/
    via_parent: null
  fit: exact
  layer: domain
  why: local pickup, listing location search
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: exact
  layer: common
  why: funnel and behaviour analytics
- capability:
    attribution: API Evangelist extension
    id: AE-150.40
    key: in-app-chat
    name: In-App Chat
    url: /capabilities/in-app-chat/
    via_parent: null
  fit: exact
  layer: domain
  why: buyer-seller messaging
- capability:
    attribution: Turbo EA
    id: BC-440.30
    key: discount-promotion-management
    name: Discount & Promotion Management
    url: /capabilities/discount-promotion-management/
    via_parent: null
  fit: exact
  layer: domain
  why: coupons and promotions
- capability:
    attribution: API Evangelist extension
    id: AE-910
    key: AE-910
    name: Workflow Automation & iPaaS
    url: /capabilities/process-automation-governance/
    via_parent: Process Automation Governance
  fit: exact
  layer: domain
  why: connect marketplace events to other tools
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.20
    key: AE-150.10.20
    name: Email Marketing Sends
    url: /capabilities/email/
    via_parent: Email
  fit: exact
  layer: common
  why: marketing newsletters to buyers and sellers
- capability:
    attribution: API Evangelist extension
    id: AE-150.20
    key: AE-150.20
    name: SMS & Messaging Apps
    url: /capabilities/sms-messaging-apps/
    via_parent: null
  fit: exact
  layer: common
  why: SMS notifications and verification
- capability:
    attribution: API Evangelist extension
    id: AE-150.80
    key: mailbox-calendar-sync
    name: Mailbox & Calendar Sync
    url: /capabilities/mailbox-calendar-sync/
    via_parent: null
  fit: exact
  layer: common
  why: availability sync (rental-style listings)
- capability:
    attribution: API Evangelist extension
    id: AE-110.40.10
    key: AE-110.40.10
    name: Machine Translation
    url: /capabilities/language-document-understanding/
    via_parent: Language & Document Understanding
  fit: exact
  layer: common
  why: cross-border listing translation
- capability:
    attribution: API Evangelist extension
    id: AE-903
    key: AE-903
    name: In-App Ad Monetisation
    url: /capabilities/in-app-ad-monetisation/
    via_parent: null
  fit: exact
  layer: common
  why: mobile-app SDK trackers reported by Exodus Privacy
- capability:
    attribution: API Evangelist extension
    id: AE-902
    key: AE-902
    name: Mobile Attribution & Deep Linking
    url: /capabilities/mobile-attribution-deep-linking/
    via_parent: null
  fit: exact
  layer: common
  why: mobile-app SDK trackers reported by Exodus Privacy
- capability:
    attribution: Turbo EA
    id: BC-3760.30
    key: programmatic-sales-management
    name: Programmatic Sales Management
    url: /capabilities/programmatic-sales-management/
    via_parent: null
  fit: exact
  layer: common
  why: mobile-app SDK trackers reported by Exodus Privacy
- capability:
    attribution: Turbo EA
    id: BC-420.10
    key: customer-data-management
    name: Customer Data Management
    url: /capabilities/customer-data-management/
    via_parent: null
  fit: exact
  layer: common
  why: mobile-app SDK trackers reported by Exodus Privacy
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  fit: exact
  layer: common
  why: mobile-app SDK trackers reported by Exodus Privacy
- capability:
    attribution: API Evangelist extension
    id: AE-911
    key: AE-911
    name: Tag Management
    url: /capabilities/product-telemetry-instrumentation/
    via_parent: Product Telemetry Instrumentation
  fit: exact
  layer: common
  why: mobile-app SDK trackers reported by Exodus Privacy
stack:
- capabilities:
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
      - Sharetribe (hosted)
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
      - https://www.sharetribe.com/docs/concepts/integrations/integrations-introduction/
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
      - Sharetribe (hosted)
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
      - https://www.sharetribe.com/docs/concepts/integrations/integrations-introduction/
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
      attribution: API Evangelist extension
      id: AE-120
      key: location-mapping
      name: Location & Mapping
      url: /capabilities/location-mapping/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 33.0
      apps:
      - Cocorico
      - Sharetribe Web Template
      band: exemplar
      in_catalog: true
      kin_score: 73.6
      mcp:
        source: https://developers.google.com/maps/ai/grounding-lite
        status: verified
      name: Google Maps Platform
      slug: google-maps
      sources:
      - https://github.com/Cocolabs-SAS/cocorico/blob/master/composer.json
      - https://github.com/sharetribe/web-template/blob/main/.env-template
      status: profiled
      tags:
      - Environment
      - Geocoding
      - Geolocation
      - Maps
      tier: observed
      url: /providers/google-maps/
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
      attribution: Turbo EA
      id: BC-440.30
      key: discount-promotion-management
      name: Discount & Promotion Management
      url: /capabilities/discount-promotion-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 43.7
      apps:
      - Sharetribe (hosted)
      band: developing
      in_catalog: true
      kin_score: 49.2
      mcp:
        source: https://docs.voucherify.io/guides/voucherify-core-mcp
        status: verified
      name: Voucherify
      slug: voucherify
      sources:
      - https://www.sharetribe.com/docs/concepts/integrations/integrations-introduction/
      status: profiled
      tags:
      - Company
      - Incentives
      - Loyalty
      - Promotions
      tier: declared
      url: /providers/voucherify/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.40
      key: in-app-chat
      name: In-App Chat
      url: /capabilities/in-app-chat/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 31.8
      apps:
      - Sharetribe (hosted)
      band: developing
      in_catalog: true
      kin_score: 52.1
      mcp:
        status: none
      name: Sendbird
      slug: sendbird
      sources:
      - https://www.sharetribe.com/docs/concepts/integrations/integrations-introduction/
      status: profiled
      tags:
      - Customer Service
      - Omnichannel
      - Video
      - Voice
      tier: declared
      url: /providers/sendbird/
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
      - Sharetribe (hosted)
      band: exemplar
      in_catalog: true
      kin_score: 72.9
      mcp:
        source: https://zapier.com/mcp
        status: verified
      name: Zapier
      slug: zapier
      sources:
      - https://www.sharetribe.com/docs/concepts/integrations/integrations-introduction/
      status: profiled
      tags:
      - Integration
      - Workflow Automation
      - Zapier
      - iPaaS
      tier: declared
      url: /providers/zapier/
  layer: domain
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 25.3
      apps:
      - Vinted
      band: exemplar
      in_catalog: true
      kin_score: 66.5
      mcp:
        source: https://github.com/Unity-Technologies/industry-ai-workflows
        status: verified
      name: Unity
      slug: unity
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/fr.vinted/latest/
      status: profiled
      tags:
      - Game Development
      - Game Services
      - Multiplayer
      - Real-Time 3D
      tier: observed
      url: /providers/unity/
    - agent_band: agent-ready
      agent_readiness: 35.3
      apps:
      - Vinted
      band: strong
      in_catalog: true
      kin_score: 65.2
      mcp:
        status: none
      name: Google AdMob
      slug: google-admob
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/fr.vinted/latest/
      status: profiled
      tags:
      - Ad Mediation
      - AdMob
      - Advertising
      - App Monetization
      tier: observed
      url: /providers/google-admob/
    - agent_band: agent-ready
      agent_readiness: 31.0
      apps:
      - Vinted
      band: strong
      in_catalog: true
      kin_score: 60.3
      mcp:
        status: none
      name: BidMachine
      slug: bidmachine-io
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/fr.vinted/latest/
      status: profiled
      tags:
      - Ad Exchange
      - AdTech
      - Advertising
      - Mobile Advertising
      tier: observed
      url: /providers/bidmachine-io/
    - agent_band: agent-native
      agent_readiness: 53.6
      apps:
      - Vinted
      band: strong
      in_catalog: true
      kin_score: 58.4
      mcp:
        source: https://github.com/amzn/selling-partner-agentic-toolkit
        status: verified
      name: Amazon
      slug: amazon
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/fr.vinted/latest/
      status: profiled
      tags:
      - Advertising
      - Alexa
      - Amazon
      - E-Commerce
      tier: observed
      url: /providers/amazon/
    - agent_band: agent-aware
      agent_readiness: 7.7
      apps:
      - Vinted
      band: developing
      in_catalog: true
      kin_score: 46.1
      mcp:
        status: none
      name: InMobi
      slug: inmobi
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/fr.vinted/latest/
      status: profiled
      tags:
      - AdTech
      - Advertising
      - Company
      - Enterprise
      tier: observed
      url: /providers/inmobi/
    - agent_band: agent-aware
      agent_readiness: 28.1
      apps:
      - Vinted
      band: developing
      in_catalog: true
      kin_score: 43.7
      mcp: &id001
        status: none
      name: Facebook
      slug: facebook
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/fr.vinted/latest/
      status: profiled
      tags: &id002
      - Advertising
      - Content Publishing
      - Facebook
      - Fortune 500
      tier: observed
      url: /providers/facebook/
    - agent_band: agent-aware
      agent_readiness: 20.3
      apps:
      - Vinted
      band: thin
      in_catalog: true
      kin_score: 38.0
      mcp:
        status: none
      name: Digital Turbine (Fyber)
      slug: digital-turbine
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/fr.vinted/latest/
      status: profiled
      tags:
      - Advertising
      - Company
      - Mobile
      - Monetization
      tier: observed
      url: /providers/digital-turbine/
    - agent_band: agent-ready
      agent_readiness: 35.5
      apps:
      - Vinted
      band: thin
      in_catalog: true
      kin_score: 37.6
      mcp:
        status: none
      name: AppLovin
      slug: applovin
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/fr.vinted/latest/
      status: profiled
      tags:
      - AdTech
      - Advertising
      - App Monetization
      - Mobile
      tier: observed
      url: /providers/applovin/
    - agent_band: agent-aware
      agent_readiness: 14.8
      apps:
      - Vinted
      band: thin
      in_catalog: true
      kin_score: 32.1
      mcp:
        status: unknown
      name: PubNative
      slug: pubnative
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/fr.vinted/latest/
      status: profiled
      tags:
      - AdTech
      - Company
      - Mobile
      - Monetization
      tier: observed
      url: /providers/pubnative/
    - agent_band: agent-aware
      agent_readiness: 19.4
      apps:
      - Vinted
      band: thin
      in_catalog: true
      kin_score: 29.6
      mcp:
        status: none
      name: AdColony
      slug: adcolony
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/fr.vinted/latest/
      status: profiled
      tags:
      - AdTech
      - Advertising
      - Company
      - Mobile Advertising
      tier: observed
      url: /providers/adcolony/
    - agent_band: agent-ready
      agent_readiness: 33.5
      apps:
      - Vinted
      band: thin
      in_catalog: true
      kin_score: 28.1
      mcp:
        source: https://github.com/PubMatic/pubmatic-mcp-server
        status: verified
      name: PubMatic
      slug: pubmatic
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/fr.vinted/latest/
      status: profiled
      tags:
      - AdTech
      - Advertising
      - Programmatic Advertising
      - Supply Side Platform
      tier: observed
      url: /providers/pubmatic/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Vinted
      band: emerging
      in_catalog: true
      kin_score: 16.2
      mcp:
        status: unknown
      name: Mintegral
      slug: mintegral
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/fr.vinted/latest/
      status: profiled
      tags:
      - Advertising
      - Artificial Intelligence
      - Company
      - Mobile Marketing
      tier: observed
      url: /providers/mintegral/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Vinted
      band: emerging
      in_catalog: true
      kin_score: 14.1
      mcp:
        status: none
      name: Pangle
      slug: pangle
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/fr.vinted/latest/
      status: profiled
      tags:
      - Advertising
      - Mobile
      - Monetization
      - TikTok
      tier: observed
      url: /providers/pangle/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Vinted
      band: emerging
      in_catalog: true
      kin_score: 13.2
      mcp:
        status: none
      name: Yandex Ads
      slug: yandex-ads
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/fr.vinted/latest/
      status: profiled
      tags:
      - Advertising
      - App Monetization
      - User Acquisition
      - Web Analytics
      tier: observed
      url: /providers/yandex-ads/
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - Vinted
      band: minimal
      in_catalog: true
      kin_score: 10.2
      mcp:
        status: none
      name: ironSource
      slug: ironsource
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/fr.vinted/latest/
      status: profiled
      tags:
      - Advertising
      - Game Development
      - Mobile
      - Mobile Games
      tier: observed
      url: /providers/ironsource/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Vinted
      band: minimal
      in_catalog: true
      kin_score: 2.0
      mcp:
        status: none
      name: Chartboost
      slug: chartboost
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/fr.vinted/latest/
      status: profiled
      tags:
      - Company
      tier: observed
      url: /providers/chartboost/
    - agent_band: null
      agent_readiness: null
      apps:
      - Vinted
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: myTarget
      slug: mytarget
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/fr.vinted/latest/
      status: queued for profiling
      tags: []
      tier: observed
      url: null
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
      - Depop
      - Mercari
      - Poshmark
      - Sharetribe (hosted)
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
      - https://reports.exodus-privacy.eu.org/en/reports/com.depop/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.mercariapp.mercari/latest/
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
      - Depop
      - Mercari
      - Poshmark
      - Vinted
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: &id003
        source: https://firebase.google.com/docs/ai-assistance/mcp-server
        status: verified
      name: Firebase
      slug: google-firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.depop/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.mercariapp.mercari/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.poshmark.app/latest/
      status: profiled
      tags: &id004
      - Analytics
      - Authentication
      - Backend-as-a-Service
      - Cloud Messaging
      tier: observed
      url: /providers/google-firebase/
    - agent_band: agent-aware
      agent_readiness: 28.1
      apps:
      - Mercari
      - Poshmark
      - Vinted
      band: developing
      in_catalog: true
      kin_score: 43.7
      mcp: *id001
      name: Facebook
      slug: facebook
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.mercariapp.mercari/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.poshmark.app/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/fr.vinted/latest/
      status: profiled
      tags: *id002
      tier: observed
      url: /providers/facebook/
    - agent_band: null
      agent_readiness: null
      apps:
      - Poshmark
      band: null
      in_catalog: false
      kin_score: null
      mcp: &id005
        status: unchecked
      name: Visual Studio App Center Analytics
      slug: microsoft-app-center
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.poshmark.app/latest/
      status: queued for profiling
      tags: &id006 []
      tier: observed
      url: null
    - agent_band: agent-aware
      agent_readiness: 27.3
      apps:
      - Sharetribe (hosted)
      band: emerging
      in_catalog: true
      kin_score: 25.5
      mcp:
        status: none
      name: Hotjar
      slug: hotjar
      sources:
      - https://www.sharetribe.com/docs/concepts/integrations/integrations-introduction/
      status: profiled
      tags:
      - Analytics
      - Personalization
      - Surveys
      - Tracking
      tier: declared
      url: /providers/hotjar/
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
      - Depop
      - Mercari
      - Poshmark
      - Sharetribe Go
      - Sharetribe Web Template
      - Vinted
      band: developing
      in_catalog: true
      kin_score: 43.7
      mcp: *id001
      name: Facebook Login
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
    - agent_band: agent-ready
      agent_readiness: 46.5
      apps:
      - Sharetribe Go
      band: exemplar
      in_catalog: true
      kin_score: 77.8
      mcp:
        status: none
      name: LinkedIn sign-in
      slug: linkedin
      sources:
      - https://github.com/sharetribe/sharetribe/blob/master/Gemfile
      status: profiled
      tags:
      - Business
      - Careers
      - LinkedIn
      - Marketing
      tier: observed
      url: /providers/linkedin/
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 39.9
      apps:
      - Depop
      - Mercari
      - Poshmark
      - Vinted
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: *id003
      name: Firebase
      slug: google-firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.depop/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.mercariapp.mercari/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.poshmark.app/latest/
      status: profiled
      tags: *id004
      tier: observed
      url: /providers/google-firebase/
    - agent_band: agent-ready
      agent_readiness: 50.2
      apps:
      - Mercari
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
      - https://reports.exodus-privacy.eu.org/en/reports/com.mercariapp.mercari/latest/
      status: profiled
      tags:
      - APM
      - Application Monitoring
      - Bug Tracking
      - Developer Tools
      tier: observed
      url: /providers/sentry-system/
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
    - agent_band: null
      agent_readiness: null
      apps:
      - Poshmark
      band: null
      in_catalog: false
      kin_score: null
      mcp: *id005
      name: Visual Studio App Center Crashes
      slug: microsoft-app-center
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.poshmark.app/latest/
      status: queued for profiling
      tags: *id006
      tier: observed
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-902
      key: AE-902
      name: Mobile Attribution & Deep Linking
      url: /capabilities/mobile-attribution-deep-linking/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 21.9
      apps:
      - Depop
      - Poshmark
      band: thin
      in_catalog: true
      kin_score: 33.8
      mcp:
        status: none
      name: Branch
      slug: branch-io
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.depop/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.poshmark.app/latest/
      status: profiled
      tags:
      - Company
      tier: observed
      url: /providers/branch-io/
    - agent_band: agent-aware
      agent_readiness: 23.3
      apps:
      - Mercari
      - Vinted
      band: thin
      in_catalog: true
      kin_score: 30.9
      mcp:
        status: none
      name: Adjust
      slug: adjust
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.mercariapp.mercari/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/fr.vinted/latest/
      status: profiled
      tags:
      - Analytics
      - Attribution
      - Deep Linking
      - Measurements
      tier: observed
      url: /providers/adjust/
    - agent_band: agent-ready
      agent_readiness: 53.4
      apps:
      - Poshmark
      band: exemplar
      in_catalog: true
      kin_score: 72.1
      mcp:
        source: https://registry.modelcontextprotocol.io/v0/servers?search=appsflyer
        status: verified
      name: AppsFlyer
      slug: appsflyer
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.poshmark.app/latest/
      status: profiled
      tags:
      - Company
      - Marketing Analytics
      - Mobile Attribution
      - Mobile Measurement
      tier: observed
      url: /providers/appsflyer/
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 28.1
      apps:
      - Depop
      - Mercari
      - Poshmark
      band: developing
      in_catalog: true
      kin_score: 43.7
      mcp: *id001
      name: Facebook
      slug: facebook
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.depop/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.mercariapp.mercari/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.poshmark.app/latest/
      status: profiled
      tags: *id002
      tier: observed
      url: /providers/facebook/
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
      - Sharetribe (hosted)
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
      - https://www.sharetribe.com/docs/concepts/integrations/integrations-introduction/
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
      id: BC-3760.30
      key: programmatic-sales-management
      name: Programmatic Sales Management
      url: /capabilities/programmatic-sales-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 36.9
      apps:
      - Vinted
      band: strong
      in_catalog: true
      kin_score: 55.6
      mcp:
        source: https://github.com/IABTechLab/agentic-real-time-framework
        status: verified
      name: IAB Open Measurement
      slug: iab-tech-lab
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/fr.vinted/latest/
      status: profiled
      tags:
      - AdTech
      - Advertising
      - Company
      - Standards
      tier: observed
      url: /providers/iab-tech-lab/
    - agent_band: null
      agent_readiness: null
      apps:
      - Vinted
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Prebid Mobile
      slug: prebid
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/fr.vinted/latest/
      status: queued for profiling
      tags: []
      tier: observed
      url: null
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
      - Mercari
      - Poshmark
      band: strong
      in_catalog: true
      kin_score: 65.8
      mcp:
        status: none
      name: Google Tag Manager
      slug: google-tag-manager
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.mercariapp.mercari/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.poshmark.app/latest/
      status: profiled
      tags:
      - Analytics
      - Conversion Tracking
      - Marketing
      - Tag Management
      tier: observed
      url: /providers/google-tag-manager/
  - capability:
      attribution: Turbo EA
      id: BC-3710.30
      key: asset-storage-tiering
      name: Asset Storage & Tiering
      url: /capabilities/asset-storage-tiering/
      via_parent: null
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
      id: AE-160.70
      key: bot-protection-captcha
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
      id: BC-420.10
      key: customer-data-management
      name: Customer Data Management
      url: /capabilities/customer-data-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 44.8
      apps:
      - Vinted
      band: strong
      in_catalog: true
      kin_score: 59.5
      mcp:
        status: none
      name: mParticle
      slug: mparticle
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/fr.vinted/latest/
      status: profiled
      tags:
      - Analytics
      - CDP
      - Customer Data Platform
      - Identity Resolution
      tier: observed
      url: /providers/mparticle/
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
      - Sharetribe (hosted)
      band: exemplar
      in_catalog: true
      kin_score: 77.7
      mcp:
        status: none
      name: Mailchimp
      slug: mailchimp
      sources:
      - https://www.sharetribe.com/docs/concepts/integrations/integrations-introduction/
      status: profiled
      tags:
      - Campaigns
      - Email Marketing
      - Marketing Automation
      - Newsletters
      tier: declared
      url: /providers/mailchimp/
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
      id: AE-150.80
      key: mailbox-calendar-sync
      name: Mailbox & Calendar Sync
      url: /capabilities/mailbox-calendar-sync/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 44.1
      apps:
      - Sharetribe (hosted)
      band: strong
      in_catalog: true
      kin_score: 64.6
      mcp:
        source: https://github.com/google/mcp
        status: verified
      name: Google Calendar
      slug: google-calendar
      sources:
      - https://www.sharetribe.com/docs/concepts/integrations/integrations-introduction/
      status: profiled
      tags:
      - Availability
      - Calendar
      - Event
      - Google
      tier: declared
      url: /providers/google-calendar/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20
      key: AE-150.20
      name: SMS & Messaging Apps
      url: /capabilities/sms-messaging-apps/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 56.6
      apps:
      - Sharetribe (hosted)
      band: exemplar
      in_catalog: true
      kin_score: 90.8
      mcp:
        source: https://www.twilio.com/docs/ai/mcp
        status: verified
      name: Twilio
      slug: twilio
      sources:
      - https://www.sharetribe.com/docs/concepts/integrations/integrations-introduction/
      status: profiled
      tags:
      - Authentication
      - Communications
      - Contact Center
      - Email
      tier: declared
      url: /providers/twilio/
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
  layer: common
summary:
  coverage_pct: 91.8
  declared_only: 7
  distinct_providers: 49
  in_catalog: 45
  mcp:
    documented: 0
    none: 24
    unchecked: 4
    verified: 19
  mcp_verified: 19
  mean_kin_score: 52.1
  observed: 42
  queued: 4
  reference_apps: 8
title: 'Resale & Second-hand Marketplaces: application blueprint'
---
