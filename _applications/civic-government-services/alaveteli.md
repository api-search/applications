---
app: Alaveteli
app_slug: alaveteli
app_url: https://github.com/mysociety/alaveteli
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: domain
  name: Payment Processing Management
  providers:
  - Stripe
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-3710.30
  key: asset-storage-tiering
  layer: common
  name: Asset Storage & Tiering
  providers:
  - Amazon S3
  - Google Cloud Storage
  url: /capabilities/asset-storage-tiering/
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
category:
  id: civic-government-services
  name: Civic & Government Services
  url: /applications/civic-government-services/
counts:
  declared: 0
  observed: 4
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/mysociety/alaveteli/blob/develop/Gemfile
integrations:
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
  source: https://github.com/mysociety/alaveteli/blob/develop/Gemfile
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
    mcp: &id003
      source: https://github.com/googleapis/gcloud-mcp
      status: verified
    slug: gcp-cloud-storage
    status: profiled
    tags: &id004
    - Archival
    - Backup
    - Blob Storage
    - Cloud Storage
    url: /providers/gcp-cloud-storage/
  layer: common
  name: Google Cloud Storage
  provider: gcp-cloud-storage
  says: ships the Google Cloud Storage SDK or integration code
  source: https://github.com/mysociety/alaveteli/blob/develop/Gemfile
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
    mcp: &id005
      status: none
    slug: google-recaptcha
    status: profiled
    tags: &id006
    - Abuse Prevention
    - Bot Detection
    - CAPTCHA
    - Fraud Prevention
    url: /providers/google-recaptcha/
  layer: common
  name: Google reCAPTCHA
  provider: google-recaptcha
  says: ships the Google reCAPTCHA SDK or integration code
  source: https://github.com/mysociety/alaveteli/blob/develop/Gemfile
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
    mcp: &id007
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id008
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
  layer: domain
  name: Stripe
  provider: stripe
  says: ships the Stripe SDK or integration code
  source: https://github.com/mysociety/alaveteli/blob/develop/Gemfile
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/civic-government-services/alaveteli/
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
  agent_readiness: 45.1
  band: exemplar
  in_catalog: true
  kin_score: 74.1
  mcp: *id003
  name: Google Cloud Storage
  slug: gcp-cloud-storage
  status: profiled
  tags: *id004
  url: /providers/gcp-cloud-storage/
- agent_band: agent-ready
  agent_readiness: 34.9
  band: strong
  in_catalog: true
  kin_score: 65.1
  mcp: *id005
  name: Google reCAPTCHA
  slug: google-recaptcha
  status: profiled
  tags: *id006
  url: /providers/google-recaptcha/
- agent_band: agent-native
  agent_readiness: 57.6
  band: exemplar
  in_catalog: true
  kin_score: 82.0
  mcp: *id007
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id008
  url: /providers/stripe/
siblings:
- name: Accela Civic Platform
  rows: 4
  url: /applications/civic-government-services/accela-civic-platform/
- name: CONSUL Democracy
  rows: 5
  url: /applications/civic-government-services/consul-democracy/
- name: Decidim
  rows: 7
  url: /applications/civic-government-services/decidim/
- name: FixMyStreet
  rows: 8
  url: /applications/civic-government-services/fixmystreet/
- name: Go Vocal (CitizenLab)
  rows: 10
  url: /applications/civic-government-services/go-vocal-citizenlab/
- name: Granicus (govDelivery)
  rows: 1
  url: /applications/civic-government-services/granicus-govdelivery/
- name: SeeClickFix (CivicPlus)
  rows: 21
  url: /applications/civic-government-services/seeclickfix-civicplus/
sitemap: true
title: 'Alaveteli: Civic & Government Services reference app'
---
