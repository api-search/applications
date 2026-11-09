---
app: Formbricks
app_slug: formbricks
app_url: https://github.com/formbricks/formbricks
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-610.50
  key: analytics-bi-management
  layer: domain
  name: Analytics & BI Management
  providers:
  - cube
  url: /capabilities/analytics-bi-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-850.10
  key: internal-communications-management
  layer: domain
  name: Internal Communications Management
  providers:
  - slack
  url: /capabilities/internal-communications-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-830
  key: knowledge-management
  layer: domain
  name: Knowledge Management
  providers:
  - notion
  url: /capabilities/knowledge-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.30
  key: AE-170.30
  layer: domain
  name: Photo & Image Libraries
  providers:
  - unsplash
  url: /capabilities/photo-image-libraries/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-922
  key: AE-922
  layer: domain
  name: Spreadsheets & No-Code Databases
  providers:
  - airtable
  - google-sheets
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: API Evangelist extension
  id: AE-160.70
  key: AE-160.70
  layer: common
  name: Bot Protection & CAPTCHA
  providers:
  - cloudflare-turnstile
  - google-recaptcha
  url: /capabilities/bot-protection-captcha/
  via_parent: null
- attribution: Turbo EA
  id: BC-620.20
  key: identity-access-management
  layer: common
  name: Identity & Access Management
  providers:
  - authzed
  url: /capabilities/identity-access-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-110.40.10
  key: AE-110.40.10
  layer: common
  name: Machine Translation
  providers:
  - lingo-dev
  url: /capabilities/language-document-understanding/
  via_parent: Language & Document Understanding
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
  id: BC-1340.20
  key: payment-processing-management
  layer: common
  name: Payment Processing Management
  providers:
  - stripe
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - posthog
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-160.10.30
  key: AE-160.10.30
  layer: common
  name: Social & Federated Login
  providers:
  - github
  - Google sign-in
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
- attribution: Turbo EA
  id: BC-4230.50
  key: tenant-identity-federation
  layer: common
  name: Tenant Identity Federation
  providers:
  - Microsoft Entra ID (Azure AD)
  url: /capabilities/tenant-identity-federation/
  via_parent: null
category:
  id: forms-surveys
  name: Forms & Surveys
  url: /applications/forms-surveys/
counts:
  declared: 0
  observed: 16
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/formbricks/formbricks/main/apps/web/package.json
- route: source code
  url: https://github.com/formbricks/formbricks/tree/main/apps/web/modules/integrations
- route: source code
  url: https://raw.githubusercontent.com/formbricks/formbricks/main/.env.example
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
    agent_readiness: 50.3
    band: exemplar
    in_catalog: true
    kin_score: 69.2
    mcp: &id001
      source: https://github.com/Airtable/airtable-mcp-cli
      status: verified
    slug: airtable
    status: profiled
    tags: &id002
    - Application
    - Collaboration
    - Data
    - Database
    url: /providers/airtable/
  layer: domain
  name: airtable
  provider: airtable
  says: ships the airtable SDK or integration code
  source: https://raw.githubusercontent.com/formbricks/formbricks/main/.env.example
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
    agent_band: agent-aware
    agent_readiness: 19.6
    band: developing
    in_catalog: true
    kin_score: 46.6
    mcp: &id003
      source: https://github.com/authzed/mcp-server-reference
      status: verified
    slug: authzed
    status: profiled
    tags: &id004
    - Access Control
    - Authorization
    - Permissions
    - Zanzibar
    url: /providers/authzed/
  layer: common
  name: authzed
  provider: authzed
  says: ships the authzed SDK or integration code
  source: https://raw.githubusercontent.com/formbricks/formbricks/main/.env.example
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
    agent_readiness: 23.1
    band: thin
    in_catalog: true
    kin_score: 28.9
    mcp: &id005
      source: https://github.com/cloudflare/mcp
      status: verified
    slug: cloudflare-turnstile
    status: profiled
    tags: &id006
    - Bot Defense
    - CAPTCHA
    - Cloudflare
    - Turnstile
    url: /providers/cloudflare-turnstile/
  layer: common
  name: cloudflare-turnstile
  provider: cloudflare-turnstile
  says: ships the cloudflare-turnstile SDK or integration code
  source: https://raw.githubusercontent.com/formbricks/formbricks/main/apps/web/package.json
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-610.50
    key: analytics-bi-management
    name: Analytics & BI Management
    url: /capabilities/analytics-bi-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 15.5
    band: emerging
    in_catalog: true
    kin_score: 21.0
    mcp: &id007
      source: https://cube.dev/docs/product/apis-integrations/mcp-server
      status: verified
    slug: cube
    status: profiled
    tags: &id008
    - Business Intelligence
    - Embedded Analytics
    - GraphQL
    - Semantic Layer
    url: /providers/cube/
  layer: domain
  name: cube
  provider: cube
  says: ships the cube SDK or integration code
  source: https://raw.githubusercontent.com/formbricks/formbricks/main/.env.example
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
    agent_readiness: 63.4
    band: exemplar
    in_catalog: true
    kin_score: 85.4
    mcp: &id009
      source: https://github.com/github/github-mcp-server
      status: verified
    slug: github
    status: profiled
    tags: &id010
    - Code
    - Developer Tools
    - Pipelines
    - Platform
    url: /providers/github/
  layer: common
  name: github
  provider: github
  says: ships the github SDK or integration code
  source: https://raw.githubusercontent.com/formbricks/formbricks/main/.env.example
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
    agent_readiness: 19.6
    band: thin
    in_catalog: true
    kin_score: 36.8
    mcp: &id011
      status: none
    slug: google-identity-platform
    status: profiled
    tags: &id012
    - Authentication
    - Google Cloud
    - Identity
    - Multi-Tenancy
    url: /providers/google-identity-platform/
  layer: common
  name: Google sign-in
  provider: google-identity-platform
  says: ships the Google sign-in SDK or integration code
  source: https://raw.githubusercontent.com/formbricks/formbricks/main/.env.example
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
    agent_readiness: 24.6
    band: developing
    in_catalog: true
    kin_score: 48.1
    mcp: &id013
      status: none
    slug: google-recaptcha
    status: profiled
    tags: &id014
    - Abuse Prevention
    - Bot Detection
    - CAPTCHA
    - Fraud Prevention
    url: /providers/google-recaptcha/
  layer: common
  name: google-recaptcha
  provider: google-recaptcha
  says: ships the google-recaptcha SDK or integration code
  source: https://raw.githubusercontent.com/formbricks/formbricks/main/.env.example
  tier: observed
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
    agent_readiness: 33.8
    band: strong
    in_catalog: true
    kin_score: 64.5
    mcp: &id015
      status: none
    slug: google-sheets
    status: profiled
    tags: &id016
    - Google Workspace
    - Productivity
    - Spreadsheets
    url: /providers/google-sheets/
  layer: domain
  name: google-sheets
  provider: google-sheets
  says: ships the google-sheets SDK or integration code
  source: https://raw.githubusercontent.com/formbricks/formbricks/main/.env.example
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.40.10
    key: AE-110.40.10
    name: Machine Translation
    url: /capabilities/language-document-understanding/
    via_parent: Language & Document Understanding
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 19.6
    band: thin
    in_catalog: true
    kin_score: 38.4
    mcp: &id017
      source: https://lingo.dev/en/docs/mcp
      status: verified
    slug: lingo-dev
    status: profiled
    tags: &id018
    - Artificial Intelligence
    - Localization
    - Translation
    - i18n
    url: /providers/lingo-dev/
  layer: common
  name: lingo-dev
  provider: lingo-dev
  says: ships the lingo-dev SDK or integration code
  source: https://raw.githubusercontent.com/formbricks/formbricks/main/.env.example
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4230.50
    key: tenant-identity-federation
    name: Tenant Identity Federation
    url: /capabilities/tenant-identity-federation/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.5
    band: exemplar
    in_catalog: true
    kin_score: 73.9
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
  name: Microsoft Entra ID (Azure AD)
  provider: microsoft-entra
  says: ships the Microsoft Entra ID (Azure AD) SDK or integration code
  source: https://raw.githubusercontent.com/formbricks/formbricks/main/.env.example
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-830
    key: knowledge-management
    name: Knowledge Management
    url: /capabilities/knowledge-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 54.9
    band: exemplar
    in_catalog: true
    kin_score: 67.2
    mcp: &id021
      source: https://developers.notion.com/docs/mcp
      status: verified
    slug: notion
    status: profiled
    tags: &id022
    - Collaboration
    - Database
    - Ideas
    - Notes
    url: /providers/notion/
  layer: domain
  name: notion
  provider: notion
  says: ships the notion SDK or integration code
  source: https://raw.githubusercontent.com/formbricks/formbricks/main/.env.example
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
    agent_readiness: 57.3
    band: strong
    in_catalog: true
    kin_score: 57.7
    mcp: &id023
      source: https://github.com/PostHog/mcp
      status: verified
    slug: posthog
    status: profiled
    tags: &id024
    - A/B Testing
    - Analytics
    - Feature Flags
    - Open Source
    url: /providers/posthog/
  layer: common
  name: posthog
  provider: posthog
  says: ships the posthog SDK or integration code
  source: https://raw.githubusercontent.com/formbricks/formbricks/main/apps/web/package.json
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
    mcp: &id025
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id026
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: common
  name: Sentry
  provider: sentry-system
  says: ships the Sentry SDK or integration code
  source: https://raw.githubusercontent.com/formbricks/formbricks/main/apps/web/package.json
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-850.10
    key: internal-communications-management
    name: Internal Communications Management
    url: /capabilities/internal-communications-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.7
    band: exemplar
    in_catalog: true
    kin_score: 74.7
    mcp: &id027
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id028
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: domain
  name: slack
  provider: slack
  says: ships the slack SDK or integration code
  source: https://raw.githubusercontent.com/formbricks/formbricks/main/.env.example
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
    agent_readiness: 58.5
    band: exemplar
    in_catalog: true
    kin_score: 81.5
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
  name: stripe
  provider: stripe
  says: ships the stripe SDK or integration code
  source: https://raw.githubusercontent.com/formbricks/formbricks/main/apps/web/package.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.30
    key: AE-170.30
    name: Photo & Image Libraries
    url: /capabilities/photo-image-libraries/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 44.1
    band: developing
    in_catalog: true
    kin_score: 40.2
    mcp: &id031
      status: none
    slug: unsplash
    status: profiled
    tags: &id032
    - Image
    - Photography
    - Photos
    - Stock Photos
    url: /providers/unsplash/
  layer: domain
  name: unsplash
  provider: unsplash
  says: ships the unsplash SDK or integration code
  source: https://raw.githubusercontent.com/formbricks/formbricks/main/.env.example
  tier: observed
kind: open-source-saas
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/forms-surveys/formbricks/
providers:
- agent_band: agent-ready
  agent_readiness: 50.3
  band: exemplar
  in_catalog: true
  kin_score: 69.2
  mcp: *id001
  name: airtable
  slug: airtable
  status: profiled
  tags: *id002
  url: /providers/airtable/
- agent_band: agent-aware
  agent_readiness: 19.6
  band: developing
  in_catalog: true
  kin_score: 46.6
  mcp: *id003
  name: authzed
  slug: authzed
  status: profiled
  tags: *id004
  url: /providers/authzed/
- agent_band: agent-aware
  agent_readiness: 23.1
  band: thin
  in_catalog: true
  kin_score: 28.9
  mcp: *id005
  name: cloudflare-turnstile
  slug: cloudflare-turnstile
  status: profiled
  tags: *id006
  url: /providers/cloudflare-turnstile/
- agent_band: agent-aware
  agent_readiness: 15.5
  band: emerging
  in_catalog: true
  kin_score: 21.0
  mcp: *id007
  name: cube
  slug: cube
  status: profiled
  tags: *id008
  url: /providers/cube/
- agent_band: agent-ready
  agent_readiness: 63.4
  band: exemplar
  in_catalog: true
  kin_score: 85.4
  mcp: *id009
  name: github
  slug: github
  status: profiled
  tags: *id010
  url: /providers/github/
- agent_band: agent-aware
  agent_readiness: 19.6
  band: thin
  in_catalog: true
  kin_score: 36.8
  mcp: *id011
  name: Google sign-in
  slug: google-identity-platform
  status: profiled
  tags: *id012
  url: /providers/google-identity-platform/
- agent_band: agent-aware
  agent_readiness: 24.6
  band: developing
  in_catalog: true
  kin_score: 48.1
  mcp: *id013
  name: google-recaptcha
  slug: google-recaptcha
  status: profiled
  tags: *id014
  url: /providers/google-recaptcha/
- agent_band: agent-ready
  agent_readiness: 33.8
  band: strong
  in_catalog: true
  kin_score: 64.5
  mcp: *id015
  name: google-sheets
  slug: google-sheets
  status: profiled
  tags: *id016
  url: /providers/google-sheets/
- agent_band: agent-aware
  agent_readiness: 19.6
  band: thin
  in_catalog: true
  kin_score: 38.4
  mcp: *id017
  name: lingo-dev
  slug: lingo-dev
  status: profiled
  tags: *id018
  url: /providers/lingo-dev/
- agent_band: agent-ready
  agent_readiness: 33.5
  band: exemplar
  in_catalog: true
  kin_score: 73.9
  mcp: *id019
  name: Microsoft Entra ID (Azure AD)
  slug: microsoft-entra
  status: profiled
  tags: *id020
  url: /providers/microsoft-entra/
- agent_band: agent-ready
  agent_readiness: 54.9
  band: exemplar
  in_catalog: true
  kin_score: 67.2
  mcp: *id021
  name: notion
  slug: notion
  status: profiled
  tags: *id022
  url: /providers/notion/
- agent_band: agent-ready
  agent_readiness: 57.3
  band: strong
  in_catalog: true
  kin_score: 57.7
  mcp: *id023
  name: posthog
  slug: posthog
  status: profiled
  tags: *id024
  url: /providers/posthog/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.6
  mcp: *id025
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id026
  url: /providers/sentry-system/
- agent_band: agent-ready
  agent_readiness: 38.7
  band: exemplar
  in_catalog: true
  kin_score: 74.7
  mcp: *id027
  name: slack
  slug: slack
  status: profiled
  tags: *id028
  url: /providers/slack/
- agent_band: agent-native
  agent_readiness: 58.5
  band: exemplar
  in_catalog: true
  kin_score: 81.5
  mcp: *id029
  name: stripe
  slug: stripe
  status: profiled
  tags: *id030
  url: /providers/stripe/
- agent_band: agent-ready
  agent_readiness: 44.1
  band: developing
  in_catalog: true
  kin_score: 40.2
  mcp: *id031
  name: unsplash
  slug: unsplash
  status: profiled
  tags: *id032
  url: /providers/unsplash/
siblings:
- name: HeyForm
  rows: 6
  url: /applications/forms-surveys/heyform/
- name: Jotform
  rows: 32
  url: /applications/forms-surveys/jotform/
- name: LimeSurvey
  rows: 3
  url: /applications/forms-surveys/limesurvey/
- name: SurveyMonkey
  rows: 9
  url: /applications/forms-surveys/surveymonkey/
- name: Typebot
  rows: 23
  url: /applications/forms-surveys/typebot/
- name: Typeform
  rows: 18
  url: /applications/forms-surveys/typeform/
sitemap: true
title: 'Formbricks: Forms & Surveys reference app'
---
