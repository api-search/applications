---
app: OpenEMR
app_slug: openemr
app_url: https://github.com/openemr/openemr
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-945
  key: AE-945
  layer: domain
  name: Clinical & Drug Terminology Services
  providers:
  - NLM RxNav / RxNorm
  url: /capabilities/medical-coding-management/
  via_parent: Medical Coding Management
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
  id: BC-2850
  key: pharmacy-medication-management
  layer: domain
  name: Pharmacy & Medication Management
  providers:
  - NewCrop eRx (Ensora)
  - Weno Exchange (eRx)
  url: /capabilities/pharmacy-medication-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.110
  key: AE-150.110
  layer: common
  name: Cloud Fax
  providers:
  - etherFAX
  - RingCentral
  url: /capabilities/cloud-fax/
  via_parent: null
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: common
  name: Payment Processing Management
  providers:
  - Authorize.net
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
category:
  id: pharmacy-prescriptions
  name: Pharmacy & Prescriptions
  url: /applications/pharmacy-prescriptions/
counts:
  declared: 0
  observed: 11
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/openemr/openemr/master/composer.json
- route: source code
  url: https://github.com/openemr/openemr/tree/master/interface/modules/custom_modules
- route: source code
  url: https://github.com/openemr/openemr/tree/master/interface/modules/custom_modules/oe-module-faxsms/src/Controller
- route: source code
  url: https://github.com/openemr/openemr/tree/master/src/Rx/Ensora
- route: source code
  url: https://raw.githubusercontent.com/openemr/openemr/master/src/Rx/RxList.php
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
  name: Authorize.net
  provider: authorizenet
  says: ships the Authorize.net SDK or integration code
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
    mcp: &id007
      status: none
    slug: etherfax
    status: profiled
    tags: &id008
    - Artificial Intelligence
    - Cloud
    - Fax
    - Secure
    url: /providers/etherfax/
  layer: common
  name: etherFAX
  provider: etherfax
  says: ships the etherFAX SDK or integration code
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
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id009
      status: unchecked
    slug: newcrop
    status: queued for profiling
    tags: &id010 []
    url: null
  layer: domain
  name: NewCrop eRx (Ensora)
  provider: newcrop
  says: ships the NewCrop eRx (Ensora) SDK or integration code
  source: https://github.com/openemr/openemr/tree/master/src/Rx/Ensora
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-945
    key: AE-945
    name: Clinical & Drug Terminology Services
    url: /capabilities/medical-coding-management/
    via_parent: Medical Coding Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 16.8
    band: emerging
    in_catalog: true
    kin_score: 26.1
    mcp: &id011
      status: unknown
    slug: national-library-of-medicine
    status: profiled
    tags: &id012
    - Federal Government
    - Health
    - Library
    - Medicine
    url: /providers/national-library-of-medicine/
  layer: domain
  name: NLM RxNav / RxNorm
  provider: national-library-of-medicine
  says: ships the NLM RxNav / RxNorm SDK or integration code
  source: https://raw.githubusercontent.com/openemr/openemr/master/src/Rx/RxList.php
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
    agent_readiness: 43.6
    band: strong
    in_catalog: true
    kin_score: 59.4
    mcp: &id013
      source: https://developers.ringcentral.com/mcp
      status: documented
    slug: ringcentral
    status: profiled
    tags: &id014
    - Communications
    - UCaaS
    - Video
    - Voice
    url: /providers/ringcentral/
  layer: common
  name: RingCentral
  provider: ringcentral
  says: ships the RingCentral SDK or integration code
  source: https://github.com/openemr/openemr/tree/master/interface/modules/custom_modules/oe-module-faxsms/src/Controller
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
    mcp: &id015
      status: none
    slug: signalwire
    status: profiled
    tags: &id016
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
    mcp: &id017
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id018
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
    mcp: &id019
      source: https://www.twilio.com/docs/ai/mcp
      status: verified
    slug: twilio
    status: profiled
    tags: &id020
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
    mcp: &id021
      status: none
    slug: weno
    status: profiled
    tags: &id022
    - Company
    - Healthcare
    - Pharmacy
    - e-Prescribing
    url: /providers/weno/
  layer: domain
  name: Weno Exchange (eRx)
  provider: weno
  says: ships the Weno Exchange (eRx) SDK or integration code
  source: https://github.com/openemr/openemr/tree/master/interface/modules/custom_modules/oe-module-weno
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/pharmacy-prescriptions/openemr/
providers:
- agent_band: agent-aware
  agent_readiness: 25.4
  band: thin
  in_catalog: true
  kin_score: 35.5
  mcp: *id001
  name: Authorize.net
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
- agent_band: agent-ready
  agent_readiness: 38.6
  band: developing
  in_catalog: true
  kin_score: 48.2
  mcp: *id007
  name: etherFAX
  slug: etherfax
  status: profiled
  tags: *id008
  url: /providers/etherfax/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id009
  name: NewCrop eRx (Ensora)
  slug: newcrop
  status: queued for profiling
  tags: *id010
  url: null
- agent_band: agent-aware
  agent_readiness: 16.8
  band: emerging
  in_catalog: true
  kin_score: 26.1
  mcp: *id011
  name: NLM RxNav / RxNorm
  slug: national-library-of-medicine
  status: profiled
  tags: *id012
  url: /providers/national-library-of-medicine/
- agent_band: agent-ready
  agent_readiness: 43.6
  band: strong
  in_catalog: true
  kin_score: 59.4
  mcp: *id013
  name: RingCentral
  slug: ringcentral
  status: profiled
  tags: *id014
  url: /providers/ringcentral/
- agent_band: agent-ready
  agent_readiness: 41.9
  band: exemplar
  in_catalog: true
  kin_score: 74.2
  mcp: *id015
  name: SignalWire
  slug: signalwire
  status: profiled
  tags: *id016
  url: /providers/signalwire/
- agent_band: agent-native
  agent_readiness: 57.6
  band: exemplar
  in_catalog: true
  kin_score: 82.0
  mcp: *id017
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id018
  url: /providers/stripe/
- agent_band: agent-native
  agent_readiness: 56.6
  band: exemplar
  in_catalog: true
  kin_score: 90.8
  mcp: *id019
  name: Twilio
  slug: twilio
  status: profiled
  tags: *id020
  url: /providers/twilio/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 15.5
  mcp: *id021
  name: Weno Exchange (eRx)
  slug: weno
  status: profiled
  tags: *id022
  url: /providers/weno/
siblings:
- name: CVS Health
  rows: 8
  url: /applications/pharmacy-prescriptions/cvs-health/
- name: GoodRx
  rows: 8
  url: /applications/pharmacy-prescriptions/goodrx/
- name: Medisafe
  rows: 9
  url: /applications/pharmacy-prescriptions/medisafe/
- name: Medplum
  rows: 11
  url: /applications/pharmacy-prescriptions/medplum/
- name: Walgreens
  rows: 8
  url: /applications/pharmacy-prescriptions/walgreens/
sitemap: true
title: 'OpenEMR: Pharmacy & Prescriptions reference app'
---
