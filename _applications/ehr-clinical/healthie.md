---
app: Healthie
app_slug: healthie
app_url: https://www.gethealthie.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-2830.40
  key: clinical-decision-support
  layer: domain
  name: Clinical Decision Support
  providers:
  - Alvee Health
  url: /capabilities/clinical-decision-support/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.110
  key: AE-150.110
  layer: domain
  name: Cloud Fax
  providers:
  - etherFAX
  - Sfax
  url: /capabilities/cloud-fax/
  via_parent: null
- attribution: Turbo EA
  id: BC-2900.60
  key: healthcare-interoperability-operations
  layer: domain
  name: Healthcare Interoperability Operations
  providers:
  - Metriport
  - Zus Health
  url: /capabilities/healthcare-interoperability-operations/
  via_parent: null
- attribution: Turbo EA
  id: BC-2870
  key: healthcare-revenue-cycle-management
  layer: domain
  name: Healthcare Revenue Cycle Management
  providers:
  - Candid Health
  - Claim.MD
  - Claim.Revolution
  url: /capabilities/healthcare-revenue-cycle-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-2860.10
  key: laboratory-services-management
  layer: domain
  name: Laboratory Services Management
  providers:
  - Labcorp
  - Quest Diagnostics
  url: /capabilities/laboratory-services-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-130.30
  key: nutrition-food-data
  layer: domain
  name: Nutrition & Food Data
  providers:
  - Sifter Solutions
  url: /capabilities/nutrition-food-data/
  via_parent: null
- attribution: Turbo EA
  id: BC-2910.10
  key: patient-engagement-communication
  layer: domain
  name: Patient Engagement & Communication
  providers:
  - OhMD
  - Tellescope
  url: /capabilities/patient-engagement-communication/
  via_parent: null
- attribution: Turbo EA
  id: BC-2850
  key: pharmacy-medication-management
  layer: domain
  name: Pharmacy & Medication Management
  providers:
  - DoseSpot
  - Fullscript
  url: /capabilities/pharmacy-medication-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-2900.60.40
  key: BC-2900.60.40
  layer: domain
  name: Provider Directory Maintenance
  providers:
  - Orderly Health
  url: /capabilities/healthcare-interoperability-operations/
  via_parent: Healthcare Interoperability Operations
- attribution: Turbo EA
  id: BC-2800.10
  key: scheduling-appointment-management
  layer: domain
  name: Scheduling & Appointment Management
  providers:
  - Zocdoc
  url: /capabilities/scheduling-appointment-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-130.20.10
  key: AE-130.20.10
  layer: domain
  name: Wearable Data Aggregation
  providers:
  - Apple Health
  - Fitbit
  - Google Fit
  - Oura
  url: /capabilities/wearable-health-data-sync/
  via_parent: Wearable & Health Data Sync
- attribution: API Evangelist extension
  id: AE-910
  key: AE-910
  layer: domain
  name: Workflow Automation & iPaaS
  providers:
  - Keragon
  - Morf Health
  url: /capabilities/process-automation-governance/
  via_parent: Process Automation Governance
category:
  id: ehr-clinical
  name: EHR & Clinical Practice
  url: /applications/ehr-clinical/
counts:
  declared: 23
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.gethealthie.com/
- route: integrations page
  url: https://www.gethealthie.com/healthie-harbor
integrations:
- capability:
    attribution: Turbo EA
    id: BC-2830.40
    key: clinical-decision-support
    name: Clinical Decision Support
    url: /capabilities/clinical-decision-support/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 9.1
    mcp: &id001
      status: unknown
    slug: alvee
    status: profiled
    tags: &id002
    - Company
    - Healthcare
    - SDOH
    - Social Determinants of Health
    url: /providers/alvee/
  layer: domain
  name: Alvee Health
  provider: alvee
  says: lists Alvee Health as an integration
  source: https://www.gethealthie.com/healthie-harbor
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-130.20.10
    key: AE-130.20.10
    name: Wearable Data Aggregation
    url: /capabilities/wearable-health-data-sync/
    via_parent: Wearable & Health Data Sync
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 36.5
    band: developing
    in_catalog: true
    kin_score: 52.9
    mcp: &id003
      status: none
    slug: apple
    status: profiled
    tags: &id004
    - Apple
    - Developers
    - iOS
    - macOS
    url: /providers/apple/
  layer: domain
  name: Apple Health
  provider: apple
  says: lists Apple Health as an integration
  source: https://www.gethealthie.com/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2870
    key: healthcare-revenue-cycle-management
    name: Healthcare Revenue Cycle Management
    url: /capabilities/healthcare-revenue-cycle-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 36.6
    band: exemplar
    in_catalog: true
    kin_score: 68.0
    mcp: &id005
      status: none
    slug: candid-health
    status: profiled
    tags: &id006
    - Claims
    - Healthcare
    - Medical Billing
    - Revenue Cycle Management
    url: /providers/candid-health/
  layer: domain
  name: Candid Health
  provider: candid-health
  says: lists Candid Health as an integration
  source: https://www.gethealthie.com/healthie-harbor
  tier: declared
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
    agent_readiness: 19.2
    band: emerging
    in_catalog: true
    kin_score: 25.5
    mcp: &id007
      status: unknown
    slug: claim-md
    status: profiled
    tags: &id008
    - Clearinghouse
    - EDI
    - Healthcare
    - Medical Claims
    url: /providers/claim-md/
  layer: domain
  name: Claim.MD
  provider: claim-md
  says: lists Claim.MD as an integration
  source: https://www.gethealthie.com/healthie-harbor
  tier: declared
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
    agent_readiness: 14.5
    band: developing
    in_catalog: true
    kin_score: 41.4
    mcp: &id009
      status: none
    slug: claimrev
    status: profiled
    tags: &id010
    - Billing
    - Claims
    - Company
    - Healthcare
    url: /providers/claimrev/
  layer: domain
  name: Claim.Revolution
  provider: claimrev
  says: lists Claim.Revolution as an integration
  source: https://www.gethealthie.com/healthie-harbor
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
    agent_band: agent-ready
    agent_readiness: 30.1
    band: strong
    in_catalog: true
    kin_score: 59.1
    mcp: &id011
      status: none
    slug: dosespot
    status: profiled
    tags: &id012
    - Electronic Health Records
    - Healthcare
    - e-Prescribing
    - eRx
    url: /providers/dosespot/
  layer: domain
  name: DoseSpot
  provider: dosespot
  says: lists DoseSpot as an integration
  source: https://www.gethealthie.com/healthie-harbor
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
    agent_readiness: 38.6
    band: developing
    in_catalog: true
    kin_score: 48.2
    mcp: &id013
      status: none
    slug: etherfax
    status: profiled
    tags: &id014
    - Artificial Intelligence
    - Cloud
    - Fax
    - Secure
    url: /providers/etherfax/
  layer: domain
  name: etherFAX
  provider: etherfax
  says: lists etherFAX as an integration
  source: https://www.gethealthie.com/healthie-harbor
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-130.20.10
    key: AE-130.20.10
    name: Wearable Data Aggregation
    url: /capabilities/wearable-health-data-sync/
    via_parent: Wearable & Health Data Sync
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 30.7
    band: strong
    in_catalog: true
    kin_score: 61.5
    mcp: &id015
      status: none
    slug: fitbit
    status: profiled
    tags: &id016
    - Activity Tracking
    - Fitness
    - Health
    - Wearables
    url: /providers/fitbit/
  layer: domain
  name: Fitbit
  provider: fitbit
  says: lists Fitbit as an integration
  source: https://www.gethealthie.com/
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
    agent_band: agent-aware
    agent_readiness: 10.6
    band: emerging
    in_catalog: true
    kin_score: 25.4
    mcp: &id017
      status: unchecked
    slug: fullscript
    status: profiled
    tags: &id018
    - Healthcare
    - Lab Testing
    - Patient Care
    - Supplements
    url: /providers/fullscript/
  layer: domain
  name: Fullscript
  provider: fullscript
  says: lists Fullscript as an integration
  source: https://www.gethealthie.com/healthie-harbor
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-130.20.10
    key: AE-130.20.10
    name: Wearable Data Aggregation
    url: /capabilities/wearable-health-data-sync/
    via_parent: Wearable & Health Data Sync
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.1
    band: developing
    in_catalog: true
    kin_score: 51.4
    mcp: &id019
      status: none
    slug: google-fitness
    status: profiled
    tags: &id020
    - Activity Tracking
    - Fitness
    - Google
    - Health
    url: /providers/google-fitness/
  layer: domain
  name: Google Fit
  provider: google-fitness
  says: lists Google Fit as an integration
  source: https://www.gethealthie.com/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-910
    key: AE-910
    name: Workflow Automation & iPaaS
    url: /capabilities/process-automation-governance/
    via_parent: Process Automation Governance
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 20.4
    band: developing
    in_catalog: true
    kin_score: 43.0
    mcp: &id021
      status: unchecked
    slug: keragon
    status: profiled
    tags: &id022
    - Artificial Intelligence
    - Automation
    - Healthcare
    - Integration
    url: /providers/keragon/
  layer: domain
  name: Keragon
  provider: keragon
  says: lists Keragon as an integration
  source: https://www.gethealthie.com/healthie-harbor
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2860.10
    key: laboratory-services-management
    name: Laboratory Services Management
    url: /capabilities/laboratory-services-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.6
    band: emerging
    in_catalog: true
    kin_score: 12.2
    mcp: &id023
      status: none
    slug: labcorp
    status: profiled
    tags: &id024
    - Diagnostics
    - FHIR
    - Fortune 500
    - Healthcare
    url: /providers/labcorp/
  layer: domain
  name: Labcorp
  provider: labcorp
  says: lists Labcorp as an integration
  source: https://www.gethealthie.com/healthie-harbor
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2900.60
    key: healthcare-interoperability-operations
    name: Healthcare Interoperability Operations
    url: /capabilities/healthcare-interoperability-operations/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 32.8
    band: strong
    in_catalog: true
    kin_score: 65.7
    mcp: &id025
      source: https://mcp.metriport.com/.well-known/oauth-protected-resource
      status: verified
    slug: metriport
    status: profiled
    tags: &id026
    - FHIR
    - Health Data
    - Healthcare
    - Medical Records
    url: /providers/metriport/
  layer: domain
  name: Metriport
  provider: metriport
  says: lists Metriport as an integration
  source: https://www.gethealthie.com/healthie-harbor
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-910
    key: AE-910
    name: Workflow Automation & iPaaS
    url: /capabilities/process-automation-governance/
    via_parent: Process Automation Governance
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 27.5
    band: developing
    in_catalog: true
    kin_score: 47.0
    mcp: &id027
      status: none
    slug: morf
    status: profiled
    tags: &id028
    - Automation
    - Company
    - Health IT
    - Healthcare
    url: /providers/morf/
  layer: domain
  name: Morf Health
  provider: morf
  says: lists Morf Health as an integration
  source: https://www.gethealthie.com/healthie-harbor
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2910.10
    key: patient-engagement-communication
    name: Patient Engagement & Communication
    url: /capabilities/patient-engagement-communication/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.7
    band: emerging
    in_catalog: true
    kin_score: 20.4
    mcp: &id029
      status: unchecked
    slug: ohmd
    status: profiled
    tags: &id030
    - Artificial Intelligence
    - HIPAA
    - Healthcare
    - Patient Communication
    url: /providers/ohmd/
  layer: domain
  name: OhMD
  provider: ohmd
  says: lists OhMD as an integration
  source: https://www.gethealthie.com/healthie-harbor
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2900.60.40
    key: BC-2900.60.40
    name: Provider Directory Maintenance
    url: /capabilities/healthcare-interoperability-operations/
    via_parent: Healthcare Interoperability Operations
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 27.0
    band: thin
    in_catalog: true
    kin_score: 38.6
    mcp: &id031
      status: none
    slug: orderly-health
    status: profiled
    tags: &id032
    - Company
    - Healthcare
    - Provider Data
    - Provider Directory
    url: /providers/orderly-health/
  layer: domain
  name: Orderly Health
  provider: orderly-health
  says: lists Orderly Health as an integration
  source: https://www.gethealthie.com/healthie-harbor
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-130.20.10
    key: AE-130.20.10
    name: Wearable Data Aggregation
    url: /capabilities/wearable-health-data-sync/
    via_parent: Wearable & Health Data Sync
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 27.5
    band: developing
    in_catalog: true
    kin_score: 50.4
    mcp: &id033
      status: none
    slug: oura-ring
    status: profiled
    tags: &id034
    - Activity
    - Biometrics
    - Cardiovascular
    - Fitness
    url: /providers/oura-ring/
  layer: domain
  name: Oura
  provider: oura-ring
  says: lists Oura as an integration
  source: https://www.gethealthie.com/healthie-harbor
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2860.10
    key: laboratory-services-management
    name: Laboratory Services Management
    url: /capabilities/laboratory-services-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.6
    band: minimal
    in_catalog: true
    kin_score: 5.9
    mcp: &id035
      status: none
    slug: quest-diagnostics
    status: profiled
    tags: &id036
    - Diagnostics
    - Fortune 500
    - Healthcare
    - Laboratory
    url: /providers/quest-diagnostics/
  layer: domain
  name: Quest Diagnostics
  provider: quest-diagnostics
  says: lists Quest Diagnostics as an integration
  source: https://www.gethealthie.com/healthie-harbor
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
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 0.4
    mcp: &id037
      status: unchecked
    slug: sfax
    status: profiled
    tags: &id038
    - Company
    url: /providers/sfax/
  layer: domain
  name: Sfax
  provider: sfax
  says: lists Sfax as an integration
  source: https://www.gethealthie.com/healthie-harbor
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-130.30
    key: nutrition-food-data
    name: Nutrition & Food Data
    url: /capabilities/nutrition-food-data/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: emerging
    in_catalog: true
    kin_score: 15.3
    mcp: &id039
      status: unchecked
    slug: sifter-solutions
    status: profiled
    tags: &id040
    - Company
    - Food
    - Healthcare
    - Nutrition
    url: /providers/sifter-solutions/
  layer: domain
  name: Sifter Solutions
  provider: sifter-solutions
  says: lists Sifter Solutions as an integration
  source: https://www.gethealthie.com/healthie-harbor
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2910.10
    key: patient-engagement-communication
    name: Patient Engagement & Communication
    url: /capabilities/patient-engagement-communication/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 12.7
    band: thin
    in_catalog: true
    kin_score: 26.7
    mcp: &id041
      status: unchecked
    slug: tellescope
    status: profiled
    tags: &id042
    - Digital Health
    - EHR Integration
    - Patient Intake
    - Telehealth
    url: /providers/tellescope/
  layer: domain
  name: Tellescope
  provider: tellescope
  says: lists Tellescope as an integration
  source: https://www.gethealthie.com/healthie-harbor
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2800.10
    key: scheduling-appointment-management
    name: Scheduling & Appointment Management
    url: /capabilities/scheduling-appointment-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 49.4
    band: strong
    in_catalog: true
    kin_score: 55.0
    mcp: &id043
      source: https://api-docs.zocdoc.com/guides
      status: documented
    slug: zocdoc
    status: profiled
    tags: &id044
    - Appointments
    - Booking
    - Healthcare
    - Providers
    url: /providers/zocdoc/
  layer: domain
  name: Zocdoc
  provider: zocdoc
  says: lists Zocdoc as an integration
  source: https://www.gethealthie.com/healthie-harbor
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2900.60
    key: healthcare-interoperability-operations
    name: Healthcare Interoperability Operations
    url: /capabilities/healthcare-interoperability-operations/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 30.4
    band: strong
    in_catalog: true
    kin_score: 57.2
    mcp: &id045
      status: none
    slug: zus
    status: profiled
    tags: &id046
    - FHIR
    - Health
    - Interoperability
    - Patient Data
    url: /providers/zus/
  layer: domain
  name: Zus Health
  provider: zus
  says: lists Zus Health as an integration
  source: https://www.gethealthie.com/healthie-harbor
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/ehr-clinical/healthie/
providers:
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 9.1
  mcp: *id001
  name: Alvee Health
  slug: alvee
  status: profiled
  tags: *id002
  url: /providers/alvee/
- agent_band: agent-ready
  agent_readiness: 36.5
  band: developing
  in_catalog: true
  kin_score: 52.9
  mcp: *id003
  name: Apple Health
  slug: apple
  status: profiled
  tags: *id004
  url: /providers/apple/
- agent_band: agent-ready
  agent_readiness: 36.6
  band: exemplar
  in_catalog: true
  kin_score: 68.0
  mcp: *id005
  name: Candid Health
  slug: candid-health
  status: profiled
  tags: *id006
  url: /providers/candid-health/
- agent_band: agent-aware
  agent_readiness: 19.2
  band: emerging
  in_catalog: true
  kin_score: 25.5
  mcp: *id007
  name: Claim.MD
  slug: claim-md
  status: profiled
  tags: *id008
  url: /providers/claim-md/
- agent_band: agent-aware
  agent_readiness: 14.5
  band: developing
  in_catalog: true
  kin_score: 41.4
  mcp: *id009
  name: Claim.Revolution
  slug: claimrev
  status: profiled
  tags: *id010
  url: /providers/claimrev/
- agent_band: agent-ready
  agent_readiness: 30.1
  band: strong
  in_catalog: true
  kin_score: 59.1
  mcp: *id011
  name: DoseSpot
  slug: dosespot
  status: profiled
  tags: *id012
  url: /providers/dosespot/
- agent_band: agent-ready
  agent_readiness: 38.6
  band: developing
  in_catalog: true
  kin_score: 48.2
  mcp: *id013
  name: etherFAX
  slug: etherfax
  status: profiled
  tags: *id014
  url: /providers/etherfax/
- agent_band: agent-ready
  agent_readiness: 30.7
  band: strong
  in_catalog: true
  kin_score: 61.5
  mcp: *id015
  name: Fitbit
  slug: fitbit
  status: profiled
  tags: *id016
  url: /providers/fitbit/
- agent_band: agent-aware
  agent_readiness: 10.6
  band: emerging
  in_catalog: true
  kin_score: 25.4
  mcp: *id017
  name: Fullscript
  slug: fullscript
  status: profiled
  tags: *id018
  url: /providers/fullscript/
- agent_band: agent-ready
  agent_readiness: 33.1
  band: developing
  in_catalog: true
  kin_score: 51.4
  mcp: *id019
  name: Google Fit
  slug: google-fitness
  status: profiled
  tags: *id020
  url: /providers/google-fitness/
- agent_band: agent-aware
  agent_readiness: 20.4
  band: developing
  in_catalog: true
  kin_score: 43.0
  mcp: *id021
  name: Keragon
  slug: keragon
  status: profiled
  tags: *id022
  url: /providers/keragon/
- agent_band: human-only
  agent_readiness: 0.6
  band: emerging
  in_catalog: true
  kin_score: 12.2
  mcp: *id023
  name: Labcorp
  slug: labcorp
  status: profiled
  tags: *id024
  url: /providers/labcorp/
- agent_band: agent-ready
  agent_readiness: 32.8
  band: strong
  in_catalog: true
  kin_score: 65.7
  mcp: *id025
  name: Metriport
  slug: metriport
  status: profiled
  tags: *id026
  url: /providers/metriport/
- agent_band: agent-aware
  agent_readiness: 27.5
  band: developing
  in_catalog: true
  kin_score: 47.0
  mcp: *id027
  name: Morf Health
  slug: morf
  status: profiled
  tags: *id028
  url: /providers/morf/
- agent_band: human-only
  agent_readiness: 3.7
  band: emerging
  in_catalog: true
  kin_score: 20.4
  mcp: *id029
  name: OhMD
  slug: ohmd
  status: profiled
  tags: *id030
  url: /providers/ohmd/
- agent_band: agent-aware
  agent_readiness: 27.0
  band: thin
  in_catalog: true
  kin_score: 38.6
  mcp: *id031
  name: Orderly Health
  slug: orderly-health
  status: profiled
  tags: *id032
  url: /providers/orderly-health/
- agent_band: agent-aware
  agent_readiness: 27.5
  band: developing
  in_catalog: true
  kin_score: 50.4
  mcp: *id033
  name: Oura
  slug: oura-ring
  status: profiled
  tags: *id034
  url: /providers/oura-ring/
- agent_band: human-only
  agent_readiness: 0.6
  band: minimal
  in_catalog: true
  kin_score: 5.9
  mcp: *id035
  name: Quest Diagnostics
  slug: quest-diagnostics
  status: profiled
  tags: *id036
  url: /providers/quest-diagnostics/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 0.4
  mcp: *id037
  name: Sfax
  slug: sfax
  status: profiled
  tags: *id038
  url: /providers/sfax/
- agent_band: human-only
  agent_readiness: 3.0
  band: emerging
  in_catalog: true
  kin_score: 15.3
  mcp: *id039
  name: Sifter Solutions
  slug: sifter-solutions
  status: profiled
  tags: *id040
  url: /providers/sifter-solutions/
- agent_band: agent-aware
  agent_readiness: 12.7
  band: thin
  in_catalog: true
  kin_score: 26.7
  mcp: *id041
  name: Tellescope
  slug: tellescope
  status: profiled
  tags: *id042
  url: /providers/tellescope/
- agent_band: agent-ready
  agent_readiness: 49.4
  band: strong
  in_catalog: true
  kin_score: 55.0
  mcp: *id043
  name: Zocdoc
  slug: zocdoc
  status: profiled
  tags: *id044
  url: /providers/zocdoc/
- agent_band: agent-ready
  agent_readiness: 30.4
  band: strong
  in_catalog: true
  kin_score: 57.2
  mcp: *id045
  name: Zus Health
  slug: zus
  status: profiled
  tags: *id046
  url: /providers/zus/
siblings:
- name: Elation Health
  rows: 24
  url: /applications/ehr-clinical/elation-health/
- name: Medplum
  rows: 37
  url: /applications/ehr-clinical/medplum/
- name: OpenEMR
  rows: 13
  url: /applications/ehr-clinical/openemr/
- name: OpenMRS (O3 Reference Application)
  rows: 2
  url: /applications/ehr-clinical/openmrs-o3-reference-application/
- name: Tebra (Kareo + PatientPop)
  rows: 7
  url: /applications/ehr-clinical/tebra-kareo-patientpop/
sitemap: true
title: 'Healthie: EHR & Clinical Practice reference app'
---
