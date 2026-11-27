---
app: Elation Health
app_slug: elation-health
app_url: https://www.elationhealth.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-2820
  key: care-coordination-management
  layer: domain
  name: Care Coordination Management
  providers:
  - Awell
  - ThoroughCare
  url: /capabilities/care-coordination-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-2830
  key: clinical-documentation-management
  layer: domain
  name: Clinical Documentation Management
  providers:
  - FlexScanMD
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
  url: /capabilities/healthcare-revenue-cycle-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-2910.10
  key: patient-engagement-communication
  layer: domain
  name: Patient Engagement & Communication
  providers:
  - Updox
  - Weave
  url: /capabilities/patient-engagement-communication/
  via_parent: null
- attribution: Turbo EA
  id: BC-2800.20
  key: patient-registration-management
  layer: domain
  name: Patient Registration Management
  providers:
  - FormDr
  - IntakeQ
  - Yosi Health
  url: /capabilities/patient-registration-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-2850
  key: pharmacy-medication-management
  layer: domain
  name: Pharmacy & Medication Management
  providers:
  - Fullscript
  - VaxCare
  url: /capabilities/pharmacy-medication-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-2880
  key: population-health-management
  layer: domain
  name: Population Health Management
  providers:
  - Aledade
  - Cozeva
  url: /capabilities/population-health-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-2810.80.40
  key: BC-2810.80.40
  layer: domain
  name: Remote Monitoring Care
  providers:
  - Nsight Health
  - Prevounce
  url: /capabilities/home-community-care-delivery/
  via_parent: Home & Community Care Delivery
- attribution: API Evangelist extension
  id: AE-140.60
  key: AE-140.60
  layer: domain
  name: Reviews & Social Proof
  providers:
  - rater8
  url: /capabilities/reviews-social-proof/
  via_parent: null
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
  id: AE-150.50.30
  key: AE-150.50.30
  layer: domain
  name: Virtual Receptionists & Answering Services
  providers:
  - Talkie.ai
  url: /capabilities/voice-telephony/
  via_parent: Voice & Telephony
- attribution: API Evangelist extension
  id: AE-130.20.10
  key: AE-130.20.10
  layer: domain
  name: Wearable Data Aggregation
  providers:
  - Heads Up Health
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
  declared: 24
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://partners.elationhealth.com/
- route: integrations page
  url: https://www.elationhealth.com/integrations/
integrations:
- capability:
    attribution: Turbo EA
    id: BC-2880
    key: population-health-management
    name: Population Health Management
    url: /capabilities/population-health-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 1.7
    band: emerging
    in_catalog: true
    kin_score: 14.9
    mcp: &id001
      status: unknown
    slug: aledade
    status: profiled
    tags: &id002
    - Company
    - Healthcare
    - Life Sciences
    - Value-Based Care
    url: /providers/aledade/
  layer: domain
  name: Aledade
  provider: aledade
  says: lists Aledade as an integration
  source: https://partners.elationhealth.com/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2820
    key: care-coordination-management
    name: Care Coordination Management
    url: /capabilities/care-coordination-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 20.3
    band: developing
    in_catalog: true
    kin_score: 43.6
    mcp: &id003
      status: unchecked
    slug: awell
    status: profiled
    tags: &id004
    - Artificial Intelligence
    - CareOps
    - Healthcare
    - Platform
    url: /providers/awell/
  layer: domain
  name: Awell
  provider: awell
  says: lists Awell as an integration
  source: https://partners.elationhealth.com/
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
  source: https://partners.elationhealth.com/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2880
    key: population-health-management
    name: Population Health Management
    url: /capabilities/population-health-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 9.7
    mcp: &id007
      status: unchecked
    slug: cozeva
    status: profiled
    tags: &id008
    - Data Platform
    - Healthcare
    - Quality Measurement
    - Risk Adjustment
    url: /providers/cozeva/
  layer: domain
  name: Cozeva
  provider: cozeva
  says: lists Cozeva as an integration
  source: https://partners.elationhealth.com/
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
    mcp: &id009
      status: unchecked
    slug: flexscanmd
    status: profiled
    tags: &id010
    - Cloud‑based
    - Compliance
    - Inventory
    - Medical Software
    url: /providers/flexscanmd/
  layer: domain
  name: FlexScanMD
  provider: flexscanmd
  says: lists FlexScanMD as an integration
  source: https://partners.elationhealth.com/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2800.20
    key: patient-registration-management
    name: Patient Registration Management
    url: /capabilities/patient-registration-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 21.4
    band: thin
    in_catalog: true
    kin_score: 31.8
    mcp: &id011
      status: unchecked
    slug: formdr
    status: profiled
    tags: &id012
    - Forms
    - HIPAA
    - Healthcare
    - Patient Intake
    url: /providers/formdr/
  layer: domain
  name: FormDr
  provider: formdr
  says: lists FormDr as an integration
  source: https://partners.elationhealth.com/
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
    mcp: &id013
      status: unchecked
    slug: fullscript
    status: profiled
    tags: &id014
    - Healthcare
    - Lab Testing
    - Patient Care
    - Supplements
    url: /providers/fullscript/
  layer: domain
  name: Fullscript
  provider: fullscript
  says: lists Fullscript as an integration
  source: https://partners.elationhealth.com/
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
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 26.0
    mcp: &id015
      status: unchecked
    slug: heads-up-health
    status: profiled
    tags: &id016
    - Artificial Intelligence
    - Clinical Intelligence
    - Health
    - Wearables
    url: /providers/heads-up-health/
  layer: domain
  name: Heads Up Health
  provider: heads-up-health
  says: lists Heads Up Health as an integration
  source: https://partners.elationhealth.com/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2800.20
    key: patient-registration-management
    name: Patient Registration Management
    url: /capabilities/patient-registration-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 29.6
    band: thin
    in_catalog: true
    kin_score: 26.7
    mcp: &id017
      status: unknown
    slug: intakeq
    status: profiled
    tags: &id018
    - Health and Wellness
    - Intake Forms
    - Practice Management
    - Scheduling
    url: /providers/intakeq/
  layer: domain
  name: IntakeQ
  provider: intakeq
  says: lists IntakeQ as an integration
  source: https://partners.elationhealth.com/
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
    mcp: &id019
      status: unchecked
    slug: keragon
    status: profiled
    tags: &id020
    - Artificial Intelligence
    - Automation
    - Healthcare
    - Integration
    url: /providers/keragon/
  layer: domain
  name: Keragon
  provider: keragon
  says: lists Keragon as an integration
  source: https://partners.elationhealth.com/
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
    mcp: &id021
      status: unchecked
    slug: medsender
    status: profiled
    tags: &id022
    - Call Automation
    - Fax Automation
    - Patient Recapture
    - Referral Management
    url: /providers/medsender/
  layer: domain
  name: Medsender
  provider: medsender
  says: lists Medsender as an integration
  source: https://partners.elationhealth.com/
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
    mcp: &id023
      source: https://mcp.metriport.com/.well-known/oauth-protected-resource
      status: verified
    slug: metriport
    status: profiled
    tags: &id024
    - FHIR
    - Health Data
    - Healthcare
    - Medical Records
    url: /providers/metriport/
  layer: domain
  name: Metriport
  provider: metriport
  says: lists Metriport as an integration
  source: https://partners.elationhealth.com/
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
    mcp: &id025
      status: none
    slug: morf
    status: profiled
    tags: &id026
    - Automation
    - Company
    - Health IT
    - Healthcare
    url: /providers/morf/
  layer: domain
  name: Morf Health
  provider: morf
  says: lists Morf Health as an integration
  source: https://partners.elationhealth.com/
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
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 12.7
    mcp: &id027
      status: unchecked
    slug: nsight-health
    status: profiled
    tags: &id028
    - Artificial Intelligence
    - Chronic Care
    - Healthcare
    - Remote Monitoring
    url: /providers/nsight-health/
  layer: domain
  name: Nsight Health
  provider: nsight-health
  says: lists Nsight Health as an integration
  source: https://partners.elationhealth.com/
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
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 11.5
    mcp: &id029
      status: unchecked
    slug: prevounce
    status: profiled
    tags: &id030
    - Artificial Intelligence
    - Company
    - Healthcare
    - Remote Monitoring
    url: /providers/prevounce/
  layer: domain
  name: Prevounce
  provider: prevounce
  says: lists Prevounce as an integration
  source: https://partners.elationhealth.com/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.60
    key: AE-140.60
    name: Reviews & Social Proof
    url: /capabilities/reviews-social-proof/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 13.6
    band: minimal
    in_catalog: true
    kin_score: 4.4
    mcp: &id031
      status: unchecked
    slug: rater8
    status: profiled
    tags: &id032
    - Healthcare
    - Management
    - Reputation
    - Software-as-a-Service
    url: /providers/rater8/
  layer: domain
  name: rater8
  provider: rater8
  says: lists rater8 as an integration
  source: https://partners.elationhealth.com/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.50.30
    key: AE-150.50.30
    name: Virtual Receptionists & Answering Services
    url: /capabilities/voice-telephony/
    via_parent: Voice & Telephony
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 22.7
    band: developing
    in_catalog: true
    kin_score: 40.7
    mcp: &id033
      status: unchecked
    slug: talkie-ai
    status: profiled
    tags: &id034
    - Artificial Intelligence
    - Company
    - Healthcare
    - MedicalReceptionist
    url: /providers/talkie-ai/
  layer: domain
  name: Talkie.ai
  provider: talkie-ai
  says: lists Talkie.ai as an integration
  source: https://partners.elationhealth.com/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2820
    key: care-coordination-management
    name: Care Coordination Management
    url: /capabilities/care-coordination-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: minimal
    in_catalog: true
    kin_score: 0.4
    mcp: &id035
      status: unchecked
    slug: thoroughcare
    status: profiled
    tags: &id036
    - Company
    url: /providers/thoroughcare/
  layer: domain
  name: ThoroughCare
  provider: thoroughcare
  says: lists ThoroughCare as an integration
  source: https://partners.elationhealth.com/
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
    agent_readiness: 16.8
    band: emerging
    in_catalog: true
    kin_score: 23.8
    mcp: &id037
      status: unknown
    slug: updox
    status: profiled
    tags: &id038
    - Electronic Fax
    - Healthcare
    - Patient Engagement
    - Secure Messaging
    url: /providers/updox/
  layer: domain
  name: Updox
  provider: updox
  says: lists Updox as an integration
  source: https://partners.elationhealth.com/
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
    agent_readiness: 28.7
    band: thin
    in_catalog: true
    kin_score: 36.5
    mcp: &id039
      status: unchecked
    slug: vaxcare
    status: profiled
    tags: &id040
    - Contraceptives
    - Health Systems
    - Pediatrics
    - Vaccines
    url: /providers/vaxcare/
  layer: domain
  name: VaxCare
  provider: vaxcare
  says: lists VaxCare as an integration
  source: https://partners.elationhealth.com/
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
    agent_band: agent-ready
    agent_readiness: 31.6
    band: strong
    in_catalog: true
    kin_score: 58.1
    mcp: &id041
      status: none
    slug: weave
    status: profiled
    tags: &id042
    - Communications
    - Company
    - Messaging
    - Payments
    url: /providers/weave/
  layer: domain
  name: Weave
  provider: weave
  says: lists Weave as an integration
  source: https://partners.elationhealth.com/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2800.20
    key: patient-registration-management
    name: Patient Registration Management
    url: /capabilities/patient-registration-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: minimal
    in_catalog: true
    kin_score: 9.0
    mcp: &id043
      status: unchecked
    slug: yosi-health
    status: profiled
    tags: &id044
    - Healthcare
    - Patient Intake
    - Scheduling
    - Telehealth
    url: /providers/yosi-health/
  layer: domain
  name: Yosi Health
  provider: yosi-health
  says: lists Yosi Health as an integration
  source: https://partners.elationhealth.com/
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
    mcp: &id045
      source: https://api-docs.zocdoc.com/guides
      status: documented
    slug: zocdoc
    status: profiled
    tags: &id046
    - Appointments
    - Booking
    - Healthcare
    - Providers
    url: /providers/zocdoc/
  layer: domain
  name: Zocdoc
  provider: zocdoc
  says: lists Zocdoc as an integration
  source: https://partners.elationhealth.com/
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
    mcp: &id047
      status: none
    slug: zus
    status: profiled
    tags: &id048
    - FHIR
    - Health
    - Interoperability
    - Patient Data
    url: /providers/zus/
  layer: domain
  name: Zus Health
  provider: zus
  says: lists Zus Health as an integration
  source: https://partners.elationhealth.com/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/ehr-clinical/elation-health/
providers:
- agent_band: human-only
  agent_readiness: 1.7
  band: emerging
  in_catalog: true
  kin_score: 14.9
  mcp: *id001
  name: Aledade
  slug: aledade
  status: profiled
  tags: *id002
  url: /providers/aledade/
- agent_band: agent-aware
  agent_readiness: 20.3
  band: developing
  in_catalog: true
  kin_score: 43.6
  mcp: *id003
  name: Awell
  slug: awell
  status: profiled
  tags: *id004
  url: /providers/awell/
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
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 9.7
  mcp: *id007
  name: Cozeva
  slug: cozeva
  status: profiled
  tags: *id008
  url: /providers/cozeva/
- agent_band: agent-aware
  agent_readiness: 7.4
  band: emerging
  in_catalog: true
  kin_score: 16.7
  mcp: *id009
  name: FlexScanMD
  slug: flexscanmd
  status: profiled
  tags: *id010
  url: /providers/flexscanmd/
- agent_band: agent-aware
  agent_readiness: 21.4
  band: thin
  in_catalog: true
  kin_score: 31.8
  mcp: *id011
  name: FormDr
  slug: formdr
  status: profiled
  tags: *id012
  url: /providers/formdr/
- agent_band: agent-aware
  agent_readiness: 10.6
  band: emerging
  in_catalog: true
  kin_score: 25.4
  mcp: *id013
  name: Fullscript
  slug: fullscript
  status: profiled
  tags: *id014
  url: /providers/fullscript/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 26.0
  mcp: *id015
  name: Heads Up Health
  slug: heads-up-health
  status: profiled
  tags: *id016
  url: /providers/heads-up-health/
- agent_band: agent-ready
  agent_readiness: 29.6
  band: thin
  in_catalog: true
  kin_score: 26.7
  mcp: *id017
  name: IntakeQ
  slug: intakeq
  status: profiled
  tags: *id018
  url: /providers/intakeq/
- agent_band: agent-aware
  agent_readiness: 20.4
  band: developing
  in_catalog: true
  kin_score: 43.0
  mcp: *id019
  name: Keragon
  slug: keragon
  status: profiled
  tags: *id020
  url: /providers/keragon/
- agent_band: agent-ready
  agent_readiness: 44.0
  band: strong
  in_catalog: true
  kin_score: 55.0
  mcp: *id021
  name: Medsender
  slug: medsender
  status: profiled
  tags: *id022
  url: /providers/medsender/
- agent_band: agent-ready
  agent_readiness: 32.8
  band: strong
  in_catalog: true
  kin_score: 65.7
  mcp: *id023
  name: Metriport
  slug: metriport
  status: profiled
  tags: *id024
  url: /providers/metriport/
- agent_band: agent-aware
  agent_readiness: 27.5
  band: developing
  in_catalog: true
  kin_score: 47.0
  mcp: *id025
  name: Morf Health
  slug: morf
  status: profiled
  tags: *id026
  url: /providers/morf/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 12.7
  mcp: *id027
  name: Nsight Health
  slug: nsight-health
  status: profiled
  tags: *id028
  url: /providers/nsight-health/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 11.5
  mcp: *id029
  name: Prevounce
  slug: prevounce
  status: profiled
  tags: *id030
  url: /providers/prevounce/
- agent_band: agent-aware
  agent_readiness: 13.6
  band: minimal
  in_catalog: true
  kin_score: 4.4
  mcp: *id031
  name: rater8
  slug: rater8
  status: profiled
  tags: *id032
  url: /providers/rater8/
- agent_band: agent-aware
  agent_readiness: 22.7
  band: developing
  in_catalog: true
  kin_score: 40.7
  mcp: *id033
  name: Talkie.ai
  slug: talkie-ai
  status: profiled
  tags: *id034
  url: /providers/talkie-ai/
- agent_band: human-only
  agent_readiness: 3.0
  band: minimal
  in_catalog: true
  kin_score: 0.4
  mcp: *id035
  name: ThoroughCare
  slug: thoroughcare
  status: profiled
  tags: *id036
  url: /providers/thoroughcare/
- agent_band: agent-aware
  agent_readiness: 16.8
  band: emerging
  in_catalog: true
  kin_score: 23.8
  mcp: *id037
  name: Updox
  slug: updox
  status: profiled
  tags: *id038
  url: /providers/updox/
- agent_band: agent-ready
  agent_readiness: 28.7
  band: thin
  in_catalog: true
  kin_score: 36.5
  mcp: *id039
  name: VaxCare
  slug: vaxcare
  status: profiled
  tags: *id040
  url: /providers/vaxcare/
- agent_band: agent-ready
  agent_readiness: 31.6
  band: strong
  in_catalog: true
  kin_score: 58.1
  mcp: *id041
  name: Weave
  slug: weave
  status: profiled
  tags: *id042
  url: /providers/weave/
- agent_band: human-only
  agent_readiness: 3.0
  band: minimal
  in_catalog: true
  kin_score: 9.0
  mcp: *id043
  name: Yosi Health
  slug: yosi-health
  status: profiled
  tags: *id044
  url: /providers/yosi-health/
- agent_band: agent-ready
  agent_readiness: 49.4
  band: strong
  in_catalog: true
  kin_score: 55.0
  mcp: *id045
  name: Zocdoc
  slug: zocdoc
  status: profiled
  tags: *id046
  url: /providers/zocdoc/
- agent_band: agent-ready
  agent_readiness: 30.4
  band: strong
  in_catalog: true
  kin_score: 57.2
  mcp: *id047
  name: Zus Health
  slug: zus
  status: profiled
  tags: *id048
  url: /providers/zus/
siblings:
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
- name: Tebra (Kareo + PatientPop)
  rows: 7
  url: /applications/ehr-clinical/tebra-kareo-patientpop/
sitemap: true
title: 'Elation Health: EHR & Clinical Practice reference app'
---
