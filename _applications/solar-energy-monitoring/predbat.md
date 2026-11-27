---
app: Predbat
app_slug: predbat
app_url: https://github.com/springfall2008/batpred
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-3840.60
  key: der-forecasting
  layer: domain
  name: DER Forecasting
  providers:
  - Forecast.Solar
  - Solcast
  url: /capabilities/der-forecasting/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-200.30.10
  key: AE-200.30.10
  layer: domain
  name: Dynamic Electricity Tariffs
  providers:
  - AgilePredict
  - E.ON Next (Kraken API)
  - EDF Energy (Kraken API)
  - Octopus Energy
  url: /capabilities/home-energy/
  via_parent: Home Energy
- attribution: API Evangelist extension
  id: AE-200.20.20
  key: AE-200.20.20
  layer: domain
  name: EV Charging
  providers:
  - Hypervolt
  - myenergi
  - Ohme
  - Wallbox
  url: /capabilities/connected-vehicles/
  via_parent: Connected Vehicles
- attribution: API Evangelist extension
  id: AE-230.80
  key: grid-carbon-intensity
  layer: domain
  name: Grid Carbon Intensity
  providers:
  - Carbon Intensity API (NESO)
  url: /capabilities/grid-carbon-intensity/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-200.30
  key: home-energy
  layer: domain
  name: Home Energy
  providers:
  - AlphaESS
  - Deye Cloud
  - Enphase Energy
  - FoxESS Cloud
  - GivEnergy Cloud
  - Growatt
  - Hanchu ESS
  - Sigenergy
  - SolaX Cloud
  - SolisCloud (Ginlong)
  - Sunsynk
  - Teslemetry (Tesla Fleet API proxy, Powerwall)
  url: /capabilities/home-energy/
  via_parent: null
- attribution: Turbo EA
  id: BC-3840.20
  key: virtual-power-plant-operations
  layer: domain
  name: Virtual Power Plant Operations
  providers:
  - Axle Energy
  url: /capabilities/virtual-power-plant-operations/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-230.10
  key: weather-environment
  layer: domain
  name: Weather & Environment
  providers:
  - MeteoAlarm (EUMETNET)
  - Open-Meteo
  url: /capabilities/weather-environment/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-120.10
  key: geocoding
  layer: common
  name: Geocoding
  providers:
  - Postcodes.io
  url: /capabilities/geocoding/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-200.10
  key: smart-home
  layer: common
  name: Smart Home
  providers:
  - Home Assistant
  url: /capabilities/smart-home/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-110.10.10
  key: AE-110.10.10
  layer: agent
  name: Hosted LLM Inference
  providers:
  - OpenAI
  - OpenRouter
  url: /capabilities/model-inference/
  via_parent: Model Inference
- attribution: API Evangelist extension
  id: AE-110.10.40
  key: AE-110.10.40
  layer: agent
  name: On-Device & Edge Inference
  providers:
  - Ollama
  url: /capabilities/model-inference/
  via_parent: Model Inference
category:
  id: solar-energy-monitoring
  name: Home Energy & Solar Monitoring
  url: /applications/solar-energy-monitoring/
counts:
  declared: 0
  observed: 31
credits: []
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
  facts:
    agent_band: agent-aware
    agent_readiness: 14.5
    band: emerging
    in_catalog: true
    kin_score: 16.2
    mcp: &id001
      status: unchecked
    slug: agilepredict
    status: profiled
    tags: &id002
    - Company
    - Electricity
    - Energy
    - Forecasting
    url: /providers/agilepredict/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 22.2
    band: emerging
    in_catalog: true
    kin_score: 13.6
    mcp: &id003
      status: unchecked
    slug: alpha-ess
    status: profiled
    tags: &id004
    - Battery
    - Company
    - Energy
    - Storage
    url: /providers/alpha-ess/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 32.9
    band: developing
    in_catalog: true
    kin_score: 44.2
    mcp: &id005
      status: none
    slug: axle-energy
    status: profiled
    tags: &id006
    - Company
    - Energy
    - Flexibility
    - Virtual Power Plant
    url: /providers/axle-energy/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 29.4
    band: thin
    in_catalog: true
    kin_score: 31.3
    mcp: &id007
      status: none
    slug: carbon-intensity
    status: profiled
    tags: &id008
    - Carbon Intensity
    - Electricity
    - Energy
    - Environment
    url: /providers/carbon-intensity/
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
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 9.6
    mcp: &id009
      status: unchecked
    slug: deye
    status: profiled
    tags: &id010
    - Cloud Services
    - Developer Portal
    - Privacy
    - Security
    url: /providers/deye/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 14.8
    band: emerging
    in_catalog: true
    kin_score: 24.8
    mcp: &id011
      status: unknown
    slug: eon-next
    status: profiled
    tags: &id012
    - Electricity
    - Energy
    - United Kingdom
    - Utilities
    url: /providers/eon-next/
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
  facts:
    agent_band: agent-native
    agent_readiness: 42.2
    band: strong
    in_catalog: true
    kin_score: 65.2
    mcp: &id013
      status: none
    slug: edf-energy
    status: profiled
    tags: &id014
    - Electricity
    - Energy
    - United Kingdom
    - Utilities
    url: /providers/edf-energy/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 35.2
    band: exemplar
    in_catalog: true
    kin_score: 68.6
    mcp: &id015
      status: none
    slug: enphase
    status: profiled
    tags: &id016
    - DER
    - Energy
    - Solar
    - United States
    url: /providers/enphase/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 29.0
    band: thin
    in_catalog: true
    kin_score: 35.4
    mcp: &id017
      status: unknown
    slug: forecast-solar
    status: profiled
    tags: &id018
    - Company
    - Forecast
    - Renewable Energy
    - Solar
    url: /providers/forecast-solar/
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
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: minimal
    in_catalog: true
    kin_score: 0.4
    mcp: &id019
      status: unchecked
    slug: fox-ess
    status: profiled
    tags: &id020
    - Company
    url: /providers/fox-ess/
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
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 9.3
    mcp: &id021
      status: unchecked
    slug: givenergy
    status: profiled
    tags: &id022
    - Battery
    - Energy
    - Renewables
    - Storage
    url: /providers/givenergy/
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
  facts:
    agent_band: human-only
    agent_readiness: 2.5
    band: emerging
    in_catalog: true
    kin_score: 11.5
    mcp: &id023
      status: unknown
    slug: growatt
    status: profiled
    tags: &id024
    - Company
    - Consumer Technology
    - Energy
    - Solar
    url: /providers/growatt/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 22.2
    band: thin
    in_catalog: true
    kin_score: 29.6
    mcp: &id025
      status: unchecked
    slug: hanchu-ess
    status: profiled
    tags: &id026
    - Battery
    - Company
    - Energy
    - Storage
    url: /providers/hanchu-ess/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 5.6
    band: thin
    in_catalog: true
    kin_score: 34.5
    mcp: &id027
      source: https://www.home-assistant.io/integrations/mcp_server/
      status: verified
    slug: home-assistant
    status: profiled
    tags: &id028
    - Community
    - Home Automation
    - IoT
    - Open Source
    url: /providers/home-assistant/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 21.8
    band: thin
    in_catalog: true
    kin_score: 35.9
    mcp: &id029
      status: unchecked
    slug: hypervolt
    status: profiled
    tags: &id030
    - Chargers
    - Company
    - Electric Vehicles
    - United Kingdom
    url: /providers/hypervolt/
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
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: emerging
    in_catalog: true
    kin_score: 11.1
    mcp: &id031
      status: unchecked
    slug: meteoalarm
    status: profiled
    tags: &id032
    - EarlyWarning
    - Europe
    - Public Service
    - Weather
    url: /providers/meteoalarm/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 40.9
    band: thin
    in_catalog: true
    kin_score: 38.6
    mcp: &id033
      status: unchecked
    slug: myenergi
    status: profiled
    tags: &id034
    - Company
    - EV Charging
    - Renewable Energy
    - Solar
    url: /providers/myenergi/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 23.5
    band: developing
    in_catalog: true
    kin_score: 44.1
    mcp: &id035
      status: none
    slug: octopus-energy
    status: profiled
    tags: &id036
    - Electricity
    - Energy
    - Gas
    - Renewable Energy
    url: /providers/octopus-energy/
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
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: minimal
    in_catalog: true
    kin_score: 7.7
    mcp: &id037
      status: unchecked
    slug: ohme
    status: profiled
    tags: &id038
    - EV Charging
    - Home Chargers
    - Mobility Solutions
    - Smart Charging
    url: /providers/ohme/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 24.4
    band: thin
    in_catalog: true
    kin_score: 37.7
    mcp: &id039
      status: none
    slug: ollama
    status: profiled
    tags: &id040
    - Artificial Intelligence
    - LLM
    - Models
    - Ollama
    url: /providers/ollama/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 17.4
    band: thin
    in_catalog: true
    kin_score: 28.3
    mcp: &id041
      status: none
    slug: open-meteo
    status: profiled
    tags: &id042
    - Air Quality
    - Forecast
    - Historical Weather
    - Weather
    url: /providers/open-meteo/
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
  facts:
    agent_band: agent-native
    agent_readiness: 57.5
    band: exemplar
    in_catalog: true
    kin_score: 82.5
    mcp: &id043
      source: https://platform.openai.com/docs/mcp
      status: verified
    slug: openai
    status: profiled
    tags: &id044
    - Artificial Intelligence
    - Generative AI
    - LLM
    - OpenAI
    url: /providers/openai/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 46.4
    band: strong
    in_catalog: true
    kin_score: 54.8
    mcp: &id045
      source: https://openrouter.ai/docs/guides/overview/mcp-server
      status: verified
    slug: openrouter
    status: profiled
    tags: &id046
    - Artificial Intelligence
    - Gateways
    - LLM
    - Router
    url: /providers/openrouter/
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
  facts:
    agent_band: human-only
    agent_readiness: 0.7
    band: minimal
    in_catalog: true
    kin_score: 4.8
    mcp: &id047
      status: unknown
    slug: postcodes-io
    status: profiled
    tags: &id048
    - Geocoding
    - Public APIs
    url: /providers/postcodes-io/
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
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: minimal
    in_catalog: true
    kin_score: 0.4
    mcp: &id049
      status: unchecked
    slug: sigenergy
    status: profiled
    tags: &id050
    - Company
    url: /providers/sigenergy/
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
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: minimal
    in_catalog: true
    kin_score: 4.4
    mcp: &id051
      status: unchecked
    slug: solax-power
    status: profiled
    tags: &id052
    - Company
    - Energy
    - Monitoring
    - Solar
    url: /providers/solax-power/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 29.6
    band: developing
    in_catalog: true
    kin_score: 53.7
    mcp: &id053
      status: none
    slug: solcast
    status: profiled
    tags: &id054
    - Energy
    - Forecasting
    - Irradiance
    - Solar
    url: /providers/solcast/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 15.1
    band: thin
    in_catalog: true
    kin_score: 29.8
    mcp: &id055
      status: unchecked
    slug: soliscloud
    status: profiled
    tags: &id056
    - Company
    - Monitoring
    - Software-as-a-Service
    - Solar
    url: /providers/soliscloud/
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
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: minimal
    in_catalog: true
    kin_score: 0.4
    mcp: &id057
      status: unchecked
    slug: sunsynk
    status: profiled
    tags: &id058
    - Company
    url: /providers/sunsynk/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 50.2
    band: developing
    in_catalog: true
    kin_score: 53.6
    mcp: &id059
      status: unchecked
    slug: teslemetry
    status: profiled
    tags: &id060
    - Company
    - Fleet API
    - Home Automation
    - Tesla
    url: /providers/teslemetry/
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
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 16.0
    mcp: &id061
      status: unknown
    slug: wallbox
    status: profiled
    tags: &id062
    - Company
    - EV Charging
    - Energy Management
    - Smart Hardware
    url: /providers/wallbox/
  layer: domain
  name: Wallbox
  provider: wallbox
  says: ships the Wallbox SDK or integration code
  source: https://github.com/springfall2008/batpred/blob/main/apps/predbat/wallbox.py
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/solar-energy-monitoring/predbat/
providers:
- agent_band: agent-aware
  agent_readiness: 14.5
  band: emerging
  in_catalog: true
  kin_score: 16.2
  mcp: *id001
  name: AgilePredict
  slug: agilepredict
  status: profiled
  tags: *id002
  url: /providers/agilepredict/
- agent_band: agent-aware
  agent_readiness: 22.2
  band: emerging
  in_catalog: true
  kin_score: 13.6
  mcp: *id003
  name: AlphaESS
  slug: alpha-ess
  status: profiled
  tags: *id004
  url: /providers/alpha-ess/
- agent_band: agent-ready
  agent_readiness: 32.9
  band: developing
  in_catalog: true
  kin_score: 44.2
  mcp: *id005
  name: Axle Energy
  slug: axle-energy
  status: profiled
  tags: *id006
  url: /providers/axle-energy/
- agent_band: agent-ready
  agent_readiness: 29.4
  band: thin
  in_catalog: true
  kin_score: 31.3
  mcp: *id007
  name: Carbon Intensity API (NESO)
  slug: carbon-intensity
  status: profiled
  tags: *id008
  url: /providers/carbon-intensity/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 9.6
  mcp: *id009
  name: Deye Cloud
  slug: deye
  status: profiled
  tags: *id010
  url: /providers/deye/
- agent_band: agent-aware
  agent_readiness: 14.8
  band: emerging
  in_catalog: true
  kin_score: 24.8
  mcp: *id011
  name: E.ON Next (Kraken API)
  slug: eon-next
  status: profiled
  tags: *id012
  url: /providers/eon-next/
- agent_band: agent-native
  agent_readiness: 42.2
  band: strong
  in_catalog: true
  kin_score: 65.2
  mcp: *id013
  name: EDF Energy (Kraken API)
  slug: edf-energy
  status: profiled
  tags: *id014
  url: /providers/edf-energy/
- agent_band: agent-ready
  agent_readiness: 35.2
  band: exemplar
  in_catalog: true
  kin_score: 68.6
  mcp: *id015
  name: Enphase Energy
  slug: enphase
  status: profiled
  tags: *id016
  url: /providers/enphase/
- agent_band: agent-ready
  agent_readiness: 29.0
  band: thin
  in_catalog: true
  kin_score: 35.4
  mcp: *id017
  name: Forecast.Solar
  slug: forecast-solar
  status: profiled
  tags: *id018
  url: /providers/forecast-solar/
- agent_band: human-only
  agent_readiness: 3.0
  band: minimal
  in_catalog: true
  kin_score: 0.4
  mcp: *id019
  name: FoxESS Cloud
  slug: fox-ess
  status: profiled
  tags: *id020
  url: /providers/fox-ess/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 9.3
  mcp: *id021
  name: GivEnergy Cloud
  slug: givenergy
  status: profiled
  tags: *id022
  url: /providers/givenergy/
- agent_band: human-only
  agent_readiness: 2.5
  band: emerging
  in_catalog: true
  kin_score: 11.5
  mcp: *id023
  name: Growatt
  slug: growatt
  status: profiled
  tags: *id024
  url: /providers/growatt/
- agent_band: agent-aware
  agent_readiness: 22.2
  band: thin
  in_catalog: true
  kin_score: 29.6
  mcp: *id025
  name: Hanchu ESS
  slug: hanchu-ess
  status: profiled
  tags: *id026
  url: /providers/hanchu-ess/
- agent_band: agent-aware
  agent_readiness: 5.6
  band: thin
  in_catalog: true
  kin_score: 34.5
  mcp: *id027
  name: Home Assistant
  slug: home-assistant
  status: profiled
  tags: *id028
  url: /providers/home-assistant/
- agent_band: agent-aware
  agent_readiness: 21.8
  band: thin
  in_catalog: true
  kin_score: 35.9
  mcp: *id029
  name: Hypervolt
  slug: hypervolt
  status: profiled
  tags: *id030
  url: /providers/hypervolt/
- agent_band: human-only
  agent_readiness: 3.0
  band: emerging
  in_catalog: true
  kin_score: 11.1
  mcp: *id031
  name: MeteoAlarm (EUMETNET)
  slug: meteoalarm
  status: profiled
  tags: *id032
  url: /providers/meteoalarm/
- agent_band: agent-ready
  agent_readiness: 40.9
  band: thin
  in_catalog: true
  kin_score: 38.6
  mcp: *id033
  name: myenergi
  slug: myenergi
  status: profiled
  tags: *id034
  url: /providers/myenergi/
- agent_band: agent-aware
  agent_readiness: 23.5
  band: developing
  in_catalog: true
  kin_score: 44.1
  mcp: *id035
  name: Octopus Energy
  slug: octopus-energy
  status: profiled
  tags: *id036
  url: /providers/octopus-energy/
- agent_band: human-only
  agent_readiness: 3.0
  band: minimal
  in_catalog: true
  kin_score: 7.7
  mcp: *id037
  name: Ohme
  slug: ohme
  status: profiled
  tags: *id038
  url: /providers/ohme/
- agent_band: agent-aware
  agent_readiness: 24.4
  band: thin
  in_catalog: true
  kin_score: 37.7
  mcp: *id039
  name: Ollama
  slug: ollama
  status: profiled
  tags: *id040
  url: /providers/ollama/
- agent_band: agent-aware
  agent_readiness: 17.4
  band: thin
  in_catalog: true
  kin_score: 28.3
  mcp: *id041
  name: Open-Meteo
  slug: open-meteo
  status: profiled
  tags: *id042
  url: /providers/open-meteo/
- agent_band: agent-native
  agent_readiness: 57.5
  band: exemplar
  in_catalog: true
  kin_score: 82.5
  mcp: *id043
  name: OpenAI
  slug: openai
  status: profiled
  tags: *id044
  url: /providers/openai/
- agent_band: agent-ready
  agent_readiness: 46.4
  band: strong
  in_catalog: true
  kin_score: 54.8
  mcp: *id045
  name: OpenRouter
  slug: openrouter
  status: profiled
  tags: *id046
  url: /providers/openrouter/
- agent_band: human-only
  agent_readiness: 0.7
  band: minimal
  in_catalog: true
  kin_score: 4.8
  mcp: *id047
  name: Postcodes.io
  slug: postcodes-io
  status: profiled
  tags: *id048
  url: /providers/postcodes-io/
- agent_band: human-only
  agent_readiness: 3.0
  band: minimal
  in_catalog: true
  kin_score: 0.4
  mcp: *id049
  name: Sigenergy
  slug: sigenergy
  status: profiled
  tags: *id050
  url: /providers/sigenergy/
- agent_band: human-only
  agent_readiness: 3.0
  band: minimal
  in_catalog: true
  kin_score: 4.4
  mcp: *id051
  name: SolaX Cloud
  slug: solax-power
  status: profiled
  tags: *id052
  url: /providers/solax-power/
- agent_band: agent-ready
  agent_readiness: 29.6
  band: developing
  in_catalog: true
  kin_score: 53.7
  mcp: *id053
  name: Solcast
  slug: solcast
  status: profiled
  tags: *id054
  url: /providers/solcast/
- agent_band: agent-aware
  agent_readiness: 15.1
  band: thin
  in_catalog: true
  kin_score: 29.8
  mcp: *id055
  name: SolisCloud (Ginlong)
  slug: soliscloud
  status: profiled
  tags: *id056
  url: /providers/soliscloud/
- agent_band: human-only
  agent_readiness: 3.0
  band: minimal
  in_catalog: true
  kin_score: 0.4
  mcp: *id057
  name: Sunsynk
  slug: sunsynk
  status: profiled
  tags: *id058
  url: /providers/sunsynk/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: developing
  in_catalog: true
  kin_score: 53.6
  mcp: *id059
  name: Teslemetry (Tesla Fleet API proxy, Powerwall)
  slug: teslemetry
  status: profiled
  tags: *id060
  url: /providers/teslemetry/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 16.0
  mcp: *id061
  name: Wallbox
  slug: wallbox
  status: profiled
  tags: *id062
  url: /providers/wallbox/
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
- name: PVOutput
  rows: 22
  url: /applications/solar-energy-monitoring/pvoutput/
- name: Sense
  rows: 6
  url: /applications/solar-energy-monitoring/sense/
sitemap: true
title: 'Predbat: Home Energy & Solar Monitoring reference app'
---
