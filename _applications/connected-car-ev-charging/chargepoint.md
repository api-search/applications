---
app: ChargePoint
app_slug: chargepoint
app_url: https://www.chargepoint.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-200.20.20
  key: AE-200.20.20
  layer: domain
  name: EV Charging
  providers:
  - EVBox
  - FLO
  url: /capabilities/connected-vehicles/
  via_parent: Connected Vehicles
- attribution: API Evangelist extension
  id: AE-902
  key: AE-902
  layer: common
  name: Mobile Attribution & Deep Linking
  providers:
  - Branch
  url: /capabilities/mobile-attribution-deep-linking/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Firebase (Crashlytics)
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Google Firebase Analytics
  - Mixpanel
  url: /capabilities/product-usage-analytics/
  via_parent: null
category:
  id: connected-car-ev-charging
  name: Connected Car & EV Charging
  url: /applications/connected-car-ev-charging/
counts:
  declared: 2
  observed: 4
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.coulombtech/latest/
- route: integrations page
  url: https://www.chargepoint.com/blog/chargepoint-extends-open-network-new-partnerships/
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
    agent_band: agent-aware
    agent_readiness: 21.9
    band: thin
    in_catalog: true
    kin_score: 33.8
    mcp: &id002
      status: none
    slug: branch-io
    status: profiled
    tags: &id003
    - Company
    url: /providers/branch-io/
  layer: common
  name: Branch
  provider: branch-io
  says: ships the Branch SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.coulombtech/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts: &id001
    agent_band: agent-ready
    agent_readiness: 39.9
    band: strong
    in_catalog: true
    kin_score: 62.0
    mcp: &id006
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: google-firebase
    status: profiled
    tags: &id007
    - Analytics
    - Authentication
    - Backend-as-a-Service
    - Cloud Messaging
    url: /providers/google-firebase/
  layer: common
  name: Firebase (Crashlytics)
  provider: firebase
  says: ships the Firebase (Crashlytics) SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.coulombtech/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts: *id001
  layer: common
  name: Google Firebase Analytics
  provider: firebase
  says: ships the Google Firebase Analytics SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.coulombtech/latest/
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
    agent_readiness: 47.7
    band: strong
    in_catalog: true
    kin_score: 60.8
    mcp: &id010
      source: https://docs.mixpanel.com/docs/features/mcp
      status: verified
    slug: mixpanel
    status: profiled
    tags: &id011
    - Analytics
    - Data Analysis
    - Event Tracking
    - Product Analytics
    url: /providers/mixpanel/
  layer: common
  name: Mixpanel
  provider: mixpanel
  says: ships the Mixpanel SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.coulombtech/latest/
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-200.20.20
    key: AE-200.20.20
    name: EV Charging
    url: /capabilities/connected-vehicles/
    via_parent: Connected Vehicles
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 18.3
    band: emerging
    in_catalog: true
    kin_score: 12.0
    mcp: &id004
      status: none
    slug: evbox
    status: profiled
    tags: &id005
    - Company
    - EV Charging
    - Hardware
    - Software
    url: /providers/evbox/
  layer: domain
  name: EVBox
  provider: evbox
  says: lists EVBox as an integration
  source: https://www.chargepoint.com/blog/chargepoint-extends-open-network-new-partnerships/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-200.20.20
    key: AE-200.20.20
    name: EV Charging
    url: /capabilities/connected-vehicles/
    via_parent: Connected Vehicles
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 19.9
    band: thin
    in_catalog: true
    kin_score: 29.8
    mcp: &id008
      status: unknown
    slug: flo-ev
    status: profiled
    tags: &id009
    - Canada
    - EV Charging
    - Electricity
    - Energy
    url: /providers/flo-ev/
  layer: domain
  name: FLO
  provider: flo-ev
  says: lists FLO as an integration
  source: https://www.chargepoint.com/blog/chargepoint-extends-open-network-new-partnerships/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/connected-car-ev-charging/chargepoint/
providers:
- agent_band: agent-aware
  agent_readiness: 21.9
  band: thin
  in_catalog: true
  kin_score: 33.8
  mcp: *id002
  name: Branch
  slug: branch-io
  status: profiled
  tags: *id003
  url: /providers/branch-io/
- agent_band: agent-aware
  agent_readiness: 18.3
  band: emerging
  in_catalog: true
  kin_score: 12.0
  mcp: *id004
  name: EVBox
  slug: evbox
  status: profiled
  tags: *id005
  url: /providers/evbox/
- agent_band: agent-ready
  agent_readiness: 39.9
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id006
  name: Firebase (Crashlytics)
  slug: google-firebase
  status: profiled
  tags: *id007
  url: /providers/google-firebase/
- agent_band: agent-aware
  agent_readiness: 19.9
  band: thin
  in_catalog: true
  kin_score: 29.8
  mcp: *id008
  name: FLO
  slug: flo-ev
  status: profiled
  tags: *id009
  url: /providers/flo-ev/
- agent_band: agent-ready
  agent_readiness: 47.7
  band: strong
  in_catalog: true
  kin_score: 60.8
  mcp: *id010
  name: Mixpanel
  slug: mixpanel
  status: profiled
  tags: *id011
  url: /providers/mixpanel/
siblings:
- name: Electrify America
  rows: 9
  url: /applications/connected-car-ev-charging/electrify-america/
- name: evcc
  rows: 71
  url: /applications/connected-car-ev-charging/evcc/
- name: Open Charge Map
  rows: 13
  url: /applications/connected-car-ev-charging/open-charge-map/
- name: openWB
  rows: 30
  url: /applications/connected-car-ev-charging/openwb/
- name: TeslaLogger
  rows: 15
  url: /applications/connected-car-ev-charging/teslalogger/
- name: TeslaMate
  rows: 3
  url: /applications/connected-car-ev-charging/teslamate/
sitemap: true
title: 'ChargePoint: Connected Car & EV Charging reference app'
---
