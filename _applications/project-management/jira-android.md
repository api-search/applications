---
app: Jira (Android)
app_slug: jira-android
app_url: https://www.atlassian.com/software/jira
author: API Evangelist
capabilities:
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
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Google Analytics
  - Twilio Segment
  url: /capabilities/product-usage-analytics/
  via_parent: null
category:
  id: project-management
  name: Project & Work Management
  url: /applications/project-management/
counts:
  declared: 0
  observed: 3
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.atlassian.android.jira.core/latest/
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
    agent_readiness: 42.9
    band: exemplar
    in_catalog: true
    kin_score: 79.7
    mcp: &id001
      source: https://developers.google.com/analytics/devguides/MCP
      status: verified
    slug: google-analytics
    status: profiled
    tags: &id002
    - Analytics
    - Data
    - Google
    - Metrics
    url: /providers/google-analytics/
  layer: common
  name: Google Analytics
  provider: google-analytics
  says: ships the Google Analytics SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.atlassian.android.jira.core/latest/
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
    mcp: &id003
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id004
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: common
  name: Sentry
  provider: sentry-system
  says: ships the Sentry SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.atlassian.android.jira.core/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-aware
    agent_readiness: 27.7
    band: developing
    in_catalog: true
    kin_score: 42.9
    mcp: &id005
      status: none
    slug: segment
    status: profiled
    tags: &id006
    - CDP
    - Company
    - Customer Data Platform
    - Identity Resolution
    url: /providers/segment/
  layer: common
  name: Twilio Segment
  provider: segment
  says: ships the Twilio Segment SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.atlassian.android.jira.core/latest/
  tier: observed
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/project-management/jira-android/
providers:
- agent_band: agent-ready
  agent_readiness: 42.9
  band: exemplar
  in_catalog: true
  kin_score: 79.7
  mcp: *id001
  name: Google Analytics
  slug: google-analytics
  status: profiled
  tags: *id002
  url: /providers/google-analytics/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.7
  mcp: *id003
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id004
  url: /providers/sentry-system/
- agent_band: agent-aware
  agent_readiness: 27.7
  band: developing
  in_catalog: true
  kin_score: 42.9
  mcp: *id005
  name: Twilio Segment
  slug: segment
  status: profiled
  tags: *id006
  url: /providers/segment/
siblings:
- name: Asana
  rows: 22
  url: /applications/project-management/asana/
- name: Leantime
  rows: 15
  url: /applications/project-management/leantime/
- name: monday.com (Android)
  rows: 4
  url: /applications/project-management/monday-com-android/
- name: OpenProject
  rows: 15
  url: /applications/project-management/openproject/
- name: Plane
  rows: 9
  url: /applications/project-management/plane/
- name: Taiga
  rows: 10
  url: /applications/project-management/taiga/
- name: Trello (Android)
  rows: 3
  url: /applications/project-management/trello-android/
- name: Vikunja
  rows: 8
  url: /applications/project-management/vikunja/
sitemap: true
title: 'Jira (Android): Project & Work Management reference app'
---
