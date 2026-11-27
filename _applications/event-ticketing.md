---
access: understanding
agent_layer:
- app: Luma
  finding: Luma runs its own read-only MCP server for Claude/ChatGPT, available on every account
  source: https://help.luma.com/p/integrations
  tier: declared
- app: Hi.Events
  finding: laravel/ai + ANTHROPIC_API_KEY used for an LLM spam check on new events (consumes an LLM; exposes nothing to agents)
  source: https://github.com/HiEventsDev/Hi.Events/blob/develop/backend/.env.example
  tier: observed
apps:
- anchor: pretix
  counts:
    declared: 19
    observed: 4
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/eu.pretix.pretixscan.droid/latest/
  - route: dependency manifest
    url: https://github.com/pretix/pretix/blob/master/pyproject.toml
  - route: integrations page
    url: https://marketplace.pretix.eu/
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-120.50.10
      key: AE-120.50.10
      name: IP Geolocation
      url: /capabilities/device-ip-location/
      via_parent: Device & IP Location
    credit: null
    layer: common
    name: MaxMind
    provider: maxmind
    says: ships the MaxMind SDK or integration code
    source: https://github.com/pretix/pretix/blob/master/pyproject.toml
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
    source: https://github.com/pretix/pretix/blob/master/pyproject.toml
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
    source: https://github.com/pretix/pretix/blob/master/pyproject.toml
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
    source: https://github.com/pretix/pretix/blob/master/pyproject.toml
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
    name: Adyen
    provider: adyen
    says: lists Adyen as an integration
    source: https://marketplace.pretix.eu/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-210.50.10
      key: AE-210.50.10
      name: Mobile Tickets & Wallet Passes
      url: /capabilities/event-ticketing/
      via_parent: Event Ticketing
    credit: null
    layer: domain
    name: Apple Wallet (Passbook)
    provider: apple
    says: lists Apple Wallet (Passbook) as an integration
    source: https://marketplace.pretix.eu/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: Authorize.net
    provider: authorizenet
    says: lists Authorize.net as an integration
    source: https://marketplace.pretix.eu/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: BitPay
    provider: bitpay
    says: lists BitPay as an integration
    source: https://marketplace.pretix.eu/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: Computop
    provider: computop
    says: lists Computop as an integration
    source: https://marketplace.pretix.eu/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: Datatrans
    provider: datatrans
    says: lists Datatrans as an integration
    source: https://marketplace.pretix.eu/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: common
    name: HubSpot
    provider: hubspot
    says: lists HubSpot as an integration
    source: https://marketplace.pretix.eu/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: iyzico
    provider: iyzico
    says: lists iyzico as an integration
    source: https://marketplace.pretix.eu/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: Mollie
    provider: mollie
    says: lists Mollie as an integration
    source: https://marketplace.pretix.eu/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: Nets Easy
    provider: nexi
    says: lists Nets Easy as an integration
    source: https://marketplace.pretix.eu/
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
    name: Newsletter2Go
    provider: brevo
    says: lists Newsletter2Go as an integration
    source: https://marketplace.pretix.eu/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: PAYONE
    provider: payone
    says: lists PAYONE as an integration
    source: https://marketplace.pretix.eu/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: Przelewy24
    provider: przelewy24
    says: lists Przelewy24 as an integration
    source: https://marketplace.pretix.eu/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: Quickpay
    provider: quickpay
    says: lists Quickpay as an integration
    source: https://marketplace.pretix.eu/
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
    name: ready2order
    provider: ready2order
    says: lists ready2order as an integration
    source: https://marketplace.pretix.eu/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: common
    name: Slack
    provider: slack
    says: lists Slack as an integration
    source: https://marketplace.pretix.eu/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-210.20.10
      key: AE-210.20.10
      name: Hotel Booking
      url: /capabilities/lodging-stays/
      via_parent: Lodging & Stays
    credit: null
    layer: domain
    name: Stay22
    provider: stay22
    says: lists Stay22 as an integration
    source: https://marketplace.pretix.eu/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-210.50
      key: AE-210.50
      name: Event Ticketing
      url: /capabilities/event-ticketing/
      via_parent: null
    credit: null
    layer: domain
    name: TicketSwap
    provider: ticketswap
    says: lists TicketSwap as an integration
    source: https://marketplace.pretix.eu/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: Worldline Direct / Saferpay
    provider: wordline
    says: lists Worldline Direct / Saferpay as an integration
    source: https://marketplace.pretix.eu/
    tier: declared
  kind: self-hosted
  name: pretix
  page: /applications/event-ticketing/pretix/
  slug: pretix
  url: https://github.com/pretix/pretix
- anchor: pretalx
  counts:
    declared: 4
    observed: 0
  evidence:
  - route: dependency manifest
    url: https://github.com/pretalx/pretalx/blob/main/pyproject.toml
  - route: source code
    url: https://github.com/pretalx
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-160.70
      key: AE-160.70
      name: Bot Protection & CAPTCHA
      url: /capabilities/bot-protection-captcha/
      via_parent: null
    credit: null
    layer: common
    name: Friendly Captcha
    provider: friendly-captcha
    says: lists Friendly Captcha as an integration
    source: https://github.com/pretalx/pretalx-friendly-captcha
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.40
      key: AE-160.10.40
      name: Account Linking
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: ORCID
    provider: orcid
    says: lists ORCID as an integration
    source: https://github.com/pretalx/pretalx-orcid
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.10.10
      key: AE-170.10.10
      name: Video Hosting & Encoding
      url: /capabilities/video-platforms/
      via_parent: Video Platforms
    credit: null
    layer: domain
    name: Vimeo
    provider: vimeo
    says: lists Vimeo as an integration
    source: https://github.com/pretalx/pretalx-vimeo
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.10.10
      key: AE-170.10.10
      name: Video Hosting & Encoding
      url: /capabilities/video-platforms/
      via_parent: Video Platforms
    credit: null
    layer: domain
    name: YouTube
    provider: youtube
    says: lists YouTube as an integration
    source: https://github.com/pretalx/pretalx-youtube
    tier: declared
  kind: self-hosted
  name: pretalx
  page: /applications/event-ticketing/pretalx/
  slug: pretalx
  url: https://github.com/pretalx/pretalx
- anchor: indico
  counts:
    declared: 0
    observed: 11
  evidence:
  - route: dependency manifest
    url: https://github.com/indico/indico/blob/master/requirements.in
  - route: source code
    url: https://github.com/indico/indico-plugins
  - route: source code
    url: https://github.com/indico/indico/tree/master/indico/modules/events/registration/wallets
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-210.50.10
      key: AE-210.50.10
      name: Mobile Tickets & Wallet Passes
      url: /capabilities/event-ticketing/
      via_parent: Event Ticketing
    credit: null
    layer: domain
    name: Apple Wallet
    provider: apple
    says: ships the Apple Wallet SDK or integration code
    source: https://github.com/indico/indico/tree/master/indico/modules/events/registration/wallets
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-210.50.10
      key: AE-210.50.10
      name: Mobile Tickets & Wallet Passes
      url: /capabilities/event-ticketing/
      via_parent: Event Ticketing
    credit: null
    layer: domain
    name: Google Wallet
    provider: google-wallet
    says: ships the Google Wallet SDK or integration code
    source: https://github.com/indico/indico/tree/master/indico/modules/events/registration/wallets
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
    name: hCaptcha
    provider: hcaptcha
    says: ships the hCaptcha SDK or integration code
    source: https://github.com/indico/indico-plugins/tree/master/cloud_captchas
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
    name: Matomo (Piwik)
    provider: matomo
    says: ships the Matomo (Piwik) SDK or integration code
    source: https://github.com/indico/indico-plugins/tree/master/piwik
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: ownCloud
    provider: owncloud
    says: ships the ownCloud SDK or integration code
    source: https://github.com/indico/indico-plugins/tree/master/owncloud
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
    source: https://github.com/indico/indico-plugins/tree/master/payment_paypal
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
    name: reCAPTCHA
    provider: google-recaptcha
    says: ships the reCAPTCHA SDK or integration code
    source: https://github.com/indico/indico-plugins/tree/master/cloud_captchas
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
    source: https://github.com/indico/indico/blob/master/requirements.in
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
    name: SIXPay Saferpay
    provider: wordline
    says: ships the SIXPay Saferpay SDK or integration code
    source: https://github.com/indico/indico-plugins/tree/master/payment_sixpay
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
    source: https://github.com/indico/indico-plugins/tree/master/payment_stripe
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.60
      key: AE-150.60
      name: Video Calling
      url: /capabilities/video-calling/
      via_parent: null
    credit: null
    layer: common
    name: Zoom
    provider: zoom
    says: ships the Zoom SDK or integration code
    source: https://github.com/indico/indico-plugins/tree/master/vc_zoom
    tier: observed
  kind: self-hosted
  name: Indico
  page: /applications/event-ticketing/indico/
  slug: indico
  url: https://github.com/indico/indico
- anchor: hievents
  counts:
    declared: 0
    observed: 6
  evidence:
  - route: dependency manifest
    url: https://github.com/HiEventsDev/Hi.Events/blob/develop/backend/composer.json
  - route: dependency manifest
    url: https://github.com/HiEventsDev/Hi.Events/blob/develop/frontend/package.json
  - route: source code
    url: https://github.com/HiEventsDev/Hi.Events/blob/develop/backend/.env.example
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: Anthropic
    provider: anthropic
    says: ships the Anthropic SDK or integration code
    source: https://github.com/HiEventsDev/Hi.Events/blob/develop/backend/.env.example
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
    name: Cloudflare Turnstile
    provider: cloudflare-turnstile
    says: ships the Cloudflare Turnstile SDK or integration code
    source: https://github.com/HiEventsDev/Hi.Events/blob/develop/backend/.env.example
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120.10.30
      key: AE-120.10.30
      name: Address Validation & Autocomplete
      url: /capabilities/geocoding/
      via_parent: Geocoding
    credit: null
    layer: common
    name: Google Places
    provider: google-places
    says: ships the Google Places SDK or integration code
    source: https://github.com/HiEventsDev/Hi.Events/blob/develop/backend/.env.example
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
    name: Postmark
    provider: postmark
    says: ships the Postmark SDK or integration code
    source: https://github.com/HiEventsDev/Hi.Events/blob/develop/backend/composer.json
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
    source: https://github.com/HiEventsDev/Hi.Events/blob/develop/backend/composer.json
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
    source: https://github.com/HiEventsDev/Hi.Events/blob/develop/backend/composer.json
    tier: observed
  kind: open-source-saas
  name: Hi.Events
  page: /applications/event-ticketing/hi-events/
  slug: hi-events
  url: https://github.com/HiEventsDev/Hi.Events
- anchor: alfio
  counts:
    declared: 0
    observed: 13
  evidence:
  - route: source code
    url: https://github.com/alfio-event/alf.io/blob/main/src/main/java/alfio/model/system/ConfigurationKeys.java
  - route: source code
    url: https://github.com/alfio-event/alf.io/tree/main/src/main/java/alfio/manager/payment
  - route: source code
    url: https://github.com/alfio-event/alf.io/tree/main/src/main/java/alfio/manager/system
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-220.20
      key: indirect-tax-management
      name: Indirect Tax Management
      url: /capabilities/indirect-tax-management/
      via_parent: null
    credit: null
    layer: domain
    name: EU VIES VAT validation
    provider: eu-vies
    says: ships the EU VIES VAT validation SDK or integration code
    source: https://github.com/alfio-event/alf.io/blob/main/src/main/java/alfio/model/system/ConfigurationKeys.java
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
    source: https://github.com/alfio-event/alf.io/blob/main/src/main/java/alfio/model/system/ConfigurationKeys.java
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120.20.10
      key: AE-120.20.10
      name: Base Map Tiles
      url: /capabilities/maps-tiles/
      via_parent: Maps & Tiles
    credit: null
    layer: common
    name: Google Maps
    provider: google-maps
    says: ships the Google Maps SDK or integration code
    source: https://github.com/alfio-event/alf.io/blob/main/src/main/java/alfio/model/system/ConfigurationKeys.java
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120.20.10
      key: AE-120.20.10
      name: Base Map Tiles
      url: /capabilities/maps-tiles/
      via_parent: Maps & Tiles
    credit: null
    layer: common
    name: HERE
    provider: here
    says: ships the HERE SDK or integration code
    source: https://github.com/alfio-event/alf.io/blob/main/src/main/java/alfio/model/system/ConfigurationKeys.java
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
    name: Mailgun
    provider: mailgun
    says: ships the Mailgun SDK or integration code
    source: https://github.com/alfio-event/alf.io/tree/main/src/main/java/alfio/manager/system
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
    name: Mailjet
    provider: mailjet
    says: ships the Mailjet SDK or integration code
    source: https://github.com/alfio-event/alf.io/tree/main/src/main/java/alfio/manager/system
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
    name: Mollie
    provider: mollie
    says: ships the Mollie SDK or integration code
    source: https://github.com/alfio-event/alf.io/tree/main/src/main/java/alfio/manager/payment
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
    source: https://github.com/alfio-event/alf.io/tree/main/src/main/java/alfio/manager/payment
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
    name: reCAPTCHA
    provider: google-recaptcha
    says: ships the reCAPTCHA SDK or integration code
    source: https://github.com/alfio-event/alf.io/blob/main/src/main/java/alfio/model/system/ConfigurationKeys.java
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
    name: Revolut Business
    provider: revolut
    says: ships the Revolut Business SDK or integration code
    source: https://github.com/alfio-event/alf.io/tree/main/src/main/java/alfio/manager/payment
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
    name: Saferpay
    provider: wordline
    says: ships the Saferpay SDK or integration code
    source: https://github.com/alfio-event/alf.io/tree/main/src/main/java/alfio/manager/payment
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
    name: SendGrid
    provider: sendgrid
    says: ships the SendGrid SDK or integration code
    source: https://github.com/alfio-event/alf.io/tree/main/src/main/java/alfio/manager/system
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
    source: https://github.com/alfio-event/alf.io/tree/main/src/main/java/alfio/manager/payment
    tier: observed
  kind: self-hosted
  name: alf.io
  page: /applications/event-ticketing/alf-io/
  slug: alf-io
  url: https://github.com/alfio-event/alf.io
- anchor: ticketmaster
  counts:
    declared: 0
    observed: 4
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://web.archive.org/web/20251108232712/https://reports.exodus-privacy.eu.org/en/reports/com.ticketmaster.mobile.android.na/latest/
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
    source: https://web.archive.org/web/20251108232712/https://reports.exodus-privacy.eu.org/en/reports/com.ticketmaster.mobile.android.na/latest/
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
    source: https://web.archive.org/web/20251108232712/https://reports.exodus-privacy.eu.org/en/reports/com.ticketmaster.mobile.android.na/latest/
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
    source: https://web.archive.org/web/20251108232712/https://reports.exodus-privacy.eu.org/en/reports/com.ticketmaster.mobile.android.na/latest/
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
    name: Salesforce Marketing Cloud
    provider: salesforce-marketing-cloud
    says: ships the Salesforce Marketing Cloud SDK or integration code
    source: https://web.archive.org/web/20251108232712/https://reports.exodus-privacy.eu.org/en/reports/com.ticketmaster.mobile.android.na/latest/
    tier: observed
  kind: commercial
  name: Ticketmaster
  page: /applications/event-ticketing/ticketmaster/
  slug: ticketmaster
  url: https://www.ticketmaster.com/
- anchor: luma
  counts:
    declared: 3
    observed: 0
  evidence:
  - route: integrations page
    url: https://help.luma.com/p/integrations
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: common
    name: HubSpot
    provider: hubspot
    says: lists HubSpot as an integration
    source: https://help.luma.com/p/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: common
    name: Salesforce
    provider: salesforce
    says: lists Salesforce as an integration
    source: https://help.luma.com/p/integrations
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
    source: https://help.luma.com/p/integrations
    tier: declared
  kind: commercial
  name: Luma
  page: /applications/event-ticketing/luma/
  slug: luma
  url: https://luma.com/
- anchor: tito
  counts:
    declared: 3
    observed: 0
  evidence:
  - route: integrations page
    url: https://ti.to/features
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
    source: https://ti.to/features
    tier: declared
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
    says: lists PayPal as an integration
    source: https://ti.to/features
    tier: declared
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
    says: lists Stripe as an integration
    source: https://ti.to/features
    tier: declared
  kind: commercial
  name: Tito
  page: /applications/event-ticketing/tito/
  slug: tito
  url: https://ti.to/
author: API Evangelist
candidates: []
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
html: public
id: event-ticketing
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Entertainment
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Lifestyle
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Events
  store: google-play
  url: https://play.google.com/store/apps/category/EVENTS
- category: Entertainment
  store: google-play
  url: https://play.google.com/store/apps/category/ENTERTAINMENT
- category: Polls and Events
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#polls-and-events
- category: Conference Management
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#conference-management
- category: Events
  store: hubspot-marketplace
  url: https://ecosystem.hubspot.com/marketplace/apps
- category: Event Management
  store: zapier
  url: https://zapier.com/apps
name: Events & Ticketing
needs:
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  fit: exact
  layer: common
  why: every ticket sale is a payment; the broadest gateway list in the category
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: common
  why: error monitoring in self-hosted apps
- capability:
    attribution: API Evangelist extension
    id: AE-120.50.10
    key: AE-120.50.10
    name: IP Geolocation
    url: /capabilities/device-ip-location/
    via_parent: Device & IP Location
  fit: exact
  layer: common
  why: country detection for checkout and tax
- capability:
    attribution: Turbo EA
    id: BC-420
    key: customer-relationship-management
    name: Customer Relationship Management
    url: /capabilities/customer-relationship-management/
    via_parent: null
  fit: exact
  layer: common
  why: sync attendees and leads into the CRM
- capability:
    attribution: Turbo EA
    id: BC-850.10
    key: internal-communications-management
    name: Internal Communications Management
    url: /capabilities/internal-communications-management/
    via_parent: null
  fit: exact
  layer: common
  why: order notifications to the organizer team
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.20
    key: AE-150.10.20
    name: Email Marketing Sends
    url: /capabilities/email/
    via_parent: Email
  fit: exact
  layer: common
  why: attendee newsletters
- capability:
    attribution: API Evangelist extension
    id: AE-210.50
    key: AE-210.50
    name: Event Ticketing
    url: /capabilities/event-ticketing/
    via_parent: null
  fit: exact
  layer: domain
  why: resale and wallet tickets; the domain node itself
- capability:
    attribution: API Evangelist extension
    id: AE-210.20.10
    key: AE-210.20.10
    name: Hotel Booking
    url: /capabilities/lodging-stays/
    via_parent: Lodging & Stays
  fit: exact
  layer: domain
  why: accommodation for travelling attendees
- capability:
    attribution: API Evangelist extension
    id: AE-170.10.10
    key: AE-170.10.10
    name: Video Hosting & Encoding
    url: /capabilities/video-platforms/
    via_parent: Video Platforms
  fit: exact
  layer: domain
  why: session recordings embedded on talk pages
- capability:
    attribution: API Evangelist extension
    id: AE-160.70
    key: AE-160.70
    name: Bot Protection & CAPTCHA
    url: /capabilities/bot-protection-captcha/
    via_parent: null
  fit: exact
  layer: common
  why: checkout and CfP forms are bot targets
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.40
    key: AE-160.10.40
    name: Account Linking
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  fit: exact
  layer: domain
  why: speaker identity via ORCID
- capability:
    attribution: API Evangelist extension
    id: AE-150.60
    key: AE-150.60
    name: Video Calling
    url: /capabilities/video-calling/
    via_parent: null
  fit: exact
  layer: common
  why: virtual and hybrid sessions
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: exact
  layer: common
  why: ticket-shop funnel analytics
- capability:
    attribution: API Evangelist extension
    id: AE-916
    key: AE-916
    name: Cloud Drive & File Sync
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: attach materials from a file store
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.10
    key: AE-150.10.10
    name: Transactional Email
    url: /capabilities/email/
    via_parent: Email
  fit: exact
  layer: common
  why: ticket and order confirmation delivery
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  fit: exact
  layer: agent
  why: LLM spam screening of new events
- capability:
    attribution: API Evangelist extension
    id: AE-120.10.30
    key: AE-120.10.30
    name: Address Validation & Autocomplete
    url: /capabilities/geocoding/
    via_parent: Geocoding
  fit: exact
  layer: common
  why: venue address entry
- capability:
    attribution: API Evangelist extension
    id: AE-120.20.10
    key: AE-120.20.10
    name: Base Map Tiles
    url: /capabilities/maps-tiles/
    via_parent: Maps & Tiles
  fit: exact
  layer: common
  why: venue maps on event pages
- capability:
    attribution: Turbo EA
    id: BC-220.20
    key: indirect-tax-management
    name: Indirect Tax Management
    url: /capabilities/indirect-tax-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: EU VAT number validation for B2B tickets
- capability:
    attribution: API Evangelist extension
    id: AE-902
    key: AE-902
    name: Mobile Attribution & Deep Linking
    url: /capabilities/mobile-attribution-deep-linking/
    via_parent: null
  fit: exact
  layer: common
  why: consumer ticket app install attribution
- capability:
    attribution: Turbo EA
    id: BC-420.10
    key: customer-data-management
    name: Customer Data Management
    url: /capabilities/customer-data-management/
    via_parent: null
  fit: exact
  layer: common
  why: fan data unification
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  fit: exact
  layer: common
  why: fan marketing journeys
- capability:
    attribution: API Evangelist extension
    id: AE-910
    key: AE-910
    name: Workflow Automation & iPaaS
    url: /capabilities/process-automation-governance/
    via_parent: Process Automation Governance
  fit: exact
  layer: common
  why: no-code export of registrations
stack:
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-210.50.10
      key: AE-210.50.10
      name: Mobile Tickets & Wallet Passes
      url: /capabilities/event-ticketing/
      via_parent: Event Ticketing
    providers:
    - agent_band: agent-ready
      agent_readiness: 36.5
      apps:
      - Indico
      - pretix
      band: developing
      in_catalog: true
      kin_score: 52.9
      mcp:
        status: none
      name: Apple Wallet (Passbook)
      slug: apple
      sources:
      - https://github.com/indico/indico/tree/master/indico/modules/events/registration/wallets
      - https://marketplace.pretix.eu/
      status: profiled
      tags:
      - Apple
      - Developers
      - iOS
      - macOS
      tier: observed
      url: /providers/apple/
    - agent_band: agent-ready
      agent_readiness: 40.5
      apps:
      - Indico
      band: strong
      in_catalog: true
      kin_score: 61.3
      mcp:
        source: https://developers.google.com/pay-wallet/ai-tools/mcp-server/mcp-server
        status: verified
      name: Google Wallet
      slug: google-wallet
      sources:
      - https://github.com/indico/indico/tree/master/indico/modules/events/registration/wallets
      status: profiled
      tags:
      - Digital Wallet
      - Google Wallet
      - Loyalty Cards
      - Mobile Payments
      tier: observed
      url: /providers/google-wallet/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.10.10
      key: AE-170.10.10
      name: Video Hosting & Encoding
      url: /capabilities/video-platforms/
      via_parent: Video Platforms
    providers:
    - agent_band: agent-ready
      agent_readiness: 41.4
      apps:
      - pretalx
      band: strong
      in_catalog: true
      kin_score: 65.4
      mcp:
        status: none
      name: YouTube
      slug: youtube
      sources:
      - https://github.com/pretalx/pretalx-youtube
      status: profiled
      tags:
      - Google
      - Media
      - Video
      - YouTube
      tier: declared
      url: /providers/youtube/
    - agent_band: agent-ready
      agent_readiness: 47.8
      apps:
      - pretalx
      band: thin
      in_catalog: true
      kin_score: 37.6
      mcp:
        source: https://developer.vimeo.com/api/mcp-server
        status: documented
      name: Vimeo
      slug: vimeo
      sources:
      - https://github.com/pretalx/pretalx-vimeo
      status: profiled
      tags:
      - Live Streaming
      - Streaming
      - Video
      - Video Hosting
      tier: declared
      url: /providers/vimeo/
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.40
      key: AE-160.10.40
      name: Account Linking
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    providers:
    - agent_band: agent-aware
      agent_readiness: 22.1
      apps:
      - pretalx
      band: thin
      in_catalog: true
      kin_score: 34.2
      mcp:
        status: none
      name: ORCID
      slug: orcid
      sources:
      - https://github.com/pretalx/pretalx-orcid
      status: profiled
      tags:
      - Academic
      - Identity
      - ORCID
      - Researchers
      tier: declared
      url: /providers/orcid/
  - capability:
      attribution: API Evangelist extension
      id: AE-210.50
      key: AE-210.50
      name: Event Ticketing
      url: /capabilities/event-ticketing/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - pretix
      band: minimal
      in_catalog: true
      kin_score: 3.4
      mcp:
        status: none
      name: TicketSwap
      slug: ticketswap
      sources:
      - https://marketplace.pretix.eu/
      status: profiled
      tags:
      - Company
      tier: declared
      url: /providers/ticketswap/
  - capability:
      attribution: API Evangelist extension
      id: AE-210.20.10
      key: AE-210.20.10
      name: Hotel Booking
      url: /capabilities/lodging-stays/
      via_parent: Lodging & Stays
    providers:
    - agent_band: agent-aware
      agent_readiness: 27.3
      apps:
      - pretix
      band: developing
      in_catalog: true
      kin_score: 52.2
      mcp:
        status: none
      name: Stay22
      slug: stay22
      sources:
      - https://marketplace.pretix.eu/
      status: profiled
      tags:
      - Affiliate Marketing
      - Event
      - Software-as-a-Service
      - TravelTech
      tier: declared
      url: /providers/stay22/
  - capability:
      attribution: Turbo EA
      id: BC-220.20
      key: indirect-tax-management
      name: Indirect Tax Management
      url: /capabilities/indirect-tax-management/
      via_parent: null
    providers:
    - agent_band: null
      agent_readiness: null
      apps:
      - alf.io
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: EU VIES VAT validation
      slug: eu-vies
      sources:
      - https://github.com/alfio-event/alf.io/blob/main/src/main/java/alfio/model/system/ConfigurationKeys.java
      status: queued for profiling
      tags: []
      tier: observed
      url: null
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 30.4
      apps:
      - pretix
      band: developing
      in_catalog: true
      kin_score: 53.7
      mcp:
        status: none
      name: ready2order
      slug: ready2order
      sources:
      - https://marketplace.pretix.eu/
      status: profiled
      tags:
      - Company
      - Payments
      - Point-of-Sale
      - Retail
      tier: declared
      url: /providers/ready2order/
  layer: domain
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
      - Hi.Events
      - Indico
      - Tito
      - alf.io
      - pretix
      band: exemplar
      in_catalog: true
      kin_score: 82.0
      mcp:
        source: https://docs.stripe.com/mcp
        status: verified
      name: Stripe
      slug: stripe
      sources:
      - https://github.com/HiEventsDev/Hi.Events/blob/develop/backend/composer.json
      - https://github.com/alfio-event/alf.io/tree/main/src/main/java/alfio/manager/payment
      - https://github.com/indico/indico-plugins/tree/master/payment_stripe
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
      - Indico
      - Tito
      - alf.io
      - pretix
      band: strong
      in_catalog: true
      kin_score: 54.9
      mcp:
        source: https://developer.paypal.com/tools/mcp-server/
        status: verified
      name: PayPal
      slug: paypal
      sources:
      - https://github.com/alfio-event/alf.io/tree/main/src/main/java/alfio/manager/payment
      - https://github.com/indico/indico-plugins/tree/master/payment_paypal
      - https://github.com/pretix/pretix/blob/master/pyproject.toml
      status: profiled
      tags:
      - Billing
      - Commerce
      - Disputes
      - PayPal
      tier: observed
      url: /providers/paypal/
    - agent_band: agent-ready
      agent_readiness: 41.5
      apps:
      - Indico
      - alf.io
      - pretix
      band: developing
      in_catalog: true
      kin_score: 54.0
      mcp:
        status: none
      name: Worldline Direct / Saferpay
      slug: wordline
      sources:
      - https://github.com/alfio-event/alf.io/tree/main/src/main/java/alfio/manager/payment
      - https://github.com/indico/indico-plugins/tree/master/payment_sixpay
      - https://marketplace.pretix.eu/
      status: profiled
      tags:
      - Acquiring
      - Issuing
      - Payment Processing
      - Payments
      tier: observed
      url: /providers/wordline/
    - agent_band: agent-native
      agent_readiness: 71.7
      apps:
      - alf.io
      - pretix
      band: exemplar
      in_catalog: true
      kin_score: 68.1
      mcp:
        source: https://docs.mollie.com/docs/mcp-server
        status: verified
      name: Mollie
      slug: mollie
      sources:
      - https://github.com/alfio-event/alf.io/tree/main/src/main/java/alfio/manager/payment
      - https://marketplace.pretix.eu/
      status: profiled
      tags:
      - Company
      - Financial Services
      - Fintech
      - Payments
      tier: observed
      url: /providers/mollie/
    - agent_band: agent-native
      agent_readiness: 50.9
      apps:
      - alf.io
      band: exemplar
      in_catalog: true
      kin_score: 69.6
      mcp:
        status: none
      name: Revolut Business
      slug: revolut
      sources:
      - https://github.com/alfio-event/alf.io/tree/main/src/main/java/alfio/manager/payment
      status: profiled
      tags:
      - Banking
      - Company
      - Fintech
      - Payments
      tier: observed
      url: /providers/revolut/
    - agent_band: agent-native
      agent_readiness: 42.8
      apps:
      - pretix
      band: exemplar
      in_catalog: true
      kin_score: 73.6
      mcp:
        source: https://github.com/Adyen/adyen-mcp
        status: verified
      name: Adyen
      slug: adyen
      sources:
      - https://marketplace.pretix.eu/
      status: profiled
      tags:
      - Agentic Commerce
      - Financial Services
      - Fintech
      - Payments
      tier: declared
      url: /providers/adyen/
    - agent_band: agent-aware
      agent_readiness: 24.6
      apps:
      - pretix
      band: developing
      in_catalog: true
      kin_score: 48.3
      mcp:
        status: none
      name: iyzico
      slug: iyzico
      sources:
      - https://marketplace.pretix.eu/
      status: profiled
      tags:
      - Company
      - Fintech
      - Payment Gateway
      - Payments
      tier: declared
      url: /providers/iyzico/
    - agent_band: agent-aware
      agent_readiness: 26.3
      apps:
      - pretix
      band: thin
      in_catalog: true
      kin_score: 36.9
      mcp:
        status: none
      name: Przelewy24
      slug: przelewy24
      sources:
      - https://marketplace.pretix.eu/
      status: profiled
      tags:
      - BLIK
      - Bank Transfers
      - Payment Gateway
      - Payments
      tier: declared
      url: /providers/przelewy24/
    - agent_band: agent-aware
      agent_readiness: 25.4
      apps:
      - pretix
      band: thin
      in_catalog: true
      kin_score: 35.5
      mcp:
        source: https://github.com/AuthorizeNet/authorize-net-mcp
        status: verified
      name: Authorize.net
      slug: authorizenet
      sources:
      - https://marketplace.pretix.eu/
      status: profiled
      tags:
      - Company
      - Credit Cards
      - Payment Gateway
      - Payments
      tier: declared
      url: /providers/authorizenet/
    - agent_band: agent-ready
      agent_readiness: 35.9
      apps:
      - pretix
      band: thin
      in_catalog: true
      kin_score: 33.9
      mcp:
        status: none
      name: BitPay
      slug: bitpay
      sources:
      - https://marketplace.pretix.eu/
      status: profiled
      tags:
      - Bitcoin
      - Blockchain
      - Cryptocurrency
      - Payments
      tier: declared
      url: /providers/bitpay/
    - agent_band: agent-aware
      agent_readiness: 14.5
      apps:
      - pretix
      band: thin
      in_catalog: true
      kin_score: 28.2
      mcp:
        status: none
      name: Computop
      slug: computop
      sources:
      - https://marketplace.pretix.eu/
      status: profiled
      tags:
      - E-Commerce
      - Fintech
      - Germany
      - Payments
      tier: declared
      url: /providers/computop/
    - agent_band: agent-aware
      agent_readiness: 16.8
      apps:
      - pretix
      band: thin
      in_catalog: true
      kin_score: 27.7
      mcp:
        status: none
      name: Nets Easy
      slug: nexi
      sources:
      - https://marketplace.pretix.eu/
      status: profiled
      tags:
      - Company
      - Europe
      - Fintech
      - Payments
      tier: declared
      url: /providers/nexi/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - pretix
      band: emerging
      in_catalog: true
      kin_score: 21.6
      mcp:
        status: none
      name: Quickpay
      slug: quickpay
      sources:
      - https://marketplace.pretix.eu/
      status: profiled
      tags:
      - E-Commerce
      - European
      - Fintech
      - Payments
      tier: declared
      url: /providers/quickpay/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - pretix
      band: emerging
      in_catalog: true
      kin_score: 16.5
      mcp:
        source: https://github.com/PAYONE-GmbH/omnichannel-mcp
        status: verified
      name: PAYONE
      slug: payone
      sources:
      - https://marketplace.pretix.eu/
      status: profiled
      tags:
      - Card Payments
      - E-Commerce
      - Payments
      - Point-of-Sale
      tier: declared
      url: /providers/payone/
    - agent_band: null
      agent_readiness: null
      apps:
      - pretix
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Datatrans
      slug: datatrans
      sources:
      - https://marketplace.pretix.eu/
      status: queued for profiling
      tags: []
      tier: declared
      url: null
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
      - Indico
      - alf.io
      band: strong
      in_catalog: true
      kin_score: 65.1
      mcp:
        status: none
      name: reCAPTCHA
      slug: google-recaptcha
      sources:
      - https://github.com/alfio-event/alf.io/blob/main/src/main/java/alfio/model/system/ConfigurationKeys.java
      - https://github.com/indico/indico-plugins/tree/master/cloud_captchas
      status: profiled
      tags:
      - Abuse Prevention
      - Bot Detection
      - CAPTCHA
      - Fraud Prevention
      tier: observed
      url: /providers/google-recaptcha/
    - agent_band: agent-aware
      agent_readiness: 17.5
      apps:
      - Indico
      band: thin
      in_catalog: true
      kin_score: 31.1
      mcp:
        status: none
      name: hCaptcha
      slug: hcaptcha
      sources:
      - https://github.com/indico/indico-plugins/tree/master/cloud_captchas
      status: profiled
      tags:
      - Bot Defense
      - CAPTCHA
      - Privacy
      - hCaptcha
      tier: observed
      url: /providers/hcaptcha/
    - agent_band: agent-aware
      agent_readiness: 24.2
      apps:
      - Hi.Events
      band: thin
      in_catalog: true
      kin_score: 28.8
      mcp:
        source: https://github.com/cloudflare/mcp
        status: verified
      name: Cloudflare Turnstile
      slug: cloudflare-turnstile
      sources:
      - https://github.com/HiEventsDev/Hi.Events/blob/develop/backend/.env.example
      status: profiled
      tags:
      - Bot Defense
      - CAPTCHA
      - Cloudflare
      - Turnstile
      tier: observed
      url: /providers/cloudflare-turnstile/
    - agent_band: agent-aware
      agent_readiness: 17.5
      apps:
      - pretalx
      band: thin
      in_catalog: true
      kin_score: 27.9
      mcp:
        status: none
      name: Friendly Captcha
      slug: friendly-captcha
      sources:
      - https://github.com/pretalx/pretalx-friendly-captcha
      status: profiled
      tags:
      - Bot Defense
      - CAPTCHA
      - Privacy
      - Proof of Work
      tier: declared
      url: /providers/friendly-captcha/
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
      - Tito
      - alf.io
      band: exemplar
      in_catalog: true
      kin_score: 79.7
      mcp:
        source: https://developers.google.com/analytics/devguides/MCP
        status: verified
      name: Google Analytics
      slug: google-analytics
      sources:
      - https://github.com/alfio-event/alf.io/blob/main/src/main/java/alfio/model/system/ConfigurationKeys.java
      - https://ti.to/features
      status: profiled
      tags:
      - Analytics
      - Data
      - Google
      - Metrics
      tier: observed
      url: /providers/google-analytics/
    - agent_band: agent-ready
      agent_readiness: 41.3
      apps:
      - Indico
      band: exemplar
      in_catalog: true
      kin_score: 70.7
      mcp:
        source: https://github.com/matomo-org/plugin-McpServer
        status: verified
      name: Matomo (Piwik)
      slug: matomo
      sources:
      - https://github.com/indico/indico-plugins/tree/master/piwik
      status: profiled
      tags:
      - Analytics
      - Open Source
      - Privacy
      - Web Analytics
      tier: observed
      url: /providers/matomo/
    - agent_band: agent-ready
      agent_readiness: 39.9
      apps:
      - Ticketmaster
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp:
        source: https://firebase.google.com/docs/ai-assistance/mcp-server
        status: verified
      name: Google Firebase Analytics / Crashlytics
      slug: google-firebase
      sources:
      - https://web.archive.org/web/20251108232712/https://reports.exodus-privacy.eu.org/en/reports/com.ticketmaster.mobile.android.na/latest/
      status: profiled
      tags:
      - Analytics
      - Authentication
      - Backend-as-a-Service
      - Cloud Messaging
      tier: observed
      url: /providers/google-firebase/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.10
      key: AE-150.10.10
      name: Transactional Email
      url: /capabilities/email/
      via_parent: Email
    providers:
    - agent_band: agent-ready
      agent_readiness: 40.7
      apps:
      - alf.io
      band: exemplar
      in_catalog: true
      kin_score: 84.0
      mcp:
        status: none
      name: SendGrid
      slug: sendgrid
      sources:
      - https://github.com/alfio-event/alf.io/tree/main/src/main/java/alfio/manager/system
      status: profiled
      tags:
      - Email
      - Email API
      - Marketing Email
      - SMTP
      tier: observed
      url: /providers/sendgrid/
    - agent_band: agent-ready
      agent_readiness: 43.0
      apps:
      - Hi.Events
      band: exemplar
      in_catalog: true
      kin_score: 70.5
      mcp:
        source: https://github.com/ActiveCampaign/postmark-mcp
        status: verified
      name: Postmark
      slug: postmark
      sources:
      - https://github.com/HiEventsDev/Hi.Events/blob/develop/backend/composer.json
      status: profiled
      tags:
      - Deliverability
      - Email
      - Messaging
      - Transactional Email
      tier: observed
      url: /providers/postmark/
    - agent_band: agent-aware
      agent_readiness: 22.9
      apps:
      - alf.io
      band: developing
      in_catalog: true
      kin_score: 50.5
      mcp:
        source: https://github.com/mailgun/mailjet-mcp-server
        status: verified
      name: Mailjet
      slug: mailjet
      sources:
      - https://github.com/alfio-event/alf.io/tree/main/src/main/java/alfio/manager/system
      status: profiled
      tags:
      - Email
      - Email Delivery
      - Marketing Email
      - SMTP
      tier: observed
      url: /providers/mailjet/
    - agent_band: agent-aware
      agent_readiness: 19.2
      apps:
      - alf.io
      band: thin
      in_catalog: true
      kin_score: 31.6
      mcp:
        source: https://github.com/mailgun/mailgun-mcp-server
        status: verified
      name: Mailgun
      slug: mailgun
      sources:
      - https://github.com/alfio-event/alf.io/tree/main/src/main/java/alfio/manager/system
      status: profiled
      tags:
      - Email
      - Email Verification
      - SMTP
      - Transactional Email
      tier: observed
      url: /providers/mailgun/
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 52.0
      apps:
      - Luma
      - pretix
      band: exemplar
      in_catalog: true
      kin_score: 91.9
      mcp:
        source: https://developers.hubspot.com/mcp
        status: verified
      name: HubSpot
      slug: hubspot
      sources:
      - https://help.luma.com/p/integrations
      - https://marketplace.pretix.eu/
      status: profiled
      tags:
      - Analytics
      - CRM
      - Commerce
      - Content
      tier: declared
      url: /providers/hubspot/
    - agent_band: agent-ready
      agent_readiness: 53.6
      apps:
      - Luma
      band: exemplar
      in_catalog: true
      kin_score: 88.0
      mcp:
        source: https://github.com/salesforcecli/mcp
        status: verified
      name: Salesforce
      slug: salesforce
      sources:
      - https://help.luma.com/p/integrations
      status: profiled
      tags:
      - Analytics
      - Artificial Intelligence
      - Cloud
      - Fortune 500
      tier: declared
      url: /providers/salesforce/
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
      - Hi.Events
      - Indico
      - pretix
      band: exemplar
      in_catalog: true
      kin_score: 80.7
      mcp:
        source: https://docs.sentry.io/product/sentry-mcp/
        status: verified
      name: Sentry
      slug: sentry-system
      sources:
      - https://github.com/HiEventsDev/Hi.Events/blob/develop/backend/composer.json
      - https://github.com/indico/indico/blob/master/requirements.in
      - https://github.com/pretix/pretix/blob/master/pyproject.toml
      status: profiled
      tags:
      - APM
      - Application Monitoring
      - Bug Tracking
      - Developer Tools
      tier: observed
      url: /providers/sentry-system/
  - capability:
      attribution: API Evangelist extension
      id: AE-120.20.10
      key: AE-120.20.10
      name: Base Map Tiles
      url: /capabilities/maps-tiles/
      via_parent: Maps & Tiles
    providers:
    - agent_band: agent-native
      agent_readiness: 54.4
      apps:
      - alf.io
      band: exemplar
      in_catalog: true
      kin_score: 79.0
      mcp:
        status: none
      name: HERE
      slug: here
      sources:
      - https://github.com/alfio-event/alf.io/blob/main/src/main/java/alfio/model/system/ConfigurationKeys.java
      status: profiled
      tags:
      - Location
      - Mapping
      - Maps
      - Spatial
      tier: observed
      url: /providers/here/
    - agent_band: agent-ready
      agent_readiness: 33.0
      apps:
      - alf.io
      band: exemplar
      in_catalog: true
      kin_score: 73.6
      mcp:
        source: https://developers.google.com/maps/ai/grounding-lite
        status: verified
      name: Google Maps
      slug: google-maps
      sources:
      - https://github.com/alfio-event/alf.io/blob/main/src/main/java/alfio/model/system/ConfigurationKeys.java
      status: profiled
      tags:
      - Environment
      - Geocoding
      - Geolocation
      - Maps
      tier: observed
      url: /providers/google-maps/
  - capability:
      attribution: API Evangelist extension
      id: AE-120.10.30
      key: AE-120.10.30
      name: Address Validation & Autocomplete
      url: /capabilities/geocoding/
      via_parent: Geocoding
    providers:
    - agent_band: agent-ready
      agent_readiness: 40.3
      apps:
      - Hi.Events
      band: strong
      in_catalog: true
      kin_score: 62.4
      mcp:
        source: https://developers.google.com/maps/ai/grounding-lite
        status: verified
      name: Google Places
      slug: google-places
      sources:
      - https://github.com/HiEventsDev/Hi.Events/blob/develop/backend/.env.example
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
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 31.0
      apps:
      - Indico
      band: developing
      in_catalog: true
      kin_score: 44.9
      mcp:
        source: https://github.com/owncloud/ocis-mcp-server
        status: verified
      name: ownCloud
      slug: owncloud
      sources:
      - https://github.com/indico/indico-plugins/tree/master/owncloud
      status: profiled
      tags:
      - Cloud Storage
      - Data Sovereignty
      - File Sharing
      - Secure Collaboration
      tier: observed
      url: /providers/owncloud/
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
      - Ticketmaster
      band: strong
      in_catalog: true
      kin_score: 59.5
      mcp:
        status: none
      name: mParticle
      slug: mparticle
      sources:
      - https://web.archive.org/web/20251108232712/https://reports.exodus-privacy.eu.org/en/reports/com.ticketmaster.mobile.android.na/latest/
      status: profiled
      tags:
      - Analytics
      - CDP
      - Customer Data Platform
      - Identity Resolution
      tier: observed
      url: /providers/mparticle/
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 52.3
      apps:
      - Ticketmaster
      band: exemplar
      in_catalog: true
      kin_score: 77.6
      mcp:
        status: none
      name: Salesforce Marketing Cloud
      slug: salesforce-marketing-cloud
      sources:
      - https://web.archive.org/web/20251108232712/https://reports.exodus-privacy.eu.org/en/reports/com.ticketmaster.mobile.android.na/latest/
      status: profiled
      tags:
      - Automation
      - Content Management
      - Customer Journey
      - Digital Marketing
      tier: observed
      url: /providers/salesforce-marketing-cloud/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    providers:
    - agent_band: agent-ready
      agent_readiness: 56.4
      apps:
      - pretix
      band: exemplar
      in_catalog: true
      kin_score: 81.3
      mcp:
        source: https://developers.brevo.com/docs/mcp-protocol
        status: verified
      name: Newsletter2Go
      slug: brevo
      sources:
      - https://marketplace.pretix.eu/
      status: profiled
      tags:
      - Email Marketing
      - Marketing
      - Marketing Automation
      - Transactional Email
      tier: declared
      url: /providers/brevo/
  - capability:
      attribution: API Evangelist extension
      id: AE-120.50.10
      key: AE-120.50.10
      name: IP Geolocation
      url: /capabilities/device-ip-location/
      via_parent: Device & IP Location
    providers:
    - agent_band: agent-aware
      agent_readiness: 23.7
      apps:
      - pretix
      band: thin
      in_catalog: true
      kin_score: 31.5
      mcp:
        status: none
      name: MaxMind
      slug: maxmind
      sources:
      - https://github.com/pretix/pretix/blob/master/pyproject.toml
      status: profiled
      tags:
      - Fraud Prevention
      - Geolocation
      - IP Intelligence
      - Risk Scoring
      tier: observed
      url: /providers/maxmind/
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 38.3
      apps:
      - pretix
      band: exemplar
      in_catalog: true
      kin_score: 74.4
      mcp:
        source: https://docs.slack.dev/ai/mcp-server/
        status: verified
      name: Slack
      slug: slack
      sources:
      - https://marketplace.pretix.eu/
      status: profiled
      tags:
      - Bots
      - Chat
      - Collaboration
      - Messaging
      tier: declared
      url: /providers/slack/
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
      - Ticketmaster
      band: exemplar
      in_catalog: true
      kin_score: 72.1
      mcp:
        source: https://registry.modelcontextprotocol.io/v0/servers?search=appsflyer
        status: verified
      name: AppsFlyer
      slug: appsflyer
      sources:
      - https://web.archive.org/web/20251108232712/https://reports.exodus-privacy.eu.org/en/reports/com.ticketmaster.mobile.android.na/latest/
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
      id: AE-150.60
      key: AE-150.60
      name: Video Calling
      url: /capabilities/video-calling/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 56.8
      apps:
      - Indico
      band: strong
      in_catalog: true
      kin_score: 57.1
      mcp:
        source: https://developers.zoom.us/docs/mcp/
        status: verified
      name: Zoom
      slug: zoom
      sources:
      - https://github.com/indico/indico-plugins/tree/master/vc_zoom
      status: profiled
      tags:
      - Chat
      - Collaboration
      - Video
      - Zoom
      tier: observed
      url: /providers/zoom/
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
      - Luma
      band: exemplar
      in_catalog: true
      kin_score: 72.9
      mcp:
        source: https://zapier.com/mcp
        status: verified
      name: Zapier
      slug: zapier
      sources:
      - https://help.luma.com/p/integrations
      status: profiled
      tags:
      - Integration
      - Workflow Automation
      - Zapier
      - iPaaS
      tier: declared
      url: /providers/zapier/
  layer: common
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
      agent_readiness: 46.6
      apps:
      - Hi.Events
      band: exemplar
      in_catalog: true
      kin_score: 86.4
      mcp:
        source: https://docs.anthropic.com/en/docs/agents-and-tools/mcp-connector
        status: verified
      name: Anthropic
      slug: anthropic
      sources:
      - https://github.com/HiEventsDev/Hi.Events/blob/develop/backend/.env.example
      status: profiled
      tags:
      - Anthropic
      - Artificial Intelligence
      - Claude
      - LLM
      tier: observed
      url: /providers/anthropic/
  layer: agent
summary:
  coverage_pct: 96.1
  declared_only: 22
  distinct_providers: 51
  in_catalog: 49
  mcp:
    documented: 1
    none: 22
    unchecked: 2
    verified: 26
  mcp_verified: 26
  mean_kin_score: 56.1
  observed: 29
  queued: 2
  reference_apps: 8
title: 'Events & Ticketing: application blueprint'
---
