---
app: Gibbon
app_slug: gibbon
app_url: https://github.com/GibbonEdu/core
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-150.80
  key: mailbox-calendar-sync
  layer: common
  name: Mailbox & Calendar Sync
  providers:
  - Google APIs (google/apiclient)
  - Microsoft Graph
  url: /capabilities/mailbox-calendar-sync/
  via_parent: null
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: common
  name: Payment Processing Management
  providers:
  - PayPal
  - Stripe
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.20.10
  key: AE-150.20.10
  layer: common
  name: SMS
  providers:
  - OneWaySMS
  - Clockwork SMS
  - Nexmo (Vonage)
  - Textlocal
  - Twilio
  url: /capabilities/sms-messaging-apps/
  via_parent: SMS & Messaging Apps
- attribution: API Evangelist extension
  id: AE-160.10.30
  key: AE-160.10.30
  layer: common
  name: Social & Federated Login
  providers:
  - Google sign-in
  - Microsoft sign-in
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
category:
  id: school-admin-sis
  name: School Administration & SIS
  url: /applications/school-admin-sis/
counts:
  declared: 4
  observed: 7
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/GibbonEdu/core/blob/v31.0.00/composer.json
- route: source code
  url: https://github.com/GibbonEdu/core/blob/v31.0.00/modules/System%20Admin/thirdPartySettings.php
- route: source code
  url: https://github.com/GibbonEdu/core/tree/v31.0.00/src/Comms/Drivers
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-150.80
    key: mailbox-calendar-sync
    name: Mailbox & Calendar Sync
    url: /capabilities/mailbox-calendar-sync/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 47.8
    band: exemplar
    in_catalog: true
    kin_score: 68.9
    mcp: &id003
      source: https://github.com/google/mcp
      status: verified
    slug: google
    status: profiled
    tags: &id004
    - Advertising
    - Cloud
    - Developers
    - Google
    url: /providers/google/
  layer: common
  name: Google APIs (google/apiclient)
  provider: google
  says: ships the Google APIs (google/apiclient) SDK or integration code
  source: https://github.com/GibbonEdu/core/blob/v31.0.00/composer.json
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
    agent_readiness: 33.7
    band: strong
    in_catalog: true
    kin_score: 58.8
    mcp: &id005
      status: none
    slug: google-identity-platform
    status: profiled
    tags: &id006
    - Authentication
    - Google Cloud
    - Identity
    - Multi-Tenancy
    url: /providers/google-identity-platform/
  layer: common
  name: Google sign-in
  provider: google-identity-platform
  says: ships the Google sign-in SDK or integration code
  source: https://github.com/GibbonEdu/core/blob/v31.0.00/modules/System%20Admin/thirdPartySettings.php
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.80
    key: mailbox-calendar-sync
    name: Mailbox & Calendar Sync
    url: /capabilities/mailbox-calendar-sync/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 39.0
    band: exemplar
    in_catalog: true
    kin_score: 69.7
    mcp: &id007
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-graph
    status: profiled
    tags: &id008
    - Azure AD
    - Collaboration
    - Contacts
    - Microsoft Graph
    url: /providers/microsoft-graph/
  layer: common
  name: Microsoft Graph
  provider: microsoft-graph
  says: ships the Microsoft Graph SDK or integration code
  source: https://github.com/GibbonEdu/core/blob/v31.0.00/composer.json
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
    agent_readiness: 28.7
    band: exemplar
    in_catalog: true
    kin_score: 70.3
    mcp: &id009
      status: none
    slug: microsoft-entra
    status: profiled
    tags: &id010
    - Authentication
    - Azure AD
    - Entra
    - Identity and Access Management
    url: /providers/microsoft-entra/
  layer: common
  name: Microsoft sign-in
  provider: microsoft-entra
  says: ships the Microsoft sign-in SDK or integration code
  source: https://github.com/GibbonEdu/core/blob/v31.0.00/modules/System%20Admin/thirdPartySettings.php
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
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 13.1
    mcp: &id013
      status: unchecked
    slug: onewaysms
    status: profiled
    tags: &id014
    - Communications
    - Malaysia
    - Marketing
    - SMS
    url: /providers/onewaysms/
  layer: common
  name: OneWaySMS
  provider: onewaysms
  says: ships the OneWaySMS SDK or integration code
  source: https://github.com/GibbonEdu/core/tree/v31.0.00/src/Comms/Drivers
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
  layer: common
  name: PayPal
  provider: paypal
  says: ships the PayPal SDK or integration code
  source: https://github.com/GibbonEdu/core/blob/v31.0.00/composer.json
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
  source: https://github.com/GibbonEdu/core/blob/v31.0.00/composer.json
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
    agent_band: agent-aware
    agent_readiness: 12.7
    band: thin
    in_catalog: true
    kin_score: 37.8
    mcp: &id001
      status: unchecked
    slug: clockwork-sms
    status: profiled
    tags: &id002
    - Company
    - Marketing
    - SMS
    - United Kingdom
    url: /providers/clockwork-sms/
  layer: common
  name: Clockwork SMS
  provider: clockwork-sms
  says: lists Clockwork SMS as an integration
  source: https://github.com/GibbonEdu/core/blob/v31.0.00/modules/System%20Admin/thirdPartySettings.php
  tier: declared
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
    agent_readiness: 40.0
    band: exemplar
    in_catalog: true
    kin_score: 68.8
    mcp: &id011
      source: https://github.com/Vonage/vonage-mcp-server-documentation
      status: verified
    slug: vonage
    status: profiled
    tags: &id012
    - Communications
    - Messaging
    - Telecommunications
    - Video Conferencing
    url: /providers/vonage/
  layer: common
  name: Nexmo (Vonage)
  provider: vonage
  says: lists Nexmo (Vonage) as an integration
  source: https://github.com/GibbonEdu/core/blob/v31.0.00/modules/System%20Admin/thirdPartySettings.php
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.10
    key: AE-150.20.10
    name: SMS
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 3.6
    mcp: &id019
      status: unknown
    slug: textlocal
    status: profiled
    tags: &id020
    - Company
    url: /providers/textlocal/
  layer: common
  name: Textlocal
  provider: textlocal
  says: lists Textlocal as an integration
  source: https://github.com/GibbonEdu/core/blob/v31.0.00/modules/System%20Admin/thirdPartySettings.php
  tier: declared
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
  says: lists Twilio as an integration
  source: https://github.com/GibbonEdu/core/blob/v31.0.00/modules/System%20Admin/thirdPartySettings.php
  tier: declared
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/school-admin-sis/gibbon/
providers:
- agent_band: agent-aware
  agent_readiness: 12.7
  band: thin
  in_catalog: true
  kin_score: 37.8
  mcp: *id001
  name: Clockwork SMS
  slug: clockwork-sms
  status: profiled
  tags: *id002
  url: /providers/clockwork-sms/
- agent_band: agent-ready
  agent_readiness: 47.8
  band: exemplar
  in_catalog: true
  kin_score: 68.9
  mcp: *id003
  name: Google APIs (google/apiclient)
  slug: google
  status: profiled
  tags: *id004
  url: /providers/google/
- agent_band: agent-ready
  agent_readiness: 33.7
  band: strong
  in_catalog: true
  kin_score: 58.8
  mcp: *id005
  name: Google sign-in
  slug: google-identity-platform
  status: profiled
  tags: *id006
  url: /providers/google-identity-platform/
- agent_band: agent-ready
  agent_readiness: 39.0
  band: exemplar
  in_catalog: true
  kin_score: 69.7
  mcp: *id007
  name: Microsoft Graph
  slug: microsoft-graph
  status: profiled
  tags: *id008
  url: /providers/microsoft-graph/
- agent_band: agent-ready
  agent_readiness: 28.7
  band: exemplar
  in_catalog: true
  kin_score: 70.3
  mcp: *id009
  name: Microsoft sign-in
  slug: microsoft-entra
  status: profiled
  tags: *id010
  url: /providers/microsoft-entra/
- agent_band: agent-ready
  agent_readiness: 40.0
  band: exemplar
  in_catalog: true
  kin_score: 68.8
  mcp: *id011
  name: Nexmo (Vonage)
  slug: vonage
  status: profiled
  tags: *id012
  url: /providers/vonage/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 13.1
  mcp: *id013
  name: OneWaySMS
  slug: onewaysms
  status: profiled
  tags: *id014
  url: /providers/onewaysms/
- agent_band: agent-ready
  agent_readiness: 36.3
  band: strong
  in_catalog: true
  kin_score: 54.9
  mcp: *id015
  name: PayPal
  slug: paypal
  status: profiled
  tags: *id016
  url: /providers/paypal/
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
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 3.6
  mcp: *id019
  name: Textlocal
  slug: textlocal
  status: profiled
  tags: *id020
  url: /providers/textlocal/
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
siblings:
- name: Alma
  rows: 1
  url: /applications/school-admin-sis/alma/
- name: Classe365
  rows: 32
  url: /applications/school-admin-sis/classe365/
- name: Frappe Education
  rows: 2
  url: /applications/school-admin-sis/frappe-education/
- name: Gradelink
  rows: 11
  url: /applications/school-admin-sis/gradelink/
- name: Infinite Campus
  rows: 2
  url: /applications/school-admin-sis/infinite-campus/
- name: PowerSchool SIS
  rows: 2
  url: /applications/school-admin-sis/powerschool-sis/
- name: RosarioSIS
  rows: 1
  url: /applications/school-admin-sis/rosariosis/
- name: Veracross
  rows: 5
  url: /applications/school-admin-sis/veracross/
sitemap: true
title: 'Gibbon: School Administration & SIS reference app'
---
