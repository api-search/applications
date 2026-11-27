---
app: Xero
app_slug: xero
app_url: https://www.xero.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: domain
  name: Payment Processing Management
  providers:
  - GoCardless
  - Stripe
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4260.40
  key: customer-lifecycle-engagement
  layer: common
  name: Customer Lifecycle Engagement
  providers:
  - Salesforce Marketing Cloud
  url: /capabilities/customer-lifecycle-engagement/
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
  - New Relic
  - Sentry
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Firebase
  - Pendo
  url: /capabilities/product-usage-analytics/
  via_parent: null
category:
  id: accounting-invoicing
  name: Accounting & Invoicing
  url: /applications/accounting-invoicing/
counts:
  declared: 2
  observed: 6
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.xero.touch/latest/
- route: documentation
  url: https://central.xero.com/s/article/Set-up-online-invoice-payments
- route: integrations page
  url: https://www.xero.com/us/accounting-software/accept-payments/
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
    mcp: &id001
      source: https://registry.modelcontextprotocol.io/v0/servers?search=appsflyer
      status: verified
    slug: appsflyer
    status: profiled
    tags: &id002
    - Company
    - Marketing Analytics
    - Mobile Attribution
    - Mobile Measurement
    url: /providers/appsflyer/
  layer: common
  name: AppsFlyer
  provider: appsflyer
  says: ships the AppsFlyer SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.xero.touch/latest/
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
    agent_readiness: 39.9
    band: strong
    in_catalog: true
    kin_score: 62.0
    mcp: &id003
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: google-firebase
    status: profiled
    tags: &id004
    - Analytics
    - Authentication
    - Backend-as-a-Service
    - Cloud Messaging
    url: /providers/google-firebase/
  layer: common
  name: Firebase
  provider: firebase
  says: ships the Firebase SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.xero.touch/latest/
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
    agent_readiness: 44.8
    band: exemplar
    in_catalog: true
    kin_score: 74.4
    mcp: &id007
      source: https://docs.newrelic.com/docs/agentic-ai/mcp/overview/
      status: verified
    slug: new-relic
    status: profiled
    tags: &id008
    - APM
    - Analysis
    - Analytics
    - DevOps
    url: /providers/new-relic/
  layer: common
  name: New Relic
  provider: new-relic
  says: ships the New Relic SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.xero.touch/latest/
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
    agent_readiness: 34.7
    band: strong
    in_catalog: true
    kin_score: 57.0
    mcp: &id009
      source: https://support.pendo.io/hc/en-us/articles/41102236924955
      status: verified
    slug: pendoio
    status: profiled
    tags: &id010
    - Company
    - Digital Adoption
    - Product Analytics
    - Product Experience
    url: /providers/pendoio/
  layer: common
  name: Pendo
  provider: pendoio
  says: ships the Pendo SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.xero.touch/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4260.40
    key: customer-lifecycle-engagement
    name: Customer Lifecycle Engagement
    url: /capabilities/customer-lifecycle-engagement/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-ready
    agent_readiness: 52.3
    band: exemplar
    in_catalog: true
    kin_score: 77.6
    mcp: &id011
      status: none
    slug: salesforce-marketing-cloud
    status: profiled
    tags: &id012
    - Automation
    - Content Management
    - Customer Journey
    - Digital Marketing
    url: /providers/salesforce-marketing-cloud/
  layer: common
  name: Salesforce Marketing Cloud
  provider: salesforce-marketing-cloud
  says: ships the Salesforce Marketing Cloud SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.xero.touch/latest/
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
    kin_score: 80.7
    mcp: &id013
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id014
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: common
  name: Sentry
  provider: sentry-system
  says: ships the Sentry SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.xero.touch/latest/
  tier: observed
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
    agent_readiness: 50.3
    band: developing
    in_catalog: true
    kin_score: 50.0
    mcp: &id005
      source: https://developer.gocardless.com/mcp
      status: verified
    slug: gocardless
    status: profiled
    tags: &id006
    - Bank Debit
    - Direct Debit
    - Payments
    - Recurring Payments
    url: /providers/gocardless/
  layer: domain
  name: GoCardless
  provider: gocardless
  says: lists GoCardless as an integration
  source: https://www.xero.com/us/accounting-software/accept-payments/
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
    mcp: &id015
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id016
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
  layer: domain
  name: Stripe
  provider: stripe
  says: lists Stripe as an integration
  source: https://www.xero.com/us/accounting-software/accept-payments/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/accounting-invoicing/xero/
providers:
- agent_band: agent-ready
  agent_readiness: 53.4
  band: exemplar
  in_catalog: true
  kin_score: 72.1
  mcp: *id001
  name: AppsFlyer
  slug: appsflyer
  status: profiled
  tags: *id002
  url: /providers/appsflyer/
- agent_band: agent-ready
  agent_readiness: 39.9
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id003
  name: Firebase
  slug: google-firebase
  status: profiled
  tags: *id004
  url: /providers/google-firebase/
- agent_band: agent-ready
  agent_readiness: 50.3
  band: developing
  in_catalog: true
  kin_score: 50.0
  mcp: *id005
  name: GoCardless
  slug: gocardless
  status: profiled
  tags: *id006
  url: /providers/gocardless/
- agent_band: agent-ready
  agent_readiness: 44.8
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id007
  name: New Relic
  slug: new-relic
  status: profiled
  tags: *id008
  url: /providers/new-relic/
- agent_band: agent-ready
  agent_readiness: 34.7
  band: strong
  in_catalog: true
  kin_score: 57.0
  mcp: *id009
  name: Pendo
  slug: pendoio
  status: profiled
  tags: *id010
  url: /providers/pendoio/
- agent_band: agent-ready
  agent_readiness: 52.3
  band: exemplar
  in_catalog: true
  kin_score: 77.6
  mcp: *id011
  name: Salesforce Marketing Cloud
  slug: salesforce-marketing-cloud
  status: profiled
  tags: *id012
  url: /providers/salesforce-marketing-cloud/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.7
  mcp: *id013
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id014
  url: /providers/sentry-system/
- agent_band: agent-native
  agent_readiness: 57.6
  band: exemplar
  in_catalog: true
  kin_score: 82.0
  mcp: *id015
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id016
  url: /providers/stripe/
siblings:
- name: Akaunting
  rows: 7
  url: /applications/accounting-invoicing/akaunting/
- name: Crater
  rows: 2
  url: /applications/accounting-invoicing/crater/
- name: ERPNext
  rows: 3
  url: /applications/accounting-invoicing/erpnext/
- name: FreshBooks
  rows: 4
  url: /applications/accounting-invoicing/freshbooks/
- name: Invoice Ninja
  rows: 42
  url: /applications/accounting-invoicing/invoice-ninja/
- name: QuickBooks
  rows: 9
  url: /applications/accounting-invoicing/quickbooks/
- name: SolidInvoice
  rows: 30
  url: /applications/accounting-invoicing/solidinvoice/
- name: Zoho Invoice
  rows: 14
  url: /applications/accounting-invoicing/zoho-invoice/
sitemap: true
title: 'Xero: Accounting & Invoicing reference app'
---
