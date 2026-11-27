---
app: EspoCRM
app_slug: espocrm
app_url: https://github.com/espocrm/espocrm
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-430.30
  key: BC-430.30
  layer: domain
  name: Contact Centre Operations Management
  providers:
  - 3CX
  - Binotel
  - Starface
  - Twilio
  url: /capabilities/contact-centre-operations-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-420.10
  key: customer-data-management
  layer: domain
  name: Customer Data Management
  providers:
  - Google Contacts
  url: /capabilities/customer-data-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-400.60
  key: digital-marketing-management
  layer: domain
  name: Digital Marketing Management
  providers:
  - Mailchimp
  url: /capabilities/digital-marketing-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.80
  key: AE-150.80
  layer: domain
  name: Mailbox & Calendar Sync
  providers:
  - Gmail
  - Google Calendar
  - Microsoft Outlook
  url: /capabilities/mailbox-calendar-sync/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.60
  key: AE-150.60
  layer: domain
  name: Video Calling
  providers:
  - Zoom
  url: /capabilities/video-calling/
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
  id: AE-120.10
  key: AE-120.10
  layer: common
  name: Geocoding
  providers:
  - Google Maps
  url: /capabilities/geocoding/
  via_parent: null
- attribution: Turbo EA
  id: BC-3710
  key: media-asset-management
  layer: common
  name: Media Asset Management
  providers:
  - Amazon S3
  url: /capabilities/media-asset-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: common
  name: Payment Processing Management
  providers:
  - Stripe
  url: /capabilities/payment-processing-management/
  via_parent: null
category:
  id: crm-sales
  name: CRM & Sales Pipeline
  url: /applications/crm-sales/
counts:
  declared: 11
  observed: 3
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/espocrm/espocrm/master/composer.json
- route: integrations page
  url: https://www.espocrm.com/extensions/
- route: source code
  url: https://github.com/espocrm/espocrm/tree/master/application/Espo/Resources/metadata/integrations
integrations:
- capability:
    attribution: Turbo EA
    id: BC-3710
    key: media-asset-management
    name: Media Asset Management
    url: /capabilities/media-asset-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 34.8
    band: exemplar
    in_catalog: true
    kin_score: 76.6
    mcp: &id003
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-s3
    status: profiled
    tags: &id004
    - Amazon Web Services
    - Archives
    - Backup
    - Cloud Storage
    url: /providers/amazon-s3/
  layer: common
  name: Amazon S3
  provider: amazon-s3
  says: ships the Amazon S3 SDK or integration code
  source: https://raw.githubusercontent.com/espocrm/espocrm/master/composer.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-120.10
    key: AE-120.10
    name: Geocoding
    url: /capabilities/geocoding/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.0
    band: exemplar
    in_catalog: true
    kin_score: 73.6
    mcp: &id013
      source: https://developers.google.com/maps/ai/grounding-lite
      status: verified
    slug: google-maps
    status: profiled
    tags: &id014
    - Environment
    - Geocoding
    - Geolocation
    - Maps
    url: /providers/google-maps/
  layer: common
  name: Google Maps
  provider: google-maps
  says: ships the Google Maps SDK or integration code
  source: https://github.com/espocrm/espocrm/tree/master/application/Espo/Resources/metadata/integrations
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
    agent_band: agent-ready
    agent_readiness: 34.9
    band: strong
    in_catalog: true
    kin_score: 65.1
    mcp: &id015
      status: none
    slug: google-recaptcha
    status: profiled
    tags: &id016
    - Abuse Prevention
    - Bot Detection
    - CAPTCHA
    - Fraud Prevention
    url: /providers/google-recaptcha/
  layer: common
  name: Google reCAPTCHA
  provider: google-recaptcha
  says: ships the Google reCAPTCHA SDK or integration code
  source: https://github.com/espocrm/espocrm/tree/master/application/Espo/Resources/metadata/integrations
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-430.30
    key: BC-430.30
    name: Contact Centre Operations Management
    url: /capabilities/contact-centre-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: thin
    in_catalog: true
    kin_score: 29.0
    mcp: &id001
      status: none
    slug: 3cx
    status: profiled
    tags: &id002
    - Artificial Intelligence
    - Communications
    - Company
    - VoIP
    url: /providers/3cx/
  layer: domain
  name: 3CX
  provider: 3cx
  says: lists 3CX as an integration
  source: https://www.espocrm.com/extensions/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-430.30
    key: BC-430.30
    name: Contact Centre Operations Management
    url: /capabilities/contact-centre-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 4.8
    mcp: &id005
      status: unknown
    slug: binotel
    status: profiled
    tags: &id006
    - Business
    - Cloud
    - Company
    - Telephony
    url: /providers/binotel/
  layer: domain
  name: Binotel
  provider: binotel
  says: lists Binotel as an integration
  source: https://www.espocrm.com/extensions/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.80
    key: AE-150.80
    name: Mailbox & Calendar Sync
    url: /capabilities/mailbox-calendar-sync/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 43.2
    band: exemplar
    in_catalog: true
    kin_score: 66.8
    mcp: &id007
      source: https://developers.google.com/workspace/gmail/api/guides/configure-mcp-server
      status: verified
    slug: google-gmail
    status: profiled
    tags: &id008
    - Drafts
    - Email
    - Gmail
    - Google
    url: /providers/google-gmail/
  layer: domain
  name: Gmail
  provider: google-gmail
  says: lists Gmail as an integration
  source: https://www.espocrm.com/extensions/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.80
    key: AE-150.80
    name: Mailbox & Calendar Sync
    url: /capabilities/mailbox-calendar-sync/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 44.1
    band: strong
    in_catalog: true
    kin_score: 64.6
    mcp: &id009
      source: https://github.com/google/mcp
      status: verified
    slug: google-calendar
    status: profiled
    tags: &id010
    - Availability
    - Calendar
    - Event
    - Google
    url: /providers/google-calendar/
  layer: domain
  name: Google Calendar
  provider: google-calendar
  says: lists Google Calendar as an integration
  source: https://www.espocrm.com/extensions/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-420.10
    key: customer-data-management
    name: Customer Data Management
    url: /capabilities/customer-data-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.2
    band: strong
    in_catalog: true
    kin_score: 57.2
    mcp: &id011
      source: https://docs.cloud.google.com/mcp/supported-products
      status: verified
    slug: google-people
    status: profiled
    tags: &id012
    - Address Book
    - Contacts
    - Google
    - People
    url: /providers/google-people/
  layer: domain
  name: Google Contacts
  provider: google-people
  says: lists Google Contacts as an integration
  source: https://www.espocrm.com/extensions/
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
    agent_band: agent-ready
    agent_readiness: 41.9
    band: exemplar
    in_catalog: true
    kin_score: 77.7
    mcp: &id017
      status: none
    slug: mailchimp
    status: profiled
    tags: &id018
    - Campaigns
    - Email Marketing
    - Marketing Automation
    - Newsletters
    url: /providers/mailchimp/
  layer: domain
  name: Mailchimp
  provider: mailchimp
  says: lists Mailchimp as an integration
  source: https://www.espocrm.com/extensions/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.80
    key: AE-150.80
    name: Mailbox & Calendar Sync
    url: /capabilities/mailbox-calendar-sync/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 42.9
    band: exemplar
    in_catalog: true
    kin_score: 70.8
    mcp: &id019
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-outlook
    status: profiled
    tags: &id020
    - Calendar
    - Contacts
    - Email
    - Enterprise
    url: /providers/microsoft-outlook/
  layer: domain
  name: Microsoft Outlook
  provider: microsoft-outlook
  says: lists Microsoft Outlook as an integration
  source: https://www.espocrm.com/extensions/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-430.30
    key: BC-430.30
    name: Contact Centre Operations Management
    url: /capabilities/contact-centre-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 18.3
    band: minimal
    in_catalog: true
    kin_score: 9.1
    mcp: &id021
      status: unknown
    slug: starface
    status: profiled
    tags: &id022
    - Communications
    - Company
    - Unified Communications
    - VoIP
    url: /providers/starface/
  layer: domain
  name: Starface
  provider: starface
  says: lists Starface as an integration
  source: https://www.espocrm.com/extensions/
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
    mcp: &id023
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id024
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
  layer: common
  name: Stripe
  provider: stripe
  says: lists Stripe as an integration
  source: https://www.espocrm.com/extensions/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-430.30
    key: BC-430.30
    name: Contact Centre Operations Management
    url: /capabilities/contact-centre-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 56.6
    band: exemplar
    in_catalog: true
    kin_score: 90.8
    mcp: &id025
      source: https://www.twilio.com/docs/ai/mcp
      status: verified
    slug: twilio
    status: profiled
    tags: &id026
    - Authentication
    - Communications
    - Contact Center
    - Email
    url: /providers/twilio/
  layer: domain
  name: Twilio
  provider: twilio
  says: lists Twilio as an integration
  source: https://www.espocrm.com/extensions/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.60
    key: AE-150.60
    name: Video Calling
    url: /capabilities/video-calling/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 56.8
    band: strong
    in_catalog: true
    kin_score: 57.1
    mcp: &id027
      source: https://developers.zoom.us/docs/mcp/
      status: verified
    slug: zoom
    status: profiled
    tags: &id028
    - Chat
    - Collaboration
    - Video
    - Zoom
    url: /providers/zoom/
  layer: domain
  name: Zoom
  provider: zoom
  says: lists Zoom as an integration
  source: https://www.espocrm.com/extensions/
  tier: declared
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/crm-sales/espocrm/
providers:
- agent_band: human-only
  agent_readiness: 0.0
  band: thin
  in_catalog: true
  kin_score: 29.0
  mcp: *id001
  name: 3CX
  slug: 3cx
  status: profiled
  tags: *id002
  url: /providers/3cx/
- agent_band: agent-ready
  agent_readiness: 34.8
  band: exemplar
  in_catalog: true
  kin_score: 76.6
  mcp: *id003
  name: Amazon S3
  slug: amazon-s3
  status: profiled
  tags: *id004
  url: /providers/amazon-s3/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 4.8
  mcp: *id005
  name: Binotel
  slug: binotel
  status: profiled
  tags: *id006
  url: /providers/binotel/
- agent_band: agent-ready
  agent_readiness: 43.2
  band: exemplar
  in_catalog: true
  kin_score: 66.8
  mcp: *id007
  name: Gmail
  slug: google-gmail
  status: profiled
  tags: *id008
  url: /providers/google-gmail/
- agent_band: agent-ready
  agent_readiness: 44.1
  band: strong
  in_catalog: true
  kin_score: 64.6
  mcp: *id009
  name: Google Calendar
  slug: google-calendar
  status: profiled
  tags: *id010
  url: /providers/google-calendar/
- agent_band: agent-ready
  agent_readiness: 38.2
  band: strong
  in_catalog: true
  kin_score: 57.2
  mcp: *id011
  name: Google Contacts
  slug: google-people
  status: profiled
  tags: *id012
  url: /providers/google-people/
- agent_band: agent-ready
  agent_readiness: 33.0
  band: exemplar
  in_catalog: true
  kin_score: 73.6
  mcp: *id013
  name: Google Maps
  slug: google-maps
  status: profiled
  tags: *id014
  url: /providers/google-maps/
- agent_band: agent-ready
  agent_readiness: 34.9
  band: strong
  in_catalog: true
  kin_score: 65.1
  mcp: *id015
  name: Google reCAPTCHA
  slug: google-recaptcha
  status: profiled
  tags: *id016
  url: /providers/google-recaptcha/
- agent_band: agent-ready
  agent_readiness: 41.9
  band: exemplar
  in_catalog: true
  kin_score: 77.7
  mcp: *id017
  name: Mailchimp
  slug: mailchimp
  status: profiled
  tags: *id018
  url: /providers/mailchimp/
- agent_band: agent-ready
  agent_readiness: 42.9
  band: exemplar
  in_catalog: true
  kin_score: 70.8
  mcp: *id019
  name: Microsoft Outlook
  slug: microsoft-outlook
  status: profiled
  tags: *id020
  url: /providers/microsoft-outlook/
- agent_band: agent-aware
  agent_readiness: 18.3
  band: minimal
  in_catalog: true
  kin_score: 9.1
  mcp: *id021
  name: Starface
  slug: starface
  status: profiled
  tags: *id022
  url: /providers/starface/
- agent_band: agent-native
  agent_readiness: 57.6
  band: exemplar
  in_catalog: true
  kin_score: 82.0
  mcp: *id023
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id024
  url: /providers/stripe/
- agent_band: agent-native
  agent_readiness: 56.6
  band: exemplar
  in_catalog: true
  kin_score: 90.8
  mcp: *id025
  name: Twilio
  slug: twilio
  status: profiled
  tags: *id026
  url: /providers/twilio/
- agent_band: agent-ready
  agent_readiness: 56.8
  band: strong
  in_catalog: true
  kin_score: 57.1
  mcp: *id027
  name: Zoom
  slug: zoom
  status: profiled
  tags: *id028
  url: /providers/zoom/
siblings:
- name: HubSpot
  rows: 6
  url: /applications/crm-sales/hubspot/
- name: Krayin CRM
  rows: 1
  url: /applications/crm-sales/krayin-crm/
- name: Pipedrive
  rows: 17
  url: /applications/crm-sales/pipedrive/
- name: Salesforce
  rows: 1
  url: /applications/crm-sales/salesforce/
- name: SuiteCRM
  rows: 10
  url: /applications/crm-sales/suitecrm/
- name: Twenty
  rows: 20
  url: /applications/crm-sales/twenty/
- name: Zoho CRM
  rows: 0
  url: /applications/crm-sales/zoho-crm/
sitemap: true
title: 'EspoCRM: CRM & Sales Pipeline reference app'
---
