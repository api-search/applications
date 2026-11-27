---
app: OpenSign
app_slug: opensign
app_url: https://github.com/OpenSignLabs/OpenSign
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-160.80
  key: AE-160.80
  layer: domain
  name: Qualified Electronic Signatures & Trust Services
  providers:
  - eID Easy
  url: /capabilities/qualified-electronic-signatures-trust-services/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-916
  key: AE-916
  layer: common
  name: Cloud Drive & File Sync
  providers:
  - Google APIs
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - PostHog
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: Turbo EA
  id: BC-600.50.20
  key: BC-600.50.20
  layer: common
  name: Storage Management
  providers:
  - Amazon S3
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: API Evangelist extension
  id: AE-911
  key: AE-911
  layer: common
  name: Tag Management
  providers:
  - Google Tag Manager
  url: /capabilities/product-telemetry-instrumentation/
  via_parent: Product Telemetry Instrumentation
- attribution: API Evangelist extension
  id: AE-150.10.10
  key: AE-150.10.10
  layer: common
  name: Transactional Email
  providers:
  - Mailgun
  url: /capabilities/email/
  via_parent: Email
- attribution: API Evangelist extension
  id: AE-910
  key: AE-910
  layer: common
  name: Workflow Automation & iPaaS
  providers:
  - Zapier
  url: /capabilities/process-automation-governance/
  via_parent: Process Automation Governance
category:
  id: e-signature-contracts
  name: E-signature & Contract Management
  url: /applications/e-signature-contracts/
counts:
  declared: 1
  observed: 6
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/OpenSignLabs/OpenSign/main/apps/OpenSign/package.json
- route: dependency manifest
  url: https://raw.githubusercontent.com/OpenSignLabs/OpenSign/main/apps/OpenSignServer/package.json
- route: documentation
  url: https://github.com/OpenSignLabs/OpenSign
integrations:
- capability:
    attribution: Turbo EA
    id: BC-600.50.20
    key: BC-600.50.20
    name: Storage Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
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
  source: https://raw.githubusercontent.com/OpenSignLabs/OpenSign/main/apps/OpenSignServer/package.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.80
    key: AE-160.80
    name: Qualified Electronic Signatures & Trust Services
    url: /capabilities/qualified-electronic-signatures-trust-services/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 6.3
    band: thin
    in_catalog: true
    kin_score: 30.9
    mcp: &id003
      source: https://github.com/eideasy/eideasy-mcp
      status: verified
    slug: eid-easy
    status: profiled
    tags: &id004
    - Company
    - E-Signature
    - eID
    - eSealing
    url: /providers/eid-easy/
  layer: domain
  name: eID Easy
  provider: eid-easy
  says: ships the eID Easy SDK or integration code
  source: https://raw.githubusercontent.com/OpenSignLabs/OpenSign/main/apps/OpenSign/package.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-916
    key: AE-916
    name: Cloud Drive & File Sync
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 47.8
    band: exemplar
    in_catalog: true
    kin_score: 68.9
    mcp: &id005
      source: https://github.com/google/mcp
      status: verified
    slug: google
    status: profiled
    tags: &id006
    - Advertising
    - Cloud
    - Developers
    - Google
    url: /providers/google/
  layer: common
  name: Google APIs
  provider: google
  says: ships the Google APIs SDK or integration code
  source: https://raw.githubusercontent.com/OpenSignLabs/OpenSign/main/apps/OpenSignServer/package.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-911
    key: AE-911
    name: Tag Management
    url: /capabilities/product-telemetry-instrumentation/
    via_parent: Product Telemetry Instrumentation
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 35.8
    band: strong
    in_catalog: true
    kin_score: 65.8
    mcp: &id007
      status: none
    slug: google-tag-manager
    status: profiled
    tags: &id008
    - Analytics
    - Conversion Tracking
    - Marketing
    - Tag Management
    url: /providers/google-tag-manager/
  layer: common
  name: Google Tag Manager
  provider: google-tag-manager
  says: ships the Google Tag Manager SDK or integration code
  source: https://raw.githubusercontent.com/OpenSignLabs/OpenSign/main/apps/OpenSign/package.json
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
    agent_readiness: 19.2
    band: thin
    in_catalog: true
    kin_score: 31.6
    mcp: &id009
      source: https://github.com/mailgun/mailgun-mcp-server
      status: verified
    slug: mailgun
    status: profiled
    tags: &id010
    - Email
    - Email Verification
    - SMTP
    - Transactional Email
    url: /providers/mailgun/
  layer: common
  name: Mailgun
  provider: mailgun
  says: ships the Mailgun SDK or integration code
  source: https://raw.githubusercontent.com/OpenSignLabs/OpenSign/main/apps/OpenSignServer/package.json
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 56.2
    band: strong
    in_catalog: true
    kin_score: 57.9
    mcp: &id011
      source: https://github.com/PostHog/mcp
      status: verified
    slug: posthog
    status: profiled
    tags: &id012
    - A/B Testing
    - Analytics
    - Feature Flags
    - Open Source
    url: /providers/posthog/
  layer: common
  name: PostHog
  provider: posthog
  says: ships the PostHog SDK or integration code
  source: https://raw.githubusercontent.com/OpenSignLabs/OpenSign/main/apps/OpenSignServer/package.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-910
    key: AE-910
    name: Workflow Automation & iPaaS
    url: /capabilities/process-automation-governance/
    via_parent: Process Automation Governance
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 66.1
    band: exemplar
    in_catalog: true
    kin_score: 72.9
    mcp: &id013
      source: https://zapier.com/mcp
      status: verified
    slug: zapier
    status: profiled
    tags: &id014
    - Integration
    - Workflow Automation
    - Zapier
    - iPaaS
    url: /providers/zapier/
  layer: common
  name: Zapier
  provider: zapier
  says: lists Zapier as an integration
  source: https://github.com/OpenSignLabs/OpenSign
  tier: declared
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/e-signature-contracts/opensign/
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
- agent_band: agent-aware
  agent_readiness: 6.3
  band: thin
  in_catalog: true
  kin_score: 30.9
  mcp: *id003
  name: eID Easy
  slug: eid-easy
  status: profiled
  tags: *id004
  url: /providers/eid-easy/
- agent_band: agent-ready
  agent_readiness: 47.8
  band: exemplar
  in_catalog: true
  kin_score: 68.9
  mcp: *id005
  name: Google APIs
  slug: google
  status: profiled
  tags: *id006
  url: /providers/google/
- agent_band: agent-ready
  agent_readiness: 35.8
  band: strong
  in_catalog: true
  kin_score: 65.8
  mcp: *id007
  name: Google Tag Manager
  slug: google-tag-manager
  status: profiled
  tags: *id008
  url: /providers/google-tag-manager/
- agent_band: agent-aware
  agent_readiness: 19.2
  band: thin
  in_catalog: true
  kin_score: 31.6
  mcp: *id009
  name: Mailgun
  slug: mailgun
  status: profiled
  tags: *id010
  url: /providers/mailgun/
- agent_band: agent-ready
  agent_readiness: 56.2
  band: strong
  in_catalog: true
  kin_score: 57.9
  mcp: *id011
  name: PostHog
  slug: posthog
  status: profiled
  tags: *id012
  url: /providers/posthog/
- agent_band: agent-ready
  agent_readiness: 66.1
  band: exemplar
  in_catalog: true
  kin_score: 72.9
  mcp: *id013
  name: Zapier
  slug: zapier
  status: profiled
  tags: *id014
  url: /providers/zapier/
siblings:
- name: Documenso
  rows: 15
  url: /applications/e-signature-contracts/documenso/
- name: DocuSeal
  rows: 4
  url: /applications/e-signature-contracts/docuseal/
- name: DocuSign
  rows: 16
  url: /applications/e-signature-contracts/docusign/
- name: Dropbox Sign
  rows: 18
  url: /applications/e-signature-contracts/dropbox-sign/
- name: Zoho Sign
  rows: 24
  url: /applications/e-signature-contracts/zoho-sign/
sitemap: true
title: 'OpenSign: E-signature & Contract Management reference app'
---
