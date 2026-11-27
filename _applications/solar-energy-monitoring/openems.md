---
app: OpenEMS
app_slug: openems
app_url: https://github.com/OpenEMS/openems
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-200.30.10
  key: AE-200.30.10
  layer: domain
  name: Dynamic Electricity Tariffs
  providers:
  - aWATTar
  - Corrently (STROMDAO)
  - EWS Elektrizitaetswerke Schoenau
  - Groupe E
  - Luox Energy
  - Rabot Energy
  - Stadtwerk Hassfurt
  - Swisspower
  - Tibber
  url: /capabilities/home-energy/
  via_parent: Home Energy
- attribution: API Evangelist extension
  id: AE-200.30
  key: home-energy
  layer: domain
  name: Home Energy
  providers:
  - BYD
  - Discovergy (inexogy)
  - Fronius
  - GoodWe
  - Huawei FusionSolar
  - KACO new energy
  - KOSTAL Solar Electric
  - OpenDTU
  - Pylontech
  - Shelly
  - SMA Solar Technology
  - Solar-Log
  - SolarEdge
  - Sungrow
  - Tesla Powerwall
  - Victron Energy
  url: /capabilities/home-energy/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-230.10
  key: weather-environment
  layer: domain
  name: Weather & Environment
  providers:
  - Open-Meteo
  url: /capabilities/weather-environment/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - InfluxDB
  url: /capabilities/observability-management/
  via_parent: null
category:
  id: solar-energy-monitoring
  name: Home Energy & Solar Monitoring
  url: /applications/solar-energy-monitoring/
counts:
  declared: 0
  observed: 27
credits: []
evidence:
- route: source code
  url: https://github.com/OpenEMS/openems
- route: source code
  url: https://github.com/OpenEMS/openems/tree/develop/io.openems.edge.timeofusetariff.tibber
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-200.30.10
    key: AE-200.30.10
    name: Dynamic Electricity Tariffs
    url: /capabilities/home-energy/
    via_parent: Home Energy
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 28.4
    band: thin
    in_catalog: true
    kin_score: 26.8
    mcp: &id001
      status: none
    slug: awattar
    status: profiled
    tags: &id002
    - EPEX Spot
    - Electricity
    - Energy
    - Spot Price
    url: /providers/awattar/
  layer: domain
  name: aWATTar
  provider: awattar
  says: ships the aWATTar SDK or integration code
  source: https://github.com/OpenEMS/openems/tree/develop/io.openems.edge.timeofusetariff.awattar
  tier: observed
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
    kin_score: 5.0
    mcp: &id003
      status: none
    slug: byd
    status: profiled
    tags: &id004
    - Automotive
    - Company
    - Electric Vehicles
    - Technology
    url: /providers/byd/
  layer: domain
  name: BYD
  provider: byd
  says: ships the BYD SDK or integration code
  source: https://github.com/OpenEMS/openems/tree/develop/io.openems.edge.battery.bydcommercial
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-200.30.10
    key: AE-200.30.10
    name: Dynamic Electricity Tariffs
    url: /capabilities/home-energy/
    via_parent: Home Energy
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: minimal
    in_catalog: true
    kin_score: 9.0
    mcp: &id005
      status: unchecked
    slug: corrently
    status: profiled
    tags: &id006
    - Energy
    - Germany
    - Renewables
    - Transparency
    url: /providers/corrently/
  layer: domain
  name: Corrently (STROMDAO)
  provider: corrently
  says: ships the Corrently (STROMDAO) SDK or integration code
  source: https://github.com/OpenEMS/openems/tree/develop/io.openems.edge.timeofusetariff.corrently
  tier: observed
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
    agent_readiness: 18.7
    band: thin
    in_catalog: true
    kin_score: 30.3
    mcp: &id007
      status: unchecked
    slug: discovergy
    status: profiled
    tags: &id008
    - Company
    - Data Platform
    - Energy
    - Smart Metering
    url: /providers/discovergy/
  layer: domain
  name: Discovergy (inexogy)
  provider: discovergy
  says: ships the Discovergy (inexogy) SDK or integration code
  source: https://github.com/OpenEMS/openems/tree/develop/io.openems.edge.meter.discovergy
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-200.30.10
    key: AE-200.30.10
    name: Dynamic Electricity Tariffs
    url: /capabilities/home-energy/
    via_parent: Home Energy
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: minimal
    in_catalog: true
    kin_score: 7.4
    mcp: &id009
      status: unchecked
    slug: ews-schoenau
    status: profiled
    tags: &id010
    - Company
    - Cooperative
    - Energy
    - Renewables
    url: /providers/ews-schoenau/
  layer: domain
  name: EWS Elektrizitaetswerke Schoenau
  provider: ews-schoenau
  says: ships the EWS Elektrizitaetswerke Schoenau SDK or integration code
  source: https://github.com/OpenEMS/openems/tree/develop/io.openems.edge.timeofusetariff.ews
  tier: observed
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
    mcp: &id011
      status: none
    slug: fronius
    status: profiled
    tags: &id012
    - Company
    - Energy
    - Solar
    - Welding
    url: /providers/fronius/
  layer: domain
  name: Fronius
  provider: fronius
  says: ships the Fronius SDK or integration code
  source: https://github.com/OpenEMS/openems/tree/develop/io.openems.edge.fronius
  tier: observed
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
    mcp: &id013
      status: unchecked
    slug: goodwe
    status: profiled
    tags: &id014
    - Company
    - Energy Storage
    - Inverters
    - Solar
    url: /providers/goodwe/
  layer: domain
  name: GoodWe
  provider: goodwe
  says: ships the GoodWe SDK or integration code
  source: https://github.com/OpenEMS/openems/tree/develop/io.openems.edge.goodwe
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-200.30.10
    key: AE-200.30.10
    name: Dynamic Electricity Tariffs
    url: /capabilities/home-energy/
    via_parent: Home Energy
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 3.1
    mcp: &id015
      status: unknown
    slug: groupe-e
    status: profiled
    tags: &id016
    - Company
    - Energy
    - Renewables
    - Switzerland
    url: /providers/groupe-e/
  layer: domain
  name: Groupe E
  provider: groupe-e
  says: ships the Groupe E SDK or integration code
  source: https://github.com/OpenEMS/openems/tree/develop/io.openems.edge.timeofusetariff.groupe
  tier: observed
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
    kin_score: 15.6
    mcp: &id017
      status: unknown
    slug: huawei-fusionsolar
    status: profiled
    tags: &id018
    - Company
    - Energy
    - IoT
    - Solar
    url: /providers/huawei-fusionsolar/
  layer: domain
  name: Huawei FusionSolar
  provider: huawei-fusionsolar
  says: ships the Huawei FusionSolar SDK or integration code
  source: https://github.com/OpenEMS/openems/tree/develop/io.openems.edge.huawei
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
    agent_readiness: 34.4
    band: strong
    in_catalog: true
    kin_score: 63.3
    mcp: &id019
      source: https://github.com/influxdata/influxdb3_mcp_server
      status: verified
    slug: influxdata
    status: profiled
    tags: &id020
    - Database
    - Monitoring
    - Observability
    - Time Series Database
    url: /providers/influxdata/
  layer: common
  name: InfluxDB
  provider: influxdata
  says: ships the InfluxDB SDK or integration code
  source: https://github.com/OpenEMS/openems/tree/develop/io.openems.edge.timedata.influxdb
  tier: observed
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
    mcp: &id021
      status: unchecked
    slug: kaco-new-energy
    status: profiled
    tags: &id022
    - Company
    - Energy Storage
    - Inverters
    - Solar
    url: /providers/kaco-new-energy/
  layer: domain
  name: KACO new energy
  provider: kaco-new-energy
  says: ships the KACO new energy SDK or integration code
  source: https://github.com/OpenEMS/openems/tree/develop/io.openems.edge.pvinverter.kaco.blueplanet
  tier: observed
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
    kin_score: 11.3
    mcp: &id023
      status: unchecked
    slug: kostal
    status: profiled
    tags: &id024
    - Company
    - Energy Storage
    - Inverters
    - Solar
    url: /providers/kostal/
  layer: domain
  name: KOSTAL Solar Electric
  provider: kostal
  says: ships the KOSTAL Solar Electric SDK or integration code
  source: https://github.com/OpenEMS/openems/tree/develop/io.openems.edge.kostal
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-200.30.10
    key: AE-200.30.10
    name: Dynamic Electricity Tariffs
    url: /capabilities/home-energy/
    via_parent: Home Energy
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 5.9
    mcp: &id025
      status: unchecked
    slug: luox-energy
    status: profiled
    tags: &id026
    - Company
    - Energy
    - Renewables
    - Tariffs
    url: /providers/luox-energy/
  layer: domain
  name: Luox Energy
  provider: luox-energy
  says: ships the Luox Energy SDK or integration code
  source: https://github.com/OpenEMS/openems/tree/develop/io.openems.edge.timeofusetariff.luox
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-230.10
    key: weather-environment
    name: Weather & Environment
    url: /capabilities/weather-environment/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 17.4
    band: thin
    in_catalog: true
    kin_score: 28.3
    mcp: &id027
      status: none
    slug: open-meteo
    status: profiled
    tags: &id028
    - Air Quality
    - Forecast
    - Historical Weather
    - Weather
    url: /providers/open-meteo/
  layer: domain
  name: Open-Meteo
  provider: open-meteo
  says: ships the Open-Meteo SDK or integration code
  source: https://github.com/OpenEMS/openems/tree/develop/io.openems.edge.weather.openmeteo
  tier: observed
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
    agent_readiness: 5.3
    band: emerging
    in_catalog: true
    kin_score: 19.5
    mcp: &id029
      status: unknown
    slug: opendtu
    status: profiled
    tags: &id030
    - Firmware
    - IoT
    - Open Source
    - Solar
    url: /providers/opendtu/
  layer: domain
  name: OpenDTU
  provider: opendtu
  says: ships the OpenDTU SDK or integration code
  source: https://github.com/OpenEMS/openems/tree/develop/io.openems.edge.meter.opendtu
  tier: observed
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
    mcp: &id031
      status: unchecked
    slug: pylontech
    status: profiled
    tags: &id032
    - Batteries
    - Company
    - Energy
    - Storage
    url: /providers/pylontech/
  layer: domain
  name: Pylontech
  provider: pylontech
  says: ships the Pylontech SDK or integration code
  source: https://github.com/OpenEMS/openems/tree/develop/io.openems.edge.battery.pylontech
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-200.30.10
    key: AE-200.30.10
    name: Dynamic Electricity Tariffs
    url: /capabilities/home-energy/
    via_parent: Home Energy
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.7
    band: minimal
    in_catalog: true
    kin_score: 10.6
    mcp: &id033
      status: unknown
    slug: rabotenergy
    status: profiled
    tags: &id034
    - Company
    - Consumer
    - Electricity
    - Energy
    url: /providers/rabotenergy/
  layer: domain
  name: Rabot Energy
  provider: rabotenergy
  says: ships the Rabot Energy SDK or integration code
  source: https://github.com/OpenEMS/openems/tree/develop/io.openems.edge.timeofusetariff.rabotcharge
  tier: observed
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
    agent_readiness: 4.4
    band: emerging
    in_catalog: true
    kin_score: 11.6
    mcp: &id035
      source: https://shelly-api-docs.shelly.cloud/mcp
      status: verified
    slug: shelly
    status: profiled
    tags: &id036
    - Company
    - Devices
    - IoT
    - Smart Home
    url: /providers/shelly/
  layer: domain
  name: Shelly
  provider: shelly
  says: ships the Shelly SDK or integration code
  source: https://github.com/OpenEMS/openems/tree/develop/io.openems.edge.io.shelly
  tier: observed
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
    mcp: &id037
      status: unknown
    slug: sma-solar
    status: profiled
    tags: &id038
    - Company
    - Energy
    - Inverters
    - Solar
    url: /providers/sma-solar/
  layer: domain
  name: SMA Solar Technology
  provider: sma-solar
  says: ships the SMA Solar Technology SDK or integration code
  source: https://github.com/OpenEMS/openems/tree/develop/io.openems.edge.sma
  tier: observed
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
    mcp: &id039
      status: unchecked
    slug: solar-log
    status: profiled
    tags: &id040
    - Germany
    - Monitoring
    - Photovoltaics
    - Solar Energy
    url: /providers/solar-log/
  layer: domain
  name: Solar-Log
  provider: solar-log
  says: ships the Solar-Log SDK or integration code
  source: https://github.com/OpenEMS/openems/tree/develop/io.openems.edge.pvinverter.solarlog
  tier: observed
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
    mcp: &id041
      status: none
    slug: solar-edge
    status: profiled
    tags: &id042
    - Energy
    - Monitoring
    - PV
    - Solar
    url: /providers/solar-edge/
  layer: domain
  name: SolarEdge
  provider: solar-edge
  says: ships the SolarEdge SDK or integration code
  source: https://github.com/OpenEMS/openems/tree/develop/io.openems.edge.solaredge
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-200.30.10
    key: AE-200.30.10
    name: Dynamic Electricity Tariffs
    url: /capabilities/home-energy/
    via_parent: Home Energy
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 10.7
    mcp: &id043
      status: unchecked
    slug: stadtwerk-hassfurt
    status: profiled
    tags: &id044
    - Energy
    - Germany
    - Municipal
    - Utilities
    url: /providers/stadtwerk-hassfurt/
  layer: domain
  name: Stadtwerk Hassfurt
  provider: stadtwerk-hassfurt
  says: ships the Stadtwerk Hassfurt SDK or integration code
  source: https://github.com/OpenEMS/openems/tree/develop/io.openems.edge.timeofusetariff.hassfurt
  tier: observed
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
    kin_score: 10.0
    mcp: &id045
      status: unchecked
    slug: sungrow
    status: profiled
    tags: &id046
    - Company
    - Energy Storage
    - Renewable Energy
    - Solar Inverters
    url: /providers/sungrow/
  layer: domain
  name: Sungrow
  provider: sungrow
  says: ships the Sungrow SDK or integration code
  source: https://github.com/OpenEMS/openems/tree/develop/io.openems.edge.sungrow
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-200.30.10
    key: AE-200.30.10
    name: Dynamic Electricity Tariffs
    url: /capabilities/home-energy/
    via_parent: Home Energy
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 8.5
    mcp: &id047
      status: unchecked
    slug: swisspower
    status: profiled
    tags: &id048
    - Alliance
    - Energy
    - Switzerland
    - Utilities
    url: /providers/swisspower/
  layer: domain
  name: Swisspower
  provider: swisspower
  says: ships the Swisspower SDK or integration code
  source: https://github.com/OpenEMS/openems/tree/develop/io.openems.edge.timeofusetariff.swisspower
  tier: observed
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
    mcp: &id049
      status: unknown
    slug: tesla-energy
    status: profiled
    tags: &id050
    - Battery Storage
    - Clean Energy
    - Energy
    - Solar
    url: /providers/tesla-energy/
  layer: domain
  name: Tesla Powerwall
  provider: tesla-energy
  says: ships the Tesla Powerwall SDK or integration code
  source: https://github.com/OpenEMS/openems/tree/develop/io.openems.edge.tesla.powerwall2
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-200.30.10
    key: AE-200.30.10
    name: Dynamic Electricity Tariffs
    url: /capabilities/home-energy/
    via_parent: Home Energy
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.6
    band: developing
    in_catalog: true
    kin_score: 49.5
    mcp: &id051
      status: none
    slug: tibber
    status: profiled
    tags: &id052
    - ElectricityPricing
    - Energy
    - Smart Home
    - Smart Meter
    url: /providers/tibber/
  layer: domain
  name: Tibber
  provider: tibber
  says: ships the Tibber SDK or integration code
  source: https://github.com/OpenEMS/openems/tree/develop/io.openems.edge.timeofusetariff.tibber
  tier: observed
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
    agent_readiness: 27.5
    band: thin
    in_catalog: true
    kin_score: 33.9
    mcp: &id053
      status: none
    slug: victron-energy
    status: profiled
    tags: &id054
    - Company
    - Energy
    - Off-Grid
    - Renewables
    url: /providers/victron-energy/
  layer: domain
  name: Victron Energy
  provider: victron-energy
  says: ships the Victron Energy SDK or integration code
  source: https://github.com/OpenEMS/openems/tree/develop/io.openems.edge.victron
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/solar-energy-monitoring/openems/
providers:
- agent_band: agent-aware
  agent_readiness: 28.4
  band: thin
  in_catalog: true
  kin_score: 26.8
  mcp: *id001
  name: aWATTar
  slug: awattar
  status: profiled
  tags: *id002
  url: /providers/awattar/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 5.0
  mcp: *id003
  name: BYD
  slug: byd
  status: profiled
  tags: *id004
  url: /providers/byd/
- agent_band: human-only
  agent_readiness: 3.0
  band: minimal
  in_catalog: true
  kin_score: 9.0
  mcp: *id005
  name: Corrently (STROMDAO)
  slug: corrently
  status: profiled
  tags: *id006
  url: /providers/corrently/
- agent_band: agent-aware
  agent_readiness: 18.7
  band: thin
  in_catalog: true
  kin_score: 30.3
  mcp: *id007
  name: Discovergy (inexogy)
  slug: discovergy
  status: profiled
  tags: *id008
  url: /providers/discovergy/
- agent_band: human-only
  agent_readiness: 3.0
  band: minimal
  in_catalog: true
  kin_score: 7.4
  mcp: *id009
  name: EWS Elektrizitaetswerke Schoenau
  slug: ews-schoenau
  status: profiled
  tags: *id010
  url: /providers/ews-schoenau/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 12.3
  mcp: *id011
  name: Fronius
  slug: fronius
  status: profiled
  tags: *id012
  url: /providers/fronius/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 2.5
  mcp: *id013
  name: GoodWe
  slug: goodwe
  status: profiled
  tags: *id014
  url: /providers/goodwe/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 3.1
  mcp: *id015
  name: Groupe E
  slug: groupe-e
  status: profiled
  tags: *id016
  url: /providers/groupe-e/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 15.6
  mcp: *id017
  name: Huawei FusionSolar
  slug: huawei-fusionsolar
  status: profiled
  tags: *id018
  url: /providers/huawei-fusionsolar/
- agent_band: agent-ready
  agent_readiness: 34.4
  band: strong
  in_catalog: true
  kin_score: 63.3
  mcp: *id019
  name: InfluxDB
  slug: influxdata
  status: profiled
  tags: *id020
  url: /providers/influxdata/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 6.9
  mcp: *id021
  name: KACO new energy
  slug: kaco-new-energy
  status: profiled
  tags: *id022
  url: /providers/kaco-new-energy/
- agent_band: human-only
  agent_readiness: 3.0
  band: emerging
  in_catalog: true
  kin_score: 11.3
  mcp: *id023
  name: KOSTAL Solar Electric
  slug: kostal
  status: profiled
  tags: *id024
  url: /providers/kostal/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 5.9
  mcp: *id025
  name: Luox Energy
  slug: luox-energy
  status: profiled
  tags: *id026
  url: /providers/luox-energy/
- agent_band: agent-aware
  agent_readiness: 17.4
  band: thin
  in_catalog: true
  kin_score: 28.3
  mcp: *id027
  name: Open-Meteo
  slug: open-meteo
  status: profiled
  tags: *id028
  url: /providers/open-meteo/
- agent_band: agent-aware
  agent_readiness: 5.3
  band: emerging
  in_catalog: true
  kin_score: 19.5
  mcp: *id029
  name: OpenDTU
  slug: opendtu
  status: profiled
  tags: *id030
  url: /providers/opendtu/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 2.5
  mcp: *id031
  name: Pylontech
  slug: pylontech
  status: profiled
  tags: *id032
  url: /providers/pylontech/
- agent_band: human-only
  agent_readiness: 0.7
  band: minimal
  in_catalog: true
  kin_score: 10.6
  mcp: *id033
  name: Rabot Energy
  slug: rabotenergy
  status: profiled
  tags: *id034
  url: /providers/rabotenergy/
- agent_band: human-only
  agent_readiness: 4.4
  band: emerging
  in_catalog: true
  kin_score: 11.6
  mcp: *id035
  name: Shelly
  slug: shelly
  status: profiled
  tags: *id036
  url: /providers/shelly/
- agent_band: agent-aware
  agent_readiness: 14.5
  band: thin
  in_catalog: true
  kin_score: 32.3
  mcp: *id037
  name: SMA Solar Technology
  slug: sma-solar
  status: profiled
  tags: *id038
  url: /providers/sma-solar/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 15.9
  mcp: *id039
  name: Solar-Log
  slug: solar-log
  status: profiled
  tags: *id040
  url: /providers/solar-log/
- agent_band: agent-aware
  agent_readiness: 28.5
  band: developing
  in_catalog: true
  kin_score: 42.7
  mcp: *id041
  name: SolarEdge
  slug: solar-edge
  status: profiled
  tags: *id042
  url: /providers/solar-edge/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 10.7
  mcp: *id043
  name: Stadtwerk Hassfurt
  slug: stadtwerk-hassfurt
  status: profiled
  tags: *id044
  url: /providers/stadtwerk-hassfurt/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 10.0
  mcp: *id045
  name: Sungrow
  slug: sungrow
  status: profiled
  tags: *id046
  url: /providers/sungrow/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 8.5
  mcp: *id047
  name: Swisspower
  slug: swisspower
  status: profiled
  tags: *id048
  url: /providers/swisspower/
- agent_band: agent-ready
  agent_readiness: 31.2
  band: developing
  in_catalog: true
  kin_score: 46.9
  mcp: *id049
  name: Tesla Powerwall
  slug: tesla-energy
  status: profiled
  tags: *id050
  url: /providers/tesla-energy/
- agent_band: agent-aware
  agent_readiness: 25.6
  band: developing
  in_catalog: true
  kin_score: 49.5
  mcp: *id051
  name: Tibber
  slug: tibber
  status: profiled
  tags: *id052
  url: /providers/tibber/
- agent_band: agent-aware
  agent_readiness: 27.5
  band: thin
  in_catalog: true
  kin_score: 33.9
  mcp: *id053
  name: Victron Energy
  slug: victron-energy
  status: profiled
  tags: *id054
  url: /providers/victron-energy/
siblings:
- name: Enphase App (Enlighten)
  rows: 4
  url: /applications/solar-energy-monitoring/enphase-app-enlighten/
- name: mySolarEdge
  rows: 2
  url: /applications/solar-energy-monitoring/mysolaredge/
- name: OpenEnergyMonitor (emonHub)
  rows: 11
  url: /applications/solar-energy-monitoring/openenergymonitor-emonhub/
- name: Predbat
  rows: 31
  url: /applications/solar-energy-monitoring/predbat/
- name: PVOutput
  rows: 22
  url: /applications/solar-energy-monitoring/pvoutput/
- name: Sense
  rows: 6
  url: /applications/solar-energy-monitoring/sense/
sitemap: true
title: 'OpenEMS: Home Energy & Solar Monitoring reference app'
---
