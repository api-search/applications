---
app: PVOutput
app_slug: pvoutput
app_url: https://pvoutput.org/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-200.30
  key: home-energy
  layer: domain
  name: Home Energy
  providers:
  - Current Cost
  - Efergy
  - EKM Metering
  - Energomonitor
  - Enphase Enlighten
  - Flukso
  - Fronius
  - Growatt ShineNET
  - KACO
  - Rainforest Automation (Eagle)
  - SMA Webbox
  - Smappee
  - Solar-Log
  - SolarEdge
  - TED (The Energy Detective)
  - Tesla Powerwall
  - Trannergy
  - Wattvision
  - Zevercloud (Zeversolar)
  url: /capabilities/home-energy/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-230.10
  key: weather-environment
  layer: domain
  name: Weather & Environment
  providers:
  - Ambient Weather
  - OpenWeatherMap
  - Weather Underground
  url: /capabilities/weather-environment/
  via_parent: null
category:
  id: solar-energy-monitoring
  name: Home Energy & Solar Monitoring
  url: /applications/solar-energy-monitoring/
counts:
  declared: 22
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://pvoutput.org/help/auto_uploader.html
- route: integrations page
  url: https://pvoutput.org/help/push_services.html
- route: integrations page
  url: https://pvoutput.org/help/service_integration.html
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-230.10
    key: weather-environment
    name: Weather & Environment
    url: /capabilities/weather-environment/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: minimal
    in_catalog: true
    kin_score: 3.2
    mcp: &id001
      status: unchecked
    slug: ambient-weather
    status: profiled
    tags: &id002
    - Company
    - Dashboards
    - IoT
    - Weather
    url: /providers/ambient-weather/
  layer: domain
  name: Ambient Weather
  provider: ambient-weather
  says: lists Ambient Weather as an integration
  source: https://pvoutput.org/help/auto_uploader.html
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-200.30
    key: home-energy
    name: Home Energy
    url: /capabilities/home-energy/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: minimal
    in_catalog: true
    kin_score: 7.5
    mcp: &id003
      status: unchecked
    slug: current-cost
    status: profiled
    tags: &id004
    - Company
    - Energy
    - IoT
    - Smart Home
    url: /providers/current-cost/
  layer: domain
  name: Current Cost
  provider: current-cost
  says: lists Current Cost as an integration
  source: https://pvoutput.org/help/service_integration.html
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-200.30
    key: home-energy
    name: Home Energy
    url: /capabilities/home-energy/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 0.4
    mcp: &id005
      status: unchecked
    slug: efergy
    status: profiled
    tags: &id006
    - Company
    url: /providers/efergy/
  layer: domain
  name: Efergy
  provider: efergy
  says: lists Efergy as an integration
  source: https://pvoutput.org/help/auto_uploader.html
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-200.30
    key: home-energy
    name: Home Energy
    url: /capabilities/home-energy/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 6.9
    band: thin
    in_catalog: true
    kin_score: 27.7
    mcp: &id007
      status: unchecked
    slug: ekm-metering
    status: profiled
    tags: &id008
    - Company
    - Energy
    - IoT
    - Submetering
    url: /providers/ekm-metering/
  layer: domain
  name: EKM Metering
  provider: ekm-metering
  says: lists EKM Metering as an integration
  source: https://pvoutput.org/help/auto_uploader.html
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-200.30
    key: home-energy
    name: Home Energy
    url: /capabilities/home-energy/
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
    slug: energomonitor
    status: queued for profiling
    tags: &id010 []
    url: null
  layer: domain
  name: Energomonitor
  provider: energomonitor
  says: lists Energomonitor as an integration
  source: https://pvoutput.org/help/auto_uploader.html
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-200.30
    key: home-energy
    name: Home Energy
    url: /capabilities/home-energy/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 35.2
    band: exemplar
    in_catalog: true
    kin_score: 68.6
    mcp: &id011
      status: none
    slug: enphase
    status: profiled
    tags: &id012
    - DER
    - Energy
    - Solar
    - United States
    url: /providers/enphase/
  layer: domain
  name: Enphase Enlighten
  provider: enphase
  says: lists Enphase Enlighten as an integration
  source: https://pvoutput.org/help/auto_uploader.html
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-200.30
    key: home-energy
    name: Home Energy
    url: /capabilities/home-energy/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: minimal
    in_catalog: true
    kin_score: 10.8
    mcp: &id013
      status: unchecked
    slug: flukso
    status: profiled
    tags: &id014
    - Company
    - IoT
    - Monitoring
    - Utilities
    url: /providers/flukso/
  layer: domain
  name: Flukso
  provider: flukso
  says: lists Flukso as an integration
  source: https://pvoutput.org/help/auto_uploader.html
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-200.30
    key: home-energy
    name: Home Energy
    url: /capabilities/home-energy/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 12.3
    mcp: &id015
      status: none
    slug: fronius
    status: profiled
    tags: &id016
    - Company
    - Energy
    - Solar
    - Welding
    url: /providers/fronius/
  layer: domain
  name: Fronius
  provider: fronius
  says: lists Fronius as an integration
  source: https://pvoutput.org/help/push_services.html
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-200.30
    key: home-energy
    name: Home Energy
    url: /capabilities/home-energy/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.5
    band: emerging
    in_catalog: true
    kin_score: 11.5
    mcp: &id017
      status: unknown
    slug: growatt
    status: profiled
    tags: &id018
    - Company
    - Consumer Technology
    - Energy
    - Solar
    url: /providers/growatt/
  layer: domain
  name: Growatt ShineNET
  provider: growatt
  says: lists Growatt ShineNET as an integration
  source: https://pvoutput.org/help/service_integration.html
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-200.30
    key: home-energy
    name: Home Energy
    url: /capabilities/home-energy/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 6.9
    mcp: &id019
      status: unchecked
    slug: kaco-new-energy
    status: profiled
    tags: &id020
    - Company
    - Energy Storage
    - Inverters
    - Solar
    url: /providers/kaco-new-energy/
  layer: domain
  name: KACO
  provider: kaco-new-energy
  says: lists KACO as an integration
  source: https://pvoutput.org/help/service_integration.html
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-230.10
    key: weather-environment
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
    mcp: &id021
      source: https://mcp.openweathermap.org/
      status: verified
    slug: openweathermap
    status: profiled
    tags: &id022
    - Air Pollution
    - Climate
    - Forecast
    - Weather
    url: /providers/openweathermap/
  layer: domain
  name: OpenWeatherMap
  provider: openweathermap
  says: lists OpenWeatherMap as an integration
  source: https://pvoutput.org/help/auto_uploader.html
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-200.30
    key: home-energy
    name: Home Energy
    url: /capabilities/home-energy/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: emerging
    in_catalog: true
    kin_score: 12.7
    mcp: &id023
      status: unchecked
    slug: rainforest-automation
    status: profiled
    tags: &id024
    - Automation
    - Energy
    - IoT
    - Smart Meter
    url: /providers/rainforest-automation/
  layer: domain
  name: Rainforest Automation (Eagle)
  provider: rainforest-automation
  says: lists Rainforest Automation (Eagle) as an integration
  source: https://pvoutput.org/help/auto_uploader.html
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-200.30
    key: home-energy
    name: Home Energy
    url: /capabilities/home-energy/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 14.5
    band: thin
    in_catalog: true
    kin_score: 32.3
    mcp: &id025
      status: unknown
    slug: sma-solar
    status: profiled
    tags: &id026
    - Company
    - Energy
    - Inverters
    - Solar
    url: /providers/sma-solar/
  layer: domain
  name: SMA Webbox
  provider: sma-solar
  says: lists SMA Webbox as an integration
  source: https://pvoutput.org/help/auto_uploader.html
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-200.30
    key: home-energy
    name: Home Energy
    url: /capabilities/home-energy/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: minimal
    in_catalog: true
    kin_score: 6.6
    mcp: &id027
      status: unchecked
    slug: smappee
    status: profiled
    tags: &id028
    - Energy
    - IoT
    - Smart Grid
    - Software-as-a-Service
    url: /providers/smappee/
  layer: domain
  name: Smappee
  provider: smappee
  says: lists Smappee as an integration
  source: https://pvoutput.org/help/auto_uploader.html
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-200.30
    key: home-energy
    name: Home Energy
    url: /capabilities/home-energy/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 15.9
    mcp: &id029
      status: unchecked
    slug: solar-log
    status: profiled
    tags: &id030
    - Germany
    - Monitoring
    - Photovoltaics
    - Solar Energy
    url: /providers/solar-log/
  layer: domain
  name: Solar-Log
  provider: solar-log
  says: lists Solar-Log as an integration
  source: https://pvoutput.org/help/service_integration.html
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-200.30
    key: home-energy
    name: Home Energy
    url: /capabilities/home-energy/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 28.5
    band: developing
    in_catalog: true
    kin_score: 42.7
    mcp: &id031
      status: none
    slug: solar-edge
    status: profiled
    tags: &id032
    - Energy
    - Monitoring
    - PV
    - Solar
    url: /providers/solar-edge/
  layer: domain
  name: SolarEdge
  provider: solar-edge
  says: lists SolarEdge as an integration
  source: https://pvoutput.org/help/auto_uploader.html
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-200.30
    key: home-energy
    name: Home Energy
    url: /capabilities/home-energy/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: minimal
    in_catalog: true
    kin_score: 6.4
    mcp: &id033
      status: unchecked
    slug: the-energy-detective
    status: profiled
    tags: &id034
    - Company
    - Energy
    - Home Automation
    - Monitoring
    url: /providers/the-energy-detective/
  layer: domain
  name: TED (The Energy Detective)
  provider: the-energy-detective
  says: lists TED (The Energy Detective) as an integration
  source: https://pvoutput.org/help/auto_uploader.html
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-200.30
    key: home-energy
    name: Home Energy
    url: /capabilities/home-energy/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.2
    band: developing
    in_catalog: true
    kin_score: 46.9
    mcp: &id035
      status: unknown
    slug: tesla-energy
    status: profiled
    tags: &id036
    - Battery Storage
    - Clean Energy
    - Energy
    - Solar
    url: /providers/tesla-energy/
  layer: domain
  name: Tesla Powerwall
  provider: tesla-energy
  says: lists Tesla Powerwall as an integration
  source: https://pvoutput.org/help/service_integration.html
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-200.30
    key: home-energy
    name: Home Energy
    url: /capabilities/home-energy/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 2.5
    mcp: &id037
      status: unchecked
    slug: trannergy
    status: profiled
    tags: &id038
    - Analytics
    - Energy
    - IoT
    - Sustainability
    url: /providers/trannergy/
  layer: domain
  name: Trannergy
  provider: trannergy
  says: lists Trannergy as an integration
  source: https://pvoutput.org/help/auto_uploader.html
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-200.30
    key: home-energy
    name: Home Energy
    url: /capabilities/home-energy/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 21.1
    mcp: &id039
      status: unchecked
    slug: wattvision
    status: profiled
    tags: &id040
    - Billing
    - Company
    - Energy
    - Monitoring
    url: /providers/wattvision/
  layer: domain
  name: Wattvision
  provider: wattvision
  says: lists Wattvision as an integration
  source: https://pvoutput.org/help/auto_uploader.html
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-230.10
    key: weather-environment
    name: Weather & Environment
    url: /capabilities/weather-environment/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.3
    band: thin
    in_catalog: true
    kin_score: 34.9
    mcp: &id041
      status: none
    slug: wunderground
    status: profiled
    tags: &id042
    - Hyperlocal
    - Observations
    - Personal Weather Stations
    - Weather
    url: /providers/wunderground/
  layer: domain
  name: Weather Underground
  provider: wunderground
  says: lists Weather Underground as an integration
  source: https://pvoutput.org/help/auto_uploader.html
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-200.30
    key: home-energy
    name: Home Energy
    url: /capabilities/home-energy/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: minimal
    in_catalog: true
    kin_score: 8.5
    mcp: &id043
      status: unchecked
    slug: zeversolar
    status: profiled
    tags: &id044
    - Company
    - Energy
    - Germany
    - Solar
    url: /providers/zeversolar/
  layer: domain
  name: Zevercloud (Zeversolar)
  provider: zeversolar
  says: lists Zevercloud (Zeversolar) as an integration
  source: https://pvoutput.org/help/auto_uploader.html
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/solar-energy-monitoring/pvoutput/
providers:
- agent_band: human-only
  agent_readiness: 3.0
  band: minimal
  in_catalog: true
  kin_score: 3.2
  mcp: *id001
  name: Ambient Weather
  slug: ambient-weather
  status: profiled
  tags: *id002
  url: /providers/ambient-weather/
- agent_band: human-only
  agent_readiness: 3.0
  band: minimal
  in_catalog: true
  kin_score: 7.5
  mcp: *id003
  name: Current Cost
  slug: current-cost
  status: profiled
  tags: *id004
  url: /providers/current-cost/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 0.4
  mcp: *id005
  name: Efergy
  slug: efergy
  status: profiled
  tags: *id006
  url: /providers/efergy/
- agent_band: agent-aware
  agent_readiness: 6.9
  band: thin
  in_catalog: true
  kin_score: 27.7
  mcp: *id007
  name: EKM Metering
  slug: ekm-metering
  status: profiled
  tags: *id008
  url: /providers/ekm-metering/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id009
  name: Energomonitor
  slug: energomonitor
  status: queued for profiling
  tags: *id010
  url: null
- agent_band: agent-ready
  agent_readiness: 35.2
  band: exemplar
  in_catalog: true
  kin_score: 68.6
  mcp: *id011
  name: Enphase Enlighten
  slug: enphase
  status: profiled
  tags: *id012
  url: /providers/enphase/
- agent_band: human-only
  agent_readiness: 3.0
  band: minimal
  in_catalog: true
  kin_score: 10.8
  mcp: *id013
  name: Flukso
  slug: flukso
  status: profiled
  tags: *id014
  url: /providers/flukso/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 12.3
  mcp: *id015
  name: Fronius
  slug: fronius
  status: profiled
  tags: *id016
  url: /providers/fronius/
- agent_band: human-only
  agent_readiness: 2.5
  band: emerging
  in_catalog: true
  kin_score: 11.5
  mcp: *id017
  name: Growatt ShineNET
  slug: growatt
  status: profiled
  tags: *id018
  url: /providers/growatt/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 6.9
  mcp: *id019
  name: KACO
  slug: kaco-new-energy
  status: profiled
  tags: *id020
  url: /providers/kaco-new-energy/
- agent_band: agent-ready
  agent_readiness: 30.0
  band: strong
  in_catalog: true
  kin_score: 59.1
  mcp: *id021
  name: OpenWeatherMap
  slug: openweathermap
  status: profiled
  tags: *id022
  url: /providers/openweathermap/
- agent_band: human-only
  agent_readiness: 3.0
  band: emerging
  in_catalog: true
  kin_score: 12.7
  mcp: *id023
  name: Rainforest Automation (Eagle)
  slug: rainforest-automation
  status: profiled
  tags: *id024
  url: /providers/rainforest-automation/
- agent_band: agent-aware
  agent_readiness: 14.5
  band: thin
  in_catalog: true
  kin_score: 32.3
  mcp: *id025
  name: SMA Webbox
  slug: sma-solar
  status: profiled
  tags: *id026
  url: /providers/sma-solar/
- agent_band: human-only
  agent_readiness: 3.0
  band: minimal
  in_catalog: true
  kin_score: 6.6
  mcp: *id027
  name: Smappee
  slug: smappee
  status: profiled
  tags: *id028
  url: /providers/smappee/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 15.9
  mcp: *id029
  name: Solar-Log
  slug: solar-log
  status: profiled
  tags: *id030
  url: /providers/solar-log/
- agent_band: agent-aware
  agent_readiness: 28.5
  band: developing
  in_catalog: true
  kin_score: 42.7
  mcp: *id031
  name: SolarEdge
  slug: solar-edge
  status: profiled
  tags: *id032
  url: /providers/solar-edge/
- agent_band: human-only
  agent_readiness: 3.0
  band: minimal
  in_catalog: true
  kin_score: 6.4
  mcp: *id033
  name: TED (The Energy Detective)
  slug: the-energy-detective
  status: profiled
  tags: *id034
  url: /providers/the-energy-detective/
- agent_band: agent-ready
  agent_readiness: 31.2
  band: developing
  in_catalog: true
  kin_score: 46.9
  mcp: *id035
  name: Tesla Powerwall
  slug: tesla-energy
  status: profiled
  tags: *id036
  url: /providers/tesla-energy/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 2.5
  mcp: *id037
  name: Trannergy
  slug: trannergy
  status: profiled
  tags: *id038
  url: /providers/trannergy/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 21.1
  mcp: *id039
  name: Wattvision
  slug: wattvision
  status: profiled
  tags: *id040
  url: /providers/wattvision/
- agent_band: agent-ready
  agent_readiness: 31.3
  band: thin
  in_catalog: true
  kin_score: 34.9
  mcp: *id041
  name: Weather Underground
  slug: wunderground
  status: profiled
  tags: *id042
  url: /providers/wunderground/
- agent_band: human-only
  agent_readiness: 3.0
  band: minimal
  in_catalog: true
  kin_score: 8.5
  mcp: *id043
  name: Zevercloud (Zeversolar)
  slug: zeversolar
  status: profiled
  tags: *id044
  url: /providers/zeversolar/
siblings:
- name: Enphase App (Enlighten)
  rows: 4
  url: /applications/solar-energy-monitoring/enphase-app-enlighten/
- name: mySolarEdge
  rows: 2
  url: /applications/solar-energy-monitoring/mysolaredge/
- name: OpenEMS
  rows: 27
  url: /applications/solar-energy-monitoring/openems/
- name: OpenEnergyMonitor (emonHub)
  rows: 11
  url: /applications/solar-energy-monitoring/openenergymonitor-emonhub/
- name: Predbat
  rows: 31
  url: /applications/solar-energy-monitoring/predbat/
- name: Sense
  rows: 6
  url: /applications/solar-energy-monitoring/sense/
sitemap: true
title: 'PVOutput: Home Energy & Solar Monitoring reference app'
---
