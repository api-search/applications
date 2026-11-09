---
app: Pipedrive
app_slug: pipedrive
app_url: https://www.pipedrive.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-150.10.30
  key: BC-150.10.30
  layer: domain
  name: Contract Execution Management
  providers:
  - DocuSign
  - Oneflow
  url: /capabilities/contract-management/
  via_parent: Contract Management
- attribution: API Evangelist extension
  id: AE-230.30.10
  key: AE-230.30.10
  layer: domain
  name: Data Enrichment
  providers:
  - Apollo.io
  - Surfe
  url: /capabilities/company-contact-data/
  via_parent: Company & Contact Data
- attribution: Turbo EA
  id: BC-850.10
  key: internal-communications-management
  layer: domain
  name: Internal Communications Management
  providers:
  - Microsoft Teams
  url: /capabilities/internal-communications-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4330.50
  key: invoice-generation-management
  layer: domain
  name: Invoice Generation Management
  providers:
  - QuickBooks
  url: /capabilities/invoice-generation-management/
  via_parent: null
- attribution: Turbo EA
  id: ''
  key: service-request-management
  layer: domain
  name: Service Request Management
  providers:
  - Zendesk
  url: null
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.60
  key: AE-150.60
  layer: domain
  name: Video Calling
  providers:
  - Google Meet
  url: /capabilities/video-calling/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.20.20
  key: AE-150.20.20
  layer: domain
  name: WhatsApp & OTT Messaging
  providers:
  - WhatsApp Business
  url: /capabilities/sms-messaging-apps/
  via_parent: SMS & Messaging Apps
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Firebase
  - New Relic
  - Sentry
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: common
  name: Payment Processing Management
  providers:
  - Stripe
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Amplitude
  - Twilio Segment
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: Turbo EA
  id: BC-900.30
  key: project-management
  layer: common
  name: Project Management
  providers:
  - Asana
  url: /capabilities/project-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-910
  key: AE-910
  layer: common
  name: Workflow Automation & iPaaS
  providers:
  - Zapier
  url: /capabilities/process-automation-governance/
  via_parent: Process Automation Governance
category:
  id: crm-sales
  name: CRM & Sales Pipeline
  url: /applications/crm-sales/
counts:
  declared: 12
  observed: 5
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.pipedrive/latest/
- route: integrations page
  url: https://www.pipedrive.com/en/marketplace
integrations:
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
    agent_readiness: 56.7
    band: strong
    in_catalog: true
    kin_score: 63.5
    mcp: &id001
      source: https://amplitude.com/docs/amplitude-ai/amplitude-mcp
      status: verified
    slug: amplitude
    status: profiled
    tags: &id002
    - A/B Testing
    - Analytics
    - Experimentation
    - Feature Flags
    url: /providers/amplitude/
  layer: common
  name: Amplitude
  provider: amplitude
  says: ships the Amplitude SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.pipedrive/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-aware
    agent_readiness: 14.2
    band: developing
    in_catalog: true
    kin_score: 50.3
    mcp: &id009
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: firebase
    status: profiled
    tags: &id010
    - Application Development
    - Backend-as-a-Service
    - Company
    - Mobile
    url: /providers/firebase/
  layer: common
  name: Firebase
  provider: firebase
  says: ships the Firebase SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.pipedrive/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-ready
    agent_readiness: 45.7
    band: exemplar
    in_catalog: true
    kin_score: 76.5
    mcp: &id015
      source: https://docs.newrelic.com/docs/agentic-ai/mcp/overview/
      status: verified
    slug: new-relic
    status: profiled
    tags: &id016
    - APM
    - Analysis
    - Analytics
    - DevOps
    url: /providers/new-relic/
  layer: common
  name: New Relic
  provider: new-relic
  says: ships the New Relic SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.pipedrive/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-ready
    agent_readiness: 50.2
    band: exemplar
    in_catalog: true
    kin_score: 80.6
    mcp: &id021
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id022
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: common
  name: Sentry
  provider: sentry-system
  says: ships the Sentry SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.pipedrive/latest/
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
    agent_band: agent-aware
    agent_readiness: 26.8
    band: developing
    in_catalog: true
    kin_score: 43.8
    mcp: &id027
      status: none
    slug: segment
    status: profiled
    tags: &id028
    - CDP
    - Company
    - Customer Data Platform
    - Identity Resolution
    url: /providers/segment/
  layer: common
  name: Twilio Segment
  provider: segment
  says: ships the Twilio Segment SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.pipedrive/latest/
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-230.30.10
    key: AE-230.30.10
    name: Data Enrichment
    url: /capabilities/company-contact-data/
    via_parent: Company & Contact Data
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 59.2
    band: exemplar
    in_catalog: true
    kin_score: 70.1
    mcp: &id003
      source: https://docs.apollo.io/docs/apollo-mcp
      status: verified
    slug: apollo-io
    status: profiled
    tags: &id004
    - B2B Data
    - Engagement
    - Prospecting
    - Sales Intelligence
    url: /providers/apollo-io/
  layer: domain
  name: Apollo.io
  provider: apollo-io
  says: lists Apollo.io as an integration
  source: https://www.pipedrive.com/en/marketplace
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
    agent_readiness: 53.7
    band: exemplar
    in_catalog: true
    kin_score: 74.8
    mcp: &id005
      source: https://developers.asana.com/docs/using-asanas-mcp-server
      status: verified
    slug: asana
    status: profiled
    tags: &id006
    - Collaboration
    - Productivity
    - Project
    - Project Management
    url: /providers/asana/
  layer: common
  name: Asana
  provider: asana
  says: lists Asana as an integration
  source: https://www.pipedrive.com/en/marketplace
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-150.10.30
    key: BC-150.10.30
    name: Contract Execution Management
    url: /capabilities/contract-management/
    via_parent: Contract Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 35.0
    band: exemplar
    in_catalog: true
    kin_score: 71.4
    mcp: &id007
      source: https://www.docusign.com/products/mcp
      status: documented
    slug: docusign
    status: profiled
    tags: &id008
    - Agreements
    - Contracts
    - DocuSign
    - E-Signature
    url: /providers/docusign/
  layer: domain
  name: DocuSign
  provider: docusign
  says: lists DocuSign as an integration
  source: https://www.pipedrive.com/en/marketplace
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.60
    key: AE-150.60
    name: Video Calling
    url: /capabilities/video-calling/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 17.2
    band: thin
    in_catalog: true
    kin_score: 27.7
    mcp: &id011
      status: none
    slug: google-meet
    status: profiled
    tags: &id012
    - Google
    - Google Workspace
    - Meetings
    - Recording
    url: /providers/google-meet/
  layer: domain
  name: Google Meet
  provider: google-meet
  says: lists Google Meet as an integration
  source: https://www.pipedrive.com/en/marketplace
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-850.10
    key: internal-communications-management
    name: Internal Communications Management
    url: /capabilities/internal-communications-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 34.2
    band: strong
    in_catalog: true
    kin_score: 59.0
    mcp: &id013
      status: none
    slug: microsoft-teams
    status: profiled
    tags: &id014
    - Chat
    - Collaboration
    - Communications
    - Microsoft Teams
    url: /providers/microsoft-teams/
  layer: domain
  name: Microsoft Teams
  provider: microsoft-teams
  says: lists Microsoft Teams as an integration
  source: https://www.pipedrive.com/en/marketplace
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-150.10.30
    key: BC-150.10.30
    name: Contract Execution Management
    url: /capabilities/contract-management/
    via_parent: Contract Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 19.0
    band: thin
    in_catalog: true
    kin_score: 30.9
    mcp: &id017
      status: none
    slug: oneflow
    status: profiled
    tags: &id018
    - Contract Lifecycle Management
    - Contract Management
    - Digital Contracts
    - E-Signature
    url: /providers/oneflow/
  layer: domain
  name: Oneflow
  provider: oneflow
  says: lists Oneflow as an integration
  source: https://www.pipedrive.com/en/marketplace
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4330.50
    key: invoice-generation-management
    name: Invoice Generation Management
    url: /capabilities/invoice-generation-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 41.2
    band: strong
    in_catalog: true
    kin_score: 61.1
    mcp: &id019
      source: https://github.com/intuit/quickbooks-online-mcp-server
      status: verified
    slug: quickbooks
    status: profiled
    tags: &id020
    - Accounting
    - Bookkeeping
    - Finance
    - Small Business
    url: /providers/quickbooks/
  layer: domain
  name: QuickBooks
  provider: quickbooks
  says: lists QuickBooks as an integration
  source: https://www.pipedrive.com/en/marketplace
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 58.5
    band: exemplar
    in_catalog: true
    kin_score: 81.5
    mcp: &id023
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id024
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
  layer: common
  name: Stripe
  provider: stripe
  says: lists Stripe as an integration
  source: https://www.pipedrive.com/en/marketplace
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-230.30.10
    key: AE-230.30.10
    name: Data Enrichment
    url: /capabilities/company-contact-data/
    via_parent: Company & Contact Data
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 53.7
    band: exemplar
    in_catalog: true
    kin_score: 77.3
    mcp: &id025
      source: https://developers.surfe.com/mcp
      status: verified
    slug: surfe
    status: profiled
    tags: &id026
    - B2B Data
    - Contact Data
    - Data Enrichment
    - Sales Intelligence
    url: /providers/surfe/
  layer: domain
  name: Surfe
  provider: surfe
  says: lists Surfe as an integration
  source: https://www.pipedrive.com/en/marketplace
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.20
    key: AE-150.20.20
    name: WhatsApp & OTT Messaging
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 48.0
    band: exemplar
    in_catalog: true
    kin_score: 68.0
    mcp: &id029
      status: none
    slug: whatsapp
    status: profiled
    tags: &id030
    - Analytics
    - Business Messaging
    - Messaging
    - WhatsApp
    url: /providers/whatsapp/
  layer: domain
  name: WhatsApp Business
  provider: whatsapp
  says: lists WhatsApp Business as an integration
  source: https://www.pipedrive.com/en/marketplace
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
    agent_readiness: 66.2
    band: exemplar
    in_catalog: true
    kin_score: 72.0
    mcp: &id031
      source: https://zapier.com/mcp
      status: verified
    slug: zapier
    status: profiled
    tags: &id032
    - Integration
    - Workflow Automation
    - Zapier
    - iPaaS
    url: /providers/zapier/
  layer: common
  name: Zapier
  provider: zapier
  says: lists Zapier as an integration
  source: https://www.pipedrive.com/en/marketplace
  tier: declared
- capability:
    attribution: Turbo EA
    id: ''
    key: service-request-management
    name: Service Request Management
    url: null
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 35.0
    band: exemplar
    in_catalog: true
    kin_score: 72.8
    mcp: &id033
      status: none
    slug: zendesk
    status: profiled
    tags: &id034
    - CRM
    - Chat
    - Help Center
    - Sell
    url: /providers/zendesk/
  layer: domain
  name: Zendesk
  provider: zendesk
  says: lists Zendesk as an integration
  source: https://www.pipedrive.com/en/marketplace
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/crm-sales/pipedrive/
providers:
- agent_band: agent-ready
  agent_readiness: 56.7
  band: strong
  in_catalog: true
  kin_score: 63.5
  mcp: *id001
  name: Amplitude
  slug: amplitude
  status: profiled
  tags: *id002
  url: /providers/amplitude/
- agent_band: agent-ready
  agent_readiness: 59.2
  band: exemplar
  in_catalog: true
  kin_score: 70.1
  mcp: *id003
  name: Apollo.io
  slug: apollo-io
  status: profiled
  tags: *id004
  url: /providers/apollo-io/
- agent_band: agent-ready
  agent_readiness: 53.7
  band: exemplar
  in_catalog: true
  kin_score: 74.8
  mcp: *id005
  name: Asana
  slug: asana
  status: profiled
  tags: *id006
  url: /providers/asana/
- agent_band: agent-ready
  agent_readiness: 35.0
  band: exemplar
  in_catalog: true
  kin_score: 71.4
  mcp: *id007
  name: DocuSign
  slug: docusign
  status: profiled
  tags: *id008
  url: /providers/docusign/
- agent_band: agent-aware
  agent_readiness: 14.2
  band: developing
  in_catalog: true
  kin_score: 50.3
  mcp: *id009
  name: Firebase
  slug: firebase
  status: profiled
  tags: *id010
  url: /providers/firebase/
- agent_band: agent-aware
  agent_readiness: 17.2
  band: thin
  in_catalog: true
  kin_score: 27.7
  mcp: *id011
  name: Google Meet
  slug: google-meet
  status: profiled
  tags: *id012
  url: /providers/google-meet/
- agent_band: agent-ready
  agent_readiness: 34.2
  band: strong
  in_catalog: true
  kin_score: 59.0
  mcp: *id013
  name: Microsoft Teams
  slug: microsoft-teams
  status: profiled
  tags: *id014
  url: /providers/microsoft-teams/
- agent_band: agent-ready
  agent_readiness: 45.7
  band: exemplar
  in_catalog: true
  kin_score: 76.5
  mcp: *id015
  name: New Relic
  slug: new-relic
  status: profiled
  tags: *id016
  url: /providers/new-relic/
- agent_band: agent-aware
  agent_readiness: 19.0
  band: thin
  in_catalog: true
  kin_score: 30.9
  mcp: *id017
  name: Oneflow
  slug: oneflow
  status: profiled
  tags: *id018
  url: /providers/oneflow/
- agent_band: agent-native
  agent_readiness: 41.2
  band: strong
  in_catalog: true
  kin_score: 61.1
  mcp: *id019
  name: QuickBooks
  slug: quickbooks
  status: profiled
  tags: *id020
  url: /providers/quickbooks/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.6
  mcp: *id021
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id022
  url: /providers/sentry-system/
- agent_band: agent-native
  agent_readiness: 58.5
  band: exemplar
  in_catalog: true
  kin_score: 81.5
  mcp: *id023
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id024
  url: /providers/stripe/
- agent_band: agent-ready
  agent_readiness: 53.7
  band: exemplar
  in_catalog: true
  kin_score: 77.3
  mcp: *id025
  name: Surfe
  slug: surfe
  status: profiled
  tags: *id026
  url: /providers/surfe/
- agent_band: agent-aware
  agent_readiness: 26.8
  band: developing
  in_catalog: true
  kin_score: 43.8
  mcp: *id027
  name: Twilio Segment
  slug: segment
  status: profiled
  tags: *id028
  url: /providers/segment/
- agent_band: agent-ready
  agent_readiness: 48.0
  band: exemplar
  in_catalog: true
  kin_score: 68.0
  mcp: *id029
  name: WhatsApp Business
  slug: whatsapp
  status: profiled
  tags: *id030
  url: /providers/whatsapp/
- agent_band: agent-ready
  agent_readiness: 66.2
  band: exemplar
  in_catalog: true
  kin_score: 72.0
  mcp: *id031
  name: Zapier
  slug: zapier
  status: profiled
  tags: *id032
  url: /providers/zapier/
- agent_band: agent-ready
  agent_readiness: 35.0
  band: exemplar
  in_catalog: true
  kin_score: 72.8
  mcp: *id033
  name: Zendesk
  slug: zendesk
  status: profiled
  tags: *id034
  url: /providers/zendesk/
siblings:
- name: EspoCRM
  rows: 14
  url: /applications/crm-sales/espocrm/
- name: HubSpot
  rows: 6
  url: /applications/crm-sales/hubspot/
- name: Krayin CRM
  rows: 1
  url: /applications/crm-sales/krayin-crm/
- name: Salesforce
  rows: 1
  url: /applications/crm-sales/salesforce/
- name: SuiteCRM
  rows: 10
  url: /applications/crm-sales/suitecrm/
- name: Twenty
  rows: 20
  url: /applications/crm-sales/twenty/
- name: Zoho CRM
  rows: 0
  url: /applications/crm-sales/zoho-crm/
sitemap: true
title: 'Pipedrive: CRM & Sales Pipeline reference app'
---
