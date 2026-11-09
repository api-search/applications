---
app: Open Charge Map
app_slug: open-charge-map
app_url: https://github.com/openchargemap/ocm-system
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-200.20.20
  key: AE-200.20.20
  layer: domain
  name: EV Charging
  providers:
  - ChargePoint
  - Chargesini
  - data.gouv.fr
  - Department of Energy (AFDC)
  - ESB ecars
  - EV24
  - FLO (AddEnergie)
  - ICAEN (Catalonia)
  - NOBIL (Enova)
  - Oplaadpalen.nl
  - PlugShare
  - RWE Mobility
  - UK National Chargepoint Registry
  url: /capabilities/connected-vehicles/
  via_parent: Connected Vehicles
category:
  id: connected-car-ev-charging
  name: Connected Car & EV Charging
  url: /applications/connected-car-ev-charging/
counts:
  declared: 0
  observed: 13
credits: []
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
  facts:
    agent_band: human-only
    agent_readiness: 3.1
    band: thin
    in_catalog: true
    kin_score: 27.5
    mcp: &id001
      status: none
    slug: chargepoint
    status: profiled
    tags: &id002
    - EV Charging
    - Electric Vehicles
    - Energy Management
    - Fleet Management
    url: /providers/chargepoint/
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
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 9.8
    mcp: &id003
      status: unknown
    slug: chargesini
    status: profiled
    tags: &id004
    - Company
    - EV Charging
    - Malaysia
    - Sustainability
    url: /providers/chargesini/
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
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id005
      status: unchecked
    slug: data-gouv-fr
    status: queued for profiling
    tags: &id006 []
    url: null
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
  facts:
    agent_band: agent-aware
    agent_readiness: 18.6
    band: thin
    in_catalog: true
    kin_score: 38.6
    mcp: &id007
      status: none
    slug: doe
    status: profiled
    tags: &id008
    - Electricity
    - Energy
    - Government
    - Renewable Energy
    url: /providers/doe/
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
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 5.7
    mcp: &id009
      status: unknown
    slug: esb
    status: profiled
    tags: &id010
    - Energy
    - Ireland
    - Renewables
    - Utilities
    url: /providers/esb/
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
  facts:
    agent_band: human-only
    agent_readiness: 2.9
    band: emerging
    in_catalog: true
    kin_score: 13.5
    mcp: &id011
      status: unknown
    slug: ev24
    status: profiled
    tags: &id012
    - EV Charging
    - Energy
    - Platform
    - Software-as-a-Service
    url: /providers/ev24/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 20.3
    band: thin
    in_catalog: true
    kin_score: 27.9
    mcp: &id013
      status: unknown
    slug: flo-ev
    status: profiled
    tags: &id014
    - Canada
    - EV Charging
    - Electricity
    - Energy
    url: /providers/flo-ev/
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
  facts:
    agent_band: human-only
    agent_readiness: 2.5
    band: minimal
    in_catalog: true
    kin_score: 9.8
    mcp: &id015
      status: unknown
    slug: icaen
    status: profiled
    tags: &id016
    - Company
    - Energy
    - Public Institution
    - Research
    url: /providers/icaen/
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
  facts:
    agent_band: human-only
    agent_readiness: 5.0
    band: emerging
    in_catalog: true
    kin_score: 12.1
    mcp: &id017
      status: unknown
    slug: nobil
    status: profiled
    tags: &id018
    - Charging
    - Data
    - Electric Vehicles
    - Energy
    url: /providers/nobil/
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
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id019
      status: unchecked
    slug: oplaadpalen
    status: queued for profiling
    tags: &id020 []
    url: null
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
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 5.3
    mcp: &id021
      status: none
    slug: plugshare
    status: profiled
    tags: &id022
    - Company
    url: /providers/plugshare/
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
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 5.1
    mcp: &id023
      status: unknown
    slug: rwe
    status: profiled
    tags: &id024
    - Energy
    - Mobility
    - Renewables
    - Sustainability
    url: /providers/rwe/
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
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id025
      status: unchecked
    slug: national-chargepoint-registry
    status: queued for profiling
    tags: &id026 []
    url: null
  layer: domain
  name: UK National Chargepoint Registry
  provider: national-chargepoint-registry
  says: ships the UK National Chargepoint Registry SDK or integration code
  source: https://github.com/openchargemap/ocm-system/blob/master/Import/OCM.Import.Common/Providers/ImportProvider_UKChargePointRegistry.cs
  tier: observed
kind: open-source-saas
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/connected-car-ev-charging/open-charge-map/
providers:
- agent_band: human-only
  agent_readiness: 3.1
  band: thin
  in_catalog: true
  kin_score: 27.5
  mcp: *id001
  name: ChargePoint
  slug: chargepoint
  status: profiled
  tags: *id002
  url: /providers/chargepoint/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 9.8
  mcp: *id003
  name: Chargesini
  slug: chargesini
  status: profiled
  tags: *id004
  url: /providers/chargesini/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id005
  name: data.gouv.fr
  slug: data-gouv-fr
  status: queued for profiling
  tags: *id006
  url: null
- agent_band: agent-aware
  agent_readiness: 18.6
  band: thin
  in_catalog: true
  kin_score: 38.6
  mcp: *id007
  name: Department of Energy (AFDC)
  slug: doe
  status: profiled
  tags: *id008
  url: /providers/doe/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 5.7
  mcp: *id009
  name: ESB ecars
  slug: esb
  status: profiled
  tags: *id010
  url: /providers/esb/
- agent_band: human-only
  agent_readiness: 2.9
  band: emerging
  in_catalog: true
  kin_score: 13.5
  mcp: *id011
  name: EV24
  slug: ev24
  status: profiled
  tags: *id012
  url: /providers/ev24/
- agent_band: agent-aware
  agent_readiness: 20.3
  band: thin
  in_catalog: true
  kin_score: 27.9
  mcp: *id013
  name: FLO (AddEnergie)
  slug: flo-ev
  status: profiled
  tags: *id014
  url: /providers/flo-ev/
- agent_band: human-only
  agent_readiness: 2.5
  band: minimal
  in_catalog: true
  kin_score: 9.8
  mcp: *id015
  name: ICAEN (Catalonia)
  slug: icaen
  status: profiled
  tags: *id016
  url: /providers/icaen/
- agent_band: human-only
  agent_readiness: 5.0
  band: emerging
  in_catalog: true
  kin_score: 12.1
  mcp: *id017
  name: NOBIL (Enova)
  slug: nobil
  status: profiled
  tags: *id018
  url: /providers/nobil/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id019
  name: Oplaadpalen.nl
  slug: oplaadpalen
  status: queued for profiling
  tags: *id020
  url: null
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 5.3
  mcp: *id021
  name: PlugShare
  slug: plugshare
  status: profiled
  tags: *id022
  url: /providers/plugshare/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 5.1
  mcp: *id023
  name: RWE Mobility
  slug: rwe
  status: profiled
  tags: *id024
  url: /providers/rwe/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id025
  name: UK National Chargepoint Registry
  slug: national-chargepoint-registry
  status: queued for profiling
  tags: *id026
  url: null
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
title: 'Open Charge Map: Connected Car & EV Charging reference app'
---
