---
app: LinkedIn
app_slug: linkedin
app_url: https://www.linkedin.com/jobs/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-170.50
  key: AE-170.50
  layer: domain
  name: Social Networks & Community
  providers:
  - Facebook
  url: /capabilities/social-networks-community/
  via_parent: null
- attribution: Turbo EA
  id: BC-430.50
  key: customer-feedback-management
  layer: common
  name: Customer Feedback Management
  providers:
  - Qualtrics
  url: /capabilities/customer-feedback-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Cedexis Radar
  - Microsoft Visual Studio App Center
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Facebook
  - Microsoft Visual Studio App Center
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-160.10.30
  key: AE-160.10.30
  layer: common
  name: Social & Federated Login
  providers:
  - Facebook
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
category:
  id: job-search
  name: Job Search
  url: /applications/job-search/
counts:
  declared: 0
  observed: 7
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.linkedin.android/latest/
integrations:
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id003
      status: unchecked
    slug: cedexis
    status: queued for profiling
    tags: &id004 []
    url: null
  layer: common
  name: Cedexis Radar
  provider: cedexis
  says: ships the Cedexis Radar SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.linkedin.android/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts: &id001
    agent_band: agent-aware
    agent_readiness: 28.1
    band: developing
    in_catalog: true
    kin_score: 43.7
    mcp: &id005
      status: none
    slug: facebook
    status: profiled
    tags: &id006
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
  layer: common
  name: Facebook
  provider: facebook
  says: ships the Facebook SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.linkedin.android/latest/
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts: *id001
  layer: common
  name: Facebook
  provider: facebook
  says: ships the Facebook SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.linkedin.android/latest/
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.50
    key: AE-170.50
    name: Social Networks & Community
    url: /capabilities/social-networks-community/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts: *id001
  layer: domain
  name: Facebook
  provider: facebook
  says: ships the Facebook SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.linkedin.android/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts: &id002
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id007
      status: unchecked
    slug: microsoft-app-center
    status: queued for profiling
    tags: &id008 []
    url: null
  layer: common
  name: Microsoft Visual Studio App Center
  provider: microsoft-app-center
  says: ships the Microsoft Visual Studio App Center SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.linkedin.android/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts: *id002
  layer: common
  name: Microsoft Visual Studio App Center
  provider: microsoft-app-center
  says: ships the Microsoft Visual Studio App Center SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.linkedin.android/latest/
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
    agent_readiness: 19.6
    band: developing
    in_catalog: true
    kin_score: 45.7
    mcp: &id009
      status: none
    slug: qualtrics
    status: profiled
    tags: &id010
    - Customer Experience
    - Employee Experience
    - Experience Management
    - Surveys
    url: /providers/qualtrics/
  layer: common
  name: Qualtrics
  provider: qualtrics
  says: ships the Qualtrics SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.linkedin.android/latest/
  tier: observed
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/job-search/linkedin/
providers:
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id003
  name: Cedexis Radar
  slug: cedexis
  status: queued for profiling
  tags: *id004
  url: null
- agent_band: agent-aware
  agent_readiness: 28.1
  band: developing
  in_catalog: true
  kin_score: 43.7
  mcp: *id005
  name: Facebook
  slug: facebook
  status: profiled
  tags: *id006
  url: /providers/facebook/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id007
  name: Microsoft Visual Studio App Center
  slug: microsoft-app-center
  status: queued for profiling
  tags: *id008
  url: null
- agent_band: agent-aware
  agent_readiness: 19.6
  band: developing
  in_catalog: true
  kin_score: 45.7
  mcp: *id009
  name: Qualtrics
  slug: qualtrics
  status: profiled
  tags: *id010
  url: /providers/qualtrics/
siblings:
- name: Glassdoor
  rows: 2
  url: /applications/job-search/glassdoor/
- name: Indeed
  rows: 2
  url: /applications/job-search/indeed/
- name: JobSpy
  rows: 9
  url: /applications/job-search/jobspy/
- name: JobSync
  rows: 8
  url: /applications/job-search/jobsync/
- name: Reactive Resume
  rows: 30
  url: /applications/job-search/reactive-resume/
- name: Resume Matcher
  rows: 8
  url: /applications/job-search/resume-matcher/
sitemap: true
title: 'LinkedIn: Job Search reference app'
---
