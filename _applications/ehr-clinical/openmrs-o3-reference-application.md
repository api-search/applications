---
app: OpenMRS (O3 Reference Application)
app_slug: openmrs-o3-reference-application
app_url: https://github.com/openmrs/openmrs-distro-referenceapplication
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-945
  key: AE-945
  layer: domain
  name: Clinical & Drug Terminology Services
  providers:
  - Open Concept Lab (OCL)
  url: /capabilities/medical-coding-management/
  via_parent: Medical Coding Management
- attribution: Turbo EA
  id: BC-2800.10
  key: scheduling-appointment-management
  layer: domain
  name: Scheduling & Appointment Management
  providers:
  - Bahmni
  url: /capabilities/scheduling-appointment-management/
  via_parent: null
category:
  id: ehr-clinical
  name: EHR & Clinical Practice
  url: /applications/ehr-clinical/
counts:
  declared: 0
  observed: 2
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/openmrs/openmrs-distro-referenceapplication/main/distro/distro.properties
- route: dependency manifest
  url: https://raw.githubusercontent.com/openmrs/openmrs-distro-referenceapplication/main/frontend/spa-assemble-config.json
- route: source code
  url: https://github.com/openmrs/openmrs-module-openconceptlab
- route: source code
  url: https://raw.githubusercontent.com/Bahmni/openmrs-module-teleconsultation/master/README.md
integrations:
- capability:
    attribution: Turbo EA
    id: BC-2800.10
    key: scheduling-appointment-management
    name: Scheduling & Appointment Management
    url: /capabilities/scheduling-appointment-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: minimal
    in_catalog: true
    kin_score: 6.7
    mcp: &id001
      status: unchecked
    slug: bahmni
    status: profiled
    tags: &id002
    - Electronic Health Records
    - Healthcare
    - Hospital Information System
    - Open Source
    url: /providers/bahmni/
  layer: domain
  name: Bahmni
  provider: bahmni
  says: ships the Bahmni SDK or integration code
  source: https://raw.githubusercontent.com/openmrs/openmrs-distro-referenceapplication/main/distro/distro.properties
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-945
    key: AE-945
    name: Clinical & Drug Terminology Services
    url: /capabilities/medical-coding-management/
    via_parent: Medical Coding Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 20.5
    band: developing
    in_catalog: true
    kin_score: 44.2
    mcp: &id003
      status: unchecked
    slug: openconceptlab
    status: profiled
    tags: &id004
    - Company
    - Health
    - Open Source
    - Terminology
    url: /providers/openconceptlab/
  layer: domain
  name: Open Concept Lab (OCL)
  provider: openconceptlab
  says: ships the Open Concept Lab (OCL) SDK or integration code
  source: https://raw.githubusercontent.com/openmrs/openmrs-distro-referenceapplication/main/distro/distro.properties
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/ehr-clinical/openmrs-o3-reference-application/
providers:
- agent_band: human-only
  agent_readiness: 3.0
  band: minimal
  in_catalog: true
  kin_score: 6.7
  mcp: *id001
  name: Bahmni
  slug: bahmni
  status: profiled
  tags: *id002
  url: /providers/bahmni/
- agent_band: agent-aware
  agent_readiness: 20.5
  band: developing
  in_catalog: true
  kin_score: 44.2
  mcp: *id003
  name: Open Concept Lab (OCL)
  slug: openconceptlab
  status: profiled
  tags: *id004
  url: /providers/openconceptlab/
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
- name: Tebra (Kareo + PatientPop)
  rows: 7
  url: /applications/ehr-clinical/tebra-kareo-patientpop/
sitemap: true
title: 'OpenMRS (O3 Reference Application): EHR & Clinical Practice reference app'
---
