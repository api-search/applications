---
app: Laudspeaker
app_slug: laudspeaker
app_url: https://github.com/laudspeaker/laudspeaker
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-420.10
  key: customer-data-management
  layer: domain
  name: Customer Data Management
  providers:
  - PostHog
  url: /capabilities/customer-data-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-610.50
  key: analytics-bi-management
  layer: common
  name: Analytics & BI Management
  providers:
  - Databricks
  url: /capabilities/analytics-bi-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.10.20
  key: AE-150.10.20
  layer: common
  name: Email Marketing Sends
  providers:
  - Mailgun
  - Resend
  - SendGrid
  url: /capabilities/email/
  via_parent: Email
- attribution: Turbo EA
  id: BC-850.10
  key: internal-communications-management
  layer: common
  name: Internal Communications Management
  providers:
  - Slack
  url: /capabilities/internal-communications-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-3710
  key: media-asset-management
  layer: common
  name: Media Asset Management
  providers:
  - AWS
  url: /capabilities/media-asset-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Papertrail
  - Sentry
  url: /capabilities/observability-management/
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
- attribution: API Evangelist extension
  id: AE-150.30
  key: AE-150.30
  layer: common
  name: Push Notifications
  providers:
  - Firebase Cloud Messaging
  url: /capabilities/push-notifications/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.20.10
  key: AE-150.20.10
  layer: common
  name: SMS
  providers:
  - Twilio
  url: /capabilities/sms-messaging-apps/
  via_parent: SMS & Messaging Apps
- attribution: Turbo EA
  id: BC-4270.80.30
  key: BC-4270.80.30
  layer: common
  name: Webhook Delivery Reliability Management
  providers:
  - Svix
  url: /capabilities/webhook-event-subscription-management/
  via_parent: Webhook & Event Subscription Management
category:
  id: marketing-automation
  name: Marketing Automation & Ads
  url: /applications/marketing-automation/
counts:
  declared: 0
  observed: 13
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/laudspeaker/laudspeaker/main/packages/server/package.json
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
    agent_readiness: 37.9
    band: exemplar
    in_catalog: true
    kin_score: 68.5
    mcp: &id001
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-web-services
    status: profiled
    tags: &id002
    - Amazon
    - Amazon Web Services
    - Cloud
    - Networks
    url: /providers/amazon-web-services/
  layer: common
  name: AWS
  provider: amazon-web-services
  says: ships the AWS SDK or integration code
  source: https://raw.githubusercontent.com/laudspeaker/laudspeaker/main/packages/server/package.json
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
    agent_band: agent-native
    agent_readiness: 65.5
    band: strong
    in_catalog: true
    kin_score: 58.7
    mcp: &id003
      source: https://docs.databricks.com/aws/en/generative-ai/mcp/
      status: verified
    slug: databricks
    status: profiled
    tags: &id004
    - Analytics
    - Artificial Intelligence
    - Cleanroom
    - Databricks
    url: /providers/databricks/
  layer: common
  name: Databricks
  provider: databricks
  says: ships the Databricks SDK or integration code
  source: https://raw.githubusercontent.com/laudspeaker/laudspeaker/main/packages/server/package.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.30
    key: AE-150.30
    name: Push Notifications
    url: /capabilities/push-notifications/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 39.9
    band: strong
    in_catalog: true
    kin_score: 62.0
    mcp: &id005
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: google-firebase
    status: profiled
    tags: &id006
    - Analytics
    - Authentication
    - Backend-as-a-Service
    - Cloud Messaging
    url: /providers/google-firebase/
  layer: common
  name: Firebase Cloud Messaging
  provider: firebase
  says: ships the Firebase Cloud Messaging SDK or integration code
  source: https://raw.githubusercontent.com/laudspeaker/laudspeaker/main/packages/server/package.json
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
    mcp: &id007
      source: https://github.com/mailgun/mailgun-mcp-server
      status: verified
    slug: mailgun
    status: profiled
    tags: &id008
    - Email
    - Email Verification
    - SMTP
    - Transactional Email
    url: /providers/mailgun/
  layer: common
  name: Mailgun
  provider: mailgun
  says: ships the Mailgun SDK or integration code
  source: https://raw.githubusercontent.com/laudspeaker/laudspeaker/main/packages/server/package.json
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
    agent_band: agent-aware
    agent_readiness: 26.4
    band: exemplar
    in_catalog: true
    kin_score: 69.2
    mcp: &id009
      status: none
    slug: solarwinds
    status: profiled
    tags: &id010
    - Application Monitoring
    - Database Monitoring
    - IP Address Management
    - Infrastructure
    url: /providers/solarwinds/
  layer: common
  name: Papertrail
  provider: solarwinds
  says: ships the Papertrail SDK or integration code
  source: https://raw.githubusercontent.com/laudspeaker/laudspeaker/main/packages/server/package.json
  tier: observed
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
  layer: domain
  name: PostHog
  provider: posthog
  says: ships the PostHog SDK or integration code
  source: https://raw.githubusercontent.com/laudspeaker/laudspeaker/main/packages/server/package.json
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
    agent_band: agent-ready
    agent_readiness: 49.8
    band: strong
    in_catalog: true
    kin_score: 56.8
    mcp: &id013
      source: https://resend.com/docs/mcp-server
      status: verified
    slug: resend
    status: profiled
    tags: &id014
    - Developer Tools
    - Email
    - Marketing Email
    - Transactional Email
    url: /providers/resend/
  layer: common
  name: Resend
  provider: resend
  says: ships the Resend SDK or integration code
  source: https://raw.githubusercontent.com/laudspeaker/laudspeaker/main/packages/server/package.json
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
    agent_band: agent-ready
    agent_readiness: 40.7
    band: exemplar
    in_catalog: true
    kin_score: 84.0
    mcp: &id015
      status: none
    slug: sendgrid
    status: profiled
    tags: &id016
    - Email
    - Email API
    - Marketing Email
    - SMTP
    url: /providers/sendgrid/
  layer: common
  name: SendGrid
  provider: sendgrid
  says: ships the SendGrid SDK or integration code
  source: https://raw.githubusercontent.com/laudspeaker/laudspeaker/main/packages/server/package.json
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
    mcp: &id017
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id018
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: common
  name: Sentry
  provider: sentry-system
  says: ships the Sentry SDK or integration code
  source: https://raw.githubusercontent.com/laudspeaker/laudspeaker/main/packages/server/package.json
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
    agent_readiness: 38.3
    band: exemplar
    in_catalog: true
    kin_score: 74.4
    mcp: &id019
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id020
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: common
  name: Slack
  provider: slack
  says: ships the Slack SDK or integration code
  source: https://raw.githubusercontent.com/laudspeaker/laudspeaker/main/packages/server/package.json
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
    mcp: &id021
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id022
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
  layer: common
  name: Stripe
  provider: stripe
  says: ships the Stripe SDK or integration code
  source: https://raw.githubusercontent.com/laudspeaker/laudspeaker/main/packages/server/package.json
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4270.80.30
    key: BC-4270.80.30
    name: Webhook Delivery Reliability Management
    url: /capabilities/webhook-event-subscription-management/
    via_parent: Webhook & Event Subscription Management
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 52.1
    band: exemplar
    in_catalog: true
    kin_score: 74.7
    mcp: &id023
      status: none
    slug: svix
    status: profiled
    tags: &id024
    - Webhook
    - Webhook Delivery
    - Webhook Sending
    - Webhooks As A Service
    url: /providers/svix/
  layer: common
  name: Svix
  provider: svix
  says: ships the Svix SDK or integration code
  source: https://raw.githubusercontent.com/laudspeaker/laudspeaker/main/packages/server/package.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.10
    key: AE-150.20.10
    name: SMS
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
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
  layer: common
  name: Twilio
  provider: twilio
  says: ships the Twilio SDK or integration code
  source: https://raw.githubusercontent.com/laudspeaker/laudspeaker/main/packages/server/package.json
  tier: observed
kind: open-source-saas
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/marketing-automation/laudspeaker/
providers:
- agent_band: agent-ready
  agent_readiness: 37.9
  band: exemplar
  in_catalog: true
  kin_score: 68.5
  mcp: *id001
  name: AWS
  slug: amazon-web-services
  status: profiled
  tags: *id002
  url: /providers/amazon-web-services/
- agent_band: agent-native
  agent_readiness: 65.5
  band: strong
  in_catalog: true
  kin_score: 58.7
  mcp: *id003
  name: Databricks
  slug: databricks
  status: profiled
  tags: *id004
  url: /providers/databricks/
- agent_band: agent-ready
  agent_readiness: 39.9
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id005
  name: Firebase Cloud Messaging
  slug: google-firebase
  status: profiled
  tags: *id006
  url: /providers/google-firebase/
- agent_band: agent-aware
  agent_readiness: 19.2
  band: thin
  in_catalog: true
  kin_score: 31.6
  mcp: *id007
  name: Mailgun
  slug: mailgun
  status: profiled
  tags: *id008
  url: /providers/mailgun/
- agent_band: agent-aware
  agent_readiness: 26.4
  band: exemplar
  in_catalog: true
  kin_score: 69.2
  mcp: *id009
  name: Papertrail
  slug: solarwinds
  status: profiled
  tags: *id010
  url: /providers/solarwinds/
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
  agent_readiness: 49.8
  band: strong
  in_catalog: true
  kin_score: 56.8
  mcp: *id013
  name: Resend
  slug: resend
  status: profiled
  tags: *id014
  url: /providers/resend/
- agent_band: agent-ready
  agent_readiness: 40.7
  band: exemplar
  in_catalog: true
  kin_score: 84.0
  mcp: *id015
  name: SendGrid
  slug: sendgrid
  status: profiled
  tags: *id016
  url: /providers/sendgrid/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.7
  mcp: *id017
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id018
  url: /providers/sentry-system/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id019
  name: Slack
  slug: slack
  status: profiled
  tags: *id020
  url: /providers/slack/
- agent_band: agent-native
  agent_readiness: 57.6
  band: exemplar
  in_catalog: true
  kin_score: 82.0
  mcp: *id021
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id022
  url: /providers/stripe/
- agent_band: agent-native
  agent_readiness: 52.1
  band: exemplar
  in_catalog: true
  kin_score: 74.7
  mcp: *id023
  name: Svix
  slug: svix
  status: profiled
  tags: *id024
  url: /providers/svix/
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
siblings:
- name: Braze
  rows: 31
  url: /applications/marketing-automation/braze/
- name: Customer.io
  rows: 21
  url: /applications/marketing-automation/customer-io/
- name: Dittofeed
  rows: 14
  url: /applications/marketing-automation/dittofeed/
- name: HubSpot Marketing Hub
  rows: 15
  url: /applications/marketing-automation/hubspot-marketing-hub/
- name: Mailchimp
  rows: 5
  url: /applications/marketing-automation/mailchimp/
- name: Mautic
  rows: 31
  url: /applications/marketing-automation/mautic/
sitemap: true
title: 'Laudspeaker: Marketing Automation & Ads reference app'
---
