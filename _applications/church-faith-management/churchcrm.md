---
app: ChurchCRM
app_slug: churchcrm
app_url: https://github.com/ChurchCRM/CRM
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-170.10.40
  key: AE-170.10.40
  layer: domain
  name: Live Presentation & Broadcast Control
  providers:
  - OpenLP
  url: /capabilities/video-platforms/
  via_parent: Video Platforms
- attribution: API Evangelist extension
  id: AE-170.30.30
  key: AE-170.30.30
  layer: common
  name: Avatars, GIFs & Stickers
  providers:
  - Gravatar
  url: /capabilities/photo-image-libraries/
  via_parent: Photo & Image Libraries
- attribution: API Evangelist extension
  id: AE-150.10.20
  key: AE-150.10.20
  layer: common
  name: Email Marketing Sends
  providers:
  - Mailchimp
  url: /capabilities/email/
  via_parent: Email
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Google Analytics
  - PostHog
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.20.10
  key: AE-150.20.10
  layer: common
  name: SMS
  providers:
  - Vonage
  url: /capabilities/sms-messaging-apps/
  via_parent: SMS & Messaging Apps
- attribution: Turbo EA
  id: BC-4200.40
  key: software-construction-management
  layer: common
  name: Software Construction Management
  providers:
  - GitHub
  url: /capabilities/software-construction-management/
  via_parent: null
category:
  id: church-faith-management
  name: Church & Faith Community Management
  url: /applications/church-faith-management/
counts:
  declared: 0
  observed: 7
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/ChurchCRM/CRM/blob/master/package.json
- route: dependency manifest
  url: https://github.com/ChurchCRM/CRM/blob/master/src/composer.json
- route: source code
  url: https://github.com/ChurchCRM/CRM/blob/master/.env.example
- route: source code
  url: https://github.com/ChurchCRM/CRM/tree/master/src/plugins/core
integrations:
- capability:
    attribution: Turbo EA
    id: BC-4200.40
    key: software-construction-management
    name: Software Construction Management
    url: /capabilities/software-construction-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 62.4
    band: exemplar
    in_catalog: true
    kin_score: 85.0
    mcp: &id001
      source: https://github.com/github/github-mcp-server
      status: verified
    slug: github
    status: profiled
    tags: &id002
    - Code
    - Developer Tools
    - Pipelines
    - Platform
    url: /providers/github/
  layer: common
  name: GitHub
  provider: github
  says: ships the GitHub SDK or integration code
  source: https://github.com/ChurchCRM/CRM/blob/master/src/composer.json
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
    agent_readiness: 42.9
    band: exemplar
    in_catalog: true
    kin_score: 79.7
    mcp: &id003
      source: https://developers.google.com/analytics/devguides/MCP
      status: verified
    slug: google-analytics
    status: profiled
    tags: &id004
    - Analytics
    - Data
    - Google
    - Metrics
    url: /providers/google-analytics/
  layer: common
  name: Google Analytics
  provider: google-analytics
  says: ships the Google Analytics SDK or integration code
  source: https://github.com/ChurchCRM/CRM/tree/master/src/plugins/core/google-analytics
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.30.30
    key: AE-170.30.30
    name: Avatars, GIFs & Stickers
    url: /capabilities/photo-image-libraries/
    via_parent: Photo & Image Libraries
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 32.7
    band: developing
    in_catalog: true
    kin_score: 41.2
    mcp: &id005
      source: https://github.com/Automattic/mcp-server-gravatar
      status: verified
    slug: gravatar
    status: profiled
    tags: &id006
    - Avatars
    - Identity
    - Profiles
    - Social
    url: /providers/gravatar/
  layer: common
  name: Gravatar
  provider: gravatar
  says: ships the Gravatar SDK or integration code
  source: https://github.com/ChurchCRM/CRM/tree/master/src/plugins/core/gravatar
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
    mcp: &id007
      status: none
    slug: mailchimp
    status: profiled
    tags: &id008
    - Campaigns
    - Email Marketing
    - Marketing Automation
    - Newsletters
    url: /providers/mailchimp/
  layer: common
  name: Mailchimp
  provider: mailchimp
  says: ships the Mailchimp SDK or integration code
  source: https://github.com/ChurchCRM/CRM/tree/master/src/plugins/core/mailchimp
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.10.40
    key: AE-170.10.40
    name: Live Presentation & Broadcast Control
    url: /capabilities/video-platforms/
    via_parent: Video Platforms
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: minimal
    in_catalog: true
    kin_score: 9.4
    mcp: &id009
      status: unchecked
    slug: openlp
    status: profiled
    tags: &id010
    - Company
    - Open Source
    - Presentation
    - Worship
    url: /providers/openlp/
  layer: domain
  name: OpenLP
  provider: openlp
  says: ships the OpenLP SDK or integration code
  source: https://github.com/ChurchCRM/CRM/tree/master/src/plugins/core/openlp
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
  source: https://github.com/ChurchCRM/CRM/blob/master/package.json
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
    agent_readiness: 40.0
    band: exemplar
    in_catalog: true
    kin_score: 68.8
    mcp: &id013
      source: https://github.com/Vonage/vonage-mcp-server-documentation
      status: verified
    slug: vonage
    status: profiled
    tags: &id014
    - Communications
    - Messaging
    - Telecommunications
    - Video Conferencing
    url: /providers/vonage/
  layer: common
  name: Vonage
  provider: vonage
  says: ships the Vonage SDK or integration code
  source: https://github.com/ChurchCRM/CRM/tree/master/src/plugins/core/vonage
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/church-faith-management/churchcrm/
providers:
- agent_band: agent-ready
  agent_readiness: 62.4
  band: exemplar
  in_catalog: true
  kin_score: 85.0
  mcp: *id001
  name: GitHub
  slug: github
  status: profiled
  tags: *id002
  url: /providers/github/
- agent_band: agent-ready
  agent_readiness: 42.9
  band: exemplar
  in_catalog: true
  kin_score: 79.7
  mcp: *id003
  name: Google Analytics
  slug: google-analytics
  status: profiled
  tags: *id004
  url: /providers/google-analytics/
- agent_band: agent-ready
  agent_readiness: 32.7
  band: developing
  in_catalog: true
  kin_score: 41.2
  mcp: *id005
  name: Gravatar
  slug: gravatar
  status: profiled
  tags: *id006
  url: /providers/gravatar/
- agent_band: agent-ready
  agent_readiness: 41.9
  band: exemplar
  in_catalog: true
  kin_score: 77.7
  mcp: *id007
  name: Mailchimp
  slug: mailchimp
  status: profiled
  tags: *id008
  url: /providers/mailchimp/
- agent_band: human-only
  agent_readiness: 3.0
  band: minimal
  in_catalog: true
  kin_score: 9.4
  mcp: *id009
  name: OpenLP
  slug: openlp
  status: profiled
  tags: *id010
  url: /providers/openlp/
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
  agent_readiness: 40.0
  band: exemplar
  in_catalog: true
  kin_score: 68.8
  mcp: *id013
  name: Vonage
  slug: vonage
  status: profiled
  tags: *id014
  url: /providers/vonage/
siblings:
- name: OpenLP
  rows: 6
  url: /applications/church-faith-management/openlp/
- name: Planning Center
  rows: 20
  url: /applications/church-faith-management/planning-center/
- name: Pushpay
  rows: 20
  url: /applications/church-faith-management/pushpay/
- name: Rock RMS
  rows: 21
  url: /applications/church-faith-management/rock-rms/
- name: Tithe.ly
  rows: 11
  url: /applications/church-faith-management/tithe-ly/
sitemap: true
title: 'ChurchCRM: Church & Faith Community Management reference app'
---
