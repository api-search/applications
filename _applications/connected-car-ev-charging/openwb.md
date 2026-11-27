---
app: openWB
app_slug: openwb
app_url: https://github.com/openWB/core
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-3480.30
  key: charging-energy-and-tariff-management
  layer: domain
  name: Charging Energy and Tariff Management
  providers:
  - aWATTar
  - EKZ
  - Energy-Charts (Fraunhofer ISE)
  - Groupe E
  - Naturstrom
  - Octopus Energy
  - Ostrom
  - rabot.energy
  - smartENERGY
  - Tibber
  - Voltego
  - WestfalenWIND
  url: /capabilities/charging-energy-and-tariff-management/
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
  - BMW
  - BYD
  - evcc (self-hosted)
  - EVNotify
  - Kia
  - MG (SAIC Motor)
  - Nissan
  - Open Vehicle Monitoring System (self-hosted)
  - Polestar
  - Porsche
  - Renault Group
  - smart Europe
  - Stellantis
  - Tesla
  - TRONITY
  - Volkswagen Group
  url: /capabilities/connected-vehicles/
  via_parent: Connected Vehicles
category:
  id: connected-car-ev-charging
  name: Connected Car & EV Charging
  url: /applications/connected-car-ev-charging/
counts:
  declared: 0
  observed: 30
credits: []
evidence:
- route: source code
  url: https://github.com/openWB/core/tree/master/packages/modules/devices
- route: source code
  url: https://github.com/openWB/core/tree/master/packages/modules/electricity_pricing/flexible_tariffs
- route: source code
  url: https://github.com/openWB/core/tree/master/packages/modules/vehicles
integrations:
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
  source: https://github.com/openWB/core/tree/master/packages/modules/electricity_pricing/flexible_tariffs
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
    mcp: &id003
      status: unknown
    slug: bmw
    status: profiled
    tags: &id004
    - Automobiles
    - Automotive
    - Cars
    - Vehicles
    url: /providers/bmw/
  layer: domain
  name: BMW
  provider: bmw
  says: ships the BMW SDK or integration code
  source: https://github.com/openWB/core/tree/master/packages/modules/vehicles
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
    kin_score: 5.0
    mcp: &id005
      status: none
    slug: byd
    status: profiled
    tags: &id006
    - Automotive
    - Company
    - Electric Vehicles
    - Technology
    url: /providers/byd/
  layer: domain
  name: BYD
  provider: byd
  says: ships the BYD SDK or integration code
  source: https://github.com/openWB/core/tree/master/packages/modules/vehicles
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
    mcp: &id007
      status: unknown
    slug: ekz
    status: profiled
    tags: &id008
    - Energy
    - Renewables
    - Switzerland
    - Utilities
    url: /providers/ekz/
  layer: domain
  name: EKZ
  provider: ekz
  says: ships the EKZ SDK or integration code
  source: https://github.com/openWB/core/tree/master/packages/modules/electricity_pricing/flexible_tariffs
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
    mcp: &id009
      status: unknown
    slug: energy-charts-api
    status: profiled
    tags: &id010
    - Electricity
    - Energy
    - Grid
    - Renewables
    url: /providers/energy-charts-api/
  layer: domain
  name: Energy-Charts (Fraunhofer ISE)
  provider: energy-charts-api
  says: ships the Energy-Charts (Fraunhofer ISE) SDK or integration code
  source: https://github.com/openWB/core/tree/master/packages/modules/electricity_pricing/flexible_tariffs
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
    agent_readiness: 32.6
    band: developing
    in_catalog: true
    kin_score: 45.0
    mcp: &id011
      source: https://docs.evcc.io/en/integrations/mcp.md
      status: verified
    slug: evcc
    status: profiled
    tags: &id012
    - Company
    - Electric Vehicles
    - Open Source
    - Smart Charging
    url: /providers/evcc/
  layer: domain
  name: evcc (self-hosted)
  provider: evcc
  says: ships the evcc (self-hosted) SDK or integration code
  source: https://github.com/openWB/core/tree/master/packages/modules/vehicles
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
    mcp: &id013
      status: unchecked
    slug: evnotify
    status: queued for profiling
    tags: &id014 []
    url: null
  layer: domain
  name: EVNotify
  provider: evnotify
  says: ships the EVNotify SDK or integration code
  source: https://github.com/openWB/core/tree/master/packages/modules/vehicles
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
  source: https://github.com/openWB/core/tree/master/packages/modules/electricity_pricing/flexible_tariffs
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
    mcp: &id017
      source: https://www.home-assistant.io/integrations/mcp_server/
      status: verified
    slug: home-assistant
    status: profiled
    tags: &id018
    - Community
    - Home Automation
    - IoT
    - Open Source
    url: /providers/home-assistant/
  layer: domain
  name: Home Assistant (self-hosted)
  provider: home-assistant
  says: ships the Home Assistant (self-hosted) SDK or integration code
  source: https://github.com/openWB/core/tree/master/packages/modules/vehicles
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
    mcp: &id019
      source: https://github.com/ioBroker/ioBroker.mcp
      status: verified
    slug: iobroker
    status: profiled
    tags: &id020
    - Company
    - Home Automation
    - IoT
    - Open Source
    url: /providers/iobroker/
  layer: domain
  name: ioBroker (self-hosted)
  provider: iobroker
  says: ships the ioBroker (self-hosted) SDK or integration code
  source: https://github.com/openWB/core/tree/master/packages/modules/vehicles
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
    mcp: &id021
      status: none
    slug: kia
    status: profiled
    tags: &id022
    - Automotive
    - Connected Vehicles
    - OAuth
    - Vehicle Data
    url: /providers/kia/
  layer: domain
  name: Kia
  provider: kia
  says: ships the Kia SDK or integration code
  source: https://github.com/openWB/core/tree/master/packages/modules/vehicles
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
    mcp: &id023
      status: unknown
    slug: saic-motor
    status: profiled
    tags: &id024
    - Automotive
    - China
    - Company
    - Manufacturing
    url: /providers/saic-motor/
  layer: domain
  name: MG (SAIC Motor)
  provider: saic-motor
  says: ships the MG (SAIC Motor) SDK or integration code
  source: https://github.com/openWB/core/tree/master/packages/modules/vehicles
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
    kin_score: 12.3
    mcp: &id025
      status: unknown
    slug: naturstrom
    status: profiled
    tags: &id026
    - Electricity
    - Energy
    - Germany
    - Renewables
    url: /providers/naturstrom/
  layer: domain
  name: Naturstrom
  provider: naturstrom
  says: ships the Naturstrom SDK or integration code
  source: https://github.com/openWB/core/tree/master/packages/modules/electricity_pricing/flexible_tariffs
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
    mcp: &id027
      status: unknown
    slug: nissan
    status: profiled
    tags: &id028
    - Automobiles
    - Cars
    - Vehicles
    url: /providers/nissan/
  layer: domain
  name: Nissan
  provider: nissan
  says: ships the Nissan SDK or integration code
  source: https://github.com/openWB/core/tree/master/packages/modules/vehicles
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
    agent_readiness: 23.5
    band: developing
    in_catalog: true
    kin_score: 44.1
    mcp: &id029
      status: none
    slug: octopus-energy
    status: profiled
    tags: &id030
    - Electricity
    - Energy
    - Gas
    - Renewable Energy
    url: /providers/octopus-energy/
  layer: domain
  name: Octopus Energy
  provider: octopus-energy
  says: ships the Octopus Energy SDK or integration code
  source: https://github.com/openWB/core/tree/master/packages/modules/electricity_pricing/flexible_tariffs
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
    mcp: &id031
      status: none
    slug: ovms
    status: profiled
    tags: &id032
    - Company
    - Electric Vehicles
    - Open Source
    - Telematics
    url: /providers/ovms/
  layer: domain
  name: Open Vehicle Monitoring System (self-hosted)
  provider: ovms
  says: ships the Open Vehicle Monitoring System (self-hosted) SDK or integration code
  source: https://github.com/openWB/core/tree/master/packages/modules/vehicles
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
    mcp: &id033
      status: none
    slug: ostrom
    status: profiled
    tags: &id034
    - Company
    - Electricity
    - Energy
    - Renewable Energy
    url: /providers/ostrom/
  layer: domain
  name: Ostrom
  provider: ostrom
  says: ships the Ostrom SDK or integration code
  source: https://github.com/openWB/core/tree/master/packages/modules/electricity_pricing/flexible_tariffs
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
    mcp: &id035
      status: none
    slug: polestar-cars
    status: profiled
    tags: &id036
    - Automotive
    - Connected Vehicles
    - Electric Vehicles
    - Premium Vehicles
    url: /providers/polestar-cars/
  layer: domain
  name: Polestar
  provider: polestar-cars
  says: ships the Polestar SDK or integration code
  source: https://github.com/openWB/core/tree/master/packages/modules/vehicles
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
    mcp: &id037
      status: none
    slug: porsche
    status: profiled
    tags: &id038
    - Automobiles
    - Automotive
    - Cars
    - Vehicles
    url: /providers/porsche/
  layer: domain
  name: Porsche
  provider: porsche
  says: ships the Porsche SDK or integration code
  source: https://github.com/openWB/core/tree/master/packages/modules/vehicles
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
    agent_readiness: 0.7
    band: minimal
    in_catalog: true
    kin_score: 10.6
    mcp: &id039
      status: unknown
    slug: rabotenergy
    status: profiled
    tags: &id040
    - Company
    - Consumer
    - Electricity
    - Energy
    url: /providers/rabotenergy/
  layer: domain
  name: rabot.energy
  provider: rabotenergy
  says: ships the rabot.energy SDK or integration code
  source: https://github.com/openWB/core/tree/master/packages/modules/electricity_pricing/flexible_tariffs
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
    mcp: &id041
      status: none
    slug: renault-group
    status: profiled
    tags: &id042
    - Android Automotive
    - Automotive
    - Company
    - In-Vehicle Apps
    url: /providers/renault-group/
  layer: domain
  name: Renault Group
  provider: renault-group
  says: ships the Renault Group SDK or integration code
  source: https://github.com/openWB/core/tree/master/packages/modules/vehicles
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
    mcp: &id043
      status: unknown
    slug: smart-com
    status: profiled
    tags: &id044
    - Company
    url: /providers/smart-com/
  layer: domain
  name: smart Europe
  provider: smart-com
  says: ships the smart Europe SDK or integration code
  source: https://github.com/openWB/core/tree/master/packages/modules/vehicles
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
    mcp: &id045
      status: none
    slug: smartenergy-at
    status: profiled
    tags: &id046
    - Austria
    - Energy
    - Renewables
    - Smart Grid
    url: /providers/smartenergy-at/
  layer: domain
  name: smartENERGY
  provider: smartenergy-at
  says: ships the smartENERGY SDK or integration code
  source: https://github.com/openWB/core/tree/master/packages/modules/electricity_pricing/flexible_tariffs
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
    mcp: &id047
      status: none
    slug: stellantis
    status: profiled
    tags: &id048
    - Automotive
    - Company
    - Manufacturing
    - Mobility
    url: /providers/stellantis/
  layer: domain
  name: Stellantis
  provider: stellantis
  says: ships the Stellantis SDK or integration code
  source: https://github.com/openWB/core/tree/master/packages/modules/vehicles
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
    mcp: &id049
      status: none
    slug: tesla
    status: profiled
    tags: &id050
    - Automobiles
    - Cars
    - Electric Vehicles
    - Vehicles
    url: /providers/tesla/
  layer: domain
  name: Tesla
  provider: tesla
  says: ships the Tesla SDK or integration code
  source: https://github.com/openWB/core/tree/master/packages/modules/vehicles
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
  source: https://github.com/openWB/core/tree/master/packages/modules/electricity_pricing/flexible_tariffs
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
    mcp: &id053
      status: none
    slug: tronity
    status: profiled
    tags: &id054
    - Connected Vehicles
    - Electric Vehicles
    - Fleet Management
    - Telematics
    url: /providers/tronity/
  layer: domain
  name: TRONITY
  provider: tronity
  says: ships the TRONITY SDK or integration code
  source: https://github.com/openWB/core/tree/master/packages/modules/vehicles
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
    mcp: &id055
      status: none
    slug: volkswagen
    status: profiled
    tags: &id056
    - Automobiles
    - Automotive
    - Cars
    - Vehicles
    url: /providers/volkswagen/
  layer: domain
  name: Volkswagen Group
  provider: volkswagen
  says: ships the Volkswagen Group SDK or integration code
  source: https://github.com/openWB/core/tree/master/packages/modules/vehicles
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
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id057
      status: unchecked
    slug: voltego
    status: queued for profiling
    tags: &id058 []
    url: null
  layer: domain
  name: Voltego
  provider: voltego
  says: ships the Voltego SDK or integration code
  source: https://github.com/openWB/core/tree/master/packages/modules/electricity_pricing/flexible_tariffs
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
    kin_score: 5.7
    mcp: &id059
      status: unknown
    slug: westfalenwind
    status: profiled
    tags: &id060
    - Company
    - Germany
    - Renewable Energy
    - Wind Power
    url: /providers/westfalenwind/
  layer: domain
  name: WestfalenWIND
  provider: westfalenwind
  says: ships the WestfalenWIND SDK or integration code
  source: https://github.com/openWB/core/tree/master/packages/modules/electricity_pricing/flexible_tariffs
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/connected-car-ev-charging/openwb/
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
  agent_readiness: 0.6
  band: emerging
  in_catalog: true
  kin_score: 20.5
  mcp: *id003
  name: BMW
  slug: bmw
  status: profiled
  tags: *id004
  url: /providers/bmw/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 5.0
  mcp: *id005
  name: BYD
  slug: byd
  status: profiled
  tags: *id006
  url: /providers/byd/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 11.8
  mcp: *id007
  name: EKZ
  slug: ekz
  status: profiled
  tags: *id008
  url: /providers/ekz/
- agent_band: agent-aware
  agent_readiness: 24.7
  band: emerging
  in_catalog: true
  kin_score: 22.7
  mcp: *id009
  name: Energy-Charts (Fraunhofer ISE)
  slug: energy-charts-api
  status: profiled
  tags: *id010
  url: /providers/energy-charts-api/
- agent_band: agent-ready
  agent_readiness: 32.6
  band: developing
  in_catalog: true
  kin_score: 45.0
  mcp: *id011
  name: evcc (self-hosted)
  slug: evcc
  status: profiled
  tags: *id012
  url: /providers/evcc/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id013
  name: EVNotify
  slug: evnotify
  status: queued for profiling
  tags: *id014
  url: null
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
- agent_band: agent-aware
  agent_readiness: 5.6
  band: thin
  in_catalog: true
  kin_score: 34.5
  mcp: *id017
  name: Home Assistant (self-hosted)
  slug: home-assistant
  status: profiled
  tags: *id018
  url: /providers/home-assistant/
- agent_band: human-only
  agent_readiness: 2.5
  band: minimal
  in_catalog: true
  kin_score: 8.2
  mcp: *id019
  name: ioBroker (self-hosted)
  slug: iobroker
  status: profiled
  tags: *id020
  url: /providers/iobroker/
- agent_band: agent-aware
  agent_readiness: 16.9
  band: thin
  in_catalog: true
  kin_score: 32.9
  mcp: *id021
  name: Kia
  slug: kia
  status: profiled
  tags: *id022
  url: /providers/kia/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 2.2
  mcp: *id023
  name: MG (SAIC Motor)
  slug: saic-motor
  status: profiled
  tags: *id024
  url: /providers/saic-motor/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 12.3
  mcp: *id025
  name: Naturstrom
  slug: naturstrom
  status: profiled
  tags: *id026
  url: /providers/naturstrom/
- agent_band: human-only
  agent_readiness: 2.5
  band: minimal
  in_catalog: true
  kin_score: 7.9
  mcp: *id027
  name: Nissan
  slug: nissan
  status: profiled
  tags: *id028
  url: /providers/nissan/
- agent_band: agent-aware
  agent_readiness: 23.5
  band: developing
  in_catalog: true
  kin_score: 44.1
  mcp: *id029
  name: Octopus Energy
  slug: octopus-energy
  status: profiled
  tags: *id030
  url: /providers/octopus-energy/
- agent_band: agent-aware
  agent_readiness: 17.6
  band: emerging
  in_catalog: true
  kin_score: 21.9
  mcp: *id031
  name: Open Vehicle Monitoring System (self-hosted)
  slug: ovms
  status: profiled
  tags: *id032
  url: /providers/ovms/
- agent_band: agent-ready
  agent_readiness: 30.8
  band: developing
  in_catalog: true
  kin_score: 45.8
  mcp: *id033
  name: Ostrom
  slug: ostrom
  status: profiled
  tags: *id034
  url: /providers/ostrom/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 6.8
  mcp: *id035
  name: Polestar
  slug: polestar-cars
  status: profiled
  tags: *id036
  url: /providers/polestar-cars/
- agent_band: agent-aware
  agent_readiness: 20.8
  band: thin
  in_catalog: true
  kin_score: 33.1
  mcp: *id037
  name: Porsche
  slug: porsche
  status: profiled
  tags: *id038
  url: /providers/porsche/
- agent_band: human-only
  agent_readiness: 0.7
  band: minimal
  in_catalog: true
  kin_score: 10.6
  mcp: *id039
  name: rabot.energy
  slug: rabotenergy
  status: profiled
  tags: *id040
  url: /providers/rabotenergy/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 21.1
  mcp: *id041
  name: Renault Group
  slug: renault-group
  status: profiled
  tags: *id042
  url: /providers/renault-group/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 4.9
  mcp: *id043
  name: smart Europe
  slug: smart-com
  status: profiled
  tags: *id044
  url: /providers/smart-com/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 11.9
  mcp: *id045
  name: smartENERGY
  slug: smartenergy-at
  status: profiled
  tags: *id046
  url: /providers/smartenergy-at/
- agent_band: agent-aware
  agent_readiness: 19.9
  band: emerging
  in_catalog: true
  kin_score: 22.8
  mcp: *id047
  name: Stellantis
  slug: stellantis
  status: profiled
  tags: *id048
  url: /providers/stellantis/
- agent_band: agent-aware
  agent_readiness: 22.3
  band: thin
  in_catalog: true
  kin_score: 34.8
  mcp: *id049
  name: Tesla
  slug: tesla
  status: profiled
  tags: *id050
  url: /providers/tesla/
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
  agent_readiness: 18.6
  band: emerging
  in_catalog: true
  kin_score: 25.6
  mcp: *id053
  name: TRONITY
  slug: tronity
  status: profiled
  tags: *id054
  url: /providers/tronity/
- agent_band: agent-aware
  agent_readiness: 24.7
  band: developing
  in_catalog: true
  kin_score: 45.5
  mcp: *id055
  name: Volkswagen Group
  slug: volkswagen
  status: profiled
  tags: *id056
  url: /providers/volkswagen/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id057
  name: Voltego
  slug: voltego
  status: queued for profiling
  tags: *id058
  url: null
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 5.7
  mcp: *id059
  name: WestfalenWIND
  slug: westfalenwind
  status: profiled
  tags: *id060
  url: /providers/westfalenwind/
siblings:
- name: ChargePoint
  rows: 6
  url: /applications/connected-car-ev-charging/chargepoint/
- name: Electrify America
  rows: 9
  url: /applications/connected-car-ev-charging/electrify-america/
- name: evcc
  rows: 71
  url: /applications/connected-car-ev-charging/evcc/
- name: Open Charge Map
  rows: 13
  url: /applications/connected-car-ev-charging/open-charge-map/
- name: TeslaLogger
  rows: 15
  url: /applications/connected-car-ev-charging/teslalogger/
- name: TeslaMate
  rows: 3
  url: /applications/connected-car-ev-charging/teslamate/
sitemap: true
title: 'openWB: Connected Car & EV Charging reference app'
---
