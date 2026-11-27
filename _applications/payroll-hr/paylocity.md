---
app: Paylocity
app_slug: paylocity
app_url: https://www.paylocity.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-170.30.30
  key: AE-170.30.30
  layer: common
  name: Avatars, GIFs & Stickers
  providers:
  - GIPHY
  url: /capabilities/photo-image-libraries/
  via_parent: Photo & Image Libraries
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Firebase (Crashlytics / Analytics)
  - Pendo
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: Turbo EA
  id: BC-3760.30
  key: programmatic-sales-management
  layer: common
  name: Programmatic Sales Management
  providers:
  - IAB Open Measurement
  url: /capabilities/programmatic-sales-management/
  via_parent: null
category:
  id: payroll-hr
  name: HR, Payroll & People Ops
  url: /applications/payroll-hr/
counts:
  declared: 0
  observed: 4
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.paylocity.paylocitymobile/latest/
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
    mcp: &id001
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: google-firebase
    status: profiled
    tags: &id002
    - Analytics
    - Authentication
    - Backend-as-a-Service
    - Cloud Messaging
    url: /providers/google-firebase/
  layer: common
  name: Firebase (Crashlytics / Analytics)
  provider: firebase
  says: ships the Firebase (Crashlytics / Analytics) SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.paylocity.paylocitymobile/latest/
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.30.30
    key: AE-170.30.30
    name: Avatars, GIFs & Stickers
    url: /capabilities/photo-image-libraries/
    via_parent: Photo & Image Libraries
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-aware
    agent_readiness: 26.8
    band: strong
    in_catalog: true
    kin_score: 56.0
    mcp: &id003
      status: none
    slug: giphy
    status: profiled
    tags: &id004
    - GIFs
    - Media
    - Photography
    - Stickers
    url: /providers/giphy/
  layer: common
  name: GIPHY
  provider: giphy
  says: ships the GIPHY SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.paylocity.paylocitymobile/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-3760.30
    key: programmatic-sales-management
    name: Programmatic Sales Management
    url: /capabilities/programmatic-sales-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-ready
    agent_readiness: 36.9
    band: strong
    in_catalog: true
    kin_score: 55.6
    mcp: &id005
      source: https://github.com/IABTechLab/agentic-real-time-framework
      status: verified
    slug: iab-tech-lab
    status: profiled
    tags: &id006
    - AdTech
    - Advertising
    - Company
    - Standards
    url: /providers/iab-tech-lab/
  layer: common
  name: IAB Open Measurement
  provider: iab-tech-lab
  says: ships the IAB Open Measurement SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.paylocity.paylocitymobile/latest/
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
    agent_band: agent-ready
    agent_readiness: 34.7
    band: strong
    in_catalog: true
    kin_score: 57.0
    mcp: &id007
      source: https://support.pendo.io/hc/en-us/articles/41102236924955
      status: verified
    slug: pendoio
    status: profiled
    tags: &id008
    - Company
    - Digital Adoption
    - Product Analytics
    - Product Experience
    url: /providers/pendoio/
  layer: common
  name: Pendo
  provider: pendoio
  says: ships the Pendo SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.paylocity.paylocitymobile/latest/
  tier: observed
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/payroll-hr/paylocity/
providers:
- agent_band: agent-ready
  agent_readiness: 39.9
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id001
  name: Firebase (Crashlytics / Analytics)
  slug: google-firebase
  status: profiled
  tags: *id002
  url: /providers/google-firebase/
- agent_band: agent-aware
  agent_readiness: 26.8
  band: strong
  in_catalog: true
  kin_score: 56.0
  mcp: *id003
  name: GIPHY
  slug: giphy
  status: profiled
  tags: *id004
  url: /providers/giphy/
- agent_band: agent-ready
  agent_readiness: 36.9
  band: strong
  in_catalog: true
  kin_score: 55.6
  mcp: *id005
  name: IAB Open Measurement
  slug: iab-tech-lab
  status: profiled
  tags: *id006
  url: /providers/iab-tech-lab/
- agent_band: agent-ready
  agent_readiness: 34.7
  band: strong
  in_catalog: true
  kin_score: 57.0
  mcp: *id007
  name: Pendo
  slug: pendoio
  status: profiled
  tags: *id008
  url: /providers/pendoio/
siblings:
- name: ADP Mobile Solutions
  rows: 5
  url: /applications/payroll-hr/adp-mobile-solutions/
- name: Connecteam
  rows: 3
  url: /applications/payroll-hr/connecteam/
- name: Deel
  rows: 35
  url: /applications/payroll-hr/deel/
- name: Frappe HR
  rows: 1
  url: /applications/payroll-hr/frappe-hr/
- name: Homebase
  rows: 19
  url: /applications/payroll-hr/homebase/
- name: Horilla
  rows: 7
  url: /applications/payroll-hr/horilla/
- name: OrangeHRM
  rows: 0
  url: /applications/payroll-hr/orangehrm/
- name: Workday
  rows: 2
  url: /applications/payroll-hr/workday/
sitemap: true
title: 'Paylocity: HR, Payroll & People Ops reference app'
---
