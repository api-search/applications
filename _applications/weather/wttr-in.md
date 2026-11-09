---
app: wttr.in
app_slug: wttr-in
app_url: https://github.com/chubin/wttr.in
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-230.10
  key: AE-230.10
  layer: domain
  name: Weather & Environment
  providers:
  - World Weather Online
  url: /capabilities/weather-environment/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-120.10.10
  key: AE-120.10.10
  layer: common
  name: Forward Geocoding
  providers:
  - LocationIQ
  - Nominatim
  - OpenCage
  url: /capabilities/geocoding/
  via_parent: Geocoding
- attribution: API Evangelist extension
  id: AE-120.50.10
  key: AE-120.50.10
  layer: common
  name: IP Geolocation
  providers:
  - MaxMind GeoLite2
  url: /capabilities/device-ip-location/
  via_parent: Device & IP Location
category:
  id: weather
  name: Weather & Environmental Alerts
  url: /applications/weather/
counts:
  declared: 0
  observed: 5
credits: []
evidence:
- route: documentation
  url: https://github.com/chubin/wttr.in/blob/master/README.md
- route: source code
  url: https://github.com/chubin/wttr.in/tree/master/internal
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-120.10.10
    key: AE-120.10.10
    name: Forward Geocoding
    url: /capabilities/geocoding/
    via_parent: Geocoding
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 5.6
    mcp: &id001
      status: none
    slug: locationiq
    status: profiled
    tags: &id002
    - Geocoding
    - Geospatial
    - Public APIs
    url: /providers/locationiq/
  layer: common
  name: LocationIQ
  provider: locationiq
  says: ships the LocationIQ SDK or integration code
  source: https://github.com/chubin/wttr.in/tree/master/internal/location
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-120.50.10
    key: AE-120.50.10
    name: IP Geolocation
    url: /capabilities/device-ip-location/
    via_parent: Device & IP Location
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 17.9
    band: thin
    in_catalog: true
    kin_score: 33.3
    mcp: &id003
      status: none
    slug: maxmind
    status: profiled
    tags: &id004
    - Fraud Prevention
    - Geolocation
    - IP Intelligence
    - Risk Scoring
    url: /providers/maxmind/
  layer: common
  name: MaxMind GeoLite2
  provider: maxmind
  says: ships the MaxMind GeoLite2 SDK or integration code
  source: https://github.com/chubin/wttr.in/tree/master/internal/ip
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-120.10.10
    key: AE-120.10.10
    name: Forward Geocoding
    url: /capabilities/geocoding/
    via_parent: Geocoding
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 19.9
    band: developing
    in_catalog: true
    kin_score: 42.4
    mcp: &id005
      status: none
    slug: nominatim
    status: profiled
    tags: &id006
    - Geocoding
    - Location Services
    - Maps
    - OpenStreetMap
    url: /providers/nominatim/
  layer: common
  name: Nominatim
  provider: nominatim
  says: ships the Nominatim SDK or integration code
  source: https://github.com/chubin/wttr.in/tree/master/internal/location
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-120.10.10
    key: AE-120.10.10
    name: Forward Geocoding
    url: /capabilities/geocoding/
    via_parent: Geocoding
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 7.9
    mcp: &id007
      source: https://github.com/OpenCageData/opencage-geocoding-mcp
      status: verified
    slug: opencage
    status: profiled
    tags: &id008
    - Geocoding
    - Geospatial
    - Public APIs
    url: /providers/opencage/
  layer: common
  name: OpenCage
  provider: opencage
  says: ships the OpenCage SDK or integration code
  source: https://github.com/chubin/wttr.in/tree/master/internal/location
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
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id009
      status: unchecked
    slug: worldweatheronline
    status: queued for profiling
    tags: &id010 []
    url: null
  layer: domain
  name: World Weather Online
  provider: worldweatheronline
  says: ships the World Weather Online SDK or integration code
  source: https://github.com/chubin/wttr.in/tree/master/internal/weather
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/weather/wttr-in/
providers:
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 5.6
  mcp: *id001
  name: LocationIQ
  slug: locationiq
  status: profiled
  tags: *id002
  url: /providers/locationiq/
- agent_band: agent-aware
  agent_readiness: 17.9
  band: thin
  in_catalog: true
  kin_score: 33.3
  mcp: *id003
  name: MaxMind GeoLite2
  slug: maxmind
  status: profiled
  tags: *id004
  url: /providers/maxmind/
- agent_band: agent-aware
  agent_readiness: 19.9
  band: developing
  in_catalog: true
  kin_score: 42.4
  mcp: *id005
  name: Nominatim
  slug: nominatim
  status: profiled
  tags: *id006
  url: /providers/nominatim/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 7.9
  mcp: *id007
  name: OpenCage
  slug: opencage
  status: profiled
  tags: *id008
  url: /providers/opencage/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id009
  name: World Weather Online
  slug: worldweatheronline
  status: queued for profiling
  tags: *id010
  url: null
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
- name: Windy
  rows: 6
  url: /applications/weather/windy/
sitemap: true
title: 'wttr.in: Weather & Environmental Alerts reference app'
---
