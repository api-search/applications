---
app: Ticketmaster
app_slug: ticketmaster
app_url: https://www.ticketmaster.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-420.10
  key: customer-data-management
  layer: common
  name: Customer Data Management
  providers:
  - mParticle
  url: /capabilities/customer-data-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-400.60
  key: digital-marketing-management
  layer: common
  name: Digital Marketing Management
  providers:
  - Salesforce Marketing Cloud
  url: /capabilities/digital-marketing-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-902
  key: AE-902
  layer: common
  name: Mobile Attribution & Deep Linking
  providers:
  - AppsFlyer
  url: /capabilities/mobile-attribution-deep-linking/
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
  id: event-ticketing
  name: Events & Ticketing
  url: /applications/event-ticketing/
counts:
  declared: 0
  observed: 4
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://web.archive.org/web/20251108232712/https://reports.exodus-privacy.eu.org/en/reports/com.ticketmaster.mobile.android.na/latest/
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-902
    key: AE-902
    name: Mobile Attribution & Deep Linking
    url: /capabilities/mobile-attribution-deep-linking/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-ready
    agent_readiness: 46.4
    band: exemplar
    in_catalog: true
    kin_score: 72.9
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
  layer: common
  name: AppsFlyer
  provider: appsflyer
  says: ships the AppsFlyer SDK or integration code
  source: https://web.archive.org/web/20251108232712/https://reports.exodus-privacy.eu.org/en/reports/com.ticketmaster.mobile.android.na/latest/
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
    agent_readiness: 14.2
    band: developing
    in_catalog: true
    kin_score: 50.3
    mcp: &id003
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: firebase
    status: profiled
    tags: &id004
    - Application Development
    - Backend-as-a-Service
    - Company
    - Mobile
    url: /providers/firebase/
  layer: common
  name: Google Firebase Analytics / Crashlytics
  provider: firebase
  says: ships the Google Firebase Analytics / Crashlytics SDK or integration code
  source: https://web.archive.org/web/20251108232712/https://reports.exodus-privacy.eu.org/en/reports/com.ticketmaster.mobile.android.na/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-420.10
    key: customer-data-management
    name: Customer Data Management
    url: /capabilities/customer-data-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-ready
    agent_readiness: 45.7
    band: strong
    in_catalog: true
    kin_score: 58.7
    mcp: &id005
      status: none
    slug: mparticle
    status: profiled
    tags: &id006
    - Analytics
    - CDP
    - Customer Data Platform
    - Identity Resolution
    url: /providers/mparticle/
  layer: common
  name: mParticle
  provider: mparticle
  says: ships the mParticle SDK or integration code
  source: https://web.archive.org/web/20251108232712/https://reports.exodus-privacy.eu.org/en/reports/com.ticketmaster.mobile.android.na/latest/
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
    agent_band: agent-ready
    agent_readiness: 56.8
    band: exemplar
    in_catalog: true
    kin_score: 80.5
    mcp: &id007
      status: none
    slug: salesforce-marketing-cloud
    status: profiled
    tags: &id008
    - Automation
    - Content Management
    - Customer Journey
    - Digital Marketing
    url: /providers/salesforce-marketing-cloud/
  layer: common
  name: Salesforce Marketing Cloud
  provider: salesforce-marketing-cloud
  says: ships the Salesforce Marketing Cloud SDK or integration code
  source: https://web.archive.org/web/20251108232712/https://reports.exodus-privacy.eu.org/en/reports/com.ticketmaster.mobile.android.na/latest/
  tier: observed
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/event-ticketing/ticketmaster/
providers:
- agent_band: agent-ready
  agent_readiness: 46.4
  band: exemplar
  in_catalog: true
  kin_score: 72.9
  mcp: *id001
  name: AppsFlyer
  slug: appsflyer
  status: profiled
  tags: *id002
  url: /providers/appsflyer/
- agent_band: agent-aware
  agent_readiness: 14.2
  band: developing
  in_catalog: true
  kin_score: 50.3
  mcp: *id003
  name: Google Firebase Analytics / Crashlytics
  slug: firebase
  status: profiled
  tags: *id004
  url: /providers/firebase/
- agent_band: agent-ready
  agent_readiness: 45.7
  band: strong
  in_catalog: true
  kin_score: 58.7
  mcp: *id005
  name: mParticle
  slug: mparticle
  status: profiled
  tags: *id006
  url: /providers/mparticle/
- agent_band: agent-ready
  agent_readiness: 56.8
  band: exemplar
  in_catalog: true
  kin_score: 80.5
  mcp: *id007
  name: Salesforce Marketing Cloud
  slug: salesforce-marketing-cloud
  status: profiled
  tags: *id008
  url: /providers/salesforce-marketing-cloud/
siblings:
- name: alf.io
  rows: 13
  url: /applications/event-ticketing/alf-io/
- name: Hi.Events
  rows: 6
  url: /applications/event-ticketing/hi-events/
- name: Indico
  rows: 11
  url: /applications/event-ticketing/indico/
- name: Luma
  rows: 3
  url: /applications/event-ticketing/luma/
- name: pretalx
  rows: 4
  url: /applications/event-ticketing/pretalx/
- name: pretix
  rows: 23
  url: /applications/event-ticketing/pretix/
- name: Tito
  rows: 3
  url: /applications/event-ticketing/tito/
sitemap: true
title: 'Ticketmaster: Events & Ticketing reference app'
---
