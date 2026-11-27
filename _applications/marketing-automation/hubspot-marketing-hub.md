---
app: HubSpot Marketing Hub
app_slug: hubspot-marketing-hub
app_url: https://www.hubspot.com/products/marketing
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-400.60
  key: digital-marketing-management
  layer: domain
  name: Digital Marketing Management
  providers:
  - ChatGPT ads
  - Google Ads
  - LinkedIn Ads
  - Meta Ads
  - Microsoft Ads
  - Reddit Ads
  - TikTok Ads
  url: /capabilities/digital-marketing-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-400.60.40
  key: BC-400.60.40
  layer: domain
  name: Social Media Management
  providers:
  - Facebook
  - Instagram
  - LinkedIn
  - TikTok
  - YouTube
  url: /capabilities/digital-marketing-management/
  via_parent: Digital Marketing Management
- attribution: Turbo EA
  id: BC-430.50
  key: customer-feedback-management
  layer: common
  name: Customer Feedback Management
  providers:
  - Wootric
  url: /capabilities/customer-feedback-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - New Relic
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Google Firebase Analytics / Crashlytics
  url: /capabilities/product-usage-analytics/
  via_parent: null
category:
  id: marketing-automation
  name: Marketing Automation & Ads
  url: /applications/marketing-automation/
counts:
  declared: 12
  observed: 3
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.hubspot.android/latest/
- route: integrations page
  url: https://www.hubspot.com/products/marketing/ads
- route: integrations page
  url: https://www.hubspot.com/products/marketing/social-inbox
integrations:
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-ready
    agent_readiness: 39.9
    band: strong
    in_catalog: true
    kin_score: 62.0
    mcp: &id010
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: google-firebase
    status: profiled
    tags: &id011
    - Analytics
    - Authentication
    - Backend-as-a-Service
    - Cloud Messaging
    url: /providers/google-firebase/
  layer: common
  name: Google Firebase Analytics / Crashlytics
  provider: firebase
  says: ships the Google Firebase Analytics / Crashlytics SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.hubspot.android/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-ready
    agent_readiness: 44.8
    band: exemplar
    in_catalog: true
    kin_score: 74.4
    mcp: &id018
      source: https://docs.newrelic.com/docs/agentic-ai/mcp/overview/
      status: verified
    slug: new-relic
    status: profiled
    tags: &id019
    - APM
    - Analysis
    - Analytics
    - DevOps
    url: /providers/new-relic/
  layer: common
  name: New Relic
  provider: new-relic
  says: ships the New Relic SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.hubspot.android/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-430.50
    key: customer-feedback-management
    name: Customer Feedback Management
    url: /capabilities/customer-feedback-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-aware
    agent_readiness: 25.6
    band: thin
    in_catalog: true
    kin_score: 32.4
    mcp: &id024
      status: none
    slug: wootric
    status: profiled
    tags: &id025
    - CES
    - CSAT
    - Customer Experience
    - NPS
    url: /providers/wootric/
  layer: common
  name: Wootric
  provider: wootric
  says: ships the Wootric SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.hubspot.android/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 57.5
    band: exemplar
    in_catalog: true
    kin_score: 82.5
    mcp: &id004
      source: https://platform.openai.com/docs/mcp
      status: verified
    slug: openai
    status: profiled
    tags: &id005
    - Artificial Intelligence
    - Generative AI
    - LLM
    - OpenAI
    url: /providers/openai/
  layer: domain
  name: ChatGPT ads
  provider: openai
  says: lists ChatGPT ads as an integration
  source: https://www.hubspot.com/products/marketing/ads
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-400.60.40
    key: BC-400.60.40
    name: Social Media Management
    url: /capabilities/digital-marketing-management/
    via_parent: Digital Marketing Management
  credit: null
  facts: &id002
    agent_band: agent-aware
    agent_readiness: 28.1
    band: developing
    in_catalog: true
    kin_score: 43.7
    mcp: &id006
      status: none
    slug: facebook
    status: profiled
    tags: &id007
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
  layer: domain
  name: Facebook
  provider: facebook
  says: lists Facebook as an integration
  source: https://www.hubspot.com/products/marketing/social-inbox
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 42.1
    band: exemplar
    in_catalog: true
    kin_score: 73.4
    mcp: &id008
      source: https://developers.google.com/google-ads/api/docs/developer-toolkit/mcp-server
      status: verified
    slug: google-ads
    status: profiled
    tags: &id009
    - Advertising
    - Campaign Management
    - Digital Advertising
    - Google
    url: /providers/google-ads/
  layer: domain
  name: Google Ads
  provider: google-ads
  says: lists Google Ads as an integration
  source: https://www.hubspot.com/products/marketing/ads
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-400.60.40
    key: BC-400.60.40
    name: Social Media Management
    url: /capabilities/digital-marketing-management/
    via_parent: Digital Marketing Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.6
    band: exemplar
    in_catalog: true
    kin_score: 67.8
    mcp: &id012
      status: none
    slug: instagram
    status: profiled
    tags: &id013
    - Instagram
    - Meta
    - Photos
    - Social Media
    url: /providers/instagram/
  layer: domain
  name: Instagram
  provider: instagram
  says: lists Instagram as an integration
  source: https://www.hubspot.com/products/marketing/social-inbox
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-400.60.40
    key: BC-400.60.40
    name: Social Media Management
    url: /capabilities/digital-marketing-management/
    via_parent: Digital Marketing Management
  credit: null
  facts: &id001
    agent_band: agent-ready
    agent_readiness: 46.5
    band: exemplar
    in_catalog: true
    kin_score: 77.8
    mcp: &id014
      status: none
    slug: linkedin
    status: profiled
    tags: &id015
    - Business
    - Careers
    - LinkedIn
    - Marketing
    url: /providers/linkedin/
  layer: domain
  name: LinkedIn
  provider: linkedin
  says: lists LinkedIn as an integration
  source: https://www.hubspot.com/products/marketing/social-inbox
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  credit: null
  facts: *id001
  layer: domain
  name: LinkedIn Ads
  provider: linkedin
  says: lists LinkedIn Ads as an integration
  source: https://www.hubspot.com/products/marketing/ads
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  credit: null
  facts: *id002
  layer: domain
  name: Meta Ads
  provider: facebook
  says: lists Meta Ads as an integration
  source: https://www.hubspot.com/products/marketing/ads
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 11.7
    band: developing
    in_catalog: true
    kin_score: 47.4
    mcp: &id016
      status: none
    slug: microsoft-advertising
    status: profiled
    tags: &id017
    - Advertising
    - Analytics
    - Bing Ads
    - Bulk Operations
    url: /providers/microsoft-advertising/
  layer: domain
  name: Microsoft Ads
  provider: microsoft-advertising
  says: lists Microsoft Ads as an integration
  source: https://www.hubspot.com/products/marketing/ads
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 43.0
    band: strong
    in_catalog: true
    kin_score: 64.4
    mcp: &id020
      source: https://github.com/reddit/devvit-mcp
      status: verified
    slug: reddit
    status: profiled
    tags: &id021
    - Advertising
    - Community
    - Content
    - Reddit
    url: /providers/reddit/
  layer: domain
  name: Reddit Ads
  provider: reddit
  says: lists Reddit Ads as an integration
  source: https://www.hubspot.com/products/marketing/ads
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-400.60.40
    key: BC-400.60.40
    name: Social Media Management
    url: /capabilities/digital-marketing-management/
    via_parent: Digital Marketing Management
  credit: null
  facts: &id003
    agent_band: agent-aware
    agent_readiness: 19.2
    band: developing
    in_catalog: true
    kin_score: 40.5
    mcp: &id022
      status: none
    slug: tiktok
    status: profiled
    tags: &id023
    - Advertising
    - Commerce
    - Content
    - TikTok
    url: /providers/tiktok/
  layer: domain
  name: TikTok
  provider: tiktok
  says: lists TikTok as an integration
  source: https://www.hubspot.com/products/marketing/social-inbox
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  credit: null
  facts: *id003
  layer: domain
  name: TikTok Ads
  provider: tiktok
  says: lists TikTok Ads as an integration
  source: https://www.hubspot.com/products/marketing/ads
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-400.60.40
    key: BC-400.60.40
    name: Social Media Management
    url: /capabilities/digital-marketing-management/
    via_parent: Digital Marketing Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 41.4
    band: strong
    in_catalog: true
    kin_score: 65.4
    mcp: &id026
      status: none
    slug: youtube
    status: profiled
    tags: &id027
    - Google
    - Media
    - Video
    - YouTube
    url: /providers/youtube/
  layer: domain
  name: YouTube
  provider: youtube
  says: lists YouTube as an integration
  source: https://www.hubspot.com/products/marketing/social-inbox
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/marketing-automation/hubspot-marketing-hub/
providers:
- agent_band: agent-native
  agent_readiness: 57.5
  band: exemplar
  in_catalog: true
  kin_score: 82.5
  mcp: *id004
  name: ChatGPT ads
  slug: openai
  status: profiled
  tags: *id005
  url: /providers/openai/
- agent_band: agent-aware
  agent_readiness: 28.1
  band: developing
  in_catalog: true
  kin_score: 43.7
  mcp: *id006
  name: Facebook
  slug: facebook
  status: profiled
  tags: *id007
  url: /providers/facebook/
- agent_band: agent-ready
  agent_readiness: 42.1
  band: exemplar
  in_catalog: true
  kin_score: 73.4
  mcp: *id008
  name: Google Ads
  slug: google-ads
  status: profiled
  tags: *id009
  url: /providers/google-ads/
- agent_band: agent-ready
  agent_readiness: 39.9
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id010
  name: Google Firebase Analytics / Crashlytics
  slug: google-firebase
  status: profiled
  tags: *id011
  url: /providers/google-firebase/
- agent_band: agent-ready
  agent_readiness: 38.6
  band: exemplar
  in_catalog: true
  kin_score: 67.8
  mcp: *id012
  name: Instagram
  slug: instagram
  status: profiled
  tags: *id013
  url: /providers/instagram/
- agent_band: agent-ready
  agent_readiness: 46.5
  band: exemplar
  in_catalog: true
  kin_score: 77.8
  mcp: *id014
  name: LinkedIn
  slug: linkedin
  status: profiled
  tags: *id015
  url: /providers/linkedin/
- agent_band: agent-aware
  agent_readiness: 11.7
  band: developing
  in_catalog: true
  kin_score: 47.4
  mcp: *id016
  name: Microsoft Ads
  slug: microsoft-advertising
  status: profiled
  tags: *id017
  url: /providers/microsoft-advertising/
- agent_band: agent-ready
  agent_readiness: 44.8
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id018
  name: New Relic
  slug: new-relic
  status: profiled
  tags: *id019
  url: /providers/new-relic/
- agent_band: agent-ready
  agent_readiness: 43.0
  band: strong
  in_catalog: true
  kin_score: 64.4
  mcp: *id020
  name: Reddit Ads
  slug: reddit
  status: profiled
  tags: *id021
  url: /providers/reddit/
- agent_band: agent-aware
  agent_readiness: 19.2
  band: developing
  in_catalog: true
  kin_score: 40.5
  mcp: *id022
  name: TikTok
  slug: tiktok
  status: profiled
  tags: *id023
  url: /providers/tiktok/
- agent_band: agent-aware
  agent_readiness: 25.6
  band: thin
  in_catalog: true
  kin_score: 32.4
  mcp: *id024
  name: Wootric
  slug: wootric
  status: profiled
  tags: *id025
  url: /providers/wootric/
- agent_band: agent-ready
  agent_readiness: 41.4
  band: strong
  in_catalog: true
  kin_score: 65.4
  mcp: *id026
  name: YouTube
  slug: youtube
  status: profiled
  tags: *id027
  url: /providers/youtube/
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
title: 'HubSpot Marketing Hub: Marketing Automation & Ads reference app'
---
