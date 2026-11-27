---
access: understanding
agent_layer:
- app: evcc
  finding: evcc ships its own MCP server (server/mcp, built on github.com/evcc-io/openapi-mcp from its OpenAPI description)
  source: https://raw.githubusercontent.com/evcc-io/evcc/master/go.mod
  tier: observed
apps:
- anchor: evcc
  counts:
    declared: 0
    observed: 71
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
    layer: domain
    name: Zero Motorcycles
    provider: zero-motorcycles
    says: ships the Zero Motorcycles SDK or integration code
    source: https://github.com/evcc-io/evcc/tree/master/templates/definition/vehicle
    tier: observed
  kind: self-hosted
  name: evcc
  page: /applications/connected-car-ev-charging/evcc/
  slug: evcc
  url: https://github.com/evcc-io/evcc
- anchor: teslamate
  counts:
    declared: 0
    observed: 3
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/teslamate-org/teslamate/main/elixir/mix.exs
  - route: source code
    url: https://github.com/teslamate-org/teslamate/blob/main/elixir/lib/tesla_api.ex
  - route: source code
    url: https://github.com/teslamate-org/teslamate/blob/main/elixir/lib/teslamate/locations/geocoder.ex
  - route: source code
    url: https://github.com/teslamate-org/teslamate/tree/main/grafana
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: common
    name: Grafana
    provider: grafana-com
    says: ships the Grafana SDK or integration code
    source: https://github.com/teslamate-org/teslamate/tree/main/grafana
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120.10.20
      key: AE-120.10.20
      name: Reverse Geocoding
      url: /capabilities/geocoding/
      via_parent: Geocoding
    credit: null
    layer: common
    name: Nominatim
    provider: nominatim
    says: ships the Nominatim SDK or integration code
    source: https://github.com/teslamate-org/teslamate/blob/main/elixir/lib/teslamate/locations/geocoder.ex
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
    name: Tesla
    provider: tesla
    says: ships the Tesla SDK or integration code
    source: https://github.com/teslamate-org/teslamate/blob/main/elixir/lib/tesla_api.ex
    tier: observed
  kind: self-hosted
  name: TeslaMate
  page: /applications/connected-car-ev-charging/teslamate/
  slug: teslamate
  url: https://github.com/teslamate-org/teslamate
- anchor: openwb
  counts:
    declared: 0
    observed: 30
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
    layer: domain
    name: WestfalenWIND
    provider: westfalenwind
    says: ships the WestfalenWIND SDK or integration code
    source: https://github.com/openWB/core/tree/master/packages/modules/electricity_pricing/flexible_tariffs
    tier: observed
  kind: self-hosted
  name: openWB
  page: /applications/connected-car-ev-charging/openwb/
  slug: openwb
  url: https://github.com/openWB/core
- anchor: teslalogger
  counts:
    declared: 6
    observed: 9
  evidence:
  - route: documentation
    url: https://github.com/bassmaster187/TeslaLogger/blob/master/wallbox.md
  - route: source code
    url: https://github.com/bassmaster187/TeslaLogger/blob/master/TeslaLogger/MapQuestMapProvider.cs
  - route: source code
    url: https://github.com/bassmaster187/TeslaLogger/blob/master/TeslaLogger/ScanMyTesla.cs
  - route: source code
    url: https://github.com/bassmaster187/TeslaLogger/blob/master/TeslaLogger/WebHelper.cs
  - route: source code
    url: https://github.com/bassmaster187/TeslaLogger/tree/master/TeslaFi-Import
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-120.30
      key: AE-120.30
      name: Routing & Navigation
      url: /capabilities/routing-navigation/
      via_parent: null
    credit: null
    layer: domain
    name: A Better Route Planner (Iternio)
    provider: iternio
    says: ships the A Better Route Planner (Iternio) SDK or integration code
    source: https://github.com/bassmaster187/TeslaLogger/blob/master/TeslaLogger/WebHelper.cs
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120.10.20
      key: AE-120.10.20
      name: Reverse Geocoding
      url: /capabilities/geocoding/
      via_parent: Geocoding
    credit: null
    layer: common
    name: MapQuest
    provider: mapquest
    says: ships the MapQuest SDK or integration code
    source: https://github.com/bassmaster187/TeslaLogger/blob/master/TeslaLogger/MapQuestMapProvider.cs
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120.10.20
      key: AE-120.10.20
      name: Reverse Geocoding
      url: /capabilities/geocoding/
      via_parent: Geocoding
    credit: null
    layer: common
    name: Nominatim
    provider: nominatim
    says: ships the Nominatim SDK or integration code
    source: https://github.com/bassmaster187/TeslaLogger/blob/master/TeslaLogger/WebHelper.cs
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120.70
      key: AE-120.70
      name: Elevation & Terrain Data
      url: /capabilities/elevation-terrain-data/
      via_parent: null
    credit: null
    layer: common
    name: Open-Elevation
    provider: open-elevation
    says: ships the Open-Elevation SDK or integration code
    source: https://github.com/bassmaster187/TeslaLogger/blob/master/TeslaLogger/WebHelper.cs
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
    name: Scan My Tesla
    provider: scanmytesla
    says: ships the Scan My Tesla SDK or integration code
    source: https://github.com/bassmaster187/TeslaLogger/blob/master/TeslaLogger/ScanMyTesla.cs
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
    name: supercharge.bingo
    provider: supercharge-bingo
    says: ships the supercharge.bingo SDK or integration code
    source: https://github.com/bassmaster187/TeslaLogger/blob/master/TeslaLogger/WebHelper.cs
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
    name: Tesla
    provider: tesla
    says: ships the Tesla SDK or integration code
    source: https://github.com/bassmaster187/TeslaLogger/blob/master/TeslaLogger/WebHelper.cs
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
    name: TeslaFi
    provider: teslafi
    says: ships the TeslaFi SDK or integration code
    source: https://github.com/bassmaster187/TeslaLogger/tree/master/TeslaFi-Import
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
    name: TeslaMate (self-hosted)
    provider: teslamate
    says: ships the TeslaMate (self-hosted) SDK or integration code
    source: https://github.com/bassmaster187/TeslaLogger/tree/master/Teslamate-Import
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
    name: evcc (self-hosted)
    provider: evcc
    says: lists evcc (self-hosted) as an integration
    source: https://github.com/bassmaster187/TeslaLogger/blob/master/wallbox.md
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-200.20.20
      key: AE-200.20.20
      name: EV Charging
      url: /capabilities/connected-vehicles/
      via_parent: Connected Vehicles
    credit: null
    layer: domain
    name: go-e
    provider: go-e
    says: lists go-e as an integration
    source: https://github.com/bassmaster187/TeslaLogger/blob/master/wallbox.md
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-200.20.20
      key: AE-200.20.20
      name: EV Charging
      url: /capabilities/connected-vehicles/
      via_parent: Connected Vehicles
    credit: null
    layer: domain
    name: KEBA
    provider: keba
    says: lists KEBA as an integration
    source: https://github.com/bassmaster187/TeslaLogger/blob/master/wallbox.md
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-200.20.20
      key: AE-200.20.20
      name: EV Charging
      url: /capabilities/connected-vehicles/
      via_parent: Connected Vehicles
    credit: null
    layer: domain
    name: openWB (self-hosted)
    provider: openwb
    says: lists openWB (self-hosted) as an integration
    source: https://github.com/bassmaster187/TeslaLogger/blob/master/wallbox.md
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-200.30
      key: AE-200.30
      name: Home Energy
      url: /capabilities/home-energy/
      via_parent: null
    credit: null
    layer: domain
    name: Shelly
    provider: shelly
    says: lists Shelly as an integration
    source: https://github.com/bassmaster187/TeslaLogger/blob/master/wallbox.md
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-200.20.20
      key: AE-200.20.20
      name: EV Charging
      url: /capabilities/connected-vehicles/
      via_parent: Connected Vehicles
    credit: null
    layer: domain
    name: Tesla
    provider: tesla
    says: lists Tesla as an integration
    source: https://github.com/bassmaster187/TeslaLogger/blob/master/wallbox.md
    tier: declared
  kind: self-hosted
  name: TeslaLogger
  page: /applications/connected-car-ev-charging/teslalogger/
  slug: teslalogger
  url: https://github.com/bassmaster187/TeslaLogger
- anchor: open-charge-map
  counts:
    declared: 0
    observed: 13
  evidence:
  - route: source code
    url: https://github.com/openchargemap/ocm-system/tree/master/Import/OCM.Import.Common/Providers
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-200.20.20
      key: AE-200.20.20
      name: EV Charging
      url: /capabilities/connected-vehicles/
      via_parent: Connected Vehicles
    credit: null
    layer: domain
    name: ChargePoint
    provider: chargepoint
    says: ships the ChargePoint SDK or integration code
    source: https://github.com/openchargemap/ocm-system/blob/master/Import/OCM.Import.Common/Providers/ImportProvider_CoulombChargepoint.cs
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
    name: Chargesini
    provider: chargesini
    says: ships the Chargesini SDK or integration code
    source: https://github.com/openchargemap/ocm-system/blob/master/Import/OCM.Import.Common/Providers/OCPI/ImportProvider_Chargesini.cs
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
    name: data.gouv.fr
    provider: data-gouv-fr
    says: ships the data.gouv.fr SDK or integration code
    source: https://github.com/openchargemap/ocm-system/blob/master/Import/OCM.Import.Common/Providers/ImportProvider_DataGouvFr.cs
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
    name: Department of Energy (AFDC)
    provider: doe
    says: ships the Department of Energy (AFDC) SDK or integration code
    source: https://github.com/openchargemap/ocm-system/blob/master/Import/OCM.Import.Common/Providers/AFDC/ImportProvider_AFDC.cs
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
    name: ESB ecars
    provider: esb
    says: ships the ESB ecars SDK or integration code
    source: https://github.com/openchargemap/ocm-system/blob/master/Import/OCM.Import.Common/Providers/ImportProvider_ESB_eCars.cs
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
    name: EV24
    provider: ev24
    says: ships the EV24 SDK or integration code
    source: https://github.com/openchargemap/ocm-system/blob/master/Import/OCM.Import.Common/Providers/OCPI/ImportProvider_EV24.cs
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
    name: FLO (AddEnergie)
    provider: flo-ev
    says: ships the FLO (AddEnergie) SDK or integration code
    source: https://github.com/openchargemap/ocm-system/blob/master/Import/OCM.Import.Common/Providers/ImportProvider_AddEnergie.cs
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
    name: ICAEN (Catalonia)
    provider: icaen
    says: ships the ICAEN (Catalonia) SDK or integration code
    source: https://github.com/openchargemap/ocm-system/blob/master/Import/OCM.Import.Common/Providers/ImportProvider_ICAEN.cs
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
    name: NOBIL (Enova)
    provider: nobil
    says: ships the NOBIL (Enova) SDK or integration code
    source: https://github.com/openchargemap/ocm-system/blob/master/Import/OCM.Import.Common/Providers/ImportProvider_NobilDotNo.cs
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
    name: Oplaadpalen.nl
    provider: oplaadpalen
    says: ships the Oplaadpalen.nl SDK or integration code
    source: https://github.com/openchargemap/ocm-system/blob/master/Import/OCM.Import.Common/Providers/ImportProvider_OplaadpalenNL.cs
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
    name: PlugShare
    provider: plugshare
    says: ships the PlugShare SDK or integration code
    source: https://github.com/openchargemap/ocm-system/blob/master/Import/OCM.Import.Common/Providers/ImportProvider_PS.cs
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
    name: RWE Mobility
    provider: rwe
    says: ships the RWE Mobility SDK or integration code
    source: https://github.com/openchargemap/ocm-system/blob/master/Import/OCM.Import.Common/Providers/ImportProvider_RWEMobility.cs
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
    name: UK National Chargepoint Registry
    provider: national-chargepoint-registry
    says: ships the UK National Chargepoint Registry SDK or integration code
    source: https://github.com/openchargemap/ocm-system/blob/master/Import/OCM.Import.Common/Providers/ImportProvider_UKChargePointRegistry.cs
    tier: observed
  kind: open-source-saas
  name: Open Charge Map
  page: /applications/connected-car-ev-charging/open-charge-map/
  slug: open-charge-map
  url: https://github.com/openchargemap/ocm-system
- anchor: chargepoint
  counts:
    declared: 2
    observed: 4
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.coulombtech/latest/
  - route: integrations page
    url: https://www.chargepoint.com/blog/chargepoint-extends-open-network-new-partnerships/
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-902
      key: AE-902
      name: Mobile Attribution & Deep Linking
      url: /capabilities/mobile-attribution-deep-linking/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Branch
    provider: branch-io
    says: ships the Branch SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.coulombtech/latest/
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
    name: Firebase (Crashlytics)
    provider: firebase
    says: ships the Firebase (Crashlytics) SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.coulombtech/latest/
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
    name: Google Firebase Analytics
    provider: firebase
    says: ships the Google Firebase Analytics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.coulombtech/latest/
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
    name: Mixpanel
    provider: mixpanel
    says: ships the Mixpanel SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.coulombtech/latest/
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
    name: EVBox
    provider: evbox
    says: lists EVBox as an integration
    source: https://www.chargepoint.com/blog/chargepoint-extends-open-network-new-partnerships/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-200.20.20
      key: AE-200.20.20
      name: EV Charging
      url: /capabilities/connected-vehicles/
      via_parent: Connected Vehicles
    credit: null
    layer: domain
    name: FLO
    provider: flo-ev
    says: lists FLO as an integration
    source: https://www.chargepoint.com/blog/chargepoint-extends-open-network-new-partnerships/
    tier: declared
  kind: commercial
  name: ChargePoint
  page: /applications/connected-car-ev-charging/chargepoint/
  slug: chargepoint
  url: https://www.chargepoint.com/
- anchor: electrify-america
  counts:
    declared: 9
    observed: 0
  evidence:
  - route: integrations page
    url: https://www.electrifyamerica.com/plug-and-charge/
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
    name: Audi
    provider: audi-connect
    says: lists Audi as an integration
    source: https://www.electrifyamerica.com/plug-and-charge/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-200.20.10
      key: AE-200.20.10
      name: Vehicle Data Access
      url: /capabilities/connected-vehicles/
      via_parent: Connected Vehicles
    credit: null
    layer: domain
    name: BMW
    provider: bmw
    says: lists BMW as an integration
    source: https://www.electrifyamerica.com/plug-and-charge/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-200.20.10
      key: AE-200.20.10
      name: Vehicle Data Access
      url: /capabilities/connected-vehicles/
      via_parent: Connected Vehicles
    credit: null
    layer: domain
    name: Ford
    provider: ford
    says: lists Ford as an integration
    source: https://www.electrifyamerica.com/plug-and-charge/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-200.20.10
      key: AE-200.20.10
      name: Vehicle Data Access
      url: /capabilities/connected-vehicles/
      via_parent: Connected Vehicles
    credit: null
    layer: domain
    name: Lucid Motors
    provider: lucid-motors
    says: lists Lucid Motors as an integration
    source: https://www.electrifyamerica.com/plug-and-charge/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-200.20.10
      key: AE-200.20.10
      name: Vehicle Data Access
      url: /capabilities/connected-vehicles/
      via_parent: Connected Vehicles
    credit: null
    layer: domain
    name: Mercedes-Benz
    provider: mercedes-benz
    says: lists Mercedes-Benz as an integration
    source: https://www.electrifyamerica.com/plug-and-charge/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-200.20.10
      key: AE-200.20.10
      name: Vehicle Data Access
      url: /capabilities/connected-vehicles/
      via_parent: Connected Vehicles
    credit: null
    layer: domain
    name: Nissan
    provider: nissan
    says: lists Nissan as an integration
    source: https://www.electrifyamerica.com/plug-and-charge/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-200.20.10
      key: AE-200.20.10
      name: Vehicle Data Access
      url: /capabilities/connected-vehicles/
      via_parent: Connected Vehicles
    credit: null
    layer: domain
    name: Porsche
    provider: porsche
    says: lists Porsche as an integration
    source: https://www.electrifyamerica.com/plug-and-charge/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-200.20.10
      key: AE-200.20.10
      name: Vehicle Data Access
      url: /capabilities/connected-vehicles/
      via_parent: Connected Vehicles
    credit: null
    layer: domain
    name: Rivian
    provider: rivian-automotive
    says: lists Rivian as an integration
    source: https://www.electrifyamerica.com/plug-and-charge/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-200.20.10
      key: AE-200.20.10
      name: Vehicle Data Access
      url: /capabilities/connected-vehicles/
      via_parent: Connected Vehicles
    credit: null
    layer: domain
    name: Volkswagen
    provider: volkswagen
    says: lists Volkswagen as an integration
    source: https://www.electrifyamerica.com/plug-and-charge/
    tier: declared
  kind: commercial
  name: Electrify America
  page: /applications/connected-car-ev-charging/electrify-america/
  slug: electrify-america
  url: https://www.electrifyamerica.com/
author: API Evangelist
candidates: []
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
html: public
id: connected-car-ev-charging
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Navigation
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Utilities
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Auto & Vehicles
  store: google-play
  url: https://play.google.com/store/apps/category/AUTO_AND_VEHICLES
name: Connected Car & EV Charging
needs:
- capability:
    attribution: API Evangelist extension
    id: AE-200.20.10
    key: AE-200.20.10
    name: Vehicle Data Access
    url: /capabilities/connected-vehicles/
    via_parent: Connected Vehicles
  fit: exact
  layer: domain
  why: reading SoC, odometer, location and charge state from the car maker cloud or a telematics aggregator
- capability:
    attribution: API Evangelist extension
    id: AE-200.20.20
    key: AE-200.20.20
    name: EV Charging
    url: /capabilities/connected-vehicles/
    via_parent: Connected Vehicles
  fit: exact
  layer: domain
  why: charge-point registries, networks, roaming and charger clouds
- capability:
    attribution: Turbo EA
    id: BC-3480.30
    key: charging-energy-and-tariff-management
    name: Charging Energy and Tariff Management
    url: /capabilities/charging-energy-and-tariff-management/
    via_parent: null
  fit: exact
  layer: domain
  why: dynamic and time-of-use electricity prices that schedule home charging
- capability:
    attribution: Turbo EA
    id: BC-3840.60
    key: der-forecasting
    name: DER Forecasting
    url: /capabilities/der-forecasting/
    via_parent: null
  fit: exact
  layer: domain
  why: PV production forecasts for solar surplus charging
- capability:
    attribution: API Evangelist extension
    id: AE-230.10
    key: AE-230.10
    name: Weather & Environment
    url: /capabilities/weather-environment/
    via_parent: null
  fit: exact
  layer: common
  why: temperature forecasts; also stands in for grid carbon intensity (gap)
- capability:
    attribution: API Evangelist extension
    id: AE-200.10
    key: AE-200.10
    name: Smart Home
    url: /capabilities/smart-home/
    via_parent: null
  fit: exact
  layer: domain
  why: home-automation hubs as vehicle and tariff bridges
- capability:
    attribution: API Evangelist extension
    id: AE-200.30
    key: AE-200.30
    name: Home Energy
    url: /capabilities/home-energy/
    via_parent: null
  fit: exact
  layer: domain
  why: home energy meters
- capability:
    attribution: API Evangelist extension
    id: AE-120.10.20
    key: AE-120.10.20
    name: Reverse Geocoding
    url: /capabilities/geocoding/
    via_parent: Geocoding
  fit: exact
  layer: common
  why: address of each drive and charge
- capability:
    attribution: API Evangelist extension
    id: AE-120.30
    key: AE-120.30
    name: Routing & Navigation
    url: /capabilities/routing-navigation/
    via_parent: null
  fit: exact
  layer: domain
  why: EV route planning with live telemetry
- capability:
    attribution: API Evangelist extension
    id: AE-120.70
    key: AE-120.70
    name: Elevation & Terrain Data
    url: /capabilities/elevation-terrain-data/
    via_parent: null
  fit: exact
  layer: common
  why: elevation lookups (gap)
- capability:
    attribution: API Evangelist extension
    id: AE-150.30
    key: AE-150.30
    name: Push Notifications
    url: /capabilities/push-notifications/
    via_parent: null
  fit: exact
  layer: common
  why: charge-complete and error alerts
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.20
    key: AE-150.20.20
    name: WhatsApp & OTT Messaging
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  fit: exact
  layer: common
  why: Telegram bot alerts
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: nearest
  layer: common
  why: time-series dashboards (Grafana, InfluxDB)
- capability:
    attribution: API Evangelist extension
    id: AE-902
    key: AE-902
    name: Mobile Attribution & Deep Linking
    url: /capabilities/mobile-attribution-deep-linking/
    via_parent: null
  fit: exact
  layer: common
  why: mobile attribution and deep linking SDKs in the shipped Android app
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: exact
  layer: common
  why: usage and audience analytics SDKs in the shipped Android app
stack:
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-200.20.10
      key: AE-200.20.10
      name: Vehicle Data Access
      url: /capabilities/connected-vehicles/
      via_parent: Connected Vehicles
    providers:
    - agent_band: agent-aware
      agent_readiness: 22.3
      apps:
      - TeslaLogger
      - TeslaMate
      - evcc
      - openWB
      band: thin
      in_catalog: true
      kin_score: 34.8
      mcp: &id007
        status: none
      name: Tesla
      slug: tesla
      sources:
      - https://github.com/bassmaster187/TeslaLogger/blob/master/TeslaLogger/WebHelper.cs
      - https://github.com/evcc-io/evcc/tree/master/templates/definition/vehicle
      - https://github.com/openWB/core/tree/master/packages/modules/vehicles
      status: profiled
      tags: &id008
      - Automobiles
      - Cars
      - Electric Vehicles
      - Vehicles
      tier: observed
      url: /providers/tesla/
    - agent_band: agent-aware
      agent_readiness: 24.7
      apps:
      - Electrify America
      - evcc
      - openWB
      band: developing
      in_catalog: true
      kin_score: 45.5
      mcp:
        status: none
      name: Volkswagen Group
      slug: volkswagen
      sources:
      - https://github.com/evcc-io/evcc/tree/master/templates/definition/vehicle
      - https://github.com/openWB/core/tree/master/packages/modules/vehicles
      - https://www.electrifyamerica.com/plug-and-charge/
      status: profiled
      tags:
      - Automobiles
      - Automotive
      - Cars
      - Vehicles
      tier: observed
      url: /providers/volkswagen/
    - agent_band: agent-aware
      agent_readiness: 20.8
      apps:
      - Electrify America
      - evcc
      - openWB
      band: thin
      in_catalog: true
      kin_score: 33.1
      mcp:
        status: none
      name: Porsche
      slug: porsche
      sources:
      - https://github.com/evcc-io/evcc/tree/master/templates/definition/vehicle
      - https://github.com/openWB/core/tree/master/packages/modules/vehicles
      - https://www.electrifyamerica.com/plug-and-charge/
      status: profiled
      tags:
      - Automobiles
      - Automotive
      - Cars
      - Vehicles
      tier: observed
      url: /providers/porsche/
    - agent_band: human-only
      agent_readiness: 0.6
      apps:
      - Electrify America
      - evcc
      - openWB
      band: emerging
      in_catalog: true
      kin_score: 20.5
      mcp:
        status: unknown
      name: BMW
      slug: bmw
      sources:
      - https://github.com/evcc-io/evcc/tree/master/templates/definition/vehicle
      - https://github.com/openWB/core/tree/master/packages/modules/vehicles
      - https://www.electrifyamerica.com/plug-and-charge/
      status: profiled
      tags:
      - Automobiles
      - Automotive
      - Cars
      - Vehicles
      tier: observed
      url: /providers/bmw/
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - Electrify America
      - evcc
      - openWB
      band: minimal
      in_catalog: true
      kin_score: 7.9
      mcp:
        status: unknown
      name: Nissan
      slug: nissan
      sources:
      - https://github.com/evcc-io/evcc/tree/master/templates/definition/vehicle
      - https://github.com/openWB/core/tree/master/packages/modules/vehicles
      - https://www.electrifyamerica.com/plug-and-charge/
      status: profiled
      tags:
      - Automobiles
      - Cars
      - Vehicles
      tier: observed
      url: /providers/nissan/
    - agent_band: agent-aware
      agent_readiness: 16.9
      apps:
      - evcc
      - openWB
      band: thin
      in_catalog: true
      kin_score: 32.9
      mcp:
        status: none
      name: Kia
      slug: kia
      sources:
      - https://github.com/evcc-io/evcc/tree/master/templates/definition/vehicle
      - https://github.com/openWB/core/tree/master/packages/modules/vehicles
      status: profiled
      tags:
      - Automotive
      - Connected Vehicles
      - OAuth
      - Vehicle Data
      tier: observed
      url: /providers/kia/
    - agent_band: human-only
      agent_readiness: 0.6
      apps:
      - Electrify America
      - evcc
      band: thin
      in_catalog: true
      kin_score: 29.3
      mcp:
        status: none
      name: Mercedes-Benz
      slug: mercedes-benz
      sources:
      - https://github.com/evcc-io/evcc/tree/master/templates/definition/vehicle
      - https://www.electrifyamerica.com/plug-and-charge/
      status: profiled
      tags:
      - Automobiles
      - Cars
      - Vehicles
      tier: observed
      url: /providers/mercedes-benz/
    - agent_band: agent-aware
      agent_readiness: 26.9
      apps:
      - Electrify America
      - evcc
      band: thin
      in_catalog: true
      kin_score: 28.7
      mcp:
        status: none
      name: Ford
      slug: ford
      sources:
      - https://github.com/evcc-io/evcc/tree/master/templates/definition/vehicle
      - https://www.electrifyamerica.com/plug-and-charge/
      status: profiled
      tags:
      - Automobiles
      - Cars
      - Connected Vehicles
      - Vehicles
      tier: observed
      url: /providers/ford/
    - agent_band: agent-aware
      agent_readiness: 18.6
      apps:
      - evcc
      - openWB
      band: emerging
      in_catalog: true
      kin_score: 25.6
      mcp:
        status: none
      name: TRONITY
      slug: tronity
      sources:
      - https://github.com/evcc-io/evcc/tree/master/templates/definition/vehicle
      - https://github.com/openWB/core/tree/master/packages/modules/vehicles
      status: profiled
      tags:
      - Connected Vehicles
      - Electric Vehicles
      - Fleet Management
      - Telematics
      tier: observed
      url: /providers/tronity/
    - agent_band: agent-aware
      agent_readiness: 19.9
      apps:
      - evcc
      - openWB
      band: emerging
      in_catalog: true
      kin_score: 22.8
      mcp:
        status: none
      name: Stellantis
      slug: stellantis
      sources:
      - https://github.com/evcc-io/evcc/tree/master/templates/definition/vehicle
      - https://github.com/openWB/core/tree/master/packages/modules/vehicles
      status: profiled
      tags:
      - Automotive
      - Company
      - Manufacturing
      - Mobility
      tier: observed
      url: /providers/stellantis/
    - agent_band: agent-aware
      agent_readiness: 17.6
      apps:
      - evcc
      - openWB
      band: emerging
      in_catalog: true
      kin_score: 21.9
      mcp:
        status: none
      name: Open Vehicle Monitoring System (self-hosted)
      slug: ovms
      sources:
      - https://github.com/evcc-io/evcc/tree/master/templates/definition/vehicle
      - https://github.com/openWB/core/tree/master/packages/modules/vehicles
      status: profiled
      tags:
      - Company
      - Electric Vehicles
      - Open Source
      - Telematics
      tier: observed
      url: /providers/ovms/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - evcc
      - openWB
      band: emerging
      in_catalog: true
      kin_score: 21.1
      mcp:
        status: none
      name: Renault Group
      slug: renault-group
      sources:
      - https://github.com/evcc-io/evcc/tree/master/templates/definition/vehicle
      - https://github.com/openWB/core/tree/master/packages/modules/vehicles
      status: profiled
      tags:
      - Android Automotive
      - Automotive
      - Company
      - In-Vehicle Apps
      tier: observed
      url: /providers/renault-group/
    - agent_band: agent-aware
      agent_readiness: 18.3
      apps:
      - TeslaLogger
      - evcc
      band: emerging
      in_catalog: true
      kin_score: 15.0
      mcp:
        source: https://teslafi.com
        status: documented
      name: TeslaFi
      slug: teslafi
      sources:
      - https://github.com/bassmaster187/TeslaLogger/tree/master/TeslaFi-Import
      - https://github.com/evcc-io/evcc/tree/master/templates/definition/vehicle
      status: profiled
      tags:
      - Company
      - Data-Logger
      - Tesla
      - Vehicle-Analytics
      tier: observed
      url: /providers/teslafi/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - evcc
      - openWB
      band: minimal
      in_catalog: true
      kin_score: 6.8
      mcp:
        status: none
      name: Polestar
      slug: polestar-cars
      sources:
      - https://github.com/evcc-io/evcc/tree/master/templates/definition/vehicle
      - https://github.com/openWB/core/tree/master/packages/modules/vehicles
      status: profiled
      tags:
      - Automotive
      - Connected Vehicles
      - Electric Vehicles
      - Premium Vehicles
      tier: observed
      url: /providers/polestar-cars/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Electrify America
      - evcc
      band: minimal
      in_catalog: true
      kin_score: 6.5
      mcp:
        status: unknown
      name: Audi Connect
      slug: audi-connect
      sources:
      - https://github.com/evcc-io/evcc/tree/master/templates/definition/vehicle
      - https://www.electrifyamerica.com/plug-and-charge/
      status: profiled
      tags:
      - Automotive
      - Connected Vehicles
      - Mobility
      - Telematics
      tier: observed
      url: /providers/audi-connect/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - evcc
      - openWB
      band: minimal
      in_catalog: true
      kin_score: 4.9
      mcp:
        status: unknown
      name: smart Europe
      slug: smart-com
      sources:
      - https://github.com/evcc-io/evcc/tree/master/templates/definition/vehicle
      - https://github.com/openWB/core/tree/master/packages/modules/vehicles
      status: profiled
      tags:
      - Company
      tier: observed
      url: /providers/smart-com/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - TeslaLogger
      - evcc
      band: minimal
      in_catalog: true
      kin_score: 4.1
      mcp:
        status: none
      name: TeslaMate (self-hosted)
      slug: teslamate
      sources:
      - https://github.com/bassmaster187/TeslaLogger/tree/master/Teslamate-Import
      - https://github.com/evcc-io/evcc/tree/master/templates/definition/vehicle
      status: profiled
      tags:
      - Company
      - Data-Logger
      - Open Source
      - Tesla
      tier: observed
      url: /providers/teslamate/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - evcc
      - openWB
      band: minimal
      in_catalog: true
      kin_score: 2.2
      mcp:
        status: unknown
      name: MG (SAIC Motor)
      slug: saic-motor
      sources:
      - https://github.com/evcc-io/evcc/tree/master/templates/definition/vehicle
      - https://github.com/openWB/core/tree/master/packages/modules/vehicles
      status: profiled
      tags:
      - Automotive
      - China
      - Company
      - Manufacturing
      tier: observed
      url: /providers/saic-motor/
    - agent_band: null
      agent_readiness: null
      apps:
      - evcc
      - openWB
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: EVNotify
      slug: evnotify
      sources:
      - https://github.com/evcc-io/evcc/tree/master/templates/definition/vehicle
      - https://github.com/openWB/core/tree/master/packages/modules/vehicles
      status: queued for profiling
      tags: []
      tier: observed
      url: null
    - agent_band: agent-ready
      agent_readiness: 28.7
      apps:
      - evcc
      band: developing
      in_catalog: true
      kin_score: 49.5
      mcp:
        status: none
      name: Hyundai
      slug: hyundai
      sources:
      - https://github.com/evcc-io/evcc/tree/master/templates/definition/vehicle
      status: profiled
      tags:
      - Automobiles
      - Cars
      - Connected Vehicles
      - Mobility
      tier: observed
      url: /providers/hyundai/
    - agent_band: agent-aware
      agent_readiness: 25.6
      apps:
      - evcc
      band: developing
      in_catalog: true
      kin_score: 49.5
      mcp: &id001
        status: none
      name: Tibber
      slug: tibber
      sources:
      - https://github.com/evcc-io/evcc/tree/master/templates/definition/vehicle
      status: profiled
      tags: &id002
      - ElectricityPricing
      - Energy
      - Smart Home
      - Smart Meter
      tier: observed
      url: /providers/tibber/
    - agent_band: agent-aware
      agent_readiness: 25.6
      apps:
      - evcc
      band: developing
      in_catalog: true
      kin_score: 47.3
      mcp:
        status: none
      name: Tessie
      slug: tessie
      sources:
      - https://github.com/evcc-io/evcc/tree/master/templates/definition/vehicle
      status: profiled
      tags:
      - Automotive
      - Company
      - Fleet Management
      - Tesla
      tier: observed
      url: /providers/tessie/
    - agent_band: agent-ready
      agent_readiness: 32.6
      apps:
      - openWB
      band: developing
      in_catalog: true
      kin_score: 45.0
      mcp: &id005
        source: https://docs.evcc.io/en/integrations/mcp.md
        status: verified
      name: evcc (self-hosted)
      slug: evcc
      sources:
      - https://github.com/openWB/core/tree/master/packages/modules/vehicles
      status: profiled
      tags: &id006
      - Company
      - Electric Vehicles
      - Open Source
      - Smart Charging
      tier: observed
      url: /providers/evcc/
    - agent_band: agent-aware
      agent_readiness: 23.5
      apps:
      - evcc
      band: developing
      in_catalog: true
      kin_score: 44.1
      mcp: &id003
        status: none
      name: Octopus Energy
      slug: octopus-energy
      sources:
      - https://github.com/evcc-io/evcc/tree/master/templates/definition/vehicle
      status: profiled
      tags: &id004
      - Electricity
      - Energy
      - Gas
      - Renewable Energy
      tier: observed
      url: /providers/octopus-energy/
    - agent_band: agent-aware
      agent_readiness: 25.6
      apps:
      - evcc
      band: thin
      in_catalog: true
      kin_score: 31.0
      mcp:
        status: none
      name: Toyota
      slug: toyota
      sources:
      - https://github.com/evcc-io/evcc/tree/master/templates/definition/vehicle
      status: profiled
      tags:
      - Automobiles
      - Cars
      - Connected Vehicles
      - Vehicles
      tier: observed
      url: /providers/toyota/
    - agent_band: agent-aware
      agent_readiness: 18.8
      apps:
      - evcc
      band: thin
      in_catalog: true
      kin_score: 27.7
      mcp:
        status: none
      name: Volvo Cars
      slug: volvo-cars
      sources:
      - https://github.com/evcc-io/evcc/tree/master/templates/definition/vehicle
      status: profiled
      tags:
      - Automotive
      - Connected Vehicles
      - Electric Vehicles
      - Telematics
      tier: observed
      url: /providers/volvo-cars/
    - agent_band: agent-aware
      agent_readiness: 23.2
      apps:
      - evcc
      band: emerging
      in_catalog: true
      kin_score: 22.4
      mcp:
        source: https://teslalogger.de/docs/extras/mcp-server
        status: verified
      name: TeslaLogger (self-hosted)
      slug: teslalogger
      sources:
      - https://github.com/evcc-io/evcc/tree/master/templates/definition/vehicle
      status: profiled
      tags:
      - Automotive
      - Company
      - Data Logging
      - Open Source
      tier: observed
      url: /providers/teslalogger/
    - agent_band: agent-aware
      agent_readiness: 14.8
      apps:
      - evcc
      band: emerging
      in_catalog: true
      kin_score: 14.6
      mcp:
        status: none
      name: LiveWire
      slug: livewire
      sources:
      - https://github.com/evcc-io/evcc/tree/master/templates/definition/vehicle
      status: profiled
      tags:
      - Company
      - Electric Motorcycles
      - Electric Vehicles
      - Transportation
      tier: observed
      url: /providers/livewire/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - evcc
      band: emerging
      in_catalog: true
      kin_score: 13.6
      mcp:
        status: unknown
      name: JLR (Jaguar Land Rover)
      slug: jlr
      sources:
      - https://github.com/evcc-io/evcc/tree/master/templates/definition/vehicle
      status: profiled
      tags:
      - Automotive
      - Company
      - Connected Vehicles
      - Vehicle Data
      tier: observed
      url: /providers/jlr/
    - agent_band: human-only
      agent_readiness: 4.4
      apps:
      - evcc
      band: emerging
      in_catalog: true
      kin_score: 11.7
      mcp:
        status: unknown
      name: NIU
      slug: niu
      sources:
      - https://github.com/evcc-io/evcc/tree/master/templates/definition/vehicle
      status: profiled
      tags:
      - E-Bikes
      - Electric Vehicles
      - Mobility
      - Scooters
      tier: observed
      url: /providers/niu/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - evcc
      band: emerging
      in_catalog: true
      kin_score: 11.4
      mcp:
        status: none
      name: Zero Motorcycles
      slug: zero-motorcycles
      sources:
      - https://github.com/evcc-io/evcc/tree/master/templates/definition/vehicle
      status: profiled
      tags:
      - Automotive
      - Company
      - Electric Vehicles
      - Motorcycles
      tier: observed
      url: /providers/zero-motorcycles/
    - agent_band: agent-aware
      agent_readiness: 18.3
      apps:
      - evcc
      band: emerging
      in_catalog: true
      kin_score: 11.2
      mcp:
        status: none
      name: Connected Cars
      slug: connectedcars-io
      sources:
      - https://github.com/evcc-io/evcc/tree/master/templates/definition/vehicle
      status: profiled
      tags:
      - Connected Car Platform
      - Dealers
      - OEM APIs
      - Real-time Vehicle Data
      tier: observed
      url: /providers/connectedcars-io/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - evcc
      band: minimal
      in_catalog: true
      kin_score: 10.8
      mcp:
        status: unknown
      name: Aiways
      slug: aiways
      sources:
      - https://github.com/evcc-io/evcc/tree/master/templates/definition/vehicle
      status: profiled
      tags:
      - Automotive
      - Company
      - Electric Vehicles
      - Mobility
      tier: observed
      url: /providers/aiways/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - TeslaLogger
      band: minimal
      in_catalog: true
      kin_score: 9.9
      mcp:
        status: unknown
      name: Scan My Tesla
      slug: scanmytesla
      sources:
      - https://github.com/bassmaster187/TeslaLogger/blob/master/TeslaLogger/ScanMyTesla.cs
      status: profiled
      tags:
      - Automotive
      - Company
      - Diagnostics
      - Telemetry
      tier: observed
      url: /providers/scanmytesla/
    - agent_band: human-only
      agent_readiness: 0.6
      apps:
      - evcc
      band: minimal
      in_catalog: true
      kin_score: 7.1
      mcp:
        status: none
      name: Subaru
      slug: subaru-of-america
      sources:
      - https://github.com/evcc-io/evcc/tree/master/templates/definition/vehicle
      status: profiled
      tags:
      - Automobiles
      - Automotive
      - Cars
      - Vehicles
      tier: observed
      url: /providers/subaru-of-america/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - openWB
      band: minimal
      in_catalog: true
      kin_score: 5.0
      mcp:
        status: none
      name: BYD
      slug: byd
      sources:
      - https://github.com/openWB/core/tree/master/packages/modules/vehicles
      status: profiled
      tags:
      - Automotive
      - Company
      - Electric Vehicles
      - Technology
      tier: observed
      url: /providers/byd/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - evcc
      band: minimal
      in_catalog: true
      kin_score: 4.1
      mcp:
        status: unknown
      name: Mazda
      slug: mazda
      sources:
      - https://github.com/evcc-io/evcc/tree/master/templates/definition/vehicle
      status: profiled
      tags:
      - Company
      tier: observed
      url: /providers/mazda/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Electrify America
      band: emerging
      in_catalog: true
      kin_score: 11.2
      mcp:
        status: unknown
      name: Lucid Motors
      slug: lucid-motors
      sources:
      - https://www.electrifyamerica.com/plug-and-charge/
      status: profiled
      tags:
      - Automotive
      - Connected Vehicles
      - Electric Vehicles
      - Luxury Vehicles
      tier: declared
      url: /providers/lucid-motors/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Electrify America
      band: emerging
      in_catalog: true
      kin_score: 11.2
      mcp:
        status: none
      name: Rivian
      slug: rivian-automotive
      sources:
      - https://www.electrifyamerica.com/plug-and-charge/
      status: profiled
      tags:
      - Automotive
      - Connected Vehicles
      - Electric Vehicles
      - Manufacturing
      tier: declared
      url: /providers/rivian-automotive/
  - capability:
      attribution: Turbo EA
      id: BC-3480.30
      key: charging-energy-and-tariff-management
      name: Charging Energy and Tariff Management
      url: /capabilities/charging-energy-and-tariff-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 25.6
      apps:
      - evcc
      - openWB
      band: developing
      in_catalog: true
      kin_score: 49.5
      mcp: *id001
      name: Tibber
      slug: tibber
      sources:
      - https://github.com/evcc-io/evcc/tree/master/templates/definition/tariff
      - https://github.com/openWB/core/tree/master/packages/modules/electricity_pricing/flexible_tariffs
      status: profiled
      tags: *id002
      tier: observed
      url: /providers/tibber/
    - agent_band: agent-ready
      agent_readiness: 30.8
      apps:
      - evcc
      - openWB
      band: developing
      in_catalog: true
      kin_score: 45.8
      mcp:
        status: none
      name: Ostrom
      slug: ostrom
      sources:
      - https://github.com/evcc-io/evcc/tree/master/templates/definition/tariff
      - https://github.com/openWB/core/tree/master/packages/modules/electricity_pricing/flexible_tariffs
      status: profiled
      tags:
      - Company
      - Electricity
      - Energy
      - Renewable Energy
      tier: observed
      url: /providers/ostrom/
    - agent_band: agent-aware
      agent_readiness: 23.5
      apps:
      - evcc
      - openWB
      band: developing
      in_catalog: true
      kin_score: 44.1
      mcp: *id003
      name: Octopus Energy
      slug: octopus-energy
      sources:
      - https://github.com/evcc-io/evcc/tree/master/templates/definition/tariff
      - https://github.com/openWB/core/tree/master/packages/modules/electricity_pricing/flexible_tariffs
      status: profiled
      tags: *id004
      tier: observed
      url: /providers/octopus-energy/
    - agent_band: agent-aware
      agent_readiness: 28.4
      apps:
      - evcc
      - openWB
      band: thin
      in_catalog: true
      kin_score: 26.8
      mcp:
        status: none
      name: aWATTar
      slug: awattar
      sources:
      - https://github.com/evcc-io/evcc/tree/master/templates/definition/tariff
      - https://github.com/openWB/core/tree/master/packages/modules/electricity_pricing/flexible_tariffs
      status: profiled
      tags:
      - EPEX Spot
      - Electricity
      - Energy
      - Spot Price
      tier: observed
      url: /providers/awattar/
    - agent_band: agent-aware
      agent_readiness: 24.7
      apps:
      - evcc
      - openWB
      band: emerging
      in_catalog: true
      kin_score: 22.7
      mcp:
        status: unknown
      name: Energy-Charts (Fraunhofer ISE)
      slug: energy-charts-api
      sources:
      - https://github.com/evcc-io/evcc/tree/master/templates/definition/tariff
      - https://github.com/openWB/core/tree/master/packages/modules/electricity_pricing/flexible_tariffs
      status: profiled
      tags:
      - Electricity
      - Energy
      - Grid
      - Renewables
      tier: observed
      url: /providers/energy-charts-api/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - evcc
      - openWB
      band: emerging
      in_catalog: true
      kin_score: 11.9
      mcp:
        status: none
      name: smartENERGY
      slug: smartenergy-at
      sources:
      - https://github.com/evcc-io/evcc/tree/master/templates/definition/tariff
      - https://github.com/openWB/core/tree/master/packages/modules/electricity_pricing/flexible_tariffs
      status: profiled
      tags:
      - Austria
      - Energy
      - Renewables
      - Smart Grid
      tier: observed
      url: /providers/smartenergy-at/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - evcc
      - openWB
      band: emerging
      in_catalog: true
      kin_score: 11.8
      mcp:
        status: unknown
      name: EKZ
      slug: ekz
      sources:
      - https://github.com/evcc-io/evcc/tree/master/templates/definition/tariff
      - https://github.com/openWB/core/tree/master/packages/modules/electricity_pricing/flexible_tariffs
      status: profiled
      tags:
      - Energy
      - Renewables
      - Switzerland
      - Utilities
      tier: observed
      url: /providers/ekz/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - evcc
      - openWB
      band: minimal
      in_catalog: true
      kin_score: 3.1
      mcp:
        status: unknown
      name: Groupe E
      slug: groupe-e
      sources:
      - https://github.com/evcc-io/evcc/tree/master/templates/definition/tariff
      - https://github.com/openWB/core/tree/master/packages/modules/electricity_pricing/flexible_tariffs
      status: profiled
      tags:
      - Company
      - Energy
      - Renewables
      - Switzerland
      tier: observed
      url: /providers/groupe-e/
    - agent_band: agent-ready
      agent_readiness: 46.4
      apps:
      - evcc
      band: strong
      in_catalog: true
      kin_score: 65.1
      mcp:
        status: none
      name: Amber Electric
      slug: amber-electric
      sources:
      - https://github.com/evcc-io/evcc/tree/master/templates/definition/tariff
      status: profiled
      tags:
      - Australia
      - Electricity
      - Energy
      - Utilities
      tier: observed
      url: /providers/amber-electric/
    - agent_band: agent-ready
      agent_readiness: 33.9
      apps:
      - evcc
      band: thin
      in_catalog: true
      kin_score: 37.8
      mcp:
        status: none
      name: Nord Pool
      slug: nordpool
      sources:
      - https://github.com/evcc-io/evcc/tree/master/templates/definition/tariff
      status: profiled
      tags:
      - Day-Ahead Prices
      - Electricity
      - Energy Markets
      - Power Exchange
      tier: observed
      url: /providers/nordpool/
    - agent_band: agent-ready
      agent_readiness: 34.0
      apps:
      - evcc
      band: thin
      in_catalog: true
      kin_score: 33.4
      mcp:
        status: none
      name: ENTSO-E
      slug: entso-e
      sources:
      - https://github.com/evcc-io/evcc/tree/master/templates/definition/tariff
      status: profiled
      tags:
      - Day-Ahead Prices
      - Electricity
      - Energy
      - Energy Markets
      tier: observed
      url: /providers/entso-e/
    - agent_band: agent-aware
      agent_readiness: 19.4
      apps:
      - evcc
      band: thin
      in_catalog: true
      kin_score: 27.4
      mcp:
        status: none
      name: Stekker
      slug: stekker
      sources:
      - https://github.com/evcc-io/evcc/tree/master/templates/definition/tariff
      status: profiled
      tags:
      - Electric Vehicles
      - Energy
      - Marketplace
      - Renewables
      tier: observed
      url: /providers/stekker/
    - agent_band: agent-aware
      agent_readiness: 22.2
      apps:
      - evcc
      band: emerging
      in_catalog: true
      kin_score: 21.9
      mcp:
        status: none
      name: Red Electrica (e-sios)
      slug: esios-red-electrica
      sources:
      - https://github.com/evcc-io/evcc/tree/master/templates/definition/tariff
      status: profiled
      tags:
      - Company
      - Data
      - Energy
      - Spain
      tier: observed
      url: /providers/esios-red-electrica/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - evcc
      band: emerging
      in_catalog: true
      kin_score: 14.2
      mcp:
        status: unknown
      name: Frank Energie
      slug: frank-energie
      sources:
      - https://github.com/evcc-io/evcc/tree/master/templates/definition/tariff
      status: profiled
      tags:
      - Company
      tier: observed
      url: /providers/frank-energie/
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - evcc
      band: emerging
      in_catalog: true
      kin_score: 12.7
      mcp:
        status: unknown
      name: Pstryk
      slug: pstryk
      sources:
      - https://github.com/evcc-io/evcc/tree/master/templates/definition/tariff
      status: profiled
      tags:
      - Company
      - Energy
      - Fintech
      - Utilities
      tier: observed
      url: /providers/pstryk/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - openWB
      band: emerging
      in_catalog: true
      kin_score: 12.3
      mcp:
        status: unknown
      name: Naturstrom
      slug: naturstrom
      sources:
      - https://github.com/openWB/core/tree/master/packages/modules/electricity_pricing/flexible_tariffs
      status: profiled
      tags:
      - Electricity
      - Energy
      - Germany
      - Renewables
      tier: observed
      url: /providers/naturstrom/
    - agent_band: human-only
      agent_readiness: 0.7
      apps:
      - openWB
      band: minimal
      in_catalog: true
      kin_score: 10.6
      mcp:
        status: unknown
      name: rabot.energy
      slug: rabotenergy
      sources:
      - https://github.com/openWB/core/tree/master/packages/modules/electricity_pricing/flexible_tariffs
      status: profiled
      tags:
      - Company
      - Consumer
      - Electricity
      - Energy
      tier: observed
      url: /providers/rabotenergy/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - evcc
      band: minimal
      in_catalog: true
      kin_score: 9.0
      mcp:
        status: unknown
      name: OMIE (Iberian power market)
      slug: omie-es
      sources:
      - https://github.com/evcc-io/evcc/tree/master/templates/definition/tariff
      status: profiled
      tags:
      - Company
      - Electricity
      - Energy
      - Markets
      tier: observed
      url: /providers/omie-es/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - evcc
      band: minimal
      in_catalog: true
      kin_score: 8.4
      mcp:
        status: none
      name: Elering
      slug: elering
      sources:
      - https://github.com/evcc-io/evcc/tree/master/templates/definition/tariff
      status: profiled
      tags:
      - Energy
      - Estonia
      - Grid
      - Transmission
      tier: observed
      url: /providers/elering/
    - agent_band: agent-aware
      agent_readiness: 11.6
      apps:
      - evcc
      band: minimal
      in_catalog: true
      kin_score: 7.7
      mcp:
        status: unknown
      name: Energinet
      slug: energinet
      sources:
      - https://github.com/evcc-io/evcc/tree/master/templates/definition/tariff
      status: profiled
      tags:
      - Company
      - Energy
      - Grid
      - Transmission
      tier: observed
      url: /providers/energinet/
    - agent_band: human-only
      agent_readiness: 2.8
      apps:
      - evcc
      band: minimal
      in_catalog: true
      kin_score: 7.0
      mcp:
        status: unknown
      name: EDF (Tempo tariff)
      slug: edf
      sources:
      - https://github.com/evcc-io/evcc/tree/master/templates/definition/tariff
      status: profiled
      tags:
      - Company
      - Energy
      - France
      - Utilities
      tier: observed
      url: /providers/edf/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - openWB
      band: minimal
      in_catalog: true
      kin_score: 5.7
      mcp:
        status: unknown
      name: WestfalenWIND
      slug: westfalenwind
      sources:
      - https://github.com/openWB/core/tree/master/packages/modules/electricity_pricing/flexible_tariffs
      status: profiled
      tags:
      - Company
      - Germany
      - Renewable Energy
      - Wind Power
      tier: observed
      url: /providers/westfalenwind/
    - agent_band: null
      agent_readiness: null
      apps:
      - openWB
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Voltego
      slug: voltego
      sources:
      - https://github.com/openWB/core/tree/master/packages/modules/electricity_pricing/flexible_tariffs
      status: queued for profiling
      tags: []
      tier: observed
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-200.20.20
      key: AE-200.20.20
      name: EV Charging
      url: /capabilities/connected-vehicles/
      via_parent: Connected Vehicles
    providers:
    - agent_band: agent-aware
      agent_readiness: 19.9
      apps:
      - ChargePoint
      - Open Charge Map
      band: thin
      in_catalog: true
      kin_score: 29.8
      mcp:
        status: unknown
      name: FLO (AddEnergie)
      slug: flo-ev
      sources:
      - https://github.com/openchargemap/ocm-system/blob/master/Import/OCM.Import.Common/Providers/ImportProvider_AddEnergie.cs
      - https://www.chargepoint.com/blog/chargepoint-extends-open-network-new-partnerships/
      status: profiled
      tags:
      - Canada
      - EV Charging
      - Electricity
      - Energy
      tier: observed
      url: /providers/flo-ev/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - TeslaLogger
      - evcc
      band: emerging
      in_catalog: true
      kin_score: 20.9
      mcp:
        status: unknown
      name: go-e
      slug: go-e
      sources:
      - https://github.com/bassmaster187/TeslaLogger/blob/master/wallbox.md
      - https://github.com/evcc-io/evcc/tree/master/charger
      status: profiled
      tags:
      - Company
      - EV Charging
      - Hardware
      - Sustainability
      tier: observed
      url: /providers/go-e/
    - agent_band: agent-ready
      agent_readiness: 29.2
      apps:
      - evcc
      band: developing
      in_catalog: true
      kin_score: 48.6
      mcp:
        status: none
      name: Easee
      slug: easee
      sources:
      - https://github.com/evcc-io/evcc/tree/master/charger
      status: profiled
      tags:
      - Company
      - EV Charging
      - IoT
      - Smart Home
      tier: observed
      url: /providers/easee/
    - agent_band: agent-ready
      agent_readiness: 35.2
      apps:
      - evcc
      band: developing
      in_catalog: true
      kin_score: 46.9
      mcp:
        status: unknown
      name: Zaptec
      slug: zaptec
      sources:
      - https://github.com/evcc-io/evcc/tree/master/charger
      status: profiled
      tags:
      - Company
      - EV Charging
      - Energy
      - Smart Charging
      tier: observed
      url: /providers/zaptec/
    - agent_band: agent-aware
      agent_readiness: 18.2
      apps:
      - Open Charge Map
      band: thin
      in_catalog: true
      kin_score: 37.7
      mcp:
        status: none
      name: Department of Energy (AFDC)
      slug: doe
      sources:
      - https://github.com/openchargemap/ocm-system/blob/master/Import/OCM.Import.Common/Providers/AFDC/ImportProvider_AFDC.cs
      status: profiled
      tags:
      - Electricity
      - Energy
      - Government
      - Renewable Energy
      tier: observed
      url: /providers/doe/
    - agent_band: human-only
      agent_readiness: 3.1
      apps:
      - Open Charge Map
      band: thin
      in_catalog: true
      kin_score: 27.1
      mcp:
        status: none
      name: ChargePoint
      slug: chargepoint
      sources:
      - https://github.com/openchargemap/ocm-system/blob/master/Import/OCM.Import.Common/Providers/ImportProvider_CoulombChargepoint.cs
      status: profiled
      tags:
      - EV Charging
      - Electric Vehicles
      - Energy Management
      - Fleet Management
      tier: observed
      url: /providers/chargepoint/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Open Charge Map
      band: emerging
      in_catalog: true
      kin_score: 22.7
      mcp:
        status: unknown
      name: EV24
      slug: ev24
      sources:
      - https://github.com/openchargemap/ocm-system/blob/master/Import/OCM.Import.Common/Providers/OCPI/ImportProvider_EV24.cs
      status: profiled
      tags:
      - EV Charging
      - Energy
      - Platform
      - Software-as-a-Service
      tier: observed
      url: /providers/ev24/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Open Charge Map
      band: emerging
      in_catalog: true
      kin_score: 16.4
      mcp:
        status: unknown
      name: Chargesini
      slug: chargesini
      sources:
      - https://github.com/openchargemap/ocm-system/blob/master/Import/OCM.Import.Common/Providers/OCPI/ImportProvider_Chargesini.cs
      status: profiled
      tags:
      - Company
      - EV Charging
      - Malaysia
      - Sustainability
      tier: observed
      url: /providers/chargesini/
    - agent_band: human-only
      agent_readiness: 4.9
      apps:
      - Open Charge Map
      band: emerging
      in_catalog: true
      kin_score: 13.7
      mcp:
        status: unknown
      name: NOBIL (Enova)
      slug: nobil
      sources:
      - https://github.com/openchargemap/ocm-system/blob/master/Import/OCM.Import.Common/Providers/ImportProvider_NobilDotNo.cs
      status: profiled
      tags:
      - Charging
      - Data
      - Electric Vehicles
      - Energy
      tier: observed
      url: /providers/nobil/
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - Open Charge Map
      band: emerging
      in_catalog: true
      kin_score: 12.8
      mcp:
        status: unknown
      name: ICAEN (Catalonia)
      slug: icaen
      sources:
      - https://github.com/openchargemap/ocm-system/blob/master/Import/OCM.Import.Common/Providers/ImportProvider_ICAEN.cs
      status: profiled
      tags:
      - Company
      - Energy
      - Public Institution
      - Research
      tier: observed
      url: /providers/icaen/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Open Charge Map
      band: minimal
      in_catalog: true
      kin_score: 7.1
      mcp:
        status: unknown
      name: ESB ecars
      slug: esb
      sources:
      - https://github.com/openchargemap/ocm-system/blob/master/Import/OCM.Import.Common/Providers/ImportProvider_ESB_eCars.cs
      status: profiled
      tags:
      - Energy
      - Ireland
      - Renewables
      - Utilities
      tier: observed
      url: /providers/esb/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Open Charge Map
      band: minimal
      in_catalog: true
      kin_score: 5.4
      mcp:
        status: unknown
      name: RWE Mobility
      slug: rwe
      sources:
      - https://github.com/openchargemap/ocm-system/blob/master/Import/OCM.Import.Common/Providers/ImportProvider_RWEMobility.cs
      status: profiled
      tags:
      - Energy
      - Mobility
      - Renewables
      - Sustainability
      tier: observed
      url: /providers/rwe/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Open Charge Map
      band: minimal
      in_catalog: true
      kin_score: 5.1
      mcp:
        status: none
      name: PlugShare
      slug: plugshare
      sources:
      - https://github.com/openchargemap/ocm-system/blob/master/Import/OCM.Import.Common/Providers/ImportProvider_PS.cs
      status: profiled
      tags:
      - Company
      tier: observed
      url: /providers/plugshare/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - TeslaLogger
      band: minimal
      in_catalog: true
      kin_score: 2.2
      mcp:
        status: unknown
      name: supercharge.bingo
      slug: supercharge-bingo
      sources:
      - https://github.com/bassmaster187/TeslaLogger/blob/master/TeslaLogger/WebHelper.cs
      status: profiled
      tags:
      - Community
      - Company
      - Electric Vehicles
      - Gaming
      tier: observed
      url: /providers/supercharge-bingo/
    - agent_band: null
      agent_readiness: null
      apps:
      - Open Charge Map
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: data.gouv.fr
      slug: data-gouv-fr
      sources:
      - https://github.com/openchargemap/ocm-system/blob/master/Import/OCM.Import.Common/Providers/ImportProvider_DataGouvFr.cs
      status: queued for profiling
      tags: []
      tier: observed
      url: null
    - agent_band: null
      agent_readiness: null
      apps:
      - Open Charge Map
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: UK National Chargepoint Registry
      slug: national-chargepoint-registry
      sources:
      - https://github.com/openchargemap/ocm-system/blob/master/Import/OCM.Import.Common/Providers/ImportProvider_UKChargePointRegistry.cs
      status: queued for profiling
      tags: []
      tier: observed
      url: null
    - agent_band: null
      agent_readiness: null
      apps:
      - Open Charge Map
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Oplaadpalen.nl
      slug: oplaadpalen
      sources:
      - https://github.com/openchargemap/ocm-system/blob/master/Import/OCM.Import.Common/Providers/ImportProvider_OplaadpalenNL.cs
      status: queued for profiling
      tags: []
      tier: observed
      url: null
    - agent_band: agent-ready
      agent_readiness: 32.6
      apps:
      - TeslaLogger
      band: developing
      in_catalog: true
      kin_score: 45.0
      mcp: *id005
      name: evcc (self-hosted)
      slug: evcc
      sources:
      - https://github.com/bassmaster187/TeslaLogger/blob/master/wallbox.md
      status: profiled
      tags: *id006
      tier: declared
      url: /providers/evcc/
    - agent_band: agent-aware
      agent_readiness: 22.3
      apps:
      - TeslaLogger
      band: thin
      in_catalog: true
      kin_score: 34.8
      mcp: *id007
      name: Tesla
      slug: tesla
      sources:
      - https://github.com/bassmaster187/TeslaLogger/blob/master/wallbox.md
      status: profiled
      tags: *id008
      tier: declared
      url: /providers/tesla/
    - agent_band: agent-aware
      agent_readiness: 7.4
      apps:
      - TeslaLogger
      band: emerging
      in_catalog: true
      kin_score: 25.7
      mcp:
        status: unknown
      name: KEBA
      slug: keba
      sources:
      - https://github.com/bassmaster187/TeslaLogger/blob/master/wallbox.md
      status: profiled
      tags:
      - Automation
      - Company
      - Energy
      - Industrial
      tier: declared
      url: /providers/keba/
    - agent_band: agent-aware
      agent_readiness: 18.3
      apps:
      - ChargePoint
      band: emerging
      in_catalog: true
      kin_score: 12.0
      mcp:
        status: none
      name: EVBox
      slug: evbox
      sources:
      - https://www.chargepoint.com/blog/chargepoint-extends-open-network-new-partnerships/
      status: profiled
      tags:
      - Company
      - EV Charging
      - Hardware
      - Software
      tier: declared
      url: /providers/evbox/
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - TeslaLogger
      band: minimal
      in_catalog: true
      kin_score: 6.8
      mcp:
        status: unknown
      name: openWB (self-hosted)
      slug: openwb
      sources:
      - https://github.com/bassmaster187/TeslaLogger/blob/master/wallbox.md
      status: profiled
      tags:
      - Company
      - EV Charging
      - Energy
      - Smart Home
      tier: declared
      url: /providers/openwb/
  - capability:
      attribution: API Evangelist extension
      id: AE-230.80
      key: AE-230.80
      name: Grid Carbon Intensity
      url: /capabilities/grid-carbon-intensity/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 24.0
      apps:
      - evcc
      band: developing
      in_catalog: true
      kin_score: 43.5
      mcp:
        status: none
      name: National Energy System Operator (NESO)
      slug: neso
      sources:
      - https://github.com/evcc-io/evcc/tree/master/templates/definition/tariff
      status: profiled
      tags:
      - Electricity
      - Energy
      - Energy Markets
      - United Kingdom
      tier: observed
      url: /providers/neso/
    - agent_band: agent-aware
      agent_readiness: 28.5
      apps:
      - evcc
      band: thin
      in_catalog: true
      kin_score: 29.8
      mcp:
        status: none
      name: Electricity Maps
      slug: electricitymaps
      sources:
      - https://github.com/evcc-io/evcc/tree/master/templates/definition/tariff
      status: profiled
      tags:
      - Carbon Intensity
      - Electricity
      - Energy
      - Grid
      tier: observed
      url: /providers/electricitymaps/
    - agent_band: human-only
      agent_readiness: 2.8
      apps:
      - evcc
      band: emerging
      in_catalog: true
      kin_score: 12.5
      mcp:
        status: none
      name: Fingrid
      slug: fingrid
      sources:
      - https://github.com/evcc-io/evcc/tree/master/templates/definition/tariff
      status: profiled
      tags:
      - Company
      - Electricity
      - Energy
      - Transmission
      tier: observed
      url: /providers/fingrid/
    - agent_band: null
      agent_readiness: null
      apps:
      - evcc
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: GrünStromIndex (Corrently)
      slug: gruenstromindex
      sources:
      - https://github.com/evcc-io/evcc/tree/master/templates/definition/tariff
      status: queued for profiling
      tags: []
      tier: observed
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-200.10
      key: AE-200.10
      name: Smart Home
      url: /capabilities/smart-home/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 5.6
      apps:
      - evcc
      - openWB
      band: thin
      in_catalog: true
      kin_score: 34.5
      mcp:
        source: https://www.home-assistant.io/integrations/mcp_server/
        status: verified
      name: Home Assistant (self-hosted)
      slug: home-assistant
      sources:
      - https://github.com/evcc-io/evcc/tree/master/templates/definition/vehicle
      - https://github.com/openWB/core/tree/master/packages/modules/vehicles
      status: profiled
      tags:
      - Community
      - Home Automation
      - IoT
      - Open Source
      tier: observed
      url: /providers/home-assistant/
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - evcc
      - openWB
      band: minimal
      in_catalog: true
      kin_score: 8.2
      mcp:
        source: https://github.com/ioBroker/ioBroker.mcp
        status: verified
      name: ioBroker (self-hosted)
      slug: iobroker
      sources:
      - https://github.com/evcc-io/evcc/tree/master/templates/definition/vehicle
      - https://github.com/openWB/core/tree/master/packages/modules/vehicles
      status: profiled
      tags:
      - Company
      - Home Automation
      - IoT
      - Open Source
      tier: observed
      url: /providers/iobroker/
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
      - evcc
      band: developing
      in_catalog: true
      kin_score: 53.7
      mcp:
        status: none
      name: Solcast
      slug: solcast
      sources:
      - https://github.com/evcc-io/evcc/tree/master/templates/definition/tariff
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
      - evcc
      band: thin
      in_catalog: true
      kin_score: 35.4
      mcp:
        status: unknown
      name: Forecast.Solar
      slug: forecast-solar
      sources:
      - https://github.com/evcc-io/evcc/tree/master/templates/definition/tariff
      status: profiled
      tags:
      - Company
      - Forecast
      - Renewable Energy
      - Solar
      tier: observed
      url: /providers/forecast-solar/
    - agent_band: agent-aware
      agent_readiness: 27.5
      apps:
      - evcc
      band: thin
      in_catalog: true
      kin_score: 33.9
      mcp:
        status: none
      name: Victron Energy (VRM)
      slug: victron-energy
      sources:
      - https://github.com/evcc-io/evcc/tree/master/templates/definition/tariff
      status: profiled
      tags:
      - Company
      - Energy
      - Off-Grid
      - Renewables
      tier: observed
      url: /providers/victron-energy/
  - capability:
      attribution: API Evangelist extension
      id: AE-200.30
      key: AE-200.30
      name: Home Energy
      url: /capabilities/home-energy/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 4.4
      apps:
      - TeslaLogger
      band: emerging
      in_catalog: true
      kin_score: 11.6
      mcp:
        source: https://shelly-api-docs.shelly.cloud/mcp
        status: verified
      name: Shelly
      slug: shelly
      sources:
      - https://github.com/bassmaster187/TeslaLogger/blob/master/wallbox.md
      status: profiled
      tags:
      - Company
      - Devices
      - IoT
      - Smart Home
      tier: declared
      url: /providers/shelly/
  - capability:
      attribution: API Evangelist extension
      id: AE-120.30
      key: AE-120.30
      name: Routing & Navigation
      url: /capabilities/routing-navigation/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - TeslaLogger
      band: emerging
      in_catalog: true
      kin_score: 12.5
      mcp:
        source: https://abetterrouteplanner.com/mcp
        status: verified
      name: A Better Route Planner (Iternio)
      slug: iternio
      sources:
      - https://github.com/bassmaster187/TeslaLogger/blob/master/TeslaLogger/WebHelper.cs
      status: profiled
      tags:
      - Company
      - Electric Vehicles
      - Routing
      - Transportation
      tier: observed
      url: /providers/iternio/
  layer: domain
- capabilities:
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 27.6
      apps:
      - TeslaMate
      band: strong
      in_catalog: true
      kin_score: 66.0
      mcp:
        source: https://github.com/grafana/mcp-grafana
        status: verified
      name: Grafana
      slug: grafana-com
      sources:
      - https://github.com/teslamate-org/teslamate/tree/main/grafana
      status: profiled
      tags:
      - Dashboards
      - Logs
      - Monitoring
      - Observability
      tier: observed
      url: /providers/grafana-com/
    - agent_band: agent-ready
      agent_readiness: 34.4
      apps:
      - evcc
      band: strong
      in_catalog: true
      kin_score: 63.3
      mcp:
        source: https://github.com/influxdata/influxdb3_mcp_server
        status: verified
      name: InfluxDB
      slug: influxdata
      sources:
      - https://github.com/evcc-io/evcc/tree/master/server
      status: profiled
      tags:
      - Database
      - Monitoring
      - Observability
      - Time Series Database
      tier: observed
      url: /providers/influxdata/
    - agent_band: agent-ready
      agent_readiness: 39.9
      apps:
      - ChargePoint
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: &id009
        source: https://firebase.google.com/docs/ai-assistance/mcp-server
        status: verified
      name: Firebase (Crashlytics)
      slug: google-firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.coulombtech/latest/
      status: profiled
      tags: &id010
      - Analytics
      - Authentication
      - Backend-as-a-Service
      - Cloud Messaging
      tier: observed
      url: /providers/google-firebase/
  - capability:
      attribution: API Evangelist extension
      id: AE-120.10.20
      key: AE-120.10.20
      name: Reverse Geocoding
      url: /capabilities/geocoding/
      via_parent: Geocoding
    providers:
    - agent_band: agent-aware
      agent_readiness: 25.7
      apps:
      - TeslaLogger
      - TeslaMate
      band: developing
      in_catalog: true
      kin_score: 43.7
      mcp:
        status: none
      name: Nominatim
      slug: nominatim
      sources:
      - https://github.com/bassmaster187/TeslaLogger/blob/master/TeslaLogger/WebHelper.cs
      - https://github.com/teslamate-org/teslamate/blob/main/elixir/lib/teslamate/locations/geocoder.ex
      status: profiled
      tags:
      - Geocoding
      - Location Services
      - Maps
      - OpenStreetMap
      tier: observed
      url: /providers/nominatim/
    - agent_band: agent-aware
      agent_readiness: 14.7
      apps:
      - TeslaLogger
      band: thin
      in_catalog: true
      kin_score: 35.2
      mcp:
        status: none
      name: MapQuest
      slug: mapquest
      sources:
      - https://github.com/bassmaster187/TeslaLogger/blob/master/TeslaLogger/MapQuestMapProvider.cs
      status: profiled
      tags:
      - Geocoding
      - Mapping
      - Maps
      - Navigation
      tier: observed
      url: /providers/mapquest/
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
      - ChargePoint
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: *id009
      name: Google Firebase Analytics
      slug: google-firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.coulombtech/latest/
      status: profiled
      tags: *id010
      tier: observed
      url: /providers/google-firebase/
    - agent_band: agent-ready
      agent_readiness: 47.7
      apps:
      - ChargePoint
      band: strong
      in_catalog: true
      kin_score: 60.8
      mcp:
        source: https://docs.mixpanel.com/docs/features/mcp
        status: verified
      name: Mixpanel
      slug: mixpanel
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.coulombtech/latest/
      status: profiled
      tags:
      - Analytics
      - Data Analysis
      - Event Tracking
      - Product Analytics
      tier: observed
      url: /providers/mixpanel/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.30
      key: AE-150.30
      name: Push Notifications
      url: /capabilities/push-notifications/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 21.6
      apps:
      - evcc
      band: thin
      in_catalog: true
      kin_score: 28.1
      mcp:
        status: none
      name: Pushover
      slug: pushover
      sources:
      - https://raw.githubusercontent.com/evcc-io/evcc/master/go.mod
      status: profiled
      tags:
      - Alerts
      - Messaging
      - Notification
      - Push Notifications
      tier: observed
      url: /providers/pushover/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - evcc
      band: emerging
      in_catalog: true
      kin_score: 15.5
      mcp:
        status: none
      name: ntfy
      slug: ntfy
      sources:
      - https://github.com/evcc-io/evcc/tree/master/templates/definition/messenger
      status: profiled
      tags:
      - Notification
      - Open Source
      - Pub/Sub
      - Self-Hosted
      tier: observed
      url: /providers/ntfy/
  - capability:
      attribution: API Evangelist extension
      id: AE-230.10
      key: AE-230.10
      name: Weather & Environment
      url: /capabilities/weather-environment/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 17.4
      apps:
      - evcc
      band: thin
      in_catalog: true
      kin_score: 28.3
      mcp:
        status: none
      name: Open-Meteo
      slug: open-meteo
      sources:
      - https://github.com/evcc-io/evcc/tree/master/templates/definition/tariff
      status: profiled
      tags:
      - Air Quality
      - Forecast
      - Historical Weather
      - Weather
      tier: observed
      url: /providers/open-meteo/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - evcc
      band: minimal
      in_catalog: true
      kin_score: 3.4
      mcp:
        status: none
      name: Deutscher Wetterdienst
      slug: deutscher-wetterdienst
      sources:
      - https://github.com/evcc-io/evcc/tree/master/templates/definition/tariff
      status: profiled
      tags:
      - Geospatial
      - OGC
      - WFS
      - WMS
      tier: observed
      url: /providers/deutscher-wetterdienst/
  - capability:
      attribution: API Evangelist extension
      id: AE-120.70
      key: AE-120.70
      name: Elevation & Terrain Data
      url: /capabilities/elevation-terrain-data/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 5.6
      apps:
      - TeslaLogger
      band: thin
      in_catalog: true
      kin_score: 30.3
      mcp:
        status: unknown
      name: Open-Elevation
      slug: open-elevation
      sources:
      - https://github.com/bassmaster187/TeslaLogger/blob/master/TeslaLogger/WebHelper.cs
      status: profiled
      tags:
      - Company
      - Elevation
      - Geospatial
      - Open Source
      tier: observed
      url: /providers/open-elevation/
  - capability:
      attribution: API Evangelist extension
      id: AE-902
      key: AE-902
      name: Mobile Attribution & Deep Linking
      url: /capabilities/mobile-attribution-deep-linking/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 21.9
      apps:
      - ChargePoint
      band: thin
      in_catalog: true
      kin_score: 33.8
      mcp:
        status: none
      name: Branch
      slug: branch-io
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.coulombtech/latest/
      status: profiled
      tags:
      - Company
      tier: observed
      url: /providers/branch-io/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.20
      key: AE-150.20.20
      name: WhatsApp & OTT Messaging
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    providers:
    - agent_band: agent-aware
      agent_readiness: 25.3
      apps:
      - evcc
      band: strong
      in_catalog: true
      kin_score: 56.8
      mcp:
        status: none
      name: Telegram
      slug: telegram
      sources:
      - https://raw.githubusercontent.com/evcc-io/evcc/master/go.mod
      status: profiled
      tags:
      - Bots
      - Chat
      - Messaging
      - Notification
      tier: observed
      url: /providers/telegram/
  layer: common
summary:
  coverage_pct: 94.2
  declared_only: 8
  distinct_providers: 104
  in_catalog: 98
  mcp:
    documented: 1
    none: 51
    unchecked: 6
    verified: 10
  mcp_verified: 10
  mean_kin_score: 23.9
  observed: 96
  queued: 6
  reference_apps: 7
title: 'Connected Car & EV Charging: application blueprint'
---
