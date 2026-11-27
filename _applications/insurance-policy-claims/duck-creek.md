---
app: Duck Creek
app_slug: duck-creek
app_url: https://www.duckcreek.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-2160
  key: insurance-claims-management
  layer: domain
  name: Insurance Claims Management
  providers:
  - CCC Intelligent Solutions
  - CLARA Analytics
  url: /capabilities/insurance-claims-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-2100
  key: insurance-product-management
  layer: domain
  name: Insurance Product Management
  providers:
  - AAIS
  url: /capabilities/insurance-product-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-2190
  key: insurance-risk-management
  layer: domain
  name: Insurance Risk Management
  providers:
  - Advisen
  url: /capabilities/insurance-risk-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-2100.20
  key: product-rating-pricing-configuration
  layer: domain
  name: Product Rating & Pricing Configuration
  providers:
  - Akur8
  url: /capabilities/product-rating-pricing-configuration/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-230.60
  key: property-data
  layer: domain
  name: Property Data
  providers:
  - CAPE Analytics
  url: /capabilities/property-data/
  via_parent: null
- attribution: Turbo EA
  id: BC-2130.10
  key: underwriting-risk-intake
  layer: domain
  name: Underwriting Risk Intake
  providers:
  - BitSight
  - Carpe Data
  url: /capabilities/underwriting-risk-intake/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-960
  key: AE-960
  layer: domain
  name: Usage-Based Insurance Telematics Data
  providers:
  - Arity
  - Cambridge Mobile Telematics
  url: /capabilities/usage-based-insurance-telematics-data/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-949
  key: AE-949
  layer: domain
  name: Vehicle History Reports
  providers:
  - CARFAX
  url: /capabilities/vehicle-history-reports/
  via_parent: null
category:
  id: insurance-policy-claims
  name: Insurance Policy & Claims
  url: /applications/insurance-policy-claims/
counts:
  declared: 11
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.duckcreek.com/partners/
integrations:
- capability:
    attribution: Turbo EA
    id: BC-2100
    key: insurance-product-management
    name: Insurance Product Management
    url: /capabilities/insurance-product-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: minimal
    in_catalog: true
    kin_score: 7.3
    mcp: &id001
      status: unchecked
    slug: aais
    status: profiled
    tags: &id002
    - Advisory Services
    - Data Technology
    - Insurance
    - Not-for-profit
    url: /providers/aais/
  layer: domain
  name: AAIS
  provider: aais
  says: lists AAIS as an integration
  source: https://www.duckcreek.com/partners/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2190
    key: insurance-risk-management
    name: Insurance Risk Management
    url: /capabilities/insurance-risk-management/
    via_parent: null
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id003
      status: unchecked
    slug: advisen
    status: queued for profiling
    tags: &id004 []
    url: null
  layer: domain
  name: Advisen
  provider: advisen
  says: lists Advisen as an integration
  source: https://www.duckcreek.com/partners/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2100.20
    key: product-rating-pricing-configuration
    name: Product Rating & Pricing Configuration
    url: /capabilities/product-rating-pricing-configuration/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 9.2
    mcp: &id005
      status: unknown
    slug: akur8
    status: profiled
    tags: &id006
    - Actuarial
    - Insurance
    - Insurtech
    - Pricing
    url: /providers/akur8/
  layer: domain
  name: Akur8
  provider: akur8
  says: lists Akur8 as an integration
  source: https://www.duckcreek.com/partners/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-960
    key: AE-960
    name: Usage-Based Insurance Telematics Data
    url: /capabilities/usage-based-insurance-telematics-data/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 22.8
    band: developing
    in_catalog: true
    kin_score: 41.6
    mcp: &id007
      status: unknown
    slug: arity
    status: profiled
    tags: &id008
    - Company
    - Insurance
    - Mobility Data
    - Telematics
    url: /providers/arity/
  layer: domain
  name: Arity
  provider: arity
  says: lists Arity as an integration
  source: https://www.duckcreek.com/partners/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2130.10
    key: underwriting-risk-intake
    name: Underwriting Risk Intake
    url: /capabilities/underwriting-risk-intake/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 14.4
    band: thin
    in_catalog: true
    kin_score: 34.4
    mcp: &id009
      status: unknown
    slug: bitsight
    status: profiled
    tags: &id010
    - Company
    - Cyber Risk
    - Security
    - Security Ratings
    url: /providers/bitsight/
  layer: domain
  name: BitSight
  provider: bitsight
  says: lists BitSight as an integration
  source: https://www.duckcreek.com/partners/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-960
    key: AE-960
    name: Usage-Based Insurance Telematics Data
    url: /capabilities/usage-based-insurance-telematics-data/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 21.6
    mcp: &id011
      status: none
    slug: cambridge-mobile-telematics
    status: profiled
    tags: &id012
    - Company
    - Enterprise
    - Insurance
    - Telematics
    url: /providers/cambridge-mobile-telematics/
  layer: domain
  name: Cambridge Mobile Telematics
  provider: cambridge-mobile-telematics
  says: lists Cambridge Mobile Telematics as an integration
  source: https://www.duckcreek.com/partners/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-230.60
    key: property-data
    name: Property Data
    url: /capabilities/property-data/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 16.8
    mcp: &id013
      status: unknown
    slug: cape-analytics
    status: profiled
    tags: &id014
    - Company
    - Computer Vision
    - Geospatial
    - Property Intelligence
    url: /providers/cape-analytics/
  layer: domain
  name: CAPE Analytics
  provider: cape-analytics
  says: lists CAPE Analytics as an integration
  source: https://www.duckcreek.com/partners/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-949
    key: AE-949
    name: Vehicle History Reports
    url: /capabilities/vehicle-history-reports/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 13.3
    band: emerging
    in_catalog: true
    kin_score: 18.2
    mcp: &id015
      status: none
    slug: carfax
    status: profiled
    tags: &id016
    - Automotive
    - Used Cars
    - VIN Lookup
    - Vehicle History
    url: /providers/carfax/
  layer: domain
  name: CARFAX
  provider: carfax
  says: lists CARFAX as an integration
  source: https://www.duckcreek.com/partners/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2130.10
    key: underwriting-risk-intake
    name: Underwriting Risk Intake
    url: /capabilities/underwriting-risk-intake/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: minimal
    in_catalog: true
    kin_score: 8.6
    mcp: &id017
      status: unchecked
    slug: carpe-data
    status: profiled
    tags: &id018
    - Artificial Intelligence
    - Claims
    - Data
    - Insurance
    url: /providers/carpe-data/
  layer: domain
  name: Carpe Data
  provider: carpe-data
  says: lists Carpe Data as an integration
  source: https://www.duckcreek.com/partners/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2160
    key: insurance-claims-management
    name: Insurance Claims Management
    url: /capabilities/insurance-claims-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 18.2
    band: thin
    in_catalog: true
    kin_score: 33.3
    mcp: &id019
      status: unknown
    slug: ccc-intelligent-solutions
    status: profiled
    tags: &id020
    - Claims
    - Insurance
    - Property and Casualty
    - United States
    url: /providers/ccc-intelligent-solutions/
  layer: domain
  name: CCC Intelligent Solutions
  provider: ccc-intelligent-solutions
  says: lists CCC Intelligent Solutions as an integration
  source: https://www.duckcreek.com/partners/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2160
    key: insurance-claims-management
    name: Insurance Claims Management
    url: /capabilities/insurance-claims-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 17.1
    mcp: &id021
      status: unknown
    slug: clara-analytics
    status: profiled
    tags: &id022
    - Claims
    - Company
    - Insurance
    - Insurtech
    url: /providers/clara-analytics/
  layer: domain
  name: CLARA Analytics
  provider: clara-analytics
  says: lists CLARA Analytics as an integration
  source: https://www.duckcreek.com/partners/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/insurance-policy-claims/duck-creek/
providers:
- agent_band: human-only
  agent_readiness: 3.0
  band: minimal
  in_catalog: true
  kin_score: 7.3
  mcp: *id001
  name: AAIS
  slug: aais
  status: profiled
  tags: *id002
  url: /providers/aais/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id003
  name: Advisen
  slug: advisen
  status: queued for profiling
  tags: *id004
  url: null
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 9.2
  mcp: *id005
  name: Akur8
  slug: akur8
  status: profiled
  tags: *id006
  url: /providers/akur8/
- agent_band: agent-aware
  agent_readiness: 22.8
  band: developing
  in_catalog: true
  kin_score: 41.6
  mcp: *id007
  name: Arity
  slug: arity
  status: profiled
  tags: *id008
  url: /providers/arity/
- agent_band: agent-aware
  agent_readiness: 14.4
  band: thin
  in_catalog: true
  kin_score: 34.4
  mcp: *id009
  name: BitSight
  slug: bitsight
  status: profiled
  tags: *id010
  url: /providers/bitsight/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 21.6
  mcp: *id011
  name: Cambridge Mobile Telematics
  slug: cambridge-mobile-telematics
  status: profiled
  tags: *id012
  url: /providers/cambridge-mobile-telematics/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 16.8
  mcp: *id013
  name: CAPE Analytics
  slug: cape-analytics
  status: profiled
  tags: *id014
  url: /providers/cape-analytics/
- agent_band: agent-aware
  agent_readiness: 13.3
  band: emerging
  in_catalog: true
  kin_score: 18.2
  mcp: *id015
  name: CARFAX
  slug: carfax
  status: profiled
  tags: *id016
  url: /providers/carfax/
- agent_band: human-only
  agent_readiness: 3.0
  band: minimal
  in_catalog: true
  kin_score: 8.6
  mcp: *id017
  name: Carpe Data
  slug: carpe-data
  status: profiled
  tags: *id018
  url: /providers/carpe-data/
- agent_band: agent-aware
  agent_readiness: 18.2
  band: thin
  in_catalog: true
  kin_score: 33.3
  mcp: *id019
  name: CCC Intelligent Solutions
  slug: ccc-intelligent-solutions
  status: profiled
  tags: *id020
  url: /providers/ccc-intelligent-solutions/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 17.1
  mcp: *id021
  name: CLARA Analytics
  slug: clara-analytics
  status: profiled
  tags: *id022
  url: /providers/clara-analytics/
siblings:
- name: EZLynx
  rows: 13
  url: /applications/insurance-policy-claims/ezlynx/
- name: HawkSoft
  rows: 12
  url: /applications/insurance-policy-claims/hawksoft/
- name: Lemonade
  rows: 0
  url: /applications/insurance-policy-claims/lemonade/
- name: openIMIS
  rows: 6
  url: /applications/insurance-policy-claims/openimis/
- name: Socotra
  rows: 12
  url: /applications/insurance-policy-claims/socotra/
sitemap: true
title: 'Duck Creek: Insurance Policy & Claims reference app'
---
