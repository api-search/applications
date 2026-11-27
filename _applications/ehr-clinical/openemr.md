---
app: OpenEMR
app_slug: openemr
app_url: https://github.com/openemr/openemr
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-150.110
  key: AE-150.110
  layer: domain
  name: Cloud Fax
  providers:
  - etherFAX
  url: /capabilities/cloud-fax/
  via_parent: null
- attribution: Turbo EA
  id: BC-2870
  key: healthcare-revenue-cycle-management
  layer: domain
  name: Healthcare Revenue Cycle Management
  providers:
  - Claim.Revolution
  url: /capabilities/healthcare-revenue-cycle-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-2860.10
  key: laboratory-services-management
  layer: domain
  name: Laboratory Services Management
  providers:
  - DORN
  url: /capabilities/laboratory-services-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-2850
  key: pharmacy-medication-management
  layer: domain
  name: Pharmacy & Medication Management
  providers:
  - Weno Exchange
  url: /capabilities/pharmacy-medication-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.60
  key: AE-150.60
  layer: domain
  name: Video Calling
  providers:
  - Comlink
  url: /capabilities/video-calling/
  via_parent: null
- attribution: Turbo EA
  id: BC-850.20
  key: external-communications-management
  layer: common
  name: External Communications Management
  providers:
  - RingCentral
  url: /capabilities/external-communications-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-160.10.20
  key: AE-160.10.20
  layer: common
  name: Multi-Factor Authentication
  providers:
  - Yubico
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: common
  name: Payment Processing Management
  providers:
  - Authorize.Net
  - Stripe
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.20.10
  key: AE-150.20.10
  layer: common
  name: SMS
  providers:
  - Clickatell
  - SignalWire
  - Twilio
  url: /capabilities/sms-messaging-apps/
  via_parent: SMS & Messaging Apps
- attribution: API Evangelist extension
  id: AE-160.10.30
  key: AE-160.10.30
  layer: common
  name: Social & Federated Login
  providers:
  - Google
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
category:
  id: ehr-clinical
  name: EHR & Clinical Practice
  url: /applications/ehr-clinical/
counts:
  declared: 0
  observed: 13
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/openemr/openemr/master/composer.json
- route: source code
  url: https://github.com/openemr/openemr/tree/master/interface/modules/custom_modules
- route: source code
  url: https://github.com/openemr/openemr/tree/master/interface/modules/custom_modules/oe-module-faxsms/src/Controller
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
    agent_readiness: 25.4
    band: thin
    in_catalog: true
    kin_score: 35.5
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
  layer: common
  name: Authorize.Net
  provider: authorizenet
  says: ships the Authorize.Net SDK or integration code
  source: https://raw.githubusercontent.com/openemr/openemr/master/composer.json
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-2870
    key: healthcare-revenue-cycle-management
    name: Healthcare Revenue Cycle Management
    url: /capabilities/healthcare-revenue-cycle-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 14.5
    band: developing
    in_catalog: true
    kin_score: 41.4
    mcp: &id003
      status: none
    slug: claimrev
    status: profiled
    tags: &id004
    - Billing
    - Claims
    - Company
    - Healthcare
    url: /providers/claimrev/
  layer: domain
  name: Claim.Revolution
  provider: claimrev
  says: ships the Claim.Revolution SDK or integration code
  source: https://raw.githubusercontent.com/openemr/openemr/master/composer.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.10
    key: AE-150.20.10
    name: SMS
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 28.9
    band: thin
    in_catalog: true
    kin_score: 38.8
    mcp: &id005
      status: none
    slug: clickatell
    status: profiled
    tags: &id006
    - Company
    - Messaging
    - SMS
    - WhatsApp
    url: /providers/clickatell/
  layer: common
  name: Clickatell
  provider: clickatell
  says: ships the Clickatell SDK or integration code
  source: https://github.com/openemr/openemr/tree/master/interface/modules/custom_modules/oe-module-faxsms/src/Controller
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.60
    key: AE-150.60
    name: Video Calling
    url: /capabilities/video-calling/
    via_parent: null
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id007
      status: none
    slug: comlink
    status: queued for profiling
    tags: &id008 []
    url: null
  layer: domain
  name: Comlink
  provider: comlink
  says: ships the Comlink SDK or integration code
  source: https://github.com/openemr/openemr/tree/master/interface/modules/custom_modules
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-2860.10
    key: laboratory-services-management
    name: Laboratory Services Management
    url: /capabilities/laboratory-services-management/
    via_parent: null
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id009
      status: unknown
    slug: dorn
    status: queued for profiling
    tags: &id010 []
    url: null
  layer: domain
  name: DORN
  provider: dorn
  says: ships the DORN SDK or integration code
  source: https://github.com/openemr/openemr/tree/master/interface/modules/custom_modules
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.110
    key: AE-150.110
    name: Cloud Fax
    url: /capabilities/cloud-fax/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.6
    band: developing
    in_catalog: true
    kin_score: 48.2
    mcp: &id011
      status: none
    slug: etherfax
    status: profiled
    tags: &id012
    - Artificial Intelligence
    - Cloud
    - Fax
    - Secure
    url: /providers/etherfax/
  layer: domain
  name: etherFAX
  provider: etherfax
  says: ships the etherFAX SDK or integration code
  source: https://github.com/openemr/openemr/tree/master/interface/modules/custom_modules/oe-module-faxsms/src/Controller
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
    agent_readiness: 47.8
    band: exemplar
    in_catalog: true
    kin_score: 68.9
    mcp: &id013
      source: https://github.com/google/mcp
      status: verified
    slug: google
    status: profiled
    tags: &id014
    - Advertising
    - Cloud
    - Developers
    - Google
    url: /providers/google/
  layer: common
  name: Google
  provider: google
  says: ships the Google SDK or integration code
  source: https://raw.githubusercontent.com/openemr/openemr/master/composer.json
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-850.20
    key: external-communications-management
    name: External Communications Management
    url: /capabilities/external-communications-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 43.6
    band: strong
    in_catalog: true
    kin_score: 59.4
    mcp: &id015
      source: https://developers.ringcentral.com/mcp
      status: documented
    slug: ringcentral
    status: profiled
    tags: &id016
    - Communications
    - UCaaS
    - Video
    - Voice
    url: /providers/ringcentral/
  layer: common
  name: RingCentral
  provider: ringcentral
  says: ships the RingCentral SDK or integration code
  source: https://raw.githubusercontent.com/openemr/openemr/master/composer.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.10
    key: AE-150.20.10
    name: SMS
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 41.9
    band: exemplar
    in_catalog: true
    kin_score: 74.2
    mcp: &id017
      status: none
    slug: signalwire
    status: profiled
    tags: &id018
    - CPaaS
    - Communications
    - Company
    - Voice
    url: /providers/signalwire/
  layer: common
  name: SignalWire
  provider: signalwire
  says: ships the SignalWire SDK or integration code
  source: https://github.com/openemr/openemr/tree/master/interface/modules/custom_modules/oe-module-faxsms/src/Controller
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
    mcp: &id019
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id020
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
  layer: common
  name: Stripe
  provider: stripe
  says: ships the Stripe SDK or integration code
  source: https://raw.githubusercontent.com/openemr/openemr/master/composer.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.10
    key: AE-150.20.10
    name: SMS
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 56.6
    band: exemplar
    in_catalog: true
    kin_score: 90.8
    mcp: &id021
      source: https://www.twilio.com/docs/ai/mcp
      status: verified
    slug: twilio
    status: profiled
    tags: &id022
    - Authentication
    - Communications
    - Contact Center
    - Email
    url: /providers/twilio/
  layer: common
  name: Twilio
  provider: twilio
  says: ships the Twilio SDK or integration code
  source: https://github.com/openemr/openemr/tree/master/interface/modules/custom_modules/oe-module-faxsms/src/Controller
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-2850
    key: pharmacy-medication-management
    name: Pharmacy & Medication Management
    url: /capabilities/pharmacy-medication-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 15.5
    mcp: &id023
      status: none
    slug: weno
    status: profiled
    tags: &id024
    - Company
    - Healthcare
    - Pharmacy
    - e-Prescribing
    url: /providers/weno/
  layer: domain
  name: Weno Exchange
  provider: weno
  says: ships the Weno Exchange SDK or integration code
  source: https://github.com/openemr/openemr/tree/master/interface/modules/custom_modules
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.20
    key: AE-160.10.20
    name: Multi-Factor Authentication
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.0
    band: strong
    in_catalog: true
    kin_score: 58.0
    mcp: &id025
      status: none
    slug: yubico
    status: profiled
    tags: &id026
    - Authentication
    - Company
    - Enterprise
    - Security
    url: /providers/yubico/
  layer: common
  name: Yubico
  provider: yubico
  says: ships the Yubico SDK or integration code
  source: https://raw.githubusercontent.com/openemr/openemr/master/composer.json
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/ehr-clinical/openemr/
providers:
- agent_band: agent-aware
  agent_readiness: 25.4
  band: thin
  in_catalog: true
  kin_score: 35.5
  mcp: *id001
  name: Authorize.Net
  slug: authorizenet
  status: profiled
  tags: *id002
  url: /providers/authorizenet/
- agent_band: agent-aware
  agent_readiness: 14.5
  band: developing
  in_catalog: true
  kin_score: 41.4
  mcp: *id003
  name: Claim.Revolution
  slug: claimrev
  status: profiled
  tags: *id004
  url: /providers/claimrev/
- agent_band: agent-ready
  agent_readiness: 28.9
  band: thin
  in_catalog: true
  kin_score: 38.8
  mcp: *id005
  name: Clickatell
  slug: clickatell
  status: profiled
  tags: *id006
  url: /providers/clickatell/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id007
  name: Comlink
  slug: comlink
  status: queued for profiling
  tags: *id008
  url: null
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id009
  name: DORN
  slug: dorn
  status: queued for profiling
  tags: *id010
  url: null
- agent_band: agent-ready
  agent_readiness: 38.6
  band: developing
  in_catalog: true
  kin_score: 48.2
  mcp: *id011
  name: etherFAX
  slug: etherfax
  status: profiled
  tags: *id012
  url: /providers/etherfax/
- agent_band: agent-ready
  agent_readiness: 47.8
  band: exemplar
  in_catalog: true
  kin_score: 68.9
  mcp: *id013
  name: Google
  slug: google
  status: profiled
  tags: *id014
  url: /providers/google/
- agent_band: agent-ready
  agent_readiness: 43.6
  band: strong
  in_catalog: true
  kin_score: 59.4
  mcp: *id015
  name: RingCentral
  slug: ringcentral
  status: profiled
  tags: *id016
  url: /providers/ringcentral/
- agent_band: agent-ready
  agent_readiness: 41.9
  band: exemplar
  in_catalog: true
  kin_score: 74.2
  mcp: *id017
  name: SignalWire
  slug: signalwire
  status: profiled
  tags: *id018
  url: /providers/signalwire/
- agent_band: agent-native
  agent_readiness: 57.6
  band: exemplar
  in_catalog: true
  kin_score: 82.0
  mcp: *id019
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id020
  url: /providers/stripe/
- agent_band: agent-native
  agent_readiness: 56.6
  band: exemplar
  in_catalog: true
  kin_score: 90.8
  mcp: *id021
  name: Twilio
  slug: twilio
  status: profiled
  tags: *id022
  url: /providers/twilio/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 15.5
  mcp: *id023
  name: Weno Exchange
  slug: weno
  status: profiled
  tags: *id024
  url: /providers/weno/
- agent_band: agent-aware
  agent_readiness: 25.0
  band: strong
  in_catalog: true
  kin_score: 58.0
  mcp: *id025
  name: Yubico
  slug: yubico
  status: profiled
  tags: *id026
  url: /providers/yubico/
siblings:
- name: Elation Health
  rows: 24
  url: /applications/ehr-clinical/elation-health/
- name: Healthie
  rows: 23
  url: /applications/ehr-clinical/healthie/
- name: Medplum
  rows: 37
  url: /applications/ehr-clinical/medplum/
- name: OpenMRS (O3 Reference Application)
  rows: 2
  url: /applications/ehr-clinical/openmrs-o3-reference-application/
- name: Tebra (Kareo + PatientPop)
  rows: 7
  url: /applications/ehr-clinical/tebra-kareo-patientpop/
sitemap: true
title: 'OpenEMR: EHR & Clinical Practice reference app'
---
