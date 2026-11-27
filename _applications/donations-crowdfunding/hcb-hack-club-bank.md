---
app: HCB (Hack Club Bank)
app_slug: hcb-hack-club-bank
app_url: https://github.com/hackclub/hcb
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-210.60
  key: bank-relationship-management
  layer: domain
  name: Bank Relationship Management
  providers:
  - Plaid
  url: /capabilities/bank-relationship-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-1340.60
  key: card-issuance-management
  layer: domain
  name: Card Issuance Management
  providers:
  - Stripe Issuing
  url: /capabilities/card-issuance-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-1340.10
  key: payment-initiation-management
  layer: domain
  name: Payment Initiation Management
  providers:
  - Column
  url: /capabilities/payment-initiation-management/
  via_parent: null
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
  id: BC-220.40
  key: tax-reporting-compliance
  layer: domain
  name: Tax Reporting & Compliance
  providers:
  - TaxBandits
  url: /capabilities/tax-reporting-compliance/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-160.70
  key: AE-160.70
  layer: common
  name: Bot Protection & CAPTCHA
  providers:
  - Cloudflare Turnstile
  url: /capabilities/bot-protection-captcha/
  via_parent: null
- attribution: Turbo EA
  id: BC-620.50.50
  key: BC-620.50.50
  layer: common
  name: Cryptography and Key Management
  providers:
  - AWS KMS
  url: /capabilities/security-architecture-management/
  via_parent: Security Architecture Management
- attribution: Turbo EA
  id: BC-620.20
  key: identity-access-management
  layer: common
  name: Identity & Access Management
  providers:
  - Google Workspace
  url: /capabilities/identity-access-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - AppSignal
  url: /capabilities/observability-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.20
  key: AE-150.20
  layer: common
  name: SMS & Messaging Apps
  providers:
  - Twilio
  url: /capabilities/sms-messaging-apps/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.50
  key: AE-170.50
  layer: common
  name: Social Networks & Community
  providers:
  - Discord
  url: /capabilities/social-networks-community/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-922
  key: AE-922
  layer: common
  name: Spreadsheets & No-Code Databases
  providers:
  - Airtable
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-600.50.20
  key: BC-600.50.20
  layer: common
  name: Storage Management
  providers:
  - Amazon S3
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
category:
  id: donations-crowdfunding
  name: Donations & Crowdfunding
  url: /applications/donations-crowdfunding/
counts:
  declared: 0
  observed: 13
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/hackclub/hcb/blob/main/Gemfile
- route: source code
  url: https://github.com/hackclub/hcb/tree/main/app/services
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-922
    key: AE-922
    name: Spreadsheets & No-Code Databases
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 52.3
    band: exemplar
    in_catalog: true
    kin_score: 68.2
    mcp: &id002
      source: https://github.com/Airtable/airtable-mcp-cli
      status: verified
    slug: airtable
    status: profiled
    tags: &id003
    - Application
    - Collaboration
    - Data
    - Database
    url: /providers/airtable/
  layer: common
  name: Airtable
  provider: airtable
  says: ships the Airtable SDK or integration code
  source: https://github.com/hackclub/hcb/blob/main/Gemfile
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
    agent_readiness: 34.8
    band: exemplar
    in_catalog: true
    kin_score: 76.6
    mcp: &id004
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-s3
    status: profiled
    tags: &id005
    - Amazon Web Services
    - Archives
    - Backup
    - Cloud Storage
    url: /providers/amazon-s3/
  layer: common
  name: Amazon S3
  provider: amazon-s3
  says: ships the Amazon S3 SDK or integration code
  source: https://github.com/hackclub/hcb/blob/main/Gemfile
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
    agent_readiness: 36.0
    band: developing
    in_catalog: true
    kin_score: 51.6
    mcp: &id006
      source: https://github.com/appsignal/appsignal-mcp
      status: verified
    slug: appsignal
    status: profiled
    tags: &id007
    - Error Tracking
    - Monitoring
    - Observability
    - Performance
    url: /providers/appsignal/
  layer: common
  name: AppSignal
  provider: appsignal
  says: ships the AppSignal SDK or integration code
  source: https://github.com/hackclub/hcb/blob/main/Gemfile
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-620.50.50
    key: BC-620.50.50
    name: Cryptography and Key Management
    url: /capabilities/security-architecture-management/
    via_parent: Security Architecture Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 44.1
    band: exemplar
    in_catalog: true
    kin_score: 76.8
    mcp: &id008
      status: none
    slug: amazon-kms
    status: profiled
    tags: &id009
    - Amazon Web Services
    - Cryptography
    - Data Protection
    - Encryption
    url: /providers/amazon-kms/
  layer: common
  name: AWS KMS
  provider: amazon-kms
  says: ships the AWS KMS SDK or integration code
  source: https://github.com/hackclub/hcb/blob/main/Gemfile
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
    agent_readiness: 24.2
    band: thin
    in_catalog: true
    kin_score: 28.8
    mcp: &id010
      source: https://github.com/cloudflare/mcp
      status: verified
    slug: cloudflare-turnstile
    status: profiled
    tags: &id011
    - Bot Defense
    - CAPTCHA
    - Cloudflare
    - Turnstile
    url: /providers/cloudflare-turnstile/
  layer: common
  name: Cloudflare Turnstile
  provider: cloudflare-turnstile
  says: ships the Cloudflare Turnstile SDK or integration code
  source: https://github.com/hackclub/hcb/tree/main/app/services
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-1340.10
    key: payment-initiation-management
    name: Payment Initiation Management
    url: /capabilities/payment-initiation-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.5
    band: thin
    in_catalog: true
    kin_score: 35.7
    mcp: &id012
      status: none
    slug: column
    status: profiled
    tags: &id013
    - ACH
    - Banking
    - Banking as a Service
    - Fintech
    url: /providers/column/
  layer: domain
  name: Column
  provider: column
  says: ships the Column SDK or integration code
  source: https://github.com/hackclub/hcb/tree/main/app/services
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.50
    key: AE-170.50
    name: Social Networks & Community
    url: /capabilities/social-networks-community/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.1
    band: developing
    in_catalog: true
    kin_score: 48.0
    mcp: &id014
      status: none
    slug: discord
    status: profiled
    tags: &id015
    - Chat
    - Communications
    - Discord
    - Gaming
    url: /providers/discord/
  layer: common
  name: Discord
  provider: discord
  says: ships the Discord SDK or integration code
  source: https://github.com/hackclub/hcb/blob/main/Gemfile
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-620.20
    key: identity-access-management
    name: Identity & Access Management
    url: /capabilities/identity-access-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 43.0
    band: exemplar
    in_catalog: true
    kin_score: 70.7
    mcp: &id016
      source: https://github.com/gemini-cli-extensions/workspace
      status: verified
    slug: google-workspace
    status: profiled
    tags: &id017
    - Calendar
    - Collaboration
    - Email
    - Productivity
    url: /providers/google-workspace/
  layer: common
  name: Google Workspace
  provider: google-workspace
  says: ships the Google Workspace SDK or integration code
  source: https://github.com/hackclub/hcb/tree/main/app/services
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-210.60
    key: bank-relationship-management
    name: Bank Relationship Management
    url: /capabilities/bank-relationship-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 51.1
    band: exemplar
    in_catalog: true
    kin_score: 86.3
    mcp: &id018
      source: https://plaid.com/docs/resources/mcp/
      status: verified
    slug: plaid
    status: profiled
    tags: &id019
    - Bank Accounts
    - Finance
    - Fintech
    - Open Banking
    url: /providers/plaid/
  layer: domain
  name: Plaid
  provider: plaid
  says: ships the Plaid SDK or integration code
  source: https://github.com/hackclub/hcb/tree/main/app/services
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  credit: null
  facts: &id001
    agent_band: agent-native
    agent_readiness: 57.6
    band: exemplar
    in_catalog: true
    kin_score: 82.0
    mcp: &id020
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id021
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
  layer: domain
  name: Stripe
  provider: stripe
  says: ships the Stripe SDK or integration code
  source: https://github.com/hackclub/hcb/tree/main/app/services
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-1340.60
    key: card-issuance-management
    name: Card Issuance Management
    url: /capabilities/card-issuance-management/
    via_parent: null
  credit: null
  facts: *id001
  layer: domain
  name: Stripe Issuing
  provider: stripe
  says: ships the Stripe Issuing SDK or integration code
  source: https://github.com/hackclub/hcb/tree/main/app/services
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-220.40
    key: tax-reporting-compliance
    name: Tax Reporting & Compliance
    url: /capabilities/tax-reporting-compliance/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 16.9
    band: developing
    in_catalog: true
    kin_score: 43.6
    mcp: &id022
      status: none
    slug: taxbandits
    status: profiled
    tags: &id023
    - Automation
    - Efiling
    - IRS
    - Tax
    url: /providers/taxbandits/
  layer: domain
  name: TaxBandits
  provider: taxbandits
  says: ships the TaxBandits SDK or integration code
  source: https://github.com/hackclub/hcb/tree/main/app/services
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.20
    key: AE-150.20
    name: SMS & Messaging Apps
    url: /capabilities/sms-messaging-apps/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 56.6
    band: exemplar
    in_catalog: true
    kin_score: 90.8
    mcp: &id024
      source: https://www.twilio.com/docs/ai/mcp
      status: verified
    slug: twilio
    status: profiled
    tags: &id025
    - Authentication
    - Communications
    - Contact Center
    - Email
    url: /providers/twilio/
  layer: common
  name: Twilio
  provider: twilio
  says: ships the Twilio SDK or integration code
  source: https://github.com/hackclub/hcb/tree/main/app/services
  tier: observed
kind: open-source-saas
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/donations-crowdfunding/hcb-hack-club-bank/
providers:
- agent_band: agent-ready
  agent_readiness: 52.3
  band: exemplar
  in_catalog: true
  kin_score: 68.2
  mcp: *id002
  name: Airtable
  slug: airtable
  status: profiled
  tags: *id003
  url: /providers/airtable/
- agent_band: agent-ready
  agent_readiness: 34.8
  band: exemplar
  in_catalog: true
  kin_score: 76.6
  mcp: *id004
  name: Amazon S3
  slug: amazon-s3
  status: profiled
  tags: *id005
  url: /providers/amazon-s3/
- agent_band: agent-ready
  agent_readiness: 36.0
  band: developing
  in_catalog: true
  kin_score: 51.6
  mcp: *id006
  name: AppSignal
  slug: appsignal
  status: profiled
  tags: *id007
  url: /providers/appsignal/
- agent_band: agent-ready
  agent_readiness: 44.1
  band: exemplar
  in_catalog: true
  kin_score: 76.8
  mcp: *id008
  name: AWS KMS
  slug: amazon-kms
  status: profiled
  tags: *id009
  url: /providers/amazon-kms/
- agent_band: agent-aware
  agent_readiness: 24.2
  band: thin
  in_catalog: true
  kin_score: 28.8
  mcp: *id010
  name: Cloudflare Turnstile
  slug: cloudflare-turnstile
  status: profiled
  tags: *id011
  url: /providers/cloudflare-turnstile/
- agent_band: agent-aware
  agent_readiness: 25.5
  band: thin
  in_catalog: true
  kin_score: 35.7
  mcp: *id012
  name: Column
  slug: column
  status: profiled
  tags: *id013
  url: /providers/column/
- agent_band: agent-ready
  agent_readiness: 33.1
  band: developing
  in_catalog: true
  kin_score: 48.0
  mcp: *id014
  name: Discord
  slug: discord
  status: profiled
  tags: *id015
  url: /providers/discord/
- agent_band: agent-ready
  agent_readiness: 43.0
  band: exemplar
  in_catalog: true
  kin_score: 70.7
  mcp: *id016
  name: Google Workspace
  slug: google-workspace
  status: profiled
  tags: *id017
  url: /providers/google-workspace/
- agent_band: agent-native
  agent_readiness: 51.1
  band: exemplar
  in_catalog: true
  kin_score: 86.3
  mcp: *id018
  name: Plaid
  slug: plaid
  status: profiled
  tags: *id019
  url: /providers/plaid/
- agent_band: agent-native
  agent_readiness: 57.6
  band: exemplar
  in_catalog: true
  kin_score: 82.0
  mcp: *id020
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id021
  url: /providers/stripe/
- agent_band: agent-aware
  agent_readiness: 16.9
  band: developing
  in_catalog: true
  kin_score: 43.6
  mcp: *id022
  name: TaxBandits
  slug: taxbandits
  status: profiled
  tags: *id023
  url: /providers/taxbandits/
- agent_band: agent-native
  agent_readiness: 56.6
  band: exemplar
  in_catalog: true
  kin_score: 90.8
  mcp: *id024
  name: Twilio
  slug: twilio
  status: profiled
  tags: *id025
  url: /providers/twilio/
siblings:
- name: Givebutter
  rows: 50
  url: /applications/donations-crowdfunding/givebutter/
- name: GiveWP
  rows: 3
  url: /applications/donations-crowdfunding/givewp/
- name: GoFundMe Pro (Classy)
  rows: 47
  url: /applications/donations-crowdfunding/gofundme-pro-classy/
- name: Liberapay
  rows: 4
  url: /applications/donations-crowdfunding/liberapay/
- name: Open Collective
  rows: 10
  url: /applications/donations-crowdfunding/open-collective/
- name: Patreon
  rows: 23
  url: /applications/donations-crowdfunding/patreon/
sitemap: true
title: 'HCB (Hack Club Bank): Donations & Crowdfunding reference app'
---
