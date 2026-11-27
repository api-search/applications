---
app: Wise
app_slug: wise
app_url: https://wise.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-200.10
  key: general-ledger-management
  layer: domain
  name: General Ledger Management
  providers:
  - Bonsai
  - FreeAgent
  - Microsoft Dynamics 365 Business Central
  - Odoo
  - Oracle NetSuite
  - QuickBooks
  - Sage Business Cloud Accounting
  - Wave
  - Xero
  - Zoho Books
  url: /capabilities/general-ledger-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-902
  key: AE-902
  layer: common
  name: Mobile Attribution & Deep Linking
  providers:
  - Singular
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
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Google Firebase Analytics
  - Mixpanel
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-160.10.30
  key: AE-160.10.30
  layer: common
  name: Social & Federated Login
  providers:
  - Facebook Login
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
category:
  id: mobile-banking-wallet
  name: Mobile Banking & Payments Wallet
  url: /applications/mobile-banking-wallet/
counts:
  declared: 10
  observed: 5
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.transferwise.android/latest/
- route: integrations page
  url: https://wise.com/us/business/accounting-software
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-aware
    agent_readiness: 28.1
    band: developing
    in_catalog: true
    kin_score: 43.7
    mcp: &id004
      status: none
    slug: facebook
    status: profiled
    tags: &id005
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
  layer: common
  name: Facebook Login
  provider: facebook
  says: ships the Facebook Login SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.transferwise.android/latest/
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
    mcp: &id006
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: google-firebase
    status: profiled
    tags: &id007
    - Analytics
    - Authentication
    - Backend-as-a-Service
    - Cloud Messaging
    url: /providers/google-firebase/
  layer: common
  name: Firebase Crashlytics
  provider: firebase
  says: ships the Firebase Crashlytics SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.transferwise.android/latest/
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
  source: https://reports.exodus-privacy.eu.org/en/reports/com.transferwise.android/latest/
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
    mcp: &id012
      source: https://docs.mixpanel.com/docs/features/mcp
      status: verified
    slug: mixpanel
    status: profiled
    tags: &id013
    - Analytics
    - Data Analysis
    - Event Tracking
    - Product Analytics
    url: /providers/mixpanel/
  layer: common
  name: Mixpanel
  provider: mixpanel
  says: ships the Mixpanel SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.transferwise.android/latest/
  tier: observed
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
    agent_readiness: 48.9
    band: strong
    in_catalog: true
    kin_score: 65.9
    mcp: &id022
      status: none
    slug: singular
    status: profiled
    tags: &id023
    - Attribution
    - Company
    - Marketing Analytics
    - Mobile Attribution
    url: /providers/singular/
  layer: common
  name: Singular
  provider: singular
  says: ships the Singular SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.transferwise.android/latest/
  tier: observed
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
    agent_readiness: 29.7
    band: thin
    in_catalog: true
    kin_score: 27.8
    mcp: &id002
      source: https://mcp.hellobonsai.com/mcp
      status: verified
    slug: bonsai
    status: profiled
    tags: &id003
    - B2B
    - Business Management
    - Company
    - Freelancing
    url: /providers/bonsai/
  layer: domain
  name: Bonsai
  provider: bonsai
  says: lists Bonsai as an integration
  source: https://wise.com/us/business/accounting-software
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
    agent_band: agent-aware
    agent_readiness: 25.1
    band: developing
    in_catalog: true
    kin_score: 39.7
    mcp: &id008
      status: none
    slug: freeagent
    status: profiled
    tags: &id009
    - Accounting
    - Bookkeeping
    - Invoicing
    - Small Business
    url: /providers/freeagent/
  layer: domain
  name: FreeAgent
  provider: freeagent
  says: lists FreeAgent as an integration
  source: https://wise.com/us/business/accounting-software
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
    agent_readiness: 39.9
    band: exemplar
    in_catalog: true
    kin_score: 73.1
    mcp: &id010
      status: none
    slug: microsoft-dynamics-365-business-central
    status: profiled
    tags: &id011
    - Accounting
    - Cloud ERP
    - ERP
    - Finance
    url: /providers/microsoft-dynamics-365-business-central/
  layer: domain
  name: Microsoft Dynamics 365 Business Central
  provider: microsoft-dynamics-365-business-central
  says: lists Microsoft Dynamics 365 Business Central as an integration
  source: https://wise.com/us/business/accounting-software
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
    agent_band: agent-aware
    agent_readiness: 17.5
    band: thin
    in_catalog: true
    kin_score: 27.6
    mcp: &id014
      status: none
    slug: odoo
    status: profiled
    tags: &id015
    - Business Applications
    - CRM
    - ERP
    - Open Source
    url: /providers/odoo/
  layer: domain
  name: Odoo
  provider: odoo
  says: lists Odoo as an integration
  source: https://wise.com/us/business/accounting-software
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
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 11.4
    mcp: &id016
      status: none
    slug: netsuite
    status: profiled
    tags: &id017
    - Accounting
    - CRM
    - ERP
    - Finance
    url: /providers/netsuite/
  layer: domain
  name: Oracle NetSuite
  provider: netsuite
  says: lists Oracle NetSuite as an integration
  source: https://wise.com/us/business/accounting-software
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
    mcp: &id018
      source: https://github.com/intuit/quickbooks-online-mcp-server
      status: verified
    slug: quickbooks
    status: profiled
    tags: &id019
    - Accounting
    - Bookkeeping
    - Finance
    - Small Business
    url: /providers/quickbooks/
  layer: domain
  name: QuickBooks
  provider: quickbooks
  says: lists QuickBooks as an integration
  source: https://wise.com/us/business/accounting-software
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
    mcp: &id020
      status: none
    slug: sage
    status: profiled
    tags: &id021
    - Accounting
    - Business Management
    - Cloud Software
    - ERP
    url: /providers/sage/
  layer: domain
  name: Sage Business Cloud Accounting
  provider: sage
  says: lists Sage Business Cloud Accounting as an integration
  source: https://wise.com/us/business/accounting-software
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
    agent_band: agent-aware
    agent_readiness: 15.8
    band: thin
    in_catalog: true
    kin_score: 26.9
    mcp: &id024
      status: none
    slug: wave-financial
    status: profiled
    tags: &id025
    - Accounting
    - Finance
    - Invoicing
    - Small Business
    url: /providers/wave-financial/
  layer: domain
  name: Wave
  provider: wave-financial
  says: lists Wave as an integration
  source: https://wise.com/us/business/accounting-software
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
    mcp: &id026
      source: https://github.com/XeroAPI/xero-mcp-server
      status: verified
    slug: xero
    status: profiled
    tags: &id027
    - Accounting
    - Bank Feeds
    - Finance
    - Financial Services
    url: /providers/xero/
  layer: domain
  name: Xero
  provider: xero
  says: lists Xero as an integration
  source: https://wise.com/us/business/accounting-software
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
    agent_band: agent-aware
    agent_readiness: 18.6
    band: developing
    in_catalog: true
    kin_score: 47.5
    mcp: &id028
      source: https://www.zoho.com/mcp/
      status: documented
    slug: zoho-books
    status: profiled
    tags: &id029
    - Accounting
    - Bookkeeping
    - Expenses
    - Invoicing
    url: /providers/zoho-books/
  layer: domain
  name: Zoho Books
  provider: zoho-books
  says: lists Zoho Books as an integration
  source: https://wise.com/us/business/accounting-software
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/mobile-banking-wallet/wise/
providers:
- agent_band: agent-ready
  agent_readiness: 29.7
  band: thin
  in_catalog: true
  kin_score: 27.8
  mcp: *id002
  name: Bonsai
  slug: bonsai
  status: profiled
  tags: *id003
  url: /providers/bonsai/
- agent_band: agent-aware
  agent_readiness: 28.1
  band: developing
  in_catalog: true
  kin_score: 43.7
  mcp: *id004
  name: Facebook Login
  slug: facebook
  status: profiled
  tags: *id005
  url: /providers/facebook/
- agent_band: agent-ready
  agent_readiness: 39.9
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id006
  name: Firebase Crashlytics
  slug: google-firebase
  status: profiled
  tags: *id007
  url: /providers/google-firebase/
- agent_band: agent-aware
  agent_readiness: 25.1
  band: developing
  in_catalog: true
  kin_score: 39.7
  mcp: *id008
  name: FreeAgent
  slug: freeagent
  status: profiled
  tags: *id009
  url: /providers/freeagent/
- agent_band: agent-ready
  agent_readiness: 39.9
  band: exemplar
  in_catalog: true
  kin_score: 73.1
  mcp: *id010
  name: Microsoft Dynamics 365 Business Central
  slug: microsoft-dynamics-365-business-central
  status: profiled
  tags: *id011
  url: /providers/microsoft-dynamics-365-business-central/
- agent_band: agent-ready
  agent_readiness: 47.7
  band: strong
  in_catalog: true
  kin_score: 60.8
  mcp: *id012
  name: Mixpanel
  slug: mixpanel
  status: profiled
  tags: *id013
  url: /providers/mixpanel/
- agent_band: agent-aware
  agent_readiness: 17.5
  band: thin
  in_catalog: true
  kin_score: 27.6
  mcp: *id014
  name: Odoo
  slug: odoo
  status: profiled
  tags: *id015
  url: /providers/odoo/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 11.4
  mcp: *id016
  name: Oracle NetSuite
  slug: netsuite
  status: profiled
  tags: *id017
  url: /providers/netsuite/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: strong
  in_catalog: true
  kin_score: 59.8
  mcp: *id018
  name: QuickBooks
  slug: quickbooks
  status: profiled
  tags: *id019
  url: /providers/quickbooks/
- agent_band: agent-ready
  agent_readiness: 30.6
  band: developing
  in_catalog: true
  kin_score: 41.7
  mcp: *id020
  name: Sage Business Cloud Accounting
  slug: sage
  status: profiled
  tags: *id021
  url: /providers/sage/
- agent_band: agent-ready
  agent_readiness: 48.9
  band: strong
  in_catalog: true
  kin_score: 65.9
  mcp: *id022
  name: Singular
  slug: singular
  status: profiled
  tags: *id023
  url: /providers/singular/
- agent_band: agent-aware
  agent_readiness: 15.8
  band: thin
  in_catalog: true
  kin_score: 26.9
  mcp: *id024
  name: Wave
  slug: wave-financial
  status: profiled
  tags: *id025
  url: /providers/wave-financial/
- agent_band: agent-native
  agent_readiness: 60.0
  band: exemplar
  in_catalog: true
  kin_score: 87.1
  mcp: *id026
  name: Xero
  slug: xero
  status: profiled
  tags: *id027
  url: /providers/xero/
- agent_band: agent-aware
  agent_readiness: 18.6
  band: developing
  in_catalog: true
  kin_score: 47.5
  mcp: *id028
  name: Zoho Books
  slug: zoho-books
  status: profiled
  tags: *id029
  url: /providers/zoho-books/
siblings:
- name: Cash App
  rows: 7
  url: /applications/mobile-banking-wallet/cash-app/
- name: Mifos Mobile (openMF mifos-mobile)
  rows: 6
  url: /applications/mobile-banking-wallet/mifos-mobile-openmf-mifos-mobile/
- name: Mifos Pay (openMF mobile-wallet)
  rows: 5
  url: /applications/mobile-banking-wallet/mifos-pay-openmf-mobile-wallet/
- name: PayPal
  rows: 3
  url: /applications/mobile-banking-wallet/paypal/
- name: Revolut
  rows: 3
  url: /applications/mobile-banking-wallet/revolut/
sitemap: true
title: 'Wise: Mobile Banking & Payments Wallet reference app'
---
