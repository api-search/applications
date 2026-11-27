---
app: Ghost
app_slug: ghost
app_url: https://github.com/TryGhost/Ghost
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-420.10
  key: customer-data-management
  layer: domain
  name: Customer Data Management
  providers:
  - Twilio Segment
  url: /capabilities/customer-data-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-420
  key: customer-relationship-management
  layer: domain
  name: Customer Relationship Management
  providers:
  - HubSpot
  url: /capabilities/customer-relationship-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.10.20
  key: AE-150.10.20
  layer: domain
  name: Email Marketing Sends
  providers:
  - Mailgun
  url: /capabilities/email/
  via_parent: Email
- attribution: API Evangelist extension
  id: AE-921
  key: AE-921
  layer: domain
  name: Online Forms & Survey Collection
  providers:
  - Typeform
  url: /capabilities/customer-feedback-management/
  via_parent: Customer Feedback Management
- attribution: Turbo EA
  id: BC-4250
  key: subscription-billing-revenue-management
  layer: domain
  name: Subscription Billing & Revenue Management
  providers:
  - Stripe
  - Patreon
  url: /capabilities/subscription-billing-revenue-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-610.50
  key: analytics-bi-management
  layer: common
  name: Analytics & BI Management
  providers:
  - Tinybird
  - Plausible Analytics
  url: /capabilities/analytics-bi-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-850.10
  key: internal-communications-management
  layer: common
  name: Internal Communications Management
  providers:
  - Discord
  - Slack
  url: /capabilities/internal-communications-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-3710
  key: media-asset-management
  layer: common
  name: Media Asset Management
  providers:
  - Amazon S3
  - Cloudinary
  - GIPHY
  - Unsplash
  url: /capabilities/media-asset-management/
  via_parent: null
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
  - PayPal
  url: /capabilities/payment-processing-management/
  via_parent: null
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
  id: email-marketing-newsletter
  name: Email Marketing & Newsletters
  url: /applications/email-marketing-newsletter/
counts:
  declared: 12
  observed: 5
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/TryGhost/Ghost/main/ghost/package.json
- route: integrations page
  url: https://ghost.org/integrations/
- route: source code
  url: https://github.com/TryGhost/Ghost/blob/main/apps/admin-x-framework/src/api/tinybird.ts
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
  source: https://raw.githubusercontent.com/TryGhost/Ghost/main/ghost/package.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.20
    key: AE-150.10.20
    name: Email Marketing Sends
    url: /capabilities/email/
    via_parent: Email
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 19.2
    band: thin
    in_catalog: true
    kin_score: 31.6
    mcp: &id011
      source: https://github.com/mailgun/mailgun-mcp-server
      status: verified
    slug: mailgun
    status: profiled
    tags: &id012
    - Email
    - Email Verification
    - SMTP
    - Transactional Email
    url: /providers/mailgun/
  layer: domain
  name: Mailgun
  provider: mailgun
  says: ships the Mailgun SDK or integration code
  source: https://raw.githubusercontent.com/TryGhost/Ghost/main/ghost/package.json
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
    kin_score: 80.7
    mcp: &id019
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id020
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: common
  name: Sentry
  provider: sentry-system
  says: ships the Sentry SDK or integration code
  source: https://raw.githubusercontent.com/TryGhost/Ghost/main/ghost/package.json
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4250
    key: subscription-billing-revenue-management
    name: Subscription Billing & Revenue Management
    url: /capabilities/subscription-billing-revenue-management/
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
  layer: domain
  name: Stripe
  provider: stripe
  says: ships the Stripe SDK or integration code
  source: https://raw.githubusercontent.com/TryGhost/Ghost/main/ghost/package.json
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
    agent_band: agent-ready
    agent_readiness: 35.3
    band: developing
    in_catalog: true
    kin_score: 46.4
    mcp: &id025
      source: https://www.tinybird.co/docs/forward/analytics-agents/mcp
      status: verified
    slug: tinybird
    status: profiled
    tags: &id026
    - Analytics
    - Data
    - Real-Time
    - SQL
    url: /providers/tinybird/
  layer: common
  name: Tinybird
  provider: tinybird
  says: ships the Tinybird SDK or integration code
  source: https://github.com/TryGhost/Ghost/blob/main/apps/admin-x-framework/src/api/tinybird.ts
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
    agent_readiness: 53.5
    band: exemplar
    in_catalog: true
    kin_score: 82.0
    mcp: &id003
      source: https://cloudinary.com/documentation/cloudinary_llm_mcp
      status: verified
    slug: cloudinary
    status: profiled
    tags: &id004
    - Asset Management
    - Digital Asset Management
    - Image Processing
    - Image Transformation
    url: /providers/cloudinary/
  layer: common
  name: Cloudinary
  provider: cloudinary
  says: lists Cloudinary as an integration
  source: https://ghost.org/integrations/
  tier: declared
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
    agent_readiness: 33.1
    band: developing
    in_catalog: true
    kin_score: 48.0
    mcp: &id005
      status: none
    slug: discord
    status: profiled
    tags: &id006
    - Chat
    - Communications
    - Discord
    - Gaming
    url: /providers/discord/
  layer: common
  name: Discord
  provider: discord
  says: lists Discord as an integration
  source: https://ghost.org/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-3710
    key: media-asset-management
    name: Media Asset Management
    url: /capabilities/media-asset-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 26.8
    band: strong
    in_catalog: true
    kin_score: 56.0
    mcp: &id007
      status: none
    slug: giphy
    status: profiled
    tags: &id008
    - GIFs
    - Media
    - Photography
    - Stickers
    url: /providers/giphy/
  layer: common
  name: GIPHY
  provider: giphy
  says: lists GIPHY as an integration
  source: https://ghost.org/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-420
    key: customer-relationship-management
    name: Customer Relationship Management
    url: /capabilities/customer-relationship-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 52.0
    band: exemplar
    in_catalog: true
    kin_score: 91.9
    mcp: &id009
      source: https://developers.hubspot.com/mcp
      status: verified
    slug: hubspot
    status: profiled
    tags: &id010
    - Analytics
    - CRM
    - Commerce
    - Content
    url: /providers/hubspot/
  layer: domain
  name: HubSpot
  provider: hubspot
  says: lists HubSpot as an integration
  source: https://ghost.org/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4250
    key: subscription-billing-revenue-management
    name: Subscription Billing & Revenue Management
    url: /capabilities/subscription-billing-revenue-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 26.4
    band: thin
    in_catalog: true
    kin_score: 33.1
    mcp: &id013
      status: none
    slug: patreon
    status: profiled
    tags: &id014
    - Content
    - Creator Economy
    - Membership
    - Subscription
    url: /providers/patreon/
  layer: domain
  name: Patreon
  provider: patreon
  says: lists Patreon as an integration
  source: https://ghost.org/integrations/
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
  says: lists PayPal as an integration
  source: https://ghost.org/integrations/
  tier: declared
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
    agent_readiness: 22.6
    band: strong
    in_catalog: true
    kin_score: 65.3
    mcp: &id017
      status: none
    slug: plausible
    status: profiled
    tags: &id018
    - Analytics
    - Cookie-Free
    - Event Tracking
    - GDPR
    url: /providers/plausible/
  layer: common
  name: Plausible Analytics
  provider: plausible
  says: lists Plausible Analytics as an integration
  source: https://ghost.org/integrations/
  tier: declared
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
    agent_readiness: 38.3
    band: exemplar
    in_catalog: true
    kin_score: 74.4
    mcp: &id021
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id022
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: common
  name: Slack
  provider: slack
  says: lists Slack as an integration
  source: https://ghost.org/integrations/
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
    agent_band: agent-aware
    agent_readiness: 27.7
    band: developing
    in_catalog: true
    kin_score: 42.9
    mcp: &id027
      status: none
    slug: segment
    status: profiled
    tags: &id028
    - CDP
    - Company
    - Customer Data Platform
    - Identity Resolution
    url: /providers/segment/
  layer: domain
  name: Twilio Segment
  provider: segment
  says: lists Twilio Segment as an integration
  source: https://ghost.org/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-921
    key: AE-921
    name: Online Forms & Survey Collection
    url: /capabilities/customer-feedback-management/
    via_parent: Customer Feedback Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 42.6
    band: thin
    in_catalog: true
    kin_score: 36.0
    mcp: &id029
      source: https://www.typeform.com/developers/mcp
      status: verified
    slug: typeform
    status: profiled
    tags: &id030
    - Forms
    - Lead Capture
    - Software-as-a-Service
    - Surveys
    url: /providers/typeform/
  layer: domain
  name: Typeform
  provider: typeform
  says: lists Typeform as an integration
  source: https://ghost.org/integrations/
  tier: declared
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
    agent_readiness: 52.6
    band: developing
    in_catalog: true
    kin_score: 39.4
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
  layer: common
  name: Unsplash
  provider: unsplash
  says: lists Unsplash as an integration
  source: https://ghost.org/integrations/
  tier: declared
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
    mcp: &id033
      source: https://zapier.com/mcp
      status: verified
    slug: zapier
    status: profiled
    tags: &id034
    - Integration
    - Workflow Automation
    - Zapier
    - iPaaS
    url: /providers/zapier/
  layer: common
  name: Zapier
  provider: zapier
  says: lists Zapier as an integration
  source: https://ghost.org/integrations/
  tier: declared
kind: open-source-saas
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/email-marketing-newsletter/ghost/
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
  agent_readiness: 53.5
  band: exemplar
  in_catalog: true
  kin_score: 82.0
  mcp: *id003
  name: Cloudinary
  slug: cloudinary
  status: profiled
  tags: *id004
  url: /providers/cloudinary/
- agent_band: agent-ready
  agent_readiness: 33.1
  band: developing
  in_catalog: true
  kin_score: 48.0
  mcp: *id005
  name: Discord
  slug: discord
  status: profiled
  tags: *id006
  url: /providers/discord/
- agent_band: agent-aware
  agent_readiness: 26.8
  band: strong
  in_catalog: true
  kin_score: 56.0
  mcp: *id007
  name: GIPHY
  slug: giphy
  status: profiled
  tags: *id008
  url: /providers/giphy/
- agent_band: agent-ready
  agent_readiness: 52.0
  band: exemplar
  in_catalog: true
  kin_score: 91.9
  mcp: *id009
  name: HubSpot
  slug: hubspot
  status: profiled
  tags: *id010
  url: /providers/hubspot/
- agent_band: agent-aware
  agent_readiness: 19.2
  band: thin
  in_catalog: true
  kin_score: 31.6
  mcp: *id011
  name: Mailgun
  slug: mailgun
  status: profiled
  tags: *id012
  url: /providers/mailgun/
- agent_band: agent-aware
  agent_readiness: 26.4
  band: thin
  in_catalog: true
  kin_score: 33.1
  mcp: *id013
  name: Patreon
  slug: patreon
  status: profiled
  tags: *id014
  url: /providers/patreon/
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
- agent_band: agent-aware
  agent_readiness: 22.6
  band: strong
  in_catalog: true
  kin_score: 65.3
  mcp: *id017
  name: Plausible Analytics
  slug: plausible
  status: profiled
  tags: *id018
  url: /providers/plausible/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.7
  mcp: *id019
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id020
  url: /providers/sentry-system/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id021
  name: Slack
  slug: slack
  status: profiled
  tags: *id022
  url: /providers/slack/
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
- agent_band: agent-ready
  agent_readiness: 35.3
  band: developing
  in_catalog: true
  kin_score: 46.4
  mcp: *id025
  name: Tinybird
  slug: tinybird
  status: profiled
  tags: *id026
  url: /providers/tinybird/
- agent_band: agent-aware
  agent_readiness: 27.7
  band: developing
  in_catalog: true
  kin_score: 42.9
  mcp: *id027
  name: Twilio Segment
  slug: segment
  status: profiled
  tags: *id028
  url: /providers/segment/
- agent_band: agent-ready
  agent_readiness: 42.6
  band: thin
  in_catalog: true
  kin_score: 36.0
  mcp: *id029
  name: Typeform
  slug: typeform
  status: profiled
  tags: *id030
  url: /providers/typeform/
- agent_band: agent-ready
  agent_readiness: 52.6
  band: developing
  in_catalog: true
  kin_score: 39.4
  mcp: *id031
  name: Unsplash
  slug: unsplash
  status: profiled
  tags: *id032
  url: /providers/unsplash/
- agent_band: agent-ready
  agent_readiness: 66.1
  band: exemplar
  in_catalog: true
  kin_score: 72.9
  mcp: *id033
  name: Zapier
  slug: zapier
  status: profiled
  tags: *id034
  url: /providers/zapier/
siblings:
- name: beehiiv
  rows: 22
  url: /applications/email-marketing-newsletter/beehiiv/
- name: Keila
  rows: 7
  url: /applications/email-marketing-newsletter/keila/
- name: Klaviyo
  rows: 15
  url: /applications/email-marketing-newsletter/klaviyo/
- name: listmonk
  rows: 13
  url: /applications/email-marketing-newsletter/listmonk/
- name: Mailchimp
  rows: 17
  url: /applications/email-marketing-newsletter/mailchimp/
- name: Mautic
  rows: 25
  url: /applications/email-marketing-newsletter/mautic/
- name: Substack
  rows: 4
  url: /applications/email-marketing-newsletter/substack/
sitemap: true
title: 'Ghost: Email Marketing & Newsletters reference app'
---
