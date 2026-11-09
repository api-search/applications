---
app: TripIt
app_slug: tripit
app_url: https://www.tripit.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-120.20.30
  key: AE-120.20.30
  layer: domain
  name: Indoor & Venue Maps
  providers:
  - LocusLabs (Atrius) indoor airport maps
  url: /capabilities/maps-tiles/
  via_parent: Maps & Tiles
- attribution: Turbo EA
  id: BC-430.50
  key: customer-feedback-management
  layer: common
  name: Customer Feedback Management
  providers:
  - Apptentive (Alchemer Mobile)
  url: /capabilities/customer-feedback-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-400.60
  key: digital-marketing-management
  layer: common
  name: Digital Marketing Management
  providers:
  - Adobe Experience Cloud
  url: /capabilities/digital-marketing-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Dynatrace
  url: /capabilities/observability-management/
  via_parent: null
category:
  id: travel-booking
  name: Travel Booking & Trip Planning
  url: /applications/travel-booking/
counts:
  declared: 0
  observed: 4
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.tripit/latest/
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
    agent_readiness: 54.1
    band: exemplar
    in_catalog: true
    kin_score: 67.2
    mcp: &id001
      source: https://github.com/adobe/cq-quickstart-mcp-server
      status: verified
    slug: adobe-experience-cloud
    status: profiled
    tags: &id002
    - Analytics
    - Customer Experience
    - Digital Marketing
    - Personalization
    url: /providers/adobe-experience-cloud/
  layer: common
  name: Adobe Experience Cloud
  provider: adobe-experience-cloud
  says: ships the Adobe Experience Cloud SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.tripit/latest/
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
    agent_readiness: 26.0
    band: developing
    in_catalog: true
    kin_score: 40.4
    mcp: &id003
      status: none
    slug: apptentive
    status: profiled
    tags: &id004
    - Company
    - Customer Feedback
    - Enterprise
    - Mobile
    url: /providers/apptentive/
  layer: common
  name: Apptentive (Alchemer Mobile)
  provider: apptentive
  says: ships the Apptentive (Alchemer Mobile) SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.tripit/latest/
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
    agent_readiness: 44.7
    band: exemplar
    in_catalog: true
    kin_score: 84.1
    mcp: &id005
      source: https://github.com/dynatrace-oss/dynatrace-mcp
      status: verified
    slug: dynatrace
    status: profiled
    tags: &id006
    - AI Operations
    - APM
    - Analytics
    - Application Performance Monitoring
    url: /providers/dynatrace/
  layer: common
  name: Dynatrace
  provider: dynatrace
  says: ships the Dynatrace SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.tripit/latest/
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-120.20.30
    key: AE-120.20.30
    name: Indoor & Venue Maps
    url: /capabilities/maps-tiles/
    via_parent: Maps & Tiles
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id007
      status: unchecked
    slug: locuslabs
    status: queued for profiling
    tags: &id008 []
    url: null
  layer: domain
  name: LocusLabs (Atrius) indoor airport maps
  provider: locuslabs
  says: ships the LocusLabs (Atrius) indoor airport maps SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.tripit/latest/
  tier: observed
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/travel-booking/tripit/
providers:
- agent_band: agent-ready
  agent_readiness: 54.1
  band: exemplar
  in_catalog: true
  kin_score: 67.2
  mcp: *id001
  name: Adobe Experience Cloud
  slug: adobe-experience-cloud
  status: profiled
  tags: *id002
  url: /providers/adobe-experience-cloud/
- agent_band: agent-aware
  agent_readiness: 26.0
  band: developing
  in_catalog: true
  kin_score: 40.4
  mcp: *id003
  name: Apptentive (Alchemer Mobile)
  slug: apptentive
  status: profiled
  tags: *id004
  url: /providers/apptentive/
- agent_band: agent-ready
  agent_readiness: 44.7
  band: exemplar
  in_catalog: true
  kin_score: 84.1
  mcp: *id005
  name: Dynatrace
  slug: dynatrace
  status: profiled
  tags: *id006
  url: /providers/dynatrace/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id007
  name: LocusLabs (Atrius) indoor airport maps
  slug: locuslabs
  status: queued for profiling
  tags: *id008
  url: null
siblings:
- name: AdventureLog
  rows: 14
  url: /applications/travel-booking/adventurelog/
- name: Airbnb
  rows: 4
  url: /applications/travel-booking/airbnb/
- name: Booking.com
  rows: 5
  url: /applications/travel-booking/booking-com/
- name: Expedia
  rows: 7
  url: /applications/travel-booking/expedia/
- name: TRIP
  rows: 6
  url: /applications/travel-booking/trip/
sitemap: true
title: 'TripIt: Travel Booking & Trip Planning reference app'
---
