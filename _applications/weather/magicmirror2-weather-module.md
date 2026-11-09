---
app: MagicMirror2 weather module
app_slug: magicmirror2-weather-module
app_url: https://github.com/MagicMirrorOrg/MagicMirror
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-230.10
  key: AE-230.10
  layer: domain
  name: Weather & Environment
  providers:
  - Buienradar
  - Environment Canada
  - FMI
  - Open-Meteo
  - OpenWeatherMap
  - Pirate Weather
  - SMHI
  - UK Met Office DataHub
  - weather.gov (NWS)
  - WeatherAPI.com
  - Weatherbit
  - WeatherFlow (Tempest)
  - yr.no (MET Norway)
  url: /capabilities/weather-environment/
  via_parent: null
category:
  id: weather
  name: Weather & Environmental Alerts
  url: /applications/weather/
counts:
  declared: 0
  observed: 13
credits: []
evidence:
- route: source code
  url: https://github.com/MagicMirrorOrg/MagicMirror/tree/master/defaultmodules/weather/providers
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
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 4.5
    mcp: &id001
      status: unknown
    slug: buienradar
    status: profiled
    tags: &id002
    - Company
    - Forecast
    - Radar
    - Weather
    url: /providers/buienradar/
  layer: domain
  name: Buienradar
  provider: buienradar
  says: ships the Buienradar SDK or integration code
  source: https://github.com/MagicMirrorOrg/MagicMirror/tree/master/defaultmodules/weather/providers
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
    kin_score: 5.3
    mcp: &id003
      status: none
    slug: environment-and-climate-change-canada
    status: profiled
    tags: &id004
    - GIS
    - Geospatial
    - OGC
    - WMS
    url: /providers/environment-and-climate-change-canada/
  layer: domain
  name: Environment Canada
  provider: environment-and-climate-change-canada
  says: ships the Environment Canada SDK or integration code
  source: https://github.com/MagicMirrorOrg/MagicMirror/tree/master/defaultmodules/weather/providers
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
    kin_score: 6.2
    mcp: &id005
      status: none
    slug: finnish-meteorological-institute
    status: profiled
    tags: &id006
    - Climate
    - Company
    - Data
    - Weather
    url: /providers/finnish-meteorological-institute/
  layer: domain
  name: FMI
  provider: finnish-meteorological-institute
  says: ships the FMI SDK or integration code
  source: https://github.com/MagicMirrorOrg/MagicMirror/tree/master/defaultmodules/weather/providers
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
    agent_band: agent-aware
    agent_readiness: 17.8
    band: thin
    in_catalog: true
    kin_score: 29.6
    mcp: &id007
      status: none
    slug: open-meteo
    status: profiled
    tags: &id008
    - Air Quality
    - Forecast
    - Historical Weather
    - Weather
    url: /providers/open-meteo/
  layer: domain
  name: Open-Meteo
  provider: open-meteo
  says: ships the Open-Meteo SDK or integration code
  source: https://github.com/MagicMirrorOrg/MagicMirror/tree/master/defaultmodules/weather/providers
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
    agent_band: agent-aware
    agent_readiness: 22.5
    band: strong
    in_catalog: true
    kin_score: 60.4
    mcp: &id009
      source: https://mcp.openweathermap.org/
      status: verified
    slug: openweathermap
    status: profiled
    tags: &id010
    - Air Pollution
    - Climate
    - Forecast
    - Weather
    url: /providers/openweathermap/
  layer: domain
  name: OpenWeatherMap
  provider: openweathermap
  says: ships the OpenWeatherMap SDK or integration code
  source: https://github.com/MagicMirrorOrg/MagicMirror/tree/master/defaultmodules/weather/providers
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
    kin_score: 3.3
    mcp: &id011
      source: https://pirateweather.net/
      status: documented
    slug: pirate-weather
    status: profiled
    tags: &id012
    - Public APIs
    - Weather
    url: /providers/pirate-weather/
  layer: domain
  name: Pirate Weather
  provider: pirate-weather
  says: ships the Pirate Weather SDK or integration code
  source: https://github.com/MagicMirrorOrg/MagicMirror/tree/master/defaultmodules/weather/providers
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
    kin_score: 9.4
    mcp: &id013
      status: none
    slug: smhi
    status: profiled
    tags: &id014
    - Climate
    - Data
    - Research
    - Weather
    url: /providers/smhi/
  layer: domain
  name: SMHI
  provider: smhi
  says: ships the SMHI SDK or integration code
  source: https://github.com/MagicMirrorOrg/MagicMirror/tree/master/defaultmodules/weather/providers
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
    agent_readiness: 34.2
    band: developing
    in_catalog: true
    kin_score: 52.9
    mcp: &id015
      status: none
    slug: met-office
    status: profiled
    tags: &id016
    - Climate
    - Company
    - Forecast
    - Weather
    url: /providers/met-office/
  layer: domain
  name: UK Met Office DataHub
  provider: met-office
  says: ships the UK Met Office DataHub SDK or integration code
  source: https://github.com/MagicMirrorOrg/MagicMirror/tree/master/defaultmodules/weather/providers
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
    agent_band: agent-aware
    agent_readiness: 23.3
    band: thin
    in_catalog: true
    kin_score: 36.6
    mcp: &id017
      status: none
    slug: weather-gov
    status: profiled
    tags: &id018
    - Forecasting
    - Government
    - United States
    - Weather
    url: /providers/weather-gov/
  layer: domain
  name: weather.gov (NWS)
  provider: weather-gov
  says: ships the weather.gov (NWS) SDK or integration code
  source: https://github.com/MagicMirrorOrg/MagicMirror/tree/master/defaultmodules/weather/providers
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
    agent_band: agent-aware
    agent_readiness: 23.7
    band: strong
    in_catalog: true
    kin_score: 55.6
    mcp: &id019
      status: unknown
    slug: weatherapi
    status: profiled
    tags: &id020
    - Forecast
    - History
    - Marine
    - Weather
    url: /providers/weatherapi/
  layer: domain
  name: WeatherAPI.com
  provider: weatherapi
  says: ships the WeatherAPI.com SDK or integration code
  source: https://github.com/MagicMirrorOrg/MagicMirror/tree/master/defaultmodules/weather/providers
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
    agent_band: agent-aware
    agent_readiness: 22.7
    band: thin
    in_catalog: true
    kin_score: 39.1
    mcp: &id021
      status: none
    slug: weatherbit
    status: profiled
    tags: &id022
    - Air Quality
    - Forecasting
    - Historical Data
    - Weather
    url: /providers/weatherbit/
  layer: domain
  name: Weatherbit
  provider: weatherbit
  says: ships the Weatherbit SDK or integration code
  source: https://github.com/MagicMirrorOrg/MagicMirror/tree/master/defaultmodules/weather/providers
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
    kin_score: 3.5
    mcp: &id023
      status: none
    slug: weatherflow
    status: profiled
    tags: &id024
    - Company
    - IoT
    - Real-Time
    - Weather
    url: /providers/weatherflow/
  layer: domain
  name: WeatherFlow (Tempest)
  provider: weatherflow
  says: ships the WeatherFlow (Tempest) SDK or integration code
  source: https://github.com/MagicMirrorOrg/MagicMirror/tree/master/defaultmodules/weather/providers
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
    kin_score: 7.4
    mcp: &id025
      status: none
    slug: meteorologisk-institutt
    status: profiled
    tags: &id026
    - Public APIs
    - Weather
    url: /providers/meteorologisk-institutt/
  layer: domain
  name: yr.no (MET Norway)
  provider: meteorologisk-institutt
  says: ships the yr.no (MET Norway) SDK or integration code
  source: https://github.com/MagicMirrorOrg/MagicMirror/tree/master/defaultmodules/weather/providers
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/weather/magicmirror2-weather-module/
providers:
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 4.5
  mcp: *id001
  name: Buienradar
  slug: buienradar
  status: profiled
  tags: *id002
  url: /providers/buienradar/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 5.3
  mcp: *id003
  name: Environment Canada
  slug: environment-and-climate-change-canada
  status: profiled
  tags: *id004
  url: /providers/environment-and-climate-change-canada/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 6.2
  mcp: *id005
  name: FMI
  slug: finnish-meteorological-institute
  status: profiled
  tags: *id006
  url: /providers/finnish-meteorological-institute/
- agent_band: agent-aware
  agent_readiness: 17.8
  band: thin
  in_catalog: true
  kin_score: 29.6
  mcp: *id007
  name: Open-Meteo
  slug: open-meteo
  status: profiled
  tags: *id008
  url: /providers/open-meteo/
- agent_band: agent-aware
  agent_readiness: 22.5
  band: strong
  in_catalog: true
  kin_score: 60.4
  mcp: *id009
  name: OpenWeatherMap
  slug: openweathermap
  status: profiled
  tags: *id010
  url: /providers/openweathermap/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 3.3
  mcp: *id011
  name: Pirate Weather
  slug: pirate-weather
  status: profiled
  tags: *id012
  url: /providers/pirate-weather/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 9.4
  mcp: *id013
  name: SMHI
  slug: smhi
  status: profiled
  tags: *id014
  url: /providers/smhi/
- agent_band: agent-ready
  agent_readiness: 34.2
  band: developing
  in_catalog: true
  kin_score: 52.9
  mcp: *id015
  name: UK Met Office DataHub
  slug: met-office
  status: profiled
  tags: *id016
  url: /providers/met-office/
- agent_band: agent-aware
  agent_readiness: 23.3
  band: thin
  in_catalog: true
  kin_score: 36.6
  mcp: *id017
  name: weather.gov (NWS)
  slug: weather-gov
  status: profiled
  tags: *id018
  url: /providers/weather-gov/
- agent_band: agent-aware
  agent_readiness: 23.7
  band: strong
  in_catalog: true
  kin_score: 55.6
  mcp: *id019
  name: WeatherAPI.com
  slug: weatherapi
  status: profiled
  tags: *id020
  url: /providers/weatherapi/
- agent_band: agent-aware
  agent_readiness: 22.7
  band: thin
  in_catalog: true
  kin_score: 39.1
  mcp: *id021
  name: Weatherbit
  slug: weatherbit
  status: profiled
  tags: *id022
  url: /providers/weatherbit/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 3.5
  mcp: *id023
  name: WeatherFlow (Tempest)
  slug: weatherflow
  status: profiled
  tags: *id024
  url: /providers/weatherflow/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 7.4
  mcp: *id025
  name: yr.no (MET Norway)
  slug: meteorologisk-institutt
  status: profiled
  tags: *id026
  url: /providers/meteorologisk-institutt/
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
title: 'MagicMirror2 weather module: Weather & Environmental Alerts reference app'
---
