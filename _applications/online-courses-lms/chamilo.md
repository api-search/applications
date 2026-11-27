---
app: Chamilo
app_slug: chamilo
app_url: https://github.com/chamilo/chamilo-lms
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-930
  key: AE-930
  layer: domain
  name: Browser Document Editing (WOPI)
  providers:
  - ONLYOFFICE
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: API Evangelist extension
  id: AE-150.60
  key: AE-150.60
  layer: domain
  name: Video Calling
  providers:
  - BigBlueButton
  url: /capabilities/video-calling/
  via_parent: null
- attribution: Turbo EA
  id: BC-3710.30
  key: asset-storage-tiering
  layer: common
  name: Asset Storage & Tiering
  providers:
  - Azure Blob Storage
  - Google Cloud Storage
  url: /capabilities/asset-storage-tiering/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-120.20.10
  key: AE-120.20.10
  layer: common
  name: Base Map Tiles
  providers:
  - Google Maps
  url: /capabilities/maps-tiles/
  via_parent: Maps & Tiles
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: common
  name: Payment Processing Management
  providers:
  - Stripe
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-160.10.30
  key: AE-160.10.30
  layer: common
  name: Social & Federated Login
  providers:
  - Facebook
  - Keycloak
  - Microsoft
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
- attribution: API Evangelist extension
  id: AE-150.10.10
  key: AE-150.10.10
  layer: common
  name: Transactional Email
  providers:
  - Amazon SES
  - Brevo
  - Mailjet
  - Microsoft Graph
  url: /capabilities/email/
  via_parent: Email
category:
  id: online-courses-lms
  name: Online Courses & Learning Management
  url: /applications/online-courses-lms/
counts:
  declared: 0
  observed: 13
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/chamilo/chamilo-lms/blob/master/composer.json
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.10
    key: AE-150.10.10
    name: Transactional Email
    url: /capabilities/email/
    via_parent: Email
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.0
    band: exemplar
    in_catalog: true
    kin_score: 83.8
    mcp: &id001
      status: none
    slug: amazon-ses
    status: profiled
    tags: &id002
    - Amazon Web Services
    - Email
    - Email Deliverability
    - Email Service
    url: /providers/amazon-ses/
  layer: common
  name: Amazon SES
  provider: amazon-ses
  says: ships the Amazon SES SDK or integration code
  source: https://github.com/chamilo/chamilo-lms/blob/master/composer.json
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-3710.30
    key: asset-storage-tiering
    name: Asset Storage & Tiering
    url: /capabilities/asset-storage-tiering/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 37.9
    band: strong
    in_catalog: true
    kin_score: 66.3
    mcp: &id003
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-azure-blob-storage
    status: profiled
    tags: &id004
    - Blobs
    - Cloud Storage
    - Microsoft
    - Microsoft Azure
    url: /providers/microsoft-azure-blob-storage/
  layer: common
  name: Azure Blob Storage
  provider: microsoft-azure-blob-storage
  says: ships the Azure Blob Storage SDK or integration code
  source: https://github.com/chamilo/chamilo-lms/blob/master/composer.json
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
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 11.5
    mcp: &id005
      status: none
    slug: bigbluebutton
    status: profiled
    tags: &id006
    - Company
    - Education
    - Open Source
    - Video Conferencing
    url: /providers/bigbluebutton/
  layer: domain
  name: BigBlueButton
  provider: bigbluebutton
  says: ships the BigBlueButton SDK or integration code
  source: https://github.com/chamilo/chamilo-lms/blob/master/composer.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.10
    key: AE-150.10.10
    name: Transactional Email
    url: /capabilities/email/
    via_parent: Email
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 56.4
    band: exemplar
    in_catalog: true
    kin_score: 81.3
    mcp: &id007
      source: https://developers.brevo.com/docs/mcp-protocol
      status: verified
    slug: brevo
    status: profiled
    tags: &id008
    - Email Marketing
    - Marketing
    - Marketing Automation
    - Transactional Email
    url: /providers/brevo/
  layer: common
  name: Brevo
  provider: brevo
  says: ships the Brevo SDK or integration code
  source: https://github.com/chamilo/chamilo-lms/blob/master/composer.json
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
    agent_readiness: 28.1
    band: developing
    in_catalog: true
    kin_score: 43.7
    mcp: &id009
      status: none
    slug: facebook
    status: profiled
    tags: &id010
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
  layer: common
  name: Facebook
  provider: facebook
  says: ships the Facebook SDK or integration code
  source: https://github.com/chamilo/chamilo-lms/blob/master/composer.json
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-3710.30
    key: asset-storage-tiering
    name: Asset Storage & Tiering
    url: /capabilities/asset-storage-tiering/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 45.1
    band: exemplar
    in_catalog: true
    kin_score: 74.1
    mcp: &id011
      source: https://github.com/googleapis/gcloud-mcp
      status: verified
    slug: gcp-cloud-storage
    status: profiled
    tags: &id012
    - Archival
    - Backup
    - Blob Storage
    - Cloud Storage
    url: /providers/gcp-cloud-storage/
  layer: common
  name: Google Cloud Storage
  provider: gcp-cloud-storage
  says: ships the Google Cloud Storage SDK or integration code
  source: https://github.com/chamilo/chamilo-lms/blob/master/composer.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-120.20.10
    key: AE-120.20.10
    name: Base Map Tiles
    url: /capabilities/maps-tiles/
    via_parent: Maps & Tiles
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
  source: https://github.com/chamilo/chamilo-lms/blob/master/composer.json
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
    agent_readiness: 17.3
    band: thin
    in_catalog: true
    kin_score: 35.3
    mcp: &id015
      status: none
    slug: keycloak
    status: profiled
    tags: &id016
    - Authentication
    - Authorization
    - Identity and Access Management
    - OAuth
    url: /providers/keycloak/
  layer: common
  name: Keycloak
  provider: keycloak
  says: ships the Keycloak SDK or integration code
  source: https://github.com/chamilo/chamilo-lms/blob/master/composer.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.10
    key: AE-150.10.10
    name: Transactional Email
    url: /capabilities/email/
    via_parent: Email
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 22.9
    band: developing
    in_catalog: true
    kin_score: 50.5
    mcp: &id017
      source: https://github.com/mailgun/mailjet-mcp-server
      status: verified
    slug: mailjet
    status: profiled
    tags: &id018
    - Email
    - Email Delivery
    - Marketing Email
    - SMTP
    url: /providers/mailjet/
  layer: common
  name: Mailjet
  provider: mailjet
  says: ships the Mailjet SDK or integration code
  source: https://github.com/chamilo/chamilo-lms/blob/master/composer.json
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
    mcp: &id019
      status: none
    slug: microsoft-entra
    status: profiled
    tags: &id020
    - Authentication
    - Azure AD
    - Entra
    - Identity and Access Management
    url: /providers/microsoft-entra/
  layer: common
  name: Microsoft
  provider: microsoft-entra
  says: ships the Microsoft SDK or integration code
  source: https://github.com/chamilo/chamilo-lms/blob/master/composer.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.10
    key: AE-150.10.10
    name: Transactional Email
    url: /capabilities/email/
    via_parent: Email
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 39.0
    band: exemplar
    in_catalog: true
    kin_score: 69.7
    mcp: &id021
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-graph
    status: profiled
    tags: &id022
    - Azure AD
    - Collaboration
    - Contacts
    - Microsoft Graph
    url: /providers/microsoft-graph/
  layer: common
  name: Microsoft Graph
  provider: microsoft-graph
  says: ships the Microsoft Graph SDK or integration code
  source: https://github.com/chamilo/chamilo-lms/blob/master/composer.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-930
    key: AE-930
    name: Browser Document Editing (WOPI)
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id023
      status: unchecked
    slug: onlyoffice
    status: queued for profiling
    tags: &id024 []
    url: null
  layer: domain
  name: ONLYOFFICE
  provider: onlyoffice
  says: ships the ONLYOFFICE SDK or integration code
  source: https://github.com/chamilo/chamilo-lms/blob/master/composer.json
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
    mcp: &id025
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id026
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
  layer: common
  name: Stripe
  provider: stripe
  says: ships the Stripe SDK or integration code
  source: https://github.com/chamilo/chamilo-lms/blob/master/composer.json
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/online-courses-lms/chamilo/
providers:
- agent_band: agent-ready
  agent_readiness: 38.0
  band: exemplar
  in_catalog: true
  kin_score: 83.8
  mcp: *id001
  name: Amazon SES
  slug: amazon-ses
  status: profiled
  tags: *id002
  url: /providers/amazon-ses/
- agent_band: agent-ready
  agent_readiness: 37.9
  band: strong
  in_catalog: true
  kin_score: 66.3
  mcp: *id003
  name: Azure Blob Storage
  slug: microsoft-azure-blob-storage
  status: profiled
  tags: *id004
  url: /providers/microsoft-azure-blob-storage/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 11.5
  mcp: *id005
  name: BigBlueButton
  slug: bigbluebutton
  status: profiled
  tags: *id006
  url: /providers/bigbluebutton/
- agent_band: agent-ready
  agent_readiness: 56.4
  band: exemplar
  in_catalog: true
  kin_score: 81.3
  mcp: *id007
  name: Brevo
  slug: brevo
  status: profiled
  tags: *id008
  url: /providers/brevo/
- agent_band: agent-aware
  agent_readiness: 28.1
  band: developing
  in_catalog: true
  kin_score: 43.7
  mcp: *id009
  name: Facebook
  slug: facebook
  status: profiled
  tags: *id010
  url: /providers/facebook/
- agent_band: agent-ready
  agent_readiness: 45.1
  band: exemplar
  in_catalog: true
  kin_score: 74.1
  mcp: *id011
  name: Google Cloud Storage
  slug: gcp-cloud-storage
  status: profiled
  tags: *id012
  url: /providers/gcp-cloud-storage/
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
- agent_band: agent-aware
  agent_readiness: 17.3
  band: thin
  in_catalog: true
  kin_score: 35.3
  mcp: *id015
  name: Keycloak
  slug: keycloak
  status: profiled
  tags: *id016
  url: /providers/keycloak/
- agent_band: agent-aware
  agent_readiness: 22.9
  band: developing
  in_catalog: true
  kin_score: 50.5
  mcp: *id017
  name: Mailjet
  slug: mailjet
  status: profiled
  tags: *id018
  url: /providers/mailjet/
- agent_band: agent-ready
  agent_readiness: 28.7
  band: exemplar
  in_catalog: true
  kin_score: 70.3
  mcp: *id019
  name: Microsoft
  slug: microsoft-entra
  status: profiled
  tags: *id020
  url: /providers/microsoft-entra/
- agent_band: agent-ready
  agent_readiness: 39.0
  band: exemplar
  in_catalog: true
  kin_score: 69.7
  mcp: *id021
  name: Microsoft Graph
  slug: microsoft-graph
  status: profiled
  tags: *id022
  url: /providers/microsoft-graph/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id023
  name: ONLYOFFICE
  slug: onlyoffice
  status: queued for profiling
  tags: *id024
  url: null
- agent_band: agent-native
  agent_readiness: 57.6
  band: exemplar
  in_catalog: true
  kin_score: 82.0
  mcp: *id025
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id026
  url: /providers/stripe/
siblings:
- name: Canvas LMS
  rows: 25
  url: /applications/online-courses-lms/canvas-lms/
- name: Coursera
  rows: 4
  url: /applications/online-courses-lms/coursera/
- name: LearnWorlds
  rows: 55
  url: /applications/online-courses-lms/learnworlds/
- name: Moodle
  rows: 27
  url: /applications/online-courses-lms/moodle/
- name: Open edX
  rows: 8
  url: /applications/online-courses-lms/open-edx/
- name: Thinkific
  rows: 13
  url: /applications/online-courses-lms/thinkific/
- name: Udemy
  rows: 6
  url: /applications/online-courses-lms/udemy/
sitemap: true
title: 'Chamilo: Online Courses & Learning Management reference app'
---
