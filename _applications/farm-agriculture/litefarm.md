---
app: LiteFarm
app_slug: litefarm
app_url: https://github.com/LiteFarmOrg/LiteFarm
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-3500.60
  key: irrigation-operations
  layer: domain
  name: Irrigation Operations
  providers:
  - Ensemble Scientific (ESCI)
  url: /capabilities/irrigation-operations/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-921
  key: AE-921
  layer: domain
  name: Online Forms & Survey Collection
  providers:
  - SurveyStack
  url: /capabilities/customer-feedback-management/
  via_parent: Customer Feedback Management
- attribution: API Evangelist extension
  id: AE-230.10
  key: AE-230.10
  layer: domain
  name: Weather & Environment
  providers:
  - OpenWeather
  url: /capabilities/weather-environment/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-120.20.10
  key: AE-120.20.10
  layer: common
  name: Base Map Tiles
  providers:
  - Google Maps Platform
  url: /capabilities/maps-tiles/
  via_parent: Maps & Tiles
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Sentry
  url: /capabilities/observability-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-160.10.30
  key: AE-160.10.30
  layer: common
  name: Social & Federated Login
  providers:
  - Google sign-in
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
- attribution: Turbo EA
  id: BC-600.50.20
  key: BC-600.50.20
  layer: common
  name: Storage Management
  providers:
  - DigitalOcean Spaces
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: API Evangelist extension
  id: AE-150.10.10
  key: AE-150.10.10
  layer: common
  name: Transactional Email
  providers:
  - Gmail API
  url: /capabilities/email/
  via_parent: Email
category:
  id: farm-agriculture
  name: Farm & Agriculture Management
  url: /applications/farm-agriculture/
counts:
  declared: 0
  observed: 8
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/LiteFarmOrg/LiteFarm/integration/packages/api/package.json
- route: dependency manifest
  url: https://raw.githubusercontent.com/LiteFarmOrg/LiteFarm/integration/packages/webapp/package.json
- route: source code
  url: https://raw.githubusercontent.com/LiteFarmOrg/LiteFarm/integration/packages/api/.env.default
integrations:
- capability:
    attribution: Turbo EA
    id: BC-600.50.20
    key: BC-600.50.20
    name: Storage Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 44.1
    band: developing
    in_catalog: true
    kin_score: 47.4
    mcp: &id001
      source: https://docs.digitalocean.com/reference/mcp/
      status: verified
    slug: digital-ocean
    status: profiled
    tags: &id002
    - Cloud
    - Compute
    - Infrastructure
    - Servers
    url: /providers/digital-ocean/
  layer: common
  name: DigitalOcean Spaces
  provider: digital-ocean
  says: ships the DigitalOcean Spaces SDK or integration code
  source: https://raw.githubusercontent.com/LiteFarmOrg/LiteFarm/integration/packages/api/.env.default
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-3500.60
    key: irrigation-operations
    name: Irrigation Operations
    url: /capabilities/irrigation-operations/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.5
    band: emerging
    in_catalog: true
    kin_score: 14.9
    mcp: &id003
      status: none
    slug: ensemble-scientific
    status: profiled
    tags: &id004
    - Agriculture
    - IoT
    - Irrigation
    - Smart Agriculture
    url: /providers/ensemble-scientific/
  layer: domain
  name: Ensemble Scientific (ESCI)
  provider: ensemble-scientific
  says: ships the Ensemble Scientific (ESCI) SDK or integration code
  source: https://raw.githubusercontent.com/LiteFarmOrg/LiteFarm/integration/packages/api/.env.default
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.10
    key: AE-150.10.10
    name: Transactional Email
    url: /capabilities/email/
    via_parent: Email
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 43.2
    band: exemplar
    in_catalog: true
    kin_score: 66.8
    mcp: &id005
      source: https://developers.google.com/workspace/gmail/api/guides/configure-mcp-server
      status: verified
    slug: google-gmail
    status: profiled
    tags: &id006
    - Drafts
    - Email
    - Gmail
    - Google
    url: /providers/google-gmail/
  layer: common
  name: Gmail API
  provider: google-gmail
  says: ships the Gmail API SDK or integration code
  source: https://raw.githubusercontent.com/LiteFarmOrg/LiteFarm/integration/packages/api/.env.default
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-120.20.10
    key: AE-120.20.10
    name: Base Map Tiles
    url: /capabilities/maps-tiles/
    via_parent: Maps & Tiles
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.0
    band: exemplar
    in_catalog: true
    kin_score: 73.6
    mcp: &id007
      source: https://developers.google.com/maps/ai/grounding-lite
      status: verified
    slug: google-maps
    status: profiled
    tags: &id008
    - Environment
    - Geocoding
    - Geolocation
    - Maps
    url: /providers/google-maps/
  layer: common
  name: Google Maps Platform
  provider: google-maps
  says: ships the Google Maps Platform SDK or integration code
  source: https://raw.githubusercontent.com/LiteFarmOrg/LiteFarm/integration/packages/api/package.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.7
    band: strong
    in_catalog: true
    kin_score: 58.8
    mcp: &id009
      status: none
    slug: google-identity-platform
    status: profiled
    tags: &id010
    - Authentication
    - Google Cloud
    - Identity
    - Multi-Tenancy
    url: /providers/google-identity-platform/
  layer: common
  name: Google sign-in
  provider: google-identity-platform
  says: ships the Google sign-in SDK or integration code
  source: https://raw.githubusercontent.com/LiteFarmOrg/LiteFarm/integration/packages/webapp/package.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-230.10
    key: AE-230.10
    name: Weather & Environment
    url: /capabilities/weather-environment/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 30.0
    band: strong
    in_catalog: true
    kin_score: 59.1
    mcp: &id011
      source: https://mcp.openweathermap.org/
      status: verified
    slug: openweathermap
    status: profiled
    tags: &id012
    - Air Pollution
    - Climate
    - Forecast
    - Weather
    url: /providers/openweathermap/
  layer: domain
  name: OpenWeather
  provider: openweathermap
  says: ships the OpenWeather SDK or integration code
  source: https://raw.githubusercontent.com/LiteFarmOrg/LiteFarm/integration/packages/api/.env.default
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
    agent_readiness: 50.2
    band: exemplar
    in_catalog: true
    kin_score: 80.7
    mcp: &id013
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id014
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: common
  name: Sentry
  provider: sentry-system
  says: ships the Sentry SDK or integration code
  source: https://raw.githubusercontent.com/LiteFarmOrg/LiteFarm/integration/packages/api/package.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-921
    key: AE-921
    name: Online Forms & Survey Collection
    url: /capabilities/customer-feedback-management/
    via_parent: Customer Feedback Management
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.5
    band: minimal
    in_catalog: true
    kin_score: 6.9
    mcp: &id015
      status: unknown
    slug: surveystack
    status: profiled
    tags: &id016
    - Analytics
    - Community
    - Data Collection
    - SurveyStack
    url: /providers/surveystack/
  layer: domain
  name: SurveyStack
  provider: surveystack
  says: ships the SurveyStack SDK or integration code
  source: https://raw.githubusercontent.com/LiteFarmOrg/LiteFarm/integration/packages/api/.env.default
  tier: observed
kind: open-source-saas
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/farm-agriculture/litefarm/
providers:
- agent_band: agent-ready
  agent_readiness: 44.1
  band: developing
  in_catalog: true
  kin_score: 47.4
  mcp: *id001
  name: DigitalOcean Spaces
  slug: digital-ocean
  status: profiled
  tags: *id002
  url: /providers/digital-ocean/
- agent_band: human-only
  agent_readiness: 2.5
  band: emerging
  in_catalog: true
  kin_score: 14.9
  mcp: *id003
  name: Ensemble Scientific (ESCI)
  slug: ensemble-scientific
  status: profiled
  tags: *id004
  url: /providers/ensemble-scientific/
- agent_band: agent-ready
  agent_readiness: 43.2
  band: exemplar
  in_catalog: true
  kin_score: 66.8
  mcp: *id005
  name: Gmail API
  slug: google-gmail
  status: profiled
  tags: *id006
  url: /providers/google-gmail/
- agent_band: agent-ready
  agent_readiness: 33.0
  band: exemplar
  in_catalog: true
  kin_score: 73.6
  mcp: *id007
  name: Google Maps Platform
  slug: google-maps
  status: profiled
  tags: *id008
  url: /providers/google-maps/
- agent_band: agent-ready
  agent_readiness: 33.7
  band: strong
  in_catalog: true
  kin_score: 58.8
  mcp: *id009
  name: Google sign-in
  slug: google-identity-platform
  status: profiled
  tags: *id010
  url: /providers/google-identity-platform/
- agent_band: agent-ready
  agent_readiness: 30.0
  band: strong
  in_catalog: true
  kin_score: 59.1
  mcp: *id011
  name: OpenWeather
  slug: openweathermap
  status: profiled
  tags: *id012
  url: /providers/openweathermap/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.7
  mcp: *id013
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id014
  url: /providers/sentry-system/
- agent_band: human-only
  agent_readiness: 2.5
  band: minimal
  in_catalog: true
  kin_score: 6.9
  mcp: *id015
  name: SurveyStack
  slug: surveystack
  status: profiled
  tags: *id016
  url: /providers/surveystack/
siblings:
- name: AgriWebb
  rows: 11
  url: /applications/farm-agriculture/agriwebb/
- name: Agworld
  rows: 17
  url: /applications/farm-agriculture/agworld/
- name: Climate FieldView
  rows: 20
  url: /applications/farm-agriculture/climate-fieldview/
- name: Farmbrite
  rows: 13
  url: /applications/farm-agriculture/farmbrite/
- name: farmOS
  rows: 1
  url: /applications/farm-agriculture/farmos/
- name: Open Food Network
  rows: 7
  url: /applications/farm-agriculture/open-food-network/
sitemap: true
title: 'LiteFarm: Farm & Agriculture Management reference app'
---
