---
app: evcc
app_slug: evcc
app_url: https://github.com/evcc-io/evcc
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-3480.30
  key: charging-energy-and-tariff-management
  layer: domain
  name: Charging Energy and Tariff Management
  providers:
  - Amber Electric
  - aWATTar
  - EDF (Tempo tariff)
  - EKZ
  - Elering
  - Energinet
  - Energy-Charts (Fraunhofer ISE)
  - ENTSO-E
  - Frank Energie
  - Groupe E
  - Nord Pool
  - Octopus Energy
  - OMIE (Iberian power market)
  - Ostrom
  - Pstryk
  - Red Electrica (e-sios)
  - smartENERGY
  - Stekker
  - Tibber
  url: /capabilities/charging-energy-and-tariff-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-3840.60
  key: der-forecasting
  layer: domain
  name: DER Forecasting
  providers:
  - Forecast.Solar
  - Solcast
  - Victron Energy (VRM)
  url: /capabilities/der-forecasting/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-200.20.20
  key: AE-200.20.20
  layer: domain
  name: EV Charging
  providers:
  - Easee
  - go-e
  - Zaptec
  url: /capabilities/connected-vehicles/
  via_parent: Connected Vehicles
- attribution: API Evangelist extension
  id: AE-230.80
  key: AE-230.80
  layer: domain
  name: Grid Carbon Intensity
  providers:
  - Electricity Maps
  - Fingrid
  - GrünStromIndex (Corrently)
  - National Energy System Operator (NESO)
  url: /capabilities/grid-carbon-intensity/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-200.10
  key: AE-200.10
  layer: domain
  name: Smart Home
  providers:
  - Home Assistant (self-hosted)
  - ioBroker (self-hosted)
  url: /capabilities/smart-home/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-200.20.10
  key: AE-200.20.10
  layer: domain
  name: Vehicle Data Access
  providers:
  - Aiways
  - Audi Connect
  - BMW
  - Connected Cars
  - EVNotify
  - Ford
  - Hyundai
  - JLR (Jaguar Land Rover)
  - Kia
  - LiveWire
  - Mazda
  - Mercedes-Benz
  - MG (SAIC Motor)
  - Nissan
  - NIU
  - Octopus Energy
  - Open Vehicle Monitoring System (self-hosted)
  - Polestar
  - Porsche
  - Renault Group
  - smart Europe
  - Stellantis
  - Subaru
  - Tesla
  - TeslaFi
  - TeslaLogger (self-hosted)
  - TeslaMate (self-hosted)
  - Tessie
  - Tibber
  - Toyota
  - TRONITY
  - Volkswagen Group
  - Volvo Cars
  - Zero Motorcycles
  url: /capabilities/connected-vehicles/
  via_parent: Connected Vehicles
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - InfluxDB
  url: /capabilities/observability-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.30
  key: AE-150.30
  layer: common
  name: Push Notifications
  providers:
  - ntfy
  - Pushover
  url: /capabilities/push-notifications/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-230.10
  key: AE-230.10
  layer: common
  name: Weather & Environment
  providers:
  - Deutscher Wetterdienst
  - Open-Meteo
  url: /capabilities/weather-environment/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.20.20
  key: AE-150.20.20
  layer: common
  name: WhatsApp & OTT Messaging
  providers:
  - Telegram
  url: /capabilities/sms-messaging-apps/
  via_parent: SMS & Messaging Apps
category:
  id: connected-car-ev-charging
  name: Connected Car & EV Charging
  url: /applications/connected-car-ev-charging/
counts:
  declared: 0
  observed: 71
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/evcc-io/evcc/master/go.mod
- route: source code
  url: https://github.com/evcc-io/evcc/tree/master/charger
- route: source code
  url: https://github.com/evcc-io/evcc/tree/master/server
- route: source code
  url: https://github.com/evcc-io/evcc/tree/master/templates/definition/messenger
- route: source code
  url: https://github.com/evcc-io/evcc/tree/master/templates/definition/tariff
- route: source code
  url: https://github.com/evcc-io/evcc/tree/master/templates/definition/vehicle
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-200.20.10
    key: AE-200.20.10
    name: Vehicle Data Access
    url: /capabilities/connected-vehicles/
    via_parent: Connected Vehicles
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 10.8
    mcp: &id003
      status: unknown
    slug: aiways
    status: profiled
    tags: &id004
    - Automotive
    - Company
    - Electric Vehicles
    - Mobility
    url: /providers/aiways/
  layer: domain
  name: Aiways
  provider: aiways
  says: ships the Aiways SDK or integration code
  source: https://github.com/evcc-io/evcc/tree/master/templates/definition/vehicle
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-3480.30
    key: charging-energy-and-tariff-management
    name: Charging Energy and Tariff Management
    url: /capabilities/charging-energy-and-tariff-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 46.4
    band: strong
    in_catalog: true
    kin_score: 65.1
    mcp: &id005
      status: none
    slug: amber-electric
    status: profiled
    tags: &id006
    - Australia
    - Electricity
    - Energy
    - Utilities
    url: /providers/amber-electric/
  layer: domain
  name: Amber Electric
  provider: amber-electric
  says: ships the Amber Electric SDK or integration code
  source: https://github.com/evcc-io/evcc/tree/master/templates/definition/tariff
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-200.20.10
    key: AE-200.20.10
    name: Vehicle Data Access
    url: /capabilities/connected-vehicles/
    via_parent: Connected Vehicles
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 6.5
    mcp: &id007
      status: unknown
    slug: audi-connect
    status: profiled
    tags: &id008
    - Automotive
    - Connected Vehicles
    - Mobility
    - Telematics
    url: /providers/audi-connect/
  layer: domain
  name: Audi Connect
  provider: audi-connect
  says: ships the Audi Connect SDK or integration code
  source: https://github.com/evcc-io/evcc/tree/master/templates/definition/vehicle
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-3480.30
    key: charging-energy-and-tariff-management
    name: Charging Energy and Tariff Management
    url: /capabilities/charging-energy-and-tariff-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 28.4
    band: thin
    in_catalog: true
    kin_score: 26.8
    mcp: &id009
      status: none
    slug: awattar
    status: profiled
    tags: &id010
    - EPEX Spot
    - Electricity
    - Energy
    - Spot Price
    url: /providers/awattar/
  layer: domain
  name: aWATTar
  provider: awattar
  says: ships the aWATTar SDK or integration code
  source: https://github.com/evcc-io/evcc/tree/master/templates/definition/tariff
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-200.20.10
    key: AE-200.20.10
    name: Vehicle Data Access
    url: /capabilities/connected-vehicles/
    via_parent: Connected Vehicles
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.6
    band: emerging
    in_catalog: true
    kin_score: 20.5
    mcp: &id011
      status: unknown
    slug: bmw
    status: profiled
    tags: &id012
    - Automobiles
    - Automotive
    - Cars
    - Vehicles
    url: /providers/bmw/
  layer: domain
  name: BMW
  provider: bmw
  says: ships the BMW SDK or integration code
  source: https://github.com/evcc-io/evcc/tree/master/templates/definition/vehicle
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-200.20.10
    key: AE-200.20.10
    name: Vehicle Data Access
    url: /capabilities/connected-vehicles/
    via_parent: Connected Vehicles
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 18.3
    band: emerging
    in_catalog: true
    kin_score: 11.2
    mcp: &id013
      status: none
    slug: connectedcars-io
    status: profiled
    tags: &id014
    - Connected Car Platform
    - Dealers
    - OEM APIs
    - Real-time Vehicle Data
    url: /providers/connectedcars-io/
  layer: domain
  name: Connected Cars
  provider: connectedcars-io
  says: ships the Connected Cars SDK or integration code
  source: https://github.com/evcc-io/evcc/tree/master/templates/definition/vehicle
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
    mcp: &id015
      status: none
    slug: deutscher-wetterdienst
    status: profiled
    tags: &id016
    - Geospatial
    - OGC
    - WFS
    - WMS
    url: /providers/deutscher-wetterdienst/
  layer: common
  name: Deutscher Wetterdienst
  provider: deutscher-wetterdienst
  says: ships the Deutscher Wetterdienst SDK or integration code
  source: https://github.com/evcc-io/evcc/tree/master/templates/definition/tariff
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
    agent_readiness: 29.2
    band: developing
    in_catalog: true
    kin_score: 48.6
    mcp: &id017
      status: none
    slug: easee
    status: profiled
    tags: &id018
    - Company
    - EV Charging
    - IoT
    - Smart Home
    url: /providers/easee/
  layer: domain
  name: Easee
  provider: easee
  says: ships the Easee SDK or integration code
  source: https://github.com/evcc-io/evcc/tree/master/charger
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-3480.30
    key: charging-energy-and-tariff-management
    name: Charging Energy and Tariff Management
    url: /capabilities/charging-energy-and-tariff-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.8
    band: minimal
    in_catalog: true
    kin_score: 7.0
    mcp: &id019
      status: unknown
    slug: edf
    status: profiled
    tags: &id020
    - Company
    - Energy
    - France
    - Utilities
    url: /providers/edf/
  layer: domain
  name: EDF (Tempo tariff)
  provider: edf
  says: ships the EDF (Tempo tariff) SDK or integration code
  source: https://github.com/evcc-io/evcc/tree/master/templates/definition/tariff
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-3480.30
    key: charging-energy-and-tariff-management
    name: Charging Energy and Tariff Management
    url: /capabilities/charging-energy-and-tariff-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 11.8
    mcp: &id021
      status: unknown
    slug: ekz
    status: profiled
    tags: &id022
    - Energy
    - Renewables
    - Switzerland
    - Utilities
    url: /providers/ekz/
  layer: domain
  name: EKZ
  provider: ekz
  says: ships the EKZ SDK or integration code
  source: https://github.com/evcc-io/evcc/tree/master/templates/definition/tariff
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-230.80
    key: AE-230.80
    name: Grid Carbon Intensity
    url: /capabilities/grid-carbon-intensity/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 28.5
    band: thin
    in_catalog: true
    kin_score: 29.8
    mcp: &id023
      status: none
    slug: electricitymaps
    status: profiled
    tags: &id024
    - Carbon Intensity
    - Electricity
    - Energy
    - Grid
    url: /providers/electricitymaps/
  layer: domain
  name: Electricity Maps
  provider: electricitymaps
  says: ships the Electricity Maps SDK or integration code
  source: https://github.com/evcc-io/evcc/tree/master/templates/definition/tariff
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-3480.30
    key: charging-energy-and-tariff-management
    name: Charging Energy and Tariff Management
    url: /capabilities/charging-energy-and-tariff-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 8.4
    mcp: &id025
      status: none
    slug: elering
    status: profiled
    tags: &id026
    - Energy
    - Estonia
    - Grid
    - Transmission
    url: /providers/elering/
  layer: domain
  name: Elering
  provider: elering
  says: ships the Elering SDK or integration code
  source: https://github.com/evcc-io/evcc/tree/master/templates/definition/tariff
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-3480.30
    key: charging-energy-and-tariff-management
    name: Charging Energy and Tariff Management
    url: /capabilities/charging-energy-and-tariff-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 11.6
    band: minimal
    in_catalog: true
    kin_score: 7.7
    mcp: &id027
      status: unknown
    slug: energinet
    status: profiled
    tags: &id028
    - Company
    - Energy
    - Grid
    - Transmission
    url: /providers/energinet/
  layer: domain
  name: Energinet
  provider: energinet
  says: ships the Energinet SDK or integration code
  source: https://github.com/evcc-io/evcc/tree/master/templates/definition/tariff
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-3480.30
    key: charging-energy-and-tariff-management
    name: Charging Energy and Tariff Management
    url: /capabilities/charging-energy-and-tariff-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.7
    band: emerging
    in_catalog: true
    kin_score: 22.7
    mcp: &id029
      status: unknown
    slug: energy-charts-api
    status: profiled
    tags: &id030
    - Electricity
    - Energy
    - Grid
    - Renewables
    url: /providers/energy-charts-api/
  layer: domain
  name: Energy-Charts (Fraunhofer ISE)
  provider: energy-charts-api
  says: ships the Energy-Charts (Fraunhofer ISE) SDK or integration code
  source: https://github.com/evcc-io/evcc/tree/master/templates/definition/tariff
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-3480.30
    key: charging-energy-and-tariff-management
    name: Charging Energy and Tariff Management
    url: /capabilities/charging-energy-and-tariff-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 34.0
    band: thin
    in_catalog: true
    kin_score: 33.4
    mcp: &id031
      status: none
    slug: entso-e
    status: profiled
    tags: &id032
    - Day-Ahead Prices
    - Electricity
    - Energy
    - Energy Markets
    url: /providers/entso-e/
  layer: domain
  name: ENTSO-E
  provider: entso-e
  says: ships the ENTSO-E SDK or integration code
  source: https://github.com/evcc-io/evcc/tree/master/templates/definition/tariff
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-200.20.10
    key: AE-200.20.10
    name: Vehicle Data Access
    url: /capabilities/connected-vehicles/
    via_parent: Connected Vehicles
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id033
      status: unchecked
    slug: evnotify
    status: queued for profiling
    tags: &id034 []
    url: null
  layer: domain
  name: EVNotify
  provider: evnotify
  says: ships the EVNotify SDK or integration code
  source: https://github.com/evcc-io/evcc/tree/master/templates/definition/vehicle
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-230.80
    key: AE-230.80
    name: Grid Carbon Intensity
    url: /capabilities/grid-carbon-intensity/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.8
    band: emerging
    in_catalog: true
    kin_score: 12.5
    mcp: &id035
      status: none
    slug: fingrid
    status: profiled
    tags: &id036
    - Company
    - Electricity
    - Energy
    - Transmission
    url: /providers/fingrid/
  layer: domain
  name: Fingrid
  provider: fingrid
  says: ships the Fingrid SDK or integration code
  source: https://github.com/evcc-io/evcc/tree/master/templates/definition/tariff
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-200.20.10
    key: AE-200.20.10
    name: Vehicle Data Access
    url: /capabilities/connected-vehicles/
    via_parent: Connected Vehicles
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 26.9
    band: thin
    in_catalog: true
    kin_score: 28.7
    mcp: &id037
      status: none
    slug: ford
    status: profiled
    tags: &id038
    - Automobiles
    - Cars
    - Connected Vehicles
    - Vehicles
    url: /providers/ford/
  layer: domain
  name: Ford
  provider: ford
  says: ships the Ford SDK or integration code
  source: https://github.com/evcc-io/evcc/tree/master/templates/definition/vehicle
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
    mcp: &id039
      status: unknown
    slug: forecast-solar
    status: profiled
    tags: &id040
    - Company
    - Forecast
    - Renewable Energy
    - Solar
    url: /providers/forecast-solar/
  layer: domain
  name: Forecast.Solar
  provider: forecast-solar
  says: ships the Forecast.Solar SDK or integration code
  source: https://github.com/evcc-io/evcc/tree/master/templates/definition/tariff
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-3480.30
    key: charging-energy-and-tariff-management
    name: Charging Energy and Tariff Management
    url: /capabilities/charging-energy-and-tariff-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 14.2
    mcp: &id041
      status: unknown
    slug: frank-energie
    status: profiled
    tags: &id042
    - Company
    url: /providers/frank-energie/
  layer: domain
  name: Frank Energie
  provider: frank-energie
  says: ships the Frank Energie SDK or integration code
  source: https://github.com/evcc-io/evcc/tree/master/templates/definition/tariff
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
    kin_score: 20.9
    mcp: &id043
      status: unknown
    slug: go-e
    status: profiled
    tags: &id044
    - Company
    - EV Charging
    - Hardware
    - Sustainability
    url: /providers/go-e/
  layer: domain
  name: go-e
  provider: go-e
  says: ships the go-e SDK or integration code
  source: https://github.com/evcc-io/evcc/tree/master/charger
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-3480.30
    key: charging-energy-and-tariff-management
    name: Charging Energy and Tariff Management
    url: /capabilities/charging-energy-and-tariff-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 3.1
    mcp: &id045
      status: unknown
    slug: groupe-e
    status: profiled
    tags: &id046
    - Company
    - Energy
    - Renewables
    - Switzerland
    url: /providers/groupe-e/
  layer: domain
  name: Groupe E
  provider: groupe-e
  says: ships the Groupe E SDK or integration code
  source: https://github.com/evcc-io/evcc/tree/master/templates/definition/tariff
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-230.80
    key: AE-230.80
    name: Grid Carbon Intensity
    url: /capabilities/grid-carbon-intensity/
    via_parent: null
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id047
      status: unchecked
    slug: gruenstromindex
    status: queued for profiling
    tags: &id048 []
    url: null
  layer: domain
  name: GrünStromIndex (Corrently)
  provider: gruenstromindex
  says: ships the GrünStromIndex (Corrently) SDK or integration code
  source: https://github.com/evcc-io/evcc/tree/master/templates/definition/tariff
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-200.10
    key: AE-200.10
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
    mcp: &id049
      source: https://www.home-assistant.io/integrations/mcp_server/
      status: verified
    slug: home-assistant
    status: profiled
    tags: &id050
    - Community
    - Home Automation
    - IoT
    - Open Source
    url: /providers/home-assistant/
  layer: domain
  name: Home Assistant (self-hosted)
  provider: home-assistant
  says: ships the Home Assistant (self-hosted) SDK or integration code
  source: https://github.com/evcc-io/evcc/tree/master/templates/definition/vehicle
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-200.20.10
    key: AE-200.20.10
    name: Vehicle Data Access
    url: /capabilities/connected-vehicles/
    via_parent: Connected Vehicles
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 28.7
    band: developing
    in_catalog: true
    kin_score: 49.5
    mcp: &id051
      status: none
    slug: hyundai
    status: profiled
    tags: &id052
    - Automobiles
    - Cars
    - Connected Vehicles
    - Mobility
    url: /providers/hyundai/
  layer: domain
  name: Hyundai
  provider: hyundai
  says: ships the Hyundai SDK or integration code
  source: https://github.com/evcc-io/evcc/tree/master/templates/definition/vehicle
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
    mcp: &id053
      source: https://github.com/influxdata/influxdb3_mcp_server
      status: verified
    slug: influxdata
    status: profiled
    tags: &id054
    - Database
    - Monitoring
    - Observability
    - Time Series Database
    url: /providers/influxdata/
  layer: common
  name: InfluxDB
  provider: influxdata
  says: ships the InfluxDB SDK or integration code
  source: https://github.com/evcc-io/evcc/tree/master/server
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-200.10
    key: AE-200.10
    name: Smart Home
    url: /capabilities/smart-home/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.5
    band: minimal
    in_catalog: true
    kin_score: 8.2
    mcp: &id055
      source: https://github.com/ioBroker/ioBroker.mcp
      status: verified
    slug: iobroker
    status: profiled
    tags: &id056
    - Company
    - Home Automation
    - IoT
    - Open Source
    url: /providers/iobroker/
  layer: domain
  name: ioBroker (self-hosted)
  provider: iobroker
  says: ships the ioBroker (self-hosted) SDK or integration code
  source: https://github.com/evcc-io/evcc/tree/master/templates/definition/vehicle
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-200.20.10
    key: AE-200.20.10
    name: Vehicle Data Access
    url: /capabilities/connected-vehicles/
    via_parent: Connected Vehicles
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 13.6
    mcp: &id057
      status: unknown
    slug: jlr
    status: profiled
    tags: &id058
    - Automotive
    - Company
    - Connected Vehicles
    - Vehicle Data
    url: /providers/jlr/
  layer: domain
  name: JLR (Jaguar Land Rover)
  provider: jlr
  says: ships the JLR (Jaguar Land Rover) SDK or integration code
  source: https://github.com/evcc-io/evcc/tree/master/templates/definition/vehicle
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-200.20.10
    key: AE-200.20.10
    name: Vehicle Data Access
    url: /capabilities/connected-vehicles/
    via_parent: Connected Vehicles
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 16.9
    band: thin
    in_catalog: true
    kin_score: 32.9
    mcp: &id059
      status: none
    slug: kia
    status: profiled
    tags: &id060
    - Automotive
    - Connected Vehicles
    - OAuth
    - Vehicle Data
    url: /providers/kia/
  layer: domain
  name: Kia
  provider: kia
  says: ships the Kia SDK or integration code
  source: https://github.com/evcc-io/evcc/tree/master/templates/definition/vehicle
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-200.20.10
    key: AE-200.20.10
    name: Vehicle Data Access
    url: /capabilities/connected-vehicles/
    via_parent: Connected Vehicles
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 14.8
    band: emerging
    in_catalog: true
    kin_score: 14.6
    mcp: &id061
      status: none
    slug: livewire
    status: profiled
    tags: &id062
    - Company
    - Electric Motorcycles
    - Electric Vehicles
    - Transportation
    url: /providers/livewire/
  layer: domain
  name: LiveWire
  provider: livewire
  says: ships the LiveWire SDK or integration code
  source: https://github.com/evcc-io/evcc/tree/master/templates/definition/vehicle
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-200.20.10
    key: AE-200.20.10
    name: Vehicle Data Access
    url: /capabilities/connected-vehicles/
    via_parent: Connected Vehicles
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 4.1
    mcp: &id063
      status: unknown
    slug: mazda
    status: profiled
    tags: &id064
    - Company
    url: /providers/mazda/
  layer: domain
  name: Mazda
  provider: mazda
  says: ships the Mazda SDK or integration code
  source: https://github.com/evcc-io/evcc/tree/master/templates/definition/vehicle
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-200.20.10
    key: AE-200.20.10
    name: Vehicle Data Access
    url: /capabilities/connected-vehicles/
    via_parent: Connected Vehicles
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.6
    band: thin
    in_catalog: true
    kin_score: 29.3
    mcp: &id065
      status: none
    slug: mercedes-benz
    status: profiled
    tags: &id066
    - Automobiles
    - Cars
    - Vehicles
    url: /providers/mercedes-benz/
  layer: domain
  name: Mercedes-Benz
  provider: mercedes-benz
  says: ships the Mercedes-Benz SDK or integration code
  source: https://github.com/evcc-io/evcc/tree/master/templates/definition/vehicle
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-200.20.10
    key: AE-200.20.10
    name: Vehicle Data Access
    url: /capabilities/connected-vehicles/
    via_parent: Connected Vehicles
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 2.2
    mcp: &id067
      status: unknown
    slug: saic-motor
    status: profiled
    tags: &id068
    - Automotive
    - China
    - Company
    - Manufacturing
    url: /providers/saic-motor/
  layer: domain
  name: MG (SAIC Motor)
  provider: saic-motor
  says: ships the MG (SAIC Motor) SDK or integration code
  source: https://github.com/evcc-io/evcc/tree/master/templates/definition/vehicle
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-230.80
    key: AE-230.80
    name: Grid Carbon Intensity
    url: /capabilities/grid-carbon-intensity/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.0
    band: developing
    in_catalog: true
    kin_score: 43.5
    mcp: &id069
      status: none
    slug: neso
    status: profiled
    tags: &id070
    - Electricity
    - Energy
    - Energy Markets
    - United Kingdom
    url: /providers/neso/
  layer: domain
  name: National Energy System Operator (NESO)
  provider: neso
  says: ships the National Energy System Operator (NESO) SDK or integration code
  source: https://github.com/evcc-io/evcc/tree/master/templates/definition/tariff
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-200.20.10
    key: AE-200.20.10
    name: Vehicle Data Access
    url: /capabilities/connected-vehicles/
    via_parent: Connected Vehicles
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.5
    band: minimal
    in_catalog: true
    kin_score: 7.9
    mcp: &id071
      status: unknown
    slug: nissan
    status: profiled
    tags: &id072
    - Automobiles
    - Cars
    - Vehicles
    url: /providers/nissan/
  layer: domain
  name: Nissan
  provider: nissan
  says: ships the Nissan SDK or integration code
  source: https://github.com/evcc-io/evcc/tree/master/templates/definition/vehicle
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-200.20.10
    key: AE-200.20.10
    name: Vehicle Data Access
    url: /capabilities/connected-vehicles/
    via_parent: Connected Vehicles
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 4.4
    band: emerging
    in_catalog: true
    kin_score: 11.7
    mcp: &id073
      status: unknown
    slug: niu
    status: profiled
    tags: &id074
    - E-Bikes
    - Electric Vehicles
    - Mobility
    - Scooters
    url: /providers/niu/
  layer: domain
  name: NIU
  provider: niu
  says: ships the NIU SDK or integration code
  source: https://github.com/evcc-io/evcc/tree/master/templates/definition/vehicle
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-3480.30
    key: charging-energy-and-tariff-management
    name: Charging Energy and Tariff Management
    url: /capabilities/charging-energy-and-tariff-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.9
    band: thin
    in_catalog: true
    kin_score: 37.8
    mcp: &id075
      status: none
    slug: nordpool
    status: profiled
    tags: &id076
    - Day-Ahead Prices
    - Electricity
    - Energy Markets
    - Power Exchange
    url: /providers/nordpool/
  layer: domain
  name: Nord Pool
  provider: nordpool
  says: ships the Nord Pool SDK or integration code
  source: https://github.com/evcc-io/evcc/tree/master/templates/definition/tariff
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.30
    key: AE-150.30
    name: Push Notifications
    url: /capabilities/push-notifications/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 15.5
    mcp: &id077
      status: none
    slug: ntfy
    status: profiled
    tags: &id078
    - Notification
    - Open Source
    - Pub/Sub
    - Self-Hosted
    url: /providers/ntfy/
  layer: common
  name: ntfy
  provider: ntfy
  says: ships the ntfy SDK or integration code
  source: https://github.com/evcc-io/evcc/tree/master/templates/definition/messenger
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-200.20.10
    key: AE-200.20.10
    name: Vehicle Data Access
    url: /capabilities/connected-vehicles/
    via_parent: Connected Vehicles
  credit: null
  facts: &id001
    agent_band: agent-aware
    agent_readiness: 23.5
    band: developing
    in_catalog: true
    kin_score: 44.1
    mcp: &id079
      status: none
    slug: octopus-energy
    status: profiled
    tags: &id080
    - Electricity
    - Energy
    - Gas
    - Renewable Energy
    url: /providers/octopus-energy/
  layer: domain
  name: Octopus Energy
  provider: octopus-energy
  says: ships the Octopus Energy SDK or integration code
  source: https://github.com/evcc-io/evcc/tree/master/templates/definition/vehicle
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-3480.30
    key: charging-energy-and-tariff-management
    name: Charging Energy and Tariff Management
    url: /capabilities/charging-energy-and-tariff-management/
    via_parent: null
  credit: null
  facts: *id001
  layer: domain
  name: Octopus Energy
  provider: octopus-energy
  says: ships the Octopus Energy SDK or integration code
  source: https://github.com/evcc-io/evcc/tree/master/templates/definition/tariff
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-3480.30
    key: charging-energy-and-tariff-management
    name: Charging Energy and Tariff Management
    url: /capabilities/charging-energy-and-tariff-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 9.0
    mcp: &id081
      status: unknown
    slug: omie-es
    status: profiled
    tags: &id082
    - Company
    - Electricity
    - Energy
    - Markets
    url: /providers/omie-es/
  layer: domain
  name: OMIE (Iberian power market)
  provider: omie-es
  says: ships the OMIE (Iberian power market) SDK or integration code
  source: https://github.com/evcc-io/evcc/tree/master/templates/definition/tariff
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-200.20.10
    key: AE-200.20.10
    name: Vehicle Data Access
    url: /capabilities/connected-vehicles/
    via_parent: Connected Vehicles
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 17.6
    band: emerging
    in_catalog: true
    kin_score: 21.9
    mcp: &id083
      status: none
    slug: ovms
    status: profiled
    tags: &id084
    - Company
    - Electric Vehicles
    - Open Source
    - Telematics
    url: /providers/ovms/
  layer: domain
  name: Open Vehicle Monitoring System (self-hosted)
  provider: ovms
  says: ships the Open Vehicle Monitoring System (self-hosted) SDK or integration code
  source: https://github.com/evcc-io/evcc/tree/master/templates/definition/vehicle
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
    agent_readiness: 17.4
    band: thin
    in_catalog: true
    kin_score: 28.3
    mcp: &id085
      status: none
    slug: open-meteo
    status: profiled
    tags: &id086
    - Air Quality
    - Forecast
    - Historical Weather
    - Weather
    url: /providers/open-meteo/
  layer: common
  name: Open-Meteo
  provider: open-meteo
  says: ships the Open-Meteo SDK or integration code
  source: https://github.com/evcc-io/evcc/tree/master/templates/definition/tariff
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-3480.30
    key: charging-energy-and-tariff-management
    name: Charging Energy and Tariff Management
    url: /capabilities/charging-energy-and-tariff-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 30.8
    band: developing
    in_catalog: true
    kin_score: 45.8
    mcp: &id087
      status: none
    slug: ostrom
    status: profiled
    tags: &id088
    - Company
    - Electricity
    - Energy
    - Renewable Energy
    url: /providers/ostrom/
  layer: domain
  name: Ostrom
  provider: ostrom
  says: ships the Ostrom SDK or integration code
  source: https://github.com/evcc-io/evcc/tree/master/templates/definition/tariff
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-200.20.10
    key: AE-200.20.10
    name: Vehicle Data Access
    url: /capabilities/connected-vehicles/
    via_parent: Connected Vehicles
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 6.8
    mcp: &id089
      status: none
    slug: polestar-cars
    status: profiled
    tags: &id090
    - Automotive
    - Connected Vehicles
    - Electric Vehicles
    - Premium Vehicles
    url: /providers/polestar-cars/
  layer: domain
  name: Polestar
  provider: polestar-cars
  says: ships the Polestar SDK or integration code
  source: https://github.com/evcc-io/evcc/tree/master/templates/definition/vehicle
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-200.20.10
    key: AE-200.20.10
    name: Vehicle Data Access
    url: /capabilities/connected-vehicles/
    via_parent: Connected Vehicles
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 20.8
    band: thin
    in_catalog: true
    kin_score: 33.1
    mcp: &id091
      status: none
    slug: porsche
    status: profiled
    tags: &id092
    - Automobiles
    - Automotive
    - Cars
    - Vehicles
    url: /providers/porsche/
  layer: domain
  name: Porsche
  provider: porsche
  says: ships the Porsche SDK or integration code
  source: https://github.com/evcc-io/evcc/tree/master/templates/definition/vehicle
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-3480.30
    key: charging-energy-and-tariff-management
    name: Charging Energy and Tariff Management
    url: /capabilities/charging-energy-and-tariff-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.5
    band: emerging
    in_catalog: true
    kin_score: 12.7
    mcp: &id093
      status: unknown
    slug: pstryk
    status: profiled
    tags: &id094
    - Company
    - Energy
    - Fintech
    - Utilities
    url: /providers/pstryk/
  layer: domain
  name: Pstryk
  provider: pstryk
  says: ships the Pstryk SDK or integration code
  source: https://github.com/evcc-io/evcc/tree/master/templates/definition/tariff
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.30
    key: AE-150.30
    name: Push Notifications
    url: /capabilities/push-notifications/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 21.6
    band: thin
    in_catalog: true
    kin_score: 28.1
    mcp: &id095
      status: none
    slug: pushover
    status: profiled
    tags: &id096
    - Alerts
    - Messaging
    - Notification
    - Push Notifications
    url: /providers/pushover/
  layer: common
  name: Pushover
  provider: pushover
  says: ships the Pushover SDK or integration code
  source: https://raw.githubusercontent.com/evcc-io/evcc/master/go.mod
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-3480.30
    key: charging-energy-and-tariff-management
    name: Charging Energy and Tariff Management
    url: /capabilities/charging-energy-and-tariff-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 22.2
    band: emerging
    in_catalog: true
    kin_score: 21.9
    mcp: &id097
      status: none
    slug: esios-red-electrica
    status: profiled
    tags: &id098
    - Company
    - Data
    - Energy
    - Spain
    url: /providers/esios-red-electrica/
  layer: domain
  name: Red Electrica (e-sios)
  provider: esios-red-electrica
  says: ships the Red Electrica (e-sios) SDK or integration code
  source: https://github.com/evcc-io/evcc/tree/master/templates/definition/tariff
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-200.20.10
    key: AE-200.20.10
    name: Vehicle Data Access
    url: /capabilities/connected-vehicles/
    via_parent: Connected Vehicles
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 21.1
    mcp: &id099
      status: none
    slug: renault-group
    status: profiled
    tags: &id100
    - Android Automotive
    - Automotive
    - Company
    - In-Vehicle Apps
    url: /providers/renault-group/
  layer: domain
  name: Renault Group
  provider: renault-group
  says: ships the Renault Group SDK or integration code
  source: https://github.com/evcc-io/evcc/tree/master/templates/definition/vehicle
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-200.20.10
    key: AE-200.20.10
    name: Vehicle Data Access
    url: /capabilities/connected-vehicles/
    via_parent: Connected Vehicles
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 4.9
    mcp: &id101
      status: unknown
    slug: smart-com
    status: profiled
    tags: &id102
    - Company
    url: /providers/smart-com/
  layer: domain
  name: smart Europe
  provider: smart-com
  says: ships the smart Europe SDK or integration code
  source: https://github.com/evcc-io/evcc/tree/master/templates/definition/vehicle
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-3480.30
    key: charging-energy-and-tariff-management
    name: Charging Energy and Tariff Management
    url: /capabilities/charging-energy-and-tariff-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 11.9
    mcp: &id103
      status: none
    slug: smartenergy-at
    status: profiled
    tags: &id104
    - Austria
    - Energy
    - Renewables
    - Smart Grid
    url: /providers/smartenergy-at/
  layer: domain
  name: smartENERGY
  provider: smartenergy-at
  says: ships the smartENERGY SDK or integration code
  source: https://github.com/evcc-io/evcc/tree/master/templates/definition/tariff
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
    mcp: &id105
      status: none
    slug: solcast
    status: profiled
    tags: &id106
    - Energy
    - Forecasting
    - Irradiance
    - Solar
    url: /providers/solcast/
  layer: domain
  name: Solcast
  provider: solcast
  says: ships the Solcast SDK or integration code
  source: https://github.com/evcc-io/evcc/tree/master/templates/definition/tariff
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-3480.30
    key: charging-energy-and-tariff-management
    name: Charging Energy and Tariff Management
    url: /capabilities/charging-energy-and-tariff-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 19.4
    band: thin
    in_catalog: true
    kin_score: 27.4
    mcp: &id107
      status: none
    slug: stekker
    status: profiled
    tags: &id108
    - Electric Vehicles
    - Energy
    - Marketplace
    - Renewables
    url: /providers/stekker/
  layer: domain
  name: Stekker
  provider: stekker
  says: ships the Stekker SDK or integration code
  source: https://github.com/evcc-io/evcc/tree/master/templates/definition/tariff
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-200.20.10
    key: AE-200.20.10
    name: Vehicle Data Access
    url: /capabilities/connected-vehicles/
    via_parent: Connected Vehicles
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 19.9
    band: emerging
    in_catalog: true
    kin_score: 22.8
    mcp: &id109
      status: none
    slug: stellantis
    status: profiled
    tags: &id110
    - Automotive
    - Company
    - Manufacturing
    - Mobility
    url: /providers/stellantis/
  layer: domain
  name: Stellantis
  provider: stellantis
  says: ships the Stellantis SDK or integration code
  source: https://github.com/evcc-io/evcc/tree/master/templates/definition/vehicle
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-200.20.10
    key: AE-200.20.10
    name: Vehicle Data Access
    url: /capabilities/connected-vehicles/
    via_parent: Connected Vehicles
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.6
    band: minimal
    in_catalog: true
    kin_score: 7.1
    mcp: &id111
      status: none
    slug: subaru-of-america
    status: profiled
    tags: &id112
    - Automobiles
    - Automotive
    - Cars
    - Vehicles
    url: /providers/subaru-of-america/
  layer: domain
  name: Subaru
  provider: subaru-of-america
  says: ships the Subaru SDK or integration code
  source: https://github.com/evcc-io/evcc/tree/master/templates/definition/vehicle
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.20
    key: AE-150.20.20
    name: WhatsApp & OTT Messaging
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.3
    band: strong
    in_catalog: true
    kin_score: 56.8
    mcp: &id113
      status: none
    slug: telegram
    status: profiled
    tags: &id114
    - Bots
    - Chat
    - Messaging
    - Notification
    url: /providers/telegram/
  layer: common
  name: Telegram
  provider: telegram
  says: ships the Telegram SDK or integration code
  source: https://raw.githubusercontent.com/evcc-io/evcc/master/go.mod
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-200.20.10
    key: AE-200.20.10
    name: Vehicle Data Access
    url: /capabilities/connected-vehicles/
    via_parent: Connected Vehicles
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 22.3
    band: thin
    in_catalog: true
    kin_score: 34.8
    mcp: &id115
      status: none
    slug: tesla
    status: profiled
    tags: &id116
    - Automobiles
    - Cars
    - Electric Vehicles
    - Vehicles
    url: /providers/tesla/
  layer: domain
  name: Tesla
  provider: tesla
  says: ships the Tesla SDK or integration code
  source: https://github.com/evcc-io/evcc/tree/master/templates/definition/vehicle
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-200.20.10
    key: AE-200.20.10
    name: Vehicle Data Access
    url: /capabilities/connected-vehicles/
    via_parent: Connected Vehicles
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 18.3
    band: emerging
    in_catalog: true
    kin_score: 15.0
    mcp: &id117
      source: https://teslafi.com
      status: documented
    slug: teslafi
    status: profiled
    tags: &id118
    - Company
    - Data-Logger
    - Tesla
    - Vehicle-Analytics
    url: /providers/teslafi/
  layer: domain
  name: TeslaFi
  provider: teslafi
  says: ships the TeslaFi SDK or integration code
  source: https://github.com/evcc-io/evcc/tree/master/templates/definition/vehicle
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-200.20.10
    key: AE-200.20.10
    name: Vehicle Data Access
    url: /capabilities/connected-vehicles/
    via_parent: Connected Vehicles
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 23.2
    band: emerging
    in_catalog: true
    kin_score: 22.4
    mcp: &id119
      source: https://teslalogger.de/docs/extras/mcp-server
      status: verified
    slug: teslalogger
    status: profiled
    tags: &id120
    - Automotive
    - Company
    - Data Logging
    - Open Source
    url: /providers/teslalogger/
  layer: domain
  name: TeslaLogger (self-hosted)
  provider: teslalogger
  says: ships the TeslaLogger (self-hosted) SDK or integration code
  source: https://github.com/evcc-io/evcc/tree/master/templates/definition/vehicle
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-200.20.10
    key: AE-200.20.10
    name: Vehicle Data Access
    url: /capabilities/connected-vehicles/
    via_parent: Connected Vehicles
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 4.1
    mcp: &id121
      status: none
    slug: teslamate
    status: profiled
    tags: &id122
    - Company
    - Data-Logger
    - Open Source
    - Tesla
    url: /providers/teslamate/
  layer: domain
  name: TeslaMate (self-hosted)
  provider: teslamate
  says: ships the TeslaMate (self-hosted) SDK or integration code
  source: https://github.com/evcc-io/evcc/tree/master/templates/definition/vehicle
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-200.20.10
    key: AE-200.20.10
    name: Vehicle Data Access
    url: /capabilities/connected-vehicles/
    via_parent: Connected Vehicles
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.6
    band: developing
    in_catalog: true
    kin_score: 47.3
    mcp: &id123
      status: none
    slug: tessie
    status: profiled
    tags: &id124
    - Automotive
    - Company
    - Fleet Management
    - Tesla
    url: /providers/tessie/
  layer: domain
  name: Tessie
  provider: tessie
  says: ships the Tessie SDK or integration code
  source: https://github.com/evcc-io/evcc/tree/master/templates/definition/vehicle
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-200.20.10
    key: AE-200.20.10
    name: Vehicle Data Access
    url: /capabilities/connected-vehicles/
    via_parent: Connected Vehicles
  credit: null
  facts: &id002
    agent_band: agent-aware
    agent_readiness: 25.6
    band: developing
    in_catalog: true
    kin_score: 49.5
    mcp: &id125
      status: none
    slug: tibber
    status: profiled
    tags: &id126
    - ElectricityPricing
    - Energy
    - Smart Home
    - Smart Meter
    url: /providers/tibber/
  layer: domain
  name: Tibber
  provider: tibber
  says: ships the Tibber SDK or integration code
  source: https://github.com/evcc-io/evcc/tree/master/templates/definition/vehicle
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-3480.30
    key: charging-energy-and-tariff-management
    name: Charging Energy and Tariff Management
    url: /capabilities/charging-energy-and-tariff-management/
    via_parent: null
  credit: null
  facts: *id002
  layer: domain
  name: Tibber
  provider: tibber
  says: ships the Tibber SDK or integration code
  source: https://github.com/evcc-io/evcc/tree/master/templates/definition/tariff
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-200.20.10
    key: AE-200.20.10
    name: Vehicle Data Access
    url: /capabilities/connected-vehicles/
    via_parent: Connected Vehicles
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.6
    band: thin
    in_catalog: true
    kin_score: 31.0
    mcp: &id127
      status: none
    slug: toyota
    status: profiled
    tags: &id128
    - Automobiles
    - Cars
    - Connected Vehicles
    - Vehicles
    url: /providers/toyota/
  layer: domain
  name: Toyota
  provider: toyota
  says: ships the Toyota SDK or integration code
  source: https://github.com/evcc-io/evcc/tree/master/templates/definition/vehicle
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-200.20.10
    key: AE-200.20.10
    name: Vehicle Data Access
    url: /capabilities/connected-vehicles/
    via_parent: Connected Vehicles
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 18.6
    band: emerging
    in_catalog: true
    kin_score: 25.6
    mcp: &id129
      status: none
    slug: tronity
    status: profiled
    tags: &id130
    - Connected Vehicles
    - Electric Vehicles
    - Fleet Management
    - Telematics
    url: /providers/tronity/
  layer: domain
  name: TRONITY
  provider: tronity
  says: ships the TRONITY SDK or integration code
  source: https://github.com/evcc-io/evcc/tree/master/templates/definition/vehicle
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
    agent_band: agent-aware
    agent_readiness: 27.5
    band: thin
    in_catalog: true
    kin_score: 33.9
    mcp: &id131
      status: none
    slug: victron-energy
    status: profiled
    tags: &id132
    - Company
    - Energy
    - Off-Grid
    - Renewables
    url: /providers/victron-energy/
  layer: domain
  name: Victron Energy (VRM)
  provider: victron-energy
  says: ships the Victron Energy (VRM) SDK or integration code
  source: https://github.com/evcc-io/evcc/tree/master/templates/definition/tariff
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-200.20.10
    key: AE-200.20.10
    name: Vehicle Data Access
    url: /capabilities/connected-vehicles/
    via_parent: Connected Vehicles
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.7
    band: developing
    in_catalog: true
    kin_score: 45.5
    mcp: &id133
      status: none
    slug: volkswagen
    status: profiled
    tags: &id134
    - Automobiles
    - Automotive
    - Cars
    - Vehicles
    url: /providers/volkswagen/
  layer: domain
  name: Volkswagen Group
  provider: volkswagen
  says: ships the Volkswagen Group SDK or integration code
  source: https://github.com/evcc-io/evcc/tree/master/templates/definition/vehicle
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-200.20.10
    key: AE-200.20.10
    name: Vehicle Data Access
    url: /capabilities/connected-vehicles/
    via_parent: Connected Vehicles
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 18.8
    band: thin
    in_catalog: true
    kin_score: 27.7
    mcp: &id135
      status: none
    slug: volvo-cars
    status: profiled
    tags: &id136
    - Automotive
    - Connected Vehicles
    - Electric Vehicles
    - Telematics
    url: /providers/volvo-cars/
  layer: domain
  name: Volvo Cars
  provider: volvo-cars
  says: ships the Volvo Cars SDK or integration code
  source: https://github.com/evcc-io/evcc/tree/master/templates/definition/vehicle
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
    agent_readiness: 35.2
    band: developing
    in_catalog: true
    kin_score: 46.9
    mcp: &id137
      status: unknown
    slug: zaptec
    status: profiled
    tags: &id138
    - Company
    - EV Charging
    - Energy
    - Smart Charging
    url: /providers/zaptec/
  layer: domain
  name: Zaptec
  provider: zaptec
  says: ships the Zaptec SDK or integration code
  source: https://github.com/evcc-io/evcc/tree/master/charger
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-200.20.10
    key: AE-200.20.10
    name: Vehicle Data Access
    url: /capabilities/connected-vehicles/
    via_parent: Connected Vehicles
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 11.4
    mcp: &id139
      status: none
    slug: zero-motorcycles
    status: profiled
    tags: &id140
    - Automotive
    - Company
    - Electric Vehicles
    - Motorcycles
    url: /providers/zero-motorcycles/
  layer: domain
  name: Zero Motorcycles
  provider: zero-motorcycles
  says: ships the Zero Motorcycles SDK or integration code
  source: https://github.com/evcc-io/evcc/tree/master/templates/definition/vehicle
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/connected-car-ev-charging/evcc/
providers:
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 10.8
  mcp: *id003
  name: Aiways
  slug: aiways
  status: profiled
  tags: *id004
  url: /providers/aiways/
- agent_band: agent-ready
  agent_readiness: 46.4
  band: strong
  in_catalog: true
  kin_score: 65.1
  mcp: *id005
  name: Amber Electric
  slug: amber-electric
  status: profiled
  tags: *id006
  url: /providers/amber-electric/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 6.5
  mcp: *id007
  name: Audi Connect
  slug: audi-connect
  status: profiled
  tags: *id008
  url: /providers/audi-connect/
- agent_band: agent-aware
  agent_readiness: 28.4
  band: thin
  in_catalog: true
  kin_score: 26.8
  mcp: *id009
  name: aWATTar
  slug: awattar
  status: profiled
  tags: *id010
  url: /providers/awattar/
- agent_band: human-only
  agent_readiness: 0.6
  band: emerging
  in_catalog: true
  kin_score: 20.5
  mcp: *id011
  name: BMW
  slug: bmw
  status: profiled
  tags: *id012
  url: /providers/bmw/
- agent_band: agent-aware
  agent_readiness: 18.3
  band: emerging
  in_catalog: true
  kin_score: 11.2
  mcp: *id013
  name: Connected Cars
  slug: connectedcars-io
  status: profiled
  tags: *id014
  url: /providers/connectedcars-io/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 3.4
  mcp: *id015
  name: Deutscher Wetterdienst
  slug: deutscher-wetterdienst
  status: profiled
  tags: *id016
  url: /providers/deutscher-wetterdienst/
- agent_band: agent-ready
  agent_readiness: 29.2
  band: developing
  in_catalog: true
  kin_score: 48.6
  mcp: *id017
  name: Easee
  slug: easee
  status: profiled
  tags: *id018
  url: /providers/easee/
- agent_band: human-only
  agent_readiness: 2.8
  band: minimal
  in_catalog: true
  kin_score: 7.0
  mcp: *id019
  name: EDF (Tempo tariff)
  slug: edf
  status: profiled
  tags: *id020
  url: /providers/edf/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 11.8
  mcp: *id021
  name: EKZ
  slug: ekz
  status: profiled
  tags: *id022
  url: /providers/ekz/
- agent_band: agent-aware
  agent_readiness: 28.5
  band: thin
  in_catalog: true
  kin_score: 29.8
  mcp: *id023
  name: Electricity Maps
  slug: electricitymaps
  status: profiled
  tags: *id024
  url: /providers/electricitymaps/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 8.4
  mcp: *id025
  name: Elering
  slug: elering
  status: profiled
  tags: *id026
  url: /providers/elering/
- agent_band: agent-aware
  agent_readiness: 11.6
  band: minimal
  in_catalog: true
  kin_score: 7.7
  mcp: *id027
  name: Energinet
  slug: energinet
  status: profiled
  tags: *id028
  url: /providers/energinet/
- agent_band: agent-aware
  agent_readiness: 24.7
  band: emerging
  in_catalog: true
  kin_score: 22.7
  mcp: *id029
  name: Energy-Charts (Fraunhofer ISE)
  slug: energy-charts-api
  status: profiled
  tags: *id030
  url: /providers/energy-charts-api/
- agent_band: agent-ready
  agent_readiness: 34.0
  band: thin
  in_catalog: true
  kin_score: 33.4
  mcp: *id031
  name: ENTSO-E
  slug: entso-e
  status: profiled
  tags: *id032
  url: /providers/entso-e/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id033
  name: EVNotify
  slug: evnotify
  status: queued for profiling
  tags: *id034
  url: null
- agent_band: human-only
  agent_readiness: 2.8
  band: emerging
  in_catalog: true
  kin_score: 12.5
  mcp: *id035
  name: Fingrid
  slug: fingrid
  status: profiled
  tags: *id036
  url: /providers/fingrid/
- agent_band: agent-aware
  agent_readiness: 26.9
  band: thin
  in_catalog: true
  kin_score: 28.7
  mcp: *id037
  name: Ford
  slug: ford
  status: profiled
  tags: *id038
  url: /providers/ford/
- agent_band: agent-ready
  agent_readiness: 29.0
  band: thin
  in_catalog: true
  kin_score: 35.4
  mcp: *id039
  name: Forecast.Solar
  slug: forecast-solar
  status: profiled
  tags: *id040
  url: /providers/forecast-solar/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 14.2
  mcp: *id041
  name: Frank Energie
  slug: frank-energie
  status: profiled
  tags: *id042
  url: /providers/frank-energie/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 20.9
  mcp: *id043
  name: go-e
  slug: go-e
  status: profiled
  tags: *id044
  url: /providers/go-e/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 3.1
  mcp: *id045
  name: Groupe E
  slug: groupe-e
  status: profiled
  tags: *id046
  url: /providers/groupe-e/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id047
  name: GrünStromIndex (Corrently)
  slug: gruenstromindex
  status: queued for profiling
  tags: *id048
  url: null
- agent_band: agent-aware
  agent_readiness: 5.6
  band: thin
  in_catalog: true
  kin_score: 34.5
  mcp: *id049
  name: Home Assistant (self-hosted)
  slug: home-assistant
  status: profiled
  tags: *id050
  url: /providers/home-assistant/
- agent_band: agent-ready
  agent_readiness: 28.7
  band: developing
  in_catalog: true
  kin_score: 49.5
  mcp: *id051
  name: Hyundai
  slug: hyundai
  status: profiled
  tags: *id052
  url: /providers/hyundai/
- agent_band: agent-ready
  agent_readiness: 34.4
  band: strong
  in_catalog: true
  kin_score: 63.3
  mcp: *id053
  name: InfluxDB
  slug: influxdata
  status: profiled
  tags: *id054
  url: /providers/influxdata/
- agent_band: human-only
  agent_readiness: 2.5
  band: minimal
  in_catalog: true
  kin_score: 8.2
  mcp: *id055
  name: ioBroker (self-hosted)
  slug: iobroker
  status: profiled
  tags: *id056
  url: /providers/iobroker/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 13.6
  mcp: *id057
  name: JLR (Jaguar Land Rover)
  slug: jlr
  status: profiled
  tags: *id058
  url: /providers/jlr/
- agent_band: agent-aware
  agent_readiness: 16.9
  band: thin
  in_catalog: true
  kin_score: 32.9
  mcp: *id059
  name: Kia
  slug: kia
  status: profiled
  tags: *id060
  url: /providers/kia/
- agent_band: agent-aware
  agent_readiness: 14.8
  band: emerging
  in_catalog: true
  kin_score: 14.6
  mcp: *id061
  name: LiveWire
  slug: livewire
  status: profiled
  tags: *id062
  url: /providers/livewire/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 4.1
  mcp: *id063
  name: Mazda
  slug: mazda
  status: profiled
  tags: *id064
  url: /providers/mazda/
- agent_band: human-only
  agent_readiness: 0.6
  band: thin
  in_catalog: true
  kin_score: 29.3
  mcp: *id065
  name: Mercedes-Benz
  slug: mercedes-benz
  status: profiled
  tags: *id066
  url: /providers/mercedes-benz/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 2.2
  mcp: *id067
  name: MG (SAIC Motor)
  slug: saic-motor
  status: profiled
  tags: *id068
  url: /providers/saic-motor/
- agent_band: agent-aware
  agent_readiness: 24.0
  band: developing
  in_catalog: true
  kin_score: 43.5
  mcp: *id069
  name: National Energy System Operator (NESO)
  slug: neso
  status: profiled
  tags: *id070
  url: /providers/neso/
- agent_band: human-only
  agent_readiness: 2.5
  band: minimal
  in_catalog: true
  kin_score: 7.9
  mcp: *id071
  name: Nissan
  slug: nissan
  status: profiled
  tags: *id072
  url: /providers/nissan/
- agent_band: human-only
  agent_readiness: 4.4
  band: emerging
  in_catalog: true
  kin_score: 11.7
  mcp: *id073
  name: NIU
  slug: niu
  status: profiled
  tags: *id074
  url: /providers/niu/
- agent_band: agent-ready
  agent_readiness: 33.9
  band: thin
  in_catalog: true
  kin_score: 37.8
  mcp: *id075
  name: Nord Pool
  slug: nordpool
  status: profiled
  tags: *id076
  url: /providers/nordpool/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 15.5
  mcp: *id077
  name: ntfy
  slug: ntfy
  status: profiled
  tags: *id078
  url: /providers/ntfy/
- agent_band: agent-aware
  agent_readiness: 23.5
  band: developing
  in_catalog: true
  kin_score: 44.1
  mcp: *id079
  name: Octopus Energy
  slug: octopus-energy
  status: profiled
  tags: *id080
  url: /providers/octopus-energy/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 9.0
  mcp: *id081
  name: OMIE (Iberian power market)
  slug: omie-es
  status: profiled
  tags: *id082
  url: /providers/omie-es/
- agent_band: agent-aware
  agent_readiness: 17.6
  band: emerging
  in_catalog: true
  kin_score: 21.9
  mcp: *id083
  name: Open Vehicle Monitoring System (self-hosted)
  slug: ovms
  status: profiled
  tags: *id084
  url: /providers/ovms/
- agent_band: agent-aware
  agent_readiness: 17.4
  band: thin
  in_catalog: true
  kin_score: 28.3
  mcp: *id085
  name: Open-Meteo
  slug: open-meteo
  status: profiled
  tags: *id086
  url: /providers/open-meteo/
- agent_band: agent-ready
  agent_readiness: 30.8
  band: developing
  in_catalog: true
  kin_score: 45.8
  mcp: *id087
  name: Ostrom
  slug: ostrom
  status: profiled
  tags: *id088
  url: /providers/ostrom/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 6.8
  mcp: *id089
  name: Polestar
  slug: polestar-cars
  status: profiled
  tags: *id090
  url: /providers/polestar-cars/
- agent_band: agent-aware
  agent_readiness: 20.8
  band: thin
  in_catalog: true
  kin_score: 33.1
  mcp: *id091
  name: Porsche
  slug: porsche
  status: profiled
  tags: *id092
  url: /providers/porsche/
- agent_band: human-only
  agent_readiness: 2.5
  band: emerging
  in_catalog: true
  kin_score: 12.7
  mcp: *id093
  name: Pstryk
  slug: pstryk
  status: profiled
  tags: *id094
  url: /providers/pstryk/
- agent_band: agent-aware
  agent_readiness: 21.6
  band: thin
  in_catalog: true
  kin_score: 28.1
  mcp: *id095
  name: Pushover
  slug: pushover
  status: profiled
  tags: *id096
  url: /providers/pushover/
- agent_band: agent-aware
  agent_readiness: 22.2
  band: emerging
  in_catalog: true
  kin_score: 21.9
  mcp: *id097
  name: Red Electrica (e-sios)
  slug: esios-red-electrica
  status: profiled
  tags: *id098
  url: /providers/esios-red-electrica/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 21.1
  mcp: *id099
  name: Renault Group
  slug: renault-group
  status: profiled
  tags: *id100
  url: /providers/renault-group/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 4.9
  mcp: *id101
  name: smart Europe
  slug: smart-com
  status: profiled
  tags: *id102
  url: /providers/smart-com/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 11.9
  mcp: *id103
  name: smartENERGY
  slug: smartenergy-at
  status: profiled
  tags: *id104
  url: /providers/smartenergy-at/
- agent_band: agent-ready
  agent_readiness: 29.6
  band: developing
  in_catalog: true
  kin_score: 53.7
  mcp: *id105
  name: Solcast
  slug: solcast
  status: profiled
  tags: *id106
  url: /providers/solcast/
- agent_band: agent-aware
  agent_readiness: 19.4
  band: thin
  in_catalog: true
  kin_score: 27.4
  mcp: *id107
  name: Stekker
  slug: stekker
  status: profiled
  tags: *id108
  url: /providers/stekker/
- agent_band: agent-aware
  agent_readiness: 19.9
  band: emerging
  in_catalog: true
  kin_score: 22.8
  mcp: *id109
  name: Stellantis
  slug: stellantis
  status: profiled
  tags: *id110
  url: /providers/stellantis/
- agent_band: human-only
  agent_readiness: 0.6
  band: minimal
  in_catalog: true
  kin_score: 7.1
  mcp: *id111
  name: Subaru
  slug: subaru-of-america
  status: profiled
  tags: *id112
  url: /providers/subaru-of-america/
- agent_band: agent-aware
  agent_readiness: 25.3
  band: strong
  in_catalog: true
  kin_score: 56.8
  mcp: *id113
  name: Telegram
  slug: telegram
  status: profiled
  tags: *id114
  url: /providers/telegram/
- agent_band: agent-aware
  agent_readiness: 22.3
  band: thin
  in_catalog: true
  kin_score: 34.8
  mcp: *id115
  name: Tesla
  slug: tesla
  status: profiled
  tags: *id116
  url: /providers/tesla/
- agent_band: agent-aware
  agent_readiness: 18.3
  band: emerging
  in_catalog: true
  kin_score: 15.0
  mcp: *id117
  name: TeslaFi
  slug: teslafi
  status: profiled
  tags: *id118
  url: /providers/teslafi/
- agent_band: agent-aware
  agent_readiness: 23.2
  band: emerging
  in_catalog: true
  kin_score: 22.4
  mcp: *id119
  name: TeslaLogger (self-hosted)
  slug: teslalogger
  status: profiled
  tags: *id120
  url: /providers/teslalogger/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 4.1
  mcp: *id121
  name: TeslaMate (self-hosted)
  slug: teslamate
  status: profiled
  tags: *id122
  url: /providers/teslamate/
- agent_band: agent-aware
  agent_readiness: 25.6
  band: developing
  in_catalog: true
  kin_score: 47.3
  mcp: *id123
  name: Tessie
  slug: tessie
  status: profiled
  tags: *id124
  url: /providers/tessie/
- agent_band: agent-aware
  agent_readiness: 25.6
  band: developing
  in_catalog: true
  kin_score: 49.5
  mcp: *id125
  name: Tibber
  slug: tibber
  status: profiled
  tags: *id126
  url: /providers/tibber/
- agent_band: agent-aware
  agent_readiness: 25.6
  band: thin
  in_catalog: true
  kin_score: 31.0
  mcp: *id127
  name: Toyota
  slug: toyota
  status: profiled
  tags: *id128
  url: /providers/toyota/
- agent_band: agent-aware
  agent_readiness: 18.6
  band: emerging
  in_catalog: true
  kin_score: 25.6
  mcp: *id129
  name: TRONITY
  slug: tronity
  status: profiled
  tags: *id130
  url: /providers/tronity/
- agent_band: agent-aware
  agent_readiness: 27.5
  band: thin
  in_catalog: true
  kin_score: 33.9
  mcp: *id131
  name: Victron Energy (VRM)
  slug: victron-energy
  status: profiled
  tags: *id132
  url: /providers/victron-energy/
- agent_band: agent-aware
  agent_readiness: 24.7
  band: developing
  in_catalog: true
  kin_score: 45.5
  mcp: *id133
  name: Volkswagen Group
  slug: volkswagen
  status: profiled
  tags: *id134
  url: /providers/volkswagen/
- agent_band: agent-aware
  agent_readiness: 18.8
  band: thin
  in_catalog: true
  kin_score: 27.7
  mcp: *id135
  name: Volvo Cars
  slug: volvo-cars
  status: profiled
  tags: *id136
  url: /providers/volvo-cars/
- agent_band: agent-ready
  agent_readiness: 35.2
  band: developing
  in_catalog: true
  kin_score: 46.9
  mcp: *id137
  name: Zaptec
  slug: zaptec
  status: profiled
  tags: *id138
  url: /providers/zaptec/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 11.4
  mcp: *id139
  name: Zero Motorcycles
  slug: zero-motorcycles
  status: profiled
  tags: *id140
  url: /providers/zero-motorcycles/
siblings:
- name: ChargePoint
  rows: 6
  url: /applications/connected-car-ev-charging/chargepoint/
- name: Electrify America
  rows: 9
  url: /applications/connected-car-ev-charging/electrify-america/
- name: Open Charge Map
  rows: 13
  url: /applications/connected-car-ev-charging/open-charge-map/
- name: openWB
  rows: 30
  url: /applications/connected-car-ev-charging/openwb/
- name: TeslaLogger
  rows: 15
  url: /applications/connected-car-ev-charging/teslalogger/
- name: TeslaMate
  rows: 3
  url: /applications/connected-car-ev-charging/teslamate/
sitemap: true
title: 'evcc: Connected Car & EV Charging reference app'
---
