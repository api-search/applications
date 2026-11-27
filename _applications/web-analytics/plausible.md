---
app: Plausible
app_slug: plausible
app_url: https://github.com/plausible/analytics
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-610.50
  key: analytics-bi-management
  layer: domain
  name: Analytics & BI Management
  providers:
  - Looker Studio (Data Studio)
  url: /capabilities/analytics-bi-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.70
  key: AE-170.70
  layer: domain
  name: Content Management
  providers:
  - Ghost
  - Squarespace
  - Webflow
  - Wix
  - WordPress
  url: /capabilities/content-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-3770.30
  key: content-performance-analytics
  layer: domain
  name: Content Performance Analytics
  providers:
  - Google Search Console
  url: /capabilities/content-performance-analytics/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-140.10.10
  key: AE-140.10.10
  layer: domain
  name: Hosted Storefronts
  providers:
  - Shopify
  url: /capabilities/storefront-platforms/
  via_parent: Storefront Platforms
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: domain
  name: Product Usage Analytics
  providers:
  - Google Analytics
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-911
  key: AE-911
  layer: domain
  name: Tag Management
  providers:
  - Google Tag Manager
  url: /capabilities/product-telemetry-instrumentation/
  via_parent: Product Telemetry Instrumentation
- attribution: Turbo EA
  id: BC-3710.30
  key: asset-storage-tiering
  layer: common
  name: Asset Storage & Tiering
  providers:
  - Amazon S3
  url: /capabilities/asset-storage-tiering/
  via_parent: null
- attribution: Turbo EA
  id: BC-420
  key: customer-relationship-management
  layer: common
  name: Customer Relationship Management
  providers:
  - HubSpot
  url: /capabilities/customer-relationship-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-430
  key: customer-service-management
  layer: common
  name: Customer Service Management
  providers:
  - Help Scout
  url: /capabilities/customer-service-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Sentry
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4250
  key: subscription-billing-revenue-management
  layer: common
  name: Subscription Billing & Revenue Management
  providers:
  - Paddle
  url: /capabilities/subscription-billing-revenue-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.10.10
  key: AE-150.10.10
  layer: common
  name: Transactional Email
  providers:
  - Postmark
  url: /capabilities/email/
  via_parent: Email
category:
  id: web-analytics
  name: Web & Product Analytics
  url: /applications/web-analytics/
counts:
  declared: 9
  observed: 7
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/plausible/analytics/master/mix.exs
- route: documentation
  url: https://plausible.io/docs/google-search-console-integration
- route: documentation
  url: https://plausible.io/docs/integration-guides
- route: source code
  url: https://github.com/plausible/analytics/blob/master/extra/lib/plausible/help_scout.ex
- route: source code
  url: https://github.com/plausible/analytics/tree/master/lib/plausible
integrations:
- capability:
    attribution: Turbo EA
    id: BC-3710.30
    key: asset-storage-tiering
    name: Asset Storage & Tiering
    url: /capabilities/asset-storage-tiering/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 34.8
    band: exemplar
    in_catalog: true
    kin_score: 76.6
    mcp: &id001
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-s3
    status: profiled
    tags: &id002
    - Amazon Web Services
    - Archives
    - Backup
    - Cloud Storage
    url: /providers/amazon-s3/
  layer: common
  name: Amazon S3
  provider: amazon-s3
  says: ships the Amazon S3 SDK or integration code
  source: https://raw.githubusercontent.com/plausible/analytics/master/mix.exs
  tier: observed
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
  layer: domain
  name: Google Analytics
  provider: google-analytics
  says: ships the Google Analytics SDK or integration code
  source: https://github.com/plausible/analytics/tree/master/lib/plausible
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-3770.30
    key: content-performance-analytics
    name: Content Performance Analytics
    url: /capabilities/content-performance-analytics/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 30.7
    band: exemplar
    in_catalog: true
    kin_score: 69.7
    mcp: &id007
      status: none
    slug: google-search-console
    status: profiled
    tags: &id008
    - Analytics
    - Google
    - Indexing
    - Search
    url: /providers/google-search-console/
  layer: domain
  name: Google Search Console
  provider: google-search-console
  says: ships the Google Search Console SDK or integration code
  source: https://github.com/plausible/analytics/tree/master/lib/plausible
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-430
    key: customer-service-management
    name: Customer Service Management
    url: /capabilities/customer-service-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.8
    band: developing
    in_catalog: true
    kin_score: 51.5
    mcp: &id011
      status: none
    slug: helpscout
    status: profiled
    tags: &id012
    - Customer Service
    - Email
    - Help Desk
    - Live Chat
    url: /providers/helpscout/
  layer: common
  name: Help Scout
  provider: helpscout
  says: ships the Help Scout SDK or integration code
  source: https://github.com/plausible/analytics/blob/master/extra/lib/plausible/help_scout.ex
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4250
    key: subscription-billing-revenue-management
    name: Subscription Billing & Revenue Management
    url: /capabilities/subscription-billing-revenue-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 46.9
    band: thin
    in_catalog: true
    kin_score: 28.6
    mcp: &id017
      source: https://github.com/PaddleHQ/paddle-mcp-server
      status: verified
    slug: paddle
    status: profiled
    tags: &id018
    - Billing
    - Merchant of Record
    - Payments
    - Subscription
    url: /providers/paddle/
  layer: common
  name: Paddle
  provider: paddle
  says: ships the Paddle SDK or integration code
  source: https://github.com/plausible/analytics/tree/master/lib/plausible
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.10
    key: AE-150.10.10
    name: Transactional Email
    url: /capabilities/email/
    via_parent: Email
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 43.0
    band: exemplar
    in_catalog: true
    kin_score: 70.5
    mcp: &id019
      source: https://github.com/ActiveCampaign/postmark-mcp
      status: verified
    slug: postmark
    status: profiled
    tags: &id020
    - Deliverability
    - Email
    - Messaging
    - Transactional Email
    url: /providers/postmark/
  layer: common
  name: Postmark
  provider: postmark
  says: ships the Postmark SDK or integration code
  source: https://raw.githubusercontent.com/plausible/analytics/master/mix.exs
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 50.2
    band: exemplar
    in_catalog: true
    kin_score: 80.7
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
  source: https://raw.githubusercontent.com/plausible/analytics/master/mix.exs
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.70
    key: AE-170.70
    name: Content Management
    url: /capabilities/content-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 34.8
    band: exemplar
    in_catalog: true
    kin_score: 79.0
    mcp: &id003
      status: none
    slug: ghost-org
    status: profiled
    tags: &id004
    - Membership
    - Newsletters
    - Publishing
    - Subscription
    url: /providers/ghost-org/
  layer: domain
  name: Ghost
  provider: ghost-org
  says: lists Ghost as an integration
  source: https://plausible.io/docs/integration-guides
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-911
    key: AE-911
    name: Tag Management
    url: /capabilities/product-telemetry-instrumentation/
    via_parent: Product Telemetry Instrumentation
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 35.8
    band: strong
    in_catalog: true
    kin_score: 65.8
    mcp: &id009
      status: none
    slug: google-tag-manager
    status: profiled
    tags: &id010
    - Analytics
    - Conversion Tracking
    - Marketing
    - Tag Management
    url: /providers/google-tag-manager/
  layer: domain
  name: Google Tag Manager
  provider: google-tag-manager
  says: lists Google Tag Manager as an integration
  source: https://plausible.io/docs/integration-guides
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
    mcp: &id013
      source: https://developers.hubspot.com/mcp
      status: verified
    slug: hubspot
    status: profiled
    tags: &id014
    - Analytics
    - CRM
    - Commerce
    - Content
    url: /providers/hubspot/
  layer: common
  name: HubSpot
  provider: hubspot
  says: lists HubSpot as an integration
  source: https://plausible.io/docs/integration-guides
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-610.50
    key: analytics-bi-management
    name: Analytics & BI Management
    url: /capabilities/analytics-bi-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 34.0
    band: strong
    in_catalog: true
    kin_score: 58.5
    mcp: &id015
      status: none
    slug: looker-studio
    status: profiled
    tags: &id016
    - Analytics
    - Business Intelligence
    - Dashboards
    - Data Visualization
    url: /providers/looker-studio/
  layer: domain
  name: Looker Studio (Data Studio)
  provider: looker-studio
  says: lists Looker Studio (Data Studio) as an integration
  source: https://plausible.io/docs/integration-guides
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.10.10
    key: AE-140.10.10
    name: Hosted Storefronts
    url: /capabilities/storefront-platforms/
    via_parent: Storefront Platforms
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 51.8
    band: exemplar
    in_catalog: true
    kin_score: 83.8
    mcp: &id023
      source: https://shopify.dev/docs/apps/build/devmcp
      status: verified
    slug: shopify
    status: profiled
    tags: &id024
    - Commerce
    - E-Commerce
    - Payments
    - Retail
    url: /providers/shopify/
  layer: domain
  name: Shopify
  provider: shopify
  says: lists Shopify as an integration
  source: https://plausible.io/docs/integration-guides
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.70
    key: AE-170.70
    name: Content Management
    url: /capabilities/content-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 48.5
    band: exemplar
    in_catalog: true
    kin_score: 68.7
    mcp: &id025
      status: none
    slug: squarespace
    status: profiled
    tags: &id026
    - Commerce
    - E-Commerce
    - Marketing
    - Payments
    url: /providers/squarespace/
  layer: domain
  name: Squarespace
  provider: squarespace
  says: lists Squarespace as an integration
  source: https://plausible.io/docs/integration-guides
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.70
    key: AE-170.70
    name: Content Management
    url: /capabilities/content-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 62.5
    band: strong
    in_catalog: true
    kin_score: 60.5
    mcp: &id027
      source: https://developers.webflow.com/mcp/reference/overview
      status: verified
    slug: webflow
    status: profiled
    tags: &id028
    - CMS
    - E-Commerce
    - No-Code
    - Web Development
    url: /providers/webflow/
  layer: domain
  name: Webflow
  provider: webflow
  says: lists Webflow as an integration
  source: https://plausible.io/docs/integration-guides
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.70
    key: AE-170.70
    name: Content Management
    url: /capabilities/content-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 47.2
    band: thin
    in_catalog: true
    kin_score: 35.5
    mcp: &id029
      source: https://dev.wix.com/docs/sdk/articles/use-the-wix-mcp/about-the-wix-mcp
      status: verified
    slug: wix
    status: profiled
    tags: &id030
    - CMS
    - E-Commerce
    - Headless
    - Website Builder
    url: /providers/wix/
  layer: domain
  name: Wix
  provider: wix
  says: lists Wix as an integration
  source: https://plausible.io/docs/integration-guides
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.70
    key: AE-170.70
    name: Content Management
    url: /capabilities/content-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.9
    band: developing
    in_catalog: true
    kin_score: 46.6
    mcp: &id031
      source: https://github.com/WordPress/mcp-adapter
      status: verified
    slug: wordpress
    status: profiled
    tags: &id032
    - CMS
    - Content Management
    - Open Source
    - WordPress
    url: /providers/wordpress/
  layer: domain
  name: WordPress
  provider: wordpress
  says: lists WordPress as an integration
  source: https://plausible.io/docs/integration-guides
  tier: declared
kind: open-source-saas
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/web-analytics/plausible/
providers:
- agent_band: agent-ready
  agent_readiness: 34.8
  band: exemplar
  in_catalog: true
  kin_score: 76.6
  mcp: *id001
  name: Amazon S3
  slug: amazon-s3
  status: profiled
  tags: *id002
  url: /providers/amazon-s3/
- agent_band: agent-ready
  agent_readiness: 34.8
  band: exemplar
  in_catalog: true
  kin_score: 79.0
  mcp: *id003
  name: Ghost
  slug: ghost-org
  status: profiled
  tags: *id004
  url: /providers/ghost-org/
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
  agent_readiness: 30.7
  band: exemplar
  in_catalog: true
  kin_score: 69.7
  mcp: *id007
  name: Google Search Console
  slug: google-search-console
  status: profiled
  tags: *id008
  url: /providers/google-search-console/
- agent_band: agent-ready
  agent_readiness: 35.8
  band: strong
  in_catalog: true
  kin_score: 65.8
  mcp: *id009
  name: Google Tag Manager
  slug: google-tag-manager
  status: profiled
  tags: *id010
  url: /providers/google-tag-manager/
- agent_band: agent-aware
  agent_readiness: 24.8
  band: developing
  in_catalog: true
  kin_score: 51.5
  mcp: *id011
  name: Help Scout
  slug: helpscout
  status: profiled
  tags: *id012
  url: /providers/helpscout/
- agent_band: agent-ready
  agent_readiness: 52.0
  band: exemplar
  in_catalog: true
  kin_score: 91.9
  mcp: *id013
  name: HubSpot
  slug: hubspot
  status: profiled
  tags: *id014
  url: /providers/hubspot/
- agent_band: agent-ready
  agent_readiness: 34.0
  band: strong
  in_catalog: true
  kin_score: 58.5
  mcp: *id015
  name: Looker Studio (Data Studio)
  slug: looker-studio
  status: profiled
  tags: *id016
  url: /providers/looker-studio/
- agent_band: agent-ready
  agent_readiness: 46.9
  band: thin
  in_catalog: true
  kin_score: 28.6
  mcp: *id017
  name: Paddle
  slug: paddle
  status: profiled
  tags: *id018
  url: /providers/paddle/
- agent_band: agent-ready
  agent_readiness: 43.0
  band: exemplar
  in_catalog: true
  kin_score: 70.5
  mcp: *id019
  name: Postmark
  slug: postmark
  status: profiled
  tags: *id020
  url: /providers/postmark/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.7
  mcp: *id021
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id022
  url: /providers/sentry-system/
- agent_band: agent-ready
  agent_readiness: 51.8
  band: exemplar
  in_catalog: true
  kin_score: 83.8
  mcp: *id023
  name: Shopify
  slug: shopify
  status: profiled
  tags: *id024
  url: /providers/shopify/
- agent_band: agent-native
  agent_readiness: 48.5
  band: exemplar
  in_catalog: true
  kin_score: 68.7
  mcp: *id025
  name: Squarespace
  slug: squarespace
  status: profiled
  tags: *id026
  url: /providers/squarespace/
- agent_band: agent-ready
  agent_readiness: 62.5
  band: strong
  in_catalog: true
  kin_score: 60.5
  mcp: *id027
  name: Webflow
  slug: webflow
  status: profiled
  tags: *id028
  url: /providers/webflow/
- agent_band: agent-ready
  agent_readiness: 47.2
  band: thin
  in_catalog: true
  kin_score: 35.5
  mcp: *id029
  name: Wix
  slug: wix
  status: profiled
  tags: *id030
  url: /providers/wix/
- agent_band: agent-ready
  agent_readiness: 31.9
  band: developing
  in_catalog: true
  kin_score: 46.6
  mcp: *id031
  name: WordPress
  slug: wordpress
  status: profiled
  tags: *id032
  url: /providers/wordpress/
siblings:
- name: Amplitude
  rows: 50
  url: /applications/web-analytics/amplitude/
- name: Google Analytics
  rows: 4
  url: /applications/web-analytics/google-analytics/
- name: Matomo
  rows: 18
  url: /applications/web-analytics/matomo/
- name: Mixpanel
  rows: 12
  url: /applications/web-analytics/mixpanel/
- name: PostHog
  rows: 42
  url: /applications/web-analytics/posthog/
- name: Umami
  rows: 4
  url: /applications/web-analytics/umami/
sitemap: true
title: 'Plausible: Web & Product Analytics reference app'
---
