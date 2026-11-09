---
app: CiviCRM
app_slug: civicrm
app_url: https://github.com/civicrm/civicrm-core
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-120.10.30
  key: AE-120.10.30
  layer: domain
  name: Address Validation & Autocomplete
  providers:
  - USPS Address API
  url: /capabilities/geocoding/
  via_parent: Geocoding
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: domain
  name: Payment Processing Management
  providers:
  - Authorize.net
  - Elavon
  - eWAY
  - First Data
  - PayJunction
  - PayPal
  - Realex Payments (Global Payments)
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-160.70
  key: AE-160.70
  layer: common
  name: Bot Protection & CAPTCHA
  providers:
  - Google reCAPTCHA
  url: /capabilities/bot-protection-captcha/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-120.10.10
  key: AE-120.10.10
  layer: common
  name: Forward Geocoding
  providers:
  - Google Maps Geocoding
  url: /capabilities/geocoding/
  via_parent: Geocoding
category:
  id: nonprofit-crm-fundraising
  name: Nonprofit CRM & Fundraising
  url: /applications/nonprofit-crm-fundraising/
counts:
  declared: 0
  observed: 10
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/civicrm/civicrm-core/blob/master/composer.json
- route: source code
  url: https://github.com/civicrm/civicrm-core/tree/master/CRM/Core/Payment
- route: source code
  url: https://github.com/civicrm/civicrm-core/tree/master/CRM/Utils/Address
- route: source code
  url: https://github.com/civicrm/civicrm-core/tree/master/CRM/Utils/Geocode
- route: source code
  url: https://github.com/civicrm/civicrm-core/tree/master/ext
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
    agent_band: agent-aware
    agent_readiness: 25.9
    band: thin
    in_catalog: true
    kin_score: 36.4
    mcp: &id001
      source: https://github.com/AuthorizeNet/authorize-net-mcp
      status: verified
    slug: authorizenet
    status: profiled
    tags: &id002
    - Company
    - Credit Cards
    - Payment Gateway
    - Payments
    url: /providers/authorizenet/
  layer: domain
  name: Authorize.net
  provider: authorizenet
  says: ships the Authorize.net SDK or integration code
  source: https://github.com/civicrm/civicrm-core/tree/master/CRM/Core/Payment
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
    agent_readiness: 32.4
    band: emerging
    in_catalog: true
    kin_score: 25.9
    mcp: &id003
      status: none
    slug: elavon
    status: profiled
    tags: &id004
    - Company
    - Fintech
    - Merchant Services
    - Payments
    url: /providers/elavon/
  layer: domain
  name: Elavon
  provider: elavon
  says: ships the Elavon SDK or integration code
  source: https://github.com/civicrm/civicrm-core/tree/master/ext
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
    agent_readiness: 5.4
    band: developing
    in_catalog: true
    kin_score: 49.0
    mcp: &id005
      status: none
    slug: eway
    status: profiled
    tags: &id006
    - Australia
    - Payment Gateway
    - Payment Processing
    - Payments
    url: /providers/eway/
  layer: domain
  name: eWAY
  provider: eway
  says: ships the eWAY SDK or integration code
  source: https://github.com/civicrm/civicrm-core/tree/master/ext
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
    agent_readiness: 7.1
    band: emerging
    in_catalog: true
    kin_score: 16.7
    mcp: &id007
      status: none
    slug: first-data
    status: profiled
    tags: &id008
    - Financial Services
    - Merchant Services
    - Payments
    - Transaction Processing
    url: /providers/first-data/
  layer: domain
  name: First Data
  provider: first-data
  says: ships the First Data SDK or integration code
  source: https://github.com/civicrm/civicrm-core/tree/master/CRM/Core/Payment
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
    agent_readiness: 36.0
    band: exemplar
    in_catalog: true
    kin_score: 71.4
    mcp: &id009
      source: https://developers.google.com/maps/ai/grounding-lite
      status: verified
    slug: google-maps
    status: profiled
    tags: &id010
    - Environment
    - Geocoding
    - Geolocation
    - Maps
    url: /providers/google-maps/
  layer: common
  name: Google Maps Geocoding
  provider: google-maps
  says: ships the Google Maps Geocoding SDK or integration code
  source: https://github.com/civicrm/civicrm-core/tree/master/CRM/Utils/Geocode
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.70
    key: AE-160.70
    name: Bot Protection & CAPTCHA
    url: /capabilities/bot-protection-captcha/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.6
    band: developing
    in_catalog: true
    kin_score: 48.1
    mcp: &id011
      status: none
    slug: google-recaptcha
    status: profiled
    tags: &id012
    - Abuse Prevention
    - Bot Detection
    - CAPTCHA
    - Fraud Prevention
    url: /providers/google-recaptcha/
  layer: common
  name: Google reCAPTCHA
  provider: google-recaptcha
  says: ships the Google reCAPTCHA SDK or integration code
  source: https://github.com/civicrm/civicrm-core/tree/master/ext
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
    agent_band: human-only
    agent_readiness: 0.0
    band: thin
    in_catalog: true
    kin_score: 28.9
    mcp: &id013
      status: none
    slug: payjunction
    status: profiled
    tags: &id014
    - B2B
    - Fintech
    - Payments
    - Software-as-a-Service
    url: /providers/payjunction/
  layer: domain
  name: PayJunction
  provider: payjunction
  says: ships the PayJunction SDK or integration code
  source: https://github.com/civicrm/civicrm-core/tree/master/CRM/Core/Payment
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
    mcp: &id015
      source: https://developer.paypal.com/tools/mcp-server/
      status: verified
    slug: paypal
    status: profiled
    tags: &id016
    - Billing
    - Commerce
    - Disputes
    - PayPal
    url: /providers/paypal/
  layer: domain
  name: PayPal
  provider: paypal
  says: ships the PayPal SDK or integration code
  source: https://github.com/civicrm/civicrm-core/tree/master/CRM/Core/Payment
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
    agent_readiness: 22.4
    band: thin
    in_catalog: true
    kin_score: 27.2
    mcp: &id017
      source: https://github.com/globalpayments/mcp-server
      status: verified
    slug: global-payments
    status: profiled
    tags: &id018
    - E-Commerce
    - Payment Processing
    - Payment Technology
    - Payments
    url: /providers/global-payments/
  layer: domain
  name: Realex Payments (Global Payments)
  provider: global-payments
  says: ships the Realex Payments (Global Payments) SDK or integration code
  source: https://github.com/civicrm/civicrm-core/tree/master/CRM/Core/Payment
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-120.10.30
    key: AE-120.10.30
    name: Address Validation & Autocomplete
    url: /capabilities/geocoding/
    via_parent: Geocoding
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.9
    band: thin
    in_catalog: true
    kin_score: 33.2
    mcp: &id019
      status: none
    slug: usps
    status: profiled
    tags: &id020
    - Government
    - Logistics
    - Postal Service
    - Shipping
    url: /providers/usps/
  layer: domain
  name: USPS Address API
  provider: usps
  says: ships the USPS Address API SDK or integration code
  source: https://github.com/civicrm/civicrm-core/tree/master/CRM/Utils/Address
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/nonprofit-crm-fundraising/civicrm/
providers:
- agent_band: agent-aware
  agent_readiness: 25.9
  band: thin
  in_catalog: true
  kin_score: 36.4
  mcp: *id001
  name: Authorize.net
  slug: authorizenet
  status: profiled
  tags: *id002
  url: /providers/authorizenet/
- agent_band: agent-ready
  agent_readiness: 32.4
  band: emerging
  in_catalog: true
  kin_score: 25.9
  mcp: *id003
  name: Elavon
  slug: elavon
  status: profiled
  tags: *id004
  url: /providers/elavon/
- agent_band: agent-aware
  agent_readiness: 5.4
  band: developing
  in_catalog: true
  kin_score: 49.0
  mcp: *id005
  name: eWAY
  slug: eway
  status: profiled
  tags: *id006
  url: /providers/eway/
- agent_band: agent-aware
  agent_readiness: 7.1
  band: emerging
  in_catalog: true
  kin_score: 16.7
  mcp: *id007
  name: First Data
  slug: first-data
  status: profiled
  tags: *id008
  url: /providers/first-data/
- agent_band: agent-ready
  agent_readiness: 36.0
  band: exemplar
  in_catalog: true
  kin_score: 71.4
  mcp: *id009
  name: Google Maps Geocoding
  slug: google-maps
  status: profiled
  tags: *id010
  url: /providers/google-maps/
- agent_band: agent-aware
  agent_readiness: 24.6
  band: developing
  in_catalog: true
  kin_score: 48.1
  mcp: *id011
  name: Google reCAPTCHA
  slug: google-recaptcha
  status: profiled
  tags: *id012
  url: /providers/google-recaptcha/
- agent_band: human-only
  agent_readiness: 0.0
  band: thin
  in_catalog: true
  kin_score: 28.9
  mcp: *id013
  name: PayJunction
  slug: payjunction
  status: profiled
  tags: *id014
  url: /providers/payjunction/
- agent_band: agent-ready
  agent_readiness: 37.1
  band: strong
  in_catalog: true
  kin_score: 54.7
  mcp: *id015
  name: PayPal
  slug: paypal
  status: profiled
  tags: *id016
  url: /providers/paypal/
- agent_band: agent-aware
  agent_readiness: 22.4
  band: thin
  in_catalog: true
  kin_score: 27.2
  mcp: *id017
  name: Realex Payments (Global Payments)
  slug: global-payments
  status: profiled
  tags: *id018
  url: /providers/global-payments/
- agent_band: agent-ready
  agent_readiness: 31.9
  band: thin
  in_catalog: true
  kin_score: 33.2
  mcp: *id019
  name: USPS Address API
  slug: usps
  status: profiled
  tags: *id020
  url: /providers/usps/
siblings:
- name: Bloomerang
  rows: 29
  url: /applications/nonprofit-crm-fundraising/bloomerang/
- name: DonorPerfect
  rows: 27
  url: /applications/nonprofit-crm-fundraising/donorperfect/
- name: Givebutter
  rows: 53
  url: /applications/nonprofit-crm-fundraising/givebutter/
- name: Little Green Light
  rows: 28
  url: /applications/nonprofit-crm-fundraising/little-green-light/
- name: Neon CRM
  rows: 18
  url: /applications/nonprofit-crm-fundraising/neon-crm/
sitemap: true
title: 'CiviCRM: Nonprofit CRM & Fundraising reference app'
---
