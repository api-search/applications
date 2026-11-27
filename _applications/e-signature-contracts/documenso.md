---
app: Documenso
app_slug: documenso
app_url: https://github.com/documenso/documenso
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-620.50.50
  key: BC-620.50.50
  layer: domain
  name: Cryptography and Key Management
  providers:
  - Google Cloud HSM (KMS)
  url: /capabilities/security-architecture-management/
  via_parent: Security Architecture Management
- attribution: API Evangelist extension
  id: AE-918
  key: AE-918
  layer: domain
  name: Document Generation & Conversion
  providers:
  - Browserless
  url: /capabilities/it-application-management/
  via_parent: IT Application Management
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
  id: BC-430
  key: customer-service-management
  layer: common
  name: Customer Service Management
  providers:
  - Plain
  url: /capabilities/customer-service-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-110.10.10
  key: AE-110.10.10
  layer: common
  name: Hosted LLM Inference
  providers:
  - Google Vertex AI
  url: /capabilities/model-inference/
  via_parent: Model Inference
- attribution: Turbo EA
  id: BC-600.40.20
  key: BC-600.40.20
  layer: common
  name: IT Job Scheduling and Batch Operations
  providers:
  - Inngest
  url: /capabilities/it-operations-management/
  via_parent: IT Operations Management
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: common
  name: Payment Processing Management
  providers:
  - Stripe
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - PostHog
  url: /capabilities/product-usage-analytics/
  via_parent: null
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
- attribution: Turbo EA
  id: BC-600.50.20
  key: BC-600.50.20
  layer: common
  name: Storage Management
  providers:
  - Amazon S3
  - Azure Blob Storage
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: API Evangelist extension
  id: AE-150.10.10
  key: AE-150.10.10
  layer: common
  name: Transactional Email
  providers:
  - Amazon SES
  - MailChannels
  - Resend
  url: /capabilities/email/
  via_parent: Email
category:
  id: e-signature-contracts
  name: E-signature & Contract Management
  url: /applications/e-signature-contracts/
counts:
  declared: 0
  observed: 15
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/documenso/documenso/main/packages/lib/package.json
- route: source code
  url: https://raw.githubusercontent.com/documenso/documenso/main/.env.example
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
  source: https://raw.githubusercontent.com/documenso/documenso/main/packages/lib/package.json
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
    agent_readiness: 38.0
    band: exemplar
    in_catalog: true
    kin_score: 83.8
    mcp: &id003
      status: none
    slug: amazon-ses
    status: profiled
    tags: &id004
    - Amazon Web Services
    - Email
    - Email Deliverability
    - Email Service
    url: /providers/amazon-ses/
  layer: common
  name: Amazon SES
  provider: amazon-ses
  says: ships the Amazon SES SDK or integration code
  source: https://raw.githubusercontent.com/documenso/documenso/main/packages/lib/package.json
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
  source: https://raw.githubusercontent.com/documenso/documenso/main/packages/lib/package.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-918
    key: AE-918
    name: Document Generation & Conversion
    url: /capabilities/it-application-management/
    via_parent: IT Application Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 47.5
    band: strong
    in_catalog: true
    kin_score: 56.4
    mcp: &id007
      source: https://github.com/browserless/browserless-mcp
      status: verified
    slug: browserless
    status: profiled
    tags: &id008
    - AI Agents
    - Browser Automation
    - Browser Infrastructure
    - Web Scraping
    url: /providers/browserless/
  layer: domain
  name: Browserless
  provider: browserless
  says: ships the Browserless SDK or integration code
  source: https://raw.githubusercontent.com/documenso/documenso/main/.env.example
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
    mcp: &id009
      source: https://github.com/cloudflare/mcp
      status: verified
    slug: cloudflare-turnstile
    status: profiled
    tags: &id010
    - Bot Defense
    - CAPTCHA
    - Cloudflare
    - Turnstile
    url: /providers/cloudflare-turnstile/
  layer: common
  name: Cloudflare Turnstile
  provider: cloudflare-turnstile
  says: ships the Cloudflare Turnstile SDK or integration code
  source: https://raw.githubusercontent.com/documenso/documenso/main/.env.example
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
    agent_readiness: 34.8
    band: exemplar
    in_catalog: true
    kin_score: 70.9
    mcp: &id011
      status: none
    slug: google-cloud-kms
    status: profiled
    tags: &id012
    - Cryptography
    - Encryption
    - Google Cloud
    - Key Management
    url: /providers/google-cloud-kms/
  layer: domain
  name: Google Cloud HSM (KMS)
  provider: google-cloud-kms
  says: ships the Google Cloud HSM (KMS) SDK or integration code
  source: https://raw.githubusercontent.com/documenso/documenso/main/.env.example
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
    mcp: &id013
      status: none
    slug: google-identity-platform
    status: profiled
    tags: &id014
    - Authentication
    - Google Cloud
    - Identity
    - Multi-Tenancy
    url: /providers/google-identity-platform/
  layer: common
  name: Google sign-in
  provider: google-identity-platform
  says: ships the Google sign-in SDK or integration code
  source: https://raw.githubusercontent.com/documenso/documenso/main/.env.example
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 42.2
    band: strong
    in_catalog: true
    kin_score: 63.2
    mcp: &id015
      source: https://github.com/googleapis/gcloud-mcp
      status: verified
    slug: google-vertex-ai
    status: profiled
    tags: &id016
    - Artificial Intelligence
    - Generative AI
    - Google Cloud
    - Machine Learning
    url: /providers/google-vertex-ai/
  layer: common
  name: Google Vertex AI
  provider: google-vertex-ai
  says: ships the Google Vertex AI SDK or integration code
  source: https://raw.githubusercontent.com/documenso/documenso/main/packages/lib/package.json
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-600.40.20
    key: BC-600.40.20
    name: IT Job Scheduling and Batch Operations
    url: /capabilities/it-operations-management/
    via_parent: IT Operations Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 37.6
    band: exemplar
    in_catalog: true
    kin_score: 68.1
    mcp: &id017
      source: https://www.inngest.com/docs/ai-dev-tools/mcp
      status: verified
    slug: inngest
    status: profiled
    tags: &id018
    - AI Agents
    - AgentKit
    - Background Jobs
    - Connect
    url: /providers/inngest/
  layer: common
  name: Inngest
  provider: inngest
  says: ships the Inngest SDK or integration code
  source: https://raw.githubusercontent.com/documenso/documenso/main/packages/lib/package.json
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
    agent_readiness: 5.6
    band: developing
    in_catalog: true
    kin_score: 44.7
    mcp: &id019
      status: none
    slug: mailchannels
    status: profiled
    tags: &id020
    - Company
    - Email
    - Platform
    - SMTP
    url: /providers/mailchannels/
  layer: common
  name: MailChannels
  provider: mailchannels
  says: ships the MailChannels SDK or integration code
  source: https://raw.githubusercontent.com/documenso/documenso/main/.env.example
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
    mcp: &id021
      status: none
    slug: microsoft-entra
    status: profiled
    tags: &id022
    - Authentication
    - Azure AD
    - Entra
    - Identity and Access Management
    url: /providers/microsoft-entra/
  layer: common
  name: Microsoft sign-in
  provider: microsoft-entra
  says: ships the Microsoft sign-in SDK or integration code
  source: https://raw.githubusercontent.com/documenso/documenso/main/.env.example
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-430
    key: customer-service-management
    name: Customer Service Management
    url: /capabilities/customer-service-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 50.3
    band: strong
    in_catalog: true
    kin_score: 61.8
    mcp: &id023
      source: https://github.com/team-plain/cursor-plugin-mcp
      status: verified
    slug: plain
    status: profiled
    tags: &id024
    - Company
    - Customer Service
    - Help Desk
    - Support
    url: /providers/plain/
  layer: common
  name: Plain
  provider: plain
  says: ships the Plain SDK or integration code
  source: https://raw.githubusercontent.com/documenso/documenso/main/packages/lib/package.json
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
    mcp: &id025
      source: https://github.com/PostHog/mcp
      status: verified
    slug: posthog
    status: profiled
    tags: &id026
    - A/B Testing
    - Analytics
    - Feature Flags
    - Open Source
    url: /providers/posthog/
  layer: common
  name: PostHog
  provider: posthog
  says: ships the PostHog SDK or integration code
  source: https://raw.githubusercontent.com/documenso/documenso/main/packages/lib/package.json
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
    agent_readiness: 49.8
    band: strong
    in_catalog: true
    kin_score: 56.8
    mcp: &id027
      source: https://resend.com/docs/mcp-server
      status: verified
    slug: resend
    status: profiled
    tags: &id028
    - Developer Tools
    - Email
    - Marketing Email
    - Transactional Email
    url: /providers/resend/
  layer: common
  name: Resend
  provider: resend
  says: ships the Resend SDK or integration code
  source: https://raw.githubusercontent.com/documenso/documenso/main/.env.example
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
    mcp: &id029
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id030
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
  layer: common
  name: Stripe
  provider: stripe
  says: ships the Stripe SDK or integration code
  source: https://raw.githubusercontent.com/documenso/documenso/main/packages/lib/package.json
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/e-signature-contracts/documenso/
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
  agent_readiness: 38.0
  band: exemplar
  in_catalog: true
  kin_score: 83.8
  mcp: *id003
  name: Amazon SES
  slug: amazon-ses
  status: profiled
  tags: *id004
  url: /providers/amazon-ses/
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
- agent_band: agent-ready
  agent_readiness: 47.5
  band: strong
  in_catalog: true
  kin_score: 56.4
  mcp: *id007
  name: Browserless
  slug: browserless
  status: profiled
  tags: *id008
  url: /providers/browserless/
- agent_band: agent-aware
  agent_readiness: 24.2
  band: thin
  in_catalog: true
  kin_score: 28.8
  mcp: *id009
  name: Cloudflare Turnstile
  slug: cloudflare-turnstile
  status: profiled
  tags: *id010
  url: /providers/cloudflare-turnstile/
- agent_band: agent-ready
  agent_readiness: 34.8
  band: exemplar
  in_catalog: true
  kin_score: 70.9
  mcp: *id011
  name: Google Cloud HSM (KMS)
  slug: google-cloud-kms
  status: profiled
  tags: *id012
  url: /providers/google-cloud-kms/
- agent_band: agent-ready
  agent_readiness: 33.7
  band: strong
  in_catalog: true
  kin_score: 58.8
  mcp: *id013
  name: Google sign-in
  slug: google-identity-platform
  status: profiled
  tags: *id014
  url: /providers/google-identity-platform/
- agent_band: agent-ready
  agent_readiness: 42.2
  band: strong
  in_catalog: true
  kin_score: 63.2
  mcp: *id015
  name: Google Vertex AI
  slug: google-vertex-ai
  status: profiled
  tags: *id016
  url: /providers/google-vertex-ai/
- agent_band: agent-ready
  agent_readiness: 37.6
  band: exemplar
  in_catalog: true
  kin_score: 68.1
  mcp: *id017
  name: Inngest
  slug: inngest
  status: profiled
  tags: *id018
  url: /providers/inngest/
- agent_band: agent-aware
  agent_readiness: 5.6
  band: developing
  in_catalog: true
  kin_score: 44.7
  mcp: *id019
  name: MailChannels
  slug: mailchannels
  status: profiled
  tags: *id020
  url: /providers/mailchannels/
- agent_band: agent-ready
  agent_readiness: 28.7
  band: exemplar
  in_catalog: true
  kin_score: 70.3
  mcp: *id021
  name: Microsoft sign-in
  slug: microsoft-entra
  status: profiled
  tags: *id022
  url: /providers/microsoft-entra/
- agent_band: agent-ready
  agent_readiness: 50.3
  band: strong
  in_catalog: true
  kin_score: 61.8
  mcp: *id023
  name: Plain
  slug: plain
  status: profiled
  tags: *id024
  url: /providers/plain/
- agent_band: agent-ready
  agent_readiness: 56.2
  band: strong
  in_catalog: true
  kin_score: 57.9
  mcp: *id025
  name: PostHog
  slug: posthog
  status: profiled
  tags: *id026
  url: /providers/posthog/
- agent_band: agent-ready
  agent_readiness: 49.8
  band: strong
  in_catalog: true
  kin_score: 56.8
  mcp: *id027
  name: Resend
  slug: resend
  status: profiled
  tags: *id028
  url: /providers/resend/
- agent_band: agent-native
  agent_readiness: 57.6
  band: exemplar
  in_catalog: true
  kin_score: 82.0
  mcp: *id029
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id030
  url: /providers/stripe/
siblings:
- name: DocuSeal
  rows: 4
  url: /applications/e-signature-contracts/docuseal/
- name: DocuSign
  rows: 16
  url: /applications/e-signature-contracts/docusign/
- name: Dropbox Sign
  rows: 18
  url: /applications/e-signature-contracts/dropbox-sign/
- name: OpenSign
  rows: 7
  url: /applications/e-signature-contracts/opensign/
- name: Zoho Sign
  rows: 24
  url: /applications/e-signature-contracts/zoho-sign/
sitemap: true
title: 'Documenso: E-signature & Contract Management reference app'
---
