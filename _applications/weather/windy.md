---
app: Windy
app_slug: windy
app_url: https://www.windy.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-230.10
  key: AE-230.10
  layer: domain
  name: Weather & Environment
  providers:
  - DWD (ICON-EU)
  - ECMWF
  - Meteoblue (NEMS)
  - NOAA (GFS)
  url: /capabilities/weather-environment/
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
- attribution: API Evangelist extension
  id: AE-160.10.30
  key: AE-160.10.30
  layer: common
  name: Social & Federated Login
  providers:
  - Facebook Analytics / Login / Share
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
category:
  id: weather
  name: Weather & Environmental Alerts
  url: /applications/weather/
counts:
  declared: 4
  observed: 2
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.windyty.android/latest/
- route: documentation
  url: https://community.windy.com/topic/12/what-source-of-weather-data-windy-use
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
  source: https://reports.exodus-privacy.eu.org/en/reports/com.windyty.android/latest/
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-aware
    agent_readiness: 28.2
    band: developing
    in_catalog: true
    kin_score: 42.7
    mcp: &id007
      status: none
    slug: facebook
    status: profiled
    tags: &id008
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
  layer: common
  name: Facebook Analytics / Login / Share
  provider: facebook
  says: ships the Facebook Analytics / Login / Share SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.windyty.android/latest/
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
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 3.4
    mcp: &id003
      status: none
    slug: deutscher-wetterdienst
    status: profiled
    tags: &id004
    - Geospatial
    - OGC
    - WFS
    - WMS
    url: /providers/deutscher-wetterdienst/
  layer: domain
  name: DWD (ICON-EU)
  provider: deutscher-wetterdienst
  says: lists DWD (ICON-EU) as an integration
  source: https://community.windy.com/topic/12/what-source-of-weather-data-windy-use
  tier: declared
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
    agent_readiness: 38.5
    band: developing
    in_catalog: true
    kin_score: 42.7
    mcp: &id005
      status: none
    slug: ecmwf
    status: profiled
    tags: &id006
    - Company
    - Forecasting
    - Meteorology
    - Weather
    url: /providers/ecmwf/
  layer: domain
  name: ECMWF
  provider: ecmwf
  says: lists ECMWF as an integration
  source: https://community.windy.com/topic/12/what-source-of-weather-data-windy-use
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-230.10
    key: AE-230.10
    name: Weather & Environment
    url: /capabilities/weather-environment/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 15.6
    band: emerging
    in_catalog: true
    kin_score: 19.5
    mcp: &id009
      status: none
    slug: meteoblue
    status: profiled
    tags: &id010
    - Climate
    - Data
    - Forecast
    - Weather
    url: /providers/meteoblue/
  layer: domain
  name: Meteoblue (NEMS)
  provider: meteoblue
  says: lists Meteoblue (NEMS) as an integration
  source: https://community.windy.com/topic/12/what-source-of-weather-data-windy-use
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-230.10
    key: AE-230.10
    name: Weather & Environment
    url: /capabilities/weather-environment/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 26.6
    band: developing
    in_catalog: true
    kin_score: 40.5
    mcp: &id011
      status: unknown
    slug: noaa-gov
    status: profiled
    tags: &id012
    - Climate
    - Ocean
    - Space Weather
    - Weather
    url: /providers/noaa-gov/
  layer: domain
  name: NOAA (GFS)
  provider: noaa-gov
  says: lists NOAA (GFS) as an integration
  source: https://community.windy.com/topic/12/what-source-of-weather-data-windy-use
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/weather/windy/
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
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 3.4
  mcp: *id003
  name: DWD (ICON-EU)
  slug: deutscher-wetterdienst
  status: profiled
  tags: *id004
  url: /providers/deutscher-wetterdienst/
- agent_band: agent-ready
  agent_readiness: 38.5
  band: developing
  in_catalog: true
  kin_score: 42.7
  mcp: *id005
  name: ECMWF
  slug: ecmwf
  status: profiled
  tags: *id006
  url: /providers/ecmwf/
- agent_band: agent-aware
  agent_readiness: 28.2
  band: developing
  in_catalog: true
  kin_score: 42.7
  mcp: *id007
  name: Facebook Analytics / Login / Share
  slug: facebook
  status: profiled
  tags: *id008
  url: /providers/facebook/
- agent_band: agent-aware
  agent_readiness: 15.6
  band: emerging
  in_catalog: true
  kin_score: 19.5
  mcp: *id009
  name: Meteoblue (NEMS)
  slug: meteoblue
  status: profiled
  tags: *id010
  url: /providers/meteoblue/
- agent_band: agent-aware
  agent_readiness: 26.6
  band: developing
  in_catalog: true
  kin_score: 40.5
  mcp: *id011
  name: NOAA (GFS)
  slug: noaa-gov
  status: profiled
  tags: *id012
  url: /providers/noaa-gov/
siblings:
- name: AccuWeather
  rows: 3
  url: /applications/weather/accuweather/
- name: Breezy Weather
  rows: 51
  url: /applications/weather/breezy-weather/
- name: Carrot Weather
  rows: 3
  url: /applications/weather/carrot-weather/
- name: MagicMirror2 weather module
  rows: 13
  url: /applications/weather/magicmirror2-weather-module/
- name: WeeWX
  rows: 6
  url: /applications/weather/weewx/
- name: wttr.in
  rows: 5
  url: /applications/weather/wttr-in/
sitemap: true
title: 'Windy: Weather & Environmental Alerts reference app'
---
