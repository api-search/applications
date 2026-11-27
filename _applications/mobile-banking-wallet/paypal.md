---
app: PayPal
app_slug: paypal
app_url: https://www.paypal.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-430.50
  key: customer-feedback-management
  layer: common
  name: Customer Feedback Management
  providers:
  - Qualtrics
  url: /capabilities/customer-feedback-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-400.60
  key: digital-marketing-management
  layer: common
  name: Digital Marketing Management
  providers:
  - Adobe Experience Cloud
  url: /capabilities/digital-marketing-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-902
  key: AE-902
  layer: common
  name: Mobile Attribution & Deep Linking
  providers:
  - Adjust
  url: /capabilities/mobile-attribution-deep-linking/
  via_parent: null
category:
  id: mobile-banking-wallet
  name: Mobile Banking & Payments Wallet
  url: /applications/mobile-banking-wallet/
counts:
  declared: 0
  observed: 3
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.paypal.android.p2pmobile/latest/
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
    agent_band: agent-aware
    agent_readiness: 23.3
    band: thin
    in_catalog: true
    kin_score: 30.9
    mcp: &id001
      status: none
    slug: adjust
    status: profiled
    tags: &id002
    - Analytics
    - Attribution
    - Deep Linking
    - Measurements
    url: /providers/adjust/
  layer: common
  name: Adjust
  provider: adjust
  says: ships the Adjust SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.paypal.android.p2pmobile/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-ready
    agent_readiness: 53.0
    band: strong
    in_catalog: true
    kin_score: 65.1
    mcp: &id003
      source: https://github.com/adobe/cq-quickstart-mcp-server
      status: verified
    slug: adobe-experience-cloud
    status: profiled
    tags: &id004
    - Analytics
    - Customer Experience
    - Digital Marketing
    - Personalization
    url: /providers/adobe-experience-cloud/
  layer: common
  name: Adobe Experience Cloud
  provider: adobe-experience-cloud
  says: ships the Adobe Experience Cloud SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.paypal.android.p2pmobile/latest/
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
    agent_readiness: 19.6
    band: developing
    in_catalog: true
    kin_score: 45.7
    mcp: &id005
      status: none
    slug: qualtrics
    status: profiled
    tags: &id006
    - Customer Experience
    - Employee Experience
    - Experience Management
    - Surveys
    url: /providers/qualtrics/
  layer: common
  name: Qualtrics
  provider: qualtrics
  says: ships the Qualtrics SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.paypal.android.p2pmobile/latest/
  tier: observed
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/mobile-banking-wallet/paypal/
providers:
- agent_band: agent-aware
  agent_readiness: 23.3
  band: thin
  in_catalog: true
  kin_score: 30.9
  mcp: *id001
  name: Adjust
  slug: adjust
  status: profiled
  tags: *id002
  url: /providers/adjust/
- agent_band: agent-ready
  agent_readiness: 53.0
  band: strong
  in_catalog: true
  kin_score: 65.1
  mcp: *id003
  name: Adobe Experience Cloud
  slug: adobe-experience-cloud
  status: profiled
  tags: *id004
  url: /providers/adobe-experience-cloud/
- agent_band: agent-aware
  agent_readiness: 19.6
  band: developing
  in_catalog: true
  kin_score: 45.7
  mcp: *id005
  name: Qualtrics
  slug: qualtrics
  status: profiled
  tags: *id006
  url: /providers/qualtrics/
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
- name: Revolut
  rows: 3
  url: /applications/mobile-banking-wallet/revolut/
- name: Wise
  rows: 15
  url: /applications/mobile-banking-wallet/wise/
sitemap: true
title: 'PayPal: Mobile Banking & Payments Wallet reference app'
---
