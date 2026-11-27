---
app: Dittofeed
app_slug: dittofeed
app_url: https://github.com/dittofeed/dittofeed
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-420.10
  key: customer-data-management
  layer: domain
  name: Customer Data Management
  providers:
  - Polytomic
  - Segment
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
  id: AE-150.80
  key: AE-150.80
  layer: domain
  name: Mailbox & Calendar Sync
  providers:
  - Gmail
  url: /capabilities/mailbox-calendar-sync/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.10.20
  key: AE-150.10.20
  layer: common
  name: Email Marketing Sends
  providers:
  - Amazon SES
  - Mailchimp (Mandrill)
  - Postmark
  - Resend
  - SendGrid
  url: /capabilities/email/
  via_parent: Email
- attribution: Turbo EA
  id: BC-3710
  key: media-asset-management
  layer: common
  name: Media Asset Management
  providers:
  - Amazon S3
  url: /capabilities/media-asset-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - HyperDX
  url: /capabilities/observability-management/
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
  - SignalWire
  - Twilio
  url: /capabilities/sms-messaging-apps/
  via_parent: SMS & Messaging Apps
category:
  id: marketing-automation
  name: Marketing Automation & Ads
  url: /applications/marketing-automation/
counts:
  declared: 3
  observed: 11
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/dittofeed/dittofeed/main/packages/backend-lib/package.json
- route: documentation
  url: https://github.com/dittofeed/dittofeed/tree/main/packages/docs/integrations
- route: source code
  url: https://github.com/dittofeed/dittofeed/tree/main/packages/backend-lib/src/destinations
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
  source: https://raw.githubusercontent.com/dittofeed/dittofeed/main/packages/backend-lib/package.json
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
  source: https://github.com/dittofeed/dittofeed/tree/main/packages/backend-lib/src/destinations
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
  source: https://github.com/dittofeed/dittofeed/tree/main/packages/backend-lib/src/destinations
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
    agent_readiness: 43.2
    band: exemplar
    in_catalog: true
    kin_score: 66.8
    mcp: &id007
      source: https://developers.google.com/workspace/gmail/api/guides/configure-mcp-server
      status: verified
    slug: google-gmail
    status: profiled
    tags: &id008
    - Drafts
    - Email
    - Gmail
    - Google
    url: /providers/google-gmail/
  layer: domain
  name: Gmail
  provider: google-gmail
  says: ships the Gmail SDK or integration code
  source: https://raw.githubusercontent.com/dittofeed/dittofeed/main/packages/backend-lib/package.json
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
    agent_readiness: 37.0
    band: exemplar
    in_catalog: true
    kin_score: 68.5
    mcp: &id011
      status: none
    slug: hyperdx
    status: profiled
    tags: &id012
    - Company
    - Logging
    - Monitoring
    - Observability
    url: /providers/hyperdx/
  layer: common
  name: HyperDX
  provider: hyperdx
  says: ships the HyperDX SDK or integration code
  source: https://raw.githubusercontent.com/dittofeed/dittofeed/main/packages/backend-lib/package.json
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
    agent_readiness: 41.9
    band: exemplar
    in_catalog: true
    kin_score: 77.7
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
  source: https://github.com/dittofeed/dittofeed/tree/main/packages/backend-lib/src/destinations
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
    agent_readiness: 43.0
    band: exemplar
    in_catalog: true
    kin_score: 70.5
    mcp: &id017
      source: https://github.com/ActiveCampaign/postmark-mcp
      status: verified
    slug: postmark
    status: profiled
    tags: &id018
    - Deliverability
    - Email
    - Messaging
    - Transactional Email
    url: /providers/postmark/
  layer: common
  name: Postmark
  provider: postmark
  says: ships the Postmark SDK or integration code
  source: https://github.com/dittofeed/dittofeed/tree/main/packages/backend-lib/src/destinations
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
    mcp: &id019
      source: https://resend.com/docs/mcp-server
      status: verified
    slug: resend
    status: profiled
    tags: &id020
    - Developer Tools
    - Email
    - Marketing Email
    - Transactional Email
    url: /providers/resend/
  layer: common
  name: Resend
  provider: resend
  says: ships the Resend SDK or integration code
  source: https://github.com/dittofeed/dittofeed/tree/main/packages/backend-lib/src/destinations
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
    mcp: &id023
      status: none
    slug: sendgrid
    status: profiled
    tags: &id024
    - Email
    - Email API
    - Marketing Email
    - SMTP
    url: /providers/sendgrid/
  layer: common
  name: SendGrid
  provider: sendgrid
  says: ships the SendGrid SDK or integration code
  source: https://github.com/dittofeed/dittofeed/tree/main/packages/backend-lib/src/destinations
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
    agent_band: agent-ready
    agent_readiness: 41.9
    band: exemplar
    in_catalog: true
    kin_score: 74.2
    mcp: &id025
      status: none
    slug: signalwire
    status: profiled
    tags: &id026
    - CPaaS
    - Communications
    - Company
    - Voice
    url: /providers/signalwire/
  layer: common
  name: SignalWire
  provider: signalwire
  says: ships the SignalWire SDK or integration code
  source: https://github.com/dittofeed/dittofeed/tree/main/packages/backend-lib/src/destinations
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
    mcp: &id027
      source: https://www.twilio.com/docs/ai/mcp
      status: verified
    slug: twilio
    status: profiled
    tags: &id028
    - Authentication
    - Communications
    - Contact Center
    - Email
    url: /providers/twilio/
  layer: common
  name: Twilio
  provider: twilio
  says: ships the Twilio SDK or integration code
  source: https://github.com/dittofeed/dittofeed/tree/main/packages/backend-lib/src/destinations
  tier: observed
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
  source: https://github.com/dittofeed/dittofeed/tree/main/packages/docs/integrations
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
    agent_band: agent-ready
    agent_readiness: 37.4
    band: developing
    in_catalog: true
    kin_score: 45.5
    mcp: &id015
      source: https://github.com/polytomic/mcp-connector
      status: verified
    slug: polytomic
    status: profiled
    tags: &id016
    - Data Integration
    - ELT
    - Reverse ETL
    - Unified API
    url: /providers/polytomic/
  layer: domain
  name: Polytomic
  provider: polytomic
  says: lists Polytomic as an integration
  source: https://github.com/dittofeed/dittofeed/tree/main/packages/docs/integrations
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
    mcp: &id021
      status: none
    slug: segment
    status: profiled
    tags: &id022
    - CDP
    - Company
    - Customer Data Platform
    - Identity Resolution
    url: /providers/segment/
  layer: domain
  name: Segment
  provider: segment
  says: lists Segment as an integration
  source: https://github.com/dittofeed/dittofeed/tree/main/packages/docs/integrations
  tier: declared
kind: open-source-saas
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/marketing-automation/dittofeed/
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
- agent_band: agent-ready
  agent_readiness: 43.2
  band: exemplar
  in_catalog: true
  kin_score: 66.8
  mcp: *id007
  name: Gmail
  slug: google-gmail
  status: profiled
  tags: *id008
  url: /providers/google-gmail/
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
- agent_band: agent-ready
  agent_readiness: 37.0
  band: exemplar
  in_catalog: true
  kin_score: 68.5
  mcp: *id011
  name: HyperDX
  slug: hyperdx
  status: profiled
  tags: *id012
  url: /providers/hyperdx/
- agent_band: agent-ready
  agent_readiness: 41.9
  band: exemplar
  in_catalog: true
  kin_score: 77.7
  mcp: *id013
  name: Mailchimp (Mandrill)
  slug: mailchimp
  status: profiled
  tags: *id014
  url: /providers/mailchimp/
- agent_band: agent-ready
  agent_readiness: 37.4
  band: developing
  in_catalog: true
  kin_score: 45.5
  mcp: *id015
  name: Polytomic
  slug: polytomic
  status: profiled
  tags: *id016
  url: /providers/polytomic/
- agent_band: agent-ready
  agent_readiness: 43.0
  band: exemplar
  in_catalog: true
  kin_score: 70.5
  mcp: *id017
  name: Postmark
  slug: postmark
  status: profiled
  tags: *id018
  url: /providers/postmark/
- agent_band: agent-ready
  agent_readiness: 49.8
  band: strong
  in_catalog: true
  kin_score: 56.8
  mcp: *id019
  name: Resend
  slug: resend
  status: profiled
  tags: *id020
  url: /providers/resend/
- agent_band: agent-aware
  agent_readiness: 27.7
  band: developing
  in_catalog: true
  kin_score: 42.9
  mcp: *id021
  name: Segment
  slug: segment
  status: profiled
  tags: *id022
  url: /providers/segment/
- agent_band: agent-ready
  agent_readiness: 40.7
  band: exemplar
  in_catalog: true
  kin_score: 84.0
  mcp: *id023
  name: SendGrid
  slug: sendgrid
  status: profiled
  tags: *id024
  url: /providers/sendgrid/
- agent_band: agent-ready
  agent_readiness: 41.9
  band: exemplar
  in_catalog: true
  kin_score: 74.2
  mcp: *id025
  name: SignalWire
  slug: signalwire
  status: profiled
  tags: *id026
  url: /providers/signalwire/
- agent_band: agent-native
  agent_readiness: 56.6
  band: exemplar
  in_catalog: true
  kin_score: 90.8
  mcp: *id027
  name: Twilio
  slug: twilio
  status: profiled
  tags: *id028
  url: /providers/twilio/
siblings:
- name: Braze
  rows: 31
  url: /applications/marketing-automation/braze/
- name: Customer.io
  rows: 21
  url: /applications/marketing-automation/customer-io/
- name: HubSpot Marketing Hub
  rows: 15
  url: /applications/marketing-automation/hubspot-marketing-hub/
- name: Laudspeaker
  rows: 13
  url: /applications/marketing-automation/laudspeaker/
- name: Mailchimp
  rows: 5
  url: /applications/marketing-automation/mailchimp/
- name: Mautic
  rows: 31
  url: /applications/marketing-automation/mautic/
sitemap: true
title: 'Dittofeed: Marketing Automation & Ads reference app'
---
