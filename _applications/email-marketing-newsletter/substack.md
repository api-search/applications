---
app: Substack
app_slug: substack
app_url: https://substack.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-400.60
  key: digital-marketing-management
  layer: domain
  name: Digital Marketing Management
  providers:
  - AppsFlyer
  - Facebook (Analytics, Login, Share)
  url: /capabilities/digital-marketing-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-610.50
  key: analytics-bi-management
  layer: common
  name: Analytics & BI Management
  providers:
  - Firebase Analytics
  url: /capabilities/analytics-bi-management/
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
category:
  id: email-marketing-newsletter
  name: Email Marketing & Newsletters
  url: /applications/email-marketing-newsletter/
counts:
  declared: 0
  observed: 4
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.substack.app/latest/
integrations:
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-ready
    agent_readiness: 53.4
    band: exemplar
    in_catalog: true
    kin_score: 72.1
    mcp: &id001
      source: https://registry.modelcontextprotocol.io/v0/servers?search=appsflyer
      status: verified
    slug: appsflyer
    status: profiled
    tags: &id002
    - Company
    - Marketing Analytics
    - Mobile Attribution
    - Mobile Measurement
    url: /providers/appsflyer/
  layer: domain
  name: AppsFlyer
  provider: appsflyer
  says: ships the AppsFlyer SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.substack.app/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-aware
    agent_readiness: 28.1
    band: developing
    in_catalog: true
    kin_score: 43.7
    mcp: &id003
      status: none
    slug: facebook
    status: profiled
    tags: &id004
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
  layer: domain
  name: Facebook (Analytics, Login, Share)
  provider: facebook
  says: ships the Facebook (Analytics, Login, Share) SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.substack.app/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-610.50
    key: analytics-bi-management
    name: Analytics & BI Management
    url: /capabilities/analytics-bi-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
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
  name: Firebase Analytics
  provider: firebase
  says: ships the Firebase Analytics SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.substack.app/latest/
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
    agent_readiness: 50.2
    band: exemplar
    in_catalog: true
    kin_score: 80.7
    mcp: &id007
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id008
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: common
  name: Sentry
  provider: sentry-system
  says: ships the Sentry SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.substack.app/latest/
  tier: observed
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/email-marketing-newsletter/substack/
providers:
- agent_band: agent-ready
  agent_readiness: 53.4
  band: exemplar
  in_catalog: true
  kin_score: 72.1
  mcp: *id001
  name: AppsFlyer
  slug: appsflyer
  status: profiled
  tags: *id002
  url: /providers/appsflyer/
- agent_band: agent-aware
  agent_readiness: 28.1
  band: developing
  in_catalog: true
  kin_score: 43.7
  mcp: *id003
  name: Facebook (Analytics, Login, Share)
  slug: facebook
  status: profiled
  tags: *id004
  url: /providers/facebook/
- agent_band: agent-ready
  agent_readiness: 39.9
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id005
  name: Firebase Analytics
  slug: google-firebase
  status: profiled
  tags: *id006
  url: /providers/google-firebase/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.7
  mcp: *id007
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id008
  url: /providers/sentry-system/
siblings:
- name: beehiiv
  rows: 22
  url: /applications/email-marketing-newsletter/beehiiv/
- name: Ghost
  rows: 17
  url: /applications/email-marketing-newsletter/ghost/
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
sitemap: true
title: 'Substack: Email Marketing & Newsletters reference app'
---
