---
access: understanding
agent_layer:
- app: Predbat
  finding: Predbat ships its own MCP server (web_mcp.py) exposing battery plan and prediction data
  source: https://github.com/springfall2008/batpred/blob/main/apps/predbat/web_mcp.py
  tier: observed
- app: Predbat
  finding: bring-your-own LLM chat (OpenAI, OpenRouter or local Ollama) over the plan
  source: https://github.com/springfall2008/batpred/blob/main/apps/predbat/chat.py
  tier: observed
apps:
- anchor: openems
  counts:
    declared: 0
    observed: 27
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
    layer: domain
    name: Victron Energy
    provider: victron-energy
    says: ships the Victron Energy SDK or integration code
    source: https://github.com/OpenEMS/openems/tree/develop/io.openems.edge.victron
    tier: observed
  kind: self-hosted
  name: OpenEMS
  page: /applications/solar-energy-monitoring/openems/
  slug: openems
  url: https://github.com/OpenEMS/openems
- anchor: predbat
  counts:
    declared: 0
    observed: 31
  evidence:
  - route: source code
    url: https://github.com/springfall2008/batpred/blob/main/apps/predbat/web_mcp.py
  - route: source code
    url: https://github.com/springfall2008/batpred/tree/main/apps/predbat
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-200.30.10
      key: AE-200.30.10
      name: Dynamic Electricity Tariffs
      url: /capabilities/home-energy/
      via_parent: Home Energy
    credit: null
    layer: domain
    name: AgilePredict
    provider: agilepredict
    says: ships the AgilePredict SDK or integration code
    source: https://github.com/springfall2008/batpred/blob/main/apps/predbat/futurerate.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-200.30
      key: home-energy
      name: Home Energy
      url: /capabilities/home-energy/
      via_parent: null
    credit: null
    layer: domain
    name: AlphaESS
    provider: alpha-ess
    says: ships the AlphaESS SDK or integration code
    source: https://github.com/springfall2008/batpred/blob/main/apps/predbat/alphaess.py
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-3840.20
      key: virtual-power-plant-operations
      name: Virtual Power Plant Operations
      url: /capabilities/virtual-power-plant-operations/
      via_parent: null
    credit: null
    layer: domain
    name: Axle Energy
    provider: axle-energy
    says: ships the Axle Energy SDK or integration code
    source: https://github.com/springfall2008/batpred/blob/main/apps/predbat/axle.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-230.80
      key: grid-carbon-intensity
      name: Grid Carbon Intensity
      url: /capabilities/grid-carbon-intensity/
      via_parent: null
    credit: null
    layer: domain
    name: Carbon Intensity API (NESO)
    provider: carbon-intensity
    says: ships the Carbon Intensity API (NESO) SDK or integration code
    source: https://github.com/springfall2008/batpred/blob/main/apps/predbat/carbon.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-200.30
      key: home-energy
      name: Home Energy
      url: /capabilities/home-energy/
      via_parent: null
    credit: null
    layer: domain
    name: Deye Cloud
    provider: deye
    says: ships the Deye Cloud SDK or integration code
    source: https://github.com/springfall2008/batpred/blob/main/apps/predbat/deye.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-200.30.10
      key: AE-200.30.10
      name: Dynamic Electricity Tariffs
      url: /capabilities/home-energy/
      via_parent: Home Energy
    credit: null
    layer: domain
    name: E.ON Next (Kraken API)
    provider: eon-next
    says: ships the E.ON Next (Kraken API) SDK or integration code
    source: https://github.com/springfall2008/batpred/blob/main/apps/predbat/kraken.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-200.30.10
      key: AE-200.30.10
      name: Dynamic Electricity Tariffs
      url: /capabilities/home-energy/
      via_parent: Home Energy
    credit: null
    layer: domain
    name: EDF Energy (Kraken API)
    provider: edf-energy
    says: ships the EDF Energy (Kraken API) SDK or integration code
    source: https://github.com/springfall2008/batpred/blob/main/apps/predbat/kraken.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-200.30
      key: home-energy
      name: Home Energy
      url: /capabilities/home-energy/
      via_parent: null
    credit: null
    layer: domain
    name: Enphase Energy
    provider: enphase
    says: ships the Enphase Energy SDK or integration code
    source: https://github.com/springfall2008/batpred/blob/main/apps/predbat/enphase.py
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-3840.60
      key: der-forecasting
      name: DER Forecasting
      url: /capabilities/der-forecasting/
      via_parent: null
    credit: null
    layer: domain
    name: Forecast.Solar
    provider: forecast-solar
    says: ships the Forecast.Solar SDK or integration code
    source: https://github.com/springfall2008/batpred/blob/main/apps/predbat/solcast.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-200.30
      key: home-energy
      name: Home Energy
      url: /capabilities/home-energy/
      via_parent: null
    credit: null
    layer: domain
    name: FoxESS Cloud
    provider: fox-ess
    says: ships the FoxESS Cloud SDK or integration code
    source: https://github.com/springfall2008/batpred/blob/main/apps/predbat/fox.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-200.30
      key: home-energy
      name: Home Energy
      url: /capabilities/home-energy/
      via_parent: null
    credit: null
    layer: domain
    name: GivEnergy Cloud
    provider: givenergy
    says: ships the GivEnergy Cloud SDK or integration code
    source: https://github.com/springfall2008/batpred/blob/main/apps/predbat/gecloud.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-200.30
      key: home-energy
      name: Home Energy
      url: /capabilities/home-energy/
      via_parent: null
    credit: null
    layer: domain
    name: Growatt
    provider: growatt
    says: ships the Growatt SDK or integration code
    source: https://github.com/springfall2008/batpred/blob/main/apps/predbat/growatt.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-200.30
      key: home-energy
      name: Home Energy
      url: /capabilities/home-energy/
      via_parent: null
    credit: null
    layer: domain
    name: Hanchu ESS
    provider: hanchu-ess
    says: ships the Hanchu ESS SDK or integration code
    source: https://github.com/springfall2008/batpred/blob/main/apps/predbat/hanchu.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-200.10
      key: smart-home
      name: Smart Home
      url: /capabilities/smart-home/
      via_parent: null
    credit: null
    layer: common
    name: Home Assistant
    provider: home-assistant
    says: ships the Home Assistant SDK or integration code
    source: https://github.com/springfall2008/batpred/blob/main/apps/predbat/ha.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-200.20.20
      key: AE-200.20.20
      name: EV Charging
      url: /capabilities/connected-vehicles/
      via_parent: Connected Vehicles
    credit: null
    layer: domain
    name: Hypervolt
    provider: hypervolt
    says: ships the Hypervolt SDK or integration code
    source: https://github.com/springfall2008/batpred/blob/main/apps/predbat/hypervolt.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-230.10
      key: weather-environment
      name: Weather & Environment
      url: /capabilities/weather-environment/
      via_parent: null
    credit: null
    layer: domain
    name: MeteoAlarm (EUMETNET)
    provider: meteoalarm
    says: ships the MeteoAlarm (EUMETNET) SDK or integration code
    source: https://github.com/springfall2008/batpred/blob/main/apps/predbat/alertfeed.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-200.20.20
      key: AE-200.20.20
      name: EV Charging
      url: /capabilities/connected-vehicles/
      via_parent: Connected Vehicles
    credit: null
    layer: domain
    name: myenergi
    provider: myenergi
    says: ships the myenergi SDK or integration code
    source: https://github.com/springfall2008/batpred/blob/main/apps/predbat/myenergi.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-200.30.10
      key: AE-200.30.10
      name: Dynamic Electricity Tariffs
      url: /capabilities/home-energy/
      via_parent: Home Energy
    credit: null
    layer: domain
    name: Octopus Energy
    provider: octopus-energy
    says: ships the Octopus Energy SDK or integration code
    source: https://github.com/springfall2008/batpred/blob/main/apps/predbat/octopus.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-200.20.20
      key: AE-200.20.20
      name: EV Charging
      url: /capabilities/connected-vehicles/
      via_parent: Connected Vehicles
    credit: null
    layer: domain
    name: Ohme
    provider: ohme
    says: ships the Ohme SDK or integration code
    source: https://github.com/springfall2008/batpred/blob/main/apps/predbat/ohme.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.40
      key: AE-110.10.40
      name: On-Device & Edge Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: Ollama
    provider: ollama
    says: ships the Ollama SDK or integration code
    source: https://github.com/springfall2008/batpred/blob/main/apps/predbat/chat.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-230.10
      key: weather-environment
      name: Weather & Environment
      url: /capabilities/weather-environment/
      via_parent: null
    credit: null
    layer: domain
    name: Open-Meteo
    provider: open-meteo
    says: ships the Open-Meteo SDK or integration code
    source: https://github.com/springfall2008/batpred/blob/main/apps/predbat/solcast.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: OpenAI
    provider: openai
    says: ships the OpenAI SDK or integration code
    source: https://github.com/springfall2008/batpred/blob/main/apps/predbat/chat.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: OpenRouter
    provider: openrouter
    says: ships the OpenRouter SDK or integration code
    source: https://github.com/springfall2008/batpred/blob/main/apps/predbat/chat.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120.10
      key: geocoding
      name: Geocoding
      url: /capabilities/geocoding/
      via_parent: null
    credit: null
    layer: common
    name: Postcodes.io
    provider: postcodes-io
    says: ships the Postcodes.io SDK or integration code
    source: https://github.com/springfall2008/batpred/blob/main/apps/predbat/solcast.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-200.30
      key: home-energy
      name: Home Energy
      url: /capabilities/home-energy/
      via_parent: null
    credit: null
    layer: domain
    name: Sigenergy
    provider: sigenergy
    says: ships the Sigenergy SDK or integration code
    source: https://github.com/springfall2008/batpred/blob/main/apps/predbat/sigenergy.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-200.30
      key: home-energy
      name: Home Energy
      url: /capabilities/home-energy/
      via_parent: null
    credit: null
    layer: domain
    name: SolaX Cloud
    provider: solax-power
    says: ships the SolaX Cloud SDK or integration code
    source: https://github.com/springfall2008/batpred/blob/main/apps/predbat/solax.py
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-3840.60
      key: der-forecasting
      name: DER Forecasting
      url: /capabilities/der-forecasting/
      via_parent: null
    credit: null
    layer: domain
    name: Solcast
    provider: solcast
    says: ships the Solcast SDK or integration code
    source: https://github.com/springfall2008/batpred/blob/main/apps/predbat/solcast.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-200.30
      key: home-energy
      name: Home Energy
      url: /capabilities/home-energy/
      via_parent: null
    credit: null
    layer: domain
    name: SolisCloud (Ginlong)
    provider: soliscloud
    says: ships the SolisCloud (Ginlong) SDK or integration code
    source: https://github.com/springfall2008/batpred/blob/main/apps/predbat/solis.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-200.30
      key: home-energy
      name: Home Energy
      url: /capabilities/home-energy/
      via_parent: null
    credit: null
    layer: domain
    name: Sunsynk
    provider: sunsynk
    says: ships the Sunsynk SDK or integration code
    source: https://github.com/springfall2008/batpred/blob/main/apps/predbat/sunsynk.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-200.30
      key: home-energy
      name: Home Energy
      url: /capabilities/home-energy/
      via_parent: null
    credit: null
    layer: domain
    name: Teslemetry (Tesla Fleet API proxy, Powerwall)
    provider: teslemetry
    says: ships the Teslemetry (Tesla Fleet API proxy, Powerwall) SDK or integration code
    source: https://github.com/springfall2008/batpred/blob/main/apps/predbat/teslemetry.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-200.20.20
      key: AE-200.20.20
      name: EV Charging
      url: /capabilities/connected-vehicles/
      via_parent: Connected Vehicles
    credit: null
    layer: domain
    name: Wallbox
    provider: wallbox
    says: ships the Wallbox SDK or integration code
    source: https://github.com/springfall2008/batpred/blob/main/apps/predbat/wallbox.py
    tier: observed
  kind: self-hosted
  name: Predbat
  page: /applications/solar-energy-monitoring/predbat/
  slug: predbat
  url: https://github.com/springfall2008/batpred
- anchor: openenergymonitor-(emonhub)
  counts:
    declared: 0
    observed: 11
  evidence:
  - route: source code
    url: https://github.com/openenergymonitor/emonhub/tree/master/src/interfacers
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-200.20.10
      key: AE-200.20.10
      name: Vehicle Data Access
      url: /capabilities/connected-vehicles/
      via_parent: Connected Vehicles
    credit: null
    layer: domain
    name: BMW ConnectedDrive
    provider: bmw-connecteddrive
    says: ships the BMW ConnectedDrive SDK or integration code
    source: https://github.com/openenergymonitor/emonhub/blob/master/src/interfacers/EmonHubBMWInterfacer.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-200.30
      key: home-energy
      name: Home Energy
      url: /capabilities/home-energy/
      via_parent: null
    credit: null
    layer: domain
    name: Eastron (SDM120 meter)
    provider: eastron
    says: ships the Eastron (SDM120 meter) SDK or integration code
    source: https://github.com/openenergymonitor/emonhub/blob/master/src/interfacers/EmonHubSDM120Interfacer.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-200.30
      key: home-energy
      name: Home Energy
      url: /capabilities/home-energy/
      via_parent: null
    credit: null
    layer: domain
    name: GoodWe
    provider: goodwe
    says: ships the GoodWe SDK or integration code
    source: https://github.com/openenergymonitor/emonhub/blob/master/src/interfacers/EmonHubGoodWeInterfacer.py
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: common
    name: InfluxDB
    provider: influxdata
    says: ships the InfluxDB SDK or integration code
    source: https://github.com/openenergymonitor/emonhub/blob/master/src/interfacers/EmonHubInfluxInterfacer.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-200.20.10
      key: AE-200.20.10
      name: Vehicle Data Access
      url: /capabilities/connected-vehicles/
      via_parent: Connected Vehicles
    credit: null
    layer: domain
    name: Jaguar Land Rover
    provider: jlr
    says: ships the Jaguar Land Rover SDK or integration code
    source: https://github.com/openenergymonitor/emonhub/blob/master/src/interfacers/EmonHubJaguarLandRoverInterfacer.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-200.30
      key: home-energy
      name: Home Energy
      url: /capabilities/home-energy/
      via_parent: null
    credit: null
    layer: domain
    name: Renogy
    provider: renogy
    says: ships the Renogy SDK or integration code
    source: https://github.com/openenergymonitor/emonhub/blob/master/src/interfacers/EmonHubModbusRenogyInterfacer.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-200.30
      key: home-energy
      name: Home Energy
      url: /capabilities/home-energy/
      via_parent: null
    credit: null
    layer: domain
    name: Shelly
    provider: shelly
    says: ships the Shelly SDK or integration code
    source: https://github.com/openenergymonitor/emonhub/blob/master/src/interfacers/EmonHubShellyInterfacer.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-200.30
      key: home-energy
      name: Home Energy
      url: /capabilities/home-energy/
      via_parent: null
    credit: null
    layer: domain
    name: SMA Solar Technology
    provider: sma-solar
    says: ships the SMA Solar Technology SDK or integration code
    source: https://github.com/openenergymonitor/emonhub/blob/master/src/interfacers/EmonHubSMASolarInterfacer.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-200.30
      key: home-energy
      name: Home Energy
      url: /capabilities/home-energy/
      via_parent: null
    credit: null
    layer: domain
    name: Sunamp
    provider: sunamp
    says: ships the Sunamp SDK or integration code
    source: https://github.com/openenergymonitor/emonhub/blob/master/src/interfacers/EmonHubSunampInterfacer.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-200.30
      key: home-energy
      name: Home Energy
      url: /capabilities/home-energy/
      via_parent: null
    credit: null
    layer: domain
    name: Tesla Powerwall
    provider: tesla-energy
    says: ships the Tesla Powerwall SDK or integration code
    source: https://github.com/openenergymonitor/emonhub/blob/master/src/interfacers/EmonHubTeslaPowerWallInterfacer.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-200.30
      key: home-energy
      name: Home Energy
      url: /capabilities/home-energy/
      via_parent: null
    credit: null
    layer: domain
    name: Victron Energy (VE.Direct)
    provider: victron-energy
    says: ships the Victron Energy (VE.Direct) SDK or integration code
    source: https://github.com/openenergymonitor/emonhub/blob/master/src/interfacers/EmonHubVEDirectInterfacer.py
    tier: observed
  kind: self-hosted
  name: OpenEnergyMonitor (emonHub)
  page: /applications/solar-energy-monitoring/openenergymonitor-emonhub/
  slug: openenergymonitor-emonhub
  url: https://github.com/openenergymonitor/emonhub
- anchor: pvoutput
  counts:
    declared: 22
    observed: 0
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
    layer: domain
    name: Zevercloud (Zeversolar)
    provider: zeversolar
    says: lists Zevercloud (Zeversolar) as an integration
    source: https://pvoutput.org/help/auto_uploader.html
    tier: declared
  kind: commercial
  name: PVOutput
  page: /applications/solar-energy-monitoring/pvoutput/
  slug: pvoutput
  url: https://pvoutput.org/
- anchor: enphase-app-(enlighten)
  counts:
    declared: 0
    observed: 4
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.enphaseenergy.myenlighten/latest/
  - route: store listing
    url: https://play.google.com/store/apps/details?id=com.enphaseenergy.myenlighten
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Firebase
    provider: firebase
    says: ships the Firebase SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.enphaseenergy.myenlighten/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Firebase
    provider: firebase
    says: ships the Firebase SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.enphaseenergy.myenlighten/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Google Analytics
    provider: google-analytics
    says: ships the Google Analytics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.enphaseenergy.myenlighten/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-911
      key: AE-911
      name: Tag Management
      url: /capabilities/product-telemetry-instrumentation/
      via_parent: Product Telemetry Instrumentation
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Google Tag Manager
    provider: google-tag-manager
    says: ships the Google Tag Manager SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.enphaseenergy.myenlighten/latest/
    tier: observed
  kind: commercial
  name: Enphase App (Enlighten)
  page: /applications/solar-energy-monitoring/enphase-app-enlighten/
  slug: enphase-app-enlighten
  url: https://enphase.com/
- anchor: mysolaredge
  counts:
    declared: 0
    observed: 2
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.solaredge.homeowner/latest/
  - route: store listing
    url: https://play.google.com/store/apps/details?id=com.solaredge.homeowner
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Firebase
    provider: firebase
    says: ships the Firebase SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.solaredge.homeowner/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Firebase
    provider: firebase
    says: ships the Firebase SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.solaredge.homeowner/latest/
    tier: observed
  kind: commercial
  name: mySolarEdge
  page: /applications/solar-energy-monitoring/mysolaredge/
  slug: mysolaredge
  url: https://www.solaredge.com/
- anchor: sense
  counts:
    declared: 0
    observed: 6
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.sense.androidclient/latest/
  - route: store listing
    url: https://play.google.com/store/apps/details?id=com.sense.androidclient
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Amplitude
    provider: amplitude
    says: ships the Amplitude SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.sense.androidclient/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Firebase
    provider: firebase
    says: ships the Firebase SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.sense.androidclient/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Firebase
    provider: firebase
    says: ships the Firebase SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.sense.androidclient/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Google Analytics
    provider: google-analytics
    says: ships the Google Analytics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.sense.androidclient/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-911
      key: AE-911
      name: Tag Management
      url: /capabilities/product-telemetry-instrumentation/
      via_parent: Product Telemetry Instrumentation
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Google Tag Manager
    provider: google-tag-manager
    says: ships the Google Tag Manager SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.sense.androidclient/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-430.50
      key: customer-feedback-management
      name: Customer Feedback Management
      url: /capabilities/customer-feedback-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Wootric
    provider: wootric
    says: ships the Wootric SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.sense.androidclient/latest/
    tier: observed
  kind: commercial
  name: Sense
  page: /applications/solar-energy-monitoring/sense/
  slug: sense
  url: https://sense.com/
author: API Evangelist
candidates: []
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
html: public
id: solar-energy-monitoring
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: House & Home
  store: google-play
  url: https://play.google.com/store/apps/category/HOUSE_AND_HOME
- category: Tools
  store: google-play
  url: https://play.google.com/store/apps/category/TOOLS
- category: Business
  store: google-play
  url: https://play.google.com/store/apps/category/BUSINESS
- category: Energy
  store: home-assistant-integrations
  url: https://www.home-assistant.io/integrations/#energy
name: Home Energy & Solar Monitoring
needs:
- capability:
    attribution: API Evangelist extension
    id: AE-200.30
    key: home-energy
    name: Home Energy
    url: /capabilities/home-energy/
    via_parent: null
  fit: exact
  layer: domain
  why: inverter, battery and meter clouds/drivers are what a solar monitor reads
- capability:
    attribution: API Evangelist extension
    id: AE-200.30.10
    key: AE-200.30.10
    name: Dynamic Electricity Tariffs
    url: /capabilities/home-energy/
    via_parent: Home Energy
  fit: exact
  layer: domain
  why: import/export prices drive savings figures and battery scheduling
- capability:
    attribution: Turbo EA
    id: BC-3840.60
    key: der-forecasting
    name: DER Forecasting
    url: /capabilities/der-forecasting/
    via_parent: null
  fit: exact
  layer: domain
  why: solar production forecasts plan battery charge and show expected yield
- capability:
    attribution: API Evangelist extension
    id: AE-230.10
    key: weather-environment
    name: Weather & Environment
    url: /capabilities/weather-environment/
    via_parent: null
  fit: exact
  layer: domain
  why: temperature and weather are logged next to yield and feed forecasts
- capability:
    attribution: API Evangelist extension
    id: AE-230.80
    key: grid-carbon-intensity
    name: Grid Carbon Intensity
    url: /capabilities/grid-carbon-intensity/
    via_parent: null
  fit: exact
  layer: domain
  why: carbon-aware charge/discharge planning
- capability:
    attribution: Turbo EA
    id: BC-3840.20
    key: virtual-power-plant-operations
    name: Virtual Power Plant Operations
    url: /capabilities/virtual-power-plant-operations/
    via_parent: null
  fit: exact
  layer: domain
  why: home batteries enrolled in VPP / demand-flex events
- capability:
    attribution: API Evangelist extension
    id: AE-200.20.20
    key: AE-200.20.20
    name: EV Charging
    url: /capabilities/connected-vehicles/
    via_parent: Connected Vehicles
  fit: exact
  layer: domain
  why: EV chargers are the largest controllable home load for solar surplus
- capability:
    attribution: API Evangelist extension
    id: AE-200.20.10
    key: AE-200.20.10
    name: Vehicle Data Access
    url: /capabilities/connected-vehicles/
    via_parent: Connected Vehicles
  fit: exact
  layer: domain
  why: vehicle state of charge for solar-surplus charging
- capability:
    attribution: API Evangelist extension
    id: AE-200.10
    key: smart-home
    name: Smart Home
    url: /capabilities/smart-home/
    via_parent: null
  fit: exact
  layer: common
  why: the monitor runs inside or alongside a home-automation hub
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  fit: exact
  layer: agent
  why: bring-your-own LLM chat over the energy plan
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.40
    key: AE-110.10.40
    name: On-Device & Edge Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  fit: exact
  layer: agent
  why: local LLM option for the same chat
- capability:
    attribution: API Evangelist extension
    id: AE-120.10
    key: geocoding
    name: Geocoding
    url: /capabilities/geocoding/
    via_parent: null
  fit: exact
  layer: common
  why: postcode to coordinates for forecasts and regional tariffs
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: nearest
  layer: common
  why: 'time-series storage of energy readings (nearest: no time-series storage node)'
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: exact
  layer: common
  why: app telemetry in the Android apps
- capability:
    attribution: API Evangelist extension
    id: AE-911
    key: AE-911
    name: Tag Management
    url: /capabilities/product-telemetry-instrumentation/
    via_parent: Product Telemetry Instrumentation
  fit: exact
  layer: common
  why: marketing tags on storefronts
- capability:
    attribution: Turbo EA
    id: BC-430.50
    key: customer-feedback-management
    name: Customer Feedback Management
    url: /capabilities/customer-feedback-management/
    via_parent: null
  fit: exact
  layer: common
  why: in-app customer feedback
stack:
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-200.30
      key: home-energy
      name: Home Energy
      url: /capabilities/home-energy/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 31.2
      apps:
      - OpenEMS
      - OpenEnergyMonitor (emonHub)
      - PVOutput
      band: developing
      in_catalog: true
      kin_score: 46.9
      mcp:
        status: unknown
      name: Tesla Powerwall
      slug: tesla-energy
      sources:
      - https://github.com/OpenEMS/openems/tree/develop/io.openems.edge.tesla.powerwall2
      - https://github.com/openenergymonitor/emonhub/blob/master/src/interfacers/EmonHubTeslaPowerWallInterfacer.py
      - https://pvoutput.org/help/service_integration.html
      status: profiled
      tags:
      - Battery Storage
      - Clean Energy
      - Energy
      - Solar
      tier: observed
      url: /providers/tesla-energy/
    - agent_band: agent-aware
      agent_readiness: 14.5
      apps:
      - OpenEMS
      - OpenEnergyMonitor (emonHub)
      - PVOutput
      band: thin
      in_catalog: true
      kin_score: 32.3
      mcp:
        status: unknown
      name: SMA Solar Technology
      slug: sma-solar
      sources:
      - https://github.com/OpenEMS/openems/tree/develop/io.openems.edge.sma
      - https://github.com/openenergymonitor/emonhub/blob/master/src/interfacers/EmonHubSMASolarInterfacer.py
      - https://pvoutput.org/help/auto_uploader.html
      status: profiled
      tags:
      - Company
      - Energy
      - Inverters
      - Solar
      tier: observed
      url: /providers/sma-solar/
    - agent_band: agent-ready
      agent_readiness: 35.2
      apps:
      - PVOutput
      - Predbat
      band: exemplar
      in_catalog: true
      kin_score: 68.6
      mcp:
        status: none
      name: Enphase Energy
      slug: enphase
      sources:
      - https://github.com/springfall2008/batpred/blob/main/apps/predbat/enphase.py
      - https://pvoutput.org/help/auto_uploader.html
      status: profiled
      tags:
      - DER
      - Energy
      - Solar
      - United States
      tier: observed
      url: /providers/enphase/
    - agent_band: agent-aware
      agent_readiness: 28.5
      apps:
      - OpenEMS
      - PVOutput
      band: developing
      in_catalog: true
      kin_score: 42.7
      mcp:
        status: none
      name: SolarEdge
      slug: solar-edge
      sources:
      - https://github.com/OpenEMS/openems/tree/develop/io.openems.edge.solaredge
      - https://pvoutput.org/help/auto_uploader.html
      status: profiled
      tags:
      - Energy
      - Monitoring
      - PV
      - Solar
      tier: observed
      url: /providers/solar-edge/
    - agent_band: agent-aware
      agent_readiness: 27.5
      apps:
      - OpenEMS
      - OpenEnergyMonitor (emonHub)
      band: thin
      in_catalog: true
      kin_score: 33.9
      mcp:
        status: none
      name: Victron Energy
      slug: victron-energy
      sources:
      - https://github.com/OpenEMS/openems/tree/develop/io.openems.edge.victron
      - https://github.com/openenergymonitor/emonhub/blob/master/src/interfacers/EmonHubVEDirectInterfacer.py
      status: profiled
      tags:
      - Company
      - Energy
      - Off-Grid
      - Renewables
      tier: observed
      url: /providers/victron-energy/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - OpenEMS
      - PVOutput
      band: emerging
      in_catalog: true
      kin_score: 15.9
      mcp:
        status: unchecked
      name: Solar-Log
      slug: solar-log
      sources:
      - https://github.com/OpenEMS/openems/tree/develop/io.openems.edge.pvinverter.solarlog
      - https://pvoutput.org/help/service_integration.html
      status: profiled
      tags:
      - Germany
      - Monitoring
      - Photovoltaics
      - Solar Energy
      tier: observed
      url: /providers/solar-log/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - OpenEMS
      - PVOutput
      band: emerging
      in_catalog: true
      kin_score: 12.3
      mcp:
        status: none
      name: Fronius
      slug: fronius
      sources:
      - https://github.com/OpenEMS/openems/tree/develop/io.openems.edge.fronius
      - https://pvoutput.org/help/push_services.html
      status: profiled
      tags:
      - Company
      - Energy
      - Solar
      - Welding
      tier: observed
      url: /providers/fronius/
    - agent_band: human-only
      agent_readiness: 4.4
      apps:
      - OpenEMS
      - OpenEnergyMonitor (emonHub)
      band: emerging
      in_catalog: true
      kin_score: 11.6
      mcp:
        source: https://shelly-api-docs.shelly.cloud/mcp
        status: verified
      name: Shelly
      slug: shelly
      sources:
      - https://github.com/OpenEMS/openems/tree/develop/io.openems.edge.io.shelly
      - https://github.com/openenergymonitor/emonhub/blob/master/src/interfacers/EmonHubShellyInterfacer.py
      status: profiled
      tags:
      - Company
      - Devices
      - IoT
      - Smart Home
      tier: observed
      url: /providers/shelly/
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - PVOutput
      - Predbat
      band: emerging
      in_catalog: true
      kin_score: 11.5
      mcp:
        status: unknown
      name: Growatt
      slug: growatt
      sources:
      - https://github.com/springfall2008/batpred/blob/main/apps/predbat/growatt.py
      - https://pvoutput.org/help/service_integration.html
      status: profiled
      tags:
      - Company
      - Consumer Technology
      - Energy
      - Solar
      tier: observed
      url: /providers/growatt/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - OpenEMS
      - PVOutput
      band: minimal
      in_catalog: true
      kin_score: 6.9
      mcp:
        status: unchecked
      name: KACO new energy
      slug: kaco-new-energy
      sources:
      - https://github.com/OpenEMS/openems/tree/develop/io.openems.edge.pvinverter.kaco.blueplanet
      - https://pvoutput.org/help/service_integration.html
      status: profiled
      tags:
      - Company
      - Energy Storage
      - Inverters
      - Solar
      tier: observed
      url: /providers/kaco-new-energy/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - OpenEMS
      - OpenEnergyMonitor (emonHub)
      band: minimal
      in_catalog: true
      kin_score: 2.5
      mcp:
        status: unchecked
      name: GoodWe
      slug: goodwe
      sources:
      - https://github.com/OpenEMS/openems/tree/develop/io.openems.edge.goodwe
      - https://github.com/openenergymonitor/emonhub/blob/master/src/interfacers/EmonHubGoodWeInterfacer.py
      status: profiled
      tags:
      - Company
      - Energy Storage
      - Inverters
      - Solar
      tier: observed
      url: /providers/goodwe/
    - agent_band: agent-ready
      agent_readiness: 50.2
      apps:
      - Predbat
      band: developing
      in_catalog: true
      kin_score: 53.6
      mcp:
        status: unchecked
      name: Teslemetry (Tesla Fleet API proxy, Powerwall)
      slug: teslemetry
      sources:
      - https://github.com/springfall2008/batpred/blob/main/apps/predbat/teslemetry.py
      status: profiled
      tags:
      - Company
      - Fleet API
      - Home Automation
      - Tesla
      tier: observed
      url: /providers/teslemetry/
    - agent_band: agent-aware
      agent_readiness: 18.7
      apps:
      - OpenEMS
      band: thin
      in_catalog: true
      kin_score: 30.3
      mcp:
        status: unchecked
      name: Discovergy (inexogy)
      slug: discovergy
      sources:
      - https://github.com/OpenEMS/openems/tree/develop/io.openems.edge.meter.discovergy
      status: profiled
      tags:
      - Company
      - Data Platform
      - Energy
      - Smart Metering
      tier: observed
      url: /providers/discovergy/
    - agent_band: agent-aware
      agent_readiness: 15.1
      apps:
      - Predbat
      band: thin
      in_catalog: true
      kin_score: 29.8
      mcp:
        status: unchecked
      name: SolisCloud (Ginlong)
      slug: soliscloud
      sources:
      - https://github.com/springfall2008/batpred/blob/main/apps/predbat/solis.py
      status: profiled
      tags:
      - Company
      - Monitoring
      - Software-as-a-Service
      - Solar
      tier: observed
      url: /providers/soliscloud/
    - agent_band: agent-aware
      agent_readiness: 22.2
      apps:
      - Predbat
      band: thin
      in_catalog: true
      kin_score: 29.6
      mcp:
        status: unchecked
      name: Hanchu ESS
      slug: hanchu-ess
      sources:
      - https://github.com/springfall2008/batpred/blob/main/apps/predbat/hanchu.py
      status: profiled
      tags:
      - Battery
      - Company
      - Energy
      - Storage
      tier: observed
      url: /providers/hanchu-ess/
    - agent_band: agent-aware
      agent_readiness: 5.3
      apps:
      - OpenEMS
      band: emerging
      in_catalog: true
      kin_score: 19.5
      mcp:
        status: unknown
      name: OpenDTU
      slug: opendtu
      sources:
      - https://github.com/OpenEMS/openems/tree/develop/io.openems.edge.meter.opendtu
      status: profiled
      tags:
      - Firmware
      - IoT
      - Open Source
      - Solar
      tier: observed
      url: /providers/opendtu/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - OpenEMS
      band: emerging
      in_catalog: true
      kin_score: 15.6
      mcp:
        status: unknown
      name: Huawei FusionSolar
      slug: huawei-fusionsolar
      sources:
      - https://github.com/OpenEMS/openems/tree/develop/io.openems.edge.huawei
      status: profiled
      tags:
      - Company
      - Energy
      - IoT
      - Solar
      tier: observed
      url: /providers/huawei-fusionsolar/
    - agent_band: agent-aware
      agent_readiness: 22.2
      apps:
      - Predbat
      band: emerging
      in_catalog: true
      kin_score: 13.6
      mcp:
        status: unchecked
      name: AlphaESS
      slug: alpha-ess
      sources:
      - https://github.com/springfall2008/batpred/blob/main/apps/predbat/alphaess.py
      status: profiled
      tags:
      - Battery
      - Company
      - Energy
      - Storage
      tier: observed
      url: /providers/alpha-ess/
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - OpenEMS
      band: emerging
      in_catalog: true
      kin_score: 11.3
      mcp:
        status: unchecked
      name: KOSTAL Solar Electric
      slug: kostal
      sources:
      - https://github.com/OpenEMS/openems/tree/develop/io.openems.edge.kostal
      status: profiled
      tags:
      - Company
      - Energy Storage
      - Inverters
      - Solar
      tier: observed
      url: /providers/kostal/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - OpenEMS
      band: minimal
      in_catalog: true
      kin_score: 10.0
      mcp:
        status: unchecked
      name: Sungrow
      slug: sungrow
      sources:
      - https://github.com/OpenEMS/openems/tree/develop/io.openems.edge.sungrow
      status: profiled
      tags:
      - Company
      - Energy Storage
      - Renewable Energy
      - Solar Inverters
      tier: observed
      url: /providers/sungrow/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Predbat
      band: minimal
      in_catalog: true
      kin_score: 9.6
      mcp:
        status: unchecked
      name: Deye Cloud
      slug: deye
      sources:
      - https://github.com/springfall2008/batpred/blob/main/apps/predbat/deye.py
      status: profiled
      tags:
      - Cloud Services
      - Developer Portal
      - Privacy
      - Security
      tier: observed
      url: /providers/deye/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Predbat
      band: minimal
      in_catalog: true
      kin_score: 9.3
      mcp:
        status: unchecked
      name: GivEnergy Cloud
      slug: givenergy
      sources:
      - https://github.com/springfall2008/batpred/blob/main/apps/predbat/gecloud.py
      status: profiled
      tags:
      - Battery
      - Energy
      - Renewables
      - Storage
      tier: observed
      url: /providers/givenergy/
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - OpenEnergyMonitor (emonHub)
      band: minimal
      in_catalog: true
      kin_score: 7.9
      mcp:
        status: unchecked
      name: Sunamp
      slug: sunamp
      sources:
      - https://github.com/openenergymonitor/emonhub/blob/master/src/interfacers/EmonHubSunampInterfacer.py
      status: profiled
      tags:
      - Company
      - Energy
      - Heat Batteries
      - Thermal Storage
      tier: observed
      url: /providers/sunamp/
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - OpenEnergyMonitor (emonHub)
      band: minimal
      in_catalog: true
      kin_score: 5.1
      mcp:
        status: unchecked
      name: Eastron (SDM120 meter)
      slug: eastron
      sources:
      - https://github.com/openenergymonitor/emonhub/blob/master/src/interfacers/EmonHubSDM120Interfacer.py
      status: profiled
      tags:
      - EV Charging
      - Electricity Meters
      - Energy Measurement
      - Smart Meter
      tier: observed
      url: /providers/eastron/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - OpenEMS
      band: minimal
      in_catalog: true
      kin_score: 5.0
      mcp:
        status: none
      name: BYD
      slug: byd
      sources:
      - https://github.com/OpenEMS/openems/tree/develop/io.openems.edge.battery.bydcommercial
      status: profiled
      tags:
      - Automotive
      - Company
      - Electric Vehicles
      - Technology
      tier: observed
      url: /providers/byd/
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - Predbat
      band: minimal
      in_catalog: true
      kin_score: 4.4
      mcp:
        status: unchecked
      name: SolaX Cloud
      slug: solax-power
      sources:
      - https://github.com/springfall2008/batpred/blob/main/apps/predbat/solax.py
      status: profiled
      tags:
      - Company
      - Energy
      - Monitoring
      - Solar
      tier: observed
      url: /providers/solax-power/
    - agent_band: agent-aware
      agent_readiness: 7.4
      apps:
      - OpenEnergyMonitor (emonHub)
      band: minimal
      in_catalog: true
      kin_score: 4.3
      mcp:
        status: unchecked
      name: Renogy
      slug: renogy
      sources:
      - https://github.com/openenergymonitor/emonhub/blob/master/src/interfacers/EmonHubModbusRenogyInterfacer.py
      status: profiled
      tags:
      - Company
      - Off-Grid
      - Renewable Energy
      - Solar
      tier: observed
      url: /providers/renogy/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - OpenEMS
      band: minimal
      in_catalog: true
      kin_score: 2.5
      mcp:
        status: unchecked
      name: Pylontech
      slug: pylontech
      sources:
      - https://github.com/OpenEMS/openems/tree/develop/io.openems.edge.battery.pylontech
      status: profiled
      tags:
      - Batteries
      - Company
      - Energy
      - Storage
      tier: observed
      url: /providers/pylontech/
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - Predbat
      band: minimal
      in_catalog: true
      kin_score: 0.4
      mcp:
        status: unchecked
      name: FoxESS Cloud
      slug: fox-ess
      sources:
      - https://github.com/springfall2008/batpred/blob/main/apps/predbat/fox.py
      status: profiled
      tags:
      - Company
      tier: observed
      url: /providers/fox-ess/
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - Predbat
      band: minimal
      in_catalog: true
      kin_score: 0.4
      mcp:
        status: unchecked
      name: Sigenergy
      slug: sigenergy
      sources:
      - https://github.com/springfall2008/batpred/blob/main/apps/predbat/sigenergy.py
      status: profiled
      tags:
      - Company
      tier: observed
      url: /providers/sigenergy/
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - Predbat
      band: minimal
      in_catalog: true
      kin_score: 0.4
      mcp:
        status: unchecked
      name: Sunsynk
      slug: sunsynk
      sources:
      - https://github.com/springfall2008/batpred/blob/main/apps/predbat/sunsynk.py
      status: profiled
      tags:
      - Company
      tier: observed
      url: /providers/sunsynk/
    - agent_band: agent-aware
      agent_readiness: 6.9
      apps:
      - PVOutput
      band: thin
      in_catalog: true
      kin_score: 27.7
      mcp:
        status: unchecked
      name: EKM Metering
      slug: ekm-metering
      sources:
      - https://pvoutput.org/help/auto_uploader.html
      status: profiled
      tags:
      - Company
      - Energy
      - IoT
      - Submetering
      tier: declared
      url: /providers/ekm-metering/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - PVOutput
      band: emerging
      in_catalog: true
      kin_score: 21.1
      mcp:
        status: unchecked
      name: Wattvision
      slug: wattvision
      sources:
      - https://pvoutput.org/help/auto_uploader.html
      status: profiled
      tags:
      - Billing
      - Company
      - Energy
      - Monitoring
      tier: declared
      url: /providers/wattvision/
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - PVOutput
      band: emerging
      in_catalog: true
      kin_score: 12.7
      mcp:
        status: unchecked
      name: Rainforest Automation (Eagle)
      slug: rainforest-automation
      sources:
      - https://pvoutput.org/help/auto_uploader.html
      status: profiled
      tags:
      - Automation
      - Energy
      - IoT
      - Smart Meter
      tier: declared
      url: /providers/rainforest-automation/
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - PVOutput
      band: minimal
      in_catalog: true
      kin_score: 10.8
      mcp:
        status: unchecked
      name: Flukso
      slug: flukso
      sources:
      - https://pvoutput.org/help/auto_uploader.html
      status: profiled
      tags:
      - Company
      - IoT
      - Monitoring
      - Utilities
      tier: declared
      url: /providers/flukso/
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - PVOutput
      band: minimal
      in_catalog: true
      kin_score: 8.5
      mcp:
        status: unchecked
      name: Zevercloud (Zeversolar)
      slug: zeversolar
      sources:
      - https://pvoutput.org/help/auto_uploader.html
      status: profiled
      tags:
      - Company
      - Energy
      - Germany
      - Solar
      tier: declared
      url: /providers/zeversolar/
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - PVOutput
      band: minimal
      in_catalog: true
      kin_score: 7.5
      mcp:
        status: unchecked
      name: Current Cost
      slug: current-cost
      sources:
      - https://pvoutput.org/help/service_integration.html
      status: profiled
      tags:
      - Company
      - Energy
      - IoT
      - Smart Home
      tier: declared
      url: /providers/current-cost/
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - PVOutput
      band: minimal
      in_catalog: true
      kin_score: 6.6
      mcp:
        status: unchecked
      name: Smappee
      slug: smappee
      sources:
      - https://pvoutput.org/help/auto_uploader.html
      status: profiled
      tags:
      - Energy
      - IoT
      - Smart Grid
      - Software-as-a-Service
      tier: declared
      url: /providers/smappee/
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - PVOutput
      band: minimal
      in_catalog: true
      kin_score: 6.4
      mcp:
        status: unchecked
      name: TED (The Energy Detective)
      slug: the-energy-detective
      sources:
      - https://pvoutput.org/help/auto_uploader.html
      status: profiled
      tags:
      - Company
      - Energy
      - Home Automation
      - Monitoring
      tier: declared
      url: /providers/the-energy-detective/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - PVOutput
      band: minimal
      in_catalog: true
      kin_score: 2.5
      mcp:
        status: unchecked
      name: Trannergy
      slug: trannergy
      sources:
      - https://pvoutput.org/help/auto_uploader.html
      status: profiled
      tags:
      - Analytics
      - Energy
      - IoT
      - Sustainability
      tier: declared
      url: /providers/trannergy/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - PVOutput
      band: minimal
      in_catalog: true
      kin_score: 0.4
      mcp:
        status: unchecked
      name: Efergy
      slug: efergy
      sources:
      - https://pvoutput.org/help/auto_uploader.html
      status: profiled
      tags:
      - Company
      tier: declared
      url: /providers/efergy/
    - agent_band: null
      agent_readiness: null
      apps:
      - PVOutput
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Energomonitor
      slug: energomonitor
      sources:
      - https://pvoutput.org/help/auto_uploader.html
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-200.30.10
      key: AE-200.30.10
      name: Dynamic Electricity Tariffs
      url: /capabilities/home-energy/
      via_parent: Home Energy
    providers:
    - agent_band: agent-native
      agent_readiness: 42.2
      apps:
      - Predbat
      band: strong
      in_catalog: true
      kin_score: 65.2
      mcp:
        status: none
      name: EDF Energy (Kraken API)
      slug: edf-energy
      sources:
      - https://github.com/springfall2008/batpred/blob/main/apps/predbat/kraken.py
      status: profiled
      tags:
      - Electricity
      - Energy
      - United Kingdom
      - Utilities
      tier: observed
      url: /providers/edf-energy/
    - agent_band: agent-aware
      agent_readiness: 25.6
      apps:
      - OpenEMS
      band: developing
      in_catalog: true
      kin_score: 49.5
      mcp:
        status: none
      name: Tibber
      slug: tibber
      sources:
      - https://github.com/OpenEMS/openems/tree/develop/io.openems.edge.timeofusetariff.tibber
      status: profiled
      tags:
      - ElectricityPricing
      - Energy
      - Smart Home
      - Smart Meter
      tier: observed
      url: /providers/tibber/
    - agent_band: agent-aware
      agent_readiness: 23.5
      apps:
      - Predbat
      band: developing
      in_catalog: true
      kin_score: 44.1
      mcp:
        status: none
      name: Octopus Energy
      slug: octopus-energy
      sources:
      - https://github.com/springfall2008/batpred/blob/main/apps/predbat/octopus.py
      status: profiled
      tags:
      - Electricity
      - Energy
      - Gas
      - Renewable Energy
      tier: observed
      url: /providers/octopus-energy/
    - agent_band: agent-aware
      agent_readiness: 28.4
      apps:
      - OpenEMS
      band: thin
      in_catalog: true
      kin_score: 26.8
      mcp:
        status: none
      name: aWATTar
      slug: awattar
      sources:
      - https://github.com/OpenEMS/openems/tree/develop/io.openems.edge.timeofusetariff.awattar
      status: profiled
      tags:
      - EPEX Spot
      - Electricity
      - Energy
      - Spot Price
      tier: observed
      url: /providers/awattar/
    - agent_band: agent-aware
      agent_readiness: 14.8
      apps:
      - Predbat
      band: emerging
      in_catalog: true
      kin_score: 24.8
      mcp:
        status: unknown
      name: E.ON Next (Kraken API)
      slug: eon-next
      sources:
      - https://github.com/springfall2008/batpred/blob/main/apps/predbat/kraken.py
      status: profiled
      tags:
      - Electricity
      - Energy
      - United Kingdom
      - Utilities
      tier: observed
      url: /providers/eon-next/
    - agent_band: agent-aware
      agent_readiness: 14.5
      apps:
      - Predbat
      band: emerging
      in_catalog: true
      kin_score: 16.2
      mcp:
        status: unchecked
      name: AgilePredict
      slug: agilepredict
      sources:
      - https://github.com/springfall2008/batpred/blob/main/apps/predbat/futurerate.py
      status: profiled
      tags:
      - Company
      - Electricity
      - Energy
      - Forecasting
      tier: observed
      url: /providers/agilepredict/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - OpenEMS
      band: minimal
      in_catalog: true
      kin_score: 10.7
      mcp:
        status: unchecked
      name: Stadtwerk Hassfurt
      slug: stadtwerk-hassfurt
      sources:
      - https://github.com/OpenEMS/openems/tree/develop/io.openems.edge.timeofusetariff.hassfurt
      status: profiled
      tags:
      - Energy
      - Germany
      - Municipal
      - Utilities
      tier: observed
      url: /providers/stadtwerk-hassfurt/
    - agent_band: human-only
      agent_readiness: 0.7
      apps:
      - OpenEMS
      band: minimal
      in_catalog: true
      kin_score: 10.6
      mcp:
        status: unknown
      name: Rabot Energy
      slug: rabotenergy
      sources:
      - https://github.com/OpenEMS/openems/tree/develop/io.openems.edge.timeofusetariff.rabotcharge
      status: profiled
      tags:
      - Company
      - Consumer
      - Electricity
      - Energy
      tier: observed
      url: /providers/rabotenergy/
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - OpenEMS
      band: minimal
      in_catalog: true
      kin_score: 9.0
      mcp:
        status: unchecked
      name: Corrently (STROMDAO)
      slug: corrently
      sources:
      - https://github.com/OpenEMS/openems/tree/develop/io.openems.edge.timeofusetariff.corrently
      status: profiled
      tags:
      - Energy
      - Germany
      - Renewables
      - Transparency
      tier: observed
      url: /providers/corrently/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - OpenEMS
      band: minimal
      in_catalog: true
      kin_score: 8.5
      mcp:
        status: unchecked
      name: Swisspower
      slug: swisspower
      sources:
      - https://github.com/OpenEMS/openems/tree/develop/io.openems.edge.timeofusetariff.swisspower
      status: profiled
      tags:
      - Alliance
      - Energy
      - Switzerland
      - Utilities
      tier: observed
      url: /providers/swisspower/
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - OpenEMS
      band: minimal
      in_catalog: true
      kin_score: 7.4
      mcp:
        status: unchecked
      name: EWS Elektrizitaetswerke Schoenau
      slug: ews-schoenau
      sources:
      - https://github.com/OpenEMS/openems/tree/develop/io.openems.edge.timeofusetariff.ews
      status: profiled
      tags:
      - Company
      - Cooperative
      - Energy
      - Renewables
      tier: observed
      url: /providers/ews-schoenau/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - OpenEMS
      band: minimal
      in_catalog: true
      kin_score: 5.9
      mcp:
        status: unchecked
      name: Luox Energy
      slug: luox-energy
      sources:
      - https://github.com/OpenEMS/openems/tree/develop/io.openems.edge.timeofusetariff.luox
      status: profiled
      tags:
      - Company
      - Energy
      - Renewables
      - Tariffs
      tier: observed
      url: /providers/luox-energy/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - OpenEMS
      band: minimal
      in_catalog: true
      kin_score: 3.1
      mcp:
        status: unknown
      name: Groupe E
      slug: groupe-e
      sources:
      - https://github.com/OpenEMS/openems/tree/develop/io.openems.edge.timeofusetariff.groupe
      status: profiled
      tags:
      - Company
      - Energy
      - Renewables
      - Switzerland
      tier: observed
      url: /providers/groupe-e/
  - capability:
      attribution: API Evangelist extension
      id: AE-230.10
      key: weather-environment
      name: Weather & Environment
      url: /capabilities/weather-environment/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 17.4
      apps:
      - OpenEMS
      - Predbat
      band: thin
      in_catalog: true
      kin_score: 28.3
      mcp:
        status: none
      name: Open-Meteo
      slug: open-meteo
      sources:
      - https://github.com/OpenEMS/openems/tree/develop/io.openems.edge.weather.openmeteo
      - https://github.com/springfall2008/batpred/blob/main/apps/predbat/solcast.py
      status: profiled
      tags:
      - Air Quality
      - Forecast
      - Historical Weather
      - Weather
      tier: observed
      url: /providers/open-meteo/
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - Predbat
      band: emerging
      in_catalog: true
      kin_score: 11.1
      mcp:
        status: unchecked
      name: MeteoAlarm (EUMETNET)
      slug: meteoalarm
      sources:
      - https://github.com/springfall2008/batpred/blob/main/apps/predbat/alertfeed.py
      status: profiled
      tags:
      - EarlyWarning
      - Europe
      - Public Service
      - Weather
      tier: observed
      url: /providers/meteoalarm/
    - agent_band: agent-ready
      agent_readiness: 30.0
      apps:
      - PVOutput
      band: strong
      in_catalog: true
      kin_score: 59.1
      mcp:
        source: https://mcp.openweathermap.org/
        status: verified
      name: OpenWeatherMap
      slug: openweathermap
      sources:
      - https://pvoutput.org/help/auto_uploader.html
      status: profiled
      tags:
      - Air Pollution
      - Climate
      - Forecast
      - Weather
      tier: declared
      url: /providers/openweathermap/
    - agent_band: agent-ready
      agent_readiness: 31.3
      apps:
      - PVOutput
      band: thin
      in_catalog: true
      kin_score: 34.9
      mcp:
        status: none
      name: Weather Underground
      slug: wunderground
      sources:
      - https://pvoutput.org/help/auto_uploader.html
      status: profiled
      tags:
      - Hyperlocal
      - Observations
      - Personal Weather Stations
      - Weather
      tier: declared
      url: /providers/wunderground/
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - PVOutput
      band: minimal
      in_catalog: true
      kin_score: 3.2
      mcp:
        status: unchecked
      name: Ambient Weather
      slug: ambient-weather
      sources:
      - https://pvoutput.org/help/auto_uploader.html
      status: profiled
      tags:
      - Company
      - Dashboards
      - IoT
      - Weather
      tier: declared
      url: /providers/ambient-weather/
  - capability:
      attribution: API Evangelist extension
      id: AE-200.20.20
      key: AE-200.20.20
      name: EV Charging
      url: /capabilities/connected-vehicles/
      via_parent: Connected Vehicles
    providers:
    - agent_band: agent-ready
      agent_readiness: 40.9
      apps:
      - Predbat
      band: thin
      in_catalog: true
      kin_score: 38.6
      mcp:
        status: unchecked
      name: myenergi
      slug: myenergi
      sources:
      - https://github.com/springfall2008/batpred/blob/main/apps/predbat/myenergi.py
      status: profiled
      tags:
      - Company
      - EV Charging
      - Renewable Energy
      - Solar
      tier: observed
      url: /providers/myenergi/
    - agent_band: agent-aware
      agent_readiness: 21.8
      apps:
      - Predbat
      band: thin
      in_catalog: true
      kin_score: 35.9
      mcp:
        status: unchecked
      name: Hypervolt
      slug: hypervolt
      sources:
      - https://github.com/springfall2008/batpred/blob/main/apps/predbat/hypervolt.py
      status: profiled
      tags:
      - Chargers
      - Company
      - Electric Vehicles
      - United Kingdom
      tier: observed
      url: /providers/hypervolt/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Predbat
      band: emerging
      in_catalog: true
      kin_score: 16.0
      mcp:
        status: unknown
      name: Wallbox
      slug: wallbox
      sources:
      - https://github.com/springfall2008/batpred/blob/main/apps/predbat/wallbox.py
      status: profiled
      tags:
      - Company
      - EV Charging
      - Energy Management
      - Smart Hardware
      tier: observed
      url: /providers/wallbox/
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - Predbat
      band: minimal
      in_catalog: true
      kin_score: 7.7
      mcp:
        status: unchecked
      name: Ohme
      slug: ohme
      sources:
      - https://github.com/springfall2008/batpred/blob/main/apps/predbat/ohme.py
      status: profiled
      tags:
      - EV Charging
      - Home Chargers
      - Mobility Solutions
      - Smart Charging
      tier: observed
      url: /providers/ohme/
  - capability:
      attribution: Turbo EA
      id: BC-3840.60
      key: der-forecasting
      name: DER Forecasting
      url: /capabilities/der-forecasting/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 29.6
      apps:
      - Predbat
      band: developing
      in_catalog: true
      kin_score: 53.7
      mcp:
        status: none
      name: Solcast
      slug: solcast
      sources:
      - https://github.com/springfall2008/batpred/blob/main/apps/predbat/solcast.py
      status: profiled
      tags:
      - Energy
      - Forecasting
      - Irradiance
      - Solar
      tier: observed
      url: /providers/solcast/
    - agent_band: agent-ready
      agent_readiness: 29.0
      apps:
      - Predbat
      band: thin
      in_catalog: true
      kin_score: 35.4
      mcp:
        status: unknown
      name: Forecast.Solar
      slug: forecast-solar
      sources:
      - https://github.com/springfall2008/batpred/blob/main/apps/predbat/solcast.py
      status: profiled
      tags:
      - Company
      - Forecast
      - Renewable Energy
      - Solar
      tier: observed
      url: /providers/forecast-solar/
  - capability:
      attribution: API Evangelist extension
      id: AE-200.20.10
      key: AE-200.20.10
      name: Vehicle Data Access
      url: /capabilities/connected-vehicles/
      via_parent: Connected Vehicles
    providers:
    - agent_band: agent-aware
      agent_readiness: 26.7
      apps:
      - OpenEnergyMonitor (emonHub)
      band: thin
      in_catalog: true
      kin_score: 28.9
      mcp:
        source: https://api.bmw.com/mcp
        status: documented
      name: BMW ConnectedDrive
      slug: bmw-connecteddrive
      sources:
      - https://github.com/openenergymonitor/emonhub/blob/master/src/interfacers/EmonHubBMWInterfacer.py
      status: profiled
      tags:
      - Automotive
      - Connected Vehicles
      - Telematics
      - Vehicle Data
      tier: observed
      url: /providers/bmw-connecteddrive/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - OpenEnergyMonitor (emonHub)
      band: emerging
      in_catalog: true
      kin_score: 13.6
      mcp:
        status: unknown
      name: Jaguar Land Rover
      slug: jlr
      sources:
      - https://github.com/openenergymonitor/emonhub/blob/master/src/interfacers/EmonHubJaguarLandRoverInterfacer.py
      status: profiled
      tags:
      - Automotive
      - Company
      - Connected Vehicles
      - Vehicle Data
      tier: observed
      url: /providers/jlr/
  - capability:
      attribution: API Evangelist extension
      id: AE-230.80
      key: grid-carbon-intensity
      name: Grid Carbon Intensity
      url: /capabilities/grid-carbon-intensity/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 29.4
      apps:
      - Predbat
      band: thin
      in_catalog: true
      kin_score: 31.3
      mcp:
        status: none
      name: Carbon Intensity API (NESO)
      slug: carbon-intensity
      sources:
      - https://github.com/springfall2008/batpred/blob/main/apps/predbat/carbon.py
      status: profiled
      tags:
      - Carbon Intensity
      - Electricity
      - Energy
      - Environment
      tier: observed
      url: /providers/carbon-intensity/
  - capability:
      attribution: Turbo EA
      id: BC-3840.20
      key: virtual-power-plant-operations
      name: Virtual Power Plant Operations
      url: /capabilities/virtual-power-plant-operations/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 32.9
      apps:
      - Predbat
      band: developing
      in_catalog: true
      kin_score: 44.2
      mcp:
        status: none
      name: Axle Energy
      slug: axle-energy
      sources:
      - https://github.com/springfall2008/batpred/blob/main/apps/predbat/axle.py
      status: profiled
      tags:
      - Company
      - Energy
      - Flexibility
      - Virtual Power Plant
      tier: observed
      url: /providers/axle-energy/
  layer: domain
- capabilities:
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 39.9
      apps:
      - Enphase App (Enlighten)
      - Sense
      - mySolarEdge
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: &id001
        source: https://firebase.google.com/docs/ai-assistance/mcp-server
        status: verified
      name: Firebase
      slug: google-firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.enphaseenergy.myenlighten/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.sense.androidclient/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.solaredge.homeowner/latest/
      status: profiled
      tags: &id002
      - Analytics
      - Authentication
      - Backend-as-a-Service
      - Cloud Messaging
      tier: observed
      url: /providers/google-firebase/
    - agent_band: agent-ready
      agent_readiness: 42.9
      apps:
      - Enphase App (Enlighten)
      - Sense
      band: exemplar
      in_catalog: true
      kin_score: 79.7
      mcp:
        source: https://developers.google.com/analytics/devguides/MCP
        status: verified
      name: Google Analytics
      slug: google-analytics
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.enphaseenergy.myenlighten/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.sense.androidclient/latest/
      status: profiled
      tags:
      - Analytics
      - Data
      - Google
      - Metrics
      tier: observed
      url: /providers/google-analytics/
    - agent_band: agent-ready
      agent_readiness: 56.9
      apps:
      - Sense
      band: strong
      in_catalog: true
      kin_score: 65.2
      mcp:
        source: https://amplitude.com/docs/amplitude-ai/amplitude-mcp
        status: verified
      name: Amplitude
      slug: amplitude
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.sense.androidclient/latest/
      status: profiled
      tags:
      - A/B Testing
      - Analytics
      - Experimentation
      - Feature Flags
      tier: observed
      url: /providers/amplitude/
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 39.9
      apps:
      - Enphase App (Enlighten)
      - Sense
      - mySolarEdge
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: *id001
      name: Firebase
      slug: google-firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.enphaseenergy.myenlighten/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.sense.androidclient/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.solaredge.homeowner/latest/
      status: profiled
      tags: *id002
      tier: observed
      url: /providers/google-firebase/
    - agent_band: agent-ready
      agent_readiness: 34.4
      apps:
      - OpenEMS
      - OpenEnergyMonitor (emonHub)
      band: strong
      in_catalog: true
      kin_score: 63.3
      mcp:
        source: https://github.com/influxdata/influxdb3_mcp_server
        status: verified
      name: InfluxDB
      slug: influxdata
      sources:
      - https://github.com/OpenEMS/openems/tree/develop/io.openems.edge.timedata.influxdb
      - https://github.com/openenergymonitor/emonhub/blob/master/src/interfacers/EmonHubInfluxInterfacer.py
      status: profiled
      tags:
      - Database
      - Monitoring
      - Observability
      - Time Series Database
      tier: observed
      url: /providers/influxdata/
  - capability:
      attribution: API Evangelist extension
      id: AE-911
      key: AE-911
      name: Tag Management
      url: /capabilities/product-telemetry-instrumentation/
      via_parent: Product Telemetry Instrumentation
    providers:
    - agent_band: agent-ready
      agent_readiness: 35.8
      apps:
      - Enphase App (Enlighten)
      - Sense
      band: strong
      in_catalog: true
      kin_score: 65.8
      mcp:
        status: none
      name: Google Tag Manager
      slug: google-tag-manager
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.enphaseenergy.myenlighten/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.sense.androidclient/latest/
      status: profiled
      tags:
      - Analytics
      - Conversion Tracking
      - Marketing
      - Tag Management
      tier: observed
      url: /providers/google-tag-manager/
  - capability:
      attribution: Turbo EA
      id: BC-430.50
      key: customer-feedback-management
      name: Customer Feedback Management
      url: /capabilities/customer-feedback-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 25.6
      apps:
      - Sense
      band: thin
      in_catalog: true
      kin_score: 32.4
      mcp:
        status: none
      name: Wootric
      slug: wootric
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.sense.androidclient/latest/
      status: profiled
      tags:
      - CES
      - CSAT
      - Customer Experience
      - NPS
      tier: observed
      url: /providers/wootric/
  - capability:
      attribution: API Evangelist extension
      id: AE-120.10
      key: geocoding
      name: Geocoding
      url: /capabilities/geocoding/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 0.7
      apps:
      - Predbat
      band: minimal
      in_catalog: true
      kin_score: 4.8
      mcp:
        status: unknown
      name: Postcodes.io
      slug: postcodes-io
      sources:
      - https://github.com/springfall2008/batpred/blob/main/apps/predbat/solcast.py
      status: profiled
      tags:
      - Geocoding
      - Public APIs
      tier: observed
      url: /providers/postcodes-io/
  - capability:
      attribution: API Evangelist extension
      id: AE-200.10
      key: smart-home
      name: Smart Home
      url: /capabilities/smart-home/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 5.6
      apps:
      - Predbat
      band: thin
      in_catalog: true
      kin_score: 34.5
      mcp:
        source: https://www.home-assistant.io/integrations/mcp_server/
        status: verified
      name: Home Assistant
      slug: home-assistant
      sources:
      - https://github.com/springfall2008/batpred/blob/main/apps/predbat/ha.py
      status: profiled
      tags:
      - Community
      - Home Automation
      - IoT
      - Open Source
      tier: observed
      url: /providers/home-assistant/
  layer: common
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    providers:
    - agent_band: agent-native
      agent_readiness: 57.5
      apps:
      - Predbat
      band: exemplar
      in_catalog: true
      kin_score: 82.5
      mcp:
        source: https://platform.openai.com/docs/mcp
        status: verified
      name: OpenAI
      slug: openai
      sources:
      - https://github.com/springfall2008/batpred/blob/main/apps/predbat/chat.py
      status: profiled
      tags:
      - Artificial Intelligence
      - Generative AI
      - LLM
      - OpenAI
      tier: observed
      url: /providers/openai/
    - agent_band: agent-ready
      agent_readiness: 46.4
      apps:
      - Predbat
      band: strong
      in_catalog: true
      kin_score: 54.8
      mcp:
        source: https://openrouter.ai/docs/guides/overview/mcp-server
        status: verified
      name: OpenRouter
      slug: openrouter
      sources:
      - https://github.com/springfall2008/batpred/blob/main/apps/predbat/chat.py
      status: profiled
      tags:
      - Artificial Intelligence
      - Gateways
      - LLM
      - Router
      tier: observed
      url: /providers/openrouter/
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.40
      key: AE-110.10.40
      name: On-Device & Edge Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    providers:
    - agent_band: agent-aware
      agent_readiness: 24.4
      apps:
      - Predbat
      band: thin
      in_catalog: true
      kin_score: 37.7
      mcp:
        status: none
      name: Ollama
      slug: ollama
      sources:
      - https://github.com/springfall2008/batpred/blob/main/apps/predbat/chat.py
      status: profiled
      tags:
      - Artificial Intelligence
      - LLM
      - Models
      - Ollama
      tier: observed
      url: /providers/ollama/
  layer: agent
summary:
  coverage_pct: 98.8
  declared_only: 14
  distinct_providers: 81
  in_catalog: 80
  mcp:
    documented: 1
    none: 17
    unchecked: 42
    verified: 9
  mcp_verified: 9
  mean_kin_score: 24.5
  observed: 67
  queued: 1
  reference_apps: 7
title: 'Home Energy & Solar Monitoring: application blueprint'
---
