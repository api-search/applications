---
app: CVS Health
app_slug: cvs-health
app_url: https://www.cvs.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-4260.40
  key: customer-lifecycle-engagement
  layer: common
  name: Customer Lifecycle Engagement
  providers:
  - Braze
  url: /capabilities/customer-lifecycle-engagement/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-903
  key: AE-903
  layer: common
  name: In-App Ad Monetisation
  providers:
  - Google AdMob
  url: /capabilities/in-app-ad-monetisation/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-902
  key: AE-902
  layer: common
  name: Mobile Attribution & Deep Linking
  providers:
  - Branch
  - Tapstream
  url: /capabilities/mobile-attribution-deep-linking/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - New Relic
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Adobe Experience Cloud
  - Firebase
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-140.60
  key: AE-140.60
  layer: common
  name: Reviews & Social Proof
  providers:
  - Bazaarvoice
  url: /capabilities/reviews-social-proof/
  via_parent: null
category:
  id: pharmacy-prescriptions
  name: Pharmacy & Prescriptions
  url: /applications/pharmacy-prescriptions/
counts:
  declared: 0
  observed: 8
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.cvs.launchers.cvs/latest/
- route: store listing
  url: https://apps.apple.com/us/app/cvs-health/id395545555
- route: store listing
  url: https://play.google.com/store/apps/details?id=com.cvs.launchers.cvs
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
    agent_readiness: 53.0
    band: strong
    in_catalog: true
    kin_score: 65.1
    mcp: &id001
      source: https://github.com/adobe/cq-quickstart-mcp-server
      status: verified
    slug: adobe-experience-cloud
    status: profiled
    tags: &id002
    - Analytics
    - Customer Experience
    - Digital Marketing
    - Personalization
    url: /providers/adobe-experience-cloud/
  layer: common
  name: Adobe Experience Cloud
  provider: adobe-experience-cloud
  says: ships the Adobe Experience Cloud SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.cvs.launchers.cvs/latest/
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-140.60
    key: AE-140.60
    name: Reviews & Social Proof
    url: /capabilities/reviews-social-proof/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-ready
    agent_readiness: 32.5
    band: exemplar
    in_catalog: true
    kin_score: 67.4
    mcp: &id003
      status: none
    slug: bazaarvoice
    status: profiled
    tags: &id004
    - BazaarVoice
    - Company
    - Ratings
    - Reviews
    url: /providers/bazaarvoice/
  layer: common
  name: Bazaarvoice
  provider: bazaarvoice
  says: ships the Bazaarvoice SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.cvs.launchers.cvs/latest/
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
    agent_band: agent-aware
    agent_readiness: 21.9
    band: thin
    in_catalog: true
    kin_score: 33.8
    mcp: &id005
      status: none
    slug: branch-io
    status: profiled
    tags: &id006
    - Company
    url: /providers/branch-io/
  layer: common
  name: Branch
  provider: branch-io
  says: ships the Branch SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.cvs.launchers.cvs/latest/
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
    agent_readiness: 58.4
    band: exemplar
    in_catalog: true
    kin_score: 74.4
    mcp: &id007
      source: https://www.braze.com/docs/user_guide/brazeai/mcp_server
      status: verified
    slug: braze
    status: profiled
    tags: &id008
    - Customer Engagement
    - Marketing Automation
    - Messaging
    - Push Notifications
    url: /providers/braze/
  layer: common
  name: Braze
  provider: braze
  says: ships the Braze SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.cvs.launchers.cvs/latest/
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
    mcp: &id009
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: google-firebase
    status: profiled
    tags: &id010
    - Analytics
    - Authentication
    - Backend-as-a-Service
    - Cloud Messaging
    url: /providers/google-firebase/
  layer: common
  name: Firebase
  provider: firebase
  says: ships the Firebase SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.cvs.launchers.cvs/latest/
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-903
    key: AE-903
    name: In-App Ad Monetisation
    url: /capabilities/in-app-ad-monetisation/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-ready
    agent_readiness: 35.3
    band: strong
    in_catalog: true
    kin_score: 65.2
    mcp: &id011
      status: none
    slug: google-admob
    status: profiled
    tags: &id012
    - Ad Mediation
    - AdMob
    - Advertising
    - App Monetization
    url: /providers/google-admob/
  layer: common
  name: Google AdMob
  provider: google-admob
  says: ships the Google AdMob SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.cvs.launchers.cvs/latest/
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
    mcp: &id013
      source: https://docs.newrelic.com/docs/agentic-ai/mcp/overview/
      status: verified
    slug: new-relic
    status: profiled
    tags: &id014
    - APM
    - Analysis
    - Analytics
    - DevOps
    url: /providers/new-relic/
  layer: common
  name: New Relic
  provider: new-relic
  says: ships the New Relic SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.cvs.launchers.cvs/latest/
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
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id015
      status: unchecked
    slug: tapstream
    status: queued for profiling
    tags: &id016 []
    url: null
  layer: common
  name: Tapstream
  provider: tapstream
  says: ships the Tapstream SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.cvs.launchers.cvs/latest/
  tier: observed
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/pharmacy-prescriptions/cvs-health/
providers:
- agent_band: agent-ready
  agent_readiness: 53.0
  band: strong
  in_catalog: true
  kin_score: 65.1
  mcp: *id001
  name: Adobe Experience Cloud
  slug: adobe-experience-cloud
  status: profiled
  tags: *id002
  url: /providers/adobe-experience-cloud/
- agent_band: agent-ready
  agent_readiness: 32.5
  band: exemplar
  in_catalog: true
  kin_score: 67.4
  mcp: *id003
  name: Bazaarvoice
  slug: bazaarvoice
  status: profiled
  tags: *id004
  url: /providers/bazaarvoice/
- agent_band: agent-aware
  agent_readiness: 21.9
  band: thin
  in_catalog: true
  kin_score: 33.8
  mcp: *id005
  name: Branch
  slug: branch-io
  status: profiled
  tags: *id006
  url: /providers/branch-io/
- agent_band: agent-ready
  agent_readiness: 58.4
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id007
  name: Braze
  slug: braze
  status: profiled
  tags: *id008
  url: /providers/braze/
- agent_band: agent-ready
  agent_readiness: 39.9
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id009
  name: Firebase
  slug: google-firebase
  status: profiled
  tags: *id010
  url: /providers/google-firebase/
- agent_band: agent-ready
  agent_readiness: 35.3
  band: strong
  in_catalog: true
  kin_score: 65.2
  mcp: *id011
  name: Google AdMob
  slug: google-admob
  status: profiled
  tags: *id012
  url: /providers/google-admob/
- agent_band: agent-ready
  agent_readiness: 44.8
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id013
  name: New Relic
  slug: new-relic
  status: profiled
  tags: *id014
  url: /providers/new-relic/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id015
  name: Tapstream
  slug: tapstream
  status: queued for profiling
  tags: *id016
  url: null
siblings:
- name: GoodRx
  rows: 8
  url: /applications/pharmacy-prescriptions/goodrx/
- name: Medisafe
  rows: 9
  url: /applications/pharmacy-prescriptions/medisafe/
- name: Medplum
  rows: 11
  url: /applications/pharmacy-prescriptions/medplum/
- name: OpenEMR
  rows: 11
  url: /applications/pharmacy-prescriptions/openemr/
- name: Walgreens
  rows: 8
  url: /applications/pharmacy-prescriptions/walgreens/
sitemap: true
title: 'CVS Health: Pharmacy & Prescriptions reference app'
---
