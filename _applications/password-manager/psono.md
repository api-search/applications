---
app: Psono
app_slug: psono
app_url: https://gitlab.com/esaqa/psono/psono-server
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-160.10.20
  key: AE-160.10.20
  layer: domain
  name: Multi-Factor Authentication
  providers:
  - Duo Security
  - iVALT
  - Yubico
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
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
  id: BC-600.50.20
  key: BC-600.50.20
  layer: common
  name: Storage Management
  providers:
  - Azure Blob Storage
  - Google Cloud Storage
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: API Evangelist extension
  id: AE-150.10.10
  key: AE-150.10.10
  layer: common
  name: Transactional Email
  providers:
  - Amazon SES
  - Brevo
  - Mailchimp (Mandrill)
  - Mailgun
  - Mailjet
  - Postmark
  - SendGrid
  - SparkPost
  url: /capabilities/email/
  via_parent: Email
category:
  id: password-manager
  name: Password Manager
  url: /applications/password-manager/
counts:
  declared: 0
  observed: 14
credits: []
evidence:
- route: dependency manifest
  url: https://gitlab.com/esaqa/psono/psono-server/-/raw/master/requirements.txt
- route: source code
  url: https://gitlab.com/esaqa/psono/psono-server/-/raw/master/psono/psono/settings.py
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
    agent_readiness: 39.4
    band: exemplar
    in_catalog: true
    kin_score: 80.6
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
  source: https://gitlab.com/esaqa/psono/psono-server/-/raw/master/psono/psono/settings.py
  tier: observed
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
    agent_readiness: 40.9
    band: exemplar
    in_catalog: true
    kin_score: 68.5
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
  source: https://gitlab.com/esaqa/psono/psono-server/-/raw/master/requirements.txt
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
    agent_readiness: 57.2
    band: exemplar
    in_catalog: true
    kin_score: 82.2
    mcp: &id005
      source: https://developers.brevo.com/docs/mcp-protocol
      status: verified
    slug: brevo
    status: profiled
    tags: &id006
    - Email Marketing
    - Marketing
    - Marketing Automation
    - Transactional Email
    url: /providers/brevo/
  layer: common
  name: Brevo
  provider: brevo
  says: ships the Brevo SDK or integration code
  source: https://gitlab.com/esaqa/psono/psono-server/-/raw/master/psono/psono/settings.py
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
    agent_readiness: 21.3
    band: thin
    in_catalog: true
    kin_score: 31.8
    mcp: &id007
      status: none
    slug: duo-security
    status: profiled
    tags: &id008
    - Authentication
    - Identity
    - MFA
    - Zero Trust
    url: /providers/duo-security/
  layer: domain
  name: Duo Security
  provider: duo-security
  says: ships the Duo Security SDK or integration code
  source: https://gitlab.com/esaqa/psono/psono-server/-/raw/master/requirements.txt
  tier: observed
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
    agent_readiness: 45.3
    band: exemplar
    in_catalog: true
    kin_score: 71.7
    mcp: &id009
      source: https://github.com/googleapis/gcloud-mcp
      status: verified
    slug: gcp-cloud-storage
    status: profiled
    tags: &id010
    - Archival
    - Backup
    - Blob Storage
    - Cloud Storage
    url: /providers/gcp-cloud-storage/
  layer: common
  name: Google Cloud Storage
  provider: gcp-cloud-storage
  says: ships the Google Cloud Storage SDK or integration code
  source: https://gitlab.com/esaqa/psono/psono-server/-/raw/master/requirements.txt
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
    agent_readiness: 17.6
    band: emerging
    in_catalog: true
    kin_score: 23.5
    mcp: &id011
      status: unknown
    slug: ivalt
    status: profiled
    tags: &id012
    - Artificial Intelligence
    - Company
    - Identity
    - Security
    url: /providers/ivalt/
  layer: domain
  name: iVALT
  provider: ivalt
  says: ships the iVALT SDK or integration code
  source: https://gitlab.com/esaqa/psono/psono-server/-/raw/master/psono/psono/settings.py
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
    agent_readiness: 42.3
    band: exemplar
    in_catalog: true
    kin_score: 78.3
    mcp: &id013
      status: none
    slug: mailchimp
    status: profiled
    tags: &id014
    - Campaigns
    - Email Marketing
    - Marketing Automation
    - Newsletters
    url: /providers/mailchimp/
  layer: common
  name: Mailchimp (Mandrill)
  provider: mailchimp
  says: ships the Mailchimp (Mandrill) SDK or integration code
  source: https://gitlab.com/esaqa/psono/psono-server/-/raw/master/psono/psono/settings.py
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
    agent_readiness: 19.0
    band: thin
    in_catalog: true
    kin_score: 32.6
    mcp: &id015
      source: https://github.com/mailgun/mailgun-mcp-server
      status: verified
    slug: mailgun
    status: profiled
    tags: &id016
    - Email
    - Email Verification
    - SMTP
    - Transactional Email
    url: /providers/mailgun/
  layer: common
  name: Mailgun
  provider: mailgun
  says: ships the Mailgun SDK or integration code
  source: https://gitlab.com/esaqa/psono/psono-server/-/raw/master/psono/psono/settings.py
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
    agent_readiness: 23.4
    band: developing
    in_catalog: true
    kin_score: 50.1
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
  source: https://gitlab.com/esaqa/psono/psono-server/-/raw/master/psono/psono/settings.py
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
    agent_readiness: 41.7
    band: exemplar
    in_catalog: true
    kin_score: 71.3
    mcp: &id019
      source: https://github.com/ActiveCampaign/postmark-mcp
      status: verified
    slug: postmark
    status: profiled
    tags: &id020
    - Deliverability
    - Email
    - Messaging
    - Transactional Email
    url: /providers/postmark/
  layer: common
  name: Postmark
  provider: postmark
  says: ships the Postmark SDK or integration code
  source: https://gitlab.com/esaqa/psono/psono-server/-/raw/master/psono/psono/settings.py
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
    agent_readiness: 40.1
    band: exemplar
    in_catalog: true
    kin_score: 87.3
    mcp: &id021
      status: none
    slug: sendgrid
    status: profiled
    tags: &id022
    - Email
    - Email API
    - Marketing Email
    - SMTP
    url: /providers/sendgrid/
  layer: common
  name: SendGrid
  provider: sendgrid
  says: ships the SendGrid SDK or integration code
  source: https://gitlab.com/esaqa/psono/psono-server/-/raw/master/psono/psono/settings.py
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
    kin_score: 80.6
    mcp: &id023
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id024
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: common
  name: Sentry
  provider: sentry-system
  says: ships the Sentry SDK or integration code
  source: https://gitlab.com/esaqa/psono/psono-server/-/raw/master/requirements.txt
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
    agent_readiness: 26.1
    band: thin
    in_catalog: true
    kin_score: 37.9
    mcp: &id025
      status: none
    slug: sparkpost
    status: profiled
    tags: &id026
    - Email
    - Email Delivery
    - Marketing Email
    - Transactional Email
    url: /providers/sparkpost/
  layer: common
  name: SparkPost
  provider: sparkpost
  says: ships the SparkPost SDK or integration code
  source: https://gitlab.com/esaqa/psono/psono-server/-/raw/master/psono/psono/settings.py
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
    agent_readiness: 25.6
    band: strong
    in_catalog: true
    kin_score: 58.3
    mcp: &id027
      status: none
    slug: yubico
    status: profiled
    tags: &id028
    - Authentication
    - Company
    - Enterprise
    - Security
    url: /providers/yubico/
  layer: domain
  name: Yubico
  provider: yubico
  says: ships the Yubico SDK or integration code
  source: https://gitlab.com/esaqa/psono/psono-server/-/raw/master/requirements.txt
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/password-manager/psono/
providers:
- agent_band: agent-ready
  agent_readiness: 39.4
  band: exemplar
  in_catalog: true
  kin_score: 80.6
  mcp: *id001
  name: Amazon SES
  slug: amazon-ses
  status: profiled
  tags: *id002
  url: /providers/amazon-ses/
- agent_band: agent-ready
  agent_readiness: 40.9
  band: exemplar
  in_catalog: true
  kin_score: 68.5
  mcp: *id003
  name: Azure Blob Storage
  slug: microsoft-azure-blob-storage
  status: profiled
  tags: *id004
  url: /providers/microsoft-azure-blob-storage/
- agent_band: agent-ready
  agent_readiness: 57.2
  band: exemplar
  in_catalog: true
  kin_score: 82.2
  mcp: *id005
  name: Brevo
  slug: brevo
  status: profiled
  tags: *id006
  url: /providers/brevo/
- agent_band: agent-aware
  agent_readiness: 21.3
  band: thin
  in_catalog: true
  kin_score: 31.8
  mcp: *id007
  name: Duo Security
  slug: duo-security
  status: profiled
  tags: *id008
  url: /providers/duo-security/
- agent_band: agent-ready
  agent_readiness: 45.3
  band: exemplar
  in_catalog: true
  kin_score: 71.7
  mcp: *id009
  name: Google Cloud Storage
  slug: gcp-cloud-storage
  status: profiled
  tags: *id010
  url: /providers/gcp-cloud-storage/
- agent_band: agent-aware
  agent_readiness: 17.6
  band: emerging
  in_catalog: true
  kin_score: 23.5
  mcp: *id011
  name: iVALT
  slug: ivalt
  status: profiled
  tags: *id012
  url: /providers/ivalt/
- agent_band: agent-ready
  agent_readiness: 42.3
  band: exemplar
  in_catalog: true
  kin_score: 78.3
  mcp: *id013
  name: Mailchimp (Mandrill)
  slug: mailchimp
  status: profiled
  tags: *id014
  url: /providers/mailchimp/
- agent_band: agent-aware
  agent_readiness: 19.0
  band: thin
  in_catalog: true
  kin_score: 32.6
  mcp: *id015
  name: Mailgun
  slug: mailgun
  status: profiled
  tags: *id016
  url: /providers/mailgun/
- agent_band: agent-aware
  agent_readiness: 23.4
  band: developing
  in_catalog: true
  kin_score: 50.1
  mcp: *id017
  name: Mailjet
  slug: mailjet
  status: profiled
  tags: *id018
  url: /providers/mailjet/
- agent_band: agent-ready
  agent_readiness: 41.7
  band: exemplar
  in_catalog: true
  kin_score: 71.3
  mcp: *id019
  name: Postmark
  slug: postmark
  status: profiled
  tags: *id020
  url: /providers/postmark/
- agent_band: agent-ready
  agent_readiness: 40.1
  band: exemplar
  in_catalog: true
  kin_score: 87.3
  mcp: *id021
  name: SendGrid
  slug: sendgrid
  status: profiled
  tags: *id022
  url: /providers/sendgrid/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.6
  mcp: *id023
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id024
  url: /providers/sentry-system/
- agent_band: agent-aware
  agent_readiness: 26.1
  band: thin
  in_catalog: true
  kin_score: 37.9
  mcp: *id025
  name: SparkPost
  slug: sparkpost
  status: profiled
  tags: *id026
  url: /providers/sparkpost/
- agent_band: agent-aware
  agent_readiness: 25.6
  band: strong
  in_catalog: true
  kin_score: 58.3
  mcp: *id027
  name: Yubico
  slug: yubico
  status: profiled
  tags: *id028
  url: /providers/yubico/
siblings:
- name: 1Password
  rows: 18
  url: /applications/password-manager/1password/
- name: Bitwarden
  rows: 40
  url: /applications/password-manager/bitwarden/
- name: KeePassXC
  rows: 2
  url: /applications/password-manager/keepassxc/
- name: Passbolt
  rows: 2
  url: /applications/password-manager/passbolt/
- name: Vaultwarden
  rows: 6
  url: /applications/password-manager/vaultwarden/
sitemap: true
title: 'Psono: Password Manager reference app'
---
