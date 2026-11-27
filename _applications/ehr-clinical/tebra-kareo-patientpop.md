---
app: Tebra (Kareo + PatientPop)
app_slug: tebra-kareo-patientpop
app_url: https://www.tebra.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-2810.60
  key: behavioural-health-care-delivery
  layer: domain
  name: Behavioural Health Care Delivery
  providers:
  - Rethink Behavioral Health
  url: /capabilities/behavioural-health-care-delivery/
  via_parent: null
- attribution: Turbo EA
  id: BC-2830
  key: clinical-documentation-management
  layer: domain
  name: Clinical Documentation Management
  providers:
  - FlexScanMD
  - WoundZoom
  url: /capabilities/clinical-documentation-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.110
  key: AE-150.110
  layer: domain
  name: Cloud Fax
  providers:
  - Medsender
  url: /capabilities/cloud-fax/
  via_parent: null
- attribution: Turbo EA
  id: BC-2870
  key: healthcare-revenue-cycle-management
  layer: domain
  name: Healthcare Revenue Cycle Management
  providers:
  - Advantum Health
  url: /capabilities/healthcare-revenue-cycle-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-2850
  key: pharmacy-medication-management
  layer: domain
  name: Pharmacy & Medication Management
  providers:
  - GoodRx
  url: /capabilities/pharmacy-medication-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-2810.80.40
  key: BC-2810.80.40
  layer: domain
  name: Remote Monitoring Care
  providers:
  - Optimize Health
  url: /capabilities/home-community-care-delivery/
  via_parent: Home & Community Care Delivery
category:
  id: ehr-clinical
  name: EHR & Clinical Practice
  url: /applications/ehr-clinical/
counts:
  declared: 7
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.tebra.com/partner-marketplace
integrations:
- capability:
    attribution: Turbo EA
    id: BC-2870
    key: healthcare-revenue-cycle-management
    name: Healthcare Revenue Cycle Management
    url: /capabilities/healthcare-revenue-cycle-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 18.3
    band: emerging
    in_catalog: true
    kin_score: 12.7
    mcp: &id001
      status: unchecked
    slug: advantum-health
    status: profiled
    tags: &id002
    - Artificial Intelligence
    - Billing
    - Healthcare
    - Revenue Cycle Management
    url: /providers/advantum-health/
  layer: domain
  name: Advantum Health
  provider: advantum-health
  says: lists Advantum Health as an integration
  source: https://www.tebra.com/partner-marketplace
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2830
    key: clinical-documentation-management
    name: Clinical Documentation Management
    url: /capabilities/clinical-documentation-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 7.4
    band: emerging
    in_catalog: true
    kin_score: 16.7
    mcp: &id003
      status: unchecked
    slug: flexscanmd
    status: profiled
    tags: &id004
    - Cloud‑based
    - Compliance
    - Inventory
    - Medical Software
    url: /providers/flexscanmd/
  layer: domain
  name: FlexScanMD
  provider: flexscanmd
  says: lists FlexScanMD as an integration
  source: https://www.tebra.com/partner-marketplace
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2850
    key: pharmacy-medication-management
    name: Pharmacy & Medication Management
    url: /capabilities/pharmacy-medication-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 3.4
    mcp: &id005
      status: unchecked
    slug: goodrx
    status: profiled
    tags: &id006
    - Company
    url: /providers/goodrx/
  layer: domain
  name: GoodRx
  provider: goodrx
  says: lists GoodRx as an integration
  source: https://www.tebra.com/partner-marketplace
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.110
    key: AE-150.110
    name: Cloud Fax
    url: /capabilities/cloud-fax/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 44.0
    band: strong
    in_catalog: true
    kin_score: 55.0
    mcp: &id007
      status: unchecked
    slug: medsender
    status: profiled
    tags: &id008
    - Call Automation
    - Fax Automation
    - Patient Recapture
    - Referral Management
    url: /providers/medsender/
  layer: domain
  name: Medsender
  provider: medsender
  says: lists Medsender as an integration
  source: https://www.tebra.com/partner-marketplace
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2810.80.40
    key: BC-2810.80.40
    name: Remote Monitoring Care
    url: /capabilities/home-community-care-delivery/
    via_parent: Home & Community Care Delivery
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id009
      status: unchecked
    slug: optimize-health
    status: queued for profiling
    tags: &id010 []
    url: null
  layer: domain
  name: Optimize Health
  provider: optimize-health
  says: lists Optimize Health as an integration
  source: https://www.tebra.com/partner-marketplace
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2810.60
    key: behavioural-health-care-delivery
    name: Behavioural Health Care Delivery
    url: /capabilities/behavioural-health-care-delivery/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 40.5
    band: thin
    in_catalog: true
    kin_score: 31.2
    mcp: &id011
      status: unchecked
    slug: rethink-behavioral-health
    status: profiled
    tags: &id012
    - ABA
    - Healthcare
    - Practice Management
    - Software
    url: /providers/rethink-behavioral-health/
  layer: domain
  name: Rethink Behavioral Health
  provider: rethink-behavioral-health
  says: lists Rethink Behavioral Health as an integration
  source: https://www.tebra.com/partner-marketplace
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2830
    key: clinical-documentation-management
    name: Clinical Documentation Management
    url: /capabilities/clinical-documentation-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: emerging
    in_catalog: true
    kin_score: 12.0
    mcp: &id013
      status: unchecked
    slug: woundzoom
    status: profiled
    tags: &id014
    - Healthcare Software
    - Hospitals
    - Long-Term Care
    - Wound Care
    url: /providers/woundzoom/
  layer: domain
  name: WoundZoom
  provider: woundzoom
  says: lists WoundZoom as an integration
  source: https://www.tebra.com/partner-marketplace
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/ehr-clinical/tebra-kareo-patientpop/
providers:
- agent_band: agent-aware
  agent_readiness: 18.3
  band: emerging
  in_catalog: true
  kin_score: 12.7
  mcp: *id001
  name: Advantum Health
  slug: advantum-health
  status: profiled
  tags: *id002
  url: /providers/advantum-health/
- agent_band: agent-aware
  agent_readiness: 7.4
  band: emerging
  in_catalog: true
  kin_score: 16.7
  mcp: *id003
  name: FlexScanMD
  slug: flexscanmd
  status: profiled
  tags: *id004
  url: /providers/flexscanmd/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 3.4
  mcp: *id005
  name: GoodRx
  slug: goodrx
  status: profiled
  tags: *id006
  url: /providers/goodrx/
- agent_band: agent-ready
  agent_readiness: 44.0
  band: strong
  in_catalog: true
  kin_score: 55.0
  mcp: *id007
  name: Medsender
  slug: medsender
  status: profiled
  tags: *id008
  url: /providers/medsender/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id009
  name: Optimize Health
  slug: optimize-health
  status: queued for profiling
  tags: *id010
  url: null
- agent_band: agent-ready
  agent_readiness: 40.5
  band: thin
  in_catalog: true
  kin_score: 31.2
  mcp: *id011
  name: Rethink Behavioral Health
  slug: rethink-behavioral-health
  status: profiled
  tags: *id012
  url: /providers/rethink-behavioral-health/
- agent_band: human-only
  agent_readiness: 3.0
  band: emerging
  in_catalog: true
  kin_score: 12.0
  mcp: *id013
  name: WoundZoom
  slug: woundzoom
  status: profiled
  tags: *id014
  url: /providers/woundzoom/
siblings:
- name: Elation Health
  rows: 24
  url: /applications/ehr-clinical/elation-health/
- name: Healthie
  rows: 23
  url: /applications/ehr-clinical/healthie/
- name: Medplum
  rows: 37
  url: /applications/ehr-clinical/medplum/
- name: OpenEMR
  rows: 13
  url: /applications/ehr-clinical/openemr/
- name: OpenMRS (O3 Reference Application)
  rows: 2
  url: /applications/ehr-clinical/openmrs-o3-reference-application/
sitemap: true
title: 'Tebra (Kareo + PatientPop): EHR & Clinical Practice reference app'
---
