---
app: Carrot Weather
app_slug: carrot-weather
app_url: https://www.meetcarrot.com/weather/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-230.10
  key: AE-230.10
  layer: domain
  name: Weather & Environment
  providers:
  - AccuWeather
  - Apple Weather (WeatherKit)
  - Foreca
  url: /capabilities/weather-environment/
  via_parent: null
category:
  id: weather
  name: Weather & Environmental Alerts
  url: /applications/weather/
counts:
  declared: 3
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.meetcarrot.com/weather/
integrations:
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
    agent_readiness: 25.5
    band: developing
    in_catalog: true
    kin_score: 42.6
    mcp: &id001
      status: none
    slug: accuweather
    status: profiled
    tags: &id002
    - Forecast
    - Location Services
    - Meteorology
    - Weather
    url: /providers/accuweather/
  layer: domain
  name: AccuWeather
  provider: accuweather
  says: lists AccuWeather as an integration
  source: https://www.meetcarrot.com/weather/
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
    agent_readiness: 31.9
    band: strong
    in_catalog: true
    kin_score: 55.2
    mcp: &id003
      status: none
    slug: apple
    status: profiled
    tags: &id004
    - Apple
    - Developers
    - iOS
    - macOS
    url: /providers/apple/
  layer: domain
  name: Apple Weather (WeatherKit)
  provider: apple
  says: lists Apple Weather (WeatherKit) as an integration
  source: https://www.meetcarrot.com/weather/
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
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 5.6
    mcp: &id005
      status: unknown
    slug: foreca
    status: profiled
    tags: &id006
    - Public APIs
    - Weather
    url: /providers/foreca/
  layer: domain
  name: Foreca
  provider: foreca
  says: lists Foreca as an integration
  source: https://www.meetcarrot.com/weather/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/weather/carrot-weather/
providers:
- agent_band: agent-aware
  agent_readiness: 25.5
  band: developing
  in_catalog: true
  kin_score: 42.6
  mcp: *id001
  name: AccuWeather
  slug: accuweather
  status: profiled
  tags: *id002
  url: /providers/accuweather/
- agent_band: agent-ready
  agent_readiness: 31.9
  band: strong
  in_catalog: true
  kin_score: 55.2
  mcp: *id003
  name: Apple Weather (WeatherKit)
  slug: apple
  status: profiled
  tags: *id004
  url: /providers/apple/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 5.6
  mcp: *id005
  name: Foreca
  slug: foreca
  status: profiled
  tags: *id006
  url: /providers/foreca/
siblings:
- name: AccuWeather
  rows: 3
  url: /applications/weather/accuweather/
- name: Breezy Weather
  rows: 51
  url: /applications/weather/breezy-weather/
- name: MagicMirror2 weather module
  rows: 13
  url: /applications/weather/magicmirror2-weather-module/
- name: WeeWX
  rows: 6
  url: /applications/weather/weewx/
- name: Windy
  rows: 6
  url: /applications/weather/windy/
- name: wttr.in
  rows: 5
  url: /applications/weather/wttr-in/
sitemap: true
title: 'Carrot Weather: Weather & Environmental Alerts reference app'
---
