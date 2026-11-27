---
app: Glue Up
app_slug: glue-up
app_url: https://www.glueup.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-420
  key: customer-relationship-management
  layer: domain
  name: Customer Relationship Management
  providers:
  - Salesforce
  url: /capabilities/customer-relationship-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-210.50
  key: event-ticketing
  layer: domain
  name: Event Ticketing
  providers:
  - Cvent
  url: /capabilities/event-ticketing/
  via_parent: null
- attribution: Turbo EA
  id: BC-200.10
  key: general-ledger-management
  layer: domain
  name: General Ledger Management
  providers:
  - Quickbooks
  - Sage
  - Xero
  url: /capabilities/general-ledger-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4330.50
  key: invoice-generation-management
  layer: domain
  name: Invoice Generation Management
  providers:
  - Storecove
  url: /capabilities/invoice-generation-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-300.40
  key: learning-development-management
  layer: domain
  name: Learning & Development Management
  providers:
  - Oasis Lms
  url: /capabilities/learning-development-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: domain
  name: Payment Processing Management
  providers:
  - Crowded
  - Paygate
  - Paypal
  - Stripe
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.80
  key: AE-150.80
  layer: common
  name: Mailbox & Calendar Sync
  providers:
  - Microsoft Outlook
  url: /capabilities/mailbox-calendar-sync/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Google Analytics
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.60
  key: AE-150.60
  layer: common
  name: Video Calling
  providers:
  - Zoom
  url: /capabilities/video-calling/
  via_parent: null
category:
  id: membership-associations
  name: Membership & Association Management
  url: /applications/membership-associations/
counts:
  declared: 14
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.glueup.com/integrations
integrations:
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
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
    slug: crowded
    status: queued for profiling
    tags: &id002 []
    url: null
  layer: domain
  name: Crowded
  provider: crowded
  says: lists Crowded as an integration
  source: https://www.glueup.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-210.50
    key: event-ticketing
    name: Event Ticketing
    url: /capabilities/event-ticketing/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 46.5
    band: exemplar
    in_catalog: true
    kin_score: 72.6
    mcp: &id003
      status: unknown
    slug: cvent
    status: profiled
    tags: &id004
    - Attendee Hub
    - Attendee Management
    - Conferences
    - Diagramming
    url: /providers/cvent/
  layer: domain
  name: Cvent
  provider: cvent
  says: lists Cvent as an integration
  source: https://www.glueup.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 42.9
    band: exemplar
    in_catalog: true
    kin_score: 79.7
    mcp: &id005
      source: https://developers.google.com/analytics/devguides/MCP
      status: verified
    slug: google-analytics
    status: profiled
    tags: &id006
    - Analytics
    - Data
    - Google
    - Metrics
    url: /providers/google-analytics/
  layer: common
  name: Google Analytics
  provider: google-analytics
  says: lists Google Analytics as an integration
  source: https://www.glueup.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.80
    key: AE-150.80
    name: Mailbox & Calendar Sync
    url: /capabilities/mailbox-calendar-sync/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 42.9
    band: exemplar
    in_catalog: true
    kin_score: 70.8
    mcp: &id007
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-outlook
    status: profiled
    tags: &id008
    - Calendar
    - Contacts
    - Email
    - Enterprise
    url: /providers/microsoft-outlook/
  layer: common
  name: Microsoft Outlook
  provider: microsoft-outlook
  says: lists Microsoft Outlook as an integration
  source: https://www.glueup.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-300.40
    key: learning-development-management
    name: Learning & Development Management
    url: /capabilities/learning-development-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: emerging
    in_catalog: true
    kin_score: 16.2
    mcp: &id009
      status: unchecked
    slug: oasis-lms
    status: profiled
    tags: &id010
    - Associations
    - Continuing Education
    - Healthcare
    - LMS
    url: /providers/oasis-lms/
  layer: domain
  name: Oasis Lms
  provider: oasis-lms
  says: lists Oasis Lms as an integration
  source: https://www.glueup.com/integrations
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
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id011
      status: unchecked
    slug: paygate
    status: queued for profiling
    tags: &id012 []
    url: null
  layer: domain
  name: Paygate
  provider: paygate
  says: lists Paygate as an integration
  source: https://www.glueup.com/integrations
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
    agent_band: agent-ready
    agent_readiness: 36.3
    band: strong
    in_catalog: true
    kin_score: 54.9
    mcp: &id013
      source: https://developer.paypal.com/tools/mcp-server/
      status: verified
    slug: paypal
    status: profiled
    tags: &id014
    - Billing
    - Commerce
    - Disputes
    - PayPal
    url: /providers/paypal/
  layer: domain
  name: Paypal
  provider: paypal
  says: lists Paypal as an integration
  source: https://www.glueup.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-200.10
    key: general-ledger-management
    name: General Ledger Management
    url: /capabilities/general-ledger-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.3
    band: strong
    in_catalog: true
    kin_score: 59.8
    mcp: &id015
      source: https://github.com/intuit/quickbooks-online-mcp-server
      status: verified
    slug: quickbooks
    status: profiled
    tags: &id016
    - Accounting
    - Bookkeeping
    - Finance
    - Small Business
    url: /providers/quickbooks/
  layer: domain
  name: Quickbooks
  provider: quickbooks
  says: lists Quickbooks as an integration
  source: https://www.glueup.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-200.10
    key: general-ledger-management
    name: General Ledger Management
    url: /capabilities/general-ledger-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 30.6
    band: developing
    in_catalog: true
    kin_score: 41.7
    mcp: &id017
      status: none
    slug: sage
    status: profiled
    tags: &id018
    - Accounting
    - Business Management
    - Cloud Software
    - ERP
    url: /providers/sage/
  layer: domain
  name: Sage
  provider: sage
  says: lists Sage as an integration
  source: https://www.glueup.com/integrations
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
    mcp: &id019
      source: https://github.com/salesforcecli/mcp
      status: verified
    slug: salesforce
    status: profiled
    tags: &id020
    - Analytics
    - Artificial Intelligence
    - Cloud
    - Fortune 500
    url: /providers/salesforce/
  layer: domain
  name: Salesforce
  provider: salesforce
  says: lists Salesforce as an integration
  source: https://www.glueup.com/integrations
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
    agent_band: agent-ready
    agent_readiness: 38.0
    band: developing
    in_catalog: true
    kin_score: 52.7
    mcp: &id021
      status: unknown
    slug: storecove
    status: profiled
    tags: &id022
    - Company
    - E-Invoicing
    - Peppol
    - Tax Compliance
    url: /providers/storecove/
  layer: domain
  name: Storecove
  provider: storecove
  says: lists Storecove as an integration
  source: https://www.glueup.com/integrations
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
    agent_readiness: 57.6
    band: exemplar
    in_catalog: true
    kin_score: 82.0
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
  layer: domain
  name: Stripe
  provider: stripe
  says: lists Stripe as an integration
  source: https://www.glueup.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-200.10
    key: general-ledger-management
    name: General Ledger Management
    url: /capabilities/general-ledger-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 60.0
    band: exemplar
    in_catalog: true
    kin_score: 87.1
    mcp: &id025
      source: https://github.com/XeroAPI/xero-mcp-server
      status: verified
    slug: xero
    status: profiled
    tags: &id026
    - Accounting
    - Bank Feeds
    - Finance
    - Financial Services
    url: /providers/xero/
  layer: domain
  name: Xero
  provider: xero
  says: lists Xero as an integration
  source: https://www.glueup.com/integrations
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
    agent_band: agent-ready
    agent_readiness: 56.8
    band: strong
    in_catalog: true
    kin_score: 57.1
    mcp: &id027
      source: https://developers.zoom.us/docs/mcp/
      status: verified
    slug: zoom
    status: profiled
    tags: &id028
    - Chat
    - Collaboration
    - Video
    - Zoom
    url: /providers/zoom/
  layer: common
  name: Zoom
  provider: zoom
  says: lists Zoom as an integration
  source: https://www.glueup.com/integrations
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/membership-associations/glue-up/
providers:
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id001
  name: Crowded
  slug: crowded
  status: queued for profiling
  tags: *id002
  url: null
- agent_band: agent-ready
  agent_readiness: 46.5
  band: exemplar
  in_catalog: true
  kin_score: 72.6
  mcp: *id003
  name: Cvent
  slug: cvent
  status: profiled
  tags: *id004
  url: /providers/cvent/
- agent_band: agent-ready
  agent_readiness: 42.9
  band: exemplar
  in_catalog: true
  kin_score: 79.7
  mcp: *id005
  name: Google Analytics
  slug: google-analytics
  status: profiled
  tags: *id006
  url: /providers/google-analytics/
- agent_band: agent-ready
  agent_readiness: 42.9
  band: exemplar
  in_catalog: true
  kin_score: 70.8
  mcp: *id007
  name: Microsoft Outlook
  slug: microsoft-outlook
  status: profiled
  tags: *id008
  url: /providers/microsoft-outlook/
- agent_band: human-only
  agent_readiness: 3.0
  band: emerging
  in_catalog: true
  kin_score: 16.2
  mcp: *id009
  name: Oasis Lms
  slug: oasis-lms
  status: profiled
  tags: *id010
  url: /providers/oasis-lms/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id011
  name: Paygate
  slug: paygate
  status: queued for profiling
  tags: *id012
  url: null
- agent_band: agent-ready
  agent_readiness: 36.3
  band: strong
  in_catalog: true
  kin_score: 54.9
  mcp: *id013
  name: Paypal
  slug: paypal
  status: profiled
  tags: *id014
  url: /providers/paypal/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: strong
  in_catalog: true
  kin_score: 59.8
  mcp: *id015
  name: Quickbooks
  slug: quickbooks
  status: profiled
  tags: *id016
  url: /providers/quickbooks/
- agent_band: agent-ready
  agent_readiness: 30.6
  band: developing
  in_catalog: true
  kin_score: 41.7
  mcp: *id017
  name: Sage
  slug: sage
  status: profiled
  tags: *id018
  url: /providers/sage/
- agent_band: agent-ready
  agent_readiness: 53.6
  band: exemplar
  in_catalog: true
  kin_score: 88.0
  mcp: *id019
  name: Salesforce
  slug: salesforce
  status: profiled
  tags: *id020
  url: /providers/salesforce/
- agent_band: agent-ready
  agent_readiness: 38.0
  band: developing
  in_catalog: true
  kin_score: 52.7
  mcp: *id021
  name: Storecove
  slug: storecove
  status: profiled
  tags: *id022
  url: /providers/storecove/
- agent_band: agent-native
  agent_readiness: 57.6
  band: exemplar
  in_catalog: true
  kin_score: 82.0
  mcp: *id023
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id024
  url: /providers/stripe/
- agent_band: agent-native
  agent_readiness: 60.0
  band: exemplar
  in_catalog: true
  kin_score: 87.1
  mcp: *id025
  name: Xero
  slug: xero
  status: profiled
  tags: *id026
  url: /providers/xero/
- agent_band: agent-ready
  agent_readiness: 56.8
  band: strong
  in_catalog: true
  kin_score: 57.1
  mcp: *id027
  name: Zoom
  slug: zoom
  status: profiled
  tags: *id028
  url: /providers/zoom/
siblings:
- name: Dolibarr (Members module)
  rows: 10
  url: /applications/membership-associations/dolibarr-members-module/
- name: Galette
  rows: 4
  url: /applications/membership-associations/galette/
- name: Novi AMS
  rows: 46
  url: /applications/membership-associations/novi-ams/
- name: Paid Memberships Pro
  rows: 29
  url: /applications/membership-associations/paid-memberships-pro/
- name: WildApricot
  rows: 8
  url: /applications/membership-associations/wildapricot/
sitemap: true
title: 'Glue Up: Membership & Association Management reference app'
---
