---
app: WeeWX
app_slug: weewx
app_url: https://github.com/weewx/weewx
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-230.10.10
  key: AE-230.10.10
  layer: domain
  name: Personal Weather Station Networks
  providers:
  - AWEKAS
  - Citizen Weather Observer Program
  - Met Office WOW
  - PWSweather
  - RMI Belgium WOW-BE
  - Weather Underground
  url: /capabilities/weather-environment/
  via_parent: Weather & Environment
category:
  id: weather
  name: Weather & Environmental Alerts
  url: /applications/weather/
counts:
  declared: 0
  observed: 6
credits: []
evidence:
- route: source code
  url: https://github.com/weewx/weewx/blob/master/src/weewx/restx.py
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-230.10.10
    key: AE-230.10.10
    name: Personal Weather Station Networks
    url: /capabilities/weather-environment/
    via_parent: Weather & Environment
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 17.2
    mcp: &id001
      status: none
    slug: awekas
    status: profiled
    tags: &id002
    - Private Weather Stations
    - Weather App
    - Weather Data
    - Weather Map
    url: /providers/awekas/
  layer: domain
  name: AWEKAS
  provider: awekas
  says: ships the AWEKAS SDK or integration code
  source: https://github.com/weewx/weewx/blob/master/src/weewx/restx.py
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-230.10.10
    key: AE-230.10.10
    name: Personal Weather Station Networks
    url: /capabilities/weather-environment/
    via_parent: Weather & Environment
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 4.6
    mcp: &id003
      status: unknown
    slug: cwop
    status: profiled
    tags: &id004
    - Citizen Science
    - Data Collection
    - PublicPrivatePartnership
    - Weather
    url: /providers/cwop/
  layer: domain
  name: Citizen Weather Observer Program
  provider: cwop
  says: ships the Citizen Weather Observer Program SDK or integration code
  source: https://github.com/weewx/weewx/blob/master/src/weewx/restx.py
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-230.10.10
    key: AE-230.10.10
    name: Personal Weather Station Networks
    url: /capabilities/weather-environment/
    via_parent: Weather & Environment
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.4
    band: strong
    in_catalog: true
    kin_score: 64.3
    mcp: &id005
      status: none
    slug: met-office
    status: profiled
    tags: &id006
    - Climate
    - Company
    - Forecast
    - Weather
    url: /providers/met-office/
  layer: domain
  name: Met Office WOW
  provider: met-office
  says: ships the Met Office WOW SDK or integration code
  source: https://github.com/weewx/weewx/blob/master/src/weewx/restx.py
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-230.10.10
    key: AE-230.10.10
    name: Personal Weather Station Networks
    url: /capabilities/weather-environment/
    via_parent: Weather & Environment
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.5
    band: emerging
    in_catalog: true
    kin_score: 13.3
    mcp: &id007
      status: unknown
    slug: pwsweather
    status: profiled
    tags: &id008
    - Company
    - Data
    - Visualization
    - Weather
    url: /providers/pwsweather/
  layer: domain
  name: PWSweather
  provider: pwsweather
  says: ships the PWSweather SDK or integration code
  source: https://github.com/weewx/weewx/blob/master/src/weewx/restx.py
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-230.10.10
    key: AE-230.10.10
    name: Personal Weather Station Networks
    url: /capabilities/weather-environment/
    via_parent: Weather & Environment
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.5
    band: emerging
    in_catalog: true
    kin_score: 12.4
    mcp: &id009
      status: unknown
    slug: royal-meteorological-institute-belgium
    status: profiled
    tags: &id010
    - Belgium
    - Climate
    - Meteorology
    - Weather
    url: /providers/royal-meteorological-institute-belgium/
  layer: domain
  name: RMI Belgium WOW-BE
  provider: royal-meteorological-institute-belgium
  says: ships the RMI Belgium WOW-BE SDK or integration code
  source: https://github.com/weewx/weewx/blob/master/src/weewx/restx.py
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-230.10.10
    key: AE-230.10.10
    name: Personal Weather Station Networks
    url: /capabilities/weather-environment/
    via_parent: Weather & Environment
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.3
    band: thin
    in_catalog: true
    kin_score: 34.9
    mcp: &id011
      status: none
    slug: wunderground
    status: profiled
    tags: &id012
    - Hyperlocal
    - Observations
    - Personal Weather Stations
    - Weather
    url: /providers/wunderground/
  layer: domain
  name: Weather Underground
  provider: wunderground
  says: ships the Weather Underground SDK or integration code
  source: https://github.com/weewx/weewx/blob/master/src/weewx/restx.py
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/weather/weewx/
providers:
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 17.2
  mcp: *id001
  name: AWEKAS
  slug: awekas
  status: profiled
  tags: *id002
  url: /providers/awekas/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 4.6
  mcp: *id003
  name: Citizen Weather Observer Program
  slug: cwop
  status: profiled
  tags: *id004
  url: /providers/cwop/
- agent_band: agent-ready
  agent_readiness: 33.4
  band: strong
  in_catalog: true
  kin_score: 64.3
  mcp: *id005
  name: Met Office WOW
  slug: met-office
  status: profiled
  tags: *id006
  url: /providers/met-office/
- agent_band: human-only
  agent_readiness: 2.5
  band: emerging
  in_catalog: true
  kin_score: 13.3
  mcp: *id007
  name: PWSweather
  slug: pwsweather
  status: profiled
  tags: *id008
  url: /providers/pwsweather/
- agent_band: human-only
  agent_readiness: 2.5
  band: emerging
  in_catalog: true
  kin_score: 12.4
  mcp: *id009
  name: RMI Belgium WOW-BE
  slug: royal-meteorological-institute-belgium
  status: profiled
  tags: *id010
  url: /providers/royal-meteorological-institute-belgium/
- agent_band: agent-ready
  agent_readiness: 31.3
  band: thin
  in_catalog: true
  kin_score: 34.9
  mcp: *id011
  name: Weather Underground
  slug: wunderground
  status: profiled
  tags: *id012
  url: /providers/wunderground/
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
- name: Windy
  rows: 6
  url: /applications/weather/windy/
- name: wttr.in
  rows: 5
  url: /applications/weather/wttr-in/
sitemap: true
title: 'WeeWX: Weather & Environmental Alerts reference app'
---
