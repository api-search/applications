---
app: Karrio
app_slug: karrio
app_url: https://github.com/karrioapi/karrio
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-928
  key: AE-928
  layer: domain
  name: Parcel Rating & Label Purchase
  providers:
  - Asendia
  - Australia Post
  - Austrian Post (Post AG)
  - bpost
  - Canada Post
  - Chronopost
  - DHL
  - DPD
  - FedEx
  - GLS
  - Hermes Germany
  - La Poste
  - Landmark Global
  - ParcelOne
  - Purolator
  - SEKO Logistics
  - Sendle
  - SmartKargo
  - Spring GDS
  - Teleship
  - UPS
  - USPS
  url: /capabilities/logistics-operations-management/
  via_parent: Logistics Operations Management
- attribution: API Evangelist extension
  id: AE-120.10.30
  key: AE-120.10.30
  layer: common
  name: Address Validation & Autocomplete
  providers:
  - Canada Post
  url: /capabilities/geocoding/
  via_parent: Geocoding
- attribution: API Evangelist extension
  id: AE-120.10.10
  key: AE-120.10.10
  layer: common
  name: Forward Geocoding
  providers:
  - Google Maps Platform (Geocoding)
  url: /capabilities/geocoding/
  via_parent: Geocoding
category:
  id: shipping-fulfillment
  name: Shipping, Fulfillment & Returns
  url: /applications/shipping-fulfillment/
counts:
  declared: 0
  observed: 24
credits: []
evidence:
- route: source code
  url: https://github.com/karrioapi/karrio/blob/main/.env.sample
- route: source code
  url: https://github.com/karrioapi/karrio/tree/main/modules/connectors
- route: source code
  url: https://github.com/karrioapi/karrio/tree/main/plugins
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-928
    key: AE-928
    name: Parcel Rating & Label Purchase
    url: /capabilities/logistics-operations-management/
    via_parent: Logistics Operations Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 17.2
    band: emerging
    in_catalog: true
    kin_score: 25.2
    mcp: &id002
      status: none
    slug: asendia
    status: profiled
    tags: &id003
    - Company
    - Logistics
    - Parcel
    - Shipping
    url: /providers/asendia/
  layer: domain
  name: Asendia
  provider: asendia
  says: ships the Asendia SDK or integration code
  source: https://github.com/karrioapi/karrio/tree/main/modules/connectors
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-928
    key: AE-928
    name: Parcel Rating & Label Purchase
    url: /capabilities/logistics-operations-management/
    via_parent: Logistics Operations Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.5
    band: strong
    in_catalog: true
    kin_score: 56.9
    mcp: &id004
      status: none
    slug: australia-post
    status: profiled
    tags: &id005
    - Address Validation
    - Click and Collect
    - Delivery
    - E-Commerce
    url: /providers/australia-post/
  layer: domain
  name: Australia Post
  provider: australia-post
  says: ships the Australia Post SDK or integration code
  source: https://github.com/karrioapi/karrio/tree/main/modules/connectors
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-928
    key: AE-928
    name: Parcel Rating & Label Purchase
    url: /capabilities/logistics-operations-management/
    via_parent: Logistics Operations Management
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 10.0
    mcp: &id006
      status: unknown
    slug: austrian-post
    status: profiled
    tags: &id007
    - Austria
    - Company
    - Logistics
    - Postal
    url: /providers/austrian-post/
  layer: domain
  name: Austrian Post (Post AG)
  provider: austrian-post
  says: ships the Austrian Post (Post AG) SDK or integration code
  source: https://github.com/karrioapi/karrio/tree/main/modules/connectors
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-928
    key: AE-928
    name: Parcel Rating & Label Purchase
    url: /capabilities/logistics-operations-management/
    via_parent: Logistics Operations Management
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.9
    band: minimal
    in_catalog: true
    kin_score: 6.0
    mcp: &id008
      status: unknown
    slug: bpost
    status: profiled
    tags: &id009
    - Belgium
    - Company
    - Logistics
    - Postal
    url: /providers/bpost/
  layer: domain
  name: bpost
  provider: bpost
  says: ships the bpost SDK or integration code
  source: https://github.com/karrioapi/karrio/tree/main/modules/connectors
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-928
    key: AE-928
    name: Parcel Rating & Label Purchase
    url: /capabilities/logistics-operations-management/
    via_parent: Logistics Operations Management
  credit: null
  facts: &id001
    agent_band: human-only
    agent_readiness: 0.6
    band: emerging
    in_catalog: true
    kin_score: 18.0
    mcp: &id010
      status: none
    slug: canada-post
    status: profiled
    tags: &id011
    - Address Validation
    - E-Commerce
    - Labels
    - Logistics
    url: /providers/canada-post/
  layer: domain
  name: Canada Post
  provider: canada-post
  says: ships the Canada Post SDK or integration code
  source: https://github.com/karrioapi/karrio/tree/main/modules/connectors
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-120.10.30
    key: AE-120.10.30
    name: Address Validation & Autocomplete
    url: /capabilities/geocoding/
    via_parent: Geocoding
  credit: null
  facts: *id001
  layer: common
  name: Canada Post
  provider: canada-post
  says: ships the Canada Post SDK or integration code
  source: https://github.com/karrioapi/karrio/tree/main/plugins
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-928
    key: AE-928
    name: Parcel Rating & Label Purchase
    url: /capabilities/logistics-operations-management/
    via_parent: Logistics Operations Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 12.9
    band: emerging
    in_catalog: true
    kin_score: 20.4
    mcp: &id012
      status: none
    slug: chronopost
    status: profiled
    tags: &id013
    - Company
    - Logistics
    - Parcel Delivery
    - Shipping
    url: /providers/chronopost/
  layer: domain
  name: Chronopost
  provider: chronopost
  says: ships the Chronopost SDK or integration code
  source: https://github.com/karrioapi/karrio/tree/main/modules/connectors
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-928
    key: AE-928
    name: Parcel Rating & Label Purchase
    url: /capabilities/logistics-operations-management/
    via_parent: Logistics Operations Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.1
    band: emerging
    in_catalog: true
    kin_score: 26.1
    mcp: &id014
      status: none
    slug: dhl
    status: profiled
    tags: &id015
    - E-Commerce
    - Freight
    - Logistics
    - Shipping
    url: /providers/dhl/
  layer: domain
  name: DHL
  provider: dhl
  says: ships the DHL SDK or integration code
  source: https://github.com/karrioapi/karrio/tree/main/modules/connectors
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-928
    key: AE-928
    name: Parcel Rating & Label Purchase
    url: /capabilities/logistics-operations-management/
    via_parent: Logistics Operations Management
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 4.9
    mcp: &id016
      status: none
    slug: dpd
    status: profiled
    tags: &id017
    - Company
    - International Shipping
    - Logistics
    - Parcel Delivery
    url: /providers/dpd/
  layer: domain
  name: DPD
  provider: dpd
  says: ships the DPD SDK or integration code
  source: https://github.com/karrioapi/karrio/tree/main/modules/connectors
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-928
    key: AE-928
    name: Parcel Rating & Label Purchase
    url: /capabilities/logistics-operations-management/
    via_parent: Logistics Operations Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 35.9
    band: exemplar
    in_catalog: true
    kin_score: 69.4
    mcp: &id018
      status: none
    slug: fedex
    status: profiled
    tags: &id019
    - Address Validation
    - Freight
    - Logistics
    - Pickup
    url: /providers/fedex/
  layer: domain
  name: FedEx
  provider: fedex
  says: ships the FedEx SDK or integration code
  source: https://github.com/karrioapi/karrio/tree/main/modules/connectors
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-928
    key: AE-928
    name: Parcel Rating & Label Purchase
    url: /capabilities/logistics-operations-management/
    via_parent: Logistics Operations Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 29.2
    band: emerging
    in_catalog: true
    kin_score: 23.5
    mcp: &id020
      status: none
    slug: gls-group
    status: profiled
    tags: &id021
    - Logistics
    - Netherlands
    - Parcel
    - Supply Chain
    url: /providers/gls-group/
  layer: domain
  name: GLS
  provider: gls-group
  says: ships the GLS SDK or integration code
  source: https://github.com/karrioapi/karrio/tree/main/modules/connectors
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
    agent_band: agent-ready
    agent_readiness: 36.0
    band: exemplar
    in_catalog: true
    kin_score: 71.4
    mcp: &id022
      source: https://developers.google.com/maps/ai/grounding-lite
      status: verified
    slug: google-maps
    status: profiled
    tags: &id023
    - Environment
    - Geocoding
    - Geolocation
    - Maps
    url: /providers/google-maps/
  layer: common
  name: Google Maps Platform (Geocoding)
  provider: google-maps
  says: ships the Google Maps Platform (Geocoding) SDK or integration code
  source: https://github.com/karrioapi/karrio/tree/main/plugins
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-928
    key: AE-928
    name: Parcel Rating & Label Purchase
    url: /capabilities/logistics-operations-management/
    via_parent: Logistics Operations Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 5.4
    band: minimal
    in_catalog: true
    kin_score: 4.6
    mcp: &id024
      status: unknown
    slug: hermes-germany
    status: profiled
    tags: &id025
    - E-Commerce
    - Logistics
    - Parcel
    - Shipping
    url: /providers/hermes-germany/
  layer: domain
  name: Hermes Germany
  provider: hermes-germany
  says: ships the Hermes Germany SDK or integration code
  source: https://github.com/karrioapi/karrio/tree/main/modules/connectors
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-928
    key: AE-928
    name: Parcel Rating & Label Purchase
    url: /capabilities/logistics-operations-management/
    via_parent: Logistics Operations Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 21.5
    band: thin
    in_catalog: true
    kin_score: 33.5
    mcp: &id026
      status: unknown
    slug: la-poste
    status: profiled
    tags: &id027
    - Address Validation
    - Geolocation
    - Parcel Tracking
    - Postal
    url: /providers/la-poste/
  layer: domain
  name: La Poste
  provider: la-poste
  says: ships the La Poste SDK or integration code
  source: https://github.com/karrioapi/karrio/tree/main/modules/connectors
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-928
    key: AE-928
    name: Parcel Rating & Label Purchase
    url: /capabilities/logistics-operations-management/
    via_parent: Logistics Operations Management
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 11.0
    mcp: &id028
      status: none
    slug: landmark-global
    status: profiled
    tags: &id029
    - Company
    - E-Commerce
    - Logistics
    - Shipping
    url: /providers/landmark-global/
  layer: domain
  name: Landmark Global
  provider: landmark-global
  says: ships the Landmark Global SDK or integration code
  source: https://github.com/karrioapi/karrio/tree/main/modules/connectors
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-928
    key: AE-928
    name: Parcel Rating & Label Purchase
    url: /capabilities/logistics-operations-management/
    via_parent: Logistics Operations Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 34.6
    band: thin
    in_catalog: true
    kin_score: 35.2
    mcp: &id030
      status: unknown
    slug: parcelone
    status: profiled
    tags: &id031
    - E-Commerce
    - Fulfillment
    - Logistics
    - Shipping
    url: /providers/parcelone/
  layer: domain
  name: ParcelOne
  provider: parcelone
  says: ships the ParcelOne SDK or integration code
  source: https://github.com/karrioapi/karrio/tree/main/modules/connectors
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-928
    key: AE-928
    name: Parcel Rating & Label Purchase
    url: /capabilities/logistics-operations-management/
    via_parent: Logistics Operations Management
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.5
    band: emerging
    in_catalog: true
    kin_score: 17.8
    mcp: &id032
      status: none
    slug: purolator
    status: profiled
    tags: &id033
    - Company
    - Couriers
    - Logistics
    - Shipping
    url: /providers/purolator/
  layer: domain
  name: Purolator
  provider: purolator
  says: ships the Purolator SDK or integration code
  source: https://github.com/karrioapi/karrio/tree/main/modules/connectors
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-928
    key: AE-928
    name: Parcel Rating & Label Purchase
    url: /capabilities/logistics-operations-management/
    via_parent: Logistics Operations Management
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 8.4
    mcp: &id034
      status: none
    slug: seko-logistics
    status: profiled
    tags: &id035
    - Company
    - Freight
    - Logistics
    - Supply Chain
    url: /providers/seko-logistics/
  layer: domain
  name: SEKO Logistics
  provider: seko-logistics
  says: ships the SEKO Logistics SDK or integration code
  source: https://github.com/karrioapi/karrio/tree/main/modules/connectors
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-928
    key: AE-928
    name: Parcel Rating & Label Purchase
    url: /capabilities/logistics-operations-management/
    via_parent: Logistics Operations Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 32.6
    band: developing
    in_catalog: true
    kin_score: 43.1
    mcp: &id036
      status: none
    slug: sendle
    status: profiled
    tags: &id037
    - Last Mile Delivery
    - Logistics
    - Parcel
    - Shipping
    url: /providers/sendle/
  layer: domain
  name: Sendle
  provider: sendle
  says: ships the Sendle SDK or integration code
  source: https://github.com/karrioapi/karrio/tree/main/modules/connectors
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-928
    key: AE-928
    name: Parcel Rating & Label Purchase
    url: /capabilities/logistics-operations-management/
    via_parent: Logistics Operations Management
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 6.0
    mcp: &id038
      status: unknown
    slug: smartkargo
    status: profiled
    tags: &id039
    - Air Cargo
    - Company
    - E-Commerce
    - Logistics
    url: /providers/smartkargo/
  layer: domain
  name: SmartKargo
  provider: smartkargo
  says: ships the SmartKargo SDK or integration code
  source: https://github.com/karrioapi/karrio/tree/main/modules/connectors
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-928
    key: AE-928
    name: Parcel Rating & Label Purchase
    url: /capabilities/logistics-operations-management/
    via_parent: Logistics Operations Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 6.5
    band: minimal
    in_catalog: true
    kin_score: 6.0
    mcp: &id040
      status: unknown
    slug: spring-gds
    status: profiled
    tags: &id041
    - Company
    - E-Commerce
    - Logistics
    - Shipping
    url: /providers/spring-gds/
  layer: domain
  name: Spring GDS
  provider: spring-gds
  says: ships the Spring GDS SDK or integration code
  source: https://github.com/karrioapi/karrio/tree/main/modules/connectors
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-928
    key: AE-928
    name: Parcel Rating & Label Purchase
    url: /capabilities/logistics-operations-management/
    via_parent: Logistics Operations Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 19.8
    band: emerging
    in_catalog: true
    kin_score: 26.0
    mcp: &id042
      status: none
    slug: teleship
    status: profiled
    tags: &id043
    - DDP
    - E-Commerce
    - Shipping
    - Tax
    url: /providers/teleship/
  layer: domain
  name: Teleship
  provider: teleship
  says: ships the Teleship SDK or integration code
  source: https://github.com/karrioapi/karrio/tree/main/modules/connectors
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-928
    key: AE-928
    name: Parcel Rating & Label Purchase
    url: /capabilities/logistics-operations-management/
    via_parent: Logistics Operations Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.1
    band: thin
    in_catalog: true
    kin_score: 29.0
    mcp: &id044
      source: https://github.com/UPS-API/ups-mcp
      status: verified
    slug: ups
    status: profiled
    tags: &id045
    - Fortune 500
    - Logistics
    - Shipping
    - Supply Chain
    url: /providers/ups/
  layer: domain
  name: UPS
  provider: ups
  says: ships the UPS SDK or integration code
  source: https://github.com/karrioapi/karrio/tree/main/modules/connectors
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-928
    key: AE-928
    name: Parcel Rating & Label Purchase
    url: /capabilities/logistics-operations-management/
    via_parent: Logistics Operations Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.9
    band: thin
    in_catalog: true
    kin_score: 33.2
    mcp: &id046
      status: none
    slug: usps
    status: profiled
    tags: &id047
    - Government
    - Logistics
    - Postal Service
    - Shipping
    url: /providers/usps/
  layer: domain
  name: USPS
  provider: usps
  says: ships the USPS SDK or integration code
  source: https://github.com/karrioapi/karrio/tree/main/modules/connectors
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/shipping-fulfillment/karrio/
providers:
- agent_band: agent-aware
  agent_readiness: 17.2
  band: emerging
  in_catalog: true
  kin_score: 25.2
  mcp: *id002
  name: Asendia
  slug: asendia
  status: profiled
  tags: *id003
  url: /providers/asendia/
- agent_band: agent-ready
  agent_readiness: 31.5
  band: strong
  in_catalog: true
  kin_score: 56.9
  mcp: *id004
  name: Australia Post
  slug: australia-post
  status: profiled
  tags: *id005
  url: /providers/australia-post/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 10.0
  mcp: *id006
  name: Austrian Post (Post AG)
  slug: austrian-post
  status: profiled
  tags: *id007
  url: /providers/austrian-post/
- agent_band: human-only
  agent_readiness: 2.9
  band: minimal
  in_catalog: true
  kin_score: 6.0
  mcp: *id008
  name: bpost
  slug: bpost
  status: profiled
  tags: *id009
  url: /providers/bpost/
- agent_band: human-only
  agent_readiness: 0.6
  band: emerging
  in_catalog: true
  kin_score: 18.0
  mcp: *id010
  name: Canada Post
  slug: canada-post
  status: profiled
  tags: *id011
  url: /providers/canada-post/
- agent_band: agent-aware
  agent_readiness: 12.9
  band: emerging
  in_catalog: true
  kin_score: 20.4
  mcp: *id012
  name: Chronopost
  slug: chronopost
  status: profiled
  tags: *id013
  url: /providers/chronopost/
- agent_band: agent-aware
  agent_readiness: 24.1
  band: emerging
  in_catalog: true
  kin_score: 26.1
  mcp: *id014
  name: DHL
  slug: dhl
  status: profiled
  tags: *id015
  url: /providers/dhl/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 4.9
  mcp: *id016
  name: DPD
  slug: dpd
  status: profiled
  tags: *id017
  url: /providers/dpd/
- agent_band: agent-ready
  agent_readiness: 35.9
  band: exemplar
  in_catalog: true
  kin_score: 69.4
  mcp: *id018
  name: FedEx
  slug: fedex
  status: profiled
  tags: *id019
  url: /providers/fedex/
- agent_band: agent-ready
  agent_readiness: 29.2
  band: emerging
  in_catalog: true
  kin_score: 23.5
  mcp: *id020
  name: GLS
  slug: gls-group
  status: profiled
  tags: *id021
  url: /providers/gls-group/
- agent_band: agent-ready
  agent_readiness: 36.0
  band: exemplar
  in_catalog: true
  kin_score: 71.4
  mcp: *id022
  name: Google Maps Platform (Geocoding)
  slug: google-maps
  status: profiled
  tags: *id023
  url: /providers/google-maps/
- agent_band: agent-aware
  agent_readiness: 5.4
  band: minimal
  in_catalog: true
  kin_score: 4.6
  mcp: *id024
  name: Hermes Germany
  slug: hermes-germany
  status: profiled
  tags: *id025
  url: /providers/hermes-germany/
- agent_band: agent-aware
  agent_readiness: 21.5
  band: thin
  in_catalog: true
  kin_score: 33.5
  mcp: *id026
  name: La Poste
  slug: la-poste
  status: profiled
  tags: *id027
  url: /providers/la-poste/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 11.0
  mcp: *id028
  name: Landmark Global
  slug: landmark-global
  status: profiled
  tags: *id029
  url: /providers/landmark-global/
- agent_band: agent-ready
  agent_readiness: 34.6
  band: thin
  in_catalog: true
  kin_score: 35.2
  mcp: *id030
  name: ParcelOne
  slug: parcelone
  status: profiled
  tags: *id031
  url: /providers/parcelone/
- agent_band: human-only
  agent_readiness: 3.5
  band: emerging
  in_catalog: true
  kin_score: 17.8
  mcp: *id032
  name: Purolator
  slug: purolator
  status: profiled
  tags: *id033
  url: /providers/purolator/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 8.4
  mcp: *id034
  name: SEKO Logistics
  slug: seko-logistics
  status: profiled
  tags: *id035
  url: /providers/seko-logistics/
- agent_band: agent-ready
  agent_readiness: 32.6
  band: developing
  in_catalog: true
  kin_score: 43.1
  mcp: *id036
  name: Sendle
  slug: sendle
  status: profiled
  tags: *id037
  url: /providers/sendle/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 6.0
  mcp: *id038
  name: SmartKargo
  slug: smartkargo
  status: profiled
  tags: *id039
  url: /providers/smartkargo/
- agent_band: agent-aware
  agent_readiness: 6.5
  band: minimal
  in_catalog: true
  kin_score: 6.0
  mcp: *id040
  name: Spring GDS
  slug: spring-gds
  status: profiled
  tags: *id041
  url: /providers/spring-gds/
- agent_band: agent-aware
  agent_readiness: 19.8
  band: emerging
  in_catalog: true
  kin_score: 26.0
  mcp: *id042
  name: Teleship
  slug: teleship
  status: profiled
  tags: *id043
  url: /providers/teleship/
- agent_band: agent-aware
  agent_readiness: 24.1
  band: thin
  in_catalog: true
  kin_score: 29.0
  mcp: *id044
  name: UPS
  slug: ups
  status: profiled
  tags: *id045
  url: /providers/ups/
- agent_band: agent-ready
  agent_readiness: 31.9
  band: thin
  in_catalog: true
  kin_score: 33.2
  mcp: *id046
  name: USPS
  slug: usps
  status: profiled
  tags: *id047
  url: /providers/usps/
siblings:
- name: ERPNext Shipping
  rows: 2
  url: /applications/shipping-fulfillment/erpnext-shipping/
- name: Loop Returns
  rows: 9
  url: /applications/shipping-fulfillment/loop-returns/
- name: Odoo Inventory (delivery connectors)
  rows: 11
  url: /applications/shipping-fulfillment/odoo-inventory-delivery-connectors/
- name: Sendcloud
  rows: 53
  url: /applications/shipping-fulfillment/sendcloud/
- name: Shippo
  rows: 33
  url: /applications/shipping-fulfillment/shippo/
sitemap: true
title: 'Karrio: Shipping, Fulfillment & Returns reference app'
---
