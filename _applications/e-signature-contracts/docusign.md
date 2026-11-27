---
app: DocuSign
app_slug: docusign
app_url: https://www.docusign.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-160.30
  key: AE-160.30
  layer: domain
  name: Identity Verification
  providers:
  - CLEAR
  url: /capabilities/identity-verification/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-916
  key: AE-916
  layer: common
  name: Cloud Drive & File Sync
  providers:
  - Box
  - Google Workspace
  - Microsoft OneDrive
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-430.50
  key: customer-feedback-management
  layer: common
  name: Customer Feedback Management
  providers:
  - Wootric
  url: /capabilities/customer-feedback-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-420
  key: customer-relationship-management
  layer: common
  name: Customer Relationship Management
  providers:
  - HubSpot
  - Salesforce
  url: /capabilities/customer-relationship-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-430
  key: customer-service-management
  layer: common
  name: Customer Service Management
  providers:
  - ServiceNow
  url: /capabilities/customer-service-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-300
  key: human-capital-management
  layer: common
  name: Human Capital Management
  providers:
  - Workday
  url: /capabilities/human-capital-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-902
  key: AE-902
  layer: common
  name: Mobile Attribution & Deep Linking
  providers:
  - AppsFlyer
  url: /capabilities/mobile-attribution-deep-linking/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Firebase Crashlytics
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280
  key: product-telemetry-experimentation-management
  layer: common
  name: Product Telemetry & Experimentation Management
  providers:
  - Optimizely
  url: /capabilities/product-telemetry-experimentation-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Google Firebase Analytics
  - Mixpanel
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: Turbo EA
  id: BC-900.30
  key: project-management
  layer: common
  name: Project Management
  providers:
  - monday.com
  url: /capabilities/project-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-910
  key: AE-910
  layer: common
  name: Workflow Automation & iPaaS
  providers:
  - Microsoft Power Automate
  url: /capabilities/process-automation-governance/
  via_parent: Process Automation Governance
category:
  id: e-signature-contracts
  name: E-signature & Contract Management
  url: /applications/e-signature-contracts/
counts:
  declared: 10
  observed: 6
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.docusign.ink/latest/
- route: integrations page
  url: https://www.docusign.com/integrations
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-902
    key: AE-902
    name: Mobile Attribution & Deep Linking
    url: /capabilities/mobile-attribution-deep-linking/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-ready
    agent_readiness: 53.4
    band: exemplar
    in_catalog: true
    kin_score: 72.1
    mcp: &id002
      source: https://registry.modelcontextprotocol.io/v0/servers?search=appsflyer
      status: verified
    slug: appsflyer
    status: profiled
    tags: &id003
    - Company
    - Marketing Analytics
    - Mobile Attribution
    - Mobile Measurement
    url: /providers/appsflyer/
  layer: common
  name: AppsFlyer
  provider: appsflyer
  says: ships the AppsFlyer SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.docusign.ink/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts: &id001
    agent_band: agent-ready
    agent_readiness: 39.9
    band: strong
    in_catalog: true
    kin_score: 62.0
    mcp: &id008
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: google-firebase
    status: profiled
    tags: &id009
    - Analytics
    - Authentication
    - Backend-as-a-Service
    - Cloud Messaging
    url: /providers/google-firebase/
  layer: common
  name: Firebase Crashlytics
  provider: firebase
  says: ships the Firebase Crashlytics SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.docusign.ink/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts: *id001
  layer: common
  name: Google Firebase Analytics
  provider: firebase
  says: ships the Google Firebase Analytics SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.docusign.ink/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-ready
    agent_readiness: 47.7
    band: strong
    in_catalog: true
    kin_score: 60.8
    mcp: &id018
      source: https://docs.mixpanel.com/docs/features/mcp
      status: verified
    slug: mixpanel
    status: profiled
    tags: &id019
    - Analytics
    - Data Analysis
    - Event Tracking
    - Product Analytics
    url: /providers/mixpanel/
  layer: common
  name: Mixpanel
  provider: mixpanel
  says: ships the Mixpanel SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.docusign.ink/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4280
    key: product-telemetry-experimentation-management
    name: Product Telemetry & Experimentation Management
    url: /capabilities/product-telemetry-experimentation-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-ready
    agent_readiness: 61.6
    band: exemplar
    in_catalog: true
    kin_score: 78.1
    mcp: &id022
      source: https://support.optimizely.com/hc/en-us/articles/45320607594893
      status: documented
    slug: optimizely
    status: profiled
    tags: &id023
    - A/B Testing
    - Content Management
    - Customer Data
    - E-Commerce
    url: /providers/optimizely/
  layer: common
  name: Optimizely
  provider: optimizely
  says: ships the Optimizely SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.docusign.ink/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-430.50
    key: customer-feedback-management
    name: Customer Feedback Management
    url: /capabilities/customer-feedback-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-aware
    agent_readiness: 25.6
    band: thin
    in_catalog: true
    kin_score: 32.4
    mcp: &id028
      status: none
    slug: wootric
    status: profiled
    tags: &id029
    - CES
    - CSAT
    - Customer Experience
    - NPS
    url: /providers/wootric/
  layer: common
  name: Wootric
  provider: wootric
  says: ships the Wootric SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.docusign.ink/latest/
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-916
    key: AE-916
    name: Cloud Drive & File Sync
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 56.6
    band: strong
    in_catalog: true
    kin_score: 63.0
    mcp: &id004
      source: https://developer.box.com/guides/box-mcp/
      status: verified
    slug: box
    status: profiled
    tags: &id005
    - Cloud Storage
    - Collaboration
    - Content Management
    - Documents
    url: /providers/box/
  layer: common
  name: Box
  provider: box
  says: lists Box as an integration
  source: https://www.docusign.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-160.30
    key: AE-160.30
    name: Identity Verification
    url: /capabilities/identity-verification/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 34.0
    band: developing
    in_catalog: true
    kin_score: 54.0
    mcp: &id006
      status: none
    slug: clear
    status: profiled
    tags: &id007
    - Authentication
    - Company
    - Identity
    - Identity Verification
    url: /providers/clear/
  layer: domain
  name: CLEAR
  provider: clear
  says: lists CLEAR as an integration
  source: https://www.docusign.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-916
    key: AE-916
    name: Cloud Drive & File Sync
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 43.0
    band: exemplar
    in_catalog: true
    kin_score: 70.7
    mcp: &id010
      source: https://github.com/gemini-cli-extensions/workspace
      status: verified
    slug: google-workspace
    status: profiled
    tags: &id011
    - Calendar
    - Collaboration
    - Email
    - Productivity
    url: /providers/google-workspace/
  layer: common
  name: Google Workspace
  provider: google-workspace
  says: lists Google Workspace as an integration
  source: https://www.docusign.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-420
    key: customer-relationship-management
    name: Customer Relationship Management
    url: /capabilities/customer-relationship-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 52.0
    band: exemplar
    in_catalog: true
    kin_score: 91.9
    mcp: &id012
      source: https://developers.hubspot.com/mcp
      status: verified
    slug: hubspot
    status: profiled
    tags: &id013
    - Analytics
    - CRM
    - Commerce
    - Content
    url: /providers/hubspot/
  layer: common
  name: HubSpot
  provider: hubspot
  says: lists HubSpot as an integration
  source: https://www.docusign.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-916
    key: AE-916
    name: Cloud Drive & File Sync
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.9
    band: developing
    in_catalog: true
    kin_score: 50.9
    mcp: &id014
      status: none
    slug: microsoft-onedrive
    status: profiled
    tags: &id015
    - Cloud Storage
    - File
    - File Storage
    - Microsoft
    url: /providers/microsoft-onedrive/
  layer: common
  name: Microsoft OneDrive
  provider: microsoft-onedrive
  says: lists Microsoft OneDrive as an integration
  source: https://www.docusign.com/integrations
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
    agent_band: agent-ready
    agent_readiness: 29.1
    band: strong
    in_catalog: true
    kin_score: 62.1
    mcp: &id016
      status: none
    slug: microsoft-power-automate
    status: profiled
    tags: &id017
    - Automation
    - Business Process
    - Integration
    - Low-Code
    url: /providers/microsoft-power-automate/
  layer: common
  name: Microsoft Power Automate
  provider: microsoft-power-automate
  says: lists Microsoft Power Automate as an integration
  source: https://www.docusign.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-900.30
    key: project-management
    name: Project Management
    url: /capabilities/project-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 50.3
    band: thin
    in_catalog: true
    kin_score: 32.2
    mcp: &id020
      source: https://github.com/mondaycom/mcp
      status: verified
    slug: monday-com
    status: profiled
    tags: &id021
    - Automation
    - CRM
    - GraphQL
    - Work Management
    url: /providers/monday-com/
  layer: common
  name: monday.com
  provider: monday-com
  says: lists monday.com as an integration
  source: https://www.docusign.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-420
    key: customer-relationship-management
    name: Customer Relationship Management
    url: /capabilities/customer-relationship-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 53.6
    band: exemplar
    in_catalog: true
    kin_score: 88.0
    mcp: &id024
      source: https://github.com/salesforcecli/mcp
      status: verified
    slug: salesforce
    status: profiled
    tags: &id025
    - Analytics
    - Artificial Intelligence
    - Cloud
    - Fortune 500
    url: /providers/salesforce/
  layer: common
  name: Salesforce
  provider: salesforce
  says: lists Salesforce as an integration
  source: https://www.docusign.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-430
    key: customer-service-management
    name: Customer Service Management
    url: /capabilities/customer-service-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 42.3
    band: strong
    in_catalog: true
    kin_score: 61.9
    mcp: &id026
      status: none
    slug: servicenow
    status: profiled
    tags: &id027
    - Automation
    - Cloud Services
    - Digital Workflows
    - ServiceNow
    url: /providers/servicenow/
  layer: common
  name: ServiceNow
  provider: servicenow
  says: lists ServiceNow as an integration
  source: https://www.docusign.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-300
    key: human-capital-management
    name: Human Capital Management
    url: /capabilities/human-capital-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.3
    band: strong
    in_catalog: true
    kin_score: 54.7
    mcp: &id030
      status: none
    slug: workday
    status: profiled
    tags: &id031
    - Cloud Computing
    - Enterprise Software
    - Financial Management
    - HCM
    url: /providers/workday/
  layer: common
  name: Workday
  provider: workday
  says: lists Workday as an integration
  source: https://www.docusign.com/integrations
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/e-signature-contracts/docusign/
providers:
- agent_band: agent-ready
  agent_readiness: 53.4
  band: exemplar
  in_catalog: true
  kin_score: 72.1
  mcp: *id002
  name: AppsFlyer
  slug: appsflyer
  status: profiled
  tags: *id003
  url: /providers/appsflyer/
- agent_band: agent-ready
  agent_readiness: 56.6
  band: strong
  in_catalog: true
  kin_score: 63.0
  mcp: *id004
  name: Box
  slug: box
  status: profiled
  tags: *id005
  url: /providers/box/
- agent_band: agent-ready
  agent_readiness: 34.0
  band: developing
  in_catalog: true
  kin_score: 54.0
  mcp: *id006
  name: CLEAR
  slug: clear
  status: profiled
  tags: *id007
  url: /providers/clear/
- agent_band: agent-ready
  agent_readiness: 39.9
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id008
  name: Firebase Crashlytics
  slug: google-firebase
  status: profiled
  tags: *id009
  url: /providers/google-firebase/
- agent_band: agent-ready
  agent_readiness: 43.0
  band: exemplar
  in_catalog: true
  kin_score: 70.7
  mcp: *id010
  name: Google Workspace
  slug: google-workspace
  status: profiled
  tags: *id011
  url: /providers/google-workspace/
- agent_band: agent-ready
  agent_readiness: 52.0
  band: exemplar
  in_catalog: true
  kin_score: 91.9
  mcp: *id012
  name: HubSpot
  slug: hubspot
  status: profiled
  tags: *id013
  url: /providers/hubspot/
- agent_band: agent-aware
  agent_readiness: 25.9
  band: developing
  in_catalog: true
  kin_score: 50.9
  mcp: *id014
  name: Microsoft OneDrive
  slug: microsoft-onedrive
  status: profiled
  tags: *id015
  url: /providers/microsoft-onedrive/
- agent_band: agent-ready
  agent_readiness: 29.1
  band: strong
  in_catalog: true
  kin_score: 62.1
  mcp: *id016
  name: Microsoft Power Automate
  slug: microsoft-power-automate
  status: profiled
  tags: *id017
  url: /providers/microsoft-power-automate/
- agent_band: agent-ready
  agent_readiness: 47.7
  band: strong
  in_catalog: true
  kin_score: 60.8
  mcp: *id018
  name: Mixpanel
  slug: mixpanel
  status: profiled
  tags: *id019
  url: /providers/mixpanel/
- agent_band: agent-ready
  agent_readiness: 50.3
  band: thin
  in_catalog: true
  kin_score: 32.2
  mcp: *id020
  name: monday.com
  slug: monday-com
  status: profiled
  tags: *id021
  url: /providers/monday-com/
- agent_band: agent-ready
  agent_readiness: 61.6
  band: exemplar
  in_catalog: true
  kin_score: 78.1
  mcp: *id022
  name: Optimizely
  slug: optimizely
  status: profiled
  tags: *id023
  url: /providers/optimizely/
- agent_band: agent-ready
  agent_readiness: 53.6
  band: exemplar
  in_catalog: true
  kin_score: 88.0
  mcp: *id024
  name: Salesforce
  slug: salesforce
  status: profiled
  tags: *id025
  url: /providers/salesforce/
- agent_band: agent-ready
  agent_readiness: 42.3
  band: strong
  in_catalog: true
  kin_score: 61.9
  mcp: *id026
  name: ServiceNow
  slug: servicenow
  status: profiled
  tags: *id027
  url: /providers/servicenow/
- agent_band: agent-aware
  agent_readiness: 25.6
  band: thin
  in_catalog: true
  kin_score: 32.4
  mcp: *id028
  name: Wootric
  slug: wootric
  status: profiled
  tags: *id029
  url: /providers/wootric/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: strong
  in_catalog: true
  kin_score: 54.7
  mcp: *id030
  name: Workday
  slug: workday
  status: profiled
  tags: *id031
  url: /providers/workday/
siblings:
- name: Documenso
  rows: 15
  url: /applications/e-signature-contracts/documenso/
- name: DocuSeal
  rows: 4
  url: /applications/e-signature-contracts/docuseal/
- name: Dropbox Sign
  rows: 18
  url: /applications/e-signature-contracts/dropbox-sign/
- name: OpenSign
  rows: 7
  url: /applications/e-signature-contracts/opensign/
- name: Zoho Sign
  rows: 24
  url: /applications/e-signature-contracts/zoho-sign/
sitemap: true
title: 'DocuSign: E-signature & Contract Management reference app'
---
