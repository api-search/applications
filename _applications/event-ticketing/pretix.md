---
app: pretix
app_slug: pretix
app_url: https://github.com/pretix/pretix
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-210.50
  key: AE-210.50
  layer: domain
  name: Event Ticketing
  providers:
  - TicketSwap
  url: /capabilities/event-ticketing/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-210.20.10
  key: AE-210.20.10
  layer: domain
  name: Hotel Booking
  providers:
  - Stay22
  url: /capabilities/lodging-stays/
  via_parent: Lodging & Stays
- attribution: API Evangelist extension
  id: AE-210.50.10
  key: AE-210.50.10
  layer: domain
  name: Mobile Tickets & Wallet Passes
  providers:
  - Apple Wallet (Passbook)
  url: /capabilities/event-ticketing/
  via_parent: Event Ticketing
- attribution: Turbo EA
  id: BC-420
  key: customer-relationship-management
  layer: common
  name: Customer Relationship Management
  providers:
  - HubSpot
  url: /capabilities/customer-relationship-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.10.20
  key: AE-150.10.20
  layer: common
  name: Email Marketing Sends
  providers:
  - Newsletter2Go
  url: /capabilities/email/
  via_parent: Email
- attribution: API Evangelist extension
  id: AE-120.50.10
  key: AE-120.50.10
  layer: common
  name: IP Geolocation
  providers:
  - MaxMind
  url: /capabilities/device-ip-location/
  via_parent: Device & IP Location
- attribution: Turbo EA
  id: BC-850.10
  key: internal-communications-management
  layer: common
  name: Internal Communications Management
  providers:
  - Slack
  url: /capabilities/internal-communications-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Sentry
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: common
  name: Payment Processing Management
  providers:
  - PayPal
  - Stripe
  - Adyen
  - Authorize.net
  - BitPay
  - Computop
  - Datatrans
  - iyzico
  - Mollie
  - Nets Easy
  - PAYONE
  - Przelewy24
  - Quickpay
  - ready2order
  - Worldline Direct / Saferpay
  url: /capabilities/payment-processing-management/
  via_parent: null
category:
  id: event-ticketing
  name: Events & Ticketing
  url: /applications/event-ticketing/
counts:
  declared: 19
  observed: 4
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
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
  facts:
    agent_band: agent-aware
    agent_readiness: 23.7
    band: thin
    in_catalog: true
    kin_score: 31.5
    mcp: &id017
      status: none
    slug: maxmind
    status: profiled
    tags: &id018
    - Fraud Prevention
    - Geolocation
    - IP Intelligence
    - Risk Scoring
    url: /providers/maxmind/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 36.3
    band: strong
    in_catalog: true
    kin_score: 54.9
    mcp: &id027
      source: https://developer.paypal.com/tools/mcp-server/
      status: verified
    slug: paypal
    status: profiled
    tags: &id028
    - Billing
    - Commerce
    - Disputes
    - PayPal
    url: /providers/paypal/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 50.2
    band: exemplar
    in_catalog: true
    kin_score: 80.7
    mcp: &id035
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id036
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
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
  facts:
    agent_band: agent-native
    agent_readiness: 57.6
    band: exemplar
    in_catalog: true
    kin_score: 82.0
    mcp: &id041
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id042
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 36.5
    band: developing
    in_catalog: true
    kin_score: 52.9
    mcp: &id003
      status: none
    slug: apple
    status: profiled
    tags: &id004
    - Apple
    - Developers
    - iOS
    - macOS
    url: /providers/apple/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 25.4
    band: thin
    in_catalog: true
    kin_score: 35.5
    mcp: &id005
      source: https://github.com/AuthorizeNet/authorize-net-mcp
      status: verified
    slug: authorizenet
    status: profiled
    tags: &id006
    - Company
    - Credit Cards
    - Payment Gateway
    - Payments
    url: /providers/authorizenet/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 35.9
    band: thin
    in_catalog: true
    kin_score: 33.9
    mcp: &id007
      status: none
    slug: bitpay
    status: profiled
    tags: &id008
    - Bitcoin
    - Blockchain
    - Cryptocurrency
    - Payments
    url: /providers/bitpay/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 14.5
    band: thin
    in_catalog: true
    kin_score: 28.2
    mcp: &id009
      status: none
    slug: computop
    status: profiled
    tags: &id010
    - E-Commerce
    - Fintech
    - Germany
    - Payments
    url: /providers/computop/
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
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id011
      status: unchecked
    slug: datatrans
    status: queued for profiling
    tags: &id012 []
    url: null
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
  facts:
    agent_band: agent-ready
    agent_readiness: 52.0
    band: exemplar
    in_catalog: true
    kin_score: 91.9
    mcp: &id013
      source: https://developers.hubspot.com/mcp
      status: verified
    slug: hubspot
    status: profiled
    tags: &id014
    - Analytics
    - CRM
    - Commerce
    - Content
    url: /providers/hubspot/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 24.6
    band: developing
    in_catalog: true
    kin_score: 48.3
    mcp: &id015
      status: none
    slug: iyzico
    status: profiled
    tags: &id016
    - Company
    - Fintech
    - Payment Gateway
    - Payments
    url: /providers/iyzico/
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
  facts:
    agent_band: agent-native
    agent_readiness: 71.7
    band: exemplar
    in_catalog: true
    kin_score: 68.1
    mcp: &id019
      source: https://docs.mollie.com/docs/mcp-server
      status: verified
    slug: mollie
    status: profiled
    tags: &id020
    - Company
    - Financial Services
    - Fintech
    - Payments
    url: /providers/mollie/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 16.8
    band: thin
    in_catalog: true
    kin_score: 27.7
    mcp: &id021
      status: none
    slug: nexi
    status: profiled
    tags: &id022
    - Company
    - Europe
    - Fintech
    - Payments
    url: /providers/nexi/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 56.4
    band: exemplar
    in_catalog: true
    kin_score: 81.3
    mcp: &id023
      source: https://developers.brevo.com/docs/mcp-protocol
      status: verified
    slug: brevo
    status: profiled
    tags: &id024
    - Email Marketing
    - Marketing
    - Marketing Automation
    - Transactional Email
    url: /providers/brevo/
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
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 16.5
    mcp: &id025
      source: https://github.com/PAYONE-GmbH/omnichannel-mcp
      status: verified
    slug: payone
    status: profiled
    tags: &id026
    - Card Payments
    - E-Commerce
    - Payments
    - Point-of-Sale
    url: /providers/payone/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 26.3
    band: thin
    in_catalog: true
    kin_score: 36.9
    mcp: &id029
      status: none
    slug: przelewy24
    status: profiled
    tags: &id030
    - BLIK
    - Bank Transfers
    - Payment Gateway
    - Payments
    url: /providers/przelewy24/
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
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 21.6
    mcp: &id031
      status: none
    slug: quickpay
    status: profiled
    tags: &id032
    - E-Commerce
    - European
    - Fintech
    - Payments
    url: /providers/quickpay/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 30.4
    band: developing
    in_catalog: true
    kin_score: 53.7
    mcp: &id033
      status: none
    slug: ready2order
    status: profiled
    tags: &id034
    - Company
    - Payments
    - Point-of-Sale
    - Retail
    url: /providers/ready2order/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 38.3
    band: exemplar
    in_catalog: true
    kin_score: 74.4
    mcp: &id037
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id038
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 27.3
    band: developing
    in_catalog: true
    kin_score: 52.2
    mcp: &id039
      status: none
    slug: stay22
    status: profiled
    tags: &id040
    - Affiliate Marketing
    - Event
    - Software-as-a-Service
    - TravelTech
    url: /providers/stay22/
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
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 3.4
    mcp: &id043
      status: none
    slug: ticketswap
    status: profiled
    tags: &id044
    - Company
    url: /providers/ticketswap/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 41.5
    band: developing
    in_catalog: true
    kin_score: 54.0
    mcp: &id045
      status: none
    slug: wordline
    status: profiled
    tags: &id046
    - Acquiring
    - Issuing
    - Payment Processing
    - Payments
    url: /providers/wordline/
  layer: common
  name: Worldline Direct / Saferpay
  provider: wordline
  says: lists Worldline Direct / Saferpay as an integration
  source: https://marketplace.pretix.eu/
  tier: declared
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/event-ticketing/pretix/
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
  agent_readiness: 36.5
  band: developing
  in_catalog: true
  kin_score: 52.9
  mcp: *id003
  name: Apple Wallet (Passbook)
  slug: apple
  status: profiled
  tags: *id004
  url: /providers/apple/
- agent_band: agent-aware
  agent_readiness: 25.4
  band: thin
  in_catalog: true
  kin_score: 35.5
  mcp: *id005
  name: Authorize.net
  slug: authorizenet
  status: profiled
  tags: *id006
  url: /providers/authorizenet/
- agent_band: agent-ready
  agent_readiness: 35.9
  band: thin
  in_catalog: true
  kin_score: 33.9
  mcp: *id007
  name: BitPay
  slug: bitpay
  status: profiled
  tags: *id008
  url: /providers/bitpay/
- agent_band: agent-aware
  agent_readiness: 14.5
  band: thin
  in_catalog: true
  kin_score: 28.2
  mcp: *id009
  name: Computop
  slug: computop
  status: profiled
  tags: *id010
  url: /providers/computop/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id011
  name: Datatrans
  slug: datatrans
  status: queued for profiling
  tags: *id012
  url: null
- agent_band: agent-ready
  agent_readiness: 52.0
  band: exemplar
  in_catalog: true
  kin_score: 91.9
  mcp: *id013
  name: HubSpot
  slug: hubspot
  status: profiled
  tags: *id014
  url: /providers/hubspot/
- agent_band: agent-aware
  agent_readiness: 24.6
  band: developing
  in_catalog: true
  kin_score: 48.3
  mcp: *id015
  name: iyzico
  slug: iyzico
  status: profiled
  tags: *id016
  url: /providers/iyzico/
- agent_band: agent-aware
  agent_readiness: 23.7
  band: thin
  in_catalog: true
  kin_score: 31.5
  mcp: *id017
  name: MaxMind
  slug: maxmind
  status: profiled
  tags: *id018
  url: /providers/maxmind/
- agent_band: agent-native
  agent_readiness: 71.7
  band: exemplar
  in_catalog: true
  kin_score: 68.1
  mcp: *id019
  name: Mollie
  slug: mollie
  status: profiled
  tags: *id020
  url: /providers/mollie/
- agent_band: agent-aware
  agent_readiness: 16.8
  band: thin
  in_catalog: true
  kin_score: 27.7
  mcp: *id021
  name: Nets Easy
  slug: nexi
  status: profiled
  tags: *id022
  url: /providers/nexi/
- agent_band: agent-ready
  agent_readiness: 56.4
  band: exemplar
  in_catalog: true
  kin_score: 81.3
  mcp: *id023
  name: Newsletter2Go
  slug: brevo
  status: profiled
  tags: *id024
  url: /providers/brevo/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 16.5
  mcp: *id025
  name: PAYONE
  slug: payone
  status: profiled
  tags: *id026
  url: /providers/payone/
- agent_band: agent-ready
  agent_readiness: 36.3
  band: strong
  in_catalog: true
  kin_score: 54.9
  mcp: *id027
  name: PayPal
  slug: paypal
  status: profiled
  tags: *id028
  url: /providers/paypal/
- agent_band: agent-aware
  agent_readiness: 26.3
  band: thin
  in_catalog: true
  kin_score: 36.9
  mcp: *id029
  name: Przelewy24
  slug: przelewy24
  status: profiled
  tags: *id030
  url: /providers/przelewy24/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 21.6
  mcp: *id031
  name: Quickpay
  slug: quickpay
  status: profiled
  tags: *id032
  url: /providers/quickpay/
- agent_band: agent-ready
  agent_readiness: 30.4
  band: developing
  in_catalog: true
  kin_score: 53.7
  mcp: *id033
  name: ready2order
  slug: ready2order
  status: profiled
  tags: *id034
  url: /providers/ready2order/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.7
  mcp: *id035
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id036
  url: /providers/sentry-system/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id037
  name: Slack
  slug: slack
  status: profiled
  tags: *id038
  url: /providers/slack/
- agent_band: agent-aware
  agent_readiness: 27.3
  band: developing
  in_catalog: true
  kin_score: 52.2
  mcp: *id039
  name: Stay22
  slug: stay22
  status: profiled
  tags: *id040
  url: /providers/stay22/
- agent_band: agent-native
  agent_readiness: 57.6
  band: exemplar
  in_catalog: true
  kin_score: 82.0
  mcp: *id041
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id042
  url: /providers/stripe/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 3.4
  mcp: *id043
  name: TicketSwap
  slug: ticketswap
  status: profiled
  tags: *id044
  url: /providers/ticketswap/
- agent_band: agent-ready
  agent_readiness: 41.5
  band: developing
  in_catalog: true
  kin_score: 54.0
  mcp: *id045
  name: Worldline Direct / Saferpay
  slug: wordline
  status: profiled
  tags: *id046
  url: /providers/wordline/
siblings:
- name: alf.io
  rows: 13
  url: /applications/event-ticketing/alf-io/
- name: Hi.Events
  rows: 6
  url: /applications/event-ticketing/hi-events/
- name: Indico
  rows: 11
  url: /applications/event-ticketing/indico/
- name: Luma
  rows: 3
  url: /applications/event-ticketing/luma/
- name: pretalx
  rows: 4
  url: /applications/event-ticketing/pretalx/
- name: Ticketmaster
  rows: 4
  url: /applications/event-ticketing/ticketmaster/
- name: Tito
  rows: 3
  url: /applications/event-ticketing/tito/
sitemap: true
title: 'pretix: Events & Ticketing reference app'
---
