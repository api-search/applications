---
app: SuiteCRM
app_slug: suitecrm
app_url: https://github.com/salesagility/SuiteCRM
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-230.30.10
  key: AE-230.30.10
  layer: domain
  name: Data Enrichment
  providers:
  - InsideView
  url: /capabilities/company-contact-data/
  via_parent: Company & Contact Data
- attribution: API Evangelist extension
  id: AE-150.80
  key: AE-150.80
  layer: domain
  name: Mailbox & Calendar Sync
  providers:
  - Google APIs
  url: /capabilities/mailbox-calendar-sync/
  via_parent: null
- attribution: Turbo EA
  id: BC-400.60.40
  key: BC-400.60.40
  layer: domain
  name: Social Media Management
  providers:
  - Facebook
  - X (Twitter)
  url: /capabilities/digital-marketing-management/
  via_parent: Digital Marketing Management
- attribution: API Evangelist extension
  id: AE-160.70
  key: AE-160.70
  layer: common
  name: Bot Protection & CAPTCHA
  providers:
  - Google reCAPTCHA
  url: /capabilities/bot-protection-captcha/
  via_parent: null
- attribution: Turbo EA
  id: BC-600.60.50
  key: BC-600.60.50
  layer: common
  name: Integration and API Management
  providers:
  - Amazon SQS
  url: /capabilities/it-application-management/
  via_parent: IT Application Management
- attribution: API Evangelist extension
  id: AE-120.20
  key: AE-120.20
  layer: common
  name: Maps & Tiles
  providers:
  - Google Maps
  url: /capabilities/maps-tiles/
  via_parent: null
- attribution: Turbo EA
  id: BC-3710
  key: media-asset-management
  layer: common
  name: Media Asset Management
  providers:
  - Amazon S3
  - Azure Blob Storage
  - Google Cloud Storage
  url: /capabilities/media-asset-management/
  via_parent: null
category:
  id: crm-sales
  name: CRM & Sales Pipeline
  url: /applications/crm-sales/
counts:
  declared: 0
  observed: 10
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/salesagility/SuiteCRM-Core/master/composer.json
- route: dependency manifest
  url: https://raw.githubusercontent.com/salesagility/SuiteCRM/master/composer.json
- route: source code
  url: https://github.com/salesagility/SuiteCRM/tree/master/include/social
- route: source code
  url: https://github.com/salesagility/SuiteCRM/tree/master/modules
- route: source code
  url: https://github.com/salesagility/SuiteCRM/tree/master/modules/Connectors/connectors/sources/ext/rest
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
    mcp: &id001
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-s3
    status: profiled
    tags: &id002
    - Amazon Web Services
    - Archives
    - Backup
    - Cloud Storage
    url: /providers/amazon-s3/
  layer: common
  name: Amazon S3
  provider: amazon-s3
  says: ships the Amazon S3 SDK or integration code
  source: https://raw.githubusercontent.com/salesagility/SuiteCRM-Core/master/composer.json
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-600.60.50
    key: BC-600.60.50
    name: Integration and API Management
    url: /capabilities/it-application-management/
    via_parent: IT Application Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 34.4
    band: exemplar
    in_catalog: true
    kin_score: 70.5
    mcp: &id003
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-sqs
    status: profiled
    tags: &id004
    - Amazon Web Services
    - Cloud
    - Distributed Systems
    - Messaging
    url: /providers/amazon-sqs/
  layer: common
  name: Amazon SQS
  provider: amazon-sqs
  says: ships the Amazon SQS SDK or integration code
  source: https://raw.githubusercontent.com/salesagility/SuiteCRM-Core/master/composer.json
  tier: observed
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
    agent_readiness: 37.9
    band: strong
    in_catalog: true
    kin_score: 66.3
    mcp: &id005
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-azure-blob-storage
    status: profiled
    tags: &id006
    - Blobs
    - Cloud Storage
    - Microsoft
    - Microsoft Azure
    url: /providers/microsoft-azure-blob-storage/
  layer: common
  name: Azure Blob Storage
  provider: microsoft-azure-blob-storage
  says: ships the Azure Blob Storage SDK or integration code
  source: https://raw.githubusercontent.com/salesagility/SuiteCRM-Core/master/composer.json
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-400.60.40
    key: BC-400.60.40
    name: Social Media Management
    url: /capabilities/digital-marketing-management/
    via_parent: Digital Marketing Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 28.1
    band: developing
    in_catalog: true
    kin_score: 43.7
    mcp: &id007
      status: none
    slug: facebook
    status: profiled
    tags: &id008
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
  layer: domain
  name: Facebook
  provider: facebook
  says: ships the Facebook SDK or integration code
  source: https://github.com/salesagility/SuiteCRM/tree/master/include/social
  tier: observed
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
    agent_readiness: 47.8
    band: exemplar
    in_catalog: true
    kin_score: 68.9
    mcp: &id009
      source: https://github.com/google/mcp
      status: verified
    slug: google
    status: profiled
    tags: &id010
    - Advertising
    - Cloud
    - Developers
    - Google
    url: /providers/google/
  layer: domain
  name: Google APIs
  provider: google
  says: ships the Google APIs SDK or integration code
  source: https://raw.githubusercontent.com/salesagility/SuiteCRM/master/composer.json
  tier: observed
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
  source: https://raw.githubusercontent.com/salesagility/SuiteCRM-Core/master/composer.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-120.20
    key: AE-120.20
    name: Maps & Tiles
    url: /capabilities/maps-tiles/
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
  source: https://github.com/salesagility/SuiteCRM/tree/master/modules
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
  source: https://raw.githubusercontent.com/salesagility/SuiteCRM/master/composer.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-230.30.10
    key: AE-230.30.10
    name: Data Enrichment
    url: /capabilities/company-contact-data/
    via_parent: Company & Contact Data
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 58.2
    band: exemplar
    in_catalog: true
    kin_score: 70.1
    mcp: &id017
      source: https://developer.demandbase.com/docs/mcp
      status: documented
    slug: demandbase
    status: profiled
    tags: &id018
    - AI Agents
    - Account Based Marketing
    - Advertising
    - B2B Marketing
    url: /providers/demandbase/
  layer: domain
  name: InsideView
  provider: demandbase
  says: ships the InsideView SDK or integration code
  source: https://github.com/salesagility/SuiteCRM/tree/master/modules/Connectors/connectors/sources/ext/rest
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-400.60.40
    key: BC-400.60.40
    name: Social Media Management
    url: /capabilities/digital-marketing-management/
    via_parent: Digital Marketing Management
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 59.9
    band: exemplar
    in_catalog: true
    kin_score: 75.0
    mcp: &id019
      source: https://github.com/xdevplatform/xmcp
      status: verified
    slug: x
    status: profiled
    tags: &id020
    - Conversations
    - Social
    - Spaces
    - X
    url: /providers/x/
  layer: domain
  name: X (Twitter)
  provider: x
  says: ships the X (Twitter) SDK or integration code
  source: https://github.com/salesagility/SuiteCRM/tree/master/include/social
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/crm-sales/suitecrm/
providers:
- agent_band: agent-ready
  agent_readiness: 34.8
  band: exemplar
  in_catalog: true
  kin_score: 76.6
  mcp: *id001
  name: Amazon S3
  slug: amazon-s3
  status: profiled
  tags: *id002
  url: /providers/amazon-s3/
- agent_band: agent-ready
  agent_readiness: 34.4
  band: exemplar
  in_catalog: true
  kin_score: 70.5
  mcp: *id003
  name: Amazon SQS
  slug: amazon-sqs
  status: profiled
  tags: *id004
  url: /providers/amazon-sqs/
- agent_band: agent-ready
  agent_readiness: 37.9
  band: strong
  in_catalog: true
  kin_score: 66.3
  mcp: *id005
  name: Azure Blob Storage
  slug: microsoft-azure-blob-storage
  status: profiled
  tags: *id006
  url: /providers/microsoft-azure-blob-storage/
- agent_band: agent-aware
  agent_readiness: 28.1
  band: developing
  in_catalog: true
  kin_score: 43.7
  mcp: *id007
  name: Facebook
  slug: facebook
  status: profiled
  tags: *id008
  url: /providers/facebook/
- agent_band: agent-ready
  agent_readiness: 47.8
  band: exemplar
  in_catalog: true
  kin_score: 68.9
  mcp: *id009
  name: Google APIs
  slug: google
  status: profiled
  tags: *id010
  url: /providers/google/
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
  agent_readiness: 58.2
  band: exemplar
  in_catalog: true
  kin_score: 70.1
  mcp: *id017
  name: InsideView
  slug: demandbase
  status: profiled
  tags: *id018
  url: /providers/demandbase/
- agent_band: agent-native
  agent_readiness: 59.9
  band: exemplar
  in_catalog: true
  kin_score: 75.0
  mcp: *id019
  name: X (Twitter)
  slug: x
  status: profiled
  tags: *id020
  url: /providers/x/
siblings:
- name: EspoCRM
  rows: 14
  url: /applications/crm-sales/espocrm/
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
- name: Twenty
  rows: 20
  url: /applications/crm-sales/twenty/
- name: Zoho CRM
  rows: 0
  url: /applications/crm-sales/zoho-crm/
sitemap: true
title: 'SuiteCRM: CRM & Sales Pipeline reference app'
---
