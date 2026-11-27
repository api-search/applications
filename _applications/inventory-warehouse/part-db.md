---
app: Part-DB
app_slug: part-db
app_url: https://github.com/Part-DB/Part-DB-server
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-1930
  key: electronic-component-sourcing-management
  layer: domain
  name: Electronic Component Sourcing Management
  providers:
  - Adafruit
  - Bambu Lab
  - Buerklin
  - Canopy API (canopyapi.co)
  - Conrad Electronic
  - Digi-Key
  - element14 / Farnell
  - LCSC Electronics
  - Mouser Electronics
  - Octopart
  - OEMsecrets
  - Pollin Electronic
  - Pololu
  - Reichelt Elektronik
  - SparkFun Electronics
  - TME (Transfer Multisort Elektronik)
  - TrustedParts
  url: /capabilities/electronic-component-sourcing-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-110.10.30
  key: AE-110.10.30
  layer: agent
  name: Model Routing & Gateways
  providers:
  - OpenRouter
  url: /capabilities/model-inference/
  via_parent: Model Inference
- attribution: API Evangelist extension
  id: AE-110.10.40
  key: AE-110.10.40
  layer: agent
  name: On-Device & Edge Inference
  providers:
  - LM Studio
  - Ollama
  url: /capabilities/model-inference/
  via_parent: Model Inference
category:
  id: inventory-warehouse
  name: Inventory & Warehouse Management
  url: /applications/inventory-warehouse/
counts:
  declared: 0
  observed: 20
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/Part-DB/Part-DB-server/master/composer.json
- route: source code
  url: https://github.com/Part-DB/Part-DB-server/tree/master/src/Services/InfoProviderSystem/Providers
integrations:
- capability:
    attribution: Turbo EA
    id: BC-1930
    key: electronic-component-sourcing-management
    name: Electronic Component Sourcing Management
    url: /capabilities/electronic-component-sourcing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id001
      status: unchecked
    slug: adafruit
    status: queued for profiling
    tags: &id002 []
    url: null
  layer: domain
  name: Adafruit
  provider: adafruit
  says: ships the Adafruit SDK or integration code
  source: https://github.com/Part-DB/Part-DB-server/tree/master/src/Services/InfoProviderSystem/Providers
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-1930
    key: electronic-component-sourcing-management
    name: Electronic Component Sourcing Management
    url: /capabilities/electronic-component-sourcing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 19.3
    mcp: &id003
      status: none
    slug: bambu-lab
    status: profiled
    tags: &id004
    - 3D Printing
    - Company
    - Consumer Technology
    - Hardware
    url: /providers/bambu-lab/
  layer: domain
  name: Bambu Lab
  provider: bambu-lab
  says: ships the Bambu Lab SDK or integration code
  source: https://github.com/Part-DB/Part-DB-server/tree/master/src/Services/InfoProviderSystem/Providers
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-1930
    key: electronic-component-sourcing-management
    name: Electronic Component Sourcing Management
    url: /capabilities/electronic-component-sourcing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 0.4
    mcp: &id005
      status: unknown
    slug: buerklin
    status: profiled
    tags: &id006
    - Company
    url: /providers/buerklin/
  layer: domain
  name: Buerklin
  provider: buerklin
  says: ships the Buerklin SDK or integration code
  source: https://github.com/Part-DB/Part-DB-server/tree/master/src/Services/InfoProviderSystem/Providers
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-1930
    key: electronic-component-sourcing-management
    name: Electronic Component Sourcing Management
    url: /capabilities/electronic-component-sourcing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id007
      status: unchecked
    slug: canopy-api
    status: queued for profiling
    tags: &id008 []
    url: null
  layer: domain
  name: Canopy API (canopyapi.co)
  provider: canopy-api
  says: ships the Canopy API (canopyapi.co) SDK or integration code
  source: https://github.com/Part-DB/Part-DB-server/tree/master/src/Services/InfoProviderSystem/Providers
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-1930
    key: electronic-component-sourcing-management
    name: Electronic Component Sourcing Management
    url: /capabilities/electronic-component-sourcing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 4.5
    mcp: &id009
      status: unknown
    slug: conrad
    status: profiled
    tags: &id010
    - Company
    - E-Commerce
    - Electronics
    - Retail
    url: /providers/conrad/
  layer: domain
  name: Conrad Electronic
  provider: conrad
  says: ships the Conrad Electronic SDK or integration code
  source: https://github.com/Part-DB/Part-DB-server/tree/master/src/Services/InfoProviderSystem/Providers
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-1930
    key: electronic-component-sourcing-management
    name: Electronic Component Sourcing Management
    url: /capabilities/electronic-component-sourcing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 27.5
    band: developing
    in_catalog: true
    kin_score: 53.9
    mcp: &id011
      status: none
    slug: digi-key
    status: profiled
    tags: &id012
    - Distribution
    - Electronic Components
    - Public APIs
    - Shopping
    url: /providers/digi-key/
  layer: domain
  name: Digi-Key
  provider: digi-key
  says: ships the Digi-Key SDK or integration code
  source: https://github.com/Part-DB/Part-DB-server/tree/master/src/Services/InfoProviderSystem/Providers
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-1930
    key: electronic-component-sourcing-management
    name: Electronic Component Sourcing Management
    url: /capabilities/electronic-component-sourcing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 3.5
    mcp: &id013
      status: none
    slug: element14
    status: profiled
    tags: &id014
    - Company
    - Distribution
    - Electronics
    - Engineering
    url: /providers/element14/
  layer: domain
  name: element14 / Farnell
  provider: element14
  says: ships the element14 / Farnell SDK or integration code
  source: https://github.com/Part-DB/Part-DB-server/tree/master/src/Services/InfoProviderSystem/Providers
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-1930
    key: electronic-component-sourcing-management
    name: Electronic Component Sourcing Management
    url: /capabilities/electronic-component-sourcing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 3.8
    mcp: &id015
      status: unknown
    slug: lcsc
    status: profiled
    tags: &id016
    - Company
    - Components
    - Distributor
    - Electronics
    url: /providers/lcsc/
  layer: domain
  name: LCSC Electronics
  provider: lcsc
  says: ships the LCSC Electronics SDK or integration code
  source: https://github.com/Part-DB/Part-DB-server/tree/master/src/Services/InfoProviderSystem/Providers
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
    agent_readiness: 22.5
    band: thin
    in_catalog: true
    kin_score: 32.2
    mcp: &id017
      status: none
    slug: lm-studio
    status: profiled
    tags: &id018
    - Artificial Intelligence
    - Company
    - Local LLM
    - Machine Learning
    url: /providers/lm-studio/
  layer: agent
  name: LM Studio
  provider: lm-studio
  says: ships the LM Studio SDK or integration code
  source: https://raw.githubusercontent.com/Part-DB/Part-DB-server/master/composer.json
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-1930
    key: electronic-component-sourcing-management
    name: Electronic Component Sourcing Management
    url: /capabilities/electronic-component-sourcing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 1.8
    mcp: &id019
      status: none
    slug: mouser
    status: profiled
    tags: &id020
    - Company
    url: /providers/mouser/
  layer: domain
  name: Mouser Electronics
  provider: mouser
  says: ships the Mouser Electronics SDK or integration code
  source: https://github.com/Part-DB/Part-DB-server/tree/master/src/Services/InfoProviderSystem/Providers
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-1930
    key: electronic-component-sourcing-management
    name: Electronic Component Sourcing Management
    url: /capabilities/electronic-component-sourcing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 7.2
    mcp: &id021
      status: none
    slug: octopart
    status: profiled
    tags: &id022
    - Public APIs
    - Shopping
    url: /providers/octopart/
  layer: domain
  name: Octopart
  provider: octopart
  says: ships the Octopart SDK or integration code
  source: https://github.com/Part-DB/Part-DB-server/tree/master/src/Services/InfoProviderSystem/Providers
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-1930
    key: electronic-component-sourcing-management
    name: Electronic Component Sourcing Management
    url: /capabilities/electronic-component-sourcing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 1.1
    band: minimal
    in_catalog: true
    kin_score: 0.4
    mcp: &id023
      status: unknown
    slug: oemsecrets
    status: profiled
    tags: &id024
    - Company
    url: /providers/oemsecrets/
  layer: domain
  name: OEMsecrets
  provider: oemsecrets
  says: ships the OEMsecrets SDK or integration code
  source: https://github.com/Part-DB/Part-DB-server/tree/master/src/Services/InfoProviderSystem/Providers
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
    mcp: &id025
      status: none
    slug: ollama
    status: profiled
    tags: &id026
    - Artificial Intelligence
    - LLM
    - Models
    - Ollama
    url: /providers/ollama/
  layer: agent
  name: Ollama
  provider: ollama
  says: ships the Ollama SDK or integration code
  source: https://raw.githubusercontent.com/Part-DB/Part-DB-server/master/composer.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.30
    key: AE-110.10.30
    name: Model Routing & Gateways
    url: /capabilities/model-inference/
    via_parent: Model Inference
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 46.4
    band: strong
    in_catalog: true
    kin_score: 54.8
    mcp: &id027
      source: https://openrouter.ai/docs/guides/overview/mcp-server
      status: verified
    slug: openrouter
    status: profiled
    tags: &id028
    - Artificial Intelligence
    - Gateways
    - LLM
    - Router
    url: /providers/openrouter/
  layer: agent
  name: OpenRouter
  provider: openrouter
  says: ships the OpenRouter SDK or integration code
  source: https://raw.githubusercontent.com/Part-DB/Part-DB-server/master/composer.json
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-1930
    key: electronic-component-sourcing-management
    name: Electronic Component Sourcing Management
    url: /capabilities/electronic-component-sourcing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.5
    band: emerging
    in_catalog: true
    kin_score: 13.8
    mcp: &id029
      status: unknown
    slug: pollin
    status: profiled
    tags: &id030
    - Company
    - E-Commerce
    - Electronics
    - Retail
    url: /providers/pollin/
  layer: domain
  name: Pollin Electronic
  provider: pollin
  says: ships the Pollin Electronic SDK or integration code
  source: https://github.com/Part-DB/Part-DB-server/tree/master/src/Services/InfoProviderSystem/Providers
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-1930
    key: electronic-component-sourcing-management
    name: Electronic Component Sourcing Management
    url: /capabilities/electronic-component-sourcing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 7.9
    mcp: &id031
      status: none
    slug: pololu
    status: profiled
    tags: &id032
    - Company
    - Electronics
    - Hobbyist
    - Robotics
    url: /providers/pololu/
  layer: domain
  name: Pololu
  provider: pololu
  says: ships the Pololu SDK or integration code
  source: https://github.com/Part-DB/Part-DB-server/tree/master/src/Services/InfoProviderSystem/Providers
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-1930
    key: electronic-component-sourcing-management
    name: Electronic Component Sourcing Management
    url: /capabilities/electronic-component-sourcing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 2.2
    mcp: &id033
      status: unknown
    slug: reichelt
    status: profiled
    tags: &id034
    - Components
    - Electronics
    - Hobbyist
    - Retail
    url: /providers/reichelt/
  layer: domain
  name: Reichelt Elektronik
  provider: reichelt
  says: ships the Reichelt Elektronik SDK or integration code
  source: https://github.com/Part-DB/Part-DB-server/tree/master/src/Services/InfoProviderSystem/Providers
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-1930
    key: electronic-component-sourcing-management
    name: Electronic Component Sourcing Management
    url: /capabilities/electronic-component-sourcing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 14.6
    mcp: &id035
      status: none
    slug: sparkfun
    status: profiled
    tags: &id036
    - Education
    - Electronics
    - Maker
    - Retail
    url: /providers/sparkfun/
  layer: domain
  name: SparkFun Electronics
  provider: sparkfun
  says: ships the SparkFun Electronics SDK or integration code
  source: https://github.com/Part-DB/Part-DB-server/tree/master/src/Services/InfoProviderSystem/Providers
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-1930
    key: electronic-component-sourcing-management
    name: Electronic Component Sourcing Management
    url: /capabilities/electronic-component-sourcing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 21.7
    band: emerging
    in_catalog: true
    kin_score: 17.0
    mcp: &id037
      status: unknown
    slug: tme
    status: profiled
    tags: &id038
    - Company
    url: /providers/tme/
  layer: domain
  name: TME (Transfer Multisort Elektronik)
  provider: tme
  says: ships the TME (Transfer Multisort Elektronik) SDK or integration code
  source: https://github.com/Part-DB/Part-DB-server/tree/master/src/Services/InfoProviderSystem/Providers
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-1930
    key: electronic-component-sourcing-management
    name: Electronic Component Sourcing Management
    url: /capabilities/electronic-component-sourcing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 14.1
    band: minimal
    in_catalog: true
    kin_score: 3.7
    mcp: &id039
      status: none
    slug: trustedparts
    status: profiled
    tags: &id040
    - Automotive
    - B2B
    - E-Commerce
    - Parts
    url: /providers/trustedparts/
  layer: domain
  name: TrustedParts
  provider: trustedparts
  says: ships the TrustedParts SDK or integration code
  source: https://github.com/Part-DB/Part-DB-server/tree/master/src/Services/InfoProviderSystem/Providers
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/inventory-warehouse/part-db/
providers:
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id001
  name: Adafruit
  slug: adafruit
  status: queued for profiling
  tags: *id002
  url: null
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 19.3
  mcp: *id003
  name: Bambu Lab
  slug: bambu-lab
  status: profiled
  tags: *id004
  url: /providers/bambu-lab/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 0.4
  mcp: *id005
  name: Buerklin
  slug: buerklin
  status: profiled
  tags: *id006
  url: /providers/buerklin/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id007
  name: Canopy API (canopyapi.co)
  slug: canopy-api
  status: queued for profiling
  tags: *id008
  url: null
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 4.5
  mcp: *id009
  name: Conrad Electronic
  slug: conrad
  status: profiled
  tags: *id010
  url: /providers/conrad/
- agent_band: agent-aware
  agent_readiness: 27.5
  band: developing
  in_catalog: true
  kin_score: 53.9
  mcp: *id011
  name: Digi-Key
  slug: digi-key
  status: profiled
  tags: *id012
  url: /providers/digi-key/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 3.5
  mcp: *id013
  name: element14 / Farnell
  slug: element14
  status: profiled
  tags: *id014
  url: /providers/element14/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 3.8
  mcp: *id015
  name: LCSC Electronics
  slug: lcsc
  status: profiled
  tags: *id016
  url: /providers/lcsc/
- agent_band: agent-aware
  agent_readiness: 22.5
  band: thin
  in_catalog: true
  kin_score: 32.2
  mcp: *id017
  name: LM Studio
  slug: lm-studio
  status: profiled
  tags: *id018
  url: /providers/lm-studio/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 1.8
  mcp: *id019
  name: Mouser Electronics
  slug: mouser
  status: profiled
  tags: *id020
  url: /providers/mouser/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 7.2
  mcp: *id021
  name: Octopart
  slug: octopart
  status: profiled
  tags: *id022
  url: /providers/octopart/
- agent_band: human-only
  agent_readiness: 1.1
  band: minimal
  in_catalog: true
  kin_score: 0.4
  mcp: *id023
  name: OEMsecrets
  slug: oemsecrets
  status: profiled
  tags: *id024
  url: /providers/oemsecrets/
- agent_band: agent-aware
  agent_readiness: 24.4
  band: thin
  in_catalog: true
  kin_score: 37.7
  mcp: *id025
  name: Ollama
  slug: ollama
  status: profiled
  tags: *id026
  url: /providers/ollama/
- agent_band: agent-ready
  agent_readiness: 46.4
  band: strong
  in_catalog: true
  kin_score: 54.8
  mcp: *id027
  name: OpenRouter
  slug: openrouter
  status: profiled
  tags: *id028
  url: /providers/openrouter/
- agent_band: human-only
  agent_readiness: 2.5
  band: emerging
  in_catalog: true
  kin_score: 13.8
  mcp: *id029
  name: Pollin Electronic
  slug: pollin
  status: profiled
  tags: *id030
  url: /providers/pollin/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 7.9
  mcp: *id031
  name: Pololu
  slug: pololu
  status: profiled
  tags: *id032
  url: /providers/pololu/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 2.2
  mcp: *id033
  name: Reichelt Elektronik
  slug: reichelt
  status: profiled
  tags: *id034
  url: /providers/reichelt/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 14.6
  mcp: *id035
  name: SparkFun Electronics
  slug: sparkfun
  status: profiled
  tags: *id036
  url: /providers/sparkfun/
- agent_band: agent-aware
  agent_readiness: 21.7
  band: emerging
  in_catalog: true
  kin_score: 17.0
  mcp: *id037
  name: TME (Transfer Multisort Elektronik)
  slug: tme
  status: profiled
  tags: *id038
  url: /providers/tme/
- agent_band: agent-aware
  agent_readiness: 14.1
  band: minimal
  in_catalog: true
  kin_score: 3.7
  mcp: *id039
  name: TrustedParts
  slug: trustedparts
  status: profiled
  tags: *id040
  url: /providers/trustedparts/
siblings:
- name: Cin7
  rows: 15
  url: /applications/inventory-warehouse/cin7/
- name: inFlow Inventory
  rows: 24
  url: /applications/inventory-warehouse/inflow-inventory/
- name: InvenTree
  rows: 8
  url: /applications/inventory-warehouse/inventree/
- name: Shelf
  rows: 5
  url: /applications/inventory-warehouse/shelf/
- name: Snipe-IT
  rows: 5
  url: /applications/inventory-warehouse/snipe-it/
- name: Sortly
  rows: 3
  url: /applications/inventory-warehouse/sortly/
- name: Zoho Inventory
  rows: 0
  url: /applications/inventory-warehouse/zoho-inventory/
sitemap: true
title: 'Part-DB: Inventory & Warehouse Management reference app'
---
